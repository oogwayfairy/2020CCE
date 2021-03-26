## 除惡務盡 
```C++
#include <stdio.h>
int main()
{
	char a[100];
	scanf("%s",&a);///將字串依序放入陣列!!最後加上'\0'
	
	int i=0;
	
	while( a[i] != '\0'){
		if(a[i] != '2')printf("%c", a[i]);
		i++;
	}
	printf("\n");
}
```
## 擲骰統計 
```C++
#include <stdio.h>
int main()
{
	char n[100];
	scanf("%s",&n);
	
	int i=0;
	
	int a=0, b=0, c=0, d=0, e=0, f=0;
	while( n[i] != '\0')
	{
		if(n[i]=='1')a++;
		else if(n[i]=='2')b++;
		else if(n[i]=='3')c++;
		else if(n[i]=='4')d++;
		else if(n[i]=='5')e++;
		else if(n[i]=='6')f++;
		i++;
	}
	printf("1:%d\n2:%d\n3:%d\n4:%d\n5:%d\n6:%d\n",a ,b ,c ,d, e, f);
}
```
## 函數找整數的最大數字
```C++
#include <stdio.h>
int main()
{
	char a[100];
	scanf("%s",&a);
	
	char ans=a[0];
	int i=0;
	
	while( a[i] != '\0')
	{
		if( a[i] > ans ) ans=a[i];
		i++;
	}
	
	printf("[%c]",ans);
}
```
## 星星等腰三角 
```C++
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	
	for(int i=0; i<n; i++){
		for(int s=n-i-1; s>0; s--){
			printf(" ");
		}
		for(int r=0; r<2*i+1; r++){
			printf("*");
		}
		printf("\n");
	}
}
```
## 分開整數的每個數字 
```C++
#include <stdio.h>
#include <string.h>
int main()
{
	char a[100];
	scanf("%s",&a);
	
	int i=0;
	
	while( i<(strlen(a)-1) )
	{
		printf("%c   ",a[i]);
		i++;
	}
	printf("%c",a[i]);
}

```
## 字元判別 
```C++
#include <stdio.h>
int main()
{
	char n;
	scanf("%c",&n);
	
	if(64<n && n<91) printf("U");
	else if(96<n && n<123) printf("L");
	else if('0'<n && n<'9') printf("D");
	else printf("O");
}
```
## 數字之首 
```C++
#include <stdio.h>
int main()
{
	char a[100];
	scanf("%s",a);
	
	int i=0;
	
	printf("%c",a[0]);
}
```
## 輸出從0到N的偶數 
```C++
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	
	for(int i=1; i<=n/2; i++){
		printf("%d ",i*2 );
		}
}
```
