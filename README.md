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
  3. [Extrapolating and Decoupling Image-to-Video Generation Models](papers/Extrapolating and Decoupling Image-to-Video Generation Models.pdf) [Mar 2025] (Interpolating model)<span style="color:red">!</span>
  3. [Dynamic Mask Guidance](papers/Resource-Efficient Motion Control.pdf) [Mar 2025]
  3. [ControlNeXt](papers/ControlNeXt.pdf) [Aug 2024]
  3. [SparseCtrl](papers/SparseCtrl.pdf) [Nov 2023]
  3. [VidSketch](papers/VidSketch.pdf) [Feb 2025]
  3. [FACESHOT](papers/FACESHOT.pdf) [Mar 2025]
  3. [AKiRa](papers/AKiRa.pdf) [Dec 2024] (Camera)
- DIT

  1. [Diffusion as Shader](papers/Diffusion as Shader.pdf) [Jan 2025]
  2. [Go-with-the-Flow](papers/Go-with-the-Flow.pdf) [Jan 2025] (initialize noise as control condition)
  3. [CatV2TON](papers/CatV2TON.pdf)[Jan 2025] (virtual tryon-task,  AdaCN for color error accumulation)
  4. [CineMaster](papers/CineMaster.pdf) [Feb 2025] (3d Bounding Boxes)
  5. [3DTrajMaster](papers/3DTRAJMASTER.pdf) [Feb 2025] (Multiple Entity 3d Trajectory)
  6. [MotionBridge](papers/MotionBridge.pdf) [Jan 2025] (Trajectory + 插值模型)
  7. [MotionCanvas](papers/MotionCanvas.pdf) [Feb 2025] (Trajectory+Box+Camera)
  7. [MagicMotion](papers/MagicMotion.pdf) [Mar 2025] (Mask + Box)
  8. [Video Motion Transfer](papers/Video Motion Transfer with Diffusion Transformers.pdf) [Dec 2024]
  8. [FullDiT](papers/FullDiT.pdf) [Mar 2025]
  8. [Tora](papers/Tora.pdf) [Oct 2024] (Trajectory control)
  8. [VACE](papers/VACE.pdf) [Mar 2025]
  8. [OmniVDiff](papers/OmniVDiff.pdf) [Apr 2025]
  8. [Uni3C](papers/Uni3C.pdf) [Apr 2025]
  8. [MTVCrafter](papers/MTVCrafter.pdf) [May 2025] (4D control)
  8. [DynamiCtrl](papers/DynamiCtrl.pdf) [May 2025] (pose control)
  8. [HyperMotion](papers/HyperMotion.pdf) [May 2025] (pose control)
  8. [DragStream](papers/DragStream.pdf) [Oct 2025] (real-time drag)

### Video Inpainting

1. [Get In Video](papers/Get In Video Add Anything You Want to the Video.pdf) [Mar 2025] 构建数据集 + DiT (条件跟noise直接concate)
2. [DiffuEraser](papers/DiffuEraser.pdf) [Jan 2025] 专注移除任务
2. [DynVFX](papers/DynVFX.pdf) [Feb 2025] (Adding Dynamic Object)
2. [VideoPainter](papers/VideoPainter.pdf) [Mar 2025]
2. [Generative Video Propagation](papers/Generative Video Propagation.pdf) [Dec 2024]
2. [OmnimatteZero](papers/OmnimatteZero.pdf) [Mar 2025]  <span style="color:red">!!!</span>

### Video Editing

1. [VIDEOGRAIN](papers/VIDEOGRAIN.pdf) [Feb 2025]
1. [Taming Rectified Flow for Inversion and Editing](papers/Taming Rectified Flow for Inversion and Editing.pdf) [Nov 2024] (Editing for Rectified Flow-based model) <span style="color:red">!</span>
1. [VideoHandles](papers/VideoHandles.pdf) [Editing object composition]
1. [V2Edit](papers/V2Edit.pdf) [Mar 2025] <span style="color:red">!!!</span>
1. [StyleMaster](papers/StyleMaster.pdf) [Dec 2024]
1. [Video-As-Prompt](papers/Video-As-Prompt.pdf) [Oct 2025] (video2video generation)

### Long Video Generation

- Early Work

  1. [Anim-Director](papers/Anim-Director.pdf) [Aug 2024] (MLLM+VDM, training-free)
  2. [SEED-STORY](papers/SEED-STORY.pdf) [Oct 2024] (image as token in MLLM)
  3. [FBSDiff](papers/FBSDiff.pdf) [Aug 2024] (low frequency from global attn + high frequency from local attn)
  4. [Ouroboros-Diffusion](papers/Ouroboros-Diffusion.pdf) [Jan 2025] (Better Latent + Feature Bank
  5. [LongDiff](papers/LongDiff.pdf) [Mar 2025] 
  6. [RIFLEx](papers/A Free Lunch for Length Extrapolation.pdf) [Feb 2025]
  7. [Training-free and Adaptive Sparse Attention](papers/Training-free and Adaptive Sparse Attention.pdf) [Feb 2025]
  8. [ShotAdapter](papers/ShotAdapter.pdf) [May 2025]

- Multi-shot

  1. Keyframe

     1. [VideoAuteur](papers/VideoAuteur.pdf) [Jan 2025] (Seed Story for the visual embedding)
     2. [TokensGen](papers/TokensGen.pdf) [Jul 2025]
     3. [Captain Cinema](papers/Captain Cinema.pdf) [Jul 2025]
     4. [HoloCine](papers/HoloCine.pdf) [Oct 2025]
     5. [Cut2Next](papers/Cut2Next.pdf) [Aug 2025] (Image model)

  2. Long Video Directly

     [Long Context Tuning for Video Generation](papers/Long Context Tuning for Video Generation.pdf) [Mar 2025]

     asynchronous noise strategy -> apply causal attention + KV-cache to enhance the efficiency

  3. Shot transition

     [CINETRANS](papers/CINETRANS.pdf) [Aug 2025]

- Autoregressive

  1. [AAPT](papers/aapt.pdf) [Oct 2025]
  2. [Causvid ](papers/causvid.pdf)[Sep 2025]
  3. [DFot](papers/DFoT.pdf) [Jul 2025]
  4. [LONGLIVE](papers/LONGLIVE.pdf) [Sep 2025]
  5. [Self Forcing](papers/Self Forcing.pdf) [Jun 2025]
  6. [Self-forcing++](papers/self-forcing++.pdf) [Oct 2025]
  7. [PUSA](papers/pusa.pdf) [Jul 2025]

- World model

  - Game-based signal
    - [From Virtual Games to Real-World Play](papers/From Virtual Games to Real-World Play.pdf) [Jun 2025]
  - World Modeling
    1. [AETHER](papers/AETHER.pdf) [Mar 2025]
    2. [DeepVerse](papers/DeepVerse.pdf) [Jun 2025] (AETHER + 自回归 + memory
    3. [WorldWeaver](papers/WorldWeaver.pdf) [Aug 2025] (generate depth together)
    4. [FANTASYWORLD](papers/FANTASYWORLD.pdf) [Sep 2025]
    5. [EvoWorld](papers/EvoWorld.pdf) [Oct 2025] (全景+3D)

- Memory

  - Explicit Memory
    - 2D
      1. [FramePack](papers/pack.pdf) [Apr 2025]
      2. [Context as Memory](papers/Context as Memory.pdf) [Aug 2025]
      3. [Gamefactory](papers/gamefactory.pdf) [Jul 2025]
      4. [WORLDMEM](papers/WORLDMEM.pdf) [Apr 2025]
    - 3D
      1. [HunyuanWorld-Voyager](papers/HunyuanWorld-Voyager.pdf) [Jun 2025]
      2. [WorldExplorer](papers/WorldExplorer.pdf) [Sep 2025] (this is not video model)
      3. [VMem](papers/VMem.pdf) [Aug 2025] (this is not video model)
    - Hybird
      1. [Spmem](papers/spmem.pdf) [Jun 2025]
  - Implicit Memory
    1. [RepVideo](papers/RepVideo.pdf) [Jan 2025] <span style="color:red">!!!</span> (Explore acculmulate feature)
    1. [TTT](papers/TTT.pdf) [Apr 2025] (猫和老鼠)
    1. [Long-Context](papers/Long-Context State-Space Video World Models.pdf) [May 2025]

### Custimized Video Generation

- Training-based
  1. [SUGAR](papers/SUGAR.pdf) [Dec 2024]
  2. [Multi-subject Open-set Personalization](papers/Multi-subject Open-set Personalization in Video Generation.pdf) [Jan 2025]
  3. [CustomVideoX](papers/CustomVideoX.pdf) [Feb 2025]
  4. [PHANTOM](papers/PHANTOM.pdf) [Feb 2025] (已开源)
  4. [Movie Weaver](papers/Movie Weaver.pdf) [Feb 2025]
  4. [SkyReels-A2](papers/SkyReels-A2.pdf) [Apr 2025]
  4. [HunyuanCustom](papers/HunyuanCustom.pdf) [May 2025]
  4. [FlexiAct](papers/FlexiAct.pdf) [May 2025]
  4. [Subject-driven Video Generation](papers/Subject-driven Video Generation.pdf) [Apr 2025]
- Optimized-based
  1. [Dynamic Concepts Personalization](papers/Dynamic Concepts Personalization from Single Videos.pdf) [Feb 2025] (focus on dynamic content)
  1. [DualReal](papers/DualReal.pdf) [May 2025]
- Face
  1. [Ingredients](papers/Ingredients.pdf) [Jan 2025]
  2. [MagicMirror](papers/Magic Mirror.pdf) [Jan 2025] 
  3. [FantasyID](papers/FantasyID Face Knowledge Enhanced ID-Preserving Video Generation.pdf) [Feb 2025] (3D feature)
  4. [Identity-Preserving Text-to-Video](papers/Identity-Preserving Text-to-Video Generation by Frequency Decomposition.pdf) (Open source)
- Effects (特效)
  1. [Omni-Effects](papers/Omni-Effects.pdf) [Aug 2025]

### Audio Video

- Audio-condition Video generation

  1. [HuMo](papers/HuMo.pdf) [Sep 2025]
  2. [FantasyTalking](papers/FantasyTalking.pdf) [Apr 2025]
  2. [VividAnimator](papers/VividAnimator.pdf) [Oct 2025]

- Unified Generation

  ​		   a. [UniVerse](papers/UniVerse_1_Unified_Audio.pdf) [Oct 2025]

### Leverage LLM/MLLM

- Image
  1. [Making LLaMA SEE and Draw with SEED Tokenizer](papers/Making LLaMA SEE and Draw with SEED Tokenizer.pdf) [Oct 2023]
  1. [Generative Multimodal Models are In-Context Learners](papers/Generative Multimodal Models are In-Context Learners.pdf) [May 2024] (Image as vision tokens)
  2. [BrushEdit](papers/BrushEdit.pdf) [Dec 2024] (similar to our SGEdit work, but with inpainting model)
  3. [EasyRef](papers/EasyRef.pdf) [Dec 2024] (LLM-style IP-adapter)
  4. [Enabling Multimodal In-Context Reasoning](papers/Enabling Multimodal In-Context Reasoning in Diffusion Models.pdf) [Feb 2025] (In-Context, Aligner connect diffusion&VLM)
  4. [DreamEngine](papers/DreamEngine.pdf) [Feb 2025] <span style="color:red">!!!</span>
  4. [Transfer between Modalities with MetaQueries](papers/Transfer between Modalities with MetaQueries.pdf) [Apr 2025]
  4. [Janus-Pro](papers/Janus-Pro.pdf) [Jan 2025]
  4. [BLIP3-o](papers/BLIP3-o.pdf) [May 2025]
  4. [Dual Diffusion for Unified Image Generation and Understanding](papers/Dual Diffusion for Unified Image Generation and Understanding.pdf) [Apr 2025]
  4. [X-Fusion](papers/X-Fusion.pdf) [Apr 2025]
  4. [FuseDiT](papers/FuseDiT.pdf) [May 2025]
  4. [MENTOR](papers/MENTOR.pdf) [Jul 2025]
  4. [INSTRUCTX](papers/INSTRUCTX.pdf) [Oct 2025]
  4. [DREAMOMNI2](papers/DREAMOMNI2.pdf) [Oct 2025]
- Video
  1. [CINEMA](papers/CINEMA Coherent Multi-Subject Video Generation via MLLM-Based Guidance.pdf) [Mar 2025]
  2. [Mimir](papers/Mimir.pdf) [Dec 2024] (Improve text alignment by LLM text feature)
  2. [AnimeGamer](papers/AnimeGamer.pdf) [Apr 2025]
  2. [Univideo](papers/univideo.pdf) [Oct 2025]

### Video Generation

- Autoregressive Video
  1. [RAIN](papers/RAIN.pdf) [Dec 2024]
  1. [StreamingT2V](papers/StreamingT2V.pdf) [Mar 2024]
  1. [Taming Teacher Forcing for Masked Autoregressive Video Generation](papers/Taming Teacher Forcing for Masked Autoregressive Video Generation.pdf) [Jan 2025]<span style="color:red">!!!</span>
  1. [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](papers/From Slow Bidirectional to Fast Autoregressive Video Diffusion Models.pdf) [Jan 2025]<span style="color:red">!!!</span>
  1. [GenDoP](papers/GenDoP.pdf) [Apr 2025]
  1. [MAGI](papers/MAGI_1.pdf) [Apr 2025]
  1. [Autoregressive Diffusion Transformer](papers/Autoregressive Diffusion Transformer.pdf) [May 2025]
- 4D Video
  1. [Reangle-A-Video](papers/Reangle-A-Video.pdf) [Mar 2025] (Synchronized multi-view videos)
  2. [GS-DiT](papers/GS-DiT.pdf) [Jan 2025]
  3. [SYNCAMMASTER](papers/SYNCAMMASTER.pdf) [Dec 2024]
  4. [TrajectoryCrafter](papers/TrajectoryCrafter.pdf) [Mar 2025]
  4. [GEN3C](papers/GEN3C.pdf) [Mar 2025]
- Physical Fidelity
  1. [Synthetic Video Enhances Physical Fidelity in Video Synthesis](papers/Synthetic Video Enhances Physical Fidelity in Video Synthesis.pdf) [Mar 2025]
  1. [PhysAnimator](papers/PhysAnimator.pdf) [Mar 2025]
  1. [NEWTONGEN](papers/NEWTONGEN.pdf) [Sep 2025]
  1. [VChain: Chain-of-Visual-Thought for Reasoning in Video Generation](papers/VChain.pdf) [Oct 2025]
- Design
  1. [PAPER2VIDEO](papers/PAPER2VIDEO.pdf) [Oct 2025]
- Layer
  1. [LayerFlow](papers/LayerFlow.pdf) [Jun 2025]

### Multi-instance Generation

- Image
  1. [3DIS-FLUX](papers/3DIS-FLUX.pdf) [Jan 2025] (layout -> depthmap -> image)
  2. [DreamRenderer](papers/DreamRenderer.pdf) [Mar 2025]
  2. [CreatiLayout](papers/CreatiLayout.pdf) [Mar 2025]
- Video
  1. [BlobGEN-Vid](papers/BlobGEN-Vid.pdf) [Jan 025]

### Image Generation

- Controllable
  1. [Uni-ControlNet](papers/Uni-ControlNet.pdf) [Oct 2023]
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
- Transparent
  1. [Anonymous Region Transformer](papers/Anonymous Region Transformer.pdf) [Feb 2025]

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
  6. [DCEdit](papers/DCEdit.pdf) [Mar 2025] (finegrain edit on DiT)
  6. [Dereflection Any Image](papers/Dereflection Any Image.pdf) [Mar 2025] (Dereflection)
  6. [OMNIEDIT](papers/OMNIEDIT.pdf) [Nov 2024] 
  6. [Diffusion Restoration Adapter](papers/Diffusion Restoration Adapter.pdf) [Feb 2025]
- Specific object manipulation/inpainting
  1. [DiffUHaul](papers/DiffUHaul.pdf) [Sep 2024]
  2. [DreamMix](papers/DreamMix Decoupling Object Attributes for Enhanced Editability in Customized Image Inpainting.pdf) [Nov 2024]
  2. [ObjectMate](papers/ObjectMate.pdf) [Dec 2024]
  2. [Affordance-Aware Object Insertion](papers/Affordance-Aware Object Insertion via Mask-Aware Dual Diffusion.pdf) [Dec 2024]
  6. [Personalize Anything](papers/Personalize Anything for Free with Diffusion Transformer.pdf) [Mar 2025]
  6. [OmniPaint](papers/OmniPaint.pdf) [Mar 2025]
  6. [Large-Scale Text-to-Image Model with Inpainting](papers/Large-Scale Text-to-Image Model with Inpainting.pdf) [Nov 2024]
  6. [Insert Anything](papers/Insert Anything.pdf) [Apr 2025]
  6. [3D-Fixup](papers/3D-Fixup.pdf) [May 2025] (3d manipulation)
  6. [Positional Encoding Field](papers/Positional Encoding Field.pdf) [Oct 2025] (Explore Positional Encoding)
- Leverage video diffusion
  1. [Pathways on the Image Manifold](papers/Pathways on the Image Manifold.pdf) [Nov 2024]
  1. [FramePainter](papers/FramePainter.pdf) [Jan 2025]
  1. [VINCIE](papers/VINCIE.pdf) [Jun 2025]
  1. [CHRONOEDIT](papers/CHRONOEDIT.pdf) [Oct 2025]
  1. [ObjectMover](papers/ObjectMover.pdf) [Mar 2025]
- In-context learning
  1. [Edit Transfer](papers/Edit Transfer.pdf) [Mar 2025]  <span style="color:red">!!!</span>
  2. [ImageRAG](papers/ImageRAG.pdf) [Feb 2025] (Image In-Context Learning)
  2. [IN-CONTEXT LORA](papers/IN-CONTEXT LORA.pdf) [Nov 2024]
  2. [In-Context Edit](papers/In-Context Edit.pdf) [Apr 2025]
- Colorization
  1. [ColorFlow](papers/ColorFlow.pdf) [Dec 2024]
  2. [MangaNinja](papers/MangaNinja.pdf) [Jan 2025]
- Lighting
  1. [LightLab](papers/LightLab.pdf) [May 2025]
- Camera
  1. [DiffCamera](papers/DiffCamera.pdf) [Sep 2025]
- Design
  1. [FACTUALITY MATTERS](papers/FACTUALITY MATTERS.pdf) [Oct 2025]

### Image Customization

1. [AnyStory](papers/AnyStory.pdf) [Jan 2025] (Multiple Subject, Router)
2. [Nested Attention](papers/Nested Attention.pdf) [Jan 2025] (Multiple concepts, utilize cross-attention)
2. [Conceptrol](papers/Conceptrol.pdf) [Mar 2025] (IP-adapter fashion)  <span style="color:red">!!!</span>
2. [UNO](papers/UNO.pdf) [Apr 2025] <span style="color:red">!</span>
2. [latexblend](papers/latexblend.pdf) [Mar 2025]
2. [Visual Persona](papers/Visual Persona.pdf) [Mar 2025]
2. [TokenVerse](papers/TokenVerse.pdf) [Jan 2025]
2. [FlexIP](papers/FlexIP.pdf) [Apr 2025]
2. [Generating Multi-Image Synthetic Data for Text-to-Image Customization](papers/Generating Multi-Image Synthetic Data for Text-to-Image Customization.pdf) [Feb 2025]

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
- Linear Attention
  1. [SANA](papers/SANA.pdf) [Oct 2024]
  2. [SANA-Video](papers/SANA-Video.pdf) [Oct 2025]


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
  2. [Seaweed-7B](papers/Seaweed-7B.pdf) [Apr 2025] <span style="color:red">!!!</span>
- video(dataset)
  1. [OPENVID-1M](papers/OPENVID-1M.pdf) [Feb 2025]
  1. [Señorita-2M](papers/Señorita-2M.pdf) [Mar 2025] (Video Editing dataset)

### New Architecture

1. [VideoPoet](papers/VideoPoet.pdf) [Jun 2024] (LLM for Video Generation)
1. [OmniFlow](papers/OmniFlow.pdf) [Dec 2024] (Any-to-Any Generation)
1. [Diffusion Forcing](papers/Diffusion Forcing.pdf) [Dec 2024]<span style="color:red">!!!</span>
2. [Diffusion Noise Condition](papers/Is Noise Conditioning Necessary for Denoising Generative Models.pdf) [Feb 2025]
2. [Block Diffusion](papers/BLOCK DIFFUSION.pdf) [Mar 2025]
2. [Everything is a Video](papers/Everything is a Video.pdf) [Jul 2025]
2. [Pyramidal Flow Matching](papers/PYRAMIDAL FLOW MATCHING FOR EFFICIENT VIDEO GENERATIVE MODELING.pdf) [Mar 2025]
2. [Unified Multimodal Discrete Diffusion ](papers/Unified Multimodal Discrete Diffusion.pdf)[Mar 2025]
2. [Learning Visual Generative Priors without Text](papers/Learning Visual Generative Priors without Text.pdf) [Mar 2025]
2. [Infinity: Scaling Bitwise AutoRegressive Modeling for High-Resolution Image Synthesis](papers/Infinity.pdf) [Dec 2024]
2. [Dynamic Diffusion Transformer](papers/DYNAMIC DIFFUSION TRANSFORMER.pdf) [Oct 2024]

### Reward

1. [Diffusion-Sharpening](papers/Diffusion-Sharpening.pdf)<span style="color:red">!</span>
2. [Diffusion Model Alignment](papers/Diffusion Model Alignment.pdf) (让模型在胜者图像上比参考模型更会去噪，而在败者图像上故意不如参考模型)
2. [VideoDPO](papers/VideoDPO.pdf) [Dec 2024]
2. [T2I-R1](papers/T2I-R1.pdf) [May 2025]
2. [SimpleAR](papers/SimpleAR.pdf) [Apr 2025]

### COT and TTS (test-time scaling)<span style="color:red">!!!</span>

1. [ImageGen-CoT](papers/ImageGen-CoT.pdf) [Mar 2025]
2. [GoT](papers/GoT.pdf) [Mar 2025]
3. [Video-T1](papers/Video-T1.pdf) [Apr 2025]
3. [Can We Generate Images with CoT](papers/Can We Generate Images with CoT.pdf) [Jan 2025]
3. [One-Minute Video Generation with Test-Time Training](papers/One-Minute Video Generation with Test-Time Training.pdf) [Apr 2025]
3. [Video-R1](papers/Video-R1.pdf) [Mar 2025] (Video reasoning)

### Talking Face

1. [mocha](papers/mocha.pdf)  [Mar 2025]

### Image-to-3D Scene Generation

1. [PanoDreamer](papers/PanoDreamer.pdf) [Mar 2025]
1. [MIDI](papers/MIDI.pdf) [Dec 2024]

### 3D Scene Generation

1. [NuiScene](papers/NuiScene.pdf)  [Mar 2025]
1. [WorldGrow](papers/WorldGrow.pdf) [Oct 2025]

### Image/Video-driven 3D

1. [Animating the Uncaptured](papers/Animating the Uncaptured.pdf) [Mar 2025]
1. [DIFIX3D+](papers/DIFIX3D+.pdf) [Mar 2025] <span style="color:red">!</span>

### SVG

1. [NeuralSVG](papers/NeuralSVG.pdf) [Jan 2025]
2. [LayerTracer](papers/LayerTracer.pdf) [Feb 2025] 

### CV

1. [CleanDIFT](papers/CleanDIFT.pdf) [Dec 2024] (clean diffusion features -> improve downstream tasks: e.g. segment...) <span style="color:red">!</span>
2. [FreestyleRet](papers/FreestyleRet.pdf) [Dec 2023] (image retrieval)
3. [Generalizable Origin Identification](papers/Generalizable Origin Identification.pdf) (Origin Identification.pdf)
3. [spatracker](papers/spatracker.pdf) [Apr 2024] (3D point tracking)
5. [3D Scene Flow](papers/3D Scene Flow.pdf) [2020] (3D optical flow)
5. [DynOMo](papers/DynOMo.pdf) [Mar 2025] (4D recon)
5. [Dynamic 3D Gaussians](papers/Dynamic 3D Gaussians.pdf) [Aug 2023] (4D recon)
5. [Segment Anything](papers/Segment Anything.pdf) [Apr 2023] (segment)
5. [RAFT-3D](papers/RAFT-3D.pdf)
5. [MONST3R](papers/MONST3R.pdf)
5. [GeometryCrafter](papers/GeometryCrafter.pdf)
5. [DUSt3R](papers/DUSt3R.pdf)
5. [Dynamic Point Maps](papers/Dynamic Point Maps.pdf)
5. 

### Other

1. [InstantFamily](papers/InstantFamily.pdf) [Apr 2024] (Multi-Face composition)
2. [IP-Composer](papers/IP-Composer.pdf) [Feb 2025] (Semantic Composition of Visual Concepts)
3. [KV Cache](papers/KV Cache.pdf) [Feb 2025] (Analyse KV Cache)
4. [MakeAnything](papers/MakeAnything.pdf) [Feb 2025] (Generate Procedural)
5. [Light-A-Video](papers/Light-A-Video.pdf) [Feb 2025] (Video Relighting)
7. [Orient Anything](papers/Orient Anything.pdf) [Dec 2024] (Predict Orientation)
8. [SeedVR](papers/SeedVR.pdf) [Feb 2025] (Image Super-resolution)
9. [Star](papers/Stable Flow.pdf) [Jan 2025] (Video Super-resolution)
10. [Spotlight](papers/SPOTLIGHT.pdf) [Nov 2024] (Shadow-Guided Object Relighting)
11. [SVDiff](papers/SVDiff Compact Parameter Space for Diffusion Fine-Tuning.pdf) [Jul 2023] (Singular Value Decomposition)
12. [TransPixeler](papers/TransPixeler.pdf) [Jan 2025] (Transparent Video Generation)
14. [Visual Anagrams](papers/Visual Anagrams.pdf) [Apr 2024] (Illusion Image Generation)
15. [DesignDiffusion](papers/DesignDiffusion.pdf) [Mar 2025] (Diffusion for Design)
16. [Generative Photomontage](papers/Generative Photomontage.pdf) [Aug 2024] (多图融合)
17. [MatAnyone](papers/MatAnyone.pdf) [Jan 2025] (Video Matting)
20. [KV Cache Quantization](papers/Plug-and-Play 1.x-Bit KV Cache Quantization.pdf) [Mar 2025] (VLLM quantization)
20. [Shining Yourself](papers/Shining Yourself.pdf) [Mar 2025] (Diffusion tryout)
20. [FILMAGENT](papers/FILMAGENT.pdf) [Jan 2025]
20. [HumanRig](papers/HumanRig.pdf) [Dec 2024] (Rigging)da
