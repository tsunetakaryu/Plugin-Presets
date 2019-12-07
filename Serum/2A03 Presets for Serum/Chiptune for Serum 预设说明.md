# 2A03 for Serum 预设说明

原作者／Yamato Ryou（原 FL 吧吧主）
编辑者／Ryusa



## 部署方法

1. 在 Serum 音源里，点击 *Menu—Show Serum Presets folder* 以打开预设文件夹。
2. 将解包得到的 *.fxp* 文件复制到 *Presets\User* 目录下。
3. 回到 Serum 音源，点击 *Menu—Rescan folders on disk* 以刷新预设文件。
4. 现在可以在预设窗口中浏览并加载了。



## 预设清单

- 2A03 12.5 Pulse Wave Analogue
- 2A03 25 Pulse Wave Analogue
- 2A03 50 Pulse Wave Analogue
- 2A03 Triangle Wave Analogue
- VRC6 Saw A Analogue
- VRC6 Saw B Analogue




## 音色比较

Analogue（模拟）为单个周期采样调用的波形文件，Digital（数字）为精准绘制而出的波形。

此外，Analogue 启用了一个低通滤波器平滑去除 22kHz 以上的频率，以抑制吉布森现象的产生。因而高频会听起来稍微柔和。

### Analogue

 ![TIM图片20170915130200](TIM图片20170915130200.png)

### Digital

 ![sp170915_130359](sp170915_130359.png)



## 特性

- 支持**力度—音量映射**（Velocity-Volume mapping）
- 支持基于**颤音速度**与**深度**控制（Vibrato speed / depth control）
- 支持基于**震音速度**与**深度**控制（Tremolo speed / depth control）
- 支持**滑音**及**滑音速度**控制（Legato slide / slide speed control）
- 支持**门限深度**控制（Gate depth control）





## 控制器信息

| 控制器   | 功能                      | 缺省值  | 对应参数 |
| :---- | :---------------------- | ---- | ---- |
| Pitch | 音高                      | 0    | -    |
| CC1   | 颤音深度／Vibrato Depth      | 0    | -    |
| CC2   | 震音深度／Tremolo Depth      | 0    | -    |
| CC3   | 颤音速度／Vibrato Speed      | 80   | 1/16 |
| CC4   | 震音速度／Tremolo Speed      | 127  | 1/16 |
| CC5   | 滑音速度／Legato Slide Speed | 45   | 45ms |
| CC7   | 主音量／Master Volume       | 89   | 70   |
| CC12  | 门限调制深度／Gate Depth       | 0    | -    |



## 备注

音色的标准音量以 C4 键 -16dBFs 为基准。