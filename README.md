#include<stdio.h>
int main()
{
int score;
char grade;
printf("输入分数:\n");
scanf_s("%d"，&score);
grade=score>=81?'A':
score>=61?'B':
score>=41?'C':
score>=21?'D':'E';
printf("成绩为%c\n",grade);
return 0;
}
