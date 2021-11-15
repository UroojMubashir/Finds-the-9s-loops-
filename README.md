#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x = 0;
	int sum = 0;
	do
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << " ";
			sum = sum + x;
			}
		x++;
	}
	while (x <= 200);
	cout << endl;
	cout << "\nThe sum is " << sum << endl;
}
