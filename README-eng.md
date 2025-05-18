Ark-Models
==========
Arknights Spine Models (Excerpt)  
明日方舟Spine动画小人模型(节选)

[🇨🇳中文](README.md) **|** **🌎English**

## Overview

This repository collected the Spine models from the game Arknights (CN server), including:

| Directory        | Content          |
| :--------------: | :--------------: |
| `models`         | Operators' building models (skins included) |
| `models_enemies` | Enemies' battle models |
| `models_illust`  | Dynamic illustrations (skins included) |

> We will do updates irregularly, you are welcome to send PR to improve the repository. The tool we use to unpack the model files is [ArkUnpacker](https://github.com/isHarryh/Ark-Unpacker) v4.0.

## Download

[Click here to download the ZIP archive file.](https://github.com/isHarryh/Ark-Models/archive/refs/heads/main.zip) However, the size of the entire repository is very large, so downloading the specific files you want may be faster.

If you want to clone this repo via Git, it is recommended to use `--depth=1` to prevent massive cloning.

## Formats

The models depends on [Spine Runtime](https://github.com/EsotericSoftware/spine-runtimes) v3.8. A Spine model is usually composed of one `.atlas` file, one `.skel` file and one `.png` image file.

In this repo, Spine models will be stored into their directories respectively.
The dataset file `models_data.json` recorded the detailed information of each model.

## Breaking Changes

- Apr.2025: Starting from version 2.5.04 of Arknights, all operators' building models have undergone changes. They no longer use the image size to the power of two, and the image size recorded in the [ATLAS file] does not match the actual size (usually enlarged to 1.5 times). As a response, our repo has scaled these images to ensure consistency between ATLAS and image size. We also rewrote our repo commit history.
- Mar.2025: Premultiplied Alpha (PMA) was forcibly enabled for all the model textures.
- Aug.2025: In CN server, we found that there are very few models whose skeleton files are not in binary format but in JSON format.
- Jul.2024: Stopped using the dataset provided by [ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData) since ArkUnpacker v3.0 has implemented the decoding of such data.
- Feb.2024: Added dynamic illustrations (skins included) to this repo. Changed the dataset file.
- Jan.2024: Premultiplied Alpha (PMA) are disabled for the models after version v2.1.41 of Arknights.
- Apr.2023: Added enemies' battle models to this repo. Changed the dataset file.

## Copyright Notice

The copyright of the resources in the repository belongs to [**HYPERGRYPH Co.,Ltd.**](https://www.hypergryph.com) Please do use the resources in a proper way.
