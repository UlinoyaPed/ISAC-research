# 北京工业大学新生研讨课学期报告模板

编辑 `report.tex` 填写封面、摘要和正文。封面的 `reportmembers` 中，每个 `\member{姓名}{学号}` 对应一位成员；个人报告保留一行，小组报告按需添加。学院、专业和班级为共同信息，可按实际情况填写。

在本目录运行 `latexmk -xelatex report.tex`，生成 `report.pdf`。VS Code 的 LaTeX Workshop 已配置同一编译方式。字体使用 TeX Live 自带的 Fandol 和 TeX Gyre Termes。

`BJUTReport.sty` 控制版式，`figures/bjut_logo.pdf` 为封面标识。模板仅保留当前使用的功能；参考文献、代码高亮和数学扩展包可在实际需要时添加。

版式改编自 ZJUT Report（Apache-2.0），上游署名保留在样式文件头；校名标识来自 https://github.com/PEKEW/BJUTLATEX ，保留其 Apache-2.0 许可于 LICENSE。本模板非学校官方格式规范。
