birection diffusion model -> causual diffusion model -> poor results (causvid)

## Diffusion Forcing

- Motivation

  1. autoregressive -> accumulate error quickly

  1. bidirection -> hard to generate video of variable length

- Method: independent noise level for each frame

## Causual Video

- Motivation:  high quality and low latency
- Intuition: Casual DIT as teacher, but performance inferior -> : Asymmetric Distillation
- Method: 
  1. Student Initialization (similar to diffusion forcing)
  2. Asymmetric Distillation with DMD (further reduce timestep)

## Self Forcing

- Motivation: Train-Inference Gap
  1. Teacher Forcing: Clean image as condition -> exposure bias
  2. Diffusion Forcing: Noisy image as condition-> exposure bias
  3. Self Forcing: Predicted Frame as condition
- Method
  1. Train a few step diffusion model
  2. In training, first generate clean history frames and append clean frames to KV cache as condition
  3. In inference, rolling KV cache for reduced time complexity

## AAPT

- Autoregressive model
- Concate the generate frame channelwise as condition

## DFoT

- no text condition, explore history frames CFG

## Self-forcing++

- Motivation: Temporal misalignment. The training phase only learns to generate short videos of about 5 seconds, while the inference phase needs to generate long videos of several minutes;
- Method
  1. Rolling Window distillation (this is my name)
     1. Backwards Noise Initialization
     2. Extended Distribution Matching Distillation
  2. GRPO

## Long Live

- Motivation: 1. longer video 2. able to change prompt
- Method:
  1. KV recache (for change prompt, just clear previous memory)
  2. stream long tuning (simlar to Rolling Window distillation)
  3. efficient long inference (short-window and frame sink: seems to be common strategy) 

## Pusa

- Motivation: Low cost to adjust T2V model to I2V, Interpolation, Extrapolation and so on
- Method: vectorized timestep adaptation
