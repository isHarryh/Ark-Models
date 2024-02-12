Ark-Models
==========
Arknights Spine Models (Excerpt)  
明日方舟Spine动画小人模型(节选)  

[中文](README.md) | **English**

## Overview

This repository collected some Spine models of the game Arknights (CN server) :

| Directory        | Content          |
| :--------------: | :--------------: |
| `models`         | Operators' building modles (skins included) |
| `models_enemies` | Enemies' battle models |
| `models_illust`  | Dynamic illustrations (skins included) |

> We will do updates irregularly, you are welcome to send PR to improve the repository. The tool we use to unpack the model files is [ArkUnpacker](https://github.com/isHarryh/Ark-Unpacker) v2.6. The dataset is collected from [ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData).

## Download

Just click the green button `Code` on the upper right of this webpage, then click `Download ZIP` to download all.

## Formats

The models depends on [Spine Runtime](https://github.com/EsotericSoftware/spine-runtimes) v3.8. A Spine model is usually composed of one `.atlas` file, one `.skel` file and one `.png` image file.

In this repo, Spine models will be stored into their directories respectively.  
The dataset file `models_data.json` recorded the detailed information of each model.

## Breaking Changes

- Feb.2024: Added dynamic illustrations (skins included) to this repo. Changed the dataset file.
- Jan.2024: `Premultiplied Alpha` should be disabled when rendering the new models due to the update of Arknights v2.1.41.
- Apr.2023: Added enemies' battle models to this repo. Changed the dataset file.

## Copyright Notice

The copyright of the resources in the repository belongs to [**HYPERGRYPH Co.,Ltd.**](https://www.hypergryph.com) Please do use the resources in a proper way.
