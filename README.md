#介绍
模板构建工具主要功能根据模板生成目标语言的代码
	
#用法
	1.编写对应语言的模板文件
	2.执行模板构建工具生成对应语言的模板代码
	3.将生成代码导入项目直接使用

#注意
要生成指定效果的模板代码，必须指定运行时参数，如果不知道参数的使用方式使用-help查看

#源码
查看源码可以使用: git clone https://github.com/abao-hello/tpl-builder.git
下载源码进行查看，但是需要注意地方是，源码不要使用go get的方式进行下载，这样会导致
引用无法找到。
