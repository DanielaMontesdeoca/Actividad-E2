# Programas en c++ de Montesdeoca Daniela  

## Informacion del  autor 

```
Autora: Montesdeoca Castillo Daniela Mishelle 

Correo: mishellecmontesdeoca@gmail.com

Link del video: https://youtu.be/tJQ3DwvqJgo

```

# Nombres de los programas.

```
MontesdeocaDaniela-Compara.cpp

MontesdeocaDaniela-CuentaMoneda.cpp

MontesdeocaDaniela-Laedad.cpp

MontesdeocaDaniela-PuntoVenta.cpp

MontesdeocaDaniela-SumaN.cpp

```

# Descripcion de los programas.

```

1° MontesdeocaDaniela-Compara.cpp: 

Es un programa que nos permite comparar dos números y verificar cual de estos es el mayor, menor o si son iguales.

2° MontesdeocaDaniela-CuentaMoneda.cpp: 

Es un programa que permite al usuario contar monedas, saber cuanto es la cantidad de dinero que tiene y cuantas monedas tiene.

3° MontesdeocaDaniela-Laedad.cpp: 

Es un programa que permite al usuario calcular su edad en Años Meses y Dias

4° MontesdeocaDaniela-PuntoVenta.cpp :  

Es un programa la cual esta se encargara de calcular la compra de varios productos, calculando su valor bruto, sumandole el Iva a la compra y realizando un descuento adicional a la compra del usuario'

5° MontesdeocaDaniela-SumaN.cpp : 

Es un programa encargado para que cualquier usuario pueda calcular un valor de muchos numeros.

```
# Funcionalidad

```

MontesdeocaDaniela-Compara.cpp:

float MD_x,MD_y;
cout<<"Ingrese el valor de X: ";
cin>>MD_x;
cout<<"Ingrese el valor de Y: ";
cin>>MD_y;

MontesdeocaDaniela-CuentaMoneda.cpp:

int MD_n,MD_c=0,MD_c1=0,MD_c2=0;
float MD_x,MD_a=0,MD_a1=0,MD_a2=0;
cout<<"Cantidad de monedas a ingresar: ";
cin>>MD_n;
do{
cout<<"Ingrese el valor de la moneda (0.10,0.25): ";
cin>>MD_x;
	
MontesdeocaDaniela-Laedad.cpp:

int MD_aa,MD_ma,MD_da,MD_an,MD_mn,MD_dn,MD_a,MD_m,MD_d;
cout<<"Ingrese la fecha actual (aaaa mn dd): ";
cin>>MD_aa>>MD_mn>>MD_da;
cout<<"Ingrese la fecha de nacimiento (aaaa mn dd): ";
cin>>MD_an>>MD_mn>>MD_dn;

MontesdeocaDaniela-PuntoVenta.cpp:

int MD_c=0,MD_p;
float MD_x,MD_a=0,MD_vb,MD_Viva,MD_Vdes,MD_Vf,MD_iva=0.12,MD_des=0.30;
cout<<"Ingrese la cantidad de producto a comprar: ";
cin>>MD_p;
do{
cout<<"Ingrese el valor del producto: "; 
cin>>MD_x;

MontesdeocaDaniela-SumaN.cpp

int MD_c=0,MD_a;
float MD_s=0,MD_b;
cout<<"Ingrese la cantidad de numeros a sumar: ";
cin>>MD_a;
do{
cout<<"Ingrese un nunero: ";
cin>>MD_b;

```

# Salidas de los programas

```

MontesdeocaDaniela-Compara.cpp:

cout<<"El valor de X: "<<MD_x<<"es menor a Y:"<<MD_y<<endl;
}else{
cout<<"El valor de Y: "<<MD_y<<"es menor a X:"<<MD_x<<endl;

MontesdeocaDaniela-CuentaMoneda.cpp:

cout<<"El resultado fue: "<<endl;
cout<<"Cantidad total en dinero contado: "<<MD_a<<endl;
cout<<"Cantidad total de monedas de 0.10 ingresadas: "<<MD_c1<<endl;
cout<<"Cantidad total de dinero de monedas de 0.10: "<<MD_a1<<endl;
cout<<"Cantidad de monedas de 0.25 ingresadas: "<<MD_c2<<endl;
cout<<"Cantidad total de dinero de monedas de 0.25: "<<MD_c2<<endl;

MontesdeocaDaniela-Laedad.cpp:

cout<<"La persona tiene "<<MD_a<<" años "<<MD_m<<" meses y "<<MD_d<<" dias ";

MontesdeocaDaniela-PuntoVenta.cpp:

cout<<"El valor total de su compra a pagar es: $ "<<MD_Vf<<endl;

MontesdeocaDaniela-SumaN.cpp:

cout<<"La suma total es: "<<MD_s<<endl;

```

# Instalacion

```
1.- Descargar F-Droid

https://f-droid.org/

2.- Descargar la Terminal (Termux)

Dentro de la aplicación F-Droid

3.- Instalar paquetes en la Terminal (Termux)

pkg install git

pkg install vim

pkg install g++

pkg install clang

apt update

apt upgrade

4.- Clonar el Repositorio en la Terminal

git clone https://github.com/DanielaMontesdeoca/Actividad-E2.git

5.- Acceder al Repositorio

cd Actividad-E2

6.- Acceder al Directorio

cd Actividad-B2-C2

7.- Escribir Comando > ls

MontesdeocaDaniela-Compara
MontesdeocaDaniela-Compara.cpp
MontesdeocaDaniela-Compara.jpg
MontesdeocaDaniela-CuentaMoneda
MontesdeocaDaniela-CuentaMoneda.cpp
MontesdeocaDaniela-CuentaMoneda.jpg
MontesdeocaDaniela-Laedad
MontesdeocaDaniela-Laedad.cpp
MontesdeocaDaniela-Laedad.jpg
MontesdeocaDaniela-puntoventa
MontesdeocaDaniela-puntoventa.cpp
MontesdeocaDaniela-puntoventa.jpg
MontesdeocaDaniela-SumaN
MontesdeocaDaniela-SumaN.cpp
MontesdeocaDaniela-SumaN.jpg

```

# Compilacion de un programa

```

1.- Ingresar al Repositorio

cd Actividad-E2

2.- Ingresar al Directorio

cd Actividad-B2-C2

3.- Compilar Programa

g++ MontesdeocaDaniela-Compara.cpp -o MontesdeocaDaniela-Compara

Ejecución de un Programa

./MontesdeocaDaniela-Compara

```



