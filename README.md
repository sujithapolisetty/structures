# structures
#include<stdio.h>
struct Employee{
	char Name[50];
	int EmployeeId;
	int Experience;
	float Salary;
};
void displayData(struct Employee emp);
int main()
{
	struct Employee emp1;
	printf("Enter Full Name : ");
	scanf("%s",&emp1.Name);
	printf("Enter EmployeeID: ");
	scanf("%d",&emp1.EmployeeId);
	printf("Enter Experience : ");
	scanf("%d",&emp1.Experience);
	printf("Enter Salary: ");
	scanf("%f",&emp1.Salary);
	printf("\nDisplaying Information of Employee 1 \n");
	displayData(emp1);
	
	struct Employee emp2;
	printf("Enter Full Name : ");
	scanf("%s",&emp2.Name);
	printf("Enter EmployeeID: ");
	scanf("%d",&emp2.EmployeeId);
	printf("Enter Experience : ");
	scanf("%d",&emp2.Experience);
	printf("Enter Salary: ");
	scanf("%f",&emp2.Salary);
	printf("\nDisplaying Information of Employee 2 \n");
	displayData(emp2);
	
	struct Employee emp3;
	printf("Enter Full Name : ");
	scanf("%s",&emp3.Name);
	printf("Enter EmployeeID: ");
	scanf("%d",&emp3.EmployeeId);
	printf("Enter Experience : ");
	scanf("%d",&emp3.Experience);
	printf("Enter Salary: ");
	scanf("%f",&emp3.Salary);
	printf("\nDisplaying Information of Employee 3 \n");
	displayData(emp3);
	
	struct Employee emp4;
	printf("Enter Full Name : ");
	scanf("%s",&emp4.Name);
	printf("Enter EmployeeID: ");
	scanf("%d",&emp4.EmployeeId);
	printf("Enter Experience : ");
	scanf("%d",&emp4.Experience);
	printf("Enter Salary: ");
	scanf("%f",&emp4.Salary);
	printf("\nDisplaying Information of Employee 4 \n");
	displayData(emp4);
	
	struct Employee emp5;
	printf("Enter Full Name : ");
	scanf("%s",&emp5.Name);
	printf("Enter EmployeeID: ");
	scanf("%d",&emp5.EmployeeId);
	printf("Enter Experience : ");
	scanf("%d",&emp5.Experience);
	printf("Enter Salary: ");
	scanf("%f",&emp5.Salary);
	printf("\nDisplaying Information of Employee 5 \n");
	displayData(emp5);
}
void displayData(struct Employee emp)
{
	printf("Name : %s \n",emp.Name);
	printf("EmployeeID : %d \n",emp.EmployeeId);
	printf("Experience  : %d \n",emp.Experience);
	printf("Salary : %f \n",emp.Salary);
	printf("\n");	
}
