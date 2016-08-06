---
layout: post
title: 安装Caffe遇到的一些问题
description: "OK."
tags: [caffe]
image:
  background: triangular.png
---



### 所有问题
*  形如<b>"undefined reference to TIFFRGBAImageOK@LIBTIFF_4.0"</b>的问题。
   1. 参考<a href="http://answers.opencv.org/question/35642/libtiff_40-link-errors/" style="color:red">opencv论坛</a>的方法
   2. 如果装了anaconda的话，可能与anaconda的tiff库冲突，使用下列命令
	```
	conda remove libtiff
	```
  


