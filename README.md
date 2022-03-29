
#include <stdlib.h>
#include <stdio.h>
#define _CRT_SECURE_NO_WARNINGS

// הגדרה של פונקציה
type funcname(type1 num1, type2 num2) 
{
//מימוש הפונקציה
}

//   |
//   V

int SUM(int num1,int num2) 
{
	return num1 + num2;
	// ^ הפעולה מתבצעת רק בפונקציה, בערכים שאני רוצה להחזיר

}

// type <- סוג funcname(int num1, num2) <-פרמטר ושם הפונקציה  
// here you can define functions like sum- adding 2 numbers, and returning them toghther...

void main() //what does main do?
{

	int num1, num2, result = 0;
	num1 = 5;
	num2 = 6;
	result = num1 + num2;
	num1 = 8;
	num2 = 9;
	result = num1 + num2;

	//  ^
	//  |
	//instead of doing this and adding it manually, you can use a function.

	system("pause");
}
