# task1
this is my first repository
#include <iostream>
#include <cstdlib>
using namespace std;

void dice(int n) {
	srand(time(0));
	for (int i = 0; i < n;i++) {
		cout << 1+(rand() % 6) << endl;
	}
}

int main() {
	int x;
	cout << "Enter number of times dice roll: ";
	cin >> x;
	dice(x);
}
