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

# Dataset
