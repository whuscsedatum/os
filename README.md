# 操作系统复习讲义 TeX 源码

这个目录保存的是《操作系统》复习讲义的 LaTeX 源码。

- `main.tex` 是主入口。
- `chapters/` 下是各章节内容。
- `frontmatter.tex` 是前置说明。
- `review.tex` 是总复习部分。
- `record.txt` 和 `record_structured.txt` 是老师课上带过考点的整理记录。

当前状态：

- 章节内容已按 `source/` 下的 PPT 做过逐章补全。
- `review.tex` 已整理为高频辨析与做题模板，覆盖老师重点强调的大题模块和关键词。
- 当前可直接通过 `latexmk -xelatex -interaction=nonstopmode -halt-on-error main.tex` 构建。
- 最新构建产物为 `main.pdf`（A4，95 页）。
