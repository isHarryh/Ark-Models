Ark-Models
==========
Arknights Spine Models (Excerpt)  
明日方舟Spine动画小人模型(节选)

**🇨🇳中文** **|** [🌎English](README-eng.md)

## 状态

当前更新至：
- 活动 **引航者试炼 5** 中新增的干员、时装和敌人模型

本仓库收集了中国服《明日方舟》中的部分Spine模型文件，包括：
| 文件夹           | 内 容           |
| :--------------: | :--------------: |
| `models`         | 干员基建小人（含时装） |
| `models_enemies` | 敌人战斗小人 |
| `models_illust`  | 干员动态立绘（含时装） |

> 本仓库为不定期更新，欢迎提交 PR 来完善仓库。本仓库使用的提取模型文件的工具是 [ArkUnpacker](https://github.com/isHarryh/Ark-Unpacker) v4.0。

## 仓库下载

可以通过以下链接来下载本仓库的完整压缩包（压缩包大小为 800+MB）。

- [从 GitHub 下载](https://github.com/isHarryh/Ark-Models/archive/refs/heads/main.zip)
- [从 Cloudflare 代理源下载](https://ghproxy.harryh.cn/?q=https%3A%2F%2Fgithub.com%2FisHarryh%2FArk-Models%2Farchive%2Frefs%2Fheads%2Fmain.zip)

或者，您可以在仓库中检索具体的模型文件来单独下载它们。

如需使用 Git 来克隆本仓库，建议使用 `--depth=1` 参数来减少克隆的总大小。

## 格式说明

《明日方舟》的 Spine 模型需要 [Spine Runtime](https://github.com/EsotericSoftware/spine-runtimes) v3.8 才能运行。一套Spine模型通常由 `.atlas` 文件、`.skel` 文件和`.png` 图片组成。

本仓库中，每个 Spine 模型会被分别存放到不同的子目录中。根目录的 `models_data.json` 数据集文件中记录了每个模型的具体信息。

## 重要变更

- 2025 年 4 月：自《明日方舟》v2.5.04 起，所有干员基建小人模型发生了变更。它们不再采用 2 的幂次方的图片尺寸，并且 ATLAS 文件中记录的图片尺寸与真实尺寸不匹配（通常是放大到了 1.5 倍）。作为应对，本仓库已经把这类图片进行了缩放，以保证 ATLAS 与图片尺寸的一致性。同时，对仓库的历史提交进行了重写。
- 2025 年 3 月：已经对所有的模型纹理图强制启用 Premultiplied Alpha (PMA)。
- 2024 年 8 月：已经发现中国服官方有个别模型的骨骼文件不是二进制格式，而是 JSON 格式。
- 2024 年 7 月：本仓库不再使用由 [ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData) 提供的数据集（因为 ArkUnpacker v3.0 已实现了这些数据的解码）。
- 2024 年 2 月：本仓库新增干员动态立绘（含时装）的模型。同时，数据集的格式发生变更。
- 2024 年 1 月：自《明日方舟》v2.1.41 起，新增的模型已经禁用了 Premultiplied Alpha (PMA)。
- 2023 年 4 月：本仓库新增敌人战斗小人的模型。同时，数据集的格式发生变更。

## 版权声明

本仓库中所有素材其版权归属 [**上海鹰角网络有限公司**](https://www.hypergryph.com) 所有。不得用于商业用途，不得损害版权方的利益。
