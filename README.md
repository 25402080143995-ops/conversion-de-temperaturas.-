# conversion-de-temperaturas.-
proyecto en equipo, al que convierta las diferentes temperaturas a diferentes grados celisius
#include <iostream>
using namespace std;

int main() {
    float celsius,rankine,kelvin,reamur,fahrenheit;
    cout<<"escribir el numero de la operacion que necesitas" <<endl;
    int op;
    cout<<"1 convertir celsius a rankine"<<endl;
    cout<<"2 convertir celsius a fahrenheit"<<endl;
    cout<<"3 celsius a kelvin"<<endl;
    cout<<"4 convertir celsius a reamur"<<endl;
    
    cin>>op;
    cout<<"introducir celsius:";
    cin>>celsius;

    return 0;
}
(op==2)
    {                
    fahrenheit=(celsius*9/5)+32;
    cout<<celsius<<" celsius = "<<fahrenheit<<" fahrenheit"<<endl;}
