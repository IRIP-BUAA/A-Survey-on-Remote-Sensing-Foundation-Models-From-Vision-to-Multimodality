# A-Review-for-remote-sensing-vision-language-models
This is a repository for ...
## Overleaf
https://www.overleaf.com/5469324254jsdvcqwcsmzz#0edfd1

## Table of Contents
- [A-Review-for-remote-sensing-vision-language-models](#a-review-for-remote-sensing-vision-language-models)
  - [Overleaf](#overleaf)
  - [Table of Contents](#table-of-contents)
- [Types of Remote Sensing Vision Language Models](#types-of-remote-sensing-vision-language-models)
  - [1](#1)
  - [2](#2)
- [Dataset](#dataset)



# Types of Remote Sensing Vision Language Models
## 1
<table style="width:100%;">
<tr>
<td>Paper</td>
<td>key</td>
<td>value</td>
<td>Short Summary</td>
</tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.09712'>SkyEyeGPT: Unifying Remote Sensing Vision-Language Tasks via Instruction Tuning with Large Language Model</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1.遥感领域的视觉语言指令数据集（SkyEye968k），包括单任务和多任务对话指令，包括968k条样本的指令跟随数据集2. 提出SkyEyeGPT模型，通过一个对齐层将RS视觉特征投影到语言领域后，它们与任务特定的指令一起被馈送到基于LLM的RS解码器中；设计了一个两阶段微调方法，第一阶段是遥感图文对齐，第二阶段是多任务对话微调</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：EVA-CLIPText Encoder：LLaMA2-chat</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption, Visual Grounding, RS VQA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ZhanYang-nwpu/SkyEyeGPT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2311.15826'>GeoChat: Grounded Large Vision-Language Model for Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. RS多模态数据集：多模态数据集，且提出了一个生成数据的pipeline2. GeoChat：利用已有的数据微调LLaVA-1.5，利用lora微调；除了能够处理自然语言问题之外，用户还可以提供视觉提示（bounding box），并且模型能够回答有关ROI（指定感兴趣区域）的问题</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP-ViTText Encoder： Vicuna-v1.5</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, RS VQA, Visual Grounding</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/mbzuai-oryx/geochat</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>CVPR 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2307.15266'>RSGPT: A Remote Sensing Vision Language Model and Benchmark</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 提出RSICap数据集，基于 DOTA 目标检测数据集构建了 RSICap2. 提出RSIEval评估集3. RSGPT模型，现成的冻结的预训练图像编码器（EVA-G）和大型语言模型（vicuna7b，vicuna13b）构成了该模型的基础，并通过微调Q-Former和线性层结构</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：EVAText Encoder：Vicuna</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption, RS VQA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2306.11029'>RemoteCLIP: A Vision Language Foundation Model for Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>CNN, Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>(CLIP)Vision Encoder:ResNet-50/ViT-Base/ViT-LargeText Encoder：Transformer Architecture</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image-text Retrieval, Scene Classification, Object Counting</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ChenDelong1999/RemoteCLIP</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>awesome-remote-sensing-vision-language-models</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>TGRS 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.06960'>Remote Sensing Vision-Language Foundation Models without Annotations via Ground Remote Alignment</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>介绍了一种在不使用任何文本注释，为遥感图像训练视觉语言模型的方法。关键是利用地面上拍摄的共同位置的互联网图像作为连接遥感图像和语言的中介</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-B</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, RS VQA, Semantic Segmentation, Image-text Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>提出了一种训练遥感图像的视觉-语言模型的方法</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>ICLR 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.09083'>Remote Sensing ChatGPT: Solving Remote Sensing Tasks with ChatGPT and Visual Models</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Agent</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 在chatgpt的基础上构建了remote sensing chatgpt。工作流程包括提示模板生成、任务规划、任务执行和响应生成。    2. 针对LLM无法直接感知遥感图像，设计了visual cues，将视觉信息注入到chatgpt</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>gpt-3.5-turbo/gpt-4</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/HaonanGuo/Remote-Sensing-ChatGPT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>IGARSS 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.16822'>EarthGPT: A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 提出了一种同一集成各种多传感器遥感解释任务的MLLM，EarthGPT，提出了视觉增强感知机制和跨模态相互理解的方法，最后提出了一种遥感领域的多传感器多任务的统一指令微调方法 2. 构建了最大的多模态多传感器的遥感指令跟随数据集MMRS-1M，由超过100万个图像文本对组成，包括有光学、合成孔径雷达（SAR）和红外图像</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>CNN, Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：DINOv2 ViT-L/14、CLIP ConvNeXt-LText Encoder：LLaMA-2</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, Image Caption, Visual Grounding, RS VQA, Object Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/wivizhang/EarthGPT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.12856'>SkyScript: A Large and Semantically Diverse Vision-Language Dataset for Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>(CLIP)Vision Encoder: ViT-B/ViT-LText Encoder：Transformer Architecture</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, Image-text Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/wangzhecheng/SkyScript</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>主要是构建数据集</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>AAAI 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2402.02544'>LHRS-Bot: Empowering Remote Sensing with VGI-Enhanced Large Multimodal Language Model</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 提出LHRS-Align数据集：大规模遥感领域的图像文本数据集，使用开源的全球地理数据生成的。2. 提出了LHRS-Instruct数据集，是一个专门为遥感图像理解定制的多模态指令跟随数据集。3. 在此基础上，提出了LHRS-Bot模型，采用了新的bridging strategy，并利用课程学习的方法来充分挖掘数据集种的内在知识4. 提出LHRS-Bench，用于对遥感领域的MLLM进行评估，包含690个单选题</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-LText Encoder：LLaMA-2</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, RS VQA, Visual Grounding</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/NJU-LHRS/LHRS-Bot</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2403.20213'>H2RSVLM: Towards Helpful and Honest Remote Sensing Large Vision Language Model</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 创建了HqDC-1.4M数据集，还构建了两个指令微调数据集HqDC-Instruct和RS-Specialized-Instruct    2. 针对幻觉问题，构建了第一个遥感self-awareness数据集，RSSA。包含一系列可回答和不可回答的任务    3. 基于上述数据，通过预训练和监督微调两个步骤，基于LLaVA模型训练了H2RSVLM模型（helpfulness 和 honesty）</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-LText Encoder：Vicuna-v1.5</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, RS VQA, Visual Grounding</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/opendatalab/H2RSVLM</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://www.mdpi.com/2072-4292/16/9/1477'>RS-LLaVA: Large Vision Language Model for Joint Captioning and Question Answering in Remote Sensing Imagery</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 通过集成caption和VQA数据集，提出了一个遥感领域的指令微调数据集2. 基于LLaVA模型，通过使用遥感数据对模型进行预训练和lora微调得到了了RS-LLaVA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-LText Encoder：Vicuna-v1.5</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption, RS VQA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/BigData-KSU/RS-LLaVA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>RS 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2305.14095'>S-CLIP: Semi-supervised Vision-Language Learning using Few Specialist Captions</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>提出了一种半监督学习方法，用于在少量专家标注的字幕情况下训练CLIP模型。S-CLIP利用额外的未配对图像，并通过两种伪标签策略增强对比学习和语言模态的训练。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>(CLIP)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, Image-text Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/alinlab/s-clip</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>awesome-remote-sensing-vision-language-models</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>NeurIPS 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2306.11300'>RS5M and GeoRSCLIP: A Large Scale Vision-Language Dataset and A Large Vision-Language Model for Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>(CLIP)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification, Image-text Retrieval, Semantic Localization</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>awesome-remote-sensing-vision-language-models</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2305.01118'>CSP: Self-Supervised Contrastive Spatial Pre-Training for Geospatial-Visual Representations</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://gengchenmai.github.io/csp-website/</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>vision-location</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>ICML 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2309.16020'>GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-L</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/VicenteVivan/geo-clip</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>vision-location</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>NeurIPS 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2311.17179'>SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/microsoft/satclip</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>vision-location</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2310.04698'>Tree-GPT: Modular Large Language Model Expert System for Forest Remote Sensing Image Understanding and Interactive Analysis</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Agent</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>gpt-4</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2402.06475'>Large Language Models for Captioning and Retrieving Remote Sensing Images</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption, Image-text Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>Image Caption & Text-image Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2403.03790'>Popeye: A Unified Visual-Language Model for Multi-Source Ship Detection from Remote Sensing Imagery</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>MLLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>1. 设计了一种image-to-caption的方法来统一各种船只检测数据集，基于现有的公开数据集构建了一个多模态多源指令跟随数据集MMShip（统一标记范式）  2. 提出Popeye架构，主要包括四个部分，统一标记范式、跨模态图像解释方法（通过多尺度多模态特征融合模块和视觉-语言对齐调整模块实现视觉-语言对齐，在 COCO Caption 数据集上对齐）、knowledge adaption paradigm（在 MMShip 数据集上进行船只领域适应阶段的训练）、与 SAM（Segment Anything Model）的集成</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-L、DINOv2 ViT-LText Encoder：LLaMA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Ship Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2209.02700'>Language-aware domain generalization network for cross-scene hyperspectral image classification</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：deep residual 3D CNN networkText Encoder：Transformer Architecture</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Scene Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>Vision-Language Models in Remote Sensing: Current Progress and Future Trends</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>IEEE Transactions on Geoscience and Remote Sensing 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2311.14656'>Charting New Territories: Exploring the Geographic and Geospatial Capabilities of Multimodal LLMs</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>评估MLLM在遥感领域的能力</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2310.06213'>GeoLLM: Extracting Geospatial Knowledge from Large Language Models</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>GeoLLM 提出了一种方法，可以从 LLMs 中提取大量的地理空间知识，并通过 OpenStreetMap 的辅助地图数据进行微调</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>RoBERTa、LLaMA-2、GPT-3.5</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/rohinmanvi/GeoLLM/</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>ICLR 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://www.sciencedirect.com/science/article/pii/S0303243422000678'>Transforming remote sensing images to textual descriptions</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>nan</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：ResNetText Encoder：Transformer Architecture</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>INT J APPL EARTH OBS 2022</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/abstract/document/10066217'>Vlca: vision-language aligning model with cross-modal attention for bilingual remote sensing image captioning</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>CNN, Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP（ResNet50/ViT）Text Encoder：GPT-2</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>J SYST ENG ELECTRON 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://www.mdpi.com/2072-4292/15/3/579'>Multi-source interactive stair attention for remote sensing image captioning</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>nan</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>RS 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2304.01091'>Changes to Captions: An Attentive Network for Remote Sensing Change Captioning</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>nan</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/shizhenchang/chg2cap</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.01191'>Bootstrapping Interactive Image-Text Alignment for Remote Sensing Image Captioning</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>Vision Encoder：CLIP ViT-LText Encoder：OPT-2.7B</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/yangcong356/BITA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2403.19646'>Change-Agent: Towards Interactive Comprehensive Remote Sensing Change Interpretation and Analysis</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Agent</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Change Detection, Change Caption</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/Chen-Yang-Liu/Change-Agent</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2405.00709'>Evaluating Tool-Augmented Agents in Remote Sensing Platforms</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Agent</td>
    <td rowspan='9' style='text-align: left; width:40%;'>提出了一个新的基准测试GeoLLM-QA，用于评估和理解工具增强型LLMs在遥感平台上的性能和潜力</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>评估</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>ICLR 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2404.15500'>GeoLLM-Engine: A Realistic Environment for Building Geospatial Copilots</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Agent</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>gpt-3.5-turbo/gpt-4</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>CVPR 2024</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2308.12509'>Parameter-Efficient Transfer Learning for Remote Sensing Image-Text Retrieval</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>VLM</td>
    <td rowspan='9' style='text-align: left; width:40%;'>构建了一个新颖的PETL框架，用于RS图像-文本检索任务，其中包括预训练的CLIP、多模态遥感adapter和混合多模态对比（HMMC）学习目标</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>Image-text Retrieval</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ZhanYang-nwpu/PE-RSITR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>偏向PETL方向</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>TGRS 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2405.04285.pdf'>On the Foundations of Earth and Climate Foundation Models</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://www.mdpi.com/2072-4292/15/13/3232'>The Potential of Visual ChatGPT for Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>设计实验对Visual Chatgpt在遥感领域的能力进行了测试评估</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>评估</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>RS 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.17600'>Good at captioning, bad at counting: Benchmarking GPT-4V on Earth observation data</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>提出了一个benchmark，用于评估VLMs在地球观测数据上的表现，特别是在场景理解、定位和计数以及变化检测任务上</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://vleo.danielz.ch/</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>评估</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
  <tr>
    <td rowspan='9' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.17016'>On the Promises and Challenges of Multimodal Foundation Models for Geographical, Environmental, Agricultural, and Urban Planning Applications</a></td>
    <td style='text-align: left; width:10%;'>Tag</td>
    <td style='text-align: left; width:20%;'>Other</td>
    <td rowspan='9' style='text-align: left; width:40%;'>评估GPT-4V模型在地理、环境科学、农业和城市规划多个领域的能力</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Visual Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Text Encoder</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Model Details</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Task</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>评估</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Published in</td>
    <td style='text-align: left;'>Arxiv 2023</td>
  </tr>
</table>

## 2
<table style="width:100%;">
<tr>
<td>Paper</td>
<td>key</td>
<td>value</td>
<td>Short Summary</td>
</tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2204.02825'>An Empirical Study of Remote Sensing Pretraining</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>提出了RS pretraining的概念。测试了CNN和VIT模型和一些增强方式。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ViTAE-Transformer/ViTAE-Transformer-Remote-Sensing</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>有监督预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2103.16607'>Seasonal Contrast:Unsupervised Pre-Training from Uncurated Remote Sensing Data</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR 2021</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>利用未标记数据进行遥感表示的领域内预训练。首先，是一个有原则的程序，用于收集大规模、未标记且未筛选的遥感数据集，其中包含来自不同地点、不同时间戳的图像。其次，是一种自监督算法，利用时间和位置的不变性来学习可转移的遥感应用表示。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ElementAI/seasonal-contrast</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，利用未标注数据</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://www.mdpi.com/2072-4292/14/18/4632'>Multi-source remote sensing pretraining based on contrastive self-supervised learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Remote Sensing 22</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>研究了基于对比自监督学习（CSSL）方法的预训练模型在SAR-光学遥感分类中的有效性</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，利用未标注数据</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2011.09980'>Geography-aware self-supervised learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>ICCV 21</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>利用随时间空间对齐的图像构建了对比学习中的时间正样本对，并利用地理定位设计了预文本任务</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/sustainlab-group/geography-aware-ssl</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，利用未标注数据</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/1805.02855'>Tile2Vec: Unsupervised representation learning for spatially distributed data</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>AAAI 19</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>主要目标是从未标记的数据中学习语义上有意义的表示，类似于自然语言处理中的词向量。Tile2Vec 利用分布假设，其中假设地理邻居具有相似的语义和表示。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ermongroup/tile2vec</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>半监督，利用未标记数据</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/document/9913413'>Semantic segmentation of remote sensing images with self-supervised semantic-aware inpainting</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Geoscience and Remote Sensing Letters 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>通过基于对抗学习的掩码和重建学习更适配语义分割的预训练特征</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/JasmineBJTU/self-supervised_RSSS</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，用于语意分割</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2204.04716'>TOV: The Original Vision Model for Optical Remote Sensing Image Understanding via Self-Supervised Learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 23</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>通过大量未标记的光学数据沿着类似人类的自监督学习(SSL)路径进行训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/GeoX-Lab/G-RSIM/tree/main/TOV_v1</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/abstract/document/9844015'>RingMo: A Remote Sensing Foundation Model With Masked Image Modeling </a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>提出了一种针对遥感图像中密集小目标的PIMask采样策略，即对遮挡补丁进行二次像素采样以暴露小目标</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>-</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>利用 生成式自监督学习 进行预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2208.03987'>Advancing plain vision transformer toward remote sensing foundation model</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ViTAE-Transformer/Remote-Sensing-RVSA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督掩码图像建模方法MAE对网络进行预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2306.16269'>Rsprompter: Learning to prompt for remote sensing instance segmentation based on visual foundation model</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv 2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>考虑基于 SAM 基础模型设计一种自动化实例分割方法，该方法将语义类别信息纳入其中，用于遥感图像</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://kyanchen.github.io/RSPrompter</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2311.07113'>SpectralGPT: Spectral Foundation Model</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>TPAMI2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>虽然大多数基础模型都是为了有效地处理各种视觉任务的RGB图像而定制的，但在光谱数据方面的研究存在明显的差距。采用MAE架构构建，多目标重建策略；generative pretrained transformer(GPT)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/danfenghong/IEEE_TPAMI_SpectralGPT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督MAE，以渐进式训练方式在多个数据集上进行训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2401.04614'>Generic Knowledge Boosted Pre-training ForRemote Sensing Images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/floatingstarZ/GeRSP</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督遥感+有监督自然图像</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2403.13430'>MTP: Advancing Remote Sensing FoundationModel via Multi-Task Pretraining</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv 2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>共享backbone+多任务头</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ViTAE-Transformer/MTP</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多任务监督预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://www.mdpi.com/2072-4292/14/22/5675'>Consecutive Pre-Training: A Knowledge Transfer Learning Strategy with Relevant Unlabeled Data for Remote Sensing Domain</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Remote Sensing 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>（1）在大规模未标记数据集（如ImageNet [18]）上进行自监督预训练；（2）在与任务相关的未标记遥感数据上进一步进行自监督预训练；（3）在多样化的下游任务上进行微调。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/ZhAnGToNG1/transfer_learning_cspt</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督+持续预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/1711.07846'>Functional Map of the World</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR 18</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>主要在数据集，没有特殊的训练方法</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/fMoW</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据集+有监督训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/1902.06148'>BIGEARTHNET: A LARGE-SCALE BENCHMARK ARCHIVE FOR REMOTE SENSINGIMAGE UNDERSTANDING</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE International Geoscience and Remote Sensing Symposium 2019</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>主要在数据集，没有特殊的训练方法</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/jerpint/bigearthnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据集+有监督训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2006.12485'>On Creating Benchmark Dataset for Aerial Image Interpretation: Reviews, Guidances, and Million-AID</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2021</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>首个与imagenet量级相当的数据集。主要在数据集，没有特殊的训练方法</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://captain-whu.github.io/DiRS/0</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据集+有监督训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2304.05215'>A billion-scale foundation model for remote sensing images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv 2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>研究参数量对预训练模型质量的影响</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2312.10115'>SkySense: A Multi-Modal Remote Sensing Foundation Model Towards Universal Interpretation for Earth Observation Imagery</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR 2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>通用的十亿级模型，在包含 2150 万个时间序列的多模态遥感图像 (RSI) 数据集上进行了预训练。通过多粒度对比学习对分解后的编码器进行预训练，从不同的模态和空间粒度构造特征。此外，我们提出了地理环境原型学习，从给定地理位置的RSI特征生成区域原型。该方法通过利用隐藏在大量未标记RSI中的区域上下文线索来增强多模态时空表征学习。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督多粒度对比学习，关注多模态和区域上下文</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2204.05381'>Self-supervised vision transformers for joint sar-optical representation learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>基于DINO，一种最先进的SSL算法，从输入图像的两个增强视图中提取知识，我们通过将所有通道连接到统一的输入来结合SAR和光学图像。随后，我们随机屏蔽掉一种模态的通道作为数据增强策略。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/zhu-xlab/DINO-MM</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，EMA, SAR+RGB多模态</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2107.05276'>Geographical Knowledge-Driven RepresentationLearning for Remote Sensing Images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/flyakon/Geographical-Knowledge-driven-Representaion-Learning</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，利用地理信息（地表覆盖种类）构建正负样本对</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2104.07070'>Self-Supervised Learning of Remote Sensing Scene Representations Using Contrastive Multiview Coding</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR 2021</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/vladan-stojnic/CMC-RSSR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多视图对比学习，用同一张图像的不同view（L，ab）作为正样本对</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2207.08051'>SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>NeurIPS 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/sustainlab-group/SatMAE</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，MAE</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2205.02049'>Self-Supervised Learning for Invariant Representations from Multi-Spectral and SAR Images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，BYOL只使用正样本对</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2112.01715'>Self-Supervised Material and Texture Representation Learning for Remote Sensing Tasks</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2204.04716'>TOV: The original vision model for optical remote sensing image understanding via self-supervised learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>先学习网络上的自然图片，然后学习未标记RSI图片，</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/GeoX-Lab/G-RSIM/tree/main/TOV_v1</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>CNN(Resnet-50)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, Object Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>scene classification, object detection and semantic segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2010.00882'>Remote Sensing Image Scene Classification with Self-Supervised Paradigm under Limited Labeled Samples</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Geoscience and Remote Sensing Letters 2020</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>the first time to use the SSL mechanism in the RSI scene classification; 分别测试了image inpainting, predicting relative position, and instance-wise contrastive learning </td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2106.10605'>Global and Local Contrastive Self-Supervised Learning for Semantic Segmentation of HR Remote Sensing Images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IEEE Transactions on Geoscience and Remote Sensing 2022</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>基于对比学习对于像素级别的任务适配不好，改论文提出了一种基于全局和局部对比学习的方法，以更好的适应像素级任务</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/GeoX-Lab/G-RSIM</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，对比学习</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2304.09670'>CMID: A Unified Self-Supervised Learning Framework for Remote Sensing Image Understanding</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>TGRS2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>对图片一个做增强一个做mask，经过网络后同时计算两个分支的contrastive loss和mask分支的regression loss。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/NJU-LHRS/official-CMID</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，通过蒸馏将对比学习和掩码结合在一起</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer, CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>architecture-agnostic(CNN/Transformer)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, Object Detection, Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>scene classification, semantic segmentation, object detection, and change detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/html/Prexl_Multi-Modal_Multi-Objective_Contrastive_Learning_for_Sentinel-12_Imagery_CVPRW_2023_paper.html'>Multi-Modal Multi-Objective Contrastive Learning for Sentinel-1/2 Imagery</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPRW2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>构建模态内和模态间相似度损失函数，通过地理编码获取更难的对比学习负样本对</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，对比学习，多模态</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>CNN(ResNet18)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Regression</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>Classification(Land-cover,Crop type mapping,), Regression (Biomass estimation)</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://openaccess.thecvf.com/content/CVPR2023/html/Mall_Change-Aware_Sampling_and_Contrastive_Learning_for_Satellite_Images_CVPR_2023_paper.html'>Change-Aware Sampling and Contrastive Learning for Satellite Images</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>季节变化损失与SeCo相同，使用同一地点几个月时间内的图片作为正样本，其他地点的图片作为负样本。长时间变化用几个月内的做正样本，长时间后的图片做负样本。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/utkarshmall13/CACo</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，对比学习</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>CNN（ResNet-18, ResNet-50）</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Change Detection, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>Classification（Landcover classification），Change detection，Semantic segmentation，Change Events</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2211.15660'>SatlasPretrain: A Large-Scale Dataset for Remote Sensing Image Understanding</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>ICCV2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>主要是数据集，说明在这个数据集上进行预训练能够得到更好的效果</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/allenai/satlas</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据集，</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Swin Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>Swin Transformer Backbone，UNet Head</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, Instance Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>8 classification，semantic segmentation, and instance segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2302.04476'>Towards Geospatial Foundation Models via Continual Pretraining</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>ICCV2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>改论文注意到了地理空间数据集的多样性对MIM预训练十分重要。为了增加纹理细节，我们确保了各种地面采样距离（GSD），包括比Sentinel-2（GSD为10米）高得多分辨率的图像。此外，选择的标签数据集涵盖了广泛的通用遥感场景类，确保样本间的视觉多样性。通过蒸馏的方式让学生网络学习到ImageNet pretrain的特征。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/mmendiet/GFM</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据集，自监督掩码+蒸馏，持续预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Swin Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>Swin transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Change Detection, Classification, Semantic Segmentation, Super-resolution</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>change detection, classification, multi-label classification, semantic segmentation, and super-resolution</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2212.14532'>Scale-MAE: A Scale-Aware Masked Autoencoder for Multiscale Geospatial Representation Learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>ICCV2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>原始ViT的位置编码与相机高度无关，Scale-MAE引入了基于地面采样距离（GSD）的位置编码，该编码与图像中土地面积成比例缩放，而不考虑图像的分辨率。此外，Scale-MAE还在MAE框架中引入了拉普拉斯金字塔解码器，以鼓励网络学习多尺度表示。来自ViT编码器的嵌入被解码为捕捉低频信息的低分辨率图像和捕捉高频信息的高分辨率图像。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/bair-climate-initiative/scale-mae</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>MAE，对位置编码和解码器进行了优化</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>ViT-Large</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>基于KNN的分类，linear classi-fication，Semantic segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2303.06670'>DINO-MC: Self-supervised Contrastive Learning for Remote Sensing Imagery with Multi-sized Local Crops</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv 2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/WennyXY/DINO-MC</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，DINO，使用时间对比任务和多尺度裁剪对比</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet, ViT, Swin Transformer, WRN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>ResNet-50，WRN-50-2，ViT-small，Swin-tiny</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification，Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/pdf/2311.00566'>CROMA: Remote Sensing Representations with Contrastive Radar-Optical Masked Autoencoders</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>NeurIPS2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>分别编码被遮盖的多光谱光学和合成孔径雷达样本，这些样本在空间和时间上是对齐的，并执行跨模态对比学习。另一个编码器融合这些传感器，生成联合多模态编码，然后通过一个轻量级解码器预测被遮盖的补丁。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/antofuller/CROMA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习+重建，多光谱+孔径雷达</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>ViT-B/ViT-L</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>Classification,Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://openreview.net/pdf?id=5oEVdOd6TV'>Cross-Scale MAE: A Tale of Multiscale Exploitation in Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>NeurIPS2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>在预训练过程中，Cross-Scale MAE采用了尺度增强技术，并通过对比损失和生成损失实施跨尺度一致性约束，以确保一致且有意义的表示，适用于广泛的下游任务。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/aicip/Cross-Scale-MAE</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>MAE+对比学习</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>ViT-L</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification and segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2309.05300'>DeCUR: decoupling common & unique representations for multimodal self-supervision</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>在不同模态间分离了通用和独特的表示，增强了模态内和跨模态的学习。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/zhu-xlab/DeCUR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多模态，对比学习</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>ResNet50 </td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification and segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2304.14065'>Lightweight, Pre-trained Transformers for Remote Sensing Timeseries</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>一种在遥感像素时间序列数据上预训练的模型</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/nasaharvest/presto</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多模态，单像素时间序列掩码，关注时间序列</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>Presto</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2310.00022'>CtxMIM: Context-Enhanced Masked Image Modeling for Remote Sensing Image Understanding</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>CtxMIM将原始图像块形式化为重建模板，并采用Siamese框架处理两组图像块。引入了一个上下文增强的生成分支，通过重建中的上下文一致性约束提供上下文信息。通过这种简单且优雅的设计，CtxMIM鼓励预训练模型在大规模数据集上学习对象级或像素级特征，而无需特定的时间或地理约束。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，掩码</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Swin Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>Swin-B</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, Object Detection, Instance Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification, semantic segmentation, object detection, instance segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2310.18653'>Feature Guided Masked Autoencoder for Self-supervised Learning in Remote Sensing</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>MAE往往过度关注像素细节，从而限制了模型的语义理解能力，特别是对于噪声较大的SAR图像。提出了特征引导掩码自动编码器（FG-MAE）：重建多光谱图像的方向梯度直方图（HOG）和归一化差异指数（NDI）的组合，以及重建SAR图像的HOG。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/zhu-xlab/FGMAE</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多模态，掩码</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'> ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2310.18660'>Foundation Models for Generalist Geospatial Artificial Intelligence</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>对ViT架构的主要修改是3D位置嵌入和3D补丁嵌入，以处理时空数据</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://huggingface.co/ibm-nasa-geospatial</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>MAE, HLS多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Cloud Gap Imputation/Flood Mapping/Wildfire Scar Mapping/Crop Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2309.09003'>RingMo-lite: A Remote Sensing Multi-task Lightweight Network with CNN-Transformer Hybrid Framework</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>RingMo-lite，这是一种具有CNN-Transformer混合框架的RS多任务轻量级网络，能够有效利用RS的频域特性来优化解释过程。它结合了变压器模块作为低通滤波器，通过双分支结构提取RS图像的全局特征，以及CNN模块作为堆叠的高通滤波器来有效提取细粒度细节。此外，在预训练阶段，设计的频域掩码图像建模（FD-MIM）结合了每个图像补丁的高频和低频特性，有效捕捉了RS数据中的潜在特征表示。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>掩码（FD-MIM），轻量化</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱, RGB</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>CNN-Transformer hybrid</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Object Detection, Semantic Segmentation, Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/abstract/document/10282433'>A Self-Supervised Cross-Modal Remote Sensing Foundation Model with Multi-Domain Representation and Cross-Domain Fusion</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IGARSS2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>然而，多模态数据在传感器种类、成像机制、分辨率和光谱信息上具有独特性。现有方法主要针对单一模态数据，特别是光学遥感图像，直接将其应用于多模态数据很难平衡提取各模态特征，并突破单一模态数据的性能上限。一种基于多域表示和跨域融合概念的模型架构.对于多模态遥感输入数据，MSFE首先在相应的特征空间中学习各种特征，即在欧几里得空间中学习光学和红外数据，在双曲空间中学习高光谱数据，在复数空间中学习SAR数据。然后，基于自监督损失，MMFH通过多模态特征对齐和交互学习跨模态互补信息，从而提高基础模型对多模态遥感数据的解释性能。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多模态，对比学习+重建</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>single-modal interpretation/multi-modal interpretation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2309.07207'>EarthPT: a foundation model for Earth Observation</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>NeurIPS2023 CCAI workshop</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>与Lightweight, Pre-trained Transformers forRemote Sensing Timeseries相似，用了更大的数据集</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/aspiaspace/EarthPT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>关注时间序列，单像素时间预测</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Future data generation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.02199'>USat: A Unified Self-Supervised Encoder for Multi-Sensor Satellite Imagery</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>遥感数据包含多传感器、多光谱和时间信息，提供了大量可用于自监督预训练的自标注数据,开发了一种新的编码器架构，称为 USat，可以输入来自多个传感器的多光谱数据进行自监督预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/stanfordmlgroup/USat</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>新的USat backbone，多光谱，MAE预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2312.10114'>FoMo-Bench: a multi-modal, multi-scale and multi-task Forest Monitoring Benchmark for remote sensing foundation models</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/RolnickLab/FoMo-Bench</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>森林监测基准，多模态</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>多光谱</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2311.15153v4'>Predicting Gradient is Better: Exploring Self-Supervised Learning for SAR ATR with a Joint-Embedding Predictive Architecture</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>发现像素采样不适用于SAR图像，因为SAR图像的单个像素包含乘性噪声。因此更倾向于使用局部补丁进行遮挡，而不是整个图像或像素级别。工作旨在通过局部补丁在目标层次上挖掘语义信息，而不是场景层次，工作发现梯度比率比HOG的差分梯度在乘性斑点噪声下更适合目标形状信息提取。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/waterdisappear/SAR-JEPA</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>自监督，类似JEPA的框架，固定student生成梯度特征</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>SAR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Target Recognition</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/document/10414422'>Self-Supervised Spatio-Temporal Representation Learning of Satellite Image Time Series</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>JSTARS2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>先生成patch编码。预训练任务旨在重建原始时间序列中被掩盖的一些输入补丁。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://src.koda.cnrs.fr/iris.dumeur/ssl_ubarn</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>类似Bert的自监督预训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>SITS</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.05093'>SwiMDiff: Scene-wide Matching Contrastive Learning with Diffusion Constraint for Remote Sensing Image</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>以往的CL忽略了细粒度特征和负样本中的潜在联系，SwiMDiff采用场景范围的匹配方法，有效地重新校准标签，将来自同一场景的数据识别为假负样本。此调整使CL更适用于遥感的细微差别。此外，SwiMDiff将CL与扩散模型无缝集成。通过实施像素级别的扩散约束，我们增强了编码器捕捉图像的全局语义信息和细粒度特征的能力。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>对比学习，用同一场景下的图片构建了一个FNS，并用一个基于Diffussion的图像恢复任务做辅助任务</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Resnet</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2401.07527'>One for All: Toward Unified Foundation Models for Earth Vision</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>目前的遥感基础模型通常专注于单一模态或特定的空间分辨率范围，这限制了它们在下游数据集中的通用性。尽管已经有开发多模态遥感基础模型的尝试，但它们通常为每种模态或空间分辨率采用单独的视觉编码器，需根据输入数据切换不同的骨干网络。为了解决这一问题，我们提出了一种简单而有效的方法，称为OFA-Net（One-For-All网络）：使用单一的共享Transformer骨干网络来处理不同空间分辨率的多种数据模态。通过使用掩码图像建模机制，我们在一个精心策划的多模态数据集上预训练单一的Transformer骨干网络。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>---</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>掩码，在主干前加了不同模态的编码器，解码器也是各个模态独立的</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>RGB, SAR, 多光谱, NIR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://ieeexplore.ieee.org/abstract/document/10378718'>Generative ConvNet Foundation Model With Sparse Modeling and Low-Frequency Reconstruction for Remote Sensing Image Interpretation</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>TGRS2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>https://github.com/HIT-SIRS/SMLFR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models/blob/main'>S2MAE: A Spatial-Spectral Pretraining Foundation Model for Spectral Remote Sensing Data</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>GeoSense的大型数据集，设计了一个稀疏建模和低频重建（SMLFR）框架，用于ConvNet基础模型的自监督表示学习。具体而言，在遮罩图像建模（MIM）中提出了一种稀疏建模策略，使ConvNet能够通过将未遮罩的补丁视为体素并对编码器进行稀疏化来处理可变长度序列。此外，我们设计了一个低频重建目标，引导模型关注遥感图像中的重要地物特征，同时减轻不必要的细节干扰。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ConvNext</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Object Detection, Semantic Segmentation, Change Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2403.05419'>Rethinking Transformers Pre-training for Multi-Spectral Satellite Imagery</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>Pretrain</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>执行多尺度预训练，并利用基于卷积的上采样块在更高尺度上重建图像，使其可以扩展到更多尺度。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>RGB</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer, CNN</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2404.01260'>Bridging Remote Sensors with Multisensor Geospatial Foundation Models</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>CVPR2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>通过使用遮罩图像建模技术可以学习到对应传感器之间的联合表示吗？针对该问题提出了msGFM（多传感器地理空间基础模型），该模型有效整合了四种关键传感器模式的数据。msGFM特别擅长处理配对和非配对的传感器数据。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>跨传感器的掩码方式。每个传感器有独立的embedding提取器，为每个传感器设置单独的解码器和跨传感器预测。例如，当模型被馈送来自DSM的遮罩图像时，它可以预测自身的遮罩补丁或RGB对应的图像</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>SAR, RGB, DSM</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Swin Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation, cloud removal, pan-sharpening</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='https://arxiv.org/abs/2403.15356'>Neural Plasticity-Inspired Foundation Model for Observing the Earth Crossing Modalities</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>这是通过设计的基于超网络的动态权重生成器实现的，该生成器适应每个通道的光谱波长。通过将具有不同通道数量的图像嵌入到统一的特征空间中，模型利用共享Transformer块来学习模态共享表示。</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>将各种数据模态自适应地集成到一个单一框架中，这种动态超网络，能够调整到不同的波长，使得一个多功能Transformer能够在来自五个传感器的数据上进行联合训练</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>RGB, NIR, 多光谱, SAR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>Transformer</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Semantic Segmentation</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='nan'>MMEarth: Exploring Multi-Modal Pretext Tasks For Geospatial Representation Learning</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>多预文本遮罩自编码器，解码器包括重建和一些下游任务</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>ConvNext</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='nan'>SARATR-X: A Foundation Model for Synthetic Aperture Radar Images Target Recognition</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>MAE，两阶段预训练（ImageNet-SAR），使用多尺度梯度特征（MGF）[这个文档里的49]来抑制斑点噪声并提取目标形状</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>SAR</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>HiViT</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>Classification, Object Detection</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='nan'>LeMeViT: Efficient Vision Transformer with Learnable Meta Tokens for Remote Sensing Image Interpretation</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>IJCAI2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>改网络结构，加速</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='nan'>On the Foundations of Earth and Climate Foundation Models</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>Arxiv2024</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>有一些问题：1. 专注于预训练数据集的策划，往往过度采样城市等人口稠密地区，而在雨林、极地和海洋等人口稀少地区采样不足 2. 预训练数据集往往专注于中高分辨率的RGB和MSI，很少有大规模的数据集用于SAR、HSI或Lidar数据，或用于非常高或低分辨率的图像。像DOFA这样的多传感器模型很少见，大多数模型需要在每次遇到新的成像平台时从头训练 3. 时间序列地球观测建模也处于起步阶段，少有模型能够处理具有不规则间隔的可变长度图像序列。在地球观测中整合不确定性量化和物理一致性仍未得到充分探索。未来的发展：1.具有条件计算的动态编码器 2.多尺度的空间-时间分析 3.多模态学习框架 4.与大型语言模型的对齐 ...</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>针对地球和气候科学</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td rowspan='11' style='text-align: left; width:30%;'><a href='nan'>遥感基础模型发展综述与未来设想</a></td>
    <td style='text-align: left; width:10%;'>Published in</td>
    <td style='text-align: left; width:20%;'>遥感学报2023</td>
    <td rowspan='11' style='text-align: left; width:40%;word-wrap: break-word;'>对比学习、生成式学习；图像，时间序列</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Type</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Code/Project</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>备注</td>
    <td style='text-align: left;'>数据、方法和应用</td>
  </tr>
  <tr>
    <td style='text-align: left;'>数据类型</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Backbone 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>下游任务 1</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>Survey Inclusion</td>
    <td style='text-align: left;'>nan</td>
  </tr>
  <tr>
    <td style='text-align: left;'>other</td>
    <td style='text-align: left;'>nan</td>
  </tr>
</table>


# Dataset
