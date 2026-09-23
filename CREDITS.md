# サードパーティ素材クレジット

このリソースパックの`assets/hakoniwacooking/textures/item/`に含まれるテクスチャ(計251点)は、
以下のMinecraft用MODのものを、各MODのMITライセンスに基づいて使用しています。
モデルJSON(`models/item/`)とアイテム定義(`items/`)は、HakoniwaCookingが独自に生成したものです。

| MOD | 作者 | 取得元(ブランチ) | ライセンスの根拠 | 使用点数 |
| --- | --- | --- | --- | --- |
| Farmer's Delight | vectorwing | https://github.com/vectorwing/FarmersDelight (1.21) | リポジトリのLICENSE(MIT) | 93(まな板を含む) |
| Ocean's Delight | Scouter456 | https://github.com/Scouter456/Oceans_Delight (oceans_delight_1.21_neoforge) | `gradle.properties`の`mod_license=MIT` | 24 |
| Corn Delight | Zheng Syameimaru | https://github.com/0999312/Corn-Delight (1.21) | リポジトリのLICENSE(MIT) | 21 |
| Cultural Delights | Baisylia | https://github.com/Baisylia/Cultural-Delights-1.18.2 (main) | `mods.toml`の`license="MIT License"`(※) | 50 |
| Delightful | brnbrd | https://github.com/brnbrd/Delightful (1.21.1) | リポジトリのLICENSE(MIT) | 63 |

※ Cultural Delightsは、MITと宣言されている1.18.2版からのみ取得しています(最新の1.21版は
All Rights Reservedのため使用していません)。

各ファイルの取得元は、ファイル名が元MODのアイテムIDと同じです(IDが重複した場合のみ
`cultural_`等の接頭辞を付けています)。対応表はプラグイン内の`data/items.json`の`source`を参照してください。

## ライセンス全文

以下の著作権表示のもと、MIT Licenseで提供されています。

```
Copyright (c) 2020 vectorwing                (Farmer's Delight)
Copyright (c) Scouter456                     (Ocean's Delight)
Copyright (c) 2022 Zheng Syameimaru          (Corn Delight)
Copyright (c) Baisylia                       (Cultural Delights)
Copyright (c) 2026 brnbrd                    (Delightful)

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
