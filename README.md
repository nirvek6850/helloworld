
#include <stdio.h>

int main() {
    char name[50];
    float math, physics, chemistry;
    float total, percentage;

    printf("Enter student name: ");
    scanf("%49s", name);

    printf("Enter Math marks: ");
    scanf("%f", &math);

    printf("Enter Physics marks: ");
    scanf("%f", &physics);

    printf("Enter Chemistry marks: ");
    scanf("%f", &chemistry);

    total = math + physics + chemistry;
    percentage = total / 3;

    printf("\nStudent Result\n");
    printf("Name: %s\n", name);
    printf("Total Marks: %.2f\n", total);
    printf("Percentage: %.2f%%\n", percentage);

    return 0;
}
