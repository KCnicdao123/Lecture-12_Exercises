# Lecture-12_Exercises

//Months of the Year

#include <iostream>
#include <string>
#include <algorithm>

using namespace std;

int main()
{
	string Months[12] = { "January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December" };
	cout << Months[2];
}
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
 
//Time Travel

#include <iostream>
#include <string>
#include <algorithm>

int main()
{
	string Months[12] = { "January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December" };
	for (int x = 0; x < 12; x++) {
		cout << Months[x] << endl;
	}
}
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
                             
//Marks
                             
#include <iostream>
#include <string>
#include <algorithm>
                             
int main()
{
	double sum = 0, average = sum / 5;
	cout << "Enter the student's marks:" << endl;
	double studentMarks[5];
	for (int x = 0; x < 5; x++) {
		cin >> studentMarks[x];
		sum = sum + studentMarks[x];
	}
	average = sum / 5;
	cout << "\nThe average is: " << average << endl;
}
