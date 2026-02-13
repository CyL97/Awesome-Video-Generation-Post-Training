<div align=center>

# Awesome Video Generation Post Training

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![arXiv](https://img.shields.io/badge/arXiv-xxxx.xxxxx-b31b1b.svg?logo=arXiv)]() 
[![hf_paper](https://img.shields.io/badge/🤗-Paper%20In%20HF-red.svg)]()
[![PDF](https://img.shields.io/badge/PDF-GitHub-blue.svg)](https://github.com/CyL97/Awesome-Video-Generation-Post-Training/blob/main/paper/Video_Generation_Post_Training_Survey.pdf)

</div>

> ## [**Video Generation Models: A Survey of Post-Training and Alignment**]()  
> [Chaoyu Li](https://chaoyuli.com/)<sup>1,†,\*</sup>,
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
> [Pooyan Fazli](https://pooyanfazli.com/)<sup>1,\*</sup>  
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
> <sup>†</sup>Equal contribution. <sup>\*</sup>Corresponding author: [Chaoyu Li](mailto:chaoyuli@asu.edu) , [Pooyan Fazli](mailto:pooyan@asu.edu).

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

<!-- ## 📌 Citation 

If you find our paper or this resource helpful, please consider cite:

```bibtex
@article{,
  title={},
  author={},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2026}
}
``` -->

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
| ![arXiv](https://img.shields.io/badge/arXiv-red) GenVidBench | 2025 | [Paper](https://arxiv.org/abs/2511.13897) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DIVE | 2025 | [Paper](https://arxiv.org/abs/2505.19901) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) UI2V-Bench | 2025 | [Paper](https://arxiv.org/abs/2509.24427) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PhysVidBench | 2025 | [Paper](https://arxiv.org/abs/2507.15824) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SurgVeo | 2025 | [Paper](https://arxiv.org/abs/2511.01775) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) LoCoT2V-Bench | 2025 | [Paper](https://arxiv.org/abs/2510.26412) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PAI-Bench | 2025 | [Paper](https://arxiv.org/abs/2512.01989) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MEve | 2025 | [Paper](https://arxiv.org/abs/2510.03049) |
| ![WACV](https://img.shields.io/badge/WACV-dodgerblue) GeneVA | 2026 | [Paper](https://arxiv.org/abs/2509.08818) · [Website](https://www.immersivecomputinglab.org/publication/geneva/) · [Dataset](https://ai-generated-videos-icl.s3.us-east-1.amazonaws.com) |


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


### arXiv Papers

| **Title** | **Year** | **Links** |
| --- | --- | :---: |
| ![arXiv](https://img.shields.io/badge/arXiv-red) ReCamDriving: LiDAR-Free Camera-Controlled Novel Trajectory Video Generation | 2025 | [Paper](https://arxiv.org/abs/2512.03621v1) · [GitHub](https://github.com/Iron-LYK/ReCamDriving) · [Website](https://recamdriving.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) In-Context Sync-LoRA for Portrait Video Editing | 2025 | [Paper](https://arxiv.org/abs/2512.03013v1) · [GitHub](https://github.com/SagiPolaczek/Sync-LoRA) · [Website](https://sagipolaczek.github.io/Sync-LoRA/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Progressive Image Restoration via Text-Conditioned Video Generation | 2025 | [Paper](https://arxiv.org/abs/2512.02273v1)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Generative Video Motion Editing with 3D Point Tracks | 2025 | [Paper](https://arxiv.org/abs/2512.02015v1) · [Website](https://edit-by-track.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SpriteHand: Real-Time Versatile Hand-Object Interaction with Autoregressive Video Generation | 2025 | [Paper](https://arxiv.org/abs/2512.01960v1)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DreamingComics: A Story Visualization Pipeline via Subject and Layout Customized Generation using Video Models | 2025 | [Paper](https://arxiv.org/abs/2512.01686v1) · [Website](https://yj7082126.github.io/dreamingcomics/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Low-Bitrate Video Compression through Semantic-Conditioned Diffusion | 2025 | [Paper](https://arxiv.org/abs/2512.00408v1)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) AnyTalker: Scaling Multi-Person Talking Video Generation with Interactivity Refinement | 2025 | [Paper](https://arxiv.org/abs/2511.23475v1) · [GitHub](https://github.com/HKUST-C4G/AnyTalker) · [Website](https://hkust-c4g.github.io/AnyTalker-homepage/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) BlockVid: Block Diffusion for High-Quality and Consistent Minute-Long Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.22973v1) · [GitHub](https://github.com/ziplab/BlockVid) · [Website](https://ziplab.co/BlockVid) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) WorldWander: Bridging Egocentric and Exocentric Worlds in Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.22098v1) · [GitHub](https://github.com/showlab/WorldWander) · [Website](https://lulupig12138.github.io/WorldWander/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) CtrlVDiff: Controllable Video Generation via Unified Multimodal Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2511.21129v1) · [GitHub](https://github.com/Tele-AI/CtrlVDiff) · [Website](https://tele-ai.github.io/CtrlVDiff/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MotionV2V: Editing Motion in a Video | 2025 | [Paper](https://arxiv.org/abs/2511.20640v1) · [GitHub](https://github.com/RyannDaGreat/MotionV2V) · [Website](https://ryanndagreat.github.io/MotionV2V/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Exo2EgoSyn: Unlocking Foundation Video Generation Models for Exocentric-to-Egocentric Video Synthesis | 2025 | [Paper](https://arxiv.org/abs/2511.20186v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SteadyDancer: Harmonized and Coherent Human Image Animation with First-Frame Preservation | 2025 | [Paper](https://arxiv.org/abs/2511.19320v1) · [GitHub](https://github.com/MCG-NJU/SteadyDancer) · [Website](https://mcg-nju.github.io/steadydancer-web/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Beyond Reward Margin: Rethinking and Resolving Likelihood Displacement in Diffusion Models via Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.19049v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) View-Consistent Diffusion Representations for 3D-Consistent Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.18991v1) · [Website](https://danier97.github.io/ViCoDR/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Eevee: Towards Close-up High-resolution Video-based Virtual Try-on | 2025 | [Paper](https://arxiv.org/abs/2511.18957v1) · [GitHub](https://github.com/AMAP-ML/Eevee) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) STCDiT: Spatio-Temporally Consistent Diffusion Transformer for High-Quality Video Super-Resolution | 2025 | [Paper](https://arxiv.org/abs/2511.18786v1) · [GitHub](https://github.com/JyChen9811/STCDiT) · [Website](https://jychen9811.github.io/STCDiT_page/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Point-to-Point: Sparse Motion Guidance for Controllable Video Editing | 2025 | [Paper](https://arxiv.org/abs/2511.18277v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) CamC2V: Context-aware Controllable Video Generation | 2025 | [Paper](https://arxiv.org/abs/2504.06022v2) · [GitHub](https://github.com/LDenninger/CamC2V) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MultiShotMaster: A Controllable Multi-Shot Video Generation Framework | 2025 | [Paper](https://arxiv.org/abs/2512.03041v1) · [GitHub](https://github.com/KlingTeam/MultiShotMaster) · [Website](https://qinghew.github.io/MultiShotMaster/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) LoVoRA: Text-guided and Mask-free Video Object Removal and Addition with Learnable Object-aware Localization | 2025 | [Paper](https://arxiv.org/abs/2512.02933v2) · [GitHub](https://github.com/cz-5f/LoVoRA.github.io) · [Website](https://cz-5f.github.io/LoVoRA.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Taming Camera-Controlled Video Generation with Verifiable Geometry Reward | 2025 | [Paper](https://arxiv.org/abs/2512.02870v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) IC-World: In-Context Generation for Shared World Modeling | 2025 | [Paper](https://arxiv.org/abs/2512.02793v1) · [GitHub](https://github.com/wufan-cse/IC-World) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Objects in Generated Videos Are Slower Than They Appear: Models Suffer Sub-Earth Gravity and Make Objects Move Slower Than in Reality | 2025 | [Paper](https://arxiv.org/abs/2512.02016v1) · [Website](https://gravity-eval.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) What about gravity in video generation? Post-Training Newton's Laws with Verifiable Rewards | 2025 | [Paper](https://arxiv.org/abs/2512.00425v1) · [GitHub](https://github.com/cvlab-stonybrook/NewtonRewards) · [Website](https://cvlab-stonybrook.github.io/NewtonRewards/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) InstanceV: Instance-Level Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.23146v1) · [GitHub](https://github.com/AliothChen/InstanceV) · [Website](https://aliothchen.github.io/projects/InstanceV/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) McSc: Motion-Corrective Preference Alignment for Video Generation with Self-Critic Hierarchical Reasoning | 2025 | [Paper](https://arxiv.org/abs/2511.22974v1) · [GitHub](https://github.com/QiushiYang/McSc) · [Website](https://qiushiyang.github.io/McSc/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) One-to-All Animation: Alignment-Free Character Animation and Image Pose Transfer | 2025 | [Paper](https://arxiv.org/abs/2511.22940v2) · [GitHub](https://github.com/ssj9596/One-to-All-Animation) · [Website](https://ssj9596.github.io/one-to-all-animation-project/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MoGAN: Improving Motion Quality in Video Diffusion via Few-Step Motion Adversarial Post-Training | 2025 | [Paper](https://arxiv.org/abs/2511.21592v1) · [Website](https://xavihart.github.io/mogan/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video Generation Models Are Good Latent Reward Models | 2025 | [Paper](https://arxiv.org/abs/2511.21541v1) · [Website](https://kululumi.github.io/PRFL/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MapReduce LoRA: Advancing the Pareto Front in Multi-Preference Optimization for Generative Models | 2025 | [Paper](https://arxiv.org/abs/2511.20629v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Growing with the Generator: Self-paced GRPO for Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.19356v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Learning What to Trust: Bayesian Prior-Guided Optimization for Visual Generation | 2025 | [Paper](https://arxiv.org/abs/2511.18919v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) EgoControl: Controllable Egocentric Video Generation via 3D Full-Body Poses | 2025 | [Paper](https://arxiv.org/abs/2511.18173v1) · [GitHub](https://github.com/CVG-Bonn/EgoControl/) · [Website](https://cvg-bonn.github.io/EgoControl/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Less is More: Data-Efficient Adaptation for Controllable Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.17844v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video-as-Answer: Predict and Generate Next Video Event with Joint-GRPO | 2025 | [Paper](https://arxiv.org/abs/2511.16669v2) · [GitHub](https://github.com/KlingTeam/VANS) · [Website](https://video-as-answer.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) First Frame Is the Place to Go for Video Content Customization | 2025 | [Paper](https://arxiv.org/abs/2511.15700v1) · [GitHub](https://github.com/zli12321/FFGO-Video-Customization) · [Website](http://firstframego.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Kandinsky 5.0: A Family of Foundation Models for Image and Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.14993v2) · [GitHub](https://github.com/kandinskylab/kandinsky-5) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) TiViBench: Benchmarking Think-in-Video Reasoning for Video Generative Models | 2025 | [Paper](https://arxiv.org/abs/2511.13704v1) · [GitHub](https://github.com/EnVision-Research/TiViBench) · [Website](https://haroldchen19.github.io/TiViBench-Page/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Adaptive Begin-of-Video Tokens for Autoregressive Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2511.12099v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) ProAV-DiT: A Projected Latent Diffusion Transformer for Efficient Synchronized Audio-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.12072v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) LiteAttention: A Temporal Sparse Attention for Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2511.11062v1) · [GitHub](https://github.com/moonmath-ai/LiteAttention) · [Website](https://moonmath-ai.github.io/LiteAttention/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) EmoVid: A Multimodal Emotion Video Dataset for Emotion-Centric Video Understanding and Generation | 2025 | [Paper](https://arxiv.org/abs/2511.11002v1) · [Website](https://zane-zyqiu.github.io/EmoVid) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video Text Preservation with Synthetic Text-Rich Videos | 2025 | [Paper](https://arxiv.org/abs/2511.05573v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Neodragon: Mobile Video Generation using Diffusion Transformer | 2025 | [Paper](https://arxiv.org/abs/2511.06055v1) · [Website](https://qualcomm-ai-research.github.io/neodragon) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) RISE-T2V: Rephrasing and Injecting Semantics with LLM for Expansive Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.04317v1) · [Website](https://rise-t2v.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PhysCorr: Dual-Reward DPO for Physics-Constrained Text-to-Video Generation with Automated Preference Selection | 2025 | [Paper](https://arxiv.org/abs/2511.03997v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) UniAVGen: Unified Audio and Video Generation with Asymmetric Cross-Modal Interactions | 2025 | [Paper](https://arxiv.org/abs/2511.03334v1) · [GitHub](https://github.com/MCG-NJU/Sora2-mini) · [Website](https://mcg-nju.github.io/UniAVGen/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) ID-Crafter: VLM-Grounded Online RL for Compositional Multi-Subject Video Generation | 2025 | [Paper](https://arxiv.org/abs/2511.00511v3) · [GitHub](https://github.com/paulpanwang/IDCrafter) · [Website](https://angericky.github.io/ID-Crafter/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Fine-Tuning Open Video Generators for Cinematic Scene Synthesis: A Small-Data Pipeline with LoRA and Wan2.1 I2V | 2025 | [Paper](https://arxiv.org/abs/2510.27364v1) · [Website](https://sedatbvb5.github.io/AyDNA/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) The Quest for Generalizable Motion Generation: Data, Model, and Evaluation | 2025 | [Paper](https://arxiv.org/abs/2510.26794v1) · [GitHub](https://github.com/MotrixLab/ViMoGen)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) VC4VG: Optimizing Video Captions for Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.24134) · [GitHub](https://github.com/qyr0403/VC4VG) · [Website](https://github.com/alimama-creative/VC4VG)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) CoMo: Compositional Motion Customization for Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.23007v1) · [Website](https://como6.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Epipolar Geometry Improves Video Generation Models | 2025 | [Paper](https://arxiv.org/abs/2510.21615v1) · [GitHub](https://github.com/KupynOrest/epipolar-dpo) · [Website](https://epipolar-dpo.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MoAlign: Motion-Centric Representation Alignment for Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2510.19022v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) TGT: Text-Grounded Trajectories for Locally Controlled Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.15104v1) · [Website](https://textgroundedtraj.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) In-Context Learning with Unpaired Clips for Instruction-based Video Editing | 2025 | [Paper](https://arxiv.org/abs/2510.14648v1) · [GitHub](https://github.com/leoisufa/ICVE) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Identity-GRPO: Optimizing Multi-Human Identity-preserving Video Generation via Reinforcement Learning | 2025 | [Paper](https://arxiv.org/abs/2510.14256v2) · [GitHub](https://github.com/alibaba/identity-grpo) · [Website](https://ali-videoai.github.io/identity_page/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Identity-Preserving Image-to-Video Generation via Reward-Guided Optimization | 2025 | [Paper](https://arxiv.org/abs/2510.14255v3) · [GitHub](https://alibaba.github.io/ROLL/docs/User%20Guides/Algorithms/Reward_FL/) · [Website](https://ipro-alimama.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Virtually Being: Customizing Camera-Controllable Video Diffusion Models with Multi-View Performance Captures | 2025 | [Paper](https://arxiv.org/abs/2510.14179v1) · [Website](https://eyeline-labs.github.io/Virtually-Being/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) PhysMaster: Mastering Physical Representation for Video Generation via Reinforcement Learning | 2025 | [Paper](https://arxiv.org/abs/2510.13809v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MVP4D: Multi-View Portrait Video Diffusion for Animatable 4D Avatars | 2025 | [Paper](https://arxiv.org/abs/2510.12785v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Stable Video Infinity: Infinite-Length Video Generation with Error Recycling | 2025 | [Paper](https://arxiv.org/abs/2510.09212v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Large Scale Diffusion Distillation via Score-Regularized Continuous-Time Consistency | 2025 | [Paper](https://arxiv.org/abs/2510.08431v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Real-Time Motion-Controllable Autoregressive Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2510.08131v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PickStyle: Video-to-Video Style Transfer with Context-Style Adapters | 2025 | [Paper](https://arxiv.org/abs/2510.07546v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Mitigating Surgical Data Imbalance with Dual-Prediction Video Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2510.07345v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MATRIX: Mask Track Alignment for Interaction-aware Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.07310v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Generative World Modelling for Humanoids: 1X World Model Challenge Technical Report | 2025 | [Paper](https://arxiv.org/abs/2510.07092v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Character Mixing for Video Generation | 2025 | [Paper](https://arxiv.org/abs/2510.05093v1) · [GitHub](https://github.com/TingtingLiao/mimix) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Arbitrary Generative Video Interpolation | 2025 | [Paper](https://arxiv.org/abs/2510.00578v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) FlashI2V: Fourier-Guided Latent Shifting Prevents Conditional Image Leakage in Image-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2509.25187v2) · [GitHub](https://github.com/PKU-YuanGroup/FlashI2V) · [Website](https://pku-yuangroup.github.io/FlashI2V) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DC-VideoGen: Efficient Video Generation with Deep Compression Video Autoencoder | 2025 | [Paper](https://arxiv.org/abs/2509.25182v1) · [GitHub](https://github.com/dc-ai-projects/DC-VideoGen) · [Website](https://hanlab.mit.edu/projects/dc-videogen)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Rolling Forcing: Autoregressive Long Video Diffusion in Real Time | 2025 | [Paper](https://arxiv.org/abs/2509.25161v1) · [GitHub](https://github.com/TencentARC/RollingForcing) · [Website](https://kunhao-liu.github.io/Rolling_Forcing_Webpage) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PanoWorld-X: Generating Explorable Panoramic Worlds via Sphere-Aware Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2509.24997v1) · [Website](https://yuyangyin.github.io/PanoWorld-X/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Attention Surgery: An Efficient Recipe to Linearize Your Video Diffusion Transformer | 2025 | [Paper](https://arxiv.org/abs/2509.24899v3) · [Website](https://qualcomm-ai-research.github.io/attention-surgery/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Reinforcement Learning with Inverse Rewards for World Model Post-training | 2025 | [Paper](https://arxiv.org/abs/2509.23958v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Echo-Path: Pathology-Conditioned Echo Video Generation | 2025 | [Paper](https://arxiv.org/abs/2509.17190v1) · [GitHub](https://github.com/Marshall-mk/EchoPathv1)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) VidCLearn: A Continual Learning Approach for Text-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2509.16956v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Lynx: Towards High-Fidelity Personalized Video Generation | 2025 | [Paper](https://arxiv.org/abs/2509.15496v1) · [GitHub](https://github.com/bytedance/lynx) · [Website](https://byteaigc.github.io/Lynx/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) OpenViGA: Video Generation for Automotive Driving Scenes by Streamlining and Fine-Tuning Open Source Models with Public Data | 2025 | [Paper](https://arxiv.org/abs/2509.15479v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PanoLora: Bridging Perspective and Panoramic Video Generation with LoRA Adaptation | 2025 | [Paper](https://arxiv.org/abs/2509.11092v1) · [Website](https://anonymous-pano-lora.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Kling-Avatar: Grounding Multimodal Instructions for Cascaded Long-Duration Avatar Animation Synthesis | 2025 | [Paper](https://arxiv.org/abs/2509.09595v2) · [Website](https://klingavatar.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Improving Video Diffusion Transformer Training by Multi-Feature Fusion and Alignment from Self-Supervised Vision Encoders | 2025 | [Paper](https://arxiv.org/abs/2509.09547v1) · [Website](https://align4gen.github.io/align4gen/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) RewardDance: Reward Scaling in Visual Generation | 2025 | [Paper](https://arxiv.org/abs/2509.08826v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) HuMo: Human-Centric Video Generation via Collaborative Multi-Modal Conditioning | 2025 | [Paper](https://arxiv.org/abs/2509.08519v1) · [GitHub](https://github.com/Phantom-video/HuMo) · [Website](https://phantom-video.github.io/HuMo/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Zero-shot 3D-Aware Trajectory-Guided image-to-video generation via Test-Time Training | 2025 | [Paper](https://arxiv.org/abs/2509.06723v2) · [GitHub](https://github.com/Richard-Zhang-AI/Zo3T-main) · [Website](https://richard-zhang-ai.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) UniVerse-1: Unified Audio-Video Generation via Stitching of Experts | 2025 | [Paper](https://arxiv.org/abs/2509.06155v1) · [GitHub](https://github.com/Dorniwang/UniVerse-1-code/) · [Website](https://dorniwang.github.io/UniVerse-1/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) BranchGRPO: Stable and Efficient GRPO with Structured Branching in Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2509.06040v5) · [GitHub](https://github.com/Fredreic1849/BranchGRPO) · [Website](https://fredreic1849.github.io/BranchGRPO-Webpage/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DevilSight: Augmenting Monocular Human Avatar Reconstruction through a Virtual Perspective | 2025 | [Paper](https://arxiv.org/abs/2509.00403v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Realistic and Controllable 3D Gaussian-Guided Object Editing for Driving Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.20471v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Learning Primitive Embodied World Models: Towards Scalable Robotic Learning | 2025 | [Paper](https://arxiv.org/abs/2508.20840v3) · [GitHub](https://github.com/qiaosun22/PrimitiveWorld) · [Website](https://qiaosun22.github.io/PrimitiveWorld/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) MIDAS: Multimodal Interactive Digital-humAn Synthesis via Real-time Autoregressive Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.19320v2) · [Website](https://chenmingthu.github.io/milm/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) ControlEchoSynth: Boosting Ejection Fraction Estimation Models via Controlled Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2508.17631v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MoSA: Motion-Coherent Human Video Generation via Structure-Appearance Decoupling | 2025 | [Paper](https://arxiv.org/abs/2508.17404v2) · [GitHub](https://github.com/hywang2002/hywang2002.github.io/tree/main/MoSA) · [Website](https://hywang2002.github.io/MoSA/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) SSG-Dit: A Spatial Signal Guided Framework for Controllable Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.17062v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Seeing Clearly, Forgetting Deeply: Revisiting Fine-Tuned Video Generators for Driving Simulation | 2025 | [Paper](https://arxiv.org/abs/2508.16512v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) WorldWeaver: Generating Long-Horizon Video Worlds via Rich Perception | 2025 | [Paper](https://arxiv.org/abs/2508.15720v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Vivid-VR: Distilling Concepts from Text-to-Video Diffusion Transformer for Photorealistic Video Restoration | 2025 | [Paper](https://arxiv.org/abs/2508.14483v3) · [GitHub](https://github.com/csbhr/Vivid-VR) · [Website](https://csbhr.github.io/projects/vivid-vr/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DreamSwapV: Mask-guided Subject Swapping for Any Customized Video Editing | 2025 | [Paper](https://arxiv.org/abs/2508.14465v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) 4DNeX: Feed-Forward 4D Generative Modeling Made Easy | 2025 | [Paper](https://arxiv.org/abs/2508.13154v1) · [GitHub](https://github.com/3DTopia/4DNeX) · [Website](https://4dnex.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Physical Autoregressive Model for Robotic Manipulation without Action Pretraining | 2025 | [Paper](https://arxiv.org/abs/2508.09822v4) · [GitHub](https://github.com/HCPLab-SYSU/PhysicalAutoregressiveModel) · [Website](https://hcplab-sysu.github.io/PhysicalAutoregressiveModel/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) From Large Angles to Consistent Faces: Identity-Preserving Video Generation via Mixture of Facial Experts | 2025 | [Paper](https://arxiv.org/abs/2508.09476v2) · [GitHub](https://github.com/rain152/LFA-Video-Generation) · [Website](https://rain152.github.io/CoFE/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Animate-X++: Universal Character Image Animation with Dynamic Backgrounds | 2025 | [Paper](https://arxiv.org/abs/2508.09454v1) · [GitHub](https://github.com/Lucaria-Academy/Animate-X-plusplus) · [Website](https://lucaria-academy.github.io/Animate-X++/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) RealisMotion: Decomposed Human Motion Control and Video Generation in the World Space | 2025 | [Paper](https://arxiv.org/abs/2508.08588v1) · [GitHub](https://github.com/JingyunLiang/RealisMotion) · [Website](https://jingyunliang.github.io/RealisMotion/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) SketchAnimator: Animate Sketch via Motion Customization of Text-to-Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2508.07149v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SwiftVideo: A Unified Framework for Few-Step Video Generation through Trajectory-Distribution Alignment | 2025 | [Paper](https://arxiv.org/abs/2508.06082v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DreamVE: Unified Instruction-based Image and Video Editing | 2025 | [Paper](https://arxiv.org/abs/2508.06080v1) · [Website](https://zj-binxia.github.io/DreamVE-ProjectPage/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) PoseGen: In-Context LoRA Finetuning for Pose-Controllable Long Human Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.05091v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) LayerT2V: Interactive Multi-Object Trajectory Layering for Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.04228v1) · [GitHub](https://github.com/Kr-Panghu/LayerT2V-public/) · [Website](https://kr-panghu.github.io/LayerT2V/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Scaling Up Audio-Synchronized Visual Animation: An Efficient Training Paradigm | 2025 | [Paper](https://arxiv.org/abs/2508.03955v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) LongVie: Multimodal-Guided Controllable Ultra-Long Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.03694v1) · [GitHub](https://github.com/Vchitect/LongVie) · [Website](https://vchitect.github.io/LongVie-project/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Macro-from-Micro Planning for High-Quality and Parallelized Autoregressive Long Video Generation | 2025 | [Paper](https://arxiv.org/abs/2508.03334v3) · [GitHub](https://github.com/Tele-AI/MMPL) · [Website](https://nju-xunzhixiang.github.io/Anchor-Forcing-Page/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DreamVVT: Mastering Realistic Video Virtual Try-On in the Wild via a Stage-Wise Diffusion Transformer Framework | 2025 | [Paper](https://arxiv.org/abs/2508.02807v1) · [GitHub](https://github.com/Virtu-Lab/DreamVVT) · [Website](https://virtu-lab.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Compositional Video Synthesis by Temporal Object-Centric Learning | 2025 | [Paper](https://arxiv.org/abs/2507.20855v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Enhancing Scene Transition Awareness in Video Generation via Post-Training | 2025 | [Paper](https://arxiv.org/abs/2507.18046v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Zero-Shot Dynamic Concept Personalization with Grid-Based LoRA | 2025 | [Paper](https://arxiv.org/abs/2507.17963v1) · [Website](https://snap-research.github.io/zero-shot-dynamic-concepts/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Navigating Large-Pose Challenge for High-Fidelity Face Reenactment with Video Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2507.16341v1) · [GitHub](https://github.com/MingtaoGuo/Face-Reenactment-Video-Diffusion) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PUSA V1.0: Surpassing Wan-I2V with $500 Training Cost by Vectorized Timestep Adaptation | 2025 | [Paper](https://arxiv.org/abs/2507.16116v1) · [GitHub](https://github.com/Yaofang-Liu/Pusa-VidGen) · [Website](https://yaofang-liu.github.io/Pusa_Web/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Conditional Video Generation for High-Efficiency Video Compression | 2025 | [Paper](https://arxiv.org/abs/2507.15269v4) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) StableAnimator++: Overcoming Pose Misalignment and Face Distortion for Human Image Animation | 2025 | [Paper](https://arxiv.org/abs/2507.15064v1) · [Website](https://francis-rings.github.io/StableAnimator/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Geometry Forcing: Marrying Video Diffusion and 3D Representation for Consistent World Modeling | 2025 | [Paper](https://arxiv.org/abs/2507.07982v1) · [GitHub](https://github.com/CIntellifusion/GeometryForcing) · [Website](https://GeometryForcing.github.io) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Geometry-aware 4D Video Generation for Robot Manipulation | 2025 | [Paper](https://arxiv.org/abs/2507.01099v1) · [GitHub](https://github.com/lzylucy/4dgen) · [Website](https://robot4dgen.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Populate-A-Scene: Affordance-Aware Human Video Generation | 2025 | [Paper](https://arxiv.org/abs/2507.00334v1) · [Website](https://shanmy.github.io/Populate-A-Scene/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) TextMesh4D: High-Quality Text-to-4D Mesh Generation | 2025 | [Paper](https://arxiv.org/abs/2506.24121v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SynMotion: Semantic-Visual Adaptation for Motion Customized Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.23690v1) · [Website](https://lucaria-academy.github.io/SynMotion/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) MirrorMe: Towards Realtime and High Fidelity Audio-Driven Halfbody Animation | 2025 | [Paper](https://arxiv.org/abs/2506.22065v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video Virtual Try-on with Conditional Diffusion Transformer Inpainter | 2025 | [Paper](https://arxiv.org/abs/2506.21270v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DFVEdit: Conditional Delta Flow Vector for Zero-shot Video Editing | 2025 | [Paper](https://arxiv.org/abs/2506.20967v2) · [GitHub](https://github.com/LinglingCai0314/DFVEdit) · [Website](https://dfvedit.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Bind-Your-Avatar: Multi-Talking-Character Video Generation with Dynamic 3D-mask-based Embedding Router | 2025 | [Paper](https://arxiv.org/abs/2506.19833v1) · [GitHub](https://github.com/Yubo-Shankui/Bind-Your-Avatar-Implementation) · [Website](https://yubo-shankui.github.io/bind-your-avatar/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) AnimaX: Animating the Inanimate in 3D with Joint Video-Pose Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.19851v1) · [GitHub](https://github.com/anima-x/anima-x) · [Website](https://anima-x.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) RDPO: Real Data Preference Optimization for Physics Consistency Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.18655v1) · [Website](https://wwenxu.github.io/RDPO/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) FramePrompt: In-context Controllable Animation with Zero Structural Changes | 2025 | [Paper](https://arxiv.org/abs/2506.17301v2) · [Website](https://frameprompt.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DAVID-XR1: Detecting AI-Generated Videos with Explainable Reasoning | 2025 | [Paper](https://arxiv.org/abs/2506.14827v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Causally Steered Diffusion for Automated Video Counterfactual Generation | 2025 | [Paper](https://arxiv.org/abs/2506.14404v2) · [GitHub](https://github.com/nysp78/counterfactual-video-generation) · [Website](https://nysp78.github.io/counterfactual-video-generation/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) iDiT-HOI: Inpainting-based Hand Object Interaction Reenactment via Video Diffusion Transformer | 2025 | [Paper](https://arxiv.org/abs/2506.12847v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) PlayerOne: Egocentric World Simulator | 2025 | [Paper](https://arxiv.org/abs/2506.09995v1) · [GitHub](https://github.com/yuanpengtu/PlayerOne) · [Website](https://playerone-hku.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) LoRA-Edit: Controllable First-Frame-Guided Video Editing via Mask-Aware LoRA Fine-Tuning | 2025 | [Paper](https://arxiv.org/abs/2506.10082v5) · [GitHub](https://github.com/cjeen/LoRAEdit) · [Website](https://cjeen.github.io/LoRAEdit/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DreamActor-H1: High-Fidelity Human-Product Demonstration Video Generation via Motion-designed Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2506.10568v2) · [Website](https://lizhenwangt.github.io/DreamActor-H1/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) GigaVideo-1: Advancing Video Generation via Automatic Feedback with 4 GPU-Hours Fine-Tuning | 2025 | [Paper](https://arxiv.org/abs/2506.10639v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) AlignHuman: Improving Motion and Fidelity via Timestep-Segment Preference Optimization for Audio-Driven Human Animation | 2025 | [Paper](https://arxiv.org/abs/2506.11144v1) · [Website](https://alignhuman.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Enhancing Motion Dynamics of Image-to-Video Models via Adaptive Low-Pass Guidance | 2025 | [Paper](https://arxiv.org/abs/2506.08456v1) · [GitHub](https://github.com/choi403/ALG) · [Website](https://choi403.github.io/ALG/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) HunyuanVideo-HOMA: Generic Human-Object Interaction in Multimodal Driven Human Animation | 2025 | [Paper](https://arxiv.org/abs/2506.08797v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Seedance 1.0: Exploring the Boundaries of Video Generation Models | 2025 | [Paper](https://arxiv.org/abs/2506.09113v2) · [Website](https://seed.bytedance.com/en/seedance)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Cosmos-Drive-Dreams: Scalable Synthetic Driving Data Generation with World Foundation Models | 2025 | [Paper](https://arxiv.org/abs/2506.09042v3) · [GitHub](https://github.com/nv-tlabs/Cosmos-Drive-Dreams) · [Website](https://research.nvidia.com/labs/toronto-ai/cosmos_drive_dreams/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Cross-Frame Representation Alignment for Fine-Tuning Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.09229v2) · [GitHub](https://github.com/deepshwang/crepa) · [Website](https://crepavideo.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Consistent Video Editing as Flow-Driven Image-to-Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.07713v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) From Generation to Generalization: Emergent Few-Shot Learning in Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.07280v2) · [GitHub](https://github.com/PabloAcuaviva/Gen2Gen) · [Website](https://pabloacuaviva.github.io/Gen2Gen/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Restereo: Diffusion stereo video generation and restoration | 2025 | [Paper](https://arxiv.org/abs/2506.06023v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Follow-Your-Motion: Video Motion Transfer via Efficient Spatial-Temporal Decoupled Finetuning | 2025 | [Paper](https://arxiv.org/abs/2506.05207v2) · [Website](https://follow-your-motion.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Follow-Your-Creation: Empowering 4D Creation through Video Inpainting | 2025 | [Paper](https://arxiv.org/abs/2506.04590v1) · [Website](https://follow-your-creation.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) UNIC: Unified In-Context Video Editing | 2025 | [Paper](https://arxiv.org/abs/2506.04216v1) · [Website](https://zixuan-ye.github.io/UNIC/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) FullDiT2: Efficient In-Context Conditioning for Video Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2506.04213v2) · [Website](https://fulldit2.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) ORV: 4D Occupancy-centric Robot Video Generation | 2025 | [Paper](https://arxiv.org/abs/2506.03079v2) · [GitHub](https://github.com/OrangeSodahub/ORV) · [Website](https://orangesodahub.github.io/ORV) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Sparse-vDiT: Unleashing the Power of Sparse Attention to Accelerate Video Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2506.03065v1) · [GitHub](https://github.com/Peyton-Chen/Sparse-vDiT)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Physics-Guided Motion Loss for Video Generation Model | 2025 | [Paper](https://arxiv.org/abs/2506.02244v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Learning Video Generation for Robotic Manipulation with Collaborative Trajectory Control | 2025 | [Paper](https://arxiv.org/abs/2506.01943v2) · [GitHub](https://github.com/KlingTeam/RoboMaster) · [Website](https://fuxiao0719.github.io/projects/robomaster/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) OmniV2V: Versatile Video Generation and Editing via Dynamic Content Manipulation | 2025 | [Paper](https://arxiv.org/abs/2506.01801v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Many-for-Many: Unify the Training of Multiple Video and Image Generation and Manipulation Tasks | 2025 | [Paper](https://arxiv.org/abs/2506.01758v2) · [GitHub](https://github.com/leeruibin/MfM) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Respond Beyond Language: A Benchmark for Video Generation in Response to Realistic User Intents | 2025 | [Paper](https://arxiv.org/abs/2506.01689v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Playing with Transformer at 30+ FPS via Next-Frame Diffusion | 2025 | [Paper](https://arxiv.org/abs/2506.01380v2) · [Website](https://nextframed.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) DeepVerse: 4D Autoregressive Video Generation as a World Model | 2025 | [Paper](https://arxiv.org/abs/2506.01103v1) · [GitHub](https://github.com/SOTAMak1r/DeepVerse) · [Website](https://sotamak1r.github.io/deepverse/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Temporal In-Context Fine-Tuning for Versatile Control of Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.00996v1) · [GitHub](https://github.com/kinam0252/TIC-FT) · [Website](https://kinam0252.github.io/TIC-FT/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SkyReels-Audio: Omni Audio-Conditioned Talking Portraits in Video Diffusion Transformers | 2025 | [Paper](https://arxiv.org/abs/2506.00830v1) · [Website](https://www.skyreels.ai/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Video Signature: Implicit Watermarking for Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2506.00652v4) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Ctrl-Crash: Controllable Diffusion for Realistic Car Crashes | 2025 | [Paper](https://arxiv.org/abs/2506.00227v1) · [GitHub](https://github.com/AnthonyGosselin/Ctrl-Crash) · [Website](https://anthonygosselin.github.io/Ctrl-Crash-ProjectPage/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) MAGREF: Masked Guidance for Any-Reference Video Generation with Subject Disentanglement | 2025 | [Paper](https://arxiv.org/abs/2505.23742v2) · [GitHub](https://github.com/MAGREF-Video/MAGREF) · [Website](https://magref-video.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) ATI: Any Trajectory Instruction for Controllable Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.22944v3) · [GitHub](https://github.com/bytedance/ATI) · [Website](https://anytraj.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) FaceEditTalker: Controllable Talking Head Generation with Facial Attribute Editing | 2025 | [Paper](https://arxiv.org/abs/2505.22141v2) · [Website](https://peterfanfan.github.io/FaceEditTalker/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) EPiC: Efficient Video Camera Control Learning with Precise Anchor-Video Guidance | 2025 | [Paper](https://arxiv.org/abs/2505.21876v1) · [GitHub](https://github.com/wz0919/EPiC) · [Website](https://zunwang1.github.io/Epic)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Think Before You Diffuse: Infusing Physical Rules into Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2505.21653v3) · [Website](https://bwgzk-keke.github.io/DiffPhy/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Any-to-Bokeh: Arbitrary-Subject Video Refocusing with Video Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2505.21593v3) · [Website](https://bwgzk-keke.github.io/DiffPhy/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) HunyuanVideo-Avatar: High-Fidelity Audio-Driven Human Animation for Multiple Characters | 2025 | [Paper](https://arxiv.org/abs/2505.20156v2) · [GitHub](https://github.com/Tencent-Hunyuan/HunyuanVideo-Avatar) · [Website](https://hunyuanvideo-avatar.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Dynamic-I2V: Exploring Image-to-Video Generation Models via Multimodal LLM | 2025 | [Paper](https://arxiv.org/abs/2505.19901v3) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.18078v1) · [GitHub](https://github.com/yisuanwang/DanceTog) · [Website](https://DanceTog.github.io/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) SafeMVDrive: Multi-view Safety-Critical Driving Video Synthesis in the Real World Domain | 2025 | [Paper](https://arxiv.org/abs/2505.17727v1) · [GitHub](https://github.com/zhoujiawei3/SafeMVDrive) · [Website](https://zhoujiawei3.github.io/SafeMVDrive/) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) T2VUnlearning: A Concept Erasing Method for Text-to-Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2505.17550v3) · [GitHub](https://github.com/VDIGPKU/T2VUnlearning.git) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) MTVCrafter: 4D Motion Tokenization for Open-World Human Image Animation | 2025 | [Paper](https://arxiv.org/abs/2505.10238v4) · [GitHub](https://github.com/DINGYANB/MTVCrafter) · [Website](https://dingyanb.github.io/MTVCtafter/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) ProFashion: Prototype-guided Fashion Video Generation with Multiple Reference Images | 2025 | [Paper](https://arxiv.org/abs/2505.06537v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) HunyuanCustom: A Multimodal-Driven Architecture for Customized Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.04512v2) · [GitHub](https://github.com/Tencent-Hunyuan/HunyuanCustom) · [Website](https://hunyuancustom.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) A Unit Enhancement and Guidance Framework for Audio-Driven Avatar Video Generation | 2025 | [Paper](https://arxiv.org/abs/2505.03603v5) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) VIDSTAMP: A Temporally-Aware Watermark for Ownership and Integrity in Video Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2505.01406v2) · [Website](https://github.com/SPIN-UMass/VidStamp)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) ReVision: High-Quality, Low-Cost Video Generation with Explicit 3D Physics Modeling for Complex Motion and Interaction | 2025 | [Paper](https://arxiv.org/abs/2504.21855v1) · [Website](https://revision-video.github.io/)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) ManipDreamer: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance | 2025 | [Paper](https://arxiv.org/abs/2504.16464v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Subject-driven Video Generation via Disentangled Identity and Motion | 2025 | [Paper](https://arxiv.org/abs/2504.17816v1) · [GitHub](https://github.com/carpedkm/disentangled-subject-to-vid) · [Website](https://carpedkm.github.io/projects/disentangled_sub/index.html)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Reasoning Physical Video Generation with Diffusion Timestep Tokens via Reinforcement Learning | 2025 | [Paper](https://arxiv.org/abs/2504.15932v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) UniAnimate-DiT: Human Image Animation with Large-Scale Video Diffusion Transformer | 2025 | [Paper](https://arxiv.org/abs/2504.11289v1) · [GitHub](https://github.com/ali-vilab/UniAnimate-DiT)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) Taming Consistency Distillation for Accelerated Human Image Animation | 2025 | [Paper](https://arxiv.org/abs/2504.11143v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Aligning Anime Video Generation with Human Feedback | 2025 | [Paper](https://arxiv.org/abs/2504.10044v2) · [GitHub](https://github.com/bilibili/Index-anisora)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) I Want It That Way! Specifying Nuanced Camera Motions in Video Editing | 2025 | [Paper](https://arxiv.org/abs/2504.09472v2) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) Discriminator-Free Direct Preference Optimization for Video Diffusion | 2025 | [Paper](https://arxiv.org/abs/2504.08542v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) EasyGenNet: An Efficient Framework for Audio-Driven Gesture Video Generation Based on Diffusion Model | 2025 | [Paper](https://arxiv.org/abs/2504.08344v1) |
| ![arXiv](https://img.shields.io/badge/arXiv-red) RAGME: Retrieval Augmented Video Generation for Enhanced Motion Realism | 2025 | [Paper](https://arxiv.org/abs/2504.06672v1) · [GitHub](https://github.com/helia95/ragme)|
| ![arXiv](https://img.shields.io/badge/arXiv-red) VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation | 2023 | [Paper](https://arxiv.org/abs/2305.10874) |

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
