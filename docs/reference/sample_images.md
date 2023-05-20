# **ControlNet-Referenceのサンプル画像です**
基本的にPreprocessorは"reference-only"で何も記載がなければControl Mode="Balanced" Style Fidelity=0.5にして実行してます。
<br>
Referenceの動画での紹介は[こちら](https://youtu.be/rVUXf823o6Q)

※素材は[イラストAC](https://www.ac-illust.com/)・[Pixabay](https://pixabay.com/)から使用しています

## **アニメ画像（モデルはAnything-V4.5）**
<br>

|  参照画像 |  reference-only  |
| ---- | ---- |
|  ![](images/anime.jpg)  |  ![](images/anime-only.png) |
<br>

|  参照画像 |  reference-only  |
| ---- | ---- |
|  ![](images/anime-maid.jpg)  |  ![](images/anime-maid-only.png) |
<br>

|  参照画像 |  reference-only  |
| ---- | ---- |
|  ![](images/anime-sd.jpg)  |  ![](images/anime-sd-only.png) |
<br>

## **実写画像（モデルはRealistic_Vision1.4）**
<br>

|  参照画像 |  reference-only  |
| ---- | ---- |
|  ![](images/child.jpg)  |  ![](images/child-only.png) |
<br>

|  参照画像 |  reference-only  |
| ---- | ---- |
|  ![](images/cat.jpg)  |  ![](images/cat-only.png) |
<br>

|  参照画像 |  Style Fidelity=0.5  |
| ---- | ---- |
|  ![](images/dog.jpg)  |  ![](images/dog-only-bl.png) |

|  Style Fidelity=1.0 |  Style Fidelity=0.1  |
| ---- | ---- |
|  ![](images/dog-only-SF1.0.png)  |  ![](images/dog-only-SF0.1.png) |
<br>

|  Controlnet is more important |  My prompt is more important  |
| ---- | ---- |
|  ![](images/dog-only-ci.png)  |  ![](images/dog-only-pi.png) |
<br>

|  参照画像 |  Style Fidelity=0.5  |
| ---- | ---- |
|  ![](images/woman.jpg)  |  ![](images/woman-only-bl.png) |

|  reference_adain |  reference_adain+attn  |
| ---- | ---- |
|  ![](images/woman-adain.png)  |  ![](images/woman-adain-attn.png) |

|  adain+attn(Style Fidelity=1.0) |  adain+attn(ControlNet is more important)  |
| ---- | ---- |
|  ![](images/woman-adain-attn-SF1.0.png)  |  ![](images/woman-adain-attn-ci.png) |
<br>

**開発者よりreference_adain+attnでStyle Fidelity=1.0が最も強力とのことですが顔がだいぶ変わってしまうようです。推奨はreference_onlyでStyle Fidelity=0.5。**