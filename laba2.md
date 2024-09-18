//Лабораторная2
#include <iostream>
using namespace std;
int main() {
	//Вариант3
	setlocale(LC_ALL, "RU");
	short a, b;
	cout << "Введи сторону A > 0" << endl;
	cin >> a;
	if (a > 0) {
		cout << "Введи сторону B < 20" << endl;
		cin >> b;
		if (b < 20) {
			cout << "Периметр прямоугольника со сторонами A и B = " << 2 * (a + b);
		}
		else
			cout << "Значение B не удовлетворяет условию, вводи заново))";
	}
	else
		cout << "Значение А не удовлетворяет условию, вводи заново))";
	return 0;
}
