# 依赖
- pandoc 2.0.3
- BasicTeX

# 命令行执行
```
pandoc test.md --toc  -f markdown -t latex -s -o a.pdf --pdf-engine=xelatex --template=pm-template.latex -V header='./Header.png'
-- toc 生成目录
header 指定封面的图片地址
```