# 仅限公开仓库，否则无法获取信息

[TOC]



## 静态标签

获取方式：进入[Shields.io](https://shields.io/)创建

- #### 标签名+信息

![](https://img.shields.io/badge/bluebox-jesse-orange)

```
![](https://img.shields.io/badge/bluebox-jesse-orange)
```

- #### 标签名

![](https://img.shields.io/badge/bluebox-orange)

```
![](https://img.shields.io/badge/bluebox-orange)
```

- #### 标签名+信息+可点击链接

[![](https://img.shields.io/badge/bluebox-web-purple)](https://www.blueboxchamil.online/)

```
[![](https://img.shields.io/badge/bluebox-web-purple)](https://www.blueboxchamil.online/)
```



## 仓库标签

仅用于github上，可以实时更新，但仓库必须是公开可读的

- #### 分支

![](https://badgen.net/github/branches/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/branches/BlueBoxChamil/ReadmeTest)
```

- #### 发布个数

![](https://badgen.net/github/releases/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/releases/BlueBoxChamil/ReadmeTest)
```

- #### 最新发布

![](https://badgen.net/github/release/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/release/BlueBoxChamil/ReadmeTest)
```

- #### 许可证

![](https://badgen.net/github/license/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/license/BlueBoxChamil/ReadmeTest)
```

- #### 观看人数

![](https://badgen.net/github/watchers/BlueBoxChamil/LVGL-clock)

```
![](https://badgen.net/github/watchers/BlueBoxChamil/LVGL-clock)
```

- #### tag个数

![](https://badgen.net/github/tags/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/tags/BlueBoxChamil/ReadmeTest)
```

- #### 最新tag

![](https://badgen.net/github/tag/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/tag/BlueBoxChamil/ReadmeTest)
```

- #### 收藏人数

![](https://badgen.net/github/stars/BlueBoxChamil/LVGL-clock)

```
![](https://badgen.net/github/stars/BlueBoxChamil/LVGL-clock)
```

- #### 贡献者个数

![](https://badgen.net/github/contributors/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/contributors/BlueBoxChamil/ReadmeTest)
```

- #### commit个数

![](https://badgen.net/github/commits/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/commits/BlueBoxChamil/ReadmeTest)
```

- #### 最近commit时间

![](https://badgen.net/github/last-commit/BlueBoxChamil/ReadmeTest)

```
![](https://badgen.net/github/last-commit/BlueBoxChamil/ReadmeTest)
```

## Admonition特殊语法

> [!tip]
>
> this is github tip
>
> 使用方法：
>
> ```
> >[!tip]
> ```

> [!caution]
>
> ```
> >[!caution]
> ```

> [!important]
>
> ```
> >[!important]
> ```

>[!note]
>
>```
>>[!note]
>```

> [!warning]
>
> ```
> >[!warning]
> ```



## 如何跳转标题到内容

任意取目录标题，不过为了方便阅读，最好选择和内容一样的标题，要注意内容标题的格式，需要加`#`，使用格式如下，

```
- [目录标题](#内容标题)
```

下边是使用示例

- [仅限公开仓库，否则无法获取信息](#仅限公开仓库否则无法获取信息)
  - [静态标签](#静态标签)
  - [仓库标签](#仓库标签)
  - [Admonition特殊语法](#admonition特殊语法)
  - [如何跳转标题到内容](#如何跳转标题到内容)
  - [优化显示小巧思](#优化显示小巧思)

> [!tip]
>
> - 当然也可以优先先把各级标题内容写好，在typora中直接点击`段落->内容目录`生成目录
> - 但这个在vscode中看不到，当在vscode中用标准格式写入一级标题时，会自动补全出后续的标题，这个有可能是markdowm中的某些插件生成的。这种目录更通用点，而且还会随着标题的更新而自动更新



## 优化显示小巧思

- #### 按键标签

  Press <kbd>ESC</kbd> to exit early and regain control

  ```
  Press <kbd>ESC</kbd> to exit early and regain control
  ```

  <kbd>CTRL</kbd>  <kbd>F5</kbd>

- #### 显示命令行

  用代码的格式

  ```
  `$ bing-rewards --profile "Default" "Profile 1" "Profile 2"`
  ```

  `$ bing-rewards --profile "Default" "Profile 1" "Profile 2"`

  `python --version`

  `<kbd>ESC</kbd>`

