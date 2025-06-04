// source : https://cses.fi/problemset/task/1068
// solution:
#include <iostream>
using namespace std;

void CollatzConjectureVerification(long int num)
{
  cout << num << " ";
  while (num != 1)
  {
    (num % 2 == 0) ? num = num / 2 : num = 3 * num + 1;
    cout << num << " ";
  }
  cout << endl;
}

int main()
{
  CollatzConjectureVerification(3) // 3 10 5 16 8 4 2 1;
  CollatzConjectureVerification(8) // 8 4 2 1;
}

// Sidi Abdullah Lemrabott
