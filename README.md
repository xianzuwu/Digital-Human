# Digital Human

A collection of recent methods on Digital Human. There are mainly 2 kinds for Digital Human:

-   2D Digital Human
    -   Avatars: AnimateDiff
    -   realistic: EMO,
    - Efficient 2D Human(single-view/real-time): AnimateDiff

-   3D Digital Human
    -   3D Avatars:
        -   AvatarGAN
    -   realistic 3d model
        -   realistic: SMPL, SMPL-X
    - Efficient 3D Human(single-view/real-time):


Note, this repo is more about Avatars and realistic human generation. For other topics like reconstruction, see more comprehensive collections (## Related Repos and Websites) at the end of this file. Welcome to send a pull request if you'd like to add any pertinent papers.

Other repos:

incoming soon

> About abbreviation: In the list below, `o` for oral, `s` for spotlight, `b` for best paper, `w` for workshop.

<details><summary>Table of Contents</summary><p>

- [3D Human Avatar Generation and Animation](#3d-human-avatar-generation-and-animation)
- [3D Head Animatable Avatar (from 2D Image Collections)](#3d-head-animatable-avatar--from-2d-image-collections-)
- [Clothed Human Digitalization](#clothed-human-digitalization)
- [Efficent 3d human](#Efficent-3d-human)
- [Human Image and Video Generation](#human-image-and-video-generation)
- [Dataset](#Datasets)
-  [Related Repos and Websites](#Related-Repos-and-Websites)



</p></details><p></p>

## 3D Human Avatar Generation and Animation

**Emotional Speech-driven 3D Body Animation Via Disentangled Latent Diffusion.**<br>
*Kiran Chhatre, Radek Daněček, Nikos Athanasiou, Giorgio Becherini, Christopher Peters, Michael J. Black, Timo Bolkart.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.04466)]

**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos.**<br>
*Shoukang Hu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02973v1)] [[Project](https://skhu101.github.io/GauHuman/)] [[Code](https://github.com/skhu101/GauHuman)]

**HumanNorm: Learning Normal Diffusion Model for High-quality and Realistic 3D Human Generation.**<br>
*Xin Huang, Ruizhi Shao, Qi Zhang, Hongwen Zhang, Ying Feng, Yebin Liu, Qing Wang..*<br> 
CVPR 2024. [[PDF]()] [[Project](https://humannorm.github.io/)]

**StyleAvatar3D: Leveraging Image-Text Diffusion Models for High-Fidelity 3D Avatar Generation.**<br>
*Chi Zhang, Yiwen Chen, Yijun Fu, Zhenglin Zhou, Gang YU, Billzb Wang, Bin Fu, Tao Chen, Guosheng Lin, Chunhua Shen.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.19012)] [[Project](https://x-zhangyang.github.io/2023_Get3DHuman/)] [[Code](https://github.com/icoz69/StyleAvatar3D)]

## 3D Head Animatable Avatar (from 2D Image Collections)

**Efficient Meshy Neural Fields for Animatable Human Avatars.**<br>
*Xiaoke Huang, Yiji Cheng, Yansong Tang, Xiu Li, Jie Zhou, Jiwen Lu .*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.12965)] [[Project](https://xk-huang.github.io/ema/)]

## Clothed Human Digitalization

**AvatarCap: Animatable Avatar Conditioned Monocular Human Volumetric Capture.**<br>
*Zhe Li, Zerong Zheng, Hongwen Zhang, Chaonan Ji, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.02031)] [[Project](http://www.liuyebin.com/avatarcap/avatarcap.html)]

**OcclusionFusion: Occlusion-aware Motion Estimation for Real-time Dynamic 3D Reconstruction.**<br>
*[Wenbin Lin](https://wenbin-lin.github.io/), Chengwei Zheng, Jun-Hai Yong, Feng Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2203.07977.pdf)] [[Project](https://wenbin-lin.github.io/OcclusionFusion/)]

**SelfRecon: Self Reconstruction Your Digital Avatar from Monocular Video.**<br>
*[Boyi Jiang](https://scholar.google.com/citations?user=lTlZV8wAAAAJ&hl=zh-CN), Yang Hong, Hujun Bao, Juyong Zhang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.12792)] [[Project](https://jby1993.github.io/SelfRecon/)]

## Efficent 3d human

**FlashAvatar: High-Fidelity Digital Avatar Rendering at 300FPS.**<br>
*Jun Xiang, Xuan Gao, Yudong Guo, Juyong Zhang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02214v1)] [[Project](https://ustc3dv.github.io/FlashAvatar/)]

**PINA: Learning a Personalized Implicit Neural Avatar from a Single RGB-D Video Sequence.**<br>
*Zijian Dong, Chen Guo, Jie Song, Xu Chen, Andreas Geiger, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01754)] [[Project](https://zj-dong.github.io/pina/)]

**High-Fidelity Human Avatars from a Single RGB Camera.**<br>
*Hao Zhao, [Jinsong Zhang](https://zhangjinso.github.io/), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai/), [Zerong Zheng](https://zhengzerong.github.io/), Yingdi Xie, [Yebin Liu](http://www.liuyebin.com/), [Kun Li](http://cic.tju.edu.cn/faculty/likun/).*<br>
CVPR 2022. [[PDF](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/assets/main.pdf)] [[Project](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/index.html)] [[Project](https://github.com/hzhao1997/HF-Avatar)] [[Data](https://drive.google.com/file/d/1qh1dj5ZoUBst_02UJY7IWstQMhb8L5IA/view?usp=sharing)]

## Human Image and Video Generation

**AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning.**<br>
*Yuwei Guo, Ceyuan Yang, Anyi Rao, Zhengyang Liang, Yaohui Wang, Yu Qiao, Maneesh Agrawala, Dahua Lin, Bo Dai.*<br> 
ICLR 2024 [[PDF](https://arxiv.org/abs/2307.04725)] [[Project](https://github.com/guoyww/AnimateDiff)]

**HyperHuman: Hyper-Realistic Human Generation with Latent Structural Diffusion.**<br>
*Xian Liu, Jian Ren, Aliaksandr Siarohin, Ivan Skorokhodov, Yanyu Li, Dahua Lin, Xihui Liu, Ziwei Liu, Sergey Tulyakov.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08579)] [[Project](https://snap-research.github.io/HyperHuman/)]

**StyleGAN-Human: A Data-Centric Odyssey of Human Generation.**<br>
*Jianglin Fu, Shikai Li, [Yuming Jiang](https://yumingj.github.io/), [Kwan-Yee Lin](https://kwanyeelin.github.io/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=zh-CN), [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/), [Wayne Wu](https://dblp.org/pid/50/8731.html), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.11823)] [[Code](https://youtu.be/nIrb9hwsdcI)] [[Project](https://stylegan-human.github.io/)] [[Colab Demo](https://colab.research.google.com/drive/1sgxoDM55iM07FS54vz9ALg1XckiYA2On)] [[Hugging Face Demo](https://huggingface.co/spaces/hysts/StyleGAN-Human)]

## Datasets
- Fashionpedia. [[Website]](https://fashionpedia.github.io/home/index.html)
- DeepFashion2 Dataset. [[Website]](<https://github.com/switchablenorms/DeepFashion2>)
- DeepFashion Dataset. [[Website]](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
- FashionGen. [[Website]](https://fashion-gen.com/)
- FashionAI. [[Tianchi]](http://fashionai.alibaba.com/datasets/?spm=a2c22.11190735.991137.8.501b6d83ilPJsX)
- TaobaoClothMatch. [[Tianchi]](TaobaoClothMatch)
- Fashion-MNIST. [[Fashion-MNIST]](https://github.com/zalandoresearch/fashion-mnist)
- Fashion IQ. [[Website]](https://www.spacewu.com/posts/fashion-iq/)
- NTURGBD-Parsing-4K Dataset. [[Website](https://github.com/hongfz16/HCMoCo)]
- Efficient Person Dataset
  - People-Snapshot 
  -  ZJU-MoCap
  - MonoperfCap

## Related Repos and Websites

-   [Awesome-Avatars](https://github.com/pansanity666/Awesome-Avatars)
-   [awesome-digital-human](https://github.com/weihaox/awesome-digital-human)
-   [awesome-3d-human-reconstruction](https://github.com/rlczddl/awesome-3d-human-reconstruction)

