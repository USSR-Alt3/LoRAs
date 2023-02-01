  # 重要事项注意！(Important!)：
 ## 简短声明，幸运点进来的人最好看一下：
  
 1. 私炉古法炼丹，现在正在整LoRa，主要供AI绘画同好以及群友交流使用，应该...大概持续更新？
    本人企鹅号2481436585，如非交流炼丹经验请勿骚扰。
    
 2. 注意文件大小，在本仓库内KB级pt文件均为EMB模型，MB级safetensors文件均为LoRa模型，使用方式有所区别。

 3. EMB模型的使用：

    放入`...\stable-diffusion-webui\Embeddings`目录下，使用`XXX.pt`模型时对应的要输入的提示词就是`XXX`。

 4. LoRa模型的使用：

    首先，确定自己的Webui为最新的2023稳定版本。

    然后，在“扩展”页面中安装`sd-webui-additional-networks`,或在`...\stable-diffusion-webui\Embeddings\extensions`目录下执行以下命令进行安装：

     `git clone https://github.com/kohya-ss/sd-webui-additional-networks.git`

    之后，将下载的LoRa模型放入`.\stable-diffusion-webui\extensions\sd-webui-additional-networks\models\lora`下。

    使用`XXX~xxx.safetensors`模型时,确保正确安装上述扩展打开Webui，在`Additional Networks`中选择需要使用的模型，并调整权重，且务必记得勾选`Enable`，输入模型对应文件名中`xxx`作为提示词可增强角色还原度。

 5. 如需用于发表的作品，请于简介附上本工程链接。
   
 6. 所有文件禁止转载！更不能无耻地偷去赚小白的米！
 
 7. 没了，谁想到能叠的甲联系我一下。
   
 ## A terse statement,for those lucky to come to this project：
   
 1. Anime and game characters‘ embeddings and LoRas developed by USSR,are used for AI painting and communicating in our group.I'll contine updating this project in idle time,maybe?

 2. Take care to the size of files.In this responsibility,`XXX.pt` means this file an Embedding model,and `XXX~xxx.safetensors` means a LoRa model.
 
 3. How to use Embeddings:

     Put Embedding models like `XXX.pt` into folder `...\stable-diffusion-webui\Embeddings`,when using,input `XXX` to use `XXX.pt`.

 4. How to use LoRas:

    First,make sure your Webui is the latest stable version of 2023.

    Then,open the page `Extensions` to install the extension `sd-webui-additional-networks`.

    Next,put LoRa models like `XXX~xxx.safetensors` into folder `.\stable-diffusion-webui\extensions\sd-webui-additional-networks\models\lora`.

    At last,make sure you correctly install the extension,so that you can enable models at `Additional Networks`,and you can input `xxx` in the corresponding model name `XXX~xxx.safetensors`,to enhance the characters' similarity.
   
 5. If you wanna use these files to publish artwork on webs like Pixiv or Twitter,please indicating this project's link.
   
 6. All files of this project are forbidden to be reproduced!Also can't be used for profit or defrauded those new guys!

  # 懒人下载(Download directly):
  
 ## `git clone https://github.com/USSR-Alt3/Embeddings.git`

  # 更新日志(Update)：
 - 2023/2/1
   + 更新 游戏王-芙莉西亚之虫惑魔(YGO-OCG-Traptrix Rafflesia)
   + 上传 游戏王-阿蒂普丝之虫惑魔(YGO-OCG-Traptrix Atypus)
   + 上传 游戏王-阿洛美勒丝之虫惑魔(YGO-OCG-Traptrix Allomerus)
   + 上传 游戏王-阿特拉之虫惑魔(YGO-OCG-Traptrix Atrax)
   + 上传 游戏王-蒂奥之虫惑魔(YGO-OCG-Traptrix Dionaea)
   + 上传 游戏王-基诺之虫惑魔(YGO-OCG-Traptrix Arachnocampa)
   + 上传 游戏王-库拉莉亚之虫惑魔(YGO-OCG-Traptrix Cularia)
   + 上传 游戏王-兰卡之虫惑魔(YGO-OCG-Traptrix Mantis)
   + 上传 游戏王-莉塞之虫惑魔(YGO-OCG-Traptrix  Genlisea)
   + 上传 游戏王-普蒂卡之虫惑魔(YGO-OCG-Traptrix Pudica)
   + 上传 游戏王-塞拉之虫惑魔(YGO-OCG-Traptrix Sera)
   + 上传 游戏王-特莱恩之虫惑魔(YGO-OCG-Traptrix Myrmeleo)
   + 上传 游戏王-西托莉丝之虫惑魔(YGO-OCG-Traptrix Pinguicula)
 - 2023-1-23
   + 上传 游戏王-吉娜之虫惑魔(YGO-OCG-Traptrix Vesiculo)
 - 2023-1-22
   + 上传 游戏王-芙莉西亚之虫惑魔(YGO-OCG-Traptrix Rafflesia)
 - 2023-1-21
   + 上传 明日方舟-星熊(Arknights-Hoshiguma)
   + 上传 明日方舟-星熊(Arknights-Hoshiguma-TempestSeries)
 - 2023-1-20
   + 上传 明日方舟-夜莺(Arknights-Nightingale)
   + 上传 明日方舟-夜莺-挽歌(Arknights-Nightingale-WitchFeast)
 - 2023-1-19
   + 上传 明日方舟-闪灵(Arknights-Shining)
   + 上传 明日方舟-闪灵-静谧午夜(Arknights-Shining-CoralCoast)
 - 2023-1-18
   + 上传 明日方舟-安洁莉娜-质素访客(Arknights-Angelina-Bloodline of Combat)
   + 上传 明日方舟-安洁莉娜-夏卉(Arknights-Angelina-CoralCoast)
 - 2023-1-17
   + 上传 明日方舟-能天使(Arknights-Exusiai)
   + 上传 明日方舟-推进之王(Arknights-Siege)
   + 上传 明日方舟-伊芙利特(Arknights-Ifrit)
   + 上传 明日方舟-伊芙利特-日晒(Arknights-Ifrit-CoralCoast)
   + 上传 明日方舟-艾雅法拉(Arknights-Eyjafjalla)
   + 上传 明日方舟-艾雅法拉-夏卉(Arknights-Eyjafjalla-CoralCoast)
   + 上传 明日方舟-安洁莉娜(Arknights-Angelina)
   + 上传 游戏王-魔女术名匠·玻璃女巫(YGO-OCG-Witchcrafter Madame Verre)
   + 上传 游戏王-白银城的拉比林斯(YGO-OCG-Labrynth of the silver castle)
   + 上传 碧蓝航线-奥古斯都(AzurLune-August)
   + 上传 碧蓝航线-奥古斯都-女仆魔女(AzurLune-August-MaidWitch)
 
  # 以下是预览图(Preview)：
 
 <details>


 <summary>明日方舟(Arknights)</summary>


 <details>
 <summary>能天使(Exusiai)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/63e989d04be7c2cc2d39106a28699dc89fc74e2b/%E9%A2%84%E8%A7%88%E5%9B%BE/%E8%83%BD%E5%A4%A9%E4%BD%BF(Exia).png)
 </details>
 
 <details>
 <summary>推进之王(Siege)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/0d842f2f6290f5c16a18a15dbc899acd9b2cb360/%E9%A2%84%E8%A7%88%E5%9B%BE/%E6%8E%A8%E8%BF%9B%E4%B9%8B%E7%8E%8B(Siege).png)
 </details>
 
 <details>
 <summary>伊芙利特+伊芙利特-日晒(Ifrit)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/004bb95cd435dd684d8395290a7edb7b52232435/%E9%A2%84%E8%A7%88%E5%9B%BE/%E4%BC%8A%E8%8A%99%E5%88%A9%E7%89%B9(Ifrit).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E4%BC%8A%E8%8A%99%E5%88%A9%E7%89%B9-%E6%97%A5%E6%99%92(Ifrit-CoralCoast).png)
 </details>
 
 <details>
 <summary>艾雅法拉+艾雅法拉-夏卉(Eyjafjalla)</summary>
 
 ![](https://github.com/USSR-Alt3/Embeddings/blob/0d842f2f6290f5c16a18a15dbc899acd9b2cb360/%E9%A2%84%E8%A7%88%E5%9B%BE/%E8%89%BE%E9%9B%85%E6%B3%95%E6%8B%89(Eyjafjalla).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E8%89%BE%E9%9B%85%E6%B3%95%E6%8B%89-%E5%A4%8F%E5%8D%89(Eyjafjalla-CoralCoast).png)
 </details>
 
 <details>
 <summary>安洁莉娜+安洁莉娜-质素访客+安洁莉娜-夏卉(Angelina)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/0d842f2f6290f5c16a18a15dbc899acd9b2cb360/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%AE%89%E6%B4%81%E8%8E%89%E5%A8%9C(Angelina).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%AE%89%E6%B4%81%E8%8E%89%E5%A8%9C-%E8%B4%A8%E7%B4%A0%E8%AE%BF%E5%AE%A2(Angelina-Bloodline%20of%20Combat).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%AE%89%E6%B4%81%E8%8E%89%E5%A8%9C-%E5%A4%8F%E5%8D%89(Angelina-CoralCoast).png)
 </details>
 
 <details>
 <summary>闪灵+闪灵-静谧午夜(Shining)</summary>
 
 ![](https://github.com/USSR-Alt3/Embeddings/blob/4a8aa4c32775fe2d9d5d4c1bdf3a508a7cd4ea86/%E9%A2%84%E8%A7%88%E5%9B%BE/%E9%97%AA%E7%81%B5(Shining).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/4a8aa4c32775fe2d9d5d4c1bdf3a508a7cd4ea86/%E9%A2%84%E8%A7%88%E5%9B%BE/%E9%97%AA%E7%81%B5-%E9%9D%99%E8%B0%A7%E5%8D%88%E5%A4%9C(Shining-CoralCoast).png)
 </details>
 
 <details>
 <summary>夜莺+夜莺-挽歌(Nightingale)</summary>
 
 ![](https://github.com/USSR-Alt3/Embeddings/blob/5cb122741d80700991a8e9dfa3f2543069135881/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%A4%9C%E8%8E%BA(Nightingale).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/5cb122741d80700991a8e9dfa3f2543069135881/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%A4%9C%E8%8E%BA-%E6%8C%BD%E6%AD%8C(Nightingale-WitchFeast).png)
 </details>
 
 <details>
 <summary>星熊+星熊-狩标浪人(Hoshiguma)</summary>
 
 ![](https://github.com/USSR-Alt3/Embeddings/blob/01ff3aa3b4f936a60af23315b5184c5e885b795d/%E9%A2%84%E8%A7%88%E5%9B%BE/%E6%98%9F%E7%86%8A(Hoshiguma).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E6%98%9F%E7%86%8A-%E7%8B%A9%E6%A0%87%E6%B5%AA%E4%BA%BA(Hoshiguma-TempestSeries).png)
 </details>
 

 </details>


 <details>
 
 <summary>游戏王(YGO-OCG)</summary>
 
 <details>
 <summary>白银城的拉比林斯(Labrynth of the Silver Castle)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/98104f5414c3a807d66a97a0eefbd67579e72228/%E9%A2%84%E8%A7%88%E5%9B%BE/%E7%99%BD%E9%93%B6%E5%9F%8E%E7%9A%84%E6%8B%89%E6%AF%94%E6%9E%97%E6%96%AF(Labrynth%20of%20the%20silver%20castle).png)
 </details>
 
 <details>
 <summary>虫惑魔(Traptrix)</summary>
 <details>
 <summary>游戏王-芙莉西亚之虫惑魔(Traptrix Rafflesia)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/984516787da8de01a6f385fd0a164f8dc2f46128/%E9%A2%84%E8%A7%88%E5%9B%BE/%E8%8A%99%E8%8E%89%E8%A5%BF%E4%BA%9A%E4%B9%8B%E8%99%AB%E6%83%91%E9%AD%94(Traptrix%20Rafflesia).png)
 </details>

<details>
 <summary>游戏王-吉娜之虫惑魔(Traptrix Vesiculo)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/879be0860b3a9643e1784552da35e493708b5b77/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%90%89%E5%A8%9C%E4%B9%8B%E8%99%AB%E6%83%91%E9%AD%94(Traptrix%20Vesiculo).png)
 </details>

<details>
 <summary>魔女术名匠·玻璃女巫(Witchcrafter Madame Verre)</summary>
    
 ![](https://github.com/USSR-Alt3/Embeddings/blob/98104f5414c3a807d66a97a0eefbd67579e72228/%E9%A2%84%E8%A7%88%E5%9B%BE/%E9%AD%94%E5%A5%B3%E6%9C%AF%E5%90%8D%E5%8C%A0%C2%B7%E7%8E%BB%E7%92%83%E5%A5%B3%E5%B7%AB(Witchcrafter%20Madame%20Verre).png)
 </details>
 

 </details>
 


 <details>
 
 <summary>碧蓝航线(AzurLune)</summary>
 
 <details>
 <summary>奥古斯都+奥古斯都-女仆魔女(August)</summary>
 
 ![](https://github.com/USSR-Alt3/Embeddings/blob/98104f5414c3a807d66a97a0eefbd67579e72228/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%A5%A5%E5%8F%A4%E6%96%AF%E9%83%BD(August).png)
 ![](https://github.com/USSR-Alt3/Embeddings/blob/98104f5414c3a807d66a97a0eefbd67579e72228/%E9%A2%84%E8%A7%88%E5%9B%BE/%E5%A5%A5%E5%8F%A4%E6%96%AF%E9%83%BD-%E5%A5%B3%E4%BB%86%E9%AD%94%E5%A5%B3(August).png)
 </details>
 

 </details>
