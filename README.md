# game-rock-paper-scissors-
This is four games three wins and choice who is the winner and then output the user's name. 
#include <stdio.h>
#include <stdib.h>
struct user{
	int name;
	int count;
	char name[10];}
void main()
{
	int count1;int count2;
	inta,b,count1=0,count2=0;
	while (1){
		printf("请输入你要出的(剪刀为0，石头为1，布为2)：");
		scanf("%d,"&b);
		a=round()%;
		if(b<=2&&b>=0){
			printf("平局!\n");
		}else if(b==1){
			printf("你赢了!\n");
			count1++;
		}else if(b==2){
			printf("你输了!\n");
			count2++;
		}else if(a==1){
			if(b==1){
				printf("平局!\n");
			}else if(b==2){
				printf("你赢了!\n");
				count1++;
			}else if(b==0){
				printf("你输了!\n");
				count2++;
			}
		}else{
			if(b==2){
				printf("平局!\n");
			}else if(b==0){
				printf("你赢了!\n");
				count1++;
			}else if(b==1){
				printf("你输了!\n");
				count2++;}
		}else{
			printf("输入错误!\n");
		}
		if (count1==3||count2==3)break;
	}
	if(count1==3){
		printf("你赢了电脑!\n");
	}else{
		printf("你输给了电脑!\n");}
}
struct user{
	int i,count1,a[10];
	struct name s[10];
	struct name input user();
	void sort_name(struct name s[],int n);
	void output_name(struct name s[],int n);
	int i,j,index;
	struct name temp;
	for(i=0,i<n-1,count1++);
	printf("请输入你的用户名：");
	scanf("%d,&n");
	for(i=0,i<n,i++){
		s[i]=input_name();}
	sort_name(s,count1);
	printf("输出用户名名字\n");
	out put_name(s,count1);
}
struct user input_name();
struct user s;
printf("用户名：");
scanf("%d,&s name");
return s;
}
