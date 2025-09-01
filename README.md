# -program-to-input-name-age-and-percentage-of-a-student-and-print-them-in-a-formatted-way.

 int main()
{
 char name[50];
 int age ;
 float percentage;
 
 printf("enter name\n");
 scanf("%s", &name);
 
 printf("enter age\n");
 scanf("%d" , &age);
 
 printf("enter percentage\n");
 scanf("%f" , &percentage);
 
 printf("student details\n");
 printf("name: %s\n",name);
 printf("age:%d years\n",age);
 printf("percentage:%f\n",percentage);
  
}

