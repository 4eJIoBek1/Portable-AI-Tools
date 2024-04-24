DOWNLOADS: https://huggingface.co/datasets/4eJIoBek/PAIT-Downloads/tree/main

This is my collection of portable AI packages to run it fast without anxious headache in console. initially, I made these tools for myself, but maybe someone else will need them. All portables can work offline and tested on gtx 1050 ti 4gb(cuda) and core i3 1005g1 (cpu). If you have any questions, ask them here. OK, heres the list:

!!! IF SOMETHING ISN'T WORKING, MAKE SURE THAT PATH TO TOOL DON'T HAVE SPACES OR NON-ENGLISH SYMBOLS !!!

!!! TO AVOID CUDA OUT OF MEMORY ERRORS, INSTALL NVIDIA DRIVERS 535 OR NEWER !!!

###-TEXT-

Koboldai (without models) [CPU/CUDA] - link - also in downloads / online demo
![Pyu6ch](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/3de9a9b0-51a9-436c-b4cb-c903a39ef987)

###-CHAT-
Mistral-7B-openorca 4bit koboldcpp webui (can also load mmproj loras to chat with images) [CPU/OpenCL] - in downloads 
![3uQIJs](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/6f513e6e-241c-4197-847f-20a5108848ab)

/ source / webui / model

Mobile AI Distribution (MAID) (same as koboldcpp, but multiplatform win-linux-andoid) [CPU] - link - also in downloads
![QdKnzH](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/5d8e357f-070e-44d2-9326-42b267626fa8)

###-CHAT WITH DOCUMENTS-

LocalGPT Llama2-7b (w/o gui) [CUDA(tokenizing only, chat on cpu)/CPU] - in downloads / source

###-TRANSLATE-

Facebook NLLB 600m webui [CPU] - in downloads / source / webui / model / online demo 
![lXex_i](https://github.com/4eJIoBek1/Portable-AI-Tools/assets/109795993/6eca7d80-023e-4cd6-958b-0f1e012fd804)

###-MIDI MUSIC GENERATION-

Midi composer app [CUDA][CPU] - link - also in downloads / source / online demo 

 Multitrack midi music generator (generates short jingles, each instrument generated separately) [CPU] - in downloads / webui 

###-TEXT TO MUSIC/AUDIO-

AudioCraft Plus [CUDA/CPU] - in downloads / source / webui / online demo  

###-TEXT TO SPEECH-

Coqui XTTS2 webui (voice cloning is more "stable" than bark, but less artistic) [CUDA/CPU] - in downloads / source / webui  

Suno ai Bark webui (tts is more chaotic than xtts, but if you have patience, you can roll ideal variant) (with zeroshot voice conversion) [CUDA/CPU] - in downloads / source / webui / online demo 

TorToiSe webui (english-only) [CUDA/CPU] - in downloads / source / webui / online demo 

###-VOICE CONVERSION VIA TRAINING-

RVC singing voice cloning webui [CUDA] - link - also in downloads / source  

###-VOICE ZEROSHOT CONVERSION-

FreeVC webui [CPU] - in downloads / source / webui 

###-VOICE TO TEXT-

Whispercpp GUI [DirectX/CPU] - link - also in downloads / source / gui / online demo 

###-UNIVERSAL AUDIO RESTORATION-

AudioSR (cli interface) [CUDA/CPU] - in downloads / source 

###-VOCALS RESTORATION-

VoiceFixer webui [CPU] - in downloads / source / webui 

###-DUAL SPEAKER SPEECH SEPARATION-

Dual Path RNN (w/o gui) [CPU] - in downloads / source 

###-STEMS EXTRACTION BY PROMPT-

AudioSep webui [CUDA/CPU] - in downloads / source / webui 

###-VOCALS/STEMS EXTRACTION-

UVR [CPU/CUDA] - link - also in downloads / online demo  

Demucs gui [CPU][CUDA] - link - also in downloads / source / gui 

###-IMAGE COLORIZATION-

DeOldify .NET gui [CPU] - link - also in downloads / source / gui / online demo 

###-ZEROSHOT IMAGE MATTING-

DIS (BRIAAI RMBG 1.4 model) webui [CPU] - in downloads / source / webui / model 

###-MONOCULAR-DEPTH-ESTIMATION-

ZoeDepth-webui [CUDA/CPU][CPU] - in downloads / source / webui  

###-IMAGE UPSCALING-

real-ESRGAN-gui [Vulkan] - link - also in downloads / source / gui / online demo 

ChaiNNer (supports a LOT of upscaling methods) [CUDA/Vulkan] - link - also in downloads / gui 

Automatic1111 sdwebui with StableSR extension [CUDA/CPU] - in downloads / source / webui / extension 

###-TEXT2IMAGE-

Automatic1111 Stable Diffusion base (without models) - link  / webui 

Automatic1111 deliberate v2 (sd1.5) model [CUDA/CPU][DIRECTX/CPU] - in downloads / source / webui  / directx webui / model 

Automatic1111 Illuminati Diffusion (sd2.1) model [CUDA/CPU] - in downloads / source / webui  / model 

Automatic1111 SDXL 1.0 (sdxl) model [CUDA/CPU] - in downloads

 / source / webui  / model / refiner 

Fooocus (sdxl) [CUDA] - link- also in downloads / source / webui / model / refiner  

ComfyUI (without models) [CUDA/CPU] - link - also in downloads / source / webui 

###-IMAGE EDITING BY PROMPT-

Automatic1111 Instructpix2pix (sd1.5) model (you also can download just model and use in default automatic1111 if you want, webui doesnt downloads any other files while loading this one) [DIRECTX/CPU][CUDA/CPU] - in downloads / source / ip2p source / webui  / directx webui / model 

###-IMAGE TO IMAGE VARIATIONS-

Automatic1111 sd-unclip (sd2.1) model (there is an alternative that works without any models - controlnet reference) [CUDA/CPU] - in downloads / source / webui  / model 

###-IMAGE EDITING BY CONCEPTS-

LEDITS webui [CUDA/CPU] - in downloads / source / webui 

###-OBJECT REMOVING-

lama cleaner [CUDA] - in downloads / source / webui / online demo

###-VIDEO FRAMES INTERPOLATION-

Flowframes [CUDA/Vulkan] - in downloads / source / gui 

###-VIDEO UPSCALING-

RealBasicVSR (cli interface) [CUDA/CPU] - in downloads / source 

###-TEXT2VIDEO-

Automatic1111 sdwebui with animatediff extension [CUDA/CPU] - in downloads / source / webui / extension / model / online demo 

###-VIDEO HUMAN MATTING-

RobustVideoMatting (w/o gui) [CUDA/CPU] - in downloads / source / online demo 

###-VIDEO ZERO-SHOT MATTING-

Track-anything webui [CPU] - in downloads / webui / online demo 

###-VIDEO FEW-SHOT MATTING VIA TRAINING-

DeepXTools by Iperov [CUDA] - link - also in downloads

###-ZERO-SHOT DEEPFAKING-

Roop neurogen mod (Refacer model) (lightning fast, has realtime deepfake on webcam function) (the refacer model swaps faces better than simswap, but have only 128px resolution and may have more artifacts when head is on side) [DirectX/CUDA/CPU] - in downloads / source / webui / mod by 

Deepinsight Refacer gradio webui (replaces only certain faces, has cool face upscale feature) [CUDA] - in downloads / source / webui / mod by 


Simswap (w/o gui) [CUDA/CPU] - in downloads / source 

###-DEEPFAKING VIA TRAINING-

DeepFaceLab (cli interface) [DirectX][CUDA] - link - also in downloads / source 

DeepfaceLive [DirectX][CUDA] - link  - also in downloads / source 

###-LIPS MANIPULATION ON VIDEO-

wav2lip gui [CUDA/CPU] - link - also in downloads / source / gui  

###-SINGLE IMAGE To MESH-

TripoSR (outputs is still rough, but better, than shap-e) [CUDA/CPU] - in downloads / source / online demo 

###-TEXT To 3D-

Shap-E webui [this model is legacy][CUDA/CPU] -in downloads / source / webui

Point-E webui [this model is legacy][CUDA/CPU] (results are worse than shap-e) - in downloads / source / webui 

###-MESH GENERATION BY IMAGES-

Dust3r webui (one model that does end-to-end photogrammetry, useful when traditional photogrammetry software like metashape dont determines camera positions, but quality may be bad) [CUDA/CPU] - in downloads / source 

###-NOVEL VIEWS GENERATION BY IMAGES-

NERFStudio (splatfacto, nerfacto) [CUDA/CPU(cpu is extremely slow,but working)] - in downloads / source 

--------------------------------------------------------------

You can theoretically run these tools on windows 7, jut download this file and place it along with python.exe

--------------------------------------------------------------

Alternative downloads with torrents on Archive.org: https://archive.org/details/@takeonme1?tab=uploads

Page on civitai: https://civitai.com/models/104609
