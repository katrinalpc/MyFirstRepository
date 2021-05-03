[link to README.md](./README.md)


![img in current directory](./courses.jpg)
```
the jpg above is in current directory
```
![img from web]()
```
the jpg above is from web
```

## anH2sizedheader
#### anH4sizedheader.

[link to baidu](https://www.baidu.com)

<!-- code block -->
```c++
int parse_main(TokenList* p) {
	tokenhead = p;

	fprintf(ERRORTXT, "LL1语法分析：\n");
	TreeNode* root = parseLL1();
	fprintf(ERRORTXT, "\n\n");
	painttree(root);
	if (error == 0)
	{
		fprintf(ERRORTXT, "语义分析：\n");
		Analyze(root);
		fprintf(ERRORTXT, "\n\n");
	}
	fp_num = 0;  //记录token个数的变量
	error = 0;

	lineno = 0;    //源代码行号

	tokenhead = p;
	show = fopen("txt/Parse_Grammer.txt", "w+");
	space = 0;
	fprintf(ERRORTXT, "递归下降语法分析：\n");
	TreeNode* root2 = parse();
	fprintf(ERRORTXT, "\n\n");
	painttree(root2);
	return 0;
}

}
```

<!-- table -->
|1111111    | 2222222   |  
| --------- | --------- |  
| asdf    |  |  12341
| afad      |12341234|

__bolded text__  
*italic text*

~~strike through~~
`a block quote`

* unorderedlist
* unordered list

1. ordered list 
1. ordered
1. list





<!-- horizontal rule -->
___
