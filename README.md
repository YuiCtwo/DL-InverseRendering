# DL-InverseRendering
Previous work on Deep Learning based Inverse Rendering

(L): Light Estimation, (M): Material Estimation, (G) Geometry Estimation

## Flat Material

|Year|Paper|Code|
|-|-|-|
|2021|[SurfaceNet: Adversarial SVBRDF Estimation from a Single Image](https://openaccess.thecvf.com/content/ICCV2021/html/Vecchio_SurfaceNet_Adversarial_SVBRDF_Estimation_From_a_Single_Image_ICCV_2021_paper.html)|[Code](https://github.com/perceivelab/surfacenet)|
|2016|[Reflectance Modeling by Neural Texture Synthesis](https://mediatech.aalto.fi/publications/graphics/NeuralSVBRDF/)||
|2017|[Modeling Surface Appearance from a Single Photograph using Self-augmented Convolutional Neural Networks](https://arxiv.org/abs/1809.00886)|[Code](https://github.com/msraig/self-augmented-net)|
|2018|[Single-Image SVBRDF Capture with a Rendering-Aware Deep Network](https://arxiv.org/abs/1810.09718)|[Code & Dataset](https://repo-sam.inria.fr/fungraph/deep-materials/)|
|2020|[MaterialGAN: Reflectance Capture using a Generative SVBRDF Model](https://shuangz.com/projects/materialgan-sa20/)|[Code](https://github.com/tflsguoyu/materialgan)|


## Single Object

|Year|Paper|Code|L|G|M|
|-|-|-|-|-|-|
|2020|[NeRD-Neural-Reflectance-Decomposition](https://arxiv.org/abs/2012.03918)|[Code](https://github.com/cgtuebingen/nerd-neural-reflectance-decomposition)|&#10003;|&#10003;|&#10003;|
|2021|[Neural-PIL: Neural Pre-Integrated Lighting for Reflectance Decomposition](https://arxiv.org/abs/2110.14373)|[Code](https://github.com/cgtuebingen/Neural-PIL)|&#10003;|&#10003;|&#10003;|
|2021|[NeRFactor: Neural Factorization of Shape and Reflectance Under an Unknown Illumination](https://arxiv.org/abs/2106.01970)|[Code](https://github.com/google/nerfactor)|&#10003;|&#10003;|&#10003;|
|2022|[PS-NeRF: Neural Inverse Rendering for Multi-view Photometric Stereo](https://arxiv.org/abs/2207.11406)|[Code](https://github.com/ywq/psnerf)||&#10003;|&#10003;|
|2022|[IRON: Inverse Rendering by Optimizing Neural SDFs and Materials from Photometric Images](https://arxiv.org/abs/2204.02232)|[Code](https://github.com/Kai-46/IRON)||&#10003;|&#10003;|
|2022|[NDJIR: Neural Direct and Joint Inverse Rendering for Geometry, Lights, and Materials of Real Object](https://arxiv.org/abs/2302.00675)|[Code](https://github.com/sony/ndjir)||&#10003;|&#10003;|
|2021|[PhySG: Inverse Rendering with Spherical Gaussians for Physics-based Material Editing and Relighting](https://kai-46.github.io/PhySG-website/)|[Code](https://github.com/Kai-46/PhySG)|&#10003;|&#10003;|&#10003;|
|2020|[Single-Shot Neural Relighting and SVBRDF Estimation](https://cseweb.ucsd.edu/~viscomp/projects/ECCV20NeuralRelighting/)|[Code](https://github.com/ssangx/NeuralRelighting)||&#10003;|&#10003;|
|2021|[Shape and Material Capture at Home](https://arxiv.org/abs/2104.06397)|[Code](https://github.com/dlichy/ShapeAndMaterial)||&#10003;|&#10003;|
|2020|[Deep 3D Capture: Geometry and Reflectance from Sparse Multi-View Images](https://openaccess.thecvf.com/content_CVPR_2020/papers/Bi_Deep_3D_Capture_Geometry_and_Reflectance_From_Sparse_Multi-View_Images_CVPR_2020_paper.pdf)|||&#10003;|&#10003;|
|2021|[Unified Shape and SVBRDF Recovery using Differentiable Monte Carlo Rendering](https://arxiv.org/abs/2103.15208)|||&#10003;|&#10003;|
|2022|[Modeling Indirect Illumination for Inverse Rendering](https://zju3dv.github.io/invrender/)|[Code](https://github.com/zju3dv/invrender)|&#10003;|&#10003;|&#10003;|
|2022|[DIP: Differentiable Interreflection-aware Physics-based Inverse Rendering](https://denghilbert.github.io/dip/)|[Code](https://github.com/denghilbert/DIP)|&#10003;|&#10003;|&#10003;|

## Indoor Scene

|Year|Paper|Code|L|G|M|
|-|-|-|-|-|-|
|2022|[IRISformer: Dense Vision Transformers for Single-Image Inverse Rendering in Indoor Scenes](https://arxiv.org/abs/2206.08423)|[Code](https://github.com/Morpheus3000/PIE-Net)|&#10003;|&#10003;|&#10003;|
|2020|[Inverse Rendering for Complex Indoor Scenes: Shape, Spatially-Varying Lighting and SVBRDF from a Single Image](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/)|[Code](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/)|&#10003;|&#10003;|&#10003;|
|2017|[Learning to Predict Indoor Illumination from a Single Image](https://arxiv.org/abs/1704.00090)|[Dataset](http://indoor.hdrdb.com/)|&#10003;|||
|2018|[Learning to Estimate Indoor Lighting from 3D Objects](https://arxiv.org/abs/1806.03994)|[Code](https://github.com/weberhen/learning_indoor_lighting)|&#10003;|||
|2019|[Fast Spatially-Varying Indoor Lighting Estimation](https://arxiv.org/abs/1906.03799)|[Dataset](https://lvsn.github.io/fastindoorlight/)|&#10003;||&#10003;|
|2019|[Neural Illumination: Lighting Prediction for Indoor Environments](https://illumination.cs.princeton.edu/)|[Dataset](https://niessner.github.io/Matterport/)|&#10003;|&#10003;||
|2020|[Lighthouse: Predicting Lighting Volumes for Spatially-Coherent Illumination](https://people.eecs.berkeley.edu/~pratul/lighthouse/)|[Code](https://github.com/pratulsrinivasan/lighthouse)|&#10003;|||
|2020|[Object-Based Illumination Estimation with Rendering-Aware Neural Networks](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600375.pdf)||&#10003;||&#10003;|
|2021|[Learning Indoor Inverse Rendering with 3D Spatially-Varying Lighting](https://nv-tlabs.github.io/inverse-rendering-3d-lighting/)||&#10003;|&#10003;||
|2021|[EMLight: Lighting Estimation via Spherical Distribution Approximation](https://arxiv.org/abs/2012.11116)||&#10003;|||
|2018|[Learning to Predict Indoor Illumination from a Single Image](https://cseweb.ucsd.edu/~viscomp/projects/SIGA18ShapeSVBRDF/)|[Code](https://github.com/lzqsd/SingleImageShapeAndSVBRDF)||&#10003;|&#10003;|
|2021|[Material and Lighting Reconstruction for Complex Indoor Scenes with Texture-space Differentiable Rendering](http://rgl.epfl.ch/publications/NimierDavid2021Material)||&#10003;|&#10003;||

## Human

|Year|Paper|Code|
|-|-|-|
|2018|[Relighting Humans: Occlusion-Aware Inverse Rendering for Full-Body Human Images](http://kanamori.cs.tsukuba.ac.jp/projects/relighting_human/)|[Code](http://kanamori.cs.tsukuba.ac.jp/projects/relighting_human/)|
|2019|[Single Image Portrait Relighting](https://arxiv.org/abs/1905.00824)||
|2020|[Learning Physics-Guided Face Relighting Under Directional Light](https://openaccess.thecvf.com/content_CVPR_2020/html/Nestmeyer_Learning_Physics-Guided_Face_Relighting_Under_Directional_Light_CVPR_2020_paper.html)||
|2020|[Single Image Portrait Relighting via Explicit Multiple Reflectance Channel Modeling](https://dl.acm.org/doi/abs/10.1145/3414685.3417824)|[Dataset](https://sireer.github.io/projects/FLM_project/)|
|2021|[Relighting Images in the Wild with a Self-Supervised Siamese Auto-Encoder](https://openaccess.thecvf.com/content/WACV2021/html/Liu_Relighting_Images_in_the_Wild_With_a_Self-Supervised_Siamese_Auto-Encoder_WACV_2021_paper.html)||
|2021|[Monocular Reconstruction of Neural Face Reflectance Fields](https://arxiv.org/abs/2008.10247)||
|2021|[Learning to Relight Portraits for Background Replacement](https://augmentedperception.github.io/total_relighting/)||
|2021|[Neural Video Portrait Relighting in Real-time via Consistency Modeling](https://zhanglongwen.com/projects/nvpr/)|[Code](https://github.com/ZoneLikeWonderland/Neural-Video-Portrait-Relighting-in-Real-time-via-Consistency-Modeling) & [Dataset](https://zhanglongwen.com/projects/nvpr/dataset.html)|

## Acknowledgement
This repo is inspired by [Awesome-InverseRendering](https://github.com/tkuri/Awesome-InverseRendering) and relate survey: [A Survey on Intrinsic Images: Delving Deep Into Lambert and Beyond](https://arxiv.org/abs/2112.03842)