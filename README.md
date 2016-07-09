```
__     ___      _               _  ____ _______     ______
\ \   / (_)_ __| |_ _   _  __ _| |/ ___| ____\ \   / / ___|__ _ _ __ ___
 \ \ / /| | '__| __| | | |/ _` | | |  _|  _|  \ \ / / |   / _` | '_ ` _ \
  \ V / | | |  | |_| |_| | (_| | | |_| | |___  \ V /| |__| (_| | | | | | |
   \_/  |_|_|   \__|\__,_|\__,_|_|\____|_____|  \_/  \____\__,_|_| |_| |_|
```

# VirtualGEVCam

- Virtual GigE Vision Camera 虚拟 GigEVision 相机
- Platform: Windows 7 VS2008 / VS2010

# 如何使用

1. VirtualGEVCam 同目录下 `.\InData` 存放图片/流媒体文件
```
    InData
    ├── pic001
    │   ├── 1.mono
    │   └── 2.mono
    └── pic002
        ├── 1.mono
        └── 2.mono
```

2. `virtual-camera.xml` 为相机描述文件，需要事先压缩为 `virtual-camera.zip`

# 框图



# TODO

- 代码中大部分组件有考虑跨平台；但目前不支持 *nux 平台
- 目前只支持 Mono8 的图片
- 已经完成 GigEVision 基本协议内容；部分高级功能未实现
