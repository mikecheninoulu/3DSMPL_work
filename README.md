# Latest 3D SMPL related good papers and works


## skeleton or image to SMPL mesh

**[1] Pose2Mesh: Graph Convolutional Network for 3D Human Pose and Mesh Recovery from a 2D Human Pose**
- intro: ECCV 2020, skeleton to 3D pose
- DATASET: 3DPW, AMASS, frame level
- paper: [https://arxiv.org/abs/2008.09047](https://arxiv.org/abs/2008.09047)
- github: [https://github.com/hongsukchoi/Pose2Mesh_RELEASE](https://github.com/hongsukchoi/Pose2Mesh_RELEASE)

**[2] VIBE: Video Inference for Human Body Pose and Shape Estimation**
- intro: CVPR-2020, micheal black, VIBE
- framework: CNN + GRU for frame level SMPL parameters, discriminators for temporal learning.
- DATASET: AMASS, Human3.6M, 3DPW
- paper: [https://arxiv.org/abs/1912.05656](https://arxiv.org/abs/1912.05656)
- github: [https://github.com/mkocabas/VIBE](https://github.com/mkocabas/VIBE)

**[3] Beyond Static Features for Temporally Consistent 3D Human Pose and Shape from a Video**
- intro: CVPR 2021, based on VIBE, Demo is very good, have temporal constraints, it's actually just a smooth process
- dataset: Human3.6M, 3DPW
- paper: [https://arxiv.org/pdf/2011.08627v3.pdf](https://arxiv.org/pdf/2011.08627v3.pdf)
- github: [https://github.com/hongsukchoi/TCMR_RELEASE](https://github.com/hongsukchoi/TCMR_RELEASE)

**[4] Mesh Graphormer**
- intro: 04.2021 released, better than vibe, with a transformer
- dataset: Human3.6M, 3DPW
- arxiv: [https://arxiv.org/pdf/2104.00272.pdf](https://arxiv.org/pdf/2104.00272.pdf)

**[3] HybrIK: A Hybrid Analytical-Neural Inverse Kinematics Solution for 3D Human Pose and Shape Estimation**
- intro: CVPR2021, used detailed SMPL kinect functions, need human settings
- arxiv: [https://arxiv.org/pdf/2011.14672v3.pdf](https://arxiv.org/pdf/2011.14672v3.pdf)
- github: [https://github.com/Jeff-sjtu/HybrIK.](https://github.com/Jeff-sjtu/HybrIK.)

**[4] On Self-Contact and Human Pose**
- intro: CVPR 2021, to Prevent meshes from clipping into each other, SMPLify-DC
- paper: [https://arxiv.org/pdf/2104.03176.pdf](https://arxiv.org/pdf/2104.03176.pdf)
- project: https://tuch.is.tue.mpg.de/

**[5] PARE: Part Attention Regressor for 3D Human Body Estimation**
- intro: CVPR 2021, to Prevent meshes from clipping into each other, SMPLify-DC
- paper: [https://arxiv.org/pdf/2104.08527.pdf](https://arxiv.org/pdf/2104.08527.pdf)
- project: https://pare.is.tue.mpg.de/

https://arxiv.org/pdf/2104.13502.pdf
**Others**

**[1] Reconstructing 3D Human Pose by Watching Humans in the Mirror**
- intro: CVPR 2021 oral, NVIDIA, code hard, mirror setting
- paper: [https://arxiv.org/pdf/2104.00340.pdf](https://arxiv.org/pdf/2104.00340.pdf)
- github: [https://github.com/zju3dv/Mirrored-Human](https://github.com/zju3dv/Mirrored-Human)
- project: https://zju3dv.github.io/Mirrored-Human/

## 3D surface mapping SMPL with textures

**[1] Neural Surface Maps**
- intro: arxiv 2021, math in side is too hard
- paper: [https://arxiv.org/pdf/2103.16942.pdf](https://arxiv.org/pdf/2103.16942.pdf)
- project: http://geometry.cs.ucl.ac.uk/projects/2021/neuralmaps/

**[2] StylePeople: A Generative Model of Fullbody Human Avatars**
- intro: avatar with SMPLX
- paper: [https://arxiv.org/pdf/2104.08363.pdf](https://arxiv.org/pdf/2104.08363.pdf)
- project: https://saic-violet.github.io/style-people/


**[3] Pose-Guided Human Animation from a Single Image in the Wild**
- intro: densepose giuded pose animation
- paper: [https://arxiv.org/pdf/2012.03796.pdf](https://arxiv.org/pdf/2012.03796.pdf)
- code: https://www.youtube.com/watch?v=x7H0kKWzRFU&t=4s

# 3D model animation
**[1] SCANimate: Weakly Supervised Learning of Skinned Clothed Avatar Networks**
- intro: CVPR 2021 (Oral), person with cloth, make cloth scans animated
- project: [https://scanimate.is.tue.mpg.de/](https://scanimate.is.tue.mpg.de/)

**[2] Dynamic Surface Function Networks for Clothed Human Bodies**
- intro: from RGBD data to SMPL
- paper: [https://arxiv.org/pdf/2104.03978.pdf](https://arxiv.org/pdf/2104.03978.pdf)

**[3] SNARF: Differentiable Forward Skinning for Animating Non-Rigid Neural Implicit Shapes**
- intro: animation by put mesh into Learned Canonical 3D Shape and Skinning Weights
- paper: https://arxiv.org/pdf/2104.03953.pdf

**[4] Action-Conditioned 3D Human Motion Synthesis with Transformer VAE**
- intro: synthesis motion with transformer VAE
- paper: https://arxiv.org/abs/2104.05670
- project: https://imagine.enpc.fr/~petrovim/actor/

**[5] AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control**
- intro:  Transactions on Graphics (Proc. ACM SIGGRAPH 2021)
- paper: [https://xbpeng.github.io/projects/AMP/](https://xbpeng.github.io/projects/AMP/)
- code: https://github.com/xbpeng/DeepMimic

https://arxiv.org/pdf/2104.06950.pdf
https://arxiv.org/pdf/2012.09159.pdf

## SMPL series

**[1] SMPL**
- intro: basic SMPL

**[2] SMPLify**
- intro: SMPL with gender


**[3] SMPL H**
- intro: SMPL with hands

**[4] SMPL X**
- intro: SMPL with faces

## SMPL models registrations
**[1] NPMs: Neural Parametric Models for 3D Deformable Shapes**
- intro: an alternative to SMPL
- paper: [https://arxiv.org/pdf/2104.00702.pdf](https://arxiv.org/pdf/2104.00702.pdf)

**[2] Locally Aware Piecewise Transformation Fields for 3D Human Mesh Registration**
- intro: from PC to SMPL
- paper: [https://arxiv.org/pdf/2104.08160v1.pdf](https://arxiv.org/pdf/2104.08160v1.pdf)

**[3] Learning Implicit 3D Representations of Dressed Humans from Sparse Views**
- intro: from multi RGB to SMPL
- paper: [https://arxiv.org/pdf/2104.08013.pdf](https://arxiv.org/pdf/2104.08013.pdf)

**[4] SCALE: Modeling Clothed Humans with a Surface Codec of Articulated Local Element**
- intro: from point cloud  to dressed SMPL
- paper: [https://arxiv.org/pdf/2104.07660.pdf](https://arxiv.org/pdf/2104.07660.pdf)


## Video Generation Transformer

**[1] A Video Is Worth Three Views: Trigeminal Transformers for Video-based Person Re-identification**
- intro: make a video into three streams
- paper: [https://arxiv.org/pdf/2104.01745v1.pdf](https://arxiv.org/pdf/2104.01745v1.pdf)

**[2] 3D Human Pose Estimation with Spatial and Temporal Transformers**
- intro: arxiv 2021
- code: https://github.com/zczcwh/PoseFormer
- paper: [https://arxiv.org/pdf/2103.10455.pdf](https://arxiv.org/pdf/2103.10455.pdf)

**[3] Decoupled Spatial-Temporal Transformer for Video Inpainting**
- intro: 2021, 
- project: [https://arxiv.org/pdf/2104.06637.pdf](https://arxiv.org/pdf/2104.06637.pdf)
- code: https://github.com/ruiliu-ai/DSTT.

Higher Order Recurrent Space-Time Transformer

## SMPL handling tools
TBD


| Updated: 2021/04/30|
| :---------: |

