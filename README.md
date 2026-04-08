# define-and-declare-structure-
#include <stdio.h>

struct Book {
    int id;
    float price;
};
int main() {
    struct Book b1;
    printf("\n25331A05E8\n");

    printf("Enter Book ID:\n");
    scanf("%d", &b1.id);

    printf("Enter Book Price:\n");
    scanf("%f", &b1.price);
    
    printf("\nBook Details\n");
    printf("Book ID: %d\n", b1.id);
    printf("Price: %.2f\n", b1.price);
    return 0;
}
