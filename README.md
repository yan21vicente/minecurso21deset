# minecurso21deset
#include <iostream>
#include <fstream>

using namespace std;

int main()
{
    int numero;
    cout << "Digite um numero" << endl;
    cin >> numero;

    ofstream arquivo;
    arquivo.open("teste.txt", ios::out);
    cout << "Numero lido " << numero << endl;
    arquivo << numero;


    arquivo.close();
    return 0;
}

