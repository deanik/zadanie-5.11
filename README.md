#include <iostream>
#include <bitset>

using namespace std;




int main() {
    int A;
    int B;
    int zadanie1 = A||B;
    int zadanie2 = A&&B;
    int zadanie3 = A^B;
    int zadanie4 = ~A;
    int zadanie5 = ~B;

    cin>>A;
    cin>>B;
    cout<<"|: "<<zadanie1<<", "<<bitset<8>(zadanie1).to_string()<<endl;
    cout<<"&: "<<zadanie2<<", "<<bitset<8>(zadanie2).to_string()<<endl;
    cout<<"^: "<<bitset<8>(zadanie3).to_string()<<endl;
    cout<<"~a: "<<bitset<8>(zadanie4).to_string()<<endl;
    cout<<"~b: "<<bitset<8>(zadanie5).to_string()<<endl;
    return 0;
}
