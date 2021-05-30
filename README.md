#include <stdio.h>
int main()
{
    FILE *fp;
fp = fopen("cap.txt","a+");

//fprintf(fp, "%s", " MyCaptain");
    /*line by line - fgets()
    char by char - getc()
    word by word - fscanf()*/

   int ch=getc(fp);

  while(ch!=EOF)
    {
        printf("%c",ch);
        ch=getc(fp);
    }
    putc()
    fclose(fp);
    return 0;
}
