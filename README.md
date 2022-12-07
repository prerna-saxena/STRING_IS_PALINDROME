# STRING_IS_PALINDROME




#include <stdio.h>
#include <string.h>

int main()
{
    char string;
    scanf("%s", &string);
    int l=0;
    int h=strlen(string)-1;
    
    while(h>l)
    if(string[l++]!=string[h--]){
        printf("%s string isnot a palindrome", string);
    }
}
        
    printf("%s string is a palindrome", string);
    return 0;
    
    
}
