#include <iostream>
#include <Math.h>
using namespace std;
int main()
{
float c, a, b, s;
cout << "üçgenin dik kenarlarını giriniz" << "\n";
cout << "1.kenar(a) = "; cin >> a;
cout << "2.kenar(b) = "; cin >> b;
c = pow(a, 2) + pow(b, 2);
s = sqrt(c);
cout << "hipotenüs = " << s;

float v, f, b, s1, s2;
cout << "vize ve final notunuzu giriniz : \n";
cin >> v >> f;
s1 = v * 0.5 + f * 0.5;
if (s1 < 60) {
	cout << "büte kaldınız\n";
	cout << "büt sonucunu giriniz\n";
	cin >> b;
	s2 = v * 0.5 + b * 0.5;
	if (s2 < 60) {
		cout << "malesef sınıfı geçemediniz\n";
	}
	else {
		cout << "sınıfı bütle geçtiniz\n";
	}
		
}
else {
	cout << "sınıfı geçtiniz\n";
}


}
return 0;
}
