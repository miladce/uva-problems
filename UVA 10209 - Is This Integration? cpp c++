#include <iostream>
#include <math.h>
#include <iomanip> 
using namespace std;
#define pi M_PI  
int main(){
	double a;
	pair<double,int> b[60];
	while (cin >> a){
		double atri15=sin(pi / 6)*a*a * 1 / 2;
		double aarc15 = (pi*a*a) / 12;
		double adlt15 = aarc15 - atri15;
		double edge15 = 2 * a*cos(pi * 5 / 12);
		double asqu_l = edge15*edge15;
		asqu_l += 4 * adlt15;
		double aarc90 = (pi*a*a) / 4;
		double adlt90 = a*a - aarc90;
		double sec =2*( a*a - 2 * adlt90-asqu_l);
		double third = a*a - asqu_l - sec;
		cout <<setprecision(3)<<fixed<<asqu_l<<" "<<sec<<" "<<third<<endl;

	}
}
