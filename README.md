#include<iostream>
#include<conio.h>
using namespace std;

int main() {
    int n;
    cout << "Enter Number of students: ";
    cin >> n;

    int students[n];
    int sum = 0;


    for(int i = 0; i < 5; i++) {
        cout<< "Marks for student : " << i+1 <<":";
        cin >> students[i];
        sum = sum + students[i];
    }

    cout << "Total marks: " << sum << endl;
    float avg = (float)(sum) / n;
    cout << "Average: " << avg << endl;

    getch();
}
