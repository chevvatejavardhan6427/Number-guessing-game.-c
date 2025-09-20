#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main(){
	int secreatnum,attempts=0,guess;
	int max=100;
	int min=0;
	srand(time(0));
	secreatnum=(rand()%(max-min+1))+min;
	printf("lets play nuber guessing game \n");
	do {
		printf("enter your guess %d-%d : ",min,max);
		scanf("%d",&guess);
		attempts++;
		if(guess>secreatnum){
			printf("Too high , Try again\n");
		}else if (guess<secreatnum){
			printf("Too low , Try again\n ");
		}else{
			printf(" congratulations you guessed right! in %d attempts",attempts);
			
		}
	}while(guess!=secreatnum);
	return 0;
}
		
	
