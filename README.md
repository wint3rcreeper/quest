# quest

#include<iostream>
#include<string>
using namespace std;
int main() {
	string a;
	int root;
	root = 4;

	a = "lxxtw>33ir2{momtihme2svk3{mom3Tvskveqqiv";

		for (int i = 0; i < a.size(); ++i) {
				a[i] = a[i] - root;
		}
	cout << a;
	return 0;
}
