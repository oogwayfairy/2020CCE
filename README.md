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
