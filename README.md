DOWNLOADS: https://huggingface.co/datasets/4eJIoBek/PAIT-Downloads/tree/main

This is my collection of portable AI packages to run it fast without anxious headache in console, sort of "Awesome N" repos, but for portables for win. initially, I made these tools for myself, but maybe someone else will need them. All portables can work offline and tested on gtx 1050 ti 4gb(cuda) and core i3 1005g1 (cpu). OK, heres the list:

!!! IF SOMETHING ISN'T WORKING, MAKE SURE THAT PATH TO TOOL DON'T HAVE SPACES OR NON-ENGLISH SYMBOLS !!!

!!! TO AVOID CUDA OUT OF MEMORY ERRORS, INSTALL NVIDIA DRIVERS 535 OR NEWER !!!

### -TEXT-

Koboldai (without models) [CPU/CUDA] - [link](https://github.com/KoboldAI/KoboldAI-Client/releases/) - also in downloads / [online demo](https://lite.koboldai.net/)
![Pyu6ch](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/3de9a9b0-51a9-436c-b4cb-c903a39ef987)

### -CHAT-
Llama-3-8b-instruct-Suzume-multilingual-4bit koboldcpp webui (can also load mmproj loras to chat with images) [CPU/OpenCL/Vulkan] - in downloads / [source](https://github.com/ggerganov/llama.cpp) / [webui](https://github.com/LostRuins/koboldcpp/releases) / [model]([https://huggingface.co/TheBloke/Mistral-7B-OpenOrca-GGUF](https://huggingface.co/QuantFactory/suzume-llama-3-8B-multilingual-GGUF))
![3ekZFe](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/82fa4ed3-6f3e-49e8-a02a-5140aa07887f)


Mobile AI Distribution (MAID) (same as koboldcpp, but multiplatform win-linux-android) [CPU] - [link](https://github.com/Mobile-Artificial-Intelligence/maid/releases) - also in downloads
![QdKnzH](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/5d8e357f-070e-44d2-9326-42b267626fa8)

### -CHAT WITH DOCUMENTS-

LocalGPT Llama2-7b (w/o gui) [CUDA(tokenizing only, chat on cpu)/CPU] - in downloads / [source](https://github.com/PromtEngineer/localGPT)

### -TRANSLATE-

Facebook NLLB 600m webui [CPU] - in downloads / [source](https://github.com/facebookresearch/fairseq/tree/nllb) / [webui](https://huggingface.co/spaces/Geonmo/nllb-translation-demo) / [model](https://huggingface.co/facebook/nllb-200-distilled-600M) / [online demo](https://huggingface.co/spaces/Geonmo/nllb-translation-demo) 
![lXex_i](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/6eca7d80-023e-4cd6-958b-0f1e012fd804)

### -MIDI MUSIC GENERATION-

Midi composer app [CUDA][CPU] - [link](https://github.com/SkyTNT/midi-model/releases/tag/v1.1.0) - also in downloads / [source](https://github.com/SkyTNT/midi-model) / [online demo](https://huggingface.co/spaces/skytnt/midi-composer) 
![MtgLrP](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/81c3f404-f911-400c-a158-ee6263a336aa)

 Multitrack midi music generator (generates short jingles, each instrument generated separately) [CPU] - in downloads / [webui](https://huggingface.co/spaces/juancopi81/multitrack-midi-music-generator) 
![OaDVXD](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/16faaa78-977e-4f96-9739-efa3e5516c6a)

### -TEXT TO MUSIC/AUDIO-

Stable Audio Open 1.0 [CUDA/CPU] - in downloads / [source](https://github.com/Stability-AI/stable-audio-tools)​ / [model](https://huggingface.co/stabilityai/stable-audio-open-1.0)​ / [online demo](https://huggingface.co/spaces/ameerazam08/stableaudio-open-1.0)​ 
![stableaudioopen](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/566b2707-65e9-4b6a-beb3-5e6d6951afd7)


[this model is in legacy] AudioCraft Plus [CUDA/CPU] - in downloads / [source](https://github.com/facebookresearch/audiocraft) / [webui](https://github.com/GrandaddyShmax/audiocraft_plus) / [online demo](https://huggingface.co/spaces/facebook/MusicGen)
![_WK2ix](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/72acb464-e4dc-4c91-92cd-c961a3be396e)

### -TEXT TO SPEECH-

Coqui XTTS2 webui (voice cloning is more "stable" than bark, but less artistic) [CUDA/CPU] - in downloads / [source](https://github.com/coqui-ai/TTS) / [webui](https://github.com/BoltzmannEntropy/xtts2-ui)  
![VJx3TB](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/88396f95-e3a6-408f-bc17-da86d4a50119)

Suno ai Bark webui (tts is more chaotic than xtts, but if you have patience, you can roll ideal variant) (with zeroshot voice conversion) [CUDA/CPU] - in downloads / [source](https://github.com/suno-ai/bark) / [webui](https://github.com/C0untFloyd/bark-gui) / [online demo](https://huggingface.co/spaces/suno/bark) 
![sbdCsJ](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/47d8bd44-8cef-47d7-8340-fcd5b0ee293f)

TorToiSe webui (english-only) [CUDA/CPU] - in downloads / [source](https://github.com/neonbjb/tortoise-tts) / [webui](https://git.ecker.tech/mrq/ai-voice-cloning) / [online demo](https://replicate.com/afiaka87/tortoise-tts) 
![V+ecJL](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/4b0a53ec-b7d0-4397-b633-d48a7130df57)

### -VOICE CONVERSION VIA TRAINING-

RVC singing voice cloning webui [CUDA] - [link](https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main) - also in downloads / [source](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI/blob/main/docs/README.en.md)  
![eh0sNS](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/35a25e3b-e675-4356-b033-83476c717b2d)

### -VOICE ZEROSHOT CONVERSION-

FreeVC webui [CPU] - in downloads / [source](https://github.com/OlaWod/FreeVC) / [webui](https://huggingface.co/spaces/OlaWod/FreeVC) 
![3gjyBR](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/75d9059a-33b8-4389-b625-d886d8bbfe71)

### -VOICE TO TEXT-

Whispercpp GUI [DirectX/CPU] - [link](https://github.com/Const-me/Whisper/releases/) - also in downloads / [source](https://github.com/ggerganov/whisper.cpp) / [gui](https://github.com/Const-me/Whisper) / [online demo](https://replicate.com/openai/whisper) 
![b40V2M](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/47d5aaec-dc74-4a5d-869c-bf31ca7f277d)

### -UNIVERSAL AUDIO RESTORATION-

AudioSR (cli interface) [CUDA/CPU] - in downloads / [source](https://github.com/haoheliu/versatile_audio_super_resolution) 
<img width="1038" alt="pSN++5" src="https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/b28d6e70-9ac8-4709-996e-9f32e3680b5e">

### -VOCALS RESTORATION-

VoiceFixer webui [CPU] - in downloads / [source](https://github.com/haoheliu/voicefixer) / [webui](https://huggingface.co/spaces/Kevin676/VoiceFixer) 
![mBGt_7](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/939ccd00-d4ce-4367-9c27-d8e1a8575ba0)

### -DUAL SPEAKER SPEECH SEPARATION-

Dual Path RNN (w/o gui) [CPU] - in downloads / [source](https://github.com/JusperLee/Dual-Path-RNN-Pytorch) 
![+TNNVI](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/ebedcd51-1495-47f6-92ad-915645e5a0ab)

### -STEMS EXTRACTION BY PROMPT-

AudioSep webui [CUDA/CPU] - in downloads / [source](https://github.com/Audio-AGI/AudioSep) / [webui](https://huggingface.co/spaces/Audio-AGI/AudioSep) 
![mn8vdd](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/3de6384a-0488-4bf9-a7ad-009341e20453)

### -VOCALS/STEMS EXTRACTION-

UVR [CPU/CUDA] - [link](https://github.com/Anjok07/ultimatevocalremovergui/releases/) - also in downloads / [online demo](https://mvsep.com/)  
![qFgCLF](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/4f9d1674-1f3c-4c37-b4d6-7884e3ab5b41)

Demucs gui [CPU][CUDA] - [link](https://carlgao4.github.io/demucs-gui/) - also in downloads / [source](https://github.com/facebookresearch/demucs) / [gui](https://github.com/CarlGao4/Demucs-Gui) 
![tuB6Y9](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/1ede69d6-3886-42d8-b1b3-c7807cc1ae6a)

### -IMAGE COLORIZATION-

DeOldify .NET gui [CPU] - [link](https://github.com/ColorfulSoft/DeOldify.NET/releases) - also in downloads / [source](https://github.com/jantic/DeOldify) / [gui](https://github.com/ColorfulSoft/DeOldify.NET) / [online demo](https://huggingface.co/spaces/leonelhs/deoldify) 
![33sfKM](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/b9b057bc-8c50-4e9a-8fb9-9d61118b4769)

### -ZEROSHOT IMAGE MATTING-

DIS (BRIAAI RMBG 1.4 model) webui [CPU] - in downloads / [source](https://github.com/xuebinqin/DIS) / [webui](https://huggingface.co/spaces/ECCV2022/dis-background-removal) / [model](https://huggingface.co/briaai/RMBG-1.4) 
![5JcFs9](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/4f09a933-6227-467e-8437-83eb4fc2cadb)

### -MONOCULAR-DEPTH-ESTIMATION-

ZoeDepth-webui [CUDA/CPU][CPU] - in downloads / [source](https://github.com/isl-org/ZoeDepth) / [webui](https://huggingface.co/spaces/shariqfarooq/ZoeDepth)  
![NoFmUy](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/937a1063-d5ba-425a-a1de-4fe02e0f7acb)

### -IMAGE UPSCALING-

real-ESRGAN-gui [Vulkan] - [link](https://github.com/TransparentLC/realesrgan-gui/releases) - also in downloads / [source](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan) / [gui](https://github.com/TransparentLC/realesrgan-gui) / [online demo](https://replicate.com/xinntao/realesrgan) 
![Xw5SMF](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/4be99cbf-ef91-42ce-bf27-904a1121ab7b)

ChaiNNer (supports a LOT of upscaling methods) [CUDA/Vulkan] - [link](https://github.com/chaiNNer-org/chaiNNer/releases) - also in downloads / [gui](https://github.com/chaiNNer-org/chaiNNer) 
![x8Xf3y](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/1cd7e216-a27a-4b52-a177-c2a944edd369)

Automatic1111 sdwebui with StableSR extension [CUDA/CPU] - in downloads / [source](https://github.com/IceClear/StableSR) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) / [extension](https://github.com/pkuliyi2015/sd-webui-stablesr) 
![12BEYB](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/bdbf23cd-b4c4-42ed-b762-31f3008a33e2)

### -TEXT2IMAGE-

Automatic1111 Stable Diffusion base (without models) - [link](https://github.com/AUTOMATIC1111/stable-diffusion-webui/releases)  / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) 
![+TieBC](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/4029bdb7-a57e-4e0c-88b6-179fffac6e25)

Automatic1111 deliberate v2 (sd1.5) model [CUDA/CPU][DIRECTX/CPU] - in downloads / [source](https://github.com/CompVis/stable-diffusion) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  / [directx webui](https://github.com/lshqqytiger/stable-diffusion-webui-directml) / [model](https://civitai.com/models/4823/deliberate) 

Automatic1111 Illuminati Diffusion (sd2.1) model [CUDA/CPU] - in downloads / [source](https://github.com/CompVis/stable-diffusion) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  / [model](https://huggingface.co/Sosaka/Illuminati) 

Automatic1111 SDXL 1.0 (sdxl) model [CUDA/CPU] - in downloads  / [source](https://github.com/CompVis/stable-diffusion) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  / [model](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) / [refiner](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0) 

Fooocus (sdxl) [CUDA] - [link](https://github.com/lllyasviel/Fooocus/releases) - also in downloads / [source](https://github.com/Stability-AI/generative-models) / [webui](https://github.com/lllyasviel/Fooocus) / [model](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) / [refiner](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0)  
![N0TvWv](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/f8c9ecd3-7a8a-40fd-8e4a-ba15ecb26425)

ComfyUI (without models) [CUDA/CPU] - [link](https://github.com/comfyanonymous/ComfyUI/releases/tag/latest) - also in downloads / [source](https://github.com/CompVis/stable-diffusion) / [webui](https://github.com/comfyanonymous/ComfyUI) 
![9K2p0q](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/5140cdfb-6c9d-4497-83a4-006ec63ad436)

### -IMAGE EDITING BY PROMPT-

Automatic1111 Instructpix2pix (sd1.5) model (you also can download just model and use in default automatic1111 if you want, webui doesnt downloads any other files while loading this one) [DIRECTX/CPU][CUDA/CPU] - in downloads / [source](https://github.com/CompVis/stable-diffusion) / [ip2p source](https://github.com/timothybrooks/instruct-pix2pix) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  / [directx webui](https://github.com/lshqqytiger/stable-diffusion-webui-directml) / [model](http://instruct-pix2pix.eecs.berkeley.edu/instruct-pix2pix-00-22000.ckpt) 
![pRlbFS](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/b6e3faf2-5c05-42b8-ab13-42b112f15bbb)

### -IMAGE TO IMAGE VARIATIONS-

Automatic1111 sd-unclip (sd2.1) model (there is an alternative that works without any models - controlnet reference) [CUDA/CPU] - in downloads / [source](https://github.com/CompVis/stable-diffusion) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  / [model](https://huggingface.co/stabilityai/stable-diffusion-2-1-unclip) 
![L_jgdU](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/b3c72e70-8161-44ac-bf5c-cb17a657e86e)

### -IMAGE EDITING BY CONCEPTS-

LEDITS webui [CUDA/CPU] - in downloads / [source](https://editing-images-project.hf.space/index.html) / [webui](https://huggingface.co/spaces/editing-images/ledits) 
![DnMv_m](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/97c53916-9140-416a-a18a-33655f47778c)

### -OBJECT REMOVING-

lama cleaner [CPU] - in downloads / [source](https://github.com/advimman/lama) / [webui](https://github.com/Sanster/lama-cleaner) / [online demo](https://huggingface.co/spaces/Sanster/Lama-Cleaner-lama)
![DRH647](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/0f0be598-cc5f-43eb-be5a-2f9704e16ea3)

### -VIDEO FRAMES INTERPOLATION-

Flowframes [CUDA/Vulkan] - in downloads / [source](https://github.com/megvii-research/ECCV2022-RIFE) / [gui](https://nmkd.itch.io/flowframes) 
![TQuffB](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/6269d94d-5167-4815-878c-9015744db83b)

### -VIDEO UPSCALING-

RealBasicVSR (cli interface) [CUDA/CPU] - in downloads / [source](https://github.com/ckkelvinchan/RealBasicVSR) 
![_vuHXH](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/f0377526-7f0c-4304-ac33-0b990a527e5b)

### -TEXT2VIDEO-

Automatic1111 sdwebui with animatediff extension [CUDA/CPU] - in downloads / [source](https://github.com/guoyww/AnimateDiff) / [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) / [extension](https://github.com/continue-revolution/sd-webui-animatediff) / [model](https://huggingface.co/guoyww/animatediff/resolve/main/mm_sd_v15_v2.ckpt) / [online demo](https://huggingface.co/spaces/guoyww/AnimateDiff) 
![GCnPWI](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/902932b2-2601-45ab-8e20-b29f54646841)

### -VIDEO HUMAN MATTING-

RobustVideoMatting (w/o gui) [CUDA/CPU] - in downloads / [source](https://github.com/PeterL1n/RobustVideoMatting) / [online demo](https://replicate.com/arielreplicate/robust_video_matting) 

### -VIDEO ZERO-SHOT MATTING-

Track-anything webui [CPU] - in downloads / [webui](https://github.com/gaomingqi/Track-Anything) / [online demo](https://huggingface.co/spaces/VIPLab/Track-Anything) 
![6CycXj](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/dfaa0b1d-ebb2-4fab-87e9-16e780e347db)

### -VIDEO FEW-SHOT MATTING VIA TRAINING-

DeepXTools by Iperov [CUDA] - [link](https://github.com/iperov/DeepXTools/releases/tag/install_win_nvidia) - also in downloads
![DDSrO3](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/c1dafee7-6f1b-475a-8581-7ff2f09e1527)

### -ZERO-SHOT DEEPFAKING-

Roop neurogen mod (Refacer model) (lightning fast, has realtime deepfake on webcam function) (the refacer model swaps faces better than simswap, but have only 128px resolution and may have more artifacts when head is on side) [DirectX/CUDA/CPU] - in downloads / [source](https://github.com/deepinsight/insightface/tree/master/web-demos/swapping_discord) / [webui](https://github.com/s0md3v/roop) / [mod by](https://t.me/neurogen_news) 
![b_Utz3](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/27d4efd0-7a38-4235-b541-f0fa6d47fda7)

Deepinsight Refacer gradio webui (replaces only certain faces, has cool face upscale feature) [CUDA] - in downloads / [source](https://github.com/deepinsight/insightface/tree/master/web-demos/swapping_discord) / [webui](https://github.com/xaviviro/refacer) / [mod by](https://t.me/neurogen_news) 
![CpoDoO](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/ea4ab998-bd43-424d-9ee4-77c32fea2516)
![pu1Fil](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/d25bdf25-20a4-44a7-b560-7194d1e90758)

Simswap (w/o gui) [CUDA/CPU] - in downloads / [source](https://github.com/neuralchen/SimSwap) 

### -DEEPFAKING VIA TRAINING-

DeepFaceLab (w/o gui) [DirectX][CUDA] - [link](https://mega.nz/folder/Po0nGQrA#dbbttiNWojCt8jzD4xYaPw) - also in downloads / [source](https://github.com/iperov/DeepFaceLab) 
![JCOsSh](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/b3cf0428-03ea-4d60-8277-a10c91ab1384)

DeepfaceLive [DirectX][CUDA] - [link](https://mega.nz/folder/m10iELBK#Y0H6BflF9C4k_clYofC7yA)  - also in downloads / [source](https://github.com/iperov/DeepFaceLive) 
![Oqsg3B](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/d9259454-f8a3-4e70-8262-fc43e66893ed)

### -LIPS MANIPULATION ON VIDEO-

wav2lip gui [CUDA/CPU] - [link](https://github.com/dunnousername/Wav2Lip/releases) - also in downloads / [source](https://github.com/Rudrabha/Wav2Lip) / [gui](https://github.com/dunnousername/Wav2Lip)  
![_HsMGK](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/25f9034d-c365-48c7-85af-44f6351a29f4)

### -SINGLE IMAGE To MESH-

TripoSR (outputs is still rough, but better, than shap-e) [CUDA/CPU] - in downloads / [source](https://github.com/VAST-AI-Research/TripoSR) / [online demo](https://huggingface.co/spaces/stabilityai/TripoSR) 
![tJncCo](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/f2be69d6-13ee-4938-b570-d155994187b8)

### -TEXT To 3D-

Shap-E webui [this model is legacy][CUDA/CPU] -in downloads / [source](https://github.com/openai/shap-e) / [webui](https://huggingface.co/spaces/hysts/Shap-E)
![0mjkaG](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/8d803e6d-a1b3-4c59-84f0-d1e302a8450a)

Point-E webui [this model is legacy][CUDA/CPU] (results are worse than shap-e) - in downloads / [source](https://github.com/openai/point-e) / [webui](https://huggingface.co/spaces/anzorq/point-e_demo) 
![wLgG6G](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/f02492ed-1eeb-4b70-bacb-65181df6f2b8)

### -MESH GENERATION BY IMAGES-

Dust3r webui (one model that does end-to-end photogrammetry, useful when traditional photogrammetry software like metashape dont determines camera positions, but quality may be bad) [CUDA/CPU] - in downloads / [source](https://github.com/naver/dust3r) 
![4pkVwk](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/45129750-884e-4c67-ae88-0d53d5deea19)

### -NOVEL VIEWS GENERATION BY IMAGES-

NERFStudio (splatfacto, nerfacto) [CUDA/CPU(cpu is extremely slow,but working)] - in downloads / [source](https://github.com/nerfstudio-project/nerfstudio) 
![pzsvz7](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/3bee44bd-1c9d-45be-9575-bfe961788a99)

--------------------------------------------------------------

You can theoretically run these tools on windows 7, jut download [this](https://huggingface.co/datasets/4eJIoBek/PAIT-Downloads/resolve/main/api-ms-win-core-path-l1-1-0.dll?download=true) file and place it along with python.exe

--------------------------------------------------------------

Page on itch.io: https://gz1k.itch.io/ai-portable-tools

Alternative downloads with torrents on Archive.org: https://archive.org/details/@takeonme1?tab=uploads

Page on civitai: https://civitai.com/models/104609
