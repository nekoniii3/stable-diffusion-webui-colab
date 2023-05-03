# stable-diffusion-webui-colab
 stable-diffusion-webuiを起動させるcolabノートブックです。<br>
 AUTOMATIC1111さんのstable-diffusion-webuiを利用し、<br>
 （https://github.com/AUTOMATIC1111/stable-diffusion-web）<br>
 拡張機能（ControlNet、Depth map library）を追加しています。<br>
 派生モデルごとにノートが分けているので、お好きなものを利用してください。<br>
 ※全てのモデルについて商用利用は推奨されてません<br>

2023/4/22<br>
 ControlNet1.1に対応しました。（Ver1.1）<br>
Openpose_hand、Lineartなどが利用できます。<br>
 <br>

## **🚸注意🚸**
GoogleColab無料版でStableDiffusionなど画像生成AIの利用が禁止となりました<br>無料版で実行すると警告が表示され、使用するとアカウント停止の恐れがあります<br>必ず有料プラン(月額Pro、従量課金版Pay As You Goなど)にご加入して実行してください
<br><br>

### **ControlNet1.1に対応したノートブック（Ver1.1）**
|  colabリンク  |  モデル名  |  モデル特徴  | VAE  |
| ---- |:----:|:----:|:----:|
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.1/stable_diffusion1_5_webui_controlnetV1_1.ipynb)  |  **stable-diffusion1.5**  |  全ての基になったモデル  |  ー  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.1/anythingv4_5_webui_controlnetV1_1.ipynb)  |  **anything-v4.5**  |  イラスト(2次元)特化モデル  |  ○  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.1/animelike2d_webui_controlnetV1_1.ipynb)   |  **animelike2d**  |  某アニメ会社のようなイラスト  |  ー  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.1/Chilloutmix_webui_controlnetV1_1.ipynb)  |  **Chilloutmix**  | AIコスプレと言われるリアルな人間の画像 |  ー  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.1/Counterfeit2_5_webui_controlnetV1_1.ipynb)  |  **Counterfeit2.5**  | 背景のクオリティも高いイラスト|  ○  |

※VAEはオリジナルVAEの有無についてで、stablediffusion汎用VAEはどのモデルも利用できるようにしてあります
<br><br><br>

### **過去のノートブック（Ver1.0）**

|  colabリンク  |  モデル名  |  モデル特徴  |
| ---- |:----:|:----:|
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.0/stablediffusion1_5_webui_cont%2Bdep_V1_0.ipynb)  |  **stable-diffusion1.5**  |  全ての基になったモデル  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.0/anythingv4_5_webui_cont%2Bdep_V1_0.ipynb)  |  **anything-v4.0**  |  イラスト(2次元)特化モデル  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.0/animelike2d_webui_cont%2Bdep_V1_0.ipynb)   |  **animelike2d**  |  某アニメ会社のようなイラスト  |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.0/Chilloutmix_webui_cont%2Bdep_V1_0.ipynb)  |  **Chilloutmix**  | AIコスプレと言われるリアルな人間の画像 |
|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nekoniii3/stable-diffusion-webui-colab/blob/main/V1.0/Counterfeit25_webui_cont%2Bdep_V1_0.ipynb)  |  **Counterfeit2.5**  | 背景のクオリティも高いイラスト|
