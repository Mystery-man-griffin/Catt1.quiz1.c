#include <stdio.h>



// Define the structure for employee

struct employee {

    char name[25];

    int id;

    char department[20];

    float salary;

    char email[50];

};



int main() {

    // Initialize an employee variable with given data

    struct employee emp = {

        "John Doe",          // name

        12345,               // id

        "Human Resources",   // department

        55000.50,            // salary

        "john.doe@company.com" // email

    };



    // Print the employee details

    printf("Employee Details:\n");

    printf("Name: %s\n", emp.name);

    printf("ID: %d\n", emp.id);

    printf("Department: %s\n", emp.department);

    printf("Salary: %.2f\n", emp.salary);

    printf("Email: %s\n", emp.email);



    return 0;

}

