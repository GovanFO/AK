# Apex-NoRecoil-Alpha

An AutoHotKey script (works on multiple resolutions) to minimize recoil with auto weapon detection for Apex Legends. 

Apex Legends 压枪宏，带武器自动检测。

## AHK Script - Description 介绍
This repository contains an Autohotkey script to help you minimize weapon recoil. Your weapon is auto-detected by the script (no need to press the F key anymore! XD). The detection is based on a straightforward and naive strategy (I call it three-pixel-detection). It is pretty safe because all it does is just capture some pixels and then use mouse DllCall to move your mouse. Run the compiled version if you want more protection. 

该库包含了一个带自动武器检测的 Apex Legends 压枪宏，不读内存，不注入游戏文件，纯粹就是识别像素颜色并帮助你移动鼠标。

- Pros
  - comes with GUI 有圖形界面
  - support multiple resolution settings 支持多種分辨率
  - simple 简单
  - out of the box 开箱即用
  - support different language setting in game 支持不同的游戏语言设置
- Cons
  - too many magic pixel position 太多神奇的像素位置设定
  - need lots of modification to support other resolution 很难去支持别的分辨率
