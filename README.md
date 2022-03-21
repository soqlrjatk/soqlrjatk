
#include <iostream>

int main() {
	double a[5], n;
	int i;

	std::cout << "5 개의 실수를 입력하라>>";
	for (i = 1; i <= 5; i++)
		std::cin >> a[i];
	n = a[1];

	for (i = 1; i <= 5; i++)
		if (a[i] > n)
			n = a[i];

	std::cout << "제일 큰 수 = " << n << std::endl; 

	return 0;

}
