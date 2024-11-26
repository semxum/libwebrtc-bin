# libwebrtc binaries

![build](https://github.com/crow-misia/libwebrtc-bin/workflows/build/badge.svg)
[![JitPack](https://jitpack.io/v/crow-misia/libwebrtc-bin.svg)](https://jitpack.io/#crow-misia/libwebrtc-bin)
[![License](https://img.shields.io/github/license/crow-misia/libwebrtc-bin)](LICENSE)

此存储库包含可用于构建静态链接的libwebrtc二进制文件的构建脚本。

## 状态

下表显示此项目的当前状态，包括支持的平台和架构。

<table>
  <tr>
    <td align="center"></td>
    <td align="center">x86</td>
    <td align="center">x64</td>
    <td align="center">arm</td>
    <td align="center">arm64</td>
  </tr>
  <tr>
    <th align="center">Linux</th>
    <td align="center">-</td>
    <td align="center">✔</td>
    <td align="center">✔</td>
    <td align="center">✔</td>
  </tr>
  <tr>
    <th align="center">macOS</th>
    <td align="center">-</td>
    <td align="center">✔</td>
    <td align="center">-</td>
    <td align="center">✔</td>
  </tr>
  <tr>
    <th align="center">Windows</th>
    <td align="center">✔</td>
    <td align="center">✔</td>
    <td align="center">-</td>
    <td align="center">-</td>
  </tr>
  <tr>
    <th align="center">iOS</th>
    <td align="center">-</td>
    <td align="center">✔</td>
    <td align="center">-</td>
    <td align="center">✔</td>
  </tr>
  <tr>
    <th align="center">Android</th>
    <td align="center">-</td>
    <td align="center">✔</td>
    <td align="center">✔</td>
    <td align="center">✔</td>
  </tr>
</table>

## 依赖环境

- Make
- Python 3.8 (Windows可选，因为它将使用位于在“depottools”安装中)

## 构建

### Linux / macOS / iOS / Android

```
cd build
make [options] [platform]
```

check `[options]` and `[platform]` by executing `make help`.

### Windows

```
build.windows.bat
```

## License

Apache License 2.0

## Reference

- https://webrtc.googlesource.com/src/
- https://github.com/aisouard/libwebrtc
- https://github.com/shiguredo/shiguredo-webrtc-windows
