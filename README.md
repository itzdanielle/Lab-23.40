# Lab-23.40
#include <iostream>
using namespace std;

int main() {
const int MAX_TEMP = 50;
int temperatures [MAX_TEMP];
int i, temperature[i], numberOfTemp, max, min;
double average; int sum = 0; 
cout << "Please enter the of temperatures to be read " << endl;
cin >> numberOfTemp;
cout << "Enter a temperature 1 - 100: " << endl;
cin >> temperature [i];
for (i = 0; i < numberOfTemp; i++) {
cin >> temperature[i];
}
max = temperature[0];
min = temperature[0];
for (int i = 0; i < numberOfTemp; i++) {
if (temperature[i] > max)
max = temperature[i];
if (temperature[i] < min)
min = temperature[i];
cout << "Input " << i+1 << " is " << temperature[i] << endl;
sum += temperature[i];
}

average = sum/ numberOfTemp;
cout << "The sum of the inputs " << numberOfTemp << " number is " << sum <<  endl;
cout << "The average temperature is " << average << endl;
cout << "The highest temperature is " << max << endl;
cout << "The lowest temperature is " << min << endl;
}
