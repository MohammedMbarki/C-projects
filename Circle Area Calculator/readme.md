# Circle Area Calculator

## Description
This program:
- Prompts the user to input the radius of a circle.
- Calculates the area of the circle using the formula:  Area = π × radius² 
```c
#include <stdio.h>

int main() {
    double radius; 
    const float PI = 3.14;

    printf("Please enter the radius of the circle:   ");
    scanf("%lf", &radius);  

    printf("The area of this circle is: %.2f cm²\n", radius * radius * PI ); 
    
    return 0; 
}

