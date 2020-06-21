# CSUR

一个全新的由个人维护的分配 PUA 码位的志愿项目 (尽可能兼容现有的 (U)CSUR 项目)。

## 项目由来

虽然得益于 Unicode 标准，各系统都支持显示世界上 **几乎所有** 的文字，
但任何标准的完善不是一蹴即至。所以仍然有很多文字还未收录进 Unicode，
有些也可能永远都不会收录进 Unicode。

那么想要显示和输入这些文字就只能在私用区中自定义，(U)CSUR 等项目也就孕育而生。
但这些项目也并未收录完所有的人造语言 (这不是废话嘛)，而提交给他们进度不可控，
进而会影响到我的 ConL-Fonts 和 ConL-IME 等项目，所以决定自己维护一个 CSUR 项目。

本项目只收录 (U)CSUR 项目未收录的语言。

## 流程

1. 发现新的语言/语言作者提交新的语言
2. 审核通过，收录进本项目
3. 为文字分配 Unicode 码位
4. 制作字体 (发布在 ConL-Fonts 项目中)
5. 制作输入法 (发布在 ConL-IME 项目中)

## 提交你的语言

尽管作者会通过网络搜寻满足条件的人造语言并将其添加进本项目，
但仍有许多未在网络上公布的人造语言。

所以如果你愿意将你的语言提交到本项目，请通过 [Issues] 的方式提交相关的资料。

+ 必选项
    + 需列出所有的字母或文字 (如果是语素文字还需提供标音或笔划方案)
    + 如果字母或文字不在 Unicode 中，需提供所有字母或文字的字形 (svg 或 png 格式的图片)
+ 可选项
    + 转写方案
        + 让未安装字体的用户方便输入你的语言
    + 语料库 (需为纯文本文件)
        + 能输入词语、句子
    + 所有字母或文字的发音音频 (如果字母或文字不在 Unicode 中)
        + 可使用输入法的按键/上屏朗读功能

[Issues]: https://github.com/aj-ash/CSUR/issues

### 注

资料的下载链接需保证从提交日起，在 7 日内都有效。

## 支持语言

| 平面     | 区段范围          | 区段码位数 | 已分配的语言              | 已分配区段范围 | 已分配的码位数 |
|:---------|:------------------|:-----------|:--------------------------|:---------------|:---------------|
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Tengwar                   | U+E000-U+E07F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Cirth                     | U+E080-U+E0FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Kinya                     | U+E150-U+E1AF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Ilianóre                  | U+E1B0-U+E1CF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Verdurian                 | U+E200-U+E26F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | aUI                       | U+E280-U+E29F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Amman-iar                 | U+E2A0-U+E2CF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Mizarian                  | U+E300-U+E33F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Zíirí:nka                 | U+E340-U+E35F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Olaetyan                  | U+E3B0-U+E3FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Gargoyle                  | U+E5C0-U+E5DF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Seussian Latin Extensions | U+E630-U+E64F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Sylabica                  | U+E650-U+E67F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Ewellic                   | U+E680-U+E6CF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Unifon Extended           | U+E6F0-U+E6FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Unifon                    | U+E740-U+E76F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Solresol                  | U+E770-U+E77F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Visible Speech            | U+E780-U+E7FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Monofon                   | U+E800-U+E82F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | D'ni                      | U+E830-U+E88F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Aurebesh                  | U+E890-U+E8DF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Tonal                     | U+E8E0-U+E8FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Glaitha-A                 | U+E900-U+E97F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Glaitha-B                 | U+E980-U+E9FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Wanya                     | U+EAA0-U+EAFF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Orokin                    | U+EB00-U+EB3F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Deini                     | U+ED00-U+ED3F  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Ath                       | U+F4C0-U+F4EF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Aiha                      | U+F8A0-U+F8CF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | Klingon                   | U+F8D0-U+F8FF  | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | 汉字笔划                  | 暂无           | 暂无           |
| 0 BMP    | U+E000-U+F8FF     | 6,400 个   | 暂无                      | 暂无           | 暂无           |
| 15 PUA-A | U+F0000-U+FFFFF   | 65,536 个  | 暂无                      | 暂无           | 暂无           |
| 15 PUA-A | U+F0000-U+FFFFF   | 65,536 个  | 暂无                      | 暂无           | 暂无           |
| 16 PUA-B | U+100000-U+10FFFF | 65,536 个  | 暂无                      | 暂无           | 暂无           |
| 16 PUA-B | U+100000-U+10FFFF | 65,536 个  | 暂无                      | 暂无           | 暂无           |

## 相关相目

+ [ConL-Fonts]

旨在提供风格统一、美观的泛 Unicode 字体。

[ConL-Fonts]: https://github.com/aj-ash/ConL-Fonts
