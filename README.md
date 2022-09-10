# structure
This is a program for storing data with dissimilar data types together using structures and arrays in C programming.


#include <stdio.h>

struct Book
{
    char Book_Name[20];
    char Author_Name[30];
    int pages;
    float price;
    int sales;
};

int main()
{
    struct Book B1 = {"Let Us C", "Yashvant Kanetkar", 758, 240, 1200};
    struct Book B2 = {"C programming", "Ajay", 550, 200, 1000};
    printf("Book Name = %s\n", B1.Book_Name);
    printf("Author Name = %s\n", B1.Author_Name);
    printf("Pages = %d\n", B1.pages);
    printf("Price = %2f\n", B1.price);
    printf("Sales = %d\n\n", B1.sales);
    printf("Book Name = %s\n", B2.Book_Name);
    printf("Author Name = %s\n", B2.Author_Name);
    printf("Pages = %d\n", B2.pages);
    printf("Price = %2f\n", B2.price);
    printf("Sales = %d\n", B2.sales);
    return 0;
}

Output:
Book Name = Let Us C
Author Name = Yashvant Kanetkar
Pages = 758
Price = 240.000000
Sales = 1200

Book Name = C programming      
Author Name = Ajay
Pages = 550
Price = 200.000000
Sales = 1000
