#include <iostream>
using namespace std;

//QUESTÃO 7 DE FUNÇÕES

// Função que verifica se um número é par
int verificarPar(int numero) {
    if (numero % 2 == 0) {
        return 1; // Retorna 1 se for par
    } else {
        return 0; // Retorna 0 se for ímpar
    }
}

int main() {
    int numero;

    cout << "Digite um numero inteiro: ";
    cin >> numero;

    // Chama a função e verifica o resultado
    if (verificarPar(numero) == 1) {
        cout << numero << " E um numero par." << endl;
    } else {
        cout << numero << " E um numero impar." << endl;
    }

    return 0;
}




