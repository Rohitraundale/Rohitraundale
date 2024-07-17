Auto:
 the auto keyword is used to declare automatic variables. By default, all local variables (variables declared within a function) are automatic variables unless explicitly declared otherwise. This means that the auto keyword is rarely used in modern C programming, as it is the default storage class for local variables.
 Example:
 #include <stdio.h>

void exampleFunction() {
    auto int a = 10;  // 'auto' keyword is optional here
    int b = 20;       // 'auto' is implied

    printf("a = %d, b = %d\n", a, b);
}

int main() {
    exampleFunction();
    return 0;
}
Break:
the break keyword is used to exit a loop or switch statement prematurely. When the break statement is encountered inside a loop (such as for, while, or do-while) or a switch statement, the control immediately comes out of the loop or switch, and the execution continues with the next statement after the loop or switch.
Example:
#include <stdio.h>

int main() {
    for (int i = 0; i < 10; i++) {
        if (i == 5) {
            break; // Exit the loop when i equals 5
        }
        printf("%d\n", i);
    }
    printf("Loop ended.\n");
    return 0;
}
Case:
The case keyword in C programming is used within a switch statement. The switch statement allows you to branch your program's execution based on the value of a variable or expression. Each case represents a possible value that the variable or expression might take, and the code associated with that case is executed if there is a match.
Example:
#include <stdio.h>

int main() {
    int day = 3;

    switch (day) {
        case 1:
            printf("Monday\n");
            break;
        case 2:
            printf("Tuesday\n");
            break;
        case 3:
            printf("Wednesday\n");
            break;
        case 4:
            printf("Thursday\n");
            break;
        case 5:
            printf("Friday\n");
            break;
        case 6:
            printf("Saturday\n");
            break;
        case 7:
            printf("Sunday\n");
            break;
        default:
            printf("Invalid day\n");
            break;
    }

    return 0;
}
char:
In C programming, the char keyword is used to declare character variables. A char in C typically holds a single byte, which can store a single character or an integer value in the range of -128 to 127 (or 0 to 255 if declared as unsigned char).
Example:
char letter = 'A';
const:
The const keyword in C programming is used to define variables whose values cannot be modified after their initial assignment. This is helpful for defining constants or ensuring that certain variables remain unchanged throughout the program, thereby increasing code reliability and readability.
Example:
#include <stdio.h>

int main() {
    const int number = 10;

    // number = 20; // This will cause a compilation error

    printf("The value of number is: %d\n", number);
    return 0;
}
Continue:

The continue keyword in C programming is used within looping constructs such as for, while, or do-while loops. When the continue statement is encountered inside a loop, it skips the rest of the code inside the loop for the current iteration and proceeds with the next iteration of the loop.
Example:
#include <stdio.h>

int main() {
    for (int i = 0; i < 10; i++) {
        if (i % 2 == 0) {
            continue;  // Skip the rest of the loop body if i is even
        }
        printf("%d ", i);
    }
    return 0;
}
Default:


