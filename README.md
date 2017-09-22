# Lab4-1028916

## Lenguaje c++:

// Simple Hello World
 
#include <iostream>
int sumar (int a, int b){
        return a+b;
}



int restar (int a, int b){
    return a-b;
}



int multiplicar (int a, int b){
    return a*b; 
}

double dividir (double a, double b){
    return a/b;
}

void sumarpunteros (int , int , int*);
void restarpunteros(int , int , int*);
void multiplicarpunteros(int , int , int*):
void dividirpunteros(int , int , int*);


int main()  
{
    int resultado;
    sumarpuntero(5,7,&resultado);
    std::cout <<resultado<< std:: endl;
    
    int resultado1;
    restarpunteros(5,7, &resultado1);
    std:: cout <<resultado1<< std:: endl;
    
    int resultado2;
    multiplicarpuntero(5,7,&resultado2);
    std:: cout <<resultado2 << std:: endl;
    
    int resultado3;
    dividirpunteros(5,7,&resultado3);
    std:: cout <<resultado3 << std:: endl;
    
 std::cout << "C++ ESTA EN EL TERCE PUESTO DE USO A NIVEL INTERNACIONAL" << std::endl;
  return 0;
}


void sumarpunteros(int a, int b, int* resultado){
    resultado = a+b;
}

void restarpunteros(int a, int b, int* resultado1){
    resultado1 = a-b;
}

void multiplicarpunteros(int a, int b, int* resultado2){
    resultado2 = a*b;
}

void dividirpunteros(int a, int b, int* resultado3){
    resultado3 = a/b;
}



## ¿Qué hice hoy en laboratorio número 4?
Lo que hice es poner en practica lo que se aprendio en la clase de teoría ya que programamos en c++ para poderlo ver detallado y más facilmente con esto se observo como trabaja la memoria STACK de un sistema operativo utilizando Referencias (&) y Punteros(*).

## ¿Qué lo que aprendí hoy?
Lo que aprendi fue como se utiliza el lenguaje de c++ ya que es un lenguaje con más antiguedad pero se a actualizando para poder cubrir las demandas de otros programadores en distintos clases tanto en telefono como computadoras.


