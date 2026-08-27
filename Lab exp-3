#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a, b, result;

    printf("Enter expression (a + b): ");
    scanf("%d + %d", &a, &b);

    result = a + b;

    printf("\nAnnotated Parse Tree:\n");
    printf("          E(%d)\n", result);
    printf("         / | \\\n");
    printf("      E(%d) + T(%d)\n", a, b);
    printf("       |       |\n");
    printf("     T(%d)    num(%d)\n", a, b);

    printf("\nValue of expression = %d\n", result);

    return 0;
}
