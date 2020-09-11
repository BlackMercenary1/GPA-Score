# GPA-Score
CPET Quiz 1, Credit hours/Course = GPa
//**********************************************************************************
//  Title: GPA 
//  Course: Computational Problem Solving 1 (CPET-121)
//  Developer: Brian Morgan
//  Date: 11Sep'20
//  Description: GPA Score
//
//**********************************************************************************

#include <iostream>
#include <string>

using namespace std;

int main(void) {

string course1;
string course2;
float c1;
float c2;
float credit1;
float credit2; 

cin >> course1 >> credit1 ;
cin >> course2 >> credit2 ;

if (course1 == "A") {
      c1 = 4;
}
else if (course1 == "B") {
      c1 = 3;
}
else if (course1 == "C") {
      c1 = 2;
}
else if (course1 == "D") {
      c1 = 1;
}
else if (course1 == "F") {
      c1 = 0 ;
}

if (course2 == "A") {
   c2 = 4;
}
else if (course2 == "B") {
      c2 = 3;
}
else if (course2 == "C") {
      c2 = 2;
}
else if (course2 == "D") {
      c2 = 1;
}
else if (course2 == "F") {
      c2 = 0 ;
}

cout << "Your GPA is " << ((c1 * credit1) + (c2 * credit2)) / (credit1 + credit2) << endl;
   return (0);
}
