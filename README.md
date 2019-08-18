# Azure-Kinect-Unity-Body-Tracker

## Overview

AzureKinectのBodyTrackingをUnityで試すために作りました。
汎用的なものではないです。

This project is for the experiments of Body Tracking of Azure Kinect on the Unity.
Not for General purpose.

## Environment

* Unity2019.2.x
* Azure Kinect SDK v1.1.0
* Azure Kinect Body Tracking SDK v0.9.1

## Setup to run

下記ファイルを Azure-Kinect-Unity-Body-Tracker\K4AUnityBT 配下に配置してください。

Put following files at "Azure-Kinect-Unity-Body-Tracker\K4AUnityBT".

* depthengine_1_0.dll
* dnn_model.onnx
* onnxruntime.dll

## Setup to build the plugin

VisualStudioのプロパティマネージャーで下記ユーザーマクロを設定してください。

Setup following user macros in Property Manager of Visual Studio.

![image](https://user-images.githubusercontent.com/530182/61995780-d7fa5b00-b0c7-11e9-9efd-8d7d3534c5eb.png)
