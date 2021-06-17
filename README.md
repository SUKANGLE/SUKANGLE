- 👋 Hi, I’m @SUKANGLE
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SUKANGLE/SUKANGLE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
笔记
转义字符 \
两个八进制如何转化为十进制 。32，                                                                130           
3                                           2                       |           1                                     3                                      0                
1                                           0                       |           2                                     1                                      0
3乘以八的一次方    相加      2乘以2的零次方      |         1乘以8的2次方          +      3乘以8的1次方        +          0乘以8的0次方
24                          +            2                        |         64                             +    24                           +          0      
=26                                                                |           =88
ASCII一些常见的数对应的字符
字符       0                  A                 a
十进制数48                81               97
字符        1                  B                b
十进制数 49                82               98
              以此类推
\x+数字      十六进制
\+数字        八进制
//while 循环语句
int main()
{
	int num =0;
	int line=0;
	while (line<200)//后没有;
	{
		printf("%d",num);
		printf("行代码\n");
		line++; 
		num++;
	错/*printf("125行代码/n");跳出循环好好研究
	break;*/
	}
	printf("好office");
	return 0;
}
//分支语句
//int main()
//{
//	int  offie=0;
//	printf("比赛\n");
//	printf("你是sb吗？（1/0)>:");
//	scanf("%d",& offie);
//	if (offie ==0)
//	printf("对的我是\n");
//	else
//		printf("不我是大聪明\n");
//	return 0;
//}
数组
数组的定义
int arr[5]={1,2,3,4,5};//定义一个数组，最多放5个元素
arr的内存布局      
12345
01234//元素的下标。下标是从零开始
要想访问第n个元素n对应的下标是n-1

数字转换成二进制
1                            1                   1                   1                      1                          1                      1
1*2的6次方              1*2的5次方    1*2的4次方     1*2的3次方      1*2的2次方            1*2的1次方       1*2的0次方
64                              32                       16                    8                        4                           2                         1
算出100的二进制数
因为64+32+4=100
答案
1                             1                   0                     0                      1                       0                        0
赋值操作符
=  赋值    ==判断相不相等
