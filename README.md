[TOC]

### Controllable Video Generation

- Unet
  1. [control-a-video](papers/Control-A-Video.pdf) [May 2023] (Noise warping + ControlNet)
  2. [Motion-I2V](papers/Motion-I2V.pdf) [Jan 2024] (Flow-based method + AnimateDiff)
  2. [DragAnything](papers/DragAnything.pdf) [Mar 2024] (Trajectory control for entity)
  3. [MOFA-Video](papers/MOFA-Video.pdf) [July 2024] (Flow-based method + SVD)
  3. [AnchorCrafter](papers/AnchorCrafter.pdf) [Nov 2024] (直播卖货: humanPose+HandMesh+ObjectDepth)
  3. [AniDoc](papers/AniDoc Animation Creation Made Easier.pdf) [Jan 2025]  (Sketch+Corresponding guidance)
  3. [VidCRAFT3](papers/VidCRAFT3.pdf) [Feb 2025] (Camera, Object, and Lighting Control)
  3. [Generative Inbetweening](papers/Generative Inbetweening through Frame-wise Conditions-Driven Video Generation.pdf) [Dec 2024] (line matching+插值模型)
  3. [Perception-as-Control](papers/Perception-as-Control.pdf) [Mar 2025] (Trajectory control)
  3. [X-Dyna](papers/X-Dyna.pdf) [Jan 2025] (dynamic dance generation)
  3. [Trajactory attention](papers/trajactory attention.pdf) [Nov 2024] (trajactory guided attention)
  3. [LeviTor](papers/LeviTor.pdf) [Mar 2025] (3D Trajectory)
  3. [Extrapolating and Decoupling Image-to-Video Generation Models](papers/Extrapolating and Decoupling Image-to-Video Generation Models.pdf) [Mar 2025] (Interpolating model)
  3. [Dynamic Mask Guidance](papers/Resource-Efficient Motion Control.pdf) [Mar 2025]
- DIT

  1. [Diffusion as Shader](papers/Diffusion as Shader.pdf) [Jan 2025]
  2. [Go-with-the-Flow](papers/Go-with-the-Flow.pdf) [Jan 2025] (initialize noise as control condition)
  3. [CatV2TON](papers/CatV2TON.pdf)[Jan 2025] (virtual tryon-task,  AdaCN for color error accumulation)
  4. [CineMaster](papers/CineMaster.pdf) [Feb 2025] (3d Bounding Boxes)
  5. [3DTrajMaster](papers/3DTRAJMASTER.pdf) [Feb 2025] (Multiple Entity 3d Trajectory)
  6. [MotionBridge](papers/MotionBridge.pdf) [Jan 2025] (Trajectory + 插值模型)
  7. [MotionCanvas](papers/MotionCanvas.pdf) [Feb 2025] (Trajectory+Box+Camera)
  8. [Video Motion Transfer](papers/Video Motion Transfer with Diffusion Transformers.pdf) [Dec 2024]
  8. [FullDiT](papers/FullDiT.pdf) [Mar 2025]
  8. [Tora](papers/Tora.pdf) [Oct 2024] (Trajectory control)

### Video Inpainting

1. [Get In Video](papers/Get In Video Add Anything You Want to the Video.pdf) [Mar 2025] 构建数据集 + DiT (条件跟noise直接concate)
2. [DiffuEraser](papers/DiffuEraser.pdf) [Jan 2025] 专注移除任务
2. [DynVFX](papers/DynVFX.pdf) [Feb 2025] (Adding Dynamic Object)
2. [VideoPainter](papers/VideoPainter.pdf) [Mar 2025]

### Video Editing

1. [VIDEOGRAIN](papers/VIDEOGRAIN.pdf) [Feb 2025]
1. [Taming Rectified Flow for Inversion and Editing](papers/Taming Rectified Flow for Inversion and Editing.pdf) [Nov 2024] (Editing for Rectified Flow-based model) <span style="color:red">!</span>
1. [VideoHandles](papers/VideoHandles.pdf) [Editing object composition]
1. [V2Edit](papers/V2Edit.pdf) [Mar 2025] <span style="color:red">!!!</span>

### Long Video Generation

1. [Anim-Director](papers/Anim-Director.pdf) [Aug 2024] (MLLM+VDM, training-free)

1. [SEED-STORY](papers/SEED-STORY.pdf) [Oct 2024] (image as token in MLLM)

1. [Long Context Tuning for Video Generation](papers/Long Context Tuning for Video Generation.pdf) [Mar 2025]

   asynchronous noise strategy -> apply causal attention + KV-cache to enhance the efficiency

2. [FBSDiff](papers/FBSDiff.pdf) [Aug 2024] (low frequency from global attn + high frequency from local attn)

5. [Ouroboros-Diffusion](papers/Ouroboros-Diffusion.pdf) [Jan 2025] (Better Latent + Feature Bank)

6. [VideoAuteur](papers/VideoAuteur.pdf) [Jan 2025] (Seed Story for the visual embedding)

3. [LongDiff](papers/LongDiff.pdf) [Mar 2025] <span style="color:red">!!!</span>

### Customized Video Generation

- Training-based
  1. [SUGAR](papers/SUGAR.pdf) [Dec 2024]
  2. [Multi-subject Open-set Personalization](papers/Multi-subject Open-set Personalization in Video Generation.pdf) [Jan 2025]
  3. [CustomVideoX](papers/CustomVideoX.pdf) [Feb 2025]
  4. [PHANTOM](papers/PHANTOM.pdf) [Feb 2025] (不开源)
  4. [Movie Weaver](papers/Movie Weaver.pdf) [Feb 2025]
- Optimized-based
  1. [Dynamic Concepts Personalization](papers/Dynamic Concepts Personalization from Single Videos.pdf) [Feb 2025] (focus on dynamic content)
- Face
  1. [Ingredients](papers/Ingredients.pdf) [Jan 2025]
  2. [MagicMirror](papers/Magic Mirror.pdf) [Jan 2025] 
  3. [FantasyID](papers/FantasyID Face Knowledge Enhanced ID-Preserving Video Generation.pdf) [Feb 2025] (3D feature)
  4. [Identity-Preserving Text-to-Video](papers/Identity-Preserving Text-to-Video Generation by Frequency Decomposition.pdf) (Open source)

### Leverage LLM/MLLM

- Image
  1. [Generative Multimodal Models are In-Context Learners](papers/Generative Multimodal Models are In-Context Learners.pdf) [May 2024] (Image as vision tokens)
  2. [BrushEdit](papers/BrushEdit.pdf) [Dec 2024] (similar to our SGEdit work, but with inpainting model)
  3. [EasyRef](papers/EasyRef.pdf) [Dec 2024] (LLM-style IP-adapter)
  4. [Enabling Multimodal In-Context Reasoning](papers/Enabling Multimodal In-Context Reasoning in Diffusion Models.pdf) [Feb 2025] (In-Context, Aligner connect diffusion&VLM)
  4. [DreamEngine](papers/DreamEngine.pdf) [Feb 2025] <span style="color:red">!!!</span>
- Video
  1. [CINEMA](papers/CINEMA Coherent Multi-Subject Video Generation via MLLM-Based Guidance.pdf) [Mar 2025]
  2. [Mimir](papers/Mimir.pdf) [Dec 2024] (Improve text alignment by LLM text feature)

### 4D Video

1. [Reangle-A-Video](papers/Reangle-A-Video.pdf) [Mar 2025] (Synchronized multi-view videos)
2. [GS-DiT](papers/GS-DiT.pdf) [Jan 2025]

### Autoregressive Video

1. [RAIN](papers/RAIN.pdf) [Dec 2024]
2. [StreamingT2V](papers/StreamingT2V.pdf) [Mar 2024]
2. [Taming Teacher Forcing for Masked Autoregressive Video Generation](papers/Taming Teacher Forcing for Masked Autoregressive Video Generation.pdf) [Jan 2025]<span style="color:red">!!!</span>
2. [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](papers/From Slow Bidirectional to Fast Autoregressive Video Diffusion Models.pdf) [Jan 2025]<span style="color:red">!!!</span>

### Multi-instance Generation

- Image
  1. [3DIS-FLUX](papers/3DIS-FLUX.pdf) [Jan 2025] (layout -> depthmap -> image)
  2. dd
- Video
  1. [BlobGEN-Vid](papers/BlobGEN-Vid.pdf) [Jan 025]

### Image Generation

- Controllable
  1. [OminiControl](papers/OminiControl.pdf) [Nov 2024]
  2. [EasyControl](papers/EasyControl.pdf) [Mar 2025]
  3. [UniCombine](papers/UniCombine.pdf) [Mar 2025]
- Text alignment
  1. [Aligning Text to Image in Diffusion Models is Easier Than You Think](papers/Aligning Text to Image in Diffusion Models is Easier Than You Think.pdf) [Mar 2025]
- Big Unified Model
  1. [OmniGen](papers/OmniGen.pdf) [Sep 2024]
  2. [UniReal](papers/UniReal.pdf) [Dec 2024]
  3. [X-Prompt](papers/X-Prompt.pdf) [Dec 2024] <span style="color:red">!!!</span>
  4. [ACE++](papers/ACE++.pdf) [Jan 2025]
- Text rendering
  1. [TextCrafter](papers/TextCrafter.pdf) [Apr 2025]
- Distill
  1. [Distilling Diversity and Control in Diffusion Models](papers/Distilling Diversity and Control in Diffusion Models.pdf) [Mar 2025] <span style="color:red">!!!</span>

### Image Editing

- I2I translation

  1. [ReNoise](papers/ReNoise.pdf) [Mar 2024] (Better inversion for few-steps diffusion)
  2. [FlowEdit](papers/FlowEdit.pdf) [Dec 2024] (ODE path directly maps the source distribution to the target distribution)
  3. [FireFlow](papers/FireFlow.pdf) [Dec 2024] (Fast Inversion of Rectified Flow)
  4. [SwiftEdit](papers/SwiftEdit.pdf) [Dec 2024] (Predict the initial noise directly)
  6. [TurboEdit](papers/TurboEdit.pdf) [Aug 2024] (Apply for few-step diffusion models)
  6. [Stable Flow](papers/Stable Flow.pdf) [Nov 2024] (PnP on DiT)
  6. [KV-Edit](papers/KV-Edit.pdf) [Feb 2025] (Modified PnP on DiT)
  6. [PhotoDoodle](papers/PhotoDoodle.pdf) [Feb 2025] (Few shot style transfer)
  6. [DCEdit](papers/DCEdit.pdf)
- Specific object manipulation/inpainting
  1. [DiffUHaul](papers/DiffUHaul.pdf) [Sep 2024]
  2. [DreamMix](papers/DreamMix Decoupling Object Attributes for Enhanced Editability in Customized Image Inpainting.pdf) [Nov 2024]
  2. [ObjectMate](papers/ObjectMate.pdf) [Dec 2024]
  2. [Affordance-Aware Object Insertion](papers/Affordance-Aware Object Insertion via Mask-Aware Dual Diffusion.pdf) [Dec 2024]
  2. [ObjectMover](papers/ObjectMover.pdf) [Mar 2025]
  6. [Personalize Anything](papers/Personalize Anything for Free with Diffusion Transformer.pdf) [Mar 2025]
  6. [OmniPaint](papers/OmniPaint.pdf) [Mar 2025]
- Leverage video diffusion
  1. [Pathways on the Image Manifold](papers/Pathways on the Image Manifold.pdf) [Nov 2024]
  1. [FramePainter](papers/FramePainter.pdf) [Jan 2025]
- In-context learning
  1. [Edit Transfer](papers/Edit Transfer.pdf) [Mar 2025]  <span style="color:red">!!!</span>
  2. [ImageRAG](papers/ImageRAG.pdf) [Feb 2025] (Image In-Context Learning)

### Image Customization

1. [AnyStory](papers/AnyStory.pdf) [Jan 2025] (Multiple Subject, Router)
2. [Nested Attention](papers/Nested Attention.pdf) [Jan 2025] (Multiple concepts, utilize cross-attention)
2. [Conceptrol](papers/Conceptrol.pdf) [Mar 2025] (IP-adapter fashion)  <span style="color:red">!!!</span>
2. [latexblend](papers/latexblend.pdf) [Mar 2025]
2. [Visual Persona](papers/Visual Persona.pdf) [Mar 2025]

### Story Generation

1. [One-prompt-one-story](papers/ONE-PROMPT-ONE-STORY.pdf) [Feb 2025]
2. [Story-adapter](papers/STORY-ADAPTER.pdf) [Oct 2024]
2. [DiffSensei](papers/DiffSensei.pdf) [Dec 2024] (漫画生成)

### Stylization

1. [Art-Free](papers/Art-Free Generative Models Art Creation Without Graphic Art Knowledge.pdf) [Nov 2024]
1. [K-LoRA](papers/K-LoRA.pdf) [Mar 2025]

### Speed Up

- Improve Efficiency

  1. [Fast Video Generation](papers/Fast Video Generation.pdf) [Feb 2025]

  1. [FlexiDiT](papers/FlexiDiT.pdf) [Feb 2025]

- One step models

  1. [Diffusion Adversarial Post-Training](papers/Diffusion Adversarial Post-Training for One-Step Video Generation.pdf) [2025] (video)
  1. [One-Step Image Translation with Text-to-Image Models](papers/One-Step Image Translation with Text-to-Image Models.pdf) [Mar 2024]


### Initial Noise Manipulation

1. [A Noise is Worth Diffusion Guidance](papers/A Noise is Worth Diffusion Guidance.pdf) (replace classifier-free guidance by predicted initial noise)
1. [Enhancing compositional T2I with random seed](papers/ENHANCING COMPOSITIONAL TEXT-TO-IMAGE GEN- ERATION WITH RELIABLE RANDOM SEEDS.pdf) (obtain better noise for better composition)
1. [Golden Noise for Diffusion Models](papers/Golden Noise.pdf) (predict high quality noise)
1. [One More Step](papers/One More Step.pdf) (mitigate brightness issuses)
1. [The Silent Prompt](papers/The Silent Prompt.pdf) (search the better initial noise)

### Diffusion Basic

1. [Flow Matching](papers/FLOW MATCHING.pdf) [Feb 2023]

### Base Model / Dataset

- video(model)
  1. [CogVideoX](papers/CogVideoX.pdf) [Aug 2024] <span style="color:red">***</span>
  2. [LTX-Video](papers/LTX-Video.pdf) [Dec 2024] <span style="color:red">**</span>
  2. [Lumina-Video](papers/Lumina-Video.pdf) [Feb 2025]
  2. [FlashVideo](papers/FlashVideo.pdf) [Feb 2025] (2 stages + flow matching)
  2. [Step-Video-T2V](papers/Step-Video-T2V.pdf) [Feb 2025]
  2. [WAN](papers/WAN.pdf) [Mar 2025]
- video(dataset)
  1. [OPENVID-1M](papers/OPENVID-1M.pdf) [Feb 2025]
  1. [Señorita-2M](papers/Señorita-2M.pdf) [Mar 2025] (Video Editing dataset)

### New Architecture

1. [Diffusion Forcing](papers/Diffusion Forcing.pdf) [Dec 2024]<span style="color:red">!!!</span>
2. [Diffusion Noise Condition](papers/Is Noise Conditioning Necessary for Denoising Generative Models.pdf) [Feb 2025]
2. [Block Diffusion](papers/BLOCK DIFFUSION.pdf) [Mar 2025]
2. [Pyramidal Flow Matching](papers/PYRAMIDAL FLOW MATCHING FOR EFFICIENT VIDEO GENERATIVE MODELING.pdf) [Mar 2025]
2. [Unified Multimodal Discrete Diffusion ](papers/Unified Multimodal Discrete Diffusion.pdf)[Mar 2025]
2. [Learning Visual Generative Priors without Text](papers/Learning Visual Generative Priors without Text.pdf) [Mar 2025]

### Reward

1. [Diffusion-Sharpening](papers/Diffusion-Sharpening.pdf)<span style="color:red">!</span>
2. [Diffusion Model Alignment](papers/Diffusion Model Alignment.pdf) (让模型在胜者图像上比参考模型更会去噪，而在败者图像上故意不如参考模型)

### COT and TTS (test-time scaling)<span style="color:red">!!!</span>

1. [ImageGen-CoT](papers/ImageGen-CoT.pdf) [Mar 2025]

2. [GoT](papers/GoT.pdf) [Mar 2025]
3. [Video-T1](papers/Video-T1.pdf) [Apr 2025]

### Talking Face

1. [mocha](papers/mocha.pdf)  [Mar 2025]

### Image-to-3D Scene Generation

1. [PanoDreamer](papers/PanoDreamer.pdf) [Mar 2025]

### 3D Scene Generation

1. [NuiScene](papers/NuiScene.pdf)  [Mar 2025]
1. dd

### Video-driven 3D

1. [Animating the Uncaptured](papers/Animating the Uncaptured.pdf) [Mar 2025]

### CV

1. [CleanDIFT](papers/CleanDIFT.pdf) [Dec 2024] (clean diffusion features -> improve downstream tasks: e.g. segment...) <span style="color:red">!</span>
2. [FreestyleRet](papers/FreestyleRet.pdf) [Dec 2023] (image retrieval)
3. [Generalizable Origin Identification](papers/Generalizable Origin Identification.pdf) (Origin Identification.pdf)

### Other

1. [InstantFamily](papers/InstantFamily.pdf) [Apr 2024] (Multi-Face composition)
2. [IP-Composer](papers/IP-Composer.pdf) [Feb 2025] (Semantic Composition of Visual Concepts)
3. [KV Cache](papers/KV Cache.pdf) [Feb 2025] (Analyse KV Cache)
4. [LayerTracer](papers/LayerTracer.pdf) [Feb 2025] / [MakeAnything](papers/MakeAnything.pdf) ] [Feb 2025] (Generate Procedural)
5. [Light-A-Video](papers/Light-A-Video.pdf) [Feb 2025] (Video Relighting)
6. [OmniFlow](papers/OmniFlow.pdf) [Dec 2024] (Any-to-Any Generation)
7. [Orient Anything](papers/Orient Anything.pdf) [Dec 2024] (Predict Orientation)
8. [SeedVR](papers/SeedVR.pdf) [Feb 2025] (Image Super-resolution)
9. [Star](papers/Stable Flow.pdf) [Jan 2025] (Video Super-resolution)
10. [Spotlight](papers/SPOTLIGHT.pdf) [Nov 2024] (Shadow-Guided Object Relighting)
11. [SVDiff](papers/SVDiff Compact Parameter Space for Diffusion Fine-Tuning.pdf) [Jul 2023] (Singular Value Decomposition)
12. [TransPixeler](papers/TransPixeler.pdf) [Jan 2025] (Transparent Video Generation)
13. [VideoPoet](papers/VideoPoet.pdf) [Jun 2024] (LLM for Video Generation)
14. [Visual Anagrams](papers/Visual Anagrams.pdf) [Apr 2024] (Illusion Image Generation)
15. [DesignDiffusion](papers/DesignDiffusion.pdf) [Mar 2025] (Diffusion for Design)
16. [Generative Photomontage](papers/Generative Photomontage.pdf) [Aug 2024] (多图融合)
17. [MatAnyone](papers/MatAnyone.pdf) [Jan 2025] (Video Matting)
18. [spatracker](papers/spatracker.pdf) [Apr 2024] (3D point tracking)
19. [3D Scene Flow](papers/3D Scene Flow.pdf) [2020] (3D optical flow)
20. [KV Cache Quantization](papers/Plug-and-Play 1.x-Bit KV Cache Quantization.pdf) [Mar 2025] (VLLM quantization)
21. [SpatialTracker](papers/SpatialTracker.pdf) [Apr 2024] (3D point tracking)
