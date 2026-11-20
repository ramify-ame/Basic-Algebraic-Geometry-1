# Basic Algebraic Geometry 1

本仓库收录 Igor R. Shafarevich《基础代数几何 I：射影空间中的簇》中文译本的 LaTeX 源码。目前收录导言、第一章「基本概念」和第二章「局部性质」。译文以 Miles Reid 的第三版英译本（Springer，2013）为底本。

**翻译由 GLM5.3 完成。**

## 目录结构

源文件布局参考 [siqiliu-tsinghua/fan](https://github.com/siqiliu-tsinghua/fan)。

- [`src/BAG1/main.tex`](src/BAG1/main.tex) 是排版入口。
- [`src/BAG1/chapters/`](src/BAG1/chapters/) 存放导言和各章正文。
- [`src/BAG1/`](src/BAG1/) 同时存放封面、字体、版式和模板示例等 TeX 源文件。

## 编译

请将原模板中的 `AJbook.cls`、`myarrows.sty`、`mycommand.sty`、`Al-jabr.bib` 和 `ccby.png` 放在 `src/BAG1/` 下，再从该目录使用 XeLaTeX 编译 `main.tex`。参考文献和索引分别使用 Biber 和 xindy。字体设置见 [`font-setup-open.tex`](src/BAG1/font-setup-open.tex)。

本项目使用李文威的 AJbook 模板，模板的署名和许可说明保留在相应的 TeX 源文件中。
