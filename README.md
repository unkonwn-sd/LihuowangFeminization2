# LihuowangFeminization2

《杀戮尖塔 2》(Slay the Spire 2) 的李火旺娘化皮肤 mod。

本仓库发布可安装的整合版本，供需要该皮肤的用户直接使用。

## 版本

- 当前发布：`v3.1.0`
- 游戏版本：`0.111.0+`
- 角色依赖：`lihuowang2`（李火旺角色 mod）

## 功能

- 135 帧待机动画（4.5 秒循环）
- 36 帧独立受击动画
- 半血以下爆衣皮肤切换
- 攻击突进、战败 CG
- 选人页面保持原样
- 黑太岁前后外观一致

## 下载

- 仓库内直接下载 `LihuowangFeminization2.dll`、`LihuowangFeminization2.pck`、`LihuowangFeminization2.json`
- 或从 Releases 下载：https://github.com/unkonwn-sd/LihuowangFeminization2/releases/tag/v3.1.0

## 安装

1. 先安装李火旺角色 mod `lihuowang2`。
2. 安装 [RitsuLib](https://steamcommunity.com/sharedfiles/filedetails/?id=3747602295)（设置页依赖）。
3. 下载本仓库的 `LihuowangFeminization2.dll`、`LihuowangFeminization2.pck`、`LihuowangFeminization2.json`。
4. 放到：

```
Slay the Spire 2/mods/LihuowangFeminization2/
```

5. 启动游戏。

## 设置

游戏内：

```
设置 → Mods → 李火旺娘化
```

- **半血以下爆衣**：勾选后，生命 ≤ 50% 时切换爆衣形象；动作保持不变。
- 取消勾选或回血后恢复普通形象。

配置保存在：

```
user://LihuowangFeminization2.cfg
```

## 文件说明

| 文件 | 说明 |
|---|---|
| `LihuowangFeminization2.dll` | 逻辑与 Harmony 补丁 |
| `LihuowangFeminization2.pck` | 帧序列与贴图 |
| `LihuowangFeminization2.json` | mod 清单 |

## 兼容性

- 仅测试于 Slay the Spire 2 `0.111.0`。
- 需要 `lihuowang2` 角色 mod。
- 设置页需要 RitsuLib；没有 RitsuLib 时 mod 仍可运行，但无法在游戏内切换爆衣开关。

## 素材与版权

- 角色与原始立绘素材来自塔1 mod `HuowangFeminization`，版权归原作者所有。
- 本仓库只发布移植、整合与帧处理后的文件，不代表原作者立场。
- 如果你是其素材作者并希望下架，请开 issue 联系。

## License

代码与整合部分采用 MIT License，见 `LICENSE`。
美术素材不包含在 MIT 授权内，版权归原素材作者。
