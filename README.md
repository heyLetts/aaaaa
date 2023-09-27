#include <iostream>
#include <locale.h>

int main(int argc, char** argv){ 
double n1, n2
setlocale(LC_ALL,"Portuguese");
char operacao 

std::cout<<"Digite o primeiro número";
std::cin>>n1;

std::cout<<"Digite uma operação (+, -, , /)";
std::cin>>operacao;

std::cout<<"Digite o segundo número";
std::cin>>n2;

double resultado; //adicionar variavel resultado

if(operacao=='+'){
    resultado=n1+n2;
}

else if(operacao=='-'){
    resultado=n1-n2;
}
 
else if(operacao==''){
    resultado=n1*n2;
}

else if(operacao=='/'){ 
if(n2!=0)
    resultado=n1/n2;
}
{
    else std::cout<<error/0
}
