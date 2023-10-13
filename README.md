# RofaidaKhaled5
#include <stdio.h> 
#include <string.h> 
 

int main() {
      char username[15]; 
    char password[12]; 
 
 
    printf("Enter your username:\n"); 
    scanf("%s",&username); 
 
    printf("Enter your password:\n"); 
    scanf("%s",&password); 
 
    if(strcmp(username,"rofaida")==0){ 
        if(strcmp(password,"123")==0){ 
 
        printf("\nWelcome.Login Success!"); 
 
 
        }else{ 
    printf("\nwrong password"); 
} 
    }else{ 
    printf("\nPlease try again"); 
} 
 
 
 
 
 
    return 0; 
 
}
