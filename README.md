# CSUR

一个全新的分配 PUA 码位的志愿项目 (尽可能兼容现有的 (U)CSUR 项目)。

## 项目由来

虽然得益于 Unicode 标准，各系统都支持显示世界上 **几乎所有** 的文字，
但任何标准的完善不是一蹴即至。所以仍然有很多语言的文字还未收录进 Unicode，
有些也可能永远都不会收录进 Unicode。

那么想要使用这些文字只能在 PUA (私用区) 中自定义，(U)CSUR 等项目也就孕育而生。
但这些项目也并未收录完所有的人造语言 (这不是废话嘛)，而提交给他们进度不可控，
进而会影响到我的 [ConL-Fonts] 和 [ConL-IME] 等项目，所以决定自己维护一个 CSUR 项目。

[ConL-Fonts]: https://github.com/aj-ash/ConL-Fonts
[ConL-IME]: https://github.com/aj-ash/ConL-IME

## 流程

1. 发现/提交新语言
2. 审核通过，收录进本项目
3. 为文字分配 Unicode 码位
4. 制作字体 (发布在 ConL-Fonts 项目中)
5. 制作输入法 (发布在 ConL-IME 项目中)

## 提交新语言

请在 [Issues] 中提交新语言，并以外链的形式提供相关的参考资料
(需保证外链从提交日起，在 7 日内有效)。

+ 必选项
    + 列出所提交语言的所有字母或文字 (如果是语素文字还需提供标音或笔划方案)
    + 如果字母或文字不在 Unicode 中，需提供所有字母或文字的字形 (svg/png 格式)
+ 可选项
    + 转写方案
        + 让未安装相应字体的用户方便显示/输入
    + 语料库 (需为纯文本文件)
        + 输入词语、句子功能需要
    + 所有字母或文字的发音音频 (如果字母或文字不在 Unicode 中)
        + 可使用输入法的按键/上屏朗读功能

[Issues]: https://github.com/aj-ash/CSUR/issues

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

## 相关项目

### [ConL-Fonts]

旨在提供风格统一、美观的人造语言字体。

[ConL-Fonts]: https://github.com/aj-ash/ConL-Fonts

### [ConL-IME]

一款旨在为各种 **[人造语言]** 提供开箱即用、
简便和各平台输入体验统一的输入法。

[ConL-IME]: https://github.com/aj-ash/ConL-IME
[人造语言]: https://baike.baidu.com/item/%E4%BA%BA%E5%B7%A5%E8%AF%AD%E8%A8%80

### [ConL-Tutor]

为各人造语言收集整理/翻译/撰写中文教程。

[ConL-Tutor]: https://github.com/aj-ash/ConL-Tutor

### [ConL.ME]

以作者本人名字命名的人造语言。

[ConL.ME]: https://github.com/aj-ash/ConL.ME

### [CSUR]

一个全新的分配 PUA 码位的志愿项目 (尽可能兼容现有的 (U)CSUR 项目)。

[CSUR]: https://github.com/aj-ash/CSUR

### [IAA]

IAA 计划，即 INPUT ANYTHING ANYWHERE 计划。

该计划旨在为任何支持自定义词库的输入法和任何支持插件机制的软件提供
ConL-IME 项目中各语言的码表。从而实现在任何地方能输入任何文字和符号。

[IAA]: https://github.com/aj-ash/IAA

### [shupin]

一款开箱即用、简便和各平台输入体验统一的四川话拼音输入法。

[shupin]: https://github.com/aj-ash/shupin
