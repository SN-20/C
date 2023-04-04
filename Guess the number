#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main ()
{
    int num,n;
    int count=1;
    srand(time(0));
    num= rand()%100;//Generates random number betweeen 1 t0 100 
    //printf("Random number is %d\n",num);
    //Keep running the loop till number is guessed 
    
    
                          //OPTION 1
    //if used while loop count will start from 1
    // printf("Guess a number:");
    // scanf("%d",&n);
    // while (n!=num)
    // {
    //     if(n>num) printf("Too High Enter a lower number\n");
    //     else printf("Too Low Enter a higher number\n");
    //     printf("Guess a number:");
    //     scanf("%d",&n);
    //     count++;
    // }
    // printf("You have guessed correct number in %d guesses",count);
    
    
    
                          //OPTION 2
    //if used do while loop count will start from 0
    do
    {
        printf("Guess a number:");
        scanf("%d",&n);
        if(n>num) printf("Too High Enter a lower number\n");
        else if(n<num) printf("Too Low Enter a higher number\n");
        else printf("You have guessed correct number in %d guesses",count);
        count++;
    }while(n!=num);
    return 0;
}
