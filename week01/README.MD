## 找零錢
```c++
#include<stdio.h>
int main()
{
	int m;
	scanf("%d",&m);
	
	printf("%d=50*%d+5*%d+1*%d\n",m ,m/50 ,m%50/5,m%5);
}
```
## 因數個數
```c++
#include<stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	
	int ans=0;
		
	for(int t=1; t<=n; t++){
		if ( n % t ==0)
		ans=ans+1;
	}
	
	printf("%d\n",ans);
}
## 找倍數 
#include<stdio.h>
int main()
{
	int a[10];
	int ans=0;
	
	for(int i=0; i<10; i++){
		scanf("%d", &a[i]);
		if(a[i]%3==0) ans = ans + 1 ;
		}
	
	printf("%d\n",ans);
}
```
## 找倍數
```c++
#include<stdio.h>
int main()
{
	int a[10];
	int ans=0;
	
	for(int i=0; i<10; i++){
		scanf("%d", &a[i]);
		if(a[i]%3==0) ans = ans + 1 ;
		}
	
	printf("%d\n",ans);
}
```
## 整數轉換為等級 
```c++
#include<stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	
	if ( n>=90 ) printf("A\n");
	else if( n>=80 && n<90 ) printf("B\n");
	else if( n>=60 && n<80 ) printf("C\n");
	else printf("F\n");
}
```
## 分式化簡
```c++
#include <stdio.h>
int main()
{
	int a,b;
	scanf("%d%d",&a ,&b);
	
	int ans=0;
	
	
	for(int i=1; i<=b; i++){
		if( a%i==0 && b%i==0)ans=i;
	}
	
	printf("%d %d\n",a/ans,b/ans);
}
```
