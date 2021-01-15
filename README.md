# ExcelTools
## 一个用于合并Excel表格的小工具
## 本软件用于合并两个Excel表,用法如下：
### 1.点击#选择第一个文件#, 在弹出的窗口中选择并确定
### 2.点击#选择第二个文件#, 在弹出的窗口中选择并确定
### 3.点击#加载文件#，如果没有出错则会加载成功并进入处理页面
### 4.前面会大致输出两个文件的部分信息，默认处理第一个Sheet
### 5.选择对应的基准组，第一个必选，第二个可选
### 6.确定后点击#开始合并文件#，合并后的文件将保存在软件目录下
## 其他问题请联系作者Violetnris@outlook.com或者直接提交issues

## 开发环境Python 3.8，主要使用了Tkinter和Xlwt，Xlrd。
### fakeData用于生成测试信息，不过需要手动去改一下生成的Excel，后面想起来再弄一个全自动的
### info_0.xls和info_1.xls是已经弄好的测试信息，共有1000行
