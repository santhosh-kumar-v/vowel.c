#include<stdio.h>
#include <stdlib.h>
int main()
{
    int i, v[]={0, 0, 0, 0, 0};
    char str[1000], vowels[]={'a','e','i','o','u'};
    scanf("%[^\n]s",&str);
    for(i=0;i<strlen(s);i++)
    {
        char s=tolower(str[i]);
        if(s=='a')
            {
                v[0]++;
            }
        else if(s=='e')
            {
                v[1]++;
            }
        else if(s=='i')
            {
                v[2]++;
            }
        else if(s=='o')
            {
                v[3]++;
            }
        else if(s=='u')
            {
                v[4]++;
            }
    }
    for(i=0;i<5;i++)
    {
        if(vcount[i]!=0)
        {
            printf("%c --> %d\n", vowels[i], v[i]);
        }
    }
}
