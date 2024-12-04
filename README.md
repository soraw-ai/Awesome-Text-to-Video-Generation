# Awesome-Text-to-Video-Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated (continually updated) list of Text-to-Video studies. It's based on our survey paper: [From Sora What We Can See: A Survey of Text-to-Video Generation](https://arxiv.org/pdf/2405.10674).
In this survey, We have conducted a comprehensive exploration of existing works in the Text-to-Video field using OpenAI’s Sora as a clue, and we have also summarized 24 datasets and 9 evaluation metrics in this field. Specifically, we discussed the problems existing in this research area and Sora itself, combined with the advantages of Sora and the characteristics of related fields to provide future research directions. If our work can inspire you, feel free to cite our paper and star our repo.

**This project is curated and maintained by [Rui Sun](https://github.com/ray-ruisun) and [Yumin Zhang](https://github.com/zymvszym).**

```
@article{sun2024sora,
  title={From Sora What We Can See: A Survey of Text-to-Video Generation},
  author={Sun, Rui and Zhang, Yumin and Shah, Tejal and Sun, Jiahao and Zhang, Shuoying and Li, Wenqi and Duan, Haoran and Wei, Bo and Ranjan, Rajiv},
  journal={arXiv preprint arXiv:2405.10674},
  year={2024}
}
```
![](imgs/structure.png)
![](imgs/evo_timeline.png)

> Topics of this repo cover: <br>
> `Text-to-Seq-Image`, `Text-to-Video`

## Table of Content
* [Text-to-Seq-Image](#text_to_seq_image)
* [Text-to-Video](#text_to_video)
* [Dataset & Metrics](#dataset_and_metrics)

## <a name="text_to_seq_image"></a> Text-to-Seq-Image
- **LivePhoto: Real Image Animation with Text-guided Motion Control**  <br>
  Team: HKU, Alibaba Group, Ant Group. <br>
  *Xi Chen, Zhiheng Liu, Mengting Chen, et al., Hengshuang Zhao* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.02928)], [[PDF](https://arxiv.org/pdf/2312.02928.pdf)], [[Code](https://github.com/XavierCHEN34/LivePhoto)], [[Demo (Video)](https://www.youtube.com/watch?v=M2vzrTYAsQI)], [[Home Page](https://xavierchen34.github.io/LivePhoto-Page/)] <br>
- **Scalable Diffusion Models with Transformers** `Sequential Images` <br>
  Team: UC Berkeley, NYU. <br>
  *William Peebles, Saining Xie* <br>
  **ICCV'23(Oral)**, arXiv, 2022.12 [[Paper](https://arxiv.org/abs/2212.09748)], [[PDF](https://arxiv.org/pdf/2212.09748.pdf)], [[Code](https://github.com/facebookresearch/DiT)], [[Pretrained Model](https://github.com/facebookresearch/DiT)], [[Home Page](https://www.wpeebles.com/DiT.html)] <br>

## <a name="text_to_video"></a> Text-to-Video
- **Identity-Preserving Text-to-Video Generation by Frequency Decomposition**<br>
  Team: Peking University, Peng Cheng Laboratory<br>
  *Shenghai Yuan, Jinfa Huang, Xianyi He, et al., Li Yuan* <br>
  arXiv, 2024.11 [[Paper](https://arxiv.org/abs/2411.17440)], [[PDF](https://arxiv.org/pdf/2411.17440)], [[Code](https://github.com/PKU-YuanGroup/ConsisID)], [[Home Page](https://pku-yuangroup.github.io/ConsisID/)]


- **Zero-Shot Video Editing through Adaptive Sliding Score Distillation** `Video Editing` <br>
  Team: Nanjing University. <br>
  *Lianghan Zhu, Yanqi Bao, Jing Huo, et al., Yang Gao* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.04888)], [[PDF](https://arxiv.org/pdf/2406.04888)], [[Home Page](https://nips24videoedit.github.io/zeroshot_videoedit/)] <br>
- **CoNo: Consistency Noise Injection for Tuning-free Long Video Diffusion** <br>
  Team: University of Science and Technology of China. <br>
  *Xingrui Wang, Xin Li, Zhibo Chen* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.05082)], [[PDF](https://arxiv.org/pdf/2406.05082)], [[Home Page](https://wxrui182.github.io/CoNo.github.io/)] <br>
- **VideoTetris: Towards Compositional Text-to-Video Generation** <br>
  Team: Peking University. <br>
  *Ye Tian, Ling Yang, Haotian Yang, et al., Bin Cui* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.04277)], [[PDF](https://arxiv.org/pdf/2406.04277)], [[Code](https://github.com/YangLing0818/VideoTetris)], [[Home Page](https://videotetris.github.io/)] <br>
- **Searching Priors Makes Text-to-Video Synthesis Better** <br>
  Team: Zhejiang University. <br>
  *Haoran Cheng, Liang Peng, Linxuan Xia, et al., Boxi Wu* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.03215)], [[PDF](https://arxiv.org/pdf/2406.03215)], [[Home Page](https://hrcheng98.github.io/Search_T2V/)] <br>
- **Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting** `3DGS Task` <br>
  Team: KAIST, ByteDance. <br>
  *Inkyu Shin, Qihang Yu, Xiaohui Shen, et al., Liang-Chieh Chen* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.02541)], [[PDF](https://arxiv.org/pdf/2406.02541)], [[Home Page](https://video-3dgs-project.github.io/)] <br>
- **ViDiT-Q: Efficient and Accurate Quantization of Diffusion Transformers for Image and Video Generation** <br>
  Team: Tsinghua University. <br>
  *Tianchen Zhao, Tongcheng Fang, Enshu Liu, et al., Yu Wang* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.02540)], [[PDF](https://arxiv.org/pdf/2406.02540)], [[Home Page](https://a-suozhang.xyz/viditq.github.io/)] <br>
- **FIFO-Diffusion: Generating Infinite Videos from Text without Training** <br>
  Team: Computer Vision Laboratory, ECE & IPAI, Seoul National University <br>
  Jihwan Kim, Junoh Kang, Jinyoung Cho, Bohyung Han <br>
  arXiv, 2024.05 [[Paper](https://arxiv.org/abs/2405.11473)], [[PDF](https://arxiv.org/pdf/2405.11473)], [[Code](https://github.com/jjihwan/FIFO-Diffusion_public)], [[Home Page](https://jjihwan.github.io/projects/FIFO-Diffusion)]
- **TALC: Time-Aligned Captions for Multi-Scene Text-to-Video Generation** <br>
  Team: UCLA, Google. <br>
  *Hritik Bansal, Yonatan Bitton, Michal Yarom, et al., Kai-Wei Chang* <br>
  arXiv, 2024.05 [[Paper](https://arxiv.org/abs/2405.04682)], [[PDF](https://arxiv.org/pdf/2405.04682)], [[Code](https://github.com/Hritikbansal/talc)], [[Dataset](https://huggingface.co/datasets/hbXNov/multi_scene_video_text_data)], [[Pretrained Model](https://huggingface.co/hbXNov/talc_finetuned_modelscope_t2v)], [[Home Page](https://talc-mst2v.github.io/)] <br>
- **iVideoGPT: Interactive VideoGPTs are Scalable World Models** `Robotics` <br>
  Team: Tsinghua University. <br>
  *Jialong Wu, Shaofeng Yin, Ningya Feng, et al., Mingsheng Long* <br>
  arXiv, 2024.05 [[Paper](https://arxiv.org/abs/2405.15223)], [[PDF](https://arxiv.org/pdf/2405.15223)], [[Code](https://github.com/thuml/iVideoGPT)], [[Home Page](https://thuml.github.io/iVideoGPT/)] <be>
- **MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators** <br>
  Team: Peking University, University of Rochester. <br>
  *Shenghai Yuan, Jinfa Huang, Yujun Shi, et al., Li Yuan, Jiebo Luo* <br>
  arXiv, 2024.04 [[Paper](https://arxiv.org/abs/2404.05014)], [[PDF](https://arxiv.org/abs/2404.05014)], [[Code](https://github.com/PKU-YuanGroup/MagicTime)], [[Home Page](https://pku-yuangroup.github.io/MagicTime/)] <br>
- **Snap Video: Scaled Spatiotemporal Transformers for Text-to-Video Synthesis** <br>
  Team: Snap Inc, University of Trento.<br>
  *Willi Menapace, Aliaksandr Siarohin, et al., Sergey Tulyakov* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.14797)], [[PDF](https://arxiv.org/pdf/2402.14797)], [[Home Page](https://snap-research.github.io/snapvideo/)]

- **Video generation models as world simulators** <br>
  Team: Sora, Open AI. <br>
  *Tim Brooks, Bill Peebles, Connor Homes, et al., Aditya Ramesh* <br>
  online page, 2024.02 [[Paper](https://openai.com/research/video-generation-models-as-world-simulators)], [[Home Page](https://openai.com/sora)] <br>
- **ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation** <br>
  Team: University of Waterloo. <br>
  *Weiming Ren, Harry Yang, Ge Zhang, et al., Wenhu Chen* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.04324)], [[PDF](https://arxiv.org/pdf/2402.04324.pdf)], [[Code](https://github.com/TIGER-AI-Lab/ConsistI2V)], [[Pretrained Model](https://huggingface.co/TIGER-Lab/)], [[Home Page](https://tiger-ai-lab.github.io/ConsistI2V/)] <br>
- **World Model on Million-Length Video And Language With RingAttention** `Long Video` <br>
  Team: UC Berkeley. <br>
  *Hao Liu, Wilson Yan, Matei Zaharia, Pieter Abbeel* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.08268)], [[PDF](https://arxiv.org/pdf/2402.08268.pdf)], [[Code](https://github.com/LargeWorldModel/LWM)], [[Pretrained Model](https://huggingface.co/LargeWorldModel)], [[Home Page](https://largeworldmodel.github.io/)] <br>
- **360DVD: Controllable Panorama Video Generation with 360-Degree Video Diffusion Model** <br>
  Team: Peking University. <br>
  *Qian Wang, Weiqi Li, Chong Mou, et al., Jian Zhang* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.06578)], [[PDF](https://arxiv.org/pdf/2401.06578.pdf)], [[Code](https://github.com/Akaneqwq/360DVD)], [[Home Page](https://akaneqwq.github.io/360DVD/)] <br>
- **MagicVideo-V2: Multi-Stage High-Aesthetic Video Generation** <br>
  Team: Bytedance Inc. <br>
  *Weimin Wang, Jiawei Liu, Zhijie Lin, et al., Jiashi Feng* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.04468)], [[PDF](https://arxiv.org/pdf/2401.04468.pdf)], [[Home Page](https://magicvideov2.github.io)] <br>
- **UniVG: Towards UNIfied-modal Video Generation** <br>
  Team: Baidu Inc. <br>
  *Ludan Ruan, Lei Tian, Chuanwei Huang, et al., Xinyan Xiao* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.09084)], [[PDF](https://arxiv.org/pdf/2401.09084.pdf)], [[Home Page](https://univg-baidu.github.io)] <br>
- **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** <br>
  Team: HiDream.ai Inc. <br>
  *Fuchen Long, Zhaofan Qiu, Ting Yao and Tao Mei* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.01256)], [[PDF](https://arxiv.org/pdf/2401.01256.pdf)], [[Home Page](https://videodrafter.github.io)] <br>
- **VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models** <br>
  Team: Tencent AI Lab. <br>
  *Haoxin Chen, Yong Zhang, Xiaodong Cun, et al., Ying Shan* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.09047)], [[PDF](https://arxiv.org/pdf/2401.09047.pdf)], [[Code](https://github.com/AILab-CVC/VideoCrafter?tab=readme-ov-file)], [[Pretrained Model](https://github.com/AILab-CVC/VideoCrafter?tab=readme-ov-file)], [[Home Page](https://ailab-cvc.github.io/videocrafter2/)] <br>
- **Lumiere: A Space-Time Diffusion Model for Video Generation** <br>
  Team: Google Research, Weizmann Institute, Tel-Aviv University, Technion. <br>
  *Omer Bar-Tal, Hila Chefer, Omer Tov, et al., Inbar Mosseri* <br>
  arXiv, 2024.01 [[Paper](https://arxiv.org/abs/2401.12945)], [[PDF](https://arxiv.org/pdf/2401.12945.pdf)], [[Home Page](https://lumiere-video.github.io/)] <br>

- **A Recipe for Scaling up Text-to-Video Generation with Text-free Videos** <br>
  Team: HUST, Alibaba Group. <br>
  *Xiang Wang, Shiwei Zhang, et al., Nong Sang* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.15770)], [[PDF](https://arxiv.org/pdf/2312.15770)], [[Home Page](https://tf-t2v.github.io/)]

- **DreamVideo: Composing Your Dream Videos with Customized Subject and Motion** <br>
  Team: Fudan University, Alibaba Group, HUST, Zhejiang University. <br>
  *Yujie Wei, Shiwei Zhang, Zhiwu Qing, et al., Hongming Shan* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2401.12945)], [[PDF](https://arxiv.org/pdf/2312.04433.pdf)], [[Code](https://github.com/ali-vilab/i2vgen-xl)], [[Home Page](https://dreamvideo-t2v.github.io)] <br>
- **VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation** <br>
  Team: Peking University, Microsoft Research. <br>
  *Wenjing Wang, Huan Yang, Zixi Tuo, et al., Jiaying Liu* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2305.10874)], [[PDF](https://arxiv.org/pdf/2305.10874.pdf)] <br>
- **TrailBlazer: Trajectory Control for Diffusion-Based Video Generation** `Training-free` <br>
  Team: Victoria University of Wellington, NVIDIA <br>
  *Wan-Duo Kurt Ma, J.P. Lewis, W. Bastiaan Kleijn* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2401.00896)], [[PDF](https://arxiv.org/pdf/2401.00896.pdf)], [[Code](https://github.com/hohonu-vicml/Trailblazer)], [[Home Page](https://hohonu-vicml.github.io/Trailblazer.Page/)], [[Demo(video)](https://www.youtube.com/watch?v=P-PSkS7sNco)]<br>
- **FreeInit: Bridging Initialization Gap in Video Diffusion Models** `Training-free` <br>
  Team: Nanyang Technological University <br>
  *Tianxing Wu, Chenyang Si, Yuming Jiang, Ziqi Huang, Ziwei Liu* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.07537)], [[PDF](https://arxiv.org/pdf/2312.07537.pdf)], [[Code](https://github.com/TianxingWu/FreeInit)], [[Home Page](https://tianxingwu.github.io/pages/FreeInit/)], [[Demo(live)](https://huggingface.co/spaces/TianxingWu/FreeInit)], [[Demo(video)](https://www.youtube.com/watch?v=lS5IYbAqriI)]<br>
- **MTVG : Multi-text Video Generation with Text-to-Video Models** `Training-free` <br>
  Team: Korea University, NVIDIA <br>
  *Gyeongrok Oh, Jaehwan Jeong, Sieun Kim, et al., Sangpil Kim* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.04086)], [[PDF](https://arxiv.org/pdf/2312.04086.pdf)], [[Code](https://github.com/TianxingWu/FreeInit)], [[Home Page](https://kuai-lab.github.io/mtvg-page/)], [[Demo(video)](https://kuai-lab.github.io/mtvg-page/)]<br>
- **A Recipe for Scaling up Text-to-Video Generation with Text-free Videos** <br>
  Team: HUST, Alibaba Group, Zhejiang University, Ant Group <br>
  *Xiang Wang, Shiwei Zhang, Hangjie Yuan, et al., Nong Sang* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.15770)], [[PDF](https://arxiv.org/pdf/2312.15770.pdf)], [[Code](https://github.com/ali-vilab/i2vgen-xl)], [[Home Page](https://instructvideo.github.io/)]<br>
- **InstructVideo: Instructing Video Diffusion Models with Human Feedback** <br>
  Team: Zhejiang University, Alibaba Group, Tsinghua University <br>
  *Hangjie Yuan, Shiwei Zhang, Xiang Wang, et al., Dong Ni* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.12490)], [[PDF](https://arxiv.org/pdf/2312.12490.pdf)], [[Code](https://github.com/ali-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md)], [[Home Page](https://tf-t2v.github.io)]<br>
- **VideoLCM: Video Latent Consistency Model** <br>
  Team: HUST, Alibaba Group, SJTU <br>
  *Xiang Wang, Shiwei Zhang, Han Zhang, et al., Nong Sang* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.09109#:~:text=VideoLCM%20builds%20upon%20existing%20latent,efficiency%2C%20fidelity%20and%20temporal%20consistency.)], [[PDF](https://arxiv.org/pdf/2312.09109.pdf)], [[Code](https://github.com/ali-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md)], [[Home Page](https://tf-t2v.github.io)]<br>
- **Photorealistic Video Generation with Diffusion Models** <br>
  Team: Stanford University Fei-Fei Li, Google. <br>
  *Agrim Gupta, Lijun Yu, Kihyuk Sohn, et al., José Lezama* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.06662)], [[PDF](https://arxiv.org/pdf/2312.06662.pdf)], [[Home Page](https://walt-video-diffusion.github.io/)] <br>
- **Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation** <br>
  Team: HUST, Alibaba Group, Fudan University. <br>
  *Zhiwu Qing, Shiwei Zhang, Jiayu Wang, et al., Nong Sang* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.04483)], [[PDF](https://arxiv.org/pdf/2312.04483.pdf)], [[Code](https://github.com/ali-vilab/i2vgen-xl)], [[Pretrained Model](https://huggingface.co/spaces/damo-vilab/I2VGen-XL)], [[Home Page](https://higen-t2v.github.io)] <br>
- **GenTron: Delving Deep into Diffusion Transformers for Image and Video Generation** <br>
  Team: HKU, Meta. <br>
  *Shoufa Chen, Mengmeng Xu, Jiawei Ren, et al., Juan-Manuel Perez-Rua* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.04557)], [[PDF](https://arxiv.org/pdf/2312.04557.pdf)], [[Home Page](https://www.shoufachen.com/gentron_website/)] <br>
- **StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter** <br>
  Team: Tsinghua University, Tencent AI Lab, CUHK. <br>
  *Gongye Liu, Menghan Xia, Yong Zhang, et al., Ying Shan* <br>
  arXiv, 2023.12 [[Paper](https://arxiv.org/abs/2312.00330)], [[PDF](https://arxiv.org/pdf/2312.00330.pdf)], [[Code](https://gongyeliu.github.io/StyleCrafter.github.io/)], [[Home Page](https://gongyeliu.github.io/StyleCrafter.github.io/)], [[Demo(live)](https://huggingface.co/spaces/liuhuohuo/StyleCrafter)] <br>
- **GPT4Video: A Unified Multimodal Large Language Model for lnstruction-Followed Understanding and Safety-Aware Generation** `Multimodal` <br> 
  Team: Tencent. <br>
  *Zhanyu Wang, Longyue Wang, Zhen Zhao, et al., Zhaopeng Tu* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.16511)], [[PDF](https://arxiv.org/pdf/2311.16511.pdf)], [[Code](https://github.com/gpt4video/GPT4Video)], [[Pretrained Model](https://github.com/gpt4video/GPT4Video)], [[Home Page](https://gpt4video.github.io/)] <br>
- **F3-Pruning: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis** `Training-free` <br>
  Team: University of Electronic Science and Technology of China. <br>
  *Sitong Su, Jianzhi Liu, Lianli Gao, Jingkuan Song* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2312.03459)], [[PDF](https://arxiv.org/pdf/2312.03459.pdf)] <br>
- **AdaDiff: Adaptive Step Selection for Fast Diffusion** `Training-free` <br>
  Team: Fudan University. <br>
  *Hui Zhang, Zuxuan Wu, Zhen Xing, Jie Shao, Yu-Gang Jiang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.14768)], [[PDF](https://arxiv.org/pdf/2311.14768.pdf)] <br>
- **FlowZero: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic Scene Syntax** `Training-free` <br>
  Team: University of Technology Sydney. <br>
  *Yu Lu, Linchao Zhu, Hehe Fan, Yi Yang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.15813)], [[PDF](https://arxiv.org/pdf/2311.15813.pdf)], [[Code(coming)](https://github.com/aniki-ly/FlowZero)], [[Home Page](https://flowzero-video.github.io/)] <br>
- **GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning** `Training-free` <br>
  Team: Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences. <br>
  *Jiaxi Lv, Yi Huang, Mingfu Yan, Jiancheng Huang, et al., Shifeng Chen* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.12631)], [[PDF](https://arxiv.org/pdf/2311.12631.pdf)], [[Code(coming)](https://github.com/jiaxilv/GPT4Motion)], [[Home Page](https://gpt4motion.github.io/)] <br>
- **MicroCinema: A Divide-and-Conquer Approach for Text-to-Video Generation** <br>
  Team: University of Science and Technology of China, MSRA, Xi'an Jiaotong University. <br>
  *Yanhui Wang, Jianmin Bao, Wenming Weng, et al., Baining Guo* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.18829#:~:text=Unlike%20existing%20approaches%20that%20align,%26text%2Dto%2Dvideo%20generation.)], [[PDF](https://arxiv.org/pdf/2311.18829.pdf)], [[Home Page](https://wangyanhui666.github.io/MicroCinema.github.io/)], [[Demo(video)](https://www.youtube.com/shorts/H7O-Ku_lqPA)] <br>
- **FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation** <br>
  Team: University of Science and Technology of China, MSRA, Xi'an Jiaotong University. <br>
  *Yuanxin Liu, Lei Li, Shuhuai Ren, et al., Lu Hou* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.01813)], [[PDF](https://arxiv.org/pdf/2311.01813.pdf)], [[Code](https://github.com/llyx97/FETV)], [[Dataset](https://huggingface.co/datasets/lyx97/FETV)] <br>
- **ART⋅V: Auto-Regressive Text-to-Video Generation with Diffusion Models** <br>
  Team: University of Science and Technology of China, Microsoft. <br>
  *Wenming Weng, Ruoyu Feng, Yanhui Wang, et al., Zhiwei Xiong* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.18834)], [[PDF](https://arxiv.org/pdf/2311.18834.pdf)], [[Code(coming)](https://github.com/WarranWeng/ART.V)], [[Home Page](https://warranweng.github.io/art.v/)], [[Demo(video)](https://www.youtube.com/watch?v=KX-BV7a-S0Q)] <br>
- **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** <br>
  Team: Stability AI. <br>
  *Andreas Blattmann, Tim Dockhorn, Sumith Kulal, et al., Robin Rombach* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.15127)], [[PDF](https://arxiv.org/pdf/2311.15127.pdf)], [[Code](https://github.com/Stability-AI/generative-models)] <br>
- **FusionFrames: Efficient Architectural Aspects for Text-to-Video Generation Pipeline** <br>
  Team: Sber AI. <br>
  *Vladimir Arkhipkin, Zein Shaheen, Viacheslav Vasilev, et al., Denis Dimitrov* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.13073)], [[PDF](https://arxiv.org/pdf/2311.13073.pdf)], [[Code](https://github.com/ai-forever/KandinskyVideo)], [[Home Page](https://ai-forever.github.io/kandinsky-video/)], [[Demo(live)](https://replicate.com/cjwbw/kandinskyvideo)] <br>
- **MoVideo: Motion-Aware Video Generation with Diffusion Models** <br>
  Team: ETH, Meta. <br>
  *Jingyun Liang, Yuchen Fan, Kai Zhang, et al., Rakesh Ranjan* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.11325)], [[PDF](https://arxiv.org/pdf/2311.11325.pdf)], [[Home Page](https://jingyunliang.github.io/MoVideo/)] <br>
- **Optimal Noise pursuit for Augmenting Text-to-Video Generation** <br>
  Team: Zhejiang Lab. <br>
  *Shijie Ma, Huayi Xu, Mengjian Li, et al., Yaxiong Wang* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.00949)], [[PDF](https://arxiv.org/pdf/2311.00949.pdf)] <br>
- **Make Pixels Dance: High-Dynamic Video Generation** <br>
  Team: ByteDance. <br>
  *Yan Zeng, Guoqiang Wei, Jiani Zheng, et al., Hang Li* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.10982)], [[PDF](https://arxiv.org/pdf/2311.10982.pdf)], [[Home Page](https://makepixelsdance.github.io/)], [[Demo(video)](https://www.youtube.com/watch?v=QERmPmCg9aQ)] <br>
- **Learning Universal Policies via Text-Guided Video Generation** <br>
  Team: MIT, Google DeepMind, UC Berkeley. <br>
  *Yilun Du, Mengjiao Yang, Bo Dai, et al., Pieter Abbeel* <br>
  **NeurIPS'23 (Spotlight)**, arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2302.00111)], [[PDF](https://arxiv.org/pdf/2302.00111.pdf)], [[Code](https://github.com/flow-diffusion/AVDC)], [[Home Page](https://universal-policy.github.io/unipi/)] <br>
- **Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning** <br>
  Team: Meta. <br>
  *Rohit Girdhar, Mannat Singh, Andrew Brown, et al., Ishan Misra* <br>
  arXiv, 2023.11 [[Paper](https://arxiv.org/abs/2311.10709)], [[PDF](https://arxiv.org/pdf/2311.10709.pdf)], [[Home Page](https://emu-video.metademolab.com/)], [[Demo(live)](https://emu-video.metademolab.com/#/demo)] <br>
- **MotionDirector: Motion Customization of Text-to-Video Diffusion Models** <br>
  Team: Show Lab, National University of Singapore, Zhejiang University <br>
  *Rui Zhao, Yuchao Gu, et al., Mike Zheng Shou* <br>
  ECCV'24 (Oral), 2023.10 [[Paper](https://arxiv.org/abs/2310.08465)], [[PDF](https://arxiv.org/pdf/2310.08465)], [[Code](https://github.com/showlab/MotionDirector)], [[Home Page](https://showlab.github.io/MotionDirector/)]

- **FreeNoise: Tuning-Free Longer Video Diffusion via Noise Rescheduling** `Training-free` <br>
  Team: Nanyang Technological University. <br>
  *Haonan Qiu, Menghan Xia, Yong Zhang, et al., Ziwei Liu* <br>
  ICLR'24 arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.15169)], [[PDF](https://arxiv.org/pdf/2310.15169.pdf)], [[Code](https://github.com/AILab-CVC/FreeNoise)], [[Home Page](http://haonanqiu.com/projects/FreeNoise.html)] <br>
- **ConditionVideo: Training-Free Condition-Guided Text-to-Video Generation** `Training-free` <br>
  Team: Shanghai Artificial Intelligence Laboratory. <br>
  *Bo Peng, Xinyuan Chen, Yaohui Wang, Chaochao Lu, Yu Qiao* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.07697)], [[PDF](https://arxiv.org/pdf/2310.07697.pdf)], [[Code](https://github.com/pengbo807/ConditionVideo)], [[Home Page](https://pengbo807.github.io/conditionvideo-website/)] <br>
- **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** <br>
  Team: Tencent AI Lab. <br>
  *Haoxin Chen, Menghan Xia, Yingqing He, et al., Ying Shan* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.19512)], [[PDF](https://arxiv.org/pdf/2310.19512.pdf)], [[Code](https://github.com/AILab-CVC/VideoCrafter)], [[Home Page](https://ailab-cvc.github.io/videocrafter2/)] <br>
- **SEINE: Short-to-Long Video Diffusion Model for Generative Transition and Prediction** <br>
  Team: Shanghai Artificial Intelligence Laboratory. <br>
  *Xinyuan Chen, Yaohui Wang, Lingjun Zhang, et al., Ziwei Liu* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.20700)], [[PDF](https://arxiv.org/pdf/2310.20700.pdf)], [[Code](https://github.com/Vchitect/SEINE)], [[Home Page](https://vchitect.github.io/SEINE-project/)] <br>
- **DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors** <br>
  Team: The Chinese University of Hong Kong. <br>
  *Jinbo Xing, Menghan Xia, Yong Zhang, et al., Ying Shan* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.12190)], [[PDF](https://arxiv.org/pdf/2310.12190.pdf)], [[Code](https://github.com/Doubiiu/DynamiCrafter)], [[Pretrained Model](https://github.com/Doubiiu/DynamiCrafter)], [[Home Page](https://doubiiu.github.io/projects/DynamiCrafter/)], [[Demo(live)](https://huggingface.co/spaces/Doubiiu/DynamiCrafter)], [[Demo(video)](https://www.youtube.com/watch?v=0NfmIsNAg-g)] <br>
- **LAMP: Learn A Motion Pattern for Few-Shot-Based Video Generation** <br>
  Team: Nankai University, MEGVII Technology. <br>
  *Ruiqi Wu, Liangyu Chen, Tong Yang, et al., Xiangyu Zhang* <br>
  arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.10769)], [[PDF](https://arxiv.org/pdf/2310.10769.pdf)], [[Code](https://github.com/RQ-Wu/LAMP)], [[Pretrained Model](https://github.com/RQ-Wu/LAMP)], [[Home Page](https://rq-wu.github.io/projects/LAMP/)] <br>
- **LLM-grounded Video Diffusion Models** `Training-free` <br>
  Team: UC Berkeley. <br>
  *Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.17444)], [[PDF](https://arxiv.org/pdf/2309.17444.pdf)], [[Code(coming)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)], [[Home Page](https://pengbo807.github.io/conditionvideo-website/)] <br>
- **VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning** <br>
  Team: UNC Chapel Hill. <br>
  *Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.15091)], [[PDF](https://arxiv.org/pdf/2309.15091.pdf)], [[Code](https://github.com/HL-hanlin/VideoDirectorGPT)] <br>
- **VideoGen: A Reference-Guided Latent Diffusion Approach for High Definition Text-to-Video Generation** <br>
  Team: Baidu Inc. <br>
  *Xin Li, Wenqing Chu, Ye Wu, et al., Jingdong Wang* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.00398)], [[PDF](https://arxiv.org/pdf/2309.00398.pdf)], [[Home Page](https://videogen.github.io/VideoGen/)] <br>
- **LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models** <br>
  Team: Shanghai Artificial Intelligence Laboratory. <br>
  *Yaohui Wang, Xinyuan Chen, Xin Ma, et al., Ziwei Liu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.15103)], [[PDF](https://arxiv.org/pdf/2309.15103.pdf)], [[Code](https://github.com/Vchitect/LaVie)], [[Home Page](https://vchitect.github.io/LaVie-project/)] <br>
- **Reuse and Diffuse: Iterative Denoising for Text-to-Video Generation** <br>
  Team: Huawei. <br>
  *Jiaxi Gu, Shicong Wang, Haoyu Zhao, et al., Hang Xu* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.03549)], [[PDF](https://arxiv.org/pdf/2309.03549.pdf)], [[Code](https://github.com/anonymous0x233/ReuseAndDiffuse)], [[Home Page](https://anonymous0x233.github.io/ReuseAndDiffuse/)] <br>
- **Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator** `Training-free` <br>
  Team: School of Information Science and Technology, ShanghaiTech University. <br>
  *Hanzhuo Huang, Yufan Feng, Cheng Shi, et al., Sibei Yang* <br>
  **NeurIPS'24**, arxiv, 2023.9[[Paper](https://arxiv.org/abs/2309.14494)], [[PDF](https://arxiv.org/pdf/2309.14494.pdf)], [[Home Page](https://github.com/showlab/Tune-A-Video)] <br>
- **Show-1: Marrying pixel and latent diffusion models for text-to-video generation.** <br>
  Team: Show Lab, National University of Singapore <br>
  *David Junhao Zhang, Jay Zhangjie Wu, Jia-Wei Liu, et al., Mike Zheng Shou* <br>
  arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.15818)], [[PDF](https://arxiv.org/pdf/2309.15818.pdf)], [[Home Page](https://showlab.github.io/Show-1/)],[[Code](https://github.com/showlab/Show-1)], [[Pretrained Model](https://huggingface.co/spaces/showlab/Show-1)] <br>
- **GLOBER: Coherent Non-autoregressive Video Generation via GLOBal Guided Video DecodER** <br>
  Team: Institute of Automation, Chinese Academy of Sciences (CASIA). <br>
  *Mingzhen Sun, Weining Wang, Zihan Qin, et al., Jing Liu* <br>
  NeurIPS'23, arXiv, 2023.09 [[Paper](https://arxiv.org/abs/2309.13274)], [[PDF](https://arxiv.org/pdf/2309.13274.pdf)], [[Code](https://github.com/iva-mzsun/GLOBER)], [[Home Page](https://iva-mzsun.github.io/GLOBER)], [[[Demo(video)](https://iva-mzsun.github.io/GLOBER)] <br>
- **DiffSynth: Latent In-Iteration Deflickering for Realistic Video Synthesis** `Training-free` <br>
  Team: East China Normal University. <br>
  *Zhongjie Duan, Lizhou You, Chengyu Wang, et al., Jun Huang* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.03463)], [[PDF](https://arxiv.org/pdf/2308.03463.pdf)], [[Home Page](https://anonymous456852.github.io/)] <br>
- **SimDA: Simple Diffusion Adapter for Efficient Video Generation** <br>
  Team: Fudan University, Microsoft. <br>
  *Zhen Xing, Qi Dai, Han Hu, Zuxuan Wu, Yu-Gang Jiang* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.09710)], [[PDF](https://arxiv.org/pdf/2308.09710.pdf)], [[Code (Coming)](https://github.com/ChenHsing/SimDA)], [[Home Page](https://chenhsing.github.io/SimDA/)] <br>
- **Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models** <br>
  Team: National University of Singapore. <br>
  *Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Tat-Seng Chua* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.13812)], [[PDF](https://arxiv.org/pdf/2308.13812.pdf)], [[Code](https://github.com/scofield7419/Dysen-VDM)] <br>
- **ModelScope Text-to-Video Technical Report** <br>
  Team: Alibaba Group. <br>
  *Jiuniu Wang, Hangjie Yuan, Dayou Chen, et al., Shiwei Zhang* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.06571)], [[PDF](https://arxiv.org/pdf/2308.06571.pdf)], [[Code](https://github.com/modelscope/modelscope)], [[Home Page](https://modelscope.cn/models/iic/text-to-video-synthesis/summary)], [[[Demo(live)](https://huggingface.co/spaces/ali-vilab/modelscope-text-to-video-synthesis)] <br>
- **Dual-Stream Diffusion Net for Text-to-Video Generation** <br>
  Team: Nanjing University of Science and Technology. <br>
  *Binhui Liu, Xin Liu, Anbo Dai, et al., Jian Yang* <br>
  arXiv, 2023.08 [[Paper](https://arxiv.org/abs/2308.08316)], [[PDF](https://arxiv.org/pdf/2308.08316.pdf)] <br>
- **AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning** <br>
  Team: The Chinese University of Hong Kong. <br>
  *Yuwei Guo, Ceyuan Yang, Anyi Rao, et al., Bo Dai* <br>
  **ICLR'24 (spotlight)**, arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.04725)], [[PDF](https://arxiv.org/pdf/2307.04725.pdf)], [[Code](https://github.com/guoyww/AnimateDiff)], [[Pretrained Model](https://github.com/guoyww/AnimateDiff)], [[Home Page](https://animatediff.github.io/)] <br>
- **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** <br>
  Team: HKUST. <br>
  *Yingqing He, Menghan Xia, Haoxin Chen, et al., Qifeng Chen* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.06940)], [[PDF](https://arxiv.org/pdf/2307.06940.pdf)], [[Code](https://github.com/AILab-CVC/Animate-A-Story)], [[Home Page](https://ailab-cvc.github.io/Animate-A-Story/)], [[[Demo(video)](https://ailab-cvc.github.io/Animate-A-Story/)] <br>
- **Probabilistic Adaptation of Text-to-Video Models** <br>
  Team: Google, UC Berkeley. <br>
  *Mengjiao Yang, Yilun Du, Bo Dai, et al., Pieter Abbeel* <br>
  arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.01872)], [[PDF](https://arxiv.org/pdf/2306.01872.pdf)], [[Home Page](https://video-adapter.github.io/video-adapter/)] <br>
- **ED-T2V: An Efficient Training Framework for Diffusion-based Text-to-Video Generation** <br>
  Team: School of Artificial Intelligence, University of Chinese Academy of Sciences. <br>
  *Jiawei Liu, Weining Wang, Wei Liu, Qian He, Jing Liu* <br>
  IJCNN'23, 2023.06 [[Paper](https://ieeexplore.ieee.org/abstract/document/10191565)], [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10191565)] <br>
- **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** <br>
  Team: CUHK. <br>
  *Jinbo Xing, Menghan Xia, Yuxin Liu, et al., Tien-Tsin Wong* <br>
  arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.00943)], [[PDF](https://arxiv.org/pdf/2306.00943.pdf)], [[Code](https://github.com/AILab-CVC/Make-Your-Video)], [[Pretrained Model](https://huggingface.co/Doubiiu/Make-Your-Video/blob/main/model.ckpt)], [[Home Page](https://doubiiu.github.io/projects/Make-Your-Video/)] <br>
- **VideoComposer: Compositional Video Synthesis with Motion Controllability** <br>
  Team: Alibaba Group. <br>
  *Xiang Wang, Hangjie Yuan, Shiwei Zhang, et al., Jingren Zhou* <br>
  NeurIPS'23, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.02018)], [[PDF](https://arxiv.org/pdf/2306.02018.pdf)], [[Code](https://github.com/ali-vilab/videocomposer)], [[Pretrained Model](https://www.modelscope.cn/models/iic/VideoComposer/summary)], [[Home Page](https://videocomposer.github.io/)] <br>
- **VideoFusion: Decomposed Diffusion Models for High-Quality Video Generation** <br>
  Team: University of Chinese Academy of Sciences (UCAS), Alibaba Group. <br>
  *Zhengxiong Luo, Dayou Chen, Yingya Zhang, et al., Tieniu Tan* <br>
  CVPR'23, arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2303.08320)], [[PDF](https://arxiv.org/pdf/2303.08320.pdf)]<br>
- **DirecT2V: Large Language Models are Frame-Level Directors for Zero-Shot Text-to-Video Generation** `Training-free` <br>
  Team: Korea University. <br>
  *Susung Hong, Junyoung Seo, Heeseong Shin, Sunghwan Hong, Seungryong Kim* <br>
  arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.14330)], [[PDF](https://arxiv.org/pdf/2305.14330.pdf)] <br>
- **Sketching the Future (STF): Applying Conditional Control Techniques to Text-to-Video Models** <br>
  Team: Carnegie Mellon University. <br>
  *Rohan Dhesikan, Vignesh Rajmohan* <br>
  arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.05845)], [[PDF](https://arxiv.org/pdf/2305.05845.pdf)], [[Code(coming)](https://github.com/rohandkn/skribble2vid)] <br>
- **Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models** <br>
  Team: University of Maryland. <br>
  *Songwei Ge, Seungjun Nah, Guilin Liu, et al., Yogesh Balaji* <br>
  ICCV'23, arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.10474)], [[PDF](https://arxiv.org/pdf/2305.10474.pdf)], [[Home Page](https://research.nvidia.com/labs/dir/pyoco/)] <br>
- **Cinematic Mindscapes: High-quality Video Reconstruction from Brain Activity** <br>
  Team: NUS, CUHK. <br>
  *Zijiao Chen, Jiaxin Qing, Juan Helen Zhou* <br>
  NeurIPS'24, arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.11675)], [[PDF](https://arxiv.org/pdf/2305.11675.pdf)], [[Code](https://github.com/jqin4749/MindVideo)], [[Home Page](https://mind-video.com)] <br>
- **VideoPoet: A Large Language Model for Zero-Shot Video Generation** <br>
  Team: Google Research <br>
  *Dan Kondratyuk, Lijun Yu, Xiuye Gu, et al., Lu Jiang* <br>
  arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2312.14125)], [[PDF](https://arxiv.org/pdf/2312.14125.pdf)], [[Home Page](https://sites.research.google/videopoet/)], [[Blog](https://blog.research.google/2023/12/videopoet-large-language-model-for-zero.html)] <br>
- **VideoDreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning** <br>
  Team: Tsinghua University, Beijing Film Academy <br>
  *Hong Chen, Xin Wang, Guanning Zeng, et al., WenwuZhu* <br>
  arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2311.00990)], [[PDF](https://arxiv.org/pdf/2311.00990.pdf)], [[Code](https://github.com/videodreamer23/videodreamer23.github.io)], [[Home Page](https://videodreamer23.github.io/)] <br>
- **Text2Performer: Text-Driven Human Video Generation** <br>
  Team: Nanyang Technological University <br>
  *Yuming Jiang, Shuai Yang, Tong Liang Koh, et al., Ziwei Liu* <br>
  arXiv, 2023.04 [[Paper](https://arxiv.org/abs/2304.08483)], [[PDF](https://arxiv.org/pdf/2304.08483.pdf)], [[Code](https://github.com/yumingj/Text2Performer)], [[Home Page](https://yumingj.github.io/projects/Text2Performer.html)], [[[Demo(video)](https://www.youtube.com/watch?v=YwhaJUk_qo0)] <br>
- **Latent-Shift: Latent Diffusion with Temporal Shift for Efficient Text-to-Video Generation** <br>
  Team: University of Rochester, Meta. <br>
  *Jie An, Songyang Zhang, Harry Yang, et al., Xi Yin* <br>
  arXiv, 2023.04 [[Paper](https://arxiv.org/abs/2304.08477)], [[PDF](https://arxiv.org/pdf/2304.08477.pdf)], [[Home Page](https://latent-shift.github.io/)] <br>
- **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** <br>
  Team: Tsinghua University, HKUST. <br>
  *Yue Ma, Yingqing He, Xiaodong Cun, et al., Qifeng Chen* <br>
  AAAI'24, arXiv, 2023.04 [[Paper](https://arxiv.org/abs/2304.01186)], [[PDF](https://arxiv.org/pdf/2304.01186.pdf)], [[Home Page](https://follow-your-pose.github.io/)], [[Code](https://github.com/mayuelala/FollowYourPose)] <br>
- **Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models** <br>
  Team: NVIDIA. <br>
  *Andreas Blattmann, Robin Rombach, Huan Ling, et al., Karsten Kreis* <br>
  CVPR'23, arXiv, 2023.04 [[Paper](https://arxiv.org/abs/2304.08818)], [[PDF](https://arxiv.org/pdf/2304.08818.pdf)], [[Home Page](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)] <br>
- **NUWA-XL: Diffusion over Diffusion for eXtremely Long Video Generation** <br>
  Team: University of Science and Technology of China, Microsoft. <br>
  *Shengming Yin, Chenfei Wu, Huan Yang, et al. , Nan Duan* <br>
  arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.12346)], [[PDF](https://arxiv.org/pdf/2303.12346.pdf)], [[Home Page](https://msra-nuwa.azurewebsites.net/#/NUWAXL)] <br>
- **Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators** <br>
  Team: Picsart AI Resarch (PAIR). <br>
  *Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, et al., Humphrey Shi* <br>
  arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.13439)], [[PDF](https://arxiv.org/pdf/2303.13439.pdf)], [[Code](https://github.com/Picsart-AI-Research/Text2Video-Zero)], [[Home Page](https://text2video-zero.github.io/)], [[Demo(live)](https://huggingface.co/spaces/PAIR/Text2Video-Zero)], [[Demo(video)](https://www.dropbox.com/s/uv90mi2z598olsq/Text2Video-Zero.MP4?dl=0)] <br>
- **Structure and Content-Guided Video Synthesis with Diffusion Models** <br>
  Team: Runway <br>
  *Patrick Esser, Johnathan Chiu, Parmida Atighehchian, Jonathan Granskog, Anastasis Germanidis* <br>
  ICCV'23, arXiv, 2023.02 [[Paper](https://arxiv.org/abs/2302.03011)], [[PDF](https://arxiv.org/pdf/2302.03011.pdf)], [[Home Page](https://research.runwayml.com/gen1)] <br>
- **SceneScape: Text-Driven Consistent Scene Generation** <br>
  Team: Weizmann Institute of Science, NVIDIA Research <br>
  *Rafail Fridman, Amit Abecasis, Yoni Kasten, Tali Dekel* <br>
  NeurIPS'23, arXiv, 2023.02 [[Paper](https://arxiv.org/abs/2302.01133)], [[PDF](https://arxiv.org/pdf/2302.01133.pdf)], [[Code](https://github.com/RafailFridman/SceneScape)], [[Home Page](https://scenescape.github.io)] <br>
- **MM-Diffusion: Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation** <br>
  Team: Renmin University of China, Peking University, Microsoft Research  <br>
  *Ludan Ruan, Yiyang Ma, Huan Yang, et al., Baining Guo* <br>
  CVPR'23, arXiv, 2022.12 [[Paper](https://arxiv.org/abs/2212.09478)], [[PDF](https://arxiv.org/pdf/2212.09478.pdf)], [[Code](https://github.com/researchmm/MM-Diffusion?tab=readme-ov-file)] <br>
- **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation** <br>
  Team: Show Lab, National University of Singapore. <br>
  *Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, Mike Zheng Shou et al* <br>
  **ICCV'23**, arxiv, 2022.12[[Paper](https://arxiv.org/abs/2212.11565)], [[PDF](https://arxiv.org/pdf/2212.11565.pdf)], [[Code](https://github.com/showlab/Tune-A-Video)], [[Pretrained Model](https://huggingface.co/Tune-A-Video-library)]  <br>
- **MagicVideo: Efficient Video Generation With Latent Diffusion Models** <br>
  Team: ByteDance Inc. <br>
  *Daquan Zhou, Weimin Wang, Hanshu Yan, et al., Jiashi Feng* <br>
  arXiv, 2022.11 [[Paper](https://arxiv.org/abs/2211.11018)], [[PDF](https://arxiv.org/pdf/2211.11018.pdf)], [[Home Page](https://magicvideo.github.io/)] <br>
- **Latent Video Diffusion Models for High-Fidelity Long Video Generation** `Long Video` <br>
  Team: HKUST, Tencent AI Lab. <br>
  *Yingqing He, Tianyu Yang, Yong Zhang, Ying Shan, Qifeng Chen* <br>
  arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2211.13221)], [[PDF](https://arxiv.org/pdf/2211.13221.pdf)], [[Code](https://github.com/YingqingHe/LVDM)], [[Home Page](https://yingqinghe.github.io/LVDM/)] <br>
- **Tell Me What Happened: Unifying Text-guided Video Completion via Multimodal Masked Video Generation** <br>
  Team: UC Santa Barbara, Meta. <br>
  *Tsu-Jui Fu, Licheng Yu, Ning Zhang, et al., Sean Bell* <br>
  CVPR'23, arXiv, 2022.11 [[Paper](https://arxiv.org/abs/2211.12824)], [[PDF](https://arxiv.org/pdf/2211.12824.pdf)]<br>
- **Phenaki: Variable Length Video Generation From Open Domain Textual Description** <br>
  Team: Google. <br>
  *Ruben Villegas, Mohammad Babaeizadeh, Pieter-Jan Kindermans, et al., Dumitru Erhan* <br>
  ICLR'23, arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2210.02399)], [[PDF](https://arxiv.org/pdf/2210.02399.pdf)], [[Home Page](https://sites.research.google/phenaki/)] <br>
- **Imagen Video: High Definition Video Generation with Diffusion Models** <br>
  Team: Google. <br>
  *Jonathan Ho, William Chan, Chitwan Saharia, et al., Tim Salimans* <br>
  arXiv, 2022.10 [[Paper](https://arxiv.org/abs/2210.02303)], [[PDF](https://arxiv.org/pdf/2210.02303.pdf)], [[Home Page](https://imagen.research.google/video/)] <br>
- **StoryDALL-E: Adapting Pretrained Text-to-Image Transformers for Story Continuation** `Story Visualization` <br>
  Team: UNC Chapel Hill. <br>
  *Adyasha Maharana, Darryl Hannan, Mohit Bansal* <br>
  ECCV'22, arXiv, 2022.09 [[Paper](https://arxiv.org/abs/2209.06192)], [[PDF](https://arxiv.org/pdf/2209.06192.pdf)], [[Code](https://github.com/adymaharana/storydalle)], [[Demo(live)](https://replicate.com/adymaharana/story-dalle)] <br>
- **Make-A-Video: Text-to-Video Generation without Text-Video Data** <br>
  Team: Meta AI. <br>
  *Uriel Singer, Adam Polyak, Thomas Hayes, et al., Yaniv Taigman* <br>
  ICLR'23, arXiv, 2022.09 [[Paper](https://arxiv.org/abs/2209.14792)], [[PDF](https://arxiv.org/pdf/2209.14792.pdf)], [[Code](https://github.com/SooLab/Free-Bloom)]<br>
- **MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model**  <br>
  Team: S-Lab, SenseTime. <br>
  *Mingyuan Zhang, Zhongang Cai, Liang Pan, et al., Ziwei Liu* <br>
  TPAMI'24, arxiv, 2022.08 [[Paper](https://arxiv.org/abs/2208.15001)], [[PDF](https://arxiv.org/pdf/2208.15001.pdf)], [[Code](https://github.com/mingyuan-zhang/MotionDiffuse)], [[Home Page](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10416192)], [[Demo](https://huggingface.co/spaces/mingyuan/MotionDiffuse)]<br>
- **Word-Level Fine-Grained Story Visualization** `Story Visualization` <br>
  Team: University of Oxford. <br>
  *Bowen Li, Thomas Lukasiewicz* <br>
  ECCV'22, arXiv, 2022.08 [[Paper](https://arxiv.org/abs/2208.02341)], [[PDF](https://arxiv.org/pdf/2208.02341.pdf)], [[Code](https://github.com/mrlibw/Word-Level-Story-Visualization)], [[Pretrained Model](https://github.com/mrlibw/Word-Level-Story-Visualization)]<br>
- **CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers** <br>
  Team: Tsinghua University. <br>
  *Wenyi Hong, Ming Ding, Wendi Zheng, Xinghan Liu, Jie Tang* <br>
  ICLR'23, arXiv, 2022.05 [[Paper](https://arxiv.org/abs/2205.15868)], [[PDF](https://arxiv.org/pdf/2205.15868.pdf)], [[Code](https://github.com/THUDM/CogVideo)], [[Home Page](https://models.aminer.cn/cogvideo/)], [[Demo(video)](https://huggingface.co/spaces/THUDM/CogVideo)] <br>
- **CogView2: Faster and Better Text-to-Image Generation via Hierarchical Transformers** <br>
  Team: Tsinghua University. <br>
  *Ming Ding, Wendi Zheng, Wenyi Hong, Jie Tang* <br>
  NeurIPS'22, arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.14217)], [[PDF](https://arxiv.org/pdf/2204.14217.pdf)], [[Code](https://github.com/THUDM/CogView2)], [[Home Page](https://replicate.com/thudm/cogview2)] <br>
- **Long video generation with time-agnostic vqgan and time-sensitive transformer** <br>
  Team: Meta AI. <br>
  *Songwei Ge, Thomas Hayes, Harry Yang, et al., Devi Parikh* <br>
  **ECCV'22** arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.03638)], [[PDF](https://arxiv.org/pdf/2204.03638.pdf)], [[Home Page](https://songweige.github.io/projects/tats/)], [[Code](https://github.com/SongweiGe/TATS)] <br>
- **Video Diffusion Models** `text-conditioned` <br>
  Team: Google. <br>
  *Jonathan Ho, Tim Salimans, Alexey Gritsenko, et al., David J. Fleet* <br>
  arXiv, 2022.04 [[Paper](https://arxiv.org/abs/2204.03458)], [[PDF](https://arxiv.org/pdf/2204.03458.pdf)], [[Home Page](https://video-diffusion.github.io/)] <br>
- **NUWA-Infinity: Autoregressive over Autoregressive Generation for Infinite Visual Synthesis** `Long Video` <br>
  Team: Microsoft. <br>
  *Chenfei Wu, Jian Liang, Xiaowei Hu, et al., Nan Duan* <br>
  NeurIPS'22, arXiv, 2022.02 [[Paper](https://arxiv.org/abs/2207.09814)], [[PDF](https://arxiv.org/pdf/2207.09814.pdf)], [[Code](https://github.com/microsoft/NUWA)], [[Home Page](https://nuwa-infinity.microsoft.com/#/)] <br>
- **NÜWA: Visual Synthesis Pre-training for Neural visUal World creAtion** <br>
  Team: Microsoft. <br>
  *Chenfei Wu, Jian Liang, Lei Ji, et al., Nan Duan* <br>
  ECCV'22, arXiv, 2021.11 [[Paper](https://arxiv.org/abs/2111.12417)], [[PDF](https://arxiv.org/pdf/2111.12417.pdf)], [[Code](https://github.com/microsoft/NUWA)]<br>
- **GODIVA: Generating Open-DomaIn Videos from nAtural Descriptions** <br>
  Team: Microsoft, Duke University. <br>
  *Chenfei Wu, Lun Huang, Qianxi Zhang, et al., Nan Duan* <br>
  arXiv, 2021.04 [[Paper](https://arxiv.org/abs/2104.14806)], [[PDF](https://arxiv.org/pdf/2104.14806.pdf)] <br>
- **Cross-Modal Dual Learning for Sentence-to-Video Generation** <br>
  Team: Tsinghua University. <br>
  *Yue Liu, Xin Wang, Yitian Yuan, Wenwu Zhu* <br>
  ACM MM'19 [[Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3350986)], [[PDF](https://dl.acm.org/doi/pdf/10.1145/3343031.3350986)]
- **IRC-GAN: introspective recurrent convolutional GAN for text-to-video generation** <br>
  Team: Peking University. <br>
  *Kangle Deng, Tianyi Fei, Xin Huang, Yuxin Peng* <br>
  IJCAI'19 [[Paper](https://dl.acm.org/doi/abs/10.5555/3367243.3367347)], [[PDF](https://www.ijcai.org/Proceedings/2019/0307.pdf)]
- **Imagine this! scripts to compositions to videos** <br>
  Team: University of Illinois Urbana-Champaign, AI2, University of Washington. <br>
  *Tanmay Gupta, Dustin Schwenk, Ali Farhadi, et al., Aniruddha Kembhavi* <br>
  ECCV'18, arxiv, 2018.04 [[Paper](https://arxiv.org/abs/1804.03608)], [[PDF](https://arxiv.org/pdf/1804.03608.pdf)]
- **To Create What You Tell: Generating Videos from Captions** <br>
  Team: USTC, Microsoft Research. <br>
  *Yingwei Pan, Zhaofan Qiu, Ting Yao, et al., Tao Mei* <br>
  ACM MM'17, arxiv, 2018.04 [[Paper](https://arxiv.org/abs/1804.08264)], [[PDF](https://arxiv.org/pdf/1804.08264.pdf)]
- **Neural Discrete Representation Learning.** <br>
  Team: DeepMind. <br>
  *Aaron van den Oord, Oriol Vinyals, Dinghan Shen, Koray Kavukcuoglu* <br>
  NeurIPS'17, arxiv, 2017.11 [[Paper](https://arxiv.org/abs/1711.00937)], [[PDF](https://arxiv.org/pdf/1711.00937.pdf)] <br>
- **Video Generation From Text.** <br>
  Team: Duke University, NEC Labs America. <br>
  *Yitong Li, Martin Renqiang Min, Dinghan Shen, et al., Lawrence Carin* <br>
  AAAI'18, arxiv, 2017.10 [[Paper](https://arxiv.org/abs/1710.00421)], [[PDF](https://arxiv.org/pdf/1710.00421.pdf)] <br>
- **Attentive semantic video generation using captions.** <br>
  Team: IIT Hyderabad. <br>
  *Tanya Marwah, Gaurav Mittal, Vineeth N. Balasubramanian* <br>
  ICCV'17, arxiv, 2017.08 [[Paper](https://arxiv.org/abs/1708.05980)], [[PDF](https://arxiv.org/pdf/1708.05980.pdf)] <br>
- **Sync-DRAW: Automatic Video Generation using Deep Recurrent Attentive Architectures** `VAE` <br>
  Team: IIT Hyderabad. <br>
  *Gaurav Mittal, Tanya Marwah, Vineeth N. Balasubramanian* <br>
  ACM MM'17, arXiv, 2016.11 [[Paper](https://arxiv.org/abs/1611.10314)], [[PDF](https://arxiv.org/pdf/1611.10314.pdf)] <br>

## <a name="dataset_and_metrics"></a> Datasets & Metrics
Datasets are divided according to their collected domains: `Face, Open, Movie, Action, Instruct`. <br>
Metrics are divided as `image-level, video-level`. <br>

|       Dataset |    Domain |  Annotated |  #Clips |   #Sent |  Len_C(s) |  Len_S |  #Videos |  Resolution |  FPS |  Dur(h) |  Year  |   Source |
|--------------:|----------:|-----------:|--------:|--------:|----------:|-------:|---------:|------------:|-----:|--------:|:------:|---------:|
|   **CV-Text** |      Face |  Generated |     70K |   1400K |         - |   67.2 |        - |        480P |    - |       - |  2023  |   Online |
|   **MSR-VTT** |      Open |     Manual |     10K |    200K |     15.0s |    9.3 |     7.2K |        240P |   30 |      40 |  2016  |  YouTube |
|    **DideMo** |      Open |     Manual |     27K |     41K |      6.9s |    8.0 |    10.5K |           - |    - |      87 |  2017  |   Flickr |
|  **Y-T-180M** |      Open |        ASR |    180M |       - |         - |      - |       6M |           - |    - |       - |  2021  |  YouTube |
|    **WVid2M** |      Open |   Alt-text |    2.5M |    2.5M |      18.0 |   12.0 |     2.5M |        360P |    - |     13K |  2021  |      Web |
|    **H-100M** |      Open |        ASR |    103M |       - |      13.4 |   32.5 |     3.3M |        720P |    - |  371.5K |  2022  |  YouTube |
| **InternVid** |      Open |  Generated |    234M |       - |      11.7 |   17.6 |     7.1M |       *720P |    - |  760.3K |  2023  |  YouTube |
|    **H-130M** |      Open |  Generated |    130M |    130M |         - |   10.0 |        - |        720P |    - |       - |  2023  |  YouTube |
|      **Y-mP** |      Open |     Manual |     10M |     10M |      54.2 |      - |        - |           - |    - |    150K |  2023  |    Youku |
|     **V-27M** |      Open |  Generated |     27M |    135M |      12.5 |      - |        - |           - |    - |       - |  2024  |  YouTube |
|     **P-70M** |      Open |  Generated |       - |   70.8M |       8.5 |   13.2 |    70.8M |        720P |    - |  166.8K |  2024  |  YouTube |
| **ChronoMagic-Pro** |      Open |  Generated |       - |   - |       234.1 |   - |    460K |        720P |    - |  30.0K |  2024  |  YouTube |
|     **LSMDC** |     Movie |     Manual |    118K |    118K |      4.8s |    7.0 |      200 |       1080P |    - |     158 |  2017  |    Movie |
|       **MAD** |     Movie |     Manual |       - |    384K |         - |   12.7 |      650 |           - |    - |    1.2K |  2022  |    Movie |
|   **UCF-101** |    Action |     Manual |     13K |       - |      7.2s |      - |        - |        240P |   25 |      27 |  2012  |  YouTube |
|  **ANet-200** |    Action |     Manual |    100K |       - |         - |   13.5 |       2K |       *720P |   30 |     849 |  2015  |  YouTube |
|  **Charades** |    Action |     Manual |     10K |     16K |         - |      - |      10K |           - |    - |      82 |  2016  |     Home |
|  **Kinetics** |    Action |     Manual |    306K |       - |     10.0s |      - |     306K |           - |    - |       - |  2017  |  YouTube |
|    **ActNe**t |    Action |     Manual |    100K |    100K |     36.0s |   13.5 |      20K |           - |    - |     849 |  2017  |  YouTube |
|     **C-Ego** |    Action |     Manual |       - |       - |         - |      - |       8K |        240P |    - |      69 |  2018  |     Home |
|     **SS-V2** |    Action |     Manual |       - |       - |         - |      - |   220.1K |           - |   12 |       - |  2018  |    Daily |
|      **How2** |  Instruct |     Manual |     80K |     80K |      90.0 |   20.0 |    13.1K |           - |    - |    2000 |  2018  |  YouTube |
|    **HT100M** |  Instruct |        ASR |    136M |    136M |       3.6 |    4.0 |     1.2M |        240P |    - |  134.5K |  2019  |  YouTube |
|    **YCook2** |   Cooking |     Manual |     14K |     14K |      19.6 |    8.8 |       2K |           - |    - |     176 |  2018  |  YouTube |
|     **E-Kit** |   Cooking |     Manual |     40K |     40K |         - |      - |      432 |      *1080P |   60 |      55 |  2018  |     Home |

- (ShareGPT4Video) **ShareGPT4Video: Improving Video Understanding and Generation with Better Captions** `Dataset (adding)` <br>
  Team: USTC, CUHK, PKU, Shanghai AI Lab. <br>
  *Lin Chen, Xilin Wei, Jinsong Li, et al., Jiaqi Wang* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.04325)], [[PDF](https://arxiv.org/pdf/2406.04325)], [[Code](https://github.com/ShareGPT4Omni/ShareGPT4Video)], [[Dataset](https://huggingface.co/datasets/ShareGPT4Video/ShareGPT4Video)], [[Home Page](https://sharegpt4video.github.io/)]

- (ChronoMagic-Pro) **ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation** <br>
  Team: Peking University, University of Rochester. <br>
  *Shenghai Yuan, Jinfa Huang, et al., Jiebo Luo, Li Yuan* <br>
  arXiv, 2024.04 [[Paper](https://arxiv.org/abs/2406.18522)], [[PDF](https://arxiv.org/abs/2406.18522)], [[Code](https://github.com/PKU-YuanGroup/ChronoMagic-Bench)], [[Home Page](https://pku-yuangroup.github.io/ChronoMagic-Bench/)] <br>
  
- (VideoPhy) **VideoPhy: Evaluating Physical Commonsense for Video Generation** `Dataset (adding)` <br>
  Team: University of California Los Angeles, Google Research. <br>
  *Hritik Bansal, Zongyu Lin, Tianyi Xie, et al., Aditya Grover* <br>
  arXiv, 2024.06 [[Paper](https://arxiv.org/abs/2406.03520)], [[PDF](https://arxiv.org/pdf/2406.03520)], [[Code](https://github.com/Hritikbansal/videophy)], [[Hugging Face](https://huggingface.co/videophysics/videocon_physics/tree/main)], [[Home Page](https://videophy.github.io/)]

- (GenAI-Bench) **Evaluating Text-to-Visual Generation with Image-to-Text Generation** `Dataset (adding)` <br>
  Team: CMU, Meta. <br>
  *Zhiqiu Lin, Deepak Pathak, Baiqi Li, et al., Deva Ramanan* <br>
  arXiv, 2024.04 [[Paper](https://arxiv.org/abs/2404.01291)], [[PDF](https://arxiv.org/pdf/2404.01291)], [[Code](https://github.com/linzhiqiu/t2v_metrics)], [[Home Page](https://linzhiqiu.github.io/papers/vqascore/)]

- (VidProM) **VidProM: A Million-scale Real Prompt-Gallery Dataset for Text-to-Video Diffusion Models** `Dataset (adding)` <br>
  Team: ReLER Lab. <br>
  *Wenhao Wang, Yi Yang* <br>
  arXiv, 2024.03 [[Paper](https://arxiv.org/abs/2403.06098)], [[PDF](https://arxiv.org/pdf/2403.06098.pdf)], [[Code](https://github.com/WangWenhao0716/VidProM)], [[Hugging Face](https://huggingface.co/datasets/WenhaoWang/VidProM)]

- (ECTV) **EvalCrafter: Benchmarking and Evaluating Large Video Generation Models** `Dataset (adding)`<br>
  Team: Tencent AI Lab, CUHK. <br>
  *Yaofang Liu, Xiaodong Cun, Xuebo Liu, et al., Ying Shan* <br>
  CVPR'24, arXiv, 2023.10 [[Paper](https://arxiv.org/abs/2310.11440)], [[PDF](https://arxiv.org/pdf/2310.11440.pdf)], [[Code](https://github.com/EvalCrafter/EvalCrafter)], [[Dataset](https://huggingface.co/datasets/RaphaelLiu/EvalCrafter_T2V_Dataset)], [[Home Page](https://evalcrafter.github.io/)]

- (CV-Text) **Celebv-text: A large-scale facial text-video datase** `Dataset (Domain:Face)`<br>
  Team: University of Sydney, SenseTime Research. <br>
  *Jianhui Yu, Hao Zhu, Liming Jiang, et al., Wayne Wu* <br>
  CVPR'23, arXiv, 2023.03 [[Paper](https://arxiv.org/abs/2303.14717)], [[PDF](https://arxiv.org/pdf/2303.14717.pdf)], [[Code](https://github.com/CelebV-Text/CelebV-Text)], [[Demo](https://www.youtube.com/watch?v=0TS1hQwjNWw)], [[Home Page](https://celebv-text.github.io/)]


- (MSR-VTT) **Msr-vtt: A large video description dataset for bridging video and language** `Dataset (Domain:Open)`<br>
  Team: Microsoft Research. <br>
  *Jun Xu , Tao Mei , Ting Yao and Yong Rui* <br>
  CVPR'16 [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Xu_MSR-VTT_A_Large_CVPR_2016_paper.html)], [[PDF](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_MSR-VTT_A_Large_CVPR_2016_paper.pdf)]


- (DideMo) **Localizing moments in video with natural language** `Dataset (Domain:Open)`<br>
  Team: UC Berkeley, Adobe <br>
  *Lisa Anne Hendricks, Oliver Wang, Eli Shechtman, et al., Bryan Russell* <br>
  ICCV'17, arXiv, 2017.08 [[Paper](https://arxiv.org/abs/1708.01641)], [[PDF](https://arxiv.org/pdf/1708.01641.pdf)]


- (YT-Tem-180M) **Merlot: Multimodal neural script knowledge models** `Dataset (Domain:Open)`<br>
  Team: University of Washington <br>
  *Rowan Zellers, Ximing Lu, Jack Hessel, et al., Yejin Choi* <br>
  NeurIPS'21, arXiv, 2021.06 [[Paper](https://arxiv.org/abs/2106.02636)], [[PDF](https://arxiv.org/pdf/2106.02636.pdf)], [[Code](https://github.com/rowanz/merlot)], [[Home Page](https://rowanzellers.com/merlot/)]

- (WebVid2M) **Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval** `Dataset (Domain:Open)`<br>
  Team: University of Oxford, CNRS. <br>
  *Max Bain, Arsha Nagrani, Gül Varol, Andrew Zisserman* <br>
  ICCV'21, arXiv, 2021.04 [[Paper](https://arxiv.org/abs/2104.00650)], [[PDF](https://arxiv.org/pdf/2104.00650.pdf)],[[Dataset](https://maxbain.com/webvid-dataset/)], [[Code](https://github.com/m-bain/frozen-in-time)],[[Demo](https://meru.robots.ox.ac.uk/frozen-in-time/)], [[Home Page](https://www.robots.ox.ac.uk/~vgg/research/frozen-in-time/)]


- (HD-VILA-100M) **Advancing High-Resolution Video-Language Representation with Large-Scale Video Transcriptions** `Dataset (Domain:Open)`<br>
  Team: Microsoft Research Asia. <br>
  *Hongwei Xue, Tiankai Hang, Yanhong Zeng, et al., Baining Guo* <br>
  CVPR'22, arXiv, 2021.11 [[Paper](https://arxiv.org/abs/2111.10337)], [[PDF](https://arxiv.org/pdf/2111.10337.pdf)], [[Code](https://github.com/microsoft/XPretrain/tree/main/hd-vila)]

- (InterVid) **Internvid: A large-scale video-text dataset for multimodal understanding and generation** `Dataset (Domain:Open)`<br>
  Team: Shanghai AI Laboratory. <br>
  *Yi Wang, Yinan He, Yizhuo Li, et al., Yu Qiao* <br>
  arXiv, 2023.07 [[Paper](https://arxiv.org/abs/2307.06942)], [[PDF](https://arxiv.org/pdf/2307.06942.pdf)], [[Code](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid)]

- (HD-VG-130M) **VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation** `Dataset (Domain:Open)`<br>
  Team: Peking University, Microsoft Research. <br>
  *Wenjing Wang, Huan Yang, Zixi Tuo, et al., Jiaying Liu* <br>
  arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.10874)], [[PDF](https://arxiv.org/pdf/2305.10874.pdf)]

- (Youku-mPLUG) **Youku-mPLUG: A 10 Million Large-scale Chinese Video-Language Pre-training Dataset and Benchmarks** `Dataset (Domain:Open)`<br>
  Team: DAMO Academy, Alibaba Group. <br>
  *Haiyang Xu, Qinghao Ye, Xuan Wu, et al., Fei Huang* <br>
  arXiv, 2023.06 [[Paper](https://arxiv.org/abs/2306.04362)], [[PDF](https://arxiv.org/pdf/2306.04362.pdf)]

- (VAST-27M) **Vast: A vision-audio-subtitle-text omni-modality foundation model and dataset** `Dataset (Domain:Open)`<br>
  Team: UCAS, CAS <br>
  *Sihan Chen, Handong Li, Qunbo Wang, et al., Jing Liu* <br>
  NeurIPS'23, arXiv, 2023.05 [[Paper](https://arxiv.org/abs/2305.18500)], [[PDF](https://arxiv.org/pdf/2305.18500.pdf)]

- (Panda-70M) **Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers**  `Dataset (Domain:Open)`<br>
  Team: Snap Inc., University of California, University of Trento. <br>
  *Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Sergey Tulyakov* <br>
  arXiv, 2024.02 [[Paper](https://arxiv.org/abs/2402.19479)], [[PDF](https://arxiv.org/pdf/2402.19479.pdf)], [[Code](https://github.com/snap-research/Panda-70M)], [[Home Page](https://snap-research.github.io/Panda-70M/)]

- (LSMDC) **Movie description** `Dataset (Domain:Movie)` <br>
  Team: Max Planck Institute for Informatics. <br>
  *Anna Rohrbach, Atousa Torabi, Marcus Rohrbach, et al., Bernt Schiele* <br>
  IJCV'17, arXiv, 2016.05 [[Paper](https://arxiv.org/abs/1605.03705)], [[PDF](https://arxiv.org/pdf/1605.03705.pdf)], [[Home Page](https://sites.google.com/site/describingmovies/)]

- (MAD) **Mad: A scalable dataset for language grounding in videos from movie audio descriptions** `Dataset (Domain:Movie)` <br>
  Team: KAUST, Adobe Research. <br>
  *Mattia Soldan, Alejandro Pardo, Juan León Alcázar, et al., Bernard Ghanem* <br>
  CVPR'22, arXiv, 2021.12 [[Paper](https://arxiv.org/abs/2112.00431)], [[PDF](https://arxiv.org/pdf/2112.00431.pdf)], [[Code](https://github.com/Soldelli/MAD)]

- (UCF-101) **UCF101: A dataset of 101 human actions classes from videos in the wild** `Dataset (Domain:Action)` <br>
  Team: University of Central Florida. <br>
  *Khurram Soomro, Amir Roshan Zamir, Mubarak Shah* <br>
  arXiv, 2012.12 [[Paper](https://arxiv.org/abs/1212.0402)], [[PDF](https://arxiv.org/pdf/1212.0402.pdf)], [[Data](https://www.crcv.ucf.edu/data/UCF101.php)]

- (ActNet-200) **Activitynet: A large-scale video benchmark for human activity understanding** `Dataset (Domain:Action)` <br>
  Team: Universidad del Norte, KAUST <br>
  *Fabian Caba Heilbron, Victor Escorcia, Bernard Ghanem, Juan Carlos Niebles* <br>
  CVPR'15, [[Paper](https://openaccess.thecvf.com/content_cvpr_2015/html/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.html)], [[PDF](https://openaccess.thecvf.com/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf)], [[Home Page](http://activity-net.org/)]

- (Charades) **Hollywood in homes: Crowdsourcing data collection for activity understanding** `Dataset (Domain:Action)` <br>
  Team: Carnegie Mellon University <br>
  *Gunnar A. Sigurdsson, Gül Varol, Xiaolong Wang, et al., Abhinav Gupta* <br>
  ECCV'16, arXiv, 2016.04, [[Paper](https://arxiv.org/abs/1604.01753)], [[PDF](https://arxiv.org/pdf/1604.01753.pdf)], [[Home Page](https://prior.allenai.org/projects/charades)]

- (Kinetics) **The kinetics human action video dataset** `Dataset (Domain:Action)` <br>
  Team: Google <br>
  *Will Kay, Joao Carreira, Karen Simonyan, et al., Andrew Zisserman* <br>
  arXiv, 2017.05, [[Paper](https://arxiv.org/abs/1705.06950)], [[PDF](https://arxiv.org/pdf/1705.06950.pdf)], [[Home Page](https://deepmind.google/)]

- (ActivityNet) **Dense-captioning events in videos** `Dataset (Domain:Action)` <br>
  Team: Stanford University <br>
  *Ranjay Krishna, Kenji Hata, Frederic Ren, et al., Juan Carlos Niebles* <br>
  ICCV'17, arXiv, 2017.05, [[Paper](https://arxiv.org/abs/1705.00754v1)], [[PDF](https://arxiv.org/pdf/1705.00754v1.pdf)], [[Home Page](https://cs.stanford.edu/people/ranjaykrishna/densevid/)]

- (Charades-Ego) **Charades-ego: A large-scale dataset of paired third and first person videos** `Dataset (Domain:Action)` <br>
  Team: Carnegie Mellon University <br>
  *Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, et al., Karteek Alahari* <br>
  arXiv, 2018.04, [[Paper](https://arxiv.org/abs/1804.09626)], [[PDF](https://arxiv.org/pdf/1804.09626.pdf)], [[Home Page](https://prior.allenai.org/projects/charades-ego)]


- (SS-V2) **The "something something" video database for learning and evaluating visual common sense** `Dataset (Domain:Action)` <br>
  *Raghav Goyal, Samira Ebrahimi Kahou, Vincent Michalski, et al., Roland Memisevic* <br>
  ICCV'17, arXiv, 2017.06 [[Paper](https://arxiv.org/abs/1706.04261)], [[PDF](https://arxiv.org/pdf/1706.04261.pdf)], [[Home Page](https://developer.qualcomm.com/software/ai-datasets/something-something)]
- (How2) **How2: a large-scale dataset for multimodal language understanding** `Dataset (Domain:Instruct)` <br>
  Team: Carnegie Mellon University. <br>
  *Ramon Sanabria, Ozan Caglayan, Shruti Palaskar, et al., Florian Metze* <br>
  arXiv, 2018.11 [[Page](https://arxiv.org/abs/1811.00347)], [[PDF](https://arxiv.org/pdf/1811.00347.pdf)]
- (HowTo100M) **HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips** `Dataset (Domain:Instruct)` <br>
  Team: Ecole Normale Superieure, Inria, CIIRC. <br>
  *Antoine Miech, Dimitri Zhukov, Jean-Baptiste Alayrac, et al., Josef Sivic* <br>
  arXiv, 2019.06 [[Page](https://arxiv.org/abs/1906.03327)], [[PDF](https://arxiv.org/pdf/1906.03327.pdf)], [[Home Page](https://www.di.ens.fr/willow/research/howto100m/)] <br>
- (YouCook2) **Towards automatic learning of procedures from web instructional video** `Dataset (Domain:Cooking)` <br>
  Team: University of Michigan, University of Rochester <br>
  *Luowei Zhou, Chenliang Xu, Jason J. Corso* <br>
  AAAI'18, arXiv, 2017.03 , [[Paper](https://arxiv.org/abs/1703.09788)], [[PDF](https://arxiv.org/pdf/1703.09788.pdf)],[[Home Page](http://youcook2.eecs.umich.edu/)]
- (Epic-Kichens) **Scaling egocentric vision: The epic-kitchens dataset** `Dataset (Domain:Cookding)` <br>
  Team: Uni. of Bristol, Uni. of Catania, Uni. of Toronto. <br>
  *Dima Damen, Hazel Doughty, Giovanni Maria Farinella, et al., Michael Wray* <br>
  ECCV'18, arXiv, 2018.04, [[Paper](https://arxiv.org/abs/1804.02748)], [[PDF](https://arxiv.org/pdf/1804.02748.pdf)], [[Home Page](https://epic-kitchens.github.io/2024)] <br>

- (PSNR/SSIM) **Image quality assessment: from error visibility to structural similarity** `Metric (image-level)` <br>
  Team: New York University. <br>
  *Zhou Wang, Alan Conrad Bovik, Hamid Rahim Sheikh, E.P. Simoncelli* <br>
  IEEE TIP, 2004.04. [[Paper](https://ieeexplore.ieee.org/abstract/document/1284395)], [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395)] <br>
- (IS) **Improved techniques for training gans** `Metric (image-level)` <br>
  Team: OpenAI <br>
  *Tim Salimans, Ian Goodfellow, Wojciech Zaremba, et al., Xi Chen* <br>
  NeurIPS'16, arXiv, 2016.06, [[Paper](https://arxiv.org/abs/1606.03498)], [[PDF](https://arxiv.org/pdf/1606.03498.pdf)], [[Code](https://github.com/openai/improved-gan)] <br>
- (FID) **Gans trained by a two time-scale update rule converge to a local nash equilibrium** `Metric (image-level)` <br>
  Team: Johannes Kepler University Linz <br>
  *Martin Heusel, Hubert Ramsauer, Thomas Unterthiner, et al., Sepp Hochreiter* <br>
  NeurIPS'17, arXiv, 2017.06 [[Paper](https://arxiv.org/abs/1706.08500)], [[PDF](https://arxiv.org/pdf/1706.08500.pdf)]

- (CLIP Score) **Learning transferable visual models from natural language supervision** `Metric (image-level)` <br>
  Team: OpenAI. <br>
  *Alec Radford, Jong Wook Kim, Chris Hallacy, et al., Ilya Sutskever* <br>
  ICML'21, arXiv, 2021.02 [[Paper](https://arxiv.org/abs/2103.00020)], [[PDF](https://arxiv.org/pdf/2103.00020.pdf)], [[Code](https://github.com/OpenAI/CLIP)] <br>

- (Video IS) **Train sparsely, generate densely: Memory-efficient unsupervised training of high-resolution temporal gan** `Metric (video-level)` <br>
  *Masaki Saito, Shunta Saito, Masanori Koyama, Sosuke Kobayashi* <br>
  IJCV'20, arXiv, 2018.11 [[Paper](https://arxiv.org/abs/1811.09245)], [[PDF](https://arxiv.org/pdf/1811.09245.pdf)], [[Code](https://github.com/pfnet-research/tgan2)]<br>
- (FVD/KVD) **FVD: A new metric for video generation** `Metric (video-level)` <br>
  Team: Johannes Kepler University, Google <br>
  *Thomas Unterthiner, Sjoerd van Steenkiste, Karol Kurach, et al., Sylvain Gelly* <br>
  ICLR'19, arXiv, 2018.12 [[Paper](https://arxiv.org/abs/1812.01717)], [[PDF](https://arxiv.org/pdf/1812.01717.pdf)], [[Code](https://github.com/google-research/google-research/tree/master/frechet_video_distance)]

- (FCS) **Tune-a-video: One-shot tuning of image diffusion models for text-to-video generation** `Metric (video-level)` <br>
  Team: Show Lab, National University of Singapore. <br>
  *Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, Mike Zheng Shou et al* <br>
  ICCV'23, arxiv, 2022.12[[Paper](https://arxiv.org/abs/2212.11565)], [[PDF](https://arxiv.org/pdf/2212.11565.pdf)], [[Code](https://github.com/showlab/Tune-A-Video)], [[Pretrained Model](https://huggingface.co/Tune-A-Video-library)]  <br>

----
## Acknowledgement and References
- [Awesome Text-to-Video Generation](https://github.com/feifeiobama/Awesome-Text-to-Video-Generation)
- [A Survey on Video Diffusion Models](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models)

## Citation
If you find this repository useful, please consider citing our paper and this list:
```
@article{sun2024sora,
  title={From Sora What We Can See: A Survey of Text-to-Video Generation},
  author={Sun, Rui and Zhang, Yumin and Shah, Tejal and Sun, Jiahao and Zhang, Shuoying and Li, Wenqi and Duan, Haoran and Wei, Bo and Ranjan, Rajiv},
  journal={arXiv preprint arXiv:2405.10674},
  year={2024}
}

@misc{sun2024t2vgenerationlist,
  title={Awesome-Text-to-Video-Generation},
  author={Sun, Rui and Zhang, Yumin},
  year={2024},
  publisher={GitHub},
  howpublished={\url{https://github.com/soraw-ai/Awesome-Text-to-Video-Generation}},
}
```


