# RFC文档添加标签

通过RFC的pdf目录生成标签，方便查看。

# 使用方法

需要先安装python3以及PyPDF2，pdfminer两个包。
```
$ python add_bookmarks_to_pdf.py foo.pdf
```

结果得到添加标签后的pdf文档 `foo_bookmark_version.pdf`
