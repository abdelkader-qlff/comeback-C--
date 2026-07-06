# comeback-C--

#include <iostream>
using namespace std;
int main() {
	int age = 18;
	cout << "the number is " << age+1 << "\n";
	string name = "abdelkader";
	cout << "My name is " << name << endl;
	char fav_word = 'A';
	cout << "My favourite word is " << fav_word << endl;
	bool liscence;
	cout << "Do you have driver liscence? (enter 1 for yes and 0 for no) ";	
	cin >> liscence;
	cout << "Driver liscence: ";
	if (liscence == 1)
		cout << "yes" << endl;
	else
		cout << "No";
	float num1 = 2.5;
	double num2 = 5.000000145;
	cout << num1 << " * " << num2 << " = " << num1 * num2 << endl;
}



#include <iostream>
using namespace std;
int main() {
	int gr;
	cout << "enter your grade ";
	cin >> gr;
	if (gr < 50 && gr > 0) {
		cout << "you fail" << endl;
	}
	else if (gr >= 50 && gr < 60) {
		cout << "you get 'D'" << endl;
	}
	else if (gr >= 60 && gr < 70) {
		cout << "you get 'C'" << endl;
	}
	else if (gr >= 70 && gr < 80) {
		cout << "you get 'B'" << endl;
	}
	else if (gr >= 80 && gr < 90) {
		cout << "you get 'B+'" << endl;
	}
	else if (gr >= 90 && gr < 100) {
		cout << "you get 'A'" << endl;
	}
	else if (gr == 100) {
		cout << "you get a complet grade" << endl;
	}
	else {
		for (gr > 100 && gr < 0) {
			cout << "you entered a wrong grade\nTry again ";
			cin >> gr;
		}
	}
}



1)-switch lesson:
#include <iostream>
using namespace std;
int main() {
	int num1;
	int num2;
	char cal;
	cout << "enter number 1: ";
	cin >> num1;
	cout << "\nenter number 2: ";
	cin >> num2;
	cout << "\nenter the type of calculation: ";
	cin >> cal;
	switch (cal) {
	case '+':
		cout << num1 << " + " << num2 << " = " << num1 + num2 << endl;
		break;
	case '-':
		cout << num1 << " - " << num2 << " = " << num1 - num2 << endl;
		break;
	case '*':
		cout << num1 << " * " << num2 << " = " << num1 * num2 << endl;
		break;
	case '/':
		cout << num1 << " / " << num2 << " = " << num1 / num2 << endl;
		break;
	default:
		cout << "you entered invalide number" << endl;
		break;
	}
}



#include <iostream>
using namespace std;
int main() {
	for (int week = 1; week <= 3; week++) {
		cout << "week " << week << endl;
		for (int day = 1; day <= 7; day++) {
			cout << "	day " << day << endl;
		}
	}
}


#include <iostream>
using namespace std;
int main() {
	int number;
	int sum = 0;
	cout << "enter a number: ";
	cin >> number;
	while (number >= 0) {
		sum += number;
		cout << "enter a number ";
		cin >> number;
		
	}
		cout << "\nsum number equal " << sum << endl;

}


