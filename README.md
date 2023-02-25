开头句式:
#include<stdio.h>
<br>
int或者void main()
<br>
{<br>
    内容;<br>
}<br>
1:<br>
每一个内容结尾都要加";"<br>
如printf("114514");<br>
<br>
2:<br>
%d表示整数
%f表示小数
%c表示字符或数字
%d如:<br>
int test;<br>
test=314<br>
printf("%d",test);<br>
<br>
难点数组:<br>
int abc[10] = {1,2,3,4,5,6,7,8,9,10};<br>
printf("%d",abc[9]);<br>
输出为10<br>
abc后的[10]表示有10个数字<br>
第二行的abc后面的[9]表示数组第十个数字，因为在此处数字以0开始，所以:<br>
printf("%d",abc[0]);<br>
输出为1<br>
<br>
%f如:<br>
double h=3.14;<br>
float a=114514;<br>
printf("%f",h)<br>
在%与f中间加.x(x为正整数)<br>
效果:<br>
printf("%.5f",a);<br>
会输出114514.00000<br>
%.5f 中的 .5 表示小数点后5位小数<br>
<br>
%c如:<br>
char c;<br>
c='h'; //注:必须用单引号，单引号内只能有一个字母<br>
printf("%c",c);<br>
输出为:c<br>
<br>
%s如:<br>
char chinese[12]="你好世界";<br>
printf("%s",chinese);<br>
输出为:你好世界<br>
[12]的12意思是12字节，中文一个占3字节，所以用12<br>
而英文字母一个占1字节<br>
