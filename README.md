#include <stdio.h>
int main() {
    printf("teamwork\nwe're team 6\n");
        int a = 2;
    int b = 2;
    printf("想继续看请按1,不想看请按0\n");
        scanf_s("%d",& a);
    if(a==1)
    {
    printf("我们小组啊，人好多的啊，有6个呐。还想继续看吗？\n想继续看请按1，结束请按0\n");
        scanf_s("%d",& b);
        if (b==1)
          {
          printf("我们组啊，有数学学院的陈阳，两个工程力学的李盈和邹乔丹，还有土木学院的林子榆，还有机械学院的李金泰\n谢谢观看\n");
          }
        else
          printf("不想看就再见了\n");
              }
   else
   printf("不想看就再见了\n");

   return 0;
}
