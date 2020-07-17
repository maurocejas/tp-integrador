# tp-integrador

#include <iostream>
#include <cstdlib>
#include <stdio.h>
#include <ctime>
#include <cstring>
#include "Libreria.h"
using namespace std;

int main(){

int Opcion;

cout<<"---------------------------------------------------------------------------------------------------------------\n";
cout<<"  Menu Principal: |  Un Jugador (Ingresar '1')  |  Dos Jugadores (Ingresar '2')  |  Salir (Ingresar '3')  | "; cin>>Opcion;
cout<<"---------------------------------------------------------------------------------------------------------------\n\n";


while(!(Opcion==1) && !(Opcion==2) && !(Opcion==3)){
    cout<<" Por favor ingresa una de las opciones correctas para continuar (1/2/3)...  "; cin>>Opcion;
    cout<<endl;
}
cout<<endl;

if(Opcion==1){
    Opcion_1();
}
else{
    if(Opcion==2){
        Opcion_2();
    }
    else{
        return 0;
    }
}

cout<<endl <<endl;
return 0;
}

