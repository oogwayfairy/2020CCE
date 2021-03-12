# 2020CCE
## 第一題
```c++
#include <stdio.h>
int main()
{
  int a[5]={0,10,20,30,40};
  int *p = &a[2];
  *p = 3333;
  
  p = p+2;
  p = 5555;
}
```
## 第二題
```c++
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printALL(){
  for(int i=0; i<5; i++)printf("%d",a[i]);
    printf("\n");
}
int main()
{
        printfALL();
  int *p = &a[2];
  *p = 3333;
        printfALL();
  p = p+2;
  *p = 5555;
        printfALL();
  p--;
  *p = 4444;
        printfALL();
}
```
## 第三題
```c++
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printALL(){
  for(int i=0; i<5; i++)printf("%d",a[i]);
    printf("\n");
}
int main()
{
        printfALL();
  int *p = &a[2];
  *p = 3333;
        printfALL();
        printf("p心理小紙條記的值是:%d\n", p);
  p = p+2;
  *p = 5555;
        printfALL();
        printf("p心理小紙條記的值是:%d\n", p);
  p--;
  *p = 4444;
        printfALL();
        printf("p心理小紙條記的值是:%d\n", p);
}
```
