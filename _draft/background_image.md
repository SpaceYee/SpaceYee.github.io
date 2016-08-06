---
layout: post
title: 安装Caffe遇到的一些问题
description: "OK."
tags: [sample post]
image:
  background: triangular.png
---

Here be a sample post with a custom background image. To utilize this "feature" just add the following YAML to a post's front matter.

```yaml
image:
  background: filename.png
```


### Ordered Lists

1. 形如"undefined reference to TIFFRGBAImageOK@LIBTIFF_4.0"的问题。
   1. 参考<a href="http://answers.opencv.org/question/35642/libtiff_40-link-errors/">opencv论坛</a>的方法
   2. 如果装了anaconda的话，可能与anaconda的tiff库冲突，使用下列命令
	```
	conda remove libtiff
	```
  


<div xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/" about="http://subtlepatterns.com" class="notice">Background images from <span property="dct:title">Subtle Patterns</span> (<a rel="cc:attributionURL" property="cc:attributionName" href="http://subtlepatterns.com">Subtle Patterns</a>) / <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a></div>