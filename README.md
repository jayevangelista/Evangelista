/* Evangelista */

#include<stdio.h>
#include<string.h>
main()
{
 char str[100],temp;
 int i=0,count=0,j,l;
 printf("Enter the string : ");
 gets(str);
 count=0;
 
 l=strlen(str)-1;
 for(j=0;j<=l;j++){
 	if(str[j]=='a'||str[j]=='b'){
 		if(str[j]=='b'){
 			count++;
     	}
 	}
 }
if(count>=5){
	printf(" Accepted");
}
else{
	printf("\nInvalid");
}
 return 0;
}
