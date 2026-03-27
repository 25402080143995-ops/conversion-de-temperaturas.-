# conversion-de-temperaturas.-
proyecto en equipo, al que convierta las diferentes temperaturas a diferentes grados celisius
#include <iostream>
using namespace std;

int main() {
    float celsius, reamur;

    cout << "Ingresa la temperatura en grados Celsius: ";
    cin >> celsius;

    // Fórmula: Réaumur = Celsius * 0.8
    reamur = celsius * 0.8;

    cout << "La temperatura en grados Reamur es: " << reamur << endl;

    return 0;
}
