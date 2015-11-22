#include <cmath>
#include <iostream>
using namespace std;
double calculate_e(double a)
{
  double b,c;
  if(a==0)
  {
  b=1;
  return b;
  }
  c= 1+(1/a);
  b=pow(c,a);
return b;
}
int main()
{
  float a;
  cout << "Insert number " << endl;
  cin >> a;
  cout << "e is  " << calculate_e(a) << endl;
  return 0;
}
