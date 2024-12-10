# Personalized Greeting Program

This project is a simple C program that prompts the user to enter their name and responds with a personalized greeting message.

## Overview


## Prompt asking for the user's name
 ![image](https://github.com/user-attachments/assets/70a43b79-9e44-4734-91ab-2754d6bce166)
## User entering their name

![image](https://github.com/user-attachments/assets/02233fe1-2b78-4590-91af-3ae6289ad595)

## Personalized greeting displayed

![image](https://github.com/user-attachments/assets/b6b4ed49-8a6d-4d84-9af8-a5fa8ad07560)





### Code Overview
```c
#include <stdio.h>
#include <cs50.h>

int main (void)
{
    string answer = get_string("what is your name ");
    printf("hello %s\n", answer);
}

//you can run this code with cs50.dev
