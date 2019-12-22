<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Traffic Sign Detection](#traffic-sign-detection)
	- [Goal](#goal)
	- [Main Structure](#main-structure)
	- [Dataset](#dataset)
	- [Warning](#warning)

<!-- /TOC -->

# Traffic Sign Detection

this project is wrriten by python notebook on google colab.

## Goal

Based on [this paper](https://www.researchgate.net/publication/317776221_An_overview_of_traffic_sign_detection_and_classification_methods), we want to reduce the false error rate in the process of traffic sign **classification**.

## Main Structure

- Detection: to simplify the question, we use nueral network to extract the possible signs. we use [faster_rcnn_resnet_101](https://drive.google.com/file/d/15OxyPlqyOOlUdsbUmdrexKLpHy1l5tP9/view)

- Classification: we will try to improve our result. We will implement some popular classification algorithms and then compare them with our method.

## Dataset

we will use German Traffic Sign Recognition Benchmark [GTSRB](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) for training and testing.

## Warning

We will not use neral network methods in classification stage.
