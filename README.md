<div align=center>

# Awesome Video Generation Post Training

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PDF](https://img.shields.io/badge/PDF-GitHub-blue.svg)](https://github.com/CyL97/Awesome-Video-Generation-Post-Training/blob/main/paper/Video_Generation_Post_Training_Survey.pdf)
<!-- [![arXiv](https://img.shields.io/badge/arXiv-xxxx.xxxxx-b31b1b.svg?logo=arXiv)]() 
[![hf_paper](https://img.shields.io/badge/🤗-Paper%20In%20HF-red.svg)]() -->

</div>

> ## [**Video Generation Models: A Survey of Post-Training and Alignment**]()  
> [Chaoyu Li](https://chaoyuli.com/)<sup>1,†,✉️</sup>,
> [Xiaoyi Gu](https://alleria1809.github.io/)<sup>2,†</sup>,
> [Yogesh Kulkarni](https://yogkul2000.github.io/)<sup>1</sup>,
> [Eun Woo Im](https://eunwooim.github.io/)<sup>1</sup>,
> [Mohammadmahdi Honarmand](https://scholar.google.com/citations?user=s0mTGYkAAAAJ&hl=en)<sup>3</sup>,
> [Zeyu Wang](https://www.linkedin.com/in/zeyu-wang-jasper/)<sup>4</sup>,
> [Juntong Song](https://scholar.google.com/citations?user=ZLeZfM4AAAAJ&hl=en)<sup>5</sup>,
> [Fei Du](https://www.linkedin.com/in/fei-du-558260229/)<sup>6</sup>,
> [Xilin Jiang](https://xi-j.github.io/)<sup>7</sup>,
> [Kexin Zheng](https://kellyzhengusc.github.io/)<sup>8</sup>,
> [Tianzhi Li](https://www.linkedin.com/in/androli/)<sup>9</sup>,
> [Fei Tao](https://scholar.google.com/citations?user=KhWMky4AAAAJ&hl=en)<sup>5</sup>,
> [Pooyan Fazli](https://pooyanfazli.com/)<sup>1,✉️</sup>  
>
> <sup>1</sup>Arizona State University ·
> <sup>2</sup>Twitch ·
> <sup>3</sup>Stanford University ·
> <sup>4</sup>eBay ·
> <sup>5</sup>NewsBreak ·
> <sup>6</sup>Microsoft ·
> <sup>7</sup>Columbia University ·
> <sup>8</sup>University of Southern California ·
> <sup>9</sup>Carnegie Mellon University  
>
> <sup>†</sup>Equal contribution. <sup>✉️</sup>Corresponding author: [Chaoyu Li](mailto:chaoyuli@asu.edu) , [Pooyan Fazli](mailto:pooyan@asu.edu).

![timeline](figures/timeline.png)

---

> [!IMPORTANT]
> We welcome your help in improving the repository and paper. Please feel free to submit a [pull request]() to:
> - Add a relevant paper not yet included.
> - Suggest a more suitable category.
> - Update the information.
> - Ask for clarification about any content.

---

## 🔥 News

- **[2026.xx.xx]** The v1 survey is now published! We have also initialized the repository.

## 🎯 Motivation
![teaser](figures/teaser.png)
While large-scale pretraining has significantly improved video generation models, aligning them with human intent, physical constraints, and deployment requirements remains a major challenge. As a result, post-training and alignment techniques have rapidly become a central research focus in modern video generation.

In our survey paper, we systematically review recent progress in supervised fine-tuning, self-training and distillation, preference-based optimization, and inference-time alignment methods.

This repository serves as a companion resource to the survey.  
It aims to:

- 📚 Curate recent papers on post-training and alignment for video generation  
- 📊 Collect datasets and evaluation benchmarks related to post-training and alignment

We hope this repository provides researchers and practitioners with a convenient, up-to-date reference for exploring the evolving landscape of post-training and alignment in video generation models.

## 📌 Citation 

If you find our paper or this resource helpful, please consider cite:

```bibtex
@article{,
  title={},
  author={},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2026}
}
```

## 📚 Content

- [Awesome Video Generation Post Training](#)
    - [Datasets](#datasets)
    - [Benchmarks](#benchmarks)
    - [Conference Papers](#conference-papers)
    - [arXiv Papers](#arXiv-papers)

---

### Datasets

| **Dataset** | **Year** | **Links** |
| --- | --- | :---: |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) ChronoMagic-Pro | 2024 | [Paper](https://arxiv.org/abs/2406.18522) · [GitHub](https://github.com/PKU-YuanGroup/ChronoMagic-Bench) · [Website](https://pku-yuangroup.github.io/ChronoMagic-Bench/) · [Dataset](https://huggingface.co/datasets/BestWishYsh/ChronoMagic-Pro) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) SafeSora | 2024 | [Paper](https://arxiv.org/abs/2406.14477) · [GitHub](https://github.com/PKU-Alignment/safe-sora) · [Website](https://sites.google.com/view/safe-sora) · [Dataset](https://huggingface.co/datasets/PKU-Alignment/SafeSora) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) TIP-I2V | 2025 | [Paper](https://arxiv.org/abs/2411.04709) · [GitHub](https://github.com/WangWenhao0716/TIP-I2V) · [Website](https://tip-i2v.github.io/) · [Dataset](https://huggingface.co/datasets/WenhaoWang/TIP-I2V) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) SynFMC | 2025 | [Paper](https://arxiv.org/abs/2501.01425) · [GitHub](https://github.com/FudanCVL/SynFMC) · [Website](https://henghuiding.com/SynFMC/) · [Dataset](https://huggingface.co/datasets/XinchengShuai/SynFMC) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) CookGen | 2025 | [Paper](https://arxiv.org/abs/2501.06173) · [Website](https://videoauteur.github.io/) · [Dataset](https://huggingface.co/datasets/lambertxiao/CookGen_youcook2) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) HOIGen-1M | 2025 | [Paper](https://arxiv.org/abs/2503.23715) · [Website](https://liuqi-creat.github.io/HOIGen.github.io/) · [Dataset](https://huggingface.co/datasets/HOIGen/HOIGen-1M) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) OpenHumanVid | 2025 | [Paper](https://arxiv.org/abs/2412.00115) · [GitHub](https://github.com/fudan-generative-vision/OpenHumanVid) · [Website](https://fudan-generative-vision.github.io/OpenHumanVid/#/) |
| ![ICML](https://img.shields.io/badge/ICML-indigo) PhyWorld | 2025 | [Paper](https://arxiv.org/abs/2411.02385) · [GitHub](https://github.com/phyworld/phyworld) · [Website](https://phyworld.github.io/) · [Dataset](https://huggingface.co/datasets/magicr/phyworld) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) WISA-80K | 2025 | [Paper](https://arxiv.org/abs/2503.08153) · [GitHub](https://github.com/360CVGroup/WISA) · [Website](https://360cvgroup.github.io/WISA/) · [Dataset](https://huggingface.co/datasets/qihoo360/WISA-80K) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) VideoUFO | 2025 | [Paper](https://arxiv.org/abs/2503.01739) · [GitHub](https://github.com/WangWenhao0716/BenchUFO) · [Dataset](https://huggingface.co/datasets/WenhaoWang/VideoUFO) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) TalkCuts | 2025 | [Paper](https://arxiv.org/abs/2510.07249) · [GitHub](https://github.com/UMass-Embodied-AGI/TalkCuts) · [Website](https://talkcuts.github.io/) · [Dataset](https://docs.google.com/forms/d/e/1FAIpQLSfapK7pqgyrcCaOxJn8yQc79AYaq1DOvJzL0-VZnLiA3CvpyQ/viewform) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) EgoVid-5M | 2025 | [Paper](https://arxiv.org/abs/2411.08380) · [GitHub](https://github.com/JeffWang987/EgoVid) · [Website](https://egovid.github.io/) · [Dataset](https://modelscope.cn/datasets/iic/EgoVid/) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) OpenS2V-5M | 2025 | [Paper](https://arxiv.org/abs/2505.20292) · [GitHub](https://github.com/PKU-YuanGroup/OpenS2V-Nexus) · [Website](https://pku-yuangroup.github.io/OpenS2V-Nexus/) · [Dataset](https://huggingface.co/datasets/BestWishYsh/OpenS2V-5M) |
| ![PMLR](https://img.shields.io/badge/PMLR-gold) GRADEO-Instruct | 2025 | [Paper](https://arxiv.org/abs/2503.02341) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) CI-VID | 2025 | [Paper](https://arxiv.org/abs/2505.18078) · [GitHub](https://github.com/ymju-BAAI/CI-VID) · [Dataset](https://huggingface.co/datasets/BAAI/CI-VID) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PNData | 2025 | [Paper](https://arxiv.org/abs/2506.16119) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PairFS-4K | 2025 | [Paper](https://arxiv.org/abs/2505.18078) · [GitHub](https://github.com/yisuanwang/DanceTog) · [Website](https://dancetog.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DAVID-X | 2025 | [Paper](https://arxiv.org/abs/2506.14827) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Dprim | 2025 | [Paper](https://arxiv.org/abs/2508.20840) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MMVideo | 2025 | [Paper](https://arxiv.org/abs/2507.01938) · [GitHub](https://github.com/Tele-AI/CtrlVDiff) · [Website](https://tele-ai.github.io/CtrlVDiff) |

### Benchmarks

| **Benchmark** | **Year** | **Links** |
| --- | --- | :---: |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) FETV | 2023 | [Paper](https://arxiv.org/abs/2311.01813) · [GitHub](https://github.com/llyx97/FETV) · [Dataset](https://huggingface.co/datasets/lyx97/FETV) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) StoryBench | 2023 | [Paper](https://arxiv.org/abs/2308.11606) · [GitHub](https://github.com/google/storybench) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) ChronoMagic-Bench | 2024 | [Paper](https://arxiv.org/abs/2406.18522) · [GitHub](https://github.com/PKU-YuanGroup/ChronoMagic-Bench) · [Website](https://pku-yuangroup.github.io/ChronoMagic-Bench/) · [Dataset](https://huggingface.co/datasets/BestWishYsh/ChronoMagic-Bench) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) EvalCrafter | 2024 | [Paper](https://arxiv.org/abs/2310.11440) · [GitHub](https://github.com/EvalCrafter/EvalCrafter) · [Website](https://evalcrafter.github.io/) · [Dataset](https://huggingface.co/datasets/RaphaelLiu/EvalCrafter_T2V_Dataset) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) VBench | 2024 | [Paper](https://arxiv.org/abs/2311.17982) · [GitHub](https://github.com/Vchitect/VBench) · [Website](https://vchitect.github.io/VBench-project/) · [Dataset](https://drive.google.com/drive/folders/1on66fnZ8atRoLDimcAXMxSwRxqN8_0yS) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) T2VSafetyBench | 2024 | [Paper](https://arxiv.org/abs/2407.05965) · [GitHub](https://github.com/yibo-miao/T2VSafetyBench) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) MTBench | 2025 | [Paper](https://arxiv.org/abs/2503.17350) · [GitHub](https://github.com/Shi-qingyu/DeT) · [Website](https://shi-qingyu.github.io/DeT.github.io/) · [Dataset](https://huggingface.co/datasets/QingyuShi/MTBench) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) FiVE | 2025 | [Paper](https://arxiv.org/abs/2503.13684) · [GitHub](https://github.com/MinghanLi/FiVE-Bench) · [Website](https://sites.google.com/view/five-benchmark) · [Dataset](https://huggingface.co/datasets/LIMinghan/FiVE-Fine-Grained-Video-Editing-Benchmark) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) VEG-Bench | 2025 | [Paper](https://arxiv.org/abs/2503.14350) · [GitHub](https://github.com/Yui010206/VEGGIE-VidEdit/) · [Website](https://veggie-gen.github.io/) · [Dataset](https://huggingface.co/datasets/Shoubin/VEGGIE-Bench) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) VMBench | 2025 | [Paper](https://arxiv.org/abs/2503.10076) · [GitHub](https://github.com/AMAP-ML/VMBench) · [Website](https://amap-ml.github.io/VMBench-Website/) · [Dataset](https://huggingface.co/GD-ML/VMBench) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) T2V-CompBench | 2025 | [Paper](https://arxiv.org/abs/2407.14505) · [GitHub](https://github.com/KaiyueSun98/T2V-CompBench) · [Website](https://t2v-compbench-2025.github.io/) · [Dataset](https://huggingface.co/datasets/Kaiyue/T2V-CompBench-Videos) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) StoryEval | 2025 | [Paper](https://arxiv.org/abs/2412.16211) · [GitHub](https://github.com/ypwang61/StoryEval) · [Website](https://ypwang61.github.io/project/StoryEval/) · [Dataset](https://drive.google.com/drive/u/0/folders/1fpvSOmPMQ0jcYyZJ0G6rweKKe-2fbATn) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) MC-Bench | 2025 | [Paper](https://arxiv.org/abs/2505.20287) · [GitHub](https://github.com/HiDream-ai/MotionPro) · [Website](https://zhw-zhang.github.io/MotionPro-page/) · [Dataset](https://huggingface.co/HiDream-ai/MotionPro/tree/main) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Video-Bench | 2025 | [Paper](https://arxiv.org/abs/2504.04907) · [GitHub](https://github.com/Video-Bench/Video-Bench) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) MJ-BENCH-VIDEO | 2025 | [Paper](https://arxiv.org/abs/2502.01719) · [GitHub](https://github.com/aiming-lab/MJ-Video) · [Website](https://aiming-lab.github.io/MJ-VIDEO.github.io/) · [Dataset](https://huggingface.co/datasets/MJ-Bench/MJ-BENCH-VIDEO) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) OpenS2V-Eval | 2025 | [Paper](https://arxiv.org/abs/2505.20292) · [GitHub](https://github.com/PKU-YuanGroup/OpenS2V-Nexus) · [Website](https://pku-yuangroup.github.io/OpenS2V-Nexus/) · [Dataset](https://huggingface.co/datasets/BestWishYsh/OpenS2V-Eval) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) VideoGen-RewardBench | 2025 | [Paper](https://arxiv.org/abs/2501.13918) · [GitHub](https://github.com/KlingTeam/VideoAlign) · [Website](https://gongyeliu.github.io/videoalign/) · [Dataset](https://huggingface.co/datasets/KlingTeam/VideoGen-RewardBench) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) AIGC-LipSync | 2025 | [Paper](https://arxiv.org/abs/2505.21448) · [Website](https://ziqiaopeng.github.io/OmniSync/) · [Dataset](https://huggingface.co/datasets/ZiqiaoPeng/AIGC_LipSync_Benchmark) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) WorldModelBench | 2025 | [Paper](https://arxiv.org/abs/2502.20694) · [GitHub](https://github.com/WorldModelBench-Team/WorldModelBench/tree/main?tab=readme-ov-file#evaluation) · [Website](https://worldmodelbench-team.github.io/) · [Dataset](https://huggingface.co/datasets/Efficient-Large-Model/worldmodelbench) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) VIP-200K | 2025 | [Paper](https://dl.acm.org/doi/10.1145/3746027.3761987) · [Website](https://hidream-ai.github.io/ipvg-challenge.github.io/) · [Dataset](https://huggingface.co/datasets/HiDream-ai/VIP-200K) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) RGCD | 2025 | [Paper](https://arxiv.org/abs/2506.23852) · [GitHub](https://github.com/IntMeGroup/RGC-VQA) · [Dataset](https://pan.baidu.com/share/init?surl=ebpoA3-DRi3XhT6d68Bf4A&pwd=hab7) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) RecipeGen | 2025 | [Paper](https://arxiv.org/abs/2506.06733) · [Dataset](https://huggingface.co/datasets/RUOXUAN123/RecipeGen) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) HVEval | 2025 | [Paper](https://dl.acm.org/doi/10.1145/3746027.3758299) |
| ![EMNLP](https://img.shields.io/badge/EMNLP-darkorange) Doc2Present | 2025 | [Paper](https://arxiv.org/abs/2507.04036) · [GitHub](https://github.com/AIGeeksGroup/PresentAgent) · [Dataset](https://huggingface.co/datasets/AIGeeksGroup/Doc2Present) |
| ![ACL](https://img.shields.io/badge/ACL-%23FF6347) VidCapBench | 2025 | [Paper](https://arxiv.org/abs/2502.12782) · [GitHub](https://github.com/VidCapBench/VidCapBench) · [Dataset](https://huggingface.co/datasets/VidCapBench/VidCapBench) |
| ![ICLR](https://img.shields.io/badge/ICLR-teal) VideoPhy | 2025 | [Paper](https://openreview.net/forum?id=9D2QvO1uWj) · [GitHub](https://github.com/Hritikbansal/videophy) · [Dataset](https://huggingface.co/datasets/videophysics/videophy_test_public) |
| ![ICML](https://img.shields.io/badge/ICML-indigo) PhyGenBench | 2025 | [Paper](https://arxiv.org/abs/2410.05363) · [GitHub](https://github.com/OpenGVLab/PhyGenBench) · [Website](https://phygenbench123.github.io/) · [Dataset](https://huggingface.co/datasets/phygenbench/phygenbench) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Paper2Video | 2025 | [Paper](https://arxiv.org/abs/2510.05096) · [GitHub](https://github.com/showlab/Paper2Video) · [Website](https://showlab.github.io/Paper2Video/) · [Dataset](https://huggingface.co/datasets/ZaynZhu/Paper2Video) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PhyWorldBench | 2025 | [Paper](https://arxiv.org/abs/2507.13428) · [GitHub](https://github.com/g-jing/phy-world-bench) · [Dataset](https://huggingface.co/datasets/phyworldbench/phyworldbench) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SafeMVDrive | 2025 | [Paper](https://arxiv.org/abs/2505.17727) · [GitHub](https://github.com/zhoujiawei3/SafeMVDrive) · [Website](https://zhoujiawei3.github.io/SafeMVDrive/) · [Dataset](https://huggingface.co/datasets/JiaweiZhou/SafeMVDrive) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SeqBench | 2025 | [Paper](https://arxiv.org/abs/2510.13042) · [GitHub](https://github.com/TangZhengxu/SeqBench-Benchmarking-Sequential-Narrative-Generation-in-Text-to-Video-Models) · [Website](https://videobench.github.io/SeqBench.github.io/) · [Dataset](https://huggingface.co/datasets/AcmmmVideobench/Acmmm2025_video_benchmark) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) VideoVerse | 2025 | [Paper](https://arxiv.org/abs/2510.08398) · [GitHub](https://github.com/Zeqing-Wang/VideoVerse) · [Website](https://www.naptmn.cn/Homepage_of_VideoVerse/) · [Dataset](https://huggingface.co/datasets/NNaptmn/VideoVerse) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) AIGVE-60K | 2025 | [Paper](https://arxiv.org/abs/2505.12098) · [GitHub](https://github.com/IntMeGroup/LOVE) · [Dataset](https://huggingface.co/datasets/anonymousdb/AIGVE-60K) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MMMC | 2025 | [Paper](https://arxiv.org/abs/2510.01174) · [GitHub](https://github.com/showlab/Code2Video/) · [Website](https://showlab.github.io/Code2Video/) · [Dataset](https://huggingface.co/datasets/YanzheChen/MMMC) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DynamicEval | 2025 | [Paper](https://arxiv.org/abs/2510.07441) · [GitHub](https://github.com/nithincbabu7/DynamicEval) · [Website](https://nithincbabu7.github.io/DynamicEval/) · [Dataset](https://huggingface.co/datasets/hexmSeeU/dynamiceval) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) V-ReasonBench | 2025 | [Paper](https://arxiv.org/abs/2511.16668) · [GitHub](https://github.com/yangluo7/V-ReasonBench) · [Website](https://oahzxl.github.io/VReasonBench/) · [Dataset](https://huggingface.co/datasets/yangluo7/V-ReasonBench) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) RGCD (alternate) | 2025 | [Paper](https://arxiv.org/abs/2506.23852) · [GitHub](https://github.com/IntMeGroup/RGC-VQA) · [Dataset](https://pan.baidu.com/share/init?surl=ebpoA3-DRi3XhT6d68Bf4A&pwd=hab7) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) VIPER | 2025 | [Paper](https://arxiv.org/abs/2512.24952) · [GitHub](https://github.com/RUCAIBox/VIPER) · [Dataset](https://huggingface.co/datasets/Monosail/VIPER)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video Reality Test | 2025 | [Paper](https://arxiv.org/abs/2512.13281) · [GitHub](https://github.com/video-reality-test/video-reality-test) · [Website](https://video-reality-test.github.io/) · [Dataset](https://huggingface.co/datasets/kolerk/Video_Reality_Test) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) T2AV-Compass | 2025 | [Paper](https://arxiv.org/abs/2512.21094) · [Dataset](https://huggingface.co/datasets/NJU-LINK/T2AV-Compass) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) GenVidBench | 2025 | [Paper](https://arxiv.org/abs/2511.13897) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DIVE | 2025 | [Paper](https://arxiv.org/abs/2505.19901) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) UI2V-Bench | 2025 | [Paper](https://arxiv.org/abs/2509.24427) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PhysVidBench | 2025 | [Paper](https://arxiv.org/abs/2507.15824) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SurgVeo | 2025 | [Paper](https://arxiv.org/abs/2511.01775) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) LoCoT2V-Bench | 2025 | [Paper](https://arxiv.org/abs/2510.26412) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PAI-Bench | 2025 | [Paper](https://arxiv.org/abs/2512.01989) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MEve | 2025 | [Paper](https://arxiv.org/abs/2510.03049) |
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) GeneVA | 2026 | [Paper](https://arxiv.org/abs/2509.08818) · [Website](https://www.immersivecomputinglab.org/publication/geneva/) · [Dataset](https://ai-generated-videos-icl.s3.us-east-1.amazonaws.com) |
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) PhyEduVideo | 2026 | [Paper](https://arxiv.org/abs/2601.00943) · [GitHub](https://github.com/meghamariamkm/PhyEduVideo?tab=readme-ov-file) · [Website](https://meghamariamkm.github.io/phyeduvideo26/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DrivingGen | 2026 | [Paper](https://arxiv.org/abs/2601.01528) · [Website](https://drivinggen-bench.github.io/) · [Dataset](https://huggingface.co/datasets/yangzhou99/DrivingGen) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) RISE-Video | 2026 | [Paper](https://arxiv.org/abs/2602.05986) · [GitHub](https://github.com/VisionXLab/RISE-Video) · [Dataset](https://huggingface.co/datasets/VisionXLab/RISE-Video) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) RBench | 2026 | [Paper](https://arxiv.org/abs/2601.15282) · [GitHub](https://github.com/DAGroup-PKU/ReVidgen/) · [Website](https://dagroup-pku.github.io/ReVidgen.github.io/) · [Dataset](https://huggingface.co/datasets/DAGroup-PKU/RBench) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) VC-Bench | 2026 | [Paper](https://arxiv.org/abs/2601.19236) · [Website](https://anonymous.4open.science/r/VC-Bench-1B67/README.md) · [Dataset](https://huggingface.co/datasets/Kevinson-lzp/VC-Bench) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MTAVG-Bench | 2026 | [Paper](https://arxiv.org/abs/2602.00607) |

### Conference Papers

| **Title** | **Year** | **Links** |
| --- | --- | :---: |
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) PanFlow: Decoupled Motion Control for Panoramic Video Generation | 2026 | [Paper](https://arxiv.org/abs/2512.00832v1) · [GitHub](https://github.com/chengzhag/PanFlow) · [Website](https://chengzhag.github.io/publication/panflow/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Phased One-Step Adversarial Equilibrium for Video Diffusion Models | 2026 | [Paper](https://arxiv.org/abs/2508.21019v2) · [Website](https://v-pae.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Omni-Effects: Unified and Spatially-Controllable Visual Effects Generation | 2026 | [Paper](https://arxiv.org/abs/2508.07981v3) · [GitHub](https://github.com/AMAP-ML/Omni-Effects) · [Website](https://amap-ml.github.io/Omni-Effects.github.io/) |
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) Show Me: Unifying Instructional Image and Video Generation with Diffusion Models | 2026 | [Paper](https://arxiv.org/abs/2511.17839v1) · [GitHub](https://github.com/yujiangpu20/ShowMe-master) · [Website](https://yujiangpu20.github.io/showme/) |
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) UniVid: Unifying Vision Tasks with Pre-trained Video Generation Models | 2026 | [Paper](https://arxiv.org/abs/2509.21760v1) · [GitHub](https://github.com/CUC-MIPG/UniVid)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Controllable Human-centric Keyframe Interpolation with Generative Prior | 2025 | [Paper](https://arxiv.org/abs/2506.03119v1) · [GitHub](http://github.com/GSeanCDAT/PoseFuse3D-KI) · [Website](https://gseancdat.github.io/projects/PoseFuse3D_KI)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) RoboScape: Physics-informed Embodied World Model | 2025 | [Paper](https://arxiv.org/abs/2506.23135v1) · [GitHub](https://github.com/tsinghua-fib-lab/RoboScape)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Aligning What Matters: Masked Latent Adaptation for Text-to-Audio-Video Generation | 2025 | [Paper](https://neurips.cc/virtual/2025/loc/mexico-city/poster/118857)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Audio-Sync Video Generation with Multi-Stream Temporal Control | 2025 | [Paper](https://arxiv.org/abs/2506.08003v1) · [GitHub](https://github.com/suimuc/MTV_Framework) · [Website](https://hjzheng.net/projects/MTV/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Autoregressive Adversarial Post-Training for Real-Time Interactive Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.09350v2) · [Website](https://seaweed-apt.com/2)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) DenseDPO: Fine-Grained Temporal Preference Optimization for Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.03517v2) · [Website](https://snap-research.github.io/DenseDPO/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) EchoShot: Multi-Shot Portrait Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.15838) · [GitHub](https://github.com/JoHnneyWang/EchoShot) · [Website](https://johnneywang.github.io/EchoShot-webpage/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Frame Context Packing and Drift Prevention in Next-Frame-Prediction Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2504.12626) · [GitHub](https://github.com/lllyasviel/FramePack) · [Website](https://lllyasviel.github.io/frame_pack_gitpage/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Frame In-N-Out: Unbounded Controllable Image-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.21491v2) · [GitHub](https://github.com/UVA-Computer-Vision-Lab/FrameINO) · [Website](https://uva-computer-vision-lab.github.io/Frame-In-N-Out/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) GeoVideo: Introducing Geometric Regularization into Video Generation Model | 2025 | [Paper](https://arxiv.org/abs/2512.03453v1) · [GitHub](https://github.com/yunpeng1998/GeoVideo) · [Website](https://geovideo.github.io/GeoVideo/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Hierarchical Fine-grained Preference Optimization for Physically Plausible Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.10858v1) · [Website](https://haroldchen19.github.io/PhysHPO-Page/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Imagine360: Immersive 360 Video Generation from Perspective Anchor | 2025 | [Paper](https://arxiv.org/abs/2412.03552) · [GitHub](https://github.com/3DTopia/Imagine360) · [Website](https://ys-imtech.github.io/projects/Imagine360/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Improving Video Generation with Human Feedback | 2025 | [Paper](https://arxiv.org/abs/2501.13918) · [GitHub](https://github.com/KlingTeam/VideoAlign) · [Website](https://gongyeliu.github.io/videoalign/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) MoCha: Towards Movie-Grade Talking Character Generation | 2025 | [Paper](https://arxiv.org/abs/2503.23307) · [GitHub](https://github.com/congwei1230/MoCha-Demo) · [Website](https://congwei1230.github.io/MoCha/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) PolyVivid: Vivid Multi-Subject Video Generation with Cross-Modal Interaction and Enhancement | 2025 | [Paper](https://arxiv.org/abs/2506.07848v1) · [Website](https://sjtuplayer.github.io/projects/PolyVivid/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Radial Attention: $O(n\log n)$ Sparse Attention with Energy Decay for Long Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.19852v1) · [GitHub](https://github.com/mit-han-lab/radial-attention) · [Website](https://hanlab.mit.edu/projects/radial-attention)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) RLGF: Reinforcement Learning with Geometric Feedback for Autonomous Driving Video Generation | 2025 | [Paper](https://arxiv.org/abs/2509.16500v2) |
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Temporal In-Context Fine-Tuning for Versatile Control of Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.00996) · [GitHub](https://github.com/kinam0252/TIC-FT) · [Website](https://kinam0252.github.io/TIC-FT/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) VideoREPA: Learning Physics for Video Generation through Relational Alignment with Foundation Models | 2025 | [Paper](https://arxiv.org/abs/2505.23656v1) · [GitHub](https://github.com/aHapBean/VideoREPA) · [Website](https://videorepa.github.io/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Virtual Fitting Room: Generating Arbitrarily Long Videos of Virtual Try-On from a Single Image | 2025 | [Paper](https://arxiv.org/abs/2509.04450v1) · [Website](https://immortalco.github.io/VirtualFittingRoom/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance | 2025 | [Paper](https://arxiv.org/abs/2512.08765) · [GitHub](https://github.com/ali-vilab/Wan-Move) · [Website](https://wan-move.github.io/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2503.08153) · [GitHub](https://github.com/360CVGroup/WISA) · [Website](https://360cvgroup.github.io/WISA/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) WorldWeaver: Generating Long-Horizon Video Worlds via Rich Perception | 2025 | [Paper](https://arxiv.org/abs/2508.15720v1) · [Website](https://johanan528.github.io/worldweaver_web/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2506.08009v2) · [GitHub](https://github.com/guandeh17/Self-Forcing) |
| ![EMNLP](https://img.shields.io/badge/EMNLP-darkorange) VC4VG: Optimizing Video Captions for Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.24134) · [GitHub](https://github.com/qyr0403/VC4VG) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) AICL: Action In-Context Learning for Video Diffusion Model | 2025 | [Paper](https://dl.acm.org/doi/10.1145/3746027.3754864)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) Improving Identity Preservation in Video Generation with Multi-Branch Models | 2025 | [Paper](https://dl.acm.org/doi/10.1145/3746027.3761990)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) M2PE-DIFF: Music-to-Pose Encoder for Dance Video Generation Leveraging Latent Diffusion Framework. | 2025 | [Paper](https://doi.org/10.1145/3746027.3754808)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) SpA2V: Harnessing Spatial Auditory Cues for Audio-driven Spatially-aware Video Generation | 2025 | [Paper](https://arxiv.org/html/2508.00782v1) |
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) Tora2: Motion and Appearance Customized Diffusion Transformer for Multi-Entity Video Generation | 2025 | [Paper](https://arxiv.org/abs/2507.05963) · [Website](https://ali-videoai.github.io/Tora2_page/)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) AnimeColor: Reference-based Animation Colorization with Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2507.20158v1) · [GitHub](https://github.com/IamCreateAI/AnimeColor) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) Causal-Entity Reflected Egocentric Traffic Accident Video Synthesis | 2025 | [Paper](https://arxiv.org/abs/2506.23263v1) · [GitHub](https://github.com/JWFanggit/Causal-VidSyn-Office) · [Website](http://lotvsmmau.net/Causal-VidSyn) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) Diffuman4D: 4D Consistent Human View Synthesis from Sparse-View Videos with Spatio-Temporal Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2507.13344v1) · [GitHub](https://github.com/zju3dv/Diffuman4D) · [Website](https://diffuman4d.github.io/) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction | 2025 | [Paper](https://arxiv.org/abs/2406.06465) · [Website](https://chenhsing.github.io/AID/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Adversarial Distribution Matching for Diffusion Distillation Towards Efficient Image and Video Synthesis | 2025 | [Paper](https://arxiv.org/abs/2507.18569)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Decouple and Track: Benchmarking and Improving Video Diffusion Transformers For Motion Transfer | 2025 | [Paper](https://arxiv.org/abs/2503.17350) · [GitHub](https://github.com/Shi-qingyu/DeT) · [Website](https://shi-qingyu.github.io/DeT.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion | 2025 | [Paper](https://arxiv.org/abs/2504.04010) · [Website](https://cv.maxi.su/DiTaiListener/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) DOLLAR: Few-Step Video Generation via Distillation and Latent Reward Optimization | 2025 | [Paper](https://arxiv.org/abs/2412.15689) · [Website](https://quantumiracle.github.io/dollar/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Dual-Expert Consistency Model for Efficient and High-Quality Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.03123) · [GitHub](https://github.com/Vchitect/DCM) · [Website](https://vchitect.github.io/DCM/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization | 2025 | [Paper](https://arxiv.org/abs/2505.02192) · [GitHub](https://github.com/wenc-k/DualReal) · [Website](https://wenc-k.github.io/dualreal-customization/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) EfficientMT: Efficient Temporal Adaptation for Motion Transfer in Text-to-Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2503.19369) · [GitHub](https://github.com/PrototypeNx/EfficientMT) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) Free-Form Motion Control: Controlling the 6D Poses of Camera and Objects in Video Generation | 2025 | [Paper](https://arxiv.org/abs/2501.01425) · [GitHub](https://github.com/FudanCVL/SynFMC) · [Website](https://henghuiding.com/SynFMC/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) I2VControl: Disentangled and Unified Video Motion Synthesis Control | 2025 | [Paper](https://arxiv.org/abs/2411.17765) · [Website](https://wanquanf.github.io/I2VControl)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) LayerAnimate: Layer-level Control for Animation | 2025 | [Paper](https://arxiv.org/abs/2501.08295) · [GitHub](https://github.com/IamCreateAI/LayerAnimate) · [Website](https://layeranimate.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Learning Few-Step Diffusion Models by Trajectory Distribution Matching | 2025 | [Paper](https://arxiv.org/abs/2503.06674) · [GitHub](https://github.com/Luo-Yihong/TDM) · [Website](https://tdm-t2x.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) LiON-LoRA: Rethinking LoRA Fusion to Unify Controllable Spatial and Temporal Generation for Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2507.05678) · [Website](https://fuchengsu.github.io/lionlora.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Long Context Tuning for Video Generation | 2025 | [Paper](https://arxiv.org/abs/2503.10589) · [Website](https://guoyww.github.io/projects/long-context-video/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization | 2025 | [Paper](https://arxiv.org/abs/2503.12689) · [GitHub](https://github.com/EchoPluto/MagicID) · [Website](https://echopluto.github.io/MagicID-project/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) MagicMirror: ID-Preserved Video Generation in Video Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2501.03931) · [GitHub](https://github.com/dvlab-research/MagicMirror) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance | 2025 | [Paper](https://arxiv.org/abs/2503.16421) · [GitHub](https://github.com/JIA-Lab-research/MagicMirror) · [Website](https://julianjuaner.github.io/projects/MagicMirror/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Mobile Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2412.07583) · [Website](https://qualcomm-ai-research.github.io/mobile-video-diffusion/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) MotionAgent: Fine-grained Controllable Video Generation via Motion Field Agent | 2025 | [Paper](https://arxiv.org/abs/2502.03207) · [GitHub](https://github.com/leoisufa/MotionAgent) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation | 2025 | [Paper](https://arxiv.org/abs/2411.17048) · [GitHub](https://github.com/EchoPluto/PersonalVideo?tab=readme-ov-file) · [Website](https://personalvideo.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment | 2025 | [Paper](https://arxiv.org/abs/2502.11079) · [GitHub](https://github.com/Phantom-video/Phantom) · [Website](https://phantom-video.github.io/Phantom/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Precise Action-to-Video Generation Through Visual Action Prompts | 2025 | [Paper](https://arxiv.org/abs/2508.13104) · [Website](https://zju3dv.github.io/VAP/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Prompt-A-Video: Prompt Your Video Diffusion Model via Preference-Aligned LLM | 2025 | [Paper](https://arxiv.org/abs/2412.15156) · [GitHub](https://github.com/jiyt17/Prompt-A-Video) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) Puppet-Master: Scaling Interactive Video Generation as a Motion Prior for Part-Level Dynamics | 2025 | [Paper](https://arxiv.org/abs/2408.04631) · [GitHub](https://github.com/RuiningLi/puppet-master) · [Website](https://vgg-puppetmaster.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Reangle-A-Video: 4D Video Generation as Video-to-Video Translation | 2025 | [Paper](https://arxiv.org/abs/2503.09151) · [GitHub](https://github.com/HyeonHo99/Reangle-Video) · [Website](https://hyeonho99.github.io/reangle-a-video/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) RealCam-I2V: Real-World Image-to-Video Generation with Interactive Complex Camera Control | 2025 | [Paper](https://arxiv.org/abs/2502.10059) · [GitHub](https://zgctroy.github.io/RealCam-I2V/) · [Website](https://github.com/ZGCTroy/RealCam-I2V)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) STAR: Spatial-Temporal Augmentation with Text-to-Video Models for Real-World Video Super-Resolution | 2025 | [Paper](https://arxiv.org/abs/2501.02976) · [GitHub](https://github.com/NJU-PCALab/STAR) · [Website](https://nju-pcalab.github.io/projects/STAR/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) TACO: Taming Diffusion for in-the-wild Video Amodal Completion | 2025 | [Paper](https://arxiv.org/abs/2503.12049) · [GitHub](https://github.com/Jason-aplp/TACO-code) · [Website](https://jason-aplp.github.io/TACO/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) V.I.P.: Iterative Online Preference Distillation for Efficient Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2508.03254) · [Website](https://jiiiisoo.github.io/VIP.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) VEGGIE: Instructional Editing and Reasoning Video Concepts with Grounded Generation | 2025 | [Paper](https://arxiv.org/abs/2503.14350) · [GitHub](https://github.com/Yui010206/VEGGIE-VidEdit/) · [Website](https://veggie-gen.github.io/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Versatile Transition Generation with Image-to-Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2508.01698) · [Website](https://mwxely.github.io/projects/yang2025vtg/index)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) VideoAuteur: Towards Long Narrative Video Generation | 2025 | [Paper](https://arxiv.org/abs/2501.06173) · [GitHub](https://github.com/lambert-x/VideoAuteur) · [Website](https://videoauteur.github.io/)|
| ![IJCAI](https://img.shields.io/badge/IJCAI-royalblue) FLAP: Fully-controllable Audio-driven Portrait Video Generation through 3D head conditioned diffusion model | 2025 | [Paper](https://arxiv.org/html/2502.19455v3)|
| ![ICML](https://img.shields.io/badge/ICML-indigo) FrameBridge: Improving Image-to-Video Generation with Bridge Models | 2025 | [Paper](https://arxiv.org/abs/2410.15371) · [Website](https://framebridge-icml.github.io/)|
| ![ICML](https://img.shields.io/badge/PMLR-gold) Diffusion Adversarial Post-Training for One-Step Video Generation  | 2025 | [Paper](https://arxiv.org/abs/2501.08316) · [Website](https://seaweed-apt.com/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) AKiRa: Augmentation Kit on Rays for Optical Video Generation | 2025 | [Paper](https://arxiv.org/abs/2412.14158) · [GitHub](https://github.com/Triocrossing/AKiRa) · [Website](https://www.lix.polytechnique.fr/vista/projects/2024_akira_wang/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) AnyMoLe: Any Character Motion In-betweening Leveraging Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2503.08417) · [GitHub](https://github.com/kwanyun/AnyMoLe) · [Website](https://kwanyun.github.io/AnyMoLe_page/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Extrapolating and Decoupling Image-to-Video Generation Models: Motion Modeling is Easier Than You Think | 2025 | [Paper](https://arxiv.org/abs/2503.00948) · [GitHub](https://github.com/Chuge0335/EDG) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) FlipSketch: Flipping Static Drawings to Text-Guided Sketch Animations | 2025 | [Paper](https://arxiv.org/abs/2411.10818) · [GitHub](https://github.com/hmrishavbandy/FlipSketch) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) MotionPro: A Precise Motion Controller for Image-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.20287v1) · [GitHub](https://github.com/HiDream-ai/MotionPro) · [Website](https://zhw-zhang.github.io/MotionPro-page/) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) FinePhys: Fine-grained Human Action Generation by Explicitly Incorporating Physical Laws for Effective Skeletal Guidance | 2025 | [Paper](https://arxiv.org/abs/2505.13437v1) · [GitHub](https://github.com/SmartDianLab/FinePhys) · [Website](https://smartdianlab.github.io/projects-FinePhys/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) From Slow Bidirectional to Fast Autoregressive Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2412.07772) · [GitHub](https://github.com/tianweiy/CausVid) · [Website](https://causvid.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Go-with-the-Flow: Motion-Controllable Video Diffusion Models Using Real-Time Warped Noise | 2025 | [Paper](https://arxiv.org/abs/2501.08331) · [GitHub](https://github.com/Eyeline-Research/Go-with-the-Flow) · [Website](https://eyeline-labs.github.io/Go-with-the-Flow/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) GS-DiT: Advancing Video Generation with Dynamic 3D Gaussian Fields through Efficient Dense 3D Point Tracking | 2025 | [Paper](https://arxiv.org/abs/2501.02690) · [GitHub](https://github.com/wkbian/GS-DiT) · [Website](https://wkbian.github.io/Projects/GS-DiT/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) High-Fidelity Relightable Monocular Portrait Animation with Lighting-Controllable Video Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2502.19894) · [GitHub](https://github.com/MingtaoGuo/Relightable-Portrait-Animation) · [Website](https://mingtaoguo.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation | 2025 | [Paper](https://arxiv.org/abs/2503.18860) · [GitHub](https://github.com/kkakkkka/HunyuanPortrait) · [Website](https://kkakkkka.github.io/HunyuanPortrait/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) InterDyn: Controllable Interactive Dynamics with Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2412.11785) · [GitHub](https://github.com/rickakkerman/InterDyn) · [Website](https://interdyn.is.tue.mpg.de/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Lux Post Facto: Learning Portrait Performance Relighting with Conditional Video Diffusion and a Hybrid Dataset | 2025 | [Paper](https://arxiv.org/abs/2503.14485) · [Website](https://www.eyelinestudios.com/research/luxpostfacto.html)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Mind the Time: Temporally-Controlled Multi-Event Video Generation | 2025 | [Paper](https://arxiv.org/abs/2412.05263) · [Website](https://mint-video.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) Silence is Golden: Leveraging Adversarial Examples to Nullify Audio Control in LDM-based Talking-Head Generation | 2025 | [Paper](https://arxiv.org/abs/2506.01591v1) · [GitHub](https://github.com/yuangan/Silencer) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) MotiF: Making Text Count in Image Animation with Motion Focal Loss | 2025 | [Paper](https://arxiv.org/abs/2412.16153) · [Website](https://wang-sj16.github.io/motif/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) One-Minute Video Generation with Test-Time Training | 2025 | [Paper](https://arxiv.org/abs/2504.05298) · [GitHub](https://github.com/test-time-training/ttt-video-dit) · [Website](https://test-time-training.github.io/video-dit/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) ReCapture: Generative Video Camera Controls for User-Provided Videos using Masked Video Fine-Tuning | 2025 | [Paper](https://arxiv.org/abs/2411.05003) · [Website](https://generative-video-camera-controls.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) ShotAdapter: Text-to-Multi-Shot Video Generation with Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2505.07652) · [Website](https://shotadapter.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation | 2025 | [Paper](https://arxiv.org/abs/2503.11423) · [GitHub](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob) · [Website](https://taste-rob.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) TransPixeler: Advancing Text-to-Video Generation with Transparency | 2025 | [Paper](https://arxiv.org/abs/2501.03006) · [GitHub](https://github.com/wileewang/TransPixeler) · [Website](https://wileewang.github.io/TransPixar/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) VideoDPO: Omni-Preference Alignment for Video Diffusion Generation | 2025 | [Paper](https://arxiv.org/abs/2412.14167) · [GitHub](https://github.com/CIntellifusion/VideoDPO) · [Website](https://videodpo.github.io/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) Boosting Camera Motion Control for Video Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2410.10802) · [GitHub](https://github.com/soon-yau/CameraMotionGuidance) · [Website](https://soon-yau.github.io/CameraMotionGuidance/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) CameraCtrl: Enabling Camera Control for Video Diffusion Models | 2025 | [Paper](https://arxiv.org/html/2404.02101v2) · [GitHub](https://github.com/hehao13/CameraCtrl) · [Website](https://hehao13.github.io/projects-CameraCtrl/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2404.09967) · [GitHub](https://github.com/HL-hanlin/Ctrl-Adapter) · [Website](https://ctrl-adapter.github.io/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) Diffusion-NPO: Negative Preference Optimization for Better Preference Aligned Generation of Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2505.11245) · [GitHub](https://github.com/G-U-N/Diffusion-NPO)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) SePPO: Semi-Policy Preference Optimization for Diffusion Alignment | 2025 | [Paper](https://arxiv.org/html/2410.05255v1) · [GitHub](https://github.com/DwanZhang-AI/SePPO) |
| ![ICLR](https://img.shields.io/badge/ICLR-teal) Trajectory attention for fine-grained video motion control | 2025 | [Paper](https://arxiv.org/abs/2411.19324) · [GitHub](https://github.com/xizaoqu/TrajectoryAttention?tab=readme-ov-file) · [Website](https://xizaoqu.github.io/trajattn/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) VADER: Video Diffusion Alignment via Reward Gradients | 2025 | [Paper](https://arxiv.org/abs/2407.08737) · [GitHub](https://github.com/vader-vid/vader) · [Website](https://vader-vid.github.io/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control | 2025 | [Paper](https://arxiv.org/abs/2407.12781) · [GitHub](https://github.com/snap-research/ac3d) · [Website](https://snap-research.github.io/vd3d/)|
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) Fine-Grained Controllable Video Generation via Object Appearance and Context | 2025 | [Paper](https://arxiv.org/abs/2312.02919) · [Website](https://hhsinping.github.io/factor/)|
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) MagicStick: Controllable Video Editing via Control Handle Transformations | 2025 | [Paper](https://arxiv.org/abs/2312.03047) · [GitHub](https://github.com/mayuelala/FollowYourHandle) · [Website](https://magic-stick-edit.github.io/)|
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) TrackDiffusion: Tracklet-Conditioned Video Generation via Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2312.00651) · [GitHub](https://github.com/pixeli99/TrackDiffusion)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) CAGE: Unsupervised Visual Composition and Animation for Controllable Video Generation | 2025 | [Paper](https://arxiv.org/abs/2403.14368) · [GitHub](https://github.com/araachie/cage) · [Website](https://araachie.github.io/cage/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) CustomCrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities | 2025 | [Paper](https://arxiv.org/abs/2408.13239) · [GitHub](https://github.com/WuTao-CS/CustomCrafter) · [Website](https://customcrafter.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training | 2025 | [Paper](https://arxiv.org/abs/2412.15646) · [GitHub](https://github.com/RongPiKing/CustomTTT) · [Website](https://customttt.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation | 2025 | [Paper](https://arxiv.org/abs/2403.06845) · [GitHub](https://github.com/f1yfisher/DriveDreamer2) · [Website](https://drivedreamer2.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Enhancing Identity-Deformation Disentanglement in StyleGAN for One-Shot Face Video Re-Enactment | 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32113) · [GitHub](https://github.com/NickChang97/ViVFace) · [Website](https://nickchang97.github.io/ViVFace.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Modular-Cam: Modular Dynamic Camera-view Video Generation with LLM | 2025 | [Paper](https://arxiv.org/abs/2504.12048v1) · [GitHub](https://github.com/pzrain/Modular-Cam) · [Website](https://modular-cam.github.io/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Occlusion-Insensitive Talking Head Video Generation via Facelet Compensation | 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32277)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) PanoDiT: Panoramic Videos Generation with Diffusion Transformer | 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33089)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) TrackGo: A Flexible and Efficient Method for Controllable Video Generation | 2025 | [Paper](https://arxiv.org/abs/2408.11475) · [Website](https://homepage.marvolo.top/TrackGo-Page/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) UFO: Enhancing Diffusion-Based Video Generation with a Uniform Frame Organizer | 2025 | [Paper](https://arxiv.org/abs/2412.09389) · [GitHub](https://github.com/Delong-liu-bupt/UFO) |
| ![SIGGRAPH Asia](https://img.shields.io/badge/SIGGRAPH%20Asia-red) Shape-for-Motion: Precise and Consistent Video Editing with 3D Proxy | 2025 | [Paper](https://arxiv.org/abs/2506.22432v2) · [GitHub](https://github.com/yuhaoliu7456/Shape-for-Motion) · [Website](https://shapeformotion.github.io/) |
| ![SIGGRAPH Asia](https://img.shields.io/badge/SIGGRAPH%20Asia-red) FairyGen: Storied Cartoon Video from a Single Child-Drawn Character | 2025 | [Paper](https://arxiv.org/abs/2506.21272v2) · [GitHub](https://github.com/GVCLab/FairyGen) · [Website](https://jayleejia.github.io/FairyGen/)|
| ![SIGGRAPH Asia](https://img.shields.io/badge/SIGGRAPH%20Asia-red) CamCloneMaster: Enabling Reference-based Camera Control for Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.03140v1) · [GitHub](https://github.com/KlingTeam/CamCloneMaster) · [Website](https://camclonemaster.github.io/)|
| ![MICCAI](https://img.shields.io/badge/MICCAI-gray) Mission Balance: Generating Under-represented Class Samples using Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2505.09858v1) |
| ![MICCAI](https://img.shields.io/badge/MICCAI-gray) Ophora: A Large-Scale Data-Driven Text-Guided Ophthalmic Surgical Video Generation Model | 2025 | [Paper](https://arxiv.org/abs/2505.07449v7) · [GitHub](https://github.com/uni-medical/Ophora)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) Animate Your Motion: Turning Still Images into Dynamic Videos | 2024 | [Paper](https://arxiv.org/abs/2403.10179) · [GitHub](https://github.com/Mingxiao-Li/Animate-Your-Motion) · [Website](https://mingxiao-li.github.io/smcd/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) DragVideo: Interactive Drag-style Video Editing | 2024 | [Paper](https://arxiv.org/abs/2312.02216) · [GitHub](https://github.com/RickySkywalker/DragVideo-Official) · [Website](https://dragvideo.github.io/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) MEVG : Multi-event Video Generation with Text-to-Video Models | 2024 | [Paper](https://arxiv.org/abs/2312.04086) · [GitHub](https://github.com/kuai-lab/eccv24_MEVG) · [Website](https://kuai-lab.github.io/eccv2024mevg/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) MoVideo: Motion-Aware Video Generation with Diffusion Models | 2024 | [Paper](https://arxiv.org/abs/2311.11325) · [Website](https://jingyunliang.github.io/MoVideo/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models | 2024 | [Paper](https://arxiv.org/abs/2311.16933) · [GitHub](https://github.com/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl) · [Website](https://guoyww.github.io/projects/SparseCtrl/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) Stable Video Portraits | 2024 | [Paper](https://arxiv.org/abs/2409.18083) · [Website](https://svp.is.tue.mpg.de/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models | 2024 | [Paper](https://arxiv.org/abs/2407.09012) · [GitHub](https://github.com/eccv2024tcan/TCAN) · [Website](https://eccv2024tcan.github.io/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) Video Editing via Factorized Diffusion Distillation | 2024 | [Paper](https://arxiv.org/abs/2403.09334) · [Website](https://fdd-video-edit.github.io/)|
| ![ECCV](https://img.shields.io/badge/ECCV-olive) VideoStudio: Generating Consistent-Content and Multi-Scene Videos | 2024 | [Paper](https://arxiv.org/abs/2401.01256) · [GitHub](https://github.com/FuchenUSTC/VideoStudio) · [Website](https://vidstudio.github.io/)|
| ![COLM](https://img.shields.io/badge/COLM-orange) VideoDirectorGPT: Consistent Multi-Scene Video Generation via LLM-Guided Planning | 2024 | [Paper](https://arxiv.org/abs/2309.15091) · [GitHub](https://github.com/HL-hanlin/VideoDirectorGPT) · [Website](https://videodirectorgpt.github.io/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Exo2Ego-V: Exocentric-to-Egocentric Video Generation | 2024 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f5a8b5e5d007e66c929b971c2bc21d76-Abstract-Conference.html) · [GitHub](https://github.com/showlab/Exo2Ego-V) · [GitHub](https://github.com/showlab/Exo2Ego-V)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) MotionBooth: Motion-Aware Customized Text-to-Video Generation | 2024 | [Paper](https://arxiv.org/abs/2406.17758) · [GitHub](https://github.com/jianzongwu/MotionBooth) · [Website](https://jianzongwu.github.io/projects/motionbooth/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) SF-V: Single Forward Video Generation Model | 2024 | [Paper](https://arxiv.org/abs/2406.04324) · [GitHub](https://github.com/snap-research/SF-V) · [Website](https://snap-research.github.io/SF-V/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) T2V-Turbo: Breaking the Quality Bottleneck of Video Consistency Model with Mixed Reward Feedback | 2024 | [Paper](https://arxiv.org/abs/2405.18750) · [GitHub](https://github.com/Ji4chenLi/t2v-turbo) · [Website](https://t2v-turbo.github.io/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) Vivid-ZOO: Multi-View Video Generation with Diffusion Model | 2024 | [Paper](https://arxiv.org/abs/2406.08659) · [GitHub](https://github.com/hi-zhengcheng/vividzoo) · [Website](https://hi-zhengcheng.github.io/vividzoo/)|
| ![EMNLP](https://img.shields.io/badge/EMNLP-darkorange) VIDEOSCORE: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation | 2024 | [Paper](https://arxiv.org/abs/2406.15252) · [GitHub](https://github.com/TIGER-AI-Lab/VideoScore/) · [Website](https://tiger-ai-lab.github.io/VideoScore/)|
| ![EMNLP](https://img.shields.io/badge/EMNLP-darkorange) VIMI: Grounding Video Generation through Multi-modal Instruction | 2024 | [Paper](https://arxiv.org/abs/2407.06304) · [GitHub](https://github.com/snap-research/VIMI) · [Website](https://snap-research.github.io/VIMI/)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control | 2024 | [Paper](https://arxiv.org/abs/2405.12796) · [GitHub](https://github.com/forchchch/disenstudio.github.io)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) DragEntity: Trajectory Guided Video Generation using Entity and Positional Relationships | 2024 | [Paper](https://arxiv.org/abs/2410.10751)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) Efficient Video Diffusion Models via Content-Frame Motion-Latent Decomposition | 2024 | [Paper](https://arxiv.org/abs/2403.14148) · [Website](https://sihyun.me/CMD/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) SEINE: Short-to-Long Video Diffusion Model for Generative Transition and Prediction | 2024 | [Paper](https://arxiv.org/abs/2310.20700) · [GitHub](https://github.com/Vchitect/SEINE) · [Website](https://vchitect.github.io/SEINE-project/)|
| ![ICLR](https://img.shields.io/badge/ICLR-teal) VersVideo: Leveraging Enhanced Temporal Diffusion Models for Versatile Video Generation | 2024 | [Paper](https://openreview.net/forum?id=K9sVJ17zvB) · [Website](https://jinxixiang.github.io/versvideo/) |
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) InstructVideo: Instructing Video Diffusion Models with Human Feedback | 2024 | [Paper](https://arxiv.org/abs/2312.12490) · [GitHub](https://github.com/ali-vilab/VGen/blob/main/doc/InstructVideo.md) · [Website](https://instructvideo.github.io/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) SimDA: Simple Diffusion Adapter for Efficient Video Generation | 2024 | [Paper](https://arxiv.org/abs/2308.09710) · [GitHub](https://github.com/ChenHsing/SimDA) · [Website](https://chenhsing.github.io/SimDA/)|
| ![CVPR](https://img.shields.io/badge/CVPR-brightgreen) VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models | 2024 | [Paper](https://arxiv.org/abs/2401.09047) · [GitHub](https://github.com/AILab-CVC/VideoCrafter) · [Website](https://ailab-cvc.github.io/videocrafter2/)|
| ![AAAI](https://img.shields.io/badge/AAAI-cyan) Follow Your Pose: Pose-Guided Text-to-Video Generation Using Pose-Free Videos | 2024 | [Paper](https://arxiv.org/abs/2304.01186) · [GitHub](https://github.com/mayuelala/FollowYourPose) · [Website](https://follow-your-pose.github.io/)|
| ![NeurIPS](https://img.shields.io/badge/NeurIPS-blue) VideoComposer: Compositional Video Synthesis with Motion Controllability | 2023 | [Paper](https://arxiv.org/abs/2306.02018) · [GitHub](https://github.com/ali-vilab/videocomposer) · [Website](https://videocomposer.github.io/)|
| ![ACM MM](https://img.shields.io/badge/ACM_MM-darkgray) MobileVidFactory: Automatic Diffusion-Based Social Media Video Generation for Mobile Devices from Text | 2023 | [Paper](https://arxiv.org/abs/2307.16371) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) DreamPose: Fashion Video Synthesis with Stable Diffusion | 2023 | [Paper](https://arxiv.org/abs/2304.06025) · [GitHub](https://github.com/johannakarras/DreamPose) · [Website](https://grail.cs.washington.edu/projects/dreampose/)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2305.10474) · [Website](https://research.nvidia.com/labs/dir/pyoco/) |
| ![ICCV](https://img.shields.io/badge/ICCV-green) Structure and Content-Guided Video Synthesis with Diffusion Models | 2023 | [Paper](https://arxiv.org/abs/2302.03011) · [GitHub](https://github.com/kyegomez/Gen1) · [Website](https://runwayml.com/research/gen-1)|
| ![ICCV](https://img.shields.io/badge/ICCV-green) Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation | 2023 | [Paper](https://arxiv.org/abs/2212.11565) · [GitHub](https://github.com/showlab/Tune-A-Video) · [Website](https://tuneavideo.github.io/)|


---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🧑‍💻 Contributors

👏 Thanks to these contributors for this excellent work！

<a href="https://github.com/CyL97/Awesome-Video-Generation-Post-Training/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CyL97/Awesome-Video-Generation-Post-Training" />
</a>

## ✉️ Contact

For questions, suggestions, or collaboration opportunities, please feel free to reach out:

✉️ Email:  [chaoyuli@asu.edu](mailto:chaoyuli@asu.edu), [pooyan@asu.edu](mailto:pooyan@asu.edu)

## ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=CyL97/Awesome-Video-Generation-Post-Training&type=date&legend=top-left)](https://www.star-history.com/#CyL97/Awesome-Video-Generation-Post-Training&type=date&legend=top-left)
