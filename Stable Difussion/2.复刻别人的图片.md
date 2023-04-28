# Stable Diffusion还原作者的图片、Stable Diffusion快速从Civitai复制图片data到webui、copy generation data

在civitai上看到一张很好看的图片，如何快速复刻？

## 1. copy generation data 

这里有一个小技巧.可以快速copy Civitai上的data到webui中.
点击copy Generation Data,复制到webui中,再点击旁边的箭头.

![image-20230428202915137](images/2.复刻别人的图片.assets/image-20230428202915137.png)

## 2.粘贴到自己的SD这里

粘贴到自己的文生图的框里，然后点击生成下面的第一个小按钮，作者的提示词就全到你这里了。

当然大模型和lora你得提前下载好放到指定的位置，关于这两点可以看我之前的博客

![image-20230428203202559](images/2.复刻别人的图片.assets/image-20230428203202559.png)

然后点击生成，可以看到效果和原图是很像的。

不能百分百复刻是因为VAE以及关键词里面可能有embedding之类的。