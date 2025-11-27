# 仅限公开仓库，否则无法获取信息

[TOC]



## 静态标签

获取方式：进入[Shields.io](https://shields.io/)创建，或者可以直接在官网搜索关键字

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

- #### commit个数

![](https://img.shields.io/github/commit-activity/t/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/commit-activity/t/BlueBoxChamil/ReadmeTest)
```

- #### last commit

![](https://img.shields.io/github/last-commit/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/last-commit/BlueBoxChamil/ReadmeTest)
```

- #### 最新release

![](https://img.shields.io/github/v/release/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/v/release/BlueBoxChamil/ReadmeTest)
```

- #### release日期

![](https://img.shields.io/github/release-date/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/release-date/BlueBoxChamil/ReadmeTest)
```

- #### 最新tag

![](https://img.shields.io/github/v/tag/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/v/tag/BlueBoxChamil/ReadmeTest)
```

- #### issues

![](https://img.shields.io/github/issues/BlueBoxChamil/ReadmeTest)

![](https://img.shields.io/github/issues-closed/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/issues/BlueBoxChamil/ReadmeTest)
![](https://img.shields.io/github/issues-closed/BlueBoxChamil/ReadmeTest)
```

- #### repositories创建日期

![](https://img.shields.io/github/created-at/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/created-at/BlueBoxChamil/ReadmeTest)
```

- #### repositories大小

![](https://img.shields.io/github/repo-size/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/repo-size/BlueBoxChamil/ReadmeTest)
```

- #### 代码大小

![](https://img.shields.io/github/languages/code-size/BlueBoxChamil/LVGL-clock)

```
![](https://img.shields.io/github/languages/code-size/BlueBoxChamil/LVGL-clock)
```

- #### star人数

![](https://img.shields.io/github/stars/BlueBoxChamil/LVGL-clock)

```
![](https://img.shields.io/github/stars/BlueBoxChamil/LVGL-clock)
```

- #### 贡献者个数

![](https://img.shields.io/github/contributors/BlueBoxChamil/ReadmeTest)

```
![](https://img.shields.io/github/contributors/BlueBoxChamil/ReadmeTest)
```

- #### label，要存在才行

![](https://img.shields.io/github/labels/BlueBoxChamil/ReadmeTest/question)

![](https://img.shields.io/github/labels/BlueBoxChamil/ReadmeTest/bug)

```
![](https://img.shields.io/github/labels/BlueBoxChamil/ReadmeTest/question)
![](https://img.shields.io/github/labels/BlueBoxChamil/ReadmeTest/bug)
```

#### 

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
> - 但使用typora生成的目录在vscode中看不到，当在vscode中用标准格式写入一级标题时，会自动补全出后续的标题，这个有可能是markdowm中的某些插件生成的。这种目录更通用点，而且还会随着标题的更新而自动更新



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

