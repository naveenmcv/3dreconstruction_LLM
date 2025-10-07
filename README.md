# 3dreconstruction_LLM

# Gaustudio / Kiri 3.12 - released in oct 2024.    2DGS milo released in Sept 2025


# REF
https://huggingface.co/papers/2311.04400
https://x.com/_akhaliq/status/1722466519253242263


# comfyUI
https://github.com/MrForExample/ComfyUI-3D-Pack



# 3dgs in omniverse
How to import 3DGS into Omniverse
https://www.youtube.com/watch?v=TDN0_jrLhGs

# 2DGS Latest ( sept 2025)
## milo
MILo: Mesh-In-the-Loop Gaussian Splatting for Detailed and Efficient Surface Reconstruction
https://github.com/Anttwo/MILo

# 2DGS - INSTEAD OF ELIPSOIDS use DISKS
2DGS: 2D Gaussian Splatting for Geometrically Accurate Radiance Fields
https://surfsplatting.github.io/
https://www.youtube.com/watch?v=oaHCtB6yiKU

# 2dgs important
https://github.com/Anttwo/MILo
https://www.youtube.com/watch?v=BUpDqXmSWBw
2D Gaussian Ray-Tracing is the future! - jan2025

https://www.youtube.com/watch?v=rOBs2yyYaJM

https://github.com/hbb1/2d-gaussian-splatting
https://github.com/hugoycj/2.5d-gaussian-splatting?tab=readme-ov-file

https://colab.research.google.com/drive/1qoclD7HJ3-o0O1R8cvV3PxLhoDCMsH8W?usp=sharing#scrollTo=pcWh0PVWT7iC
https://drive.google.com/drive/folders/1SJFgt8qhQomHX55Q4xSvYE2C6-8tFll9

https://arxiv.org/abs/2403.17888
3D Gaussian Splatting (3DGS) has recently revolutionized radiance field reconstruction, achieving high quality novel view synthesis and fast rendering speed without baking. However, 3DGS fails to accurately represent surfaces due to the multi-view inconsistent nature of 3D Gaussians. We present 2D Gaussian Splatting (2DGS), a novel approach to model and reconstruct geometrically accurate radiance fields from multi-view images. Our key idea is to collapse the 3D volume into a set of 2D oriented planar Gaussian disks. Unlike 3D Gaussians, 2D Gaussians provide view-consistent geometry while modeling surfaces intrinsically. To accurately recover thin surfaces and achieve stable optimization, we introduce a perspective-correct 2D splatting process utilizing ray-splat intersection and rasterization. Additionally, we incorporate depth distortion and normal consistency terms to further enhance the quality of the reconstructions. We demonstrate that our differentiable renderer allows for noise-free and detailed geometry reconstruction while maintaining competitive appearance quality, fast training speed, and real-time rendering.


# reddit
https://www.reddit.com/r/GaussianSplatting/comments/1ffpgtk/training_3dgs_models_based_on_a_dense_mesh/

https://www.themoonlight.io/en/review/gaustudio-a-modular-framework-for-3d-gaussian-splatting-and-beyond


https://huggingface.co/spaces/Stable-X/ReconViaGen

https://www.reddit.com/r/GaussianSplatting/comments/1iz9p7d/good_ways_to_convert_gaussian_splats_to_mesh/
I'd recommend checking up Houdini GSOPs plugin!

As far as I know, Kiri Engine is the only one that can do 3DGS to Mesh at the moment. The results look really good, but unfortunately, it is limited by filesize (I think 2GB is the limit), so the textures do come out muddy sometimes.
https://github.com/cgnomads/GSOPs


https://x.com/zhenjun_zhao
https://x.com/ychngji6


try
Could you get to a mesh with a dense point cloud from something like OpenMVS? I’m a newbie and self teaching. So this is just my barely know anything idea.
