---
tags:
- Diff-SVC
- DiffSVC
- Pre-trained Model
- Genshin
- Genshin Impact
---
# Genshin SVC Models for Diff-SVC

## 说明

### 仓库地址

|                    仓库                     |                            传送门                            |
| :-----------------------------------------: | :----------------------------------------------------------: |
|                  Diff-SVC                   |      [点此传送](https://github.com/prophesier/diff-svc)      |
|               44.1KHz 声码器                |        [点此传送](https://openvpi.github.io/vocoders)        |
|               原神语音数据集                |      [点此传送](https://github.com/w4123/GenshinVoice)       |
| Diff-SVC 原神模型训练集（如果需要自己训练） | [点此传送](https://huggingface.co/datasets/Erythrocyte/Diff-SVC_Genshin_Datasets) |
|   训练所用底模（也可用于训练非原神模型）    | [点此传送](https://huggingface.co/Erythrocyte/Diff-SVC_Pre-trained_Models) |
|                模型训练进度                 | [点此传送](https://docs.qq.com/sheet/DR2ZUR05XbHJwS2xK?tab=BB08J2) |

### 模型介绍

该模型为 **Diff-SVC** 的 **原神角色模型** ，可用于 **二创整活** ，由于模型是用 **44.1KHz** 声码器训练的，需要下载 44.1KHz的声码器才能推理，该仓库将会不定期更新。**训练所用的《原神》角色语音所有版权均归 米哈游 所有**。

《原神》官方网站：[https://ys.mihoyo.com/](https://ys.mihoyo.com/)

米哈游官方网站：[https://www.mihoyo.com/](https://www.mihoyo.com/)

### 注意事项

1. 该仓库所提供的 **原神角色Diff-SVC模型** 仅可用于 **二次创作** ，**模型以及所用的数据集均不得用于商业用途**。在用此仓库提供的模型进行二次创作的时候，创作的 **内容均必须合法合规**，**不得** 用该仓库模型 **创作任何违法违规内容**。**如有滥用此仓库模型的，该仓库将停止公开！**
2. 此仓库里上传的模型 **均为精简后的模型**，**无法** 作为底模 **继续训练**。

## 试听&下载（已按照地区排序）

### 效果试听

|  角色名  |                           输入音频                           |                           输出音频                           |
| :------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|   温迪   | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/in/input1.wav" controls="controls"> | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/out/Mondstadt/venti.wav" controls="controls"> |
|   钟离   | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/in/Liyue/to_zhongli.wav" controls="controls"> | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/out/Liyue/zhongli.wav" controls="controls"> |
| 雷电将军 | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/in/Inazuma/to_raiden.wav" controls="controls"> | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/out/Inazuma/raiden.wav" controls="controls"> |
|  流浪者  | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/in/Sumeru/to_wanderer.wav" controls="controls"> | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/out/Sumeru/wanderer.wav" controls="controls"> |
|  纳西妲  | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/in/Sumeru/to_nahida.wav" controls="controls"> | <audio src="https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/demo/out/Sumeru/nahida.wav" controls="controls"> |

### 下载地址

|  角色名  |                           下载地址                           |
| :------: | :----------------------------------------------------------: |
|   温迪   | [venti.zip](https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/models/Mondstadt/venti.zip) |
|   钟离   | [zhongli.zip](https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/models/Liyue/zhongli.zip) |
| 雷电将军 | [raiden.zip](https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/models/Inazuma/raiden.zip) |
|  流浪者  | [wanderer.zip](https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/models/Sumeru/wanderer.zip) |
|  纳西妲  | [nahida.zip](https://huggingface.co/Erythrocyte/Diff-SVC_Genshin_Models/resolve/main/models/Sumeru/nahida.zip) |
