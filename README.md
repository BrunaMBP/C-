//Questão 1;

#include <stdio.h>

int main()

{

int INDICE = 13, SOMA = 0, K = 0;

 while(K < INDICE){

K = K + 1;
SOMA = SOMA + K;

   }

   printf("%d",SOMA);

return 0;

}

//Questão 2;

Termo1 = int(0)

Termo2 = int(1)

Termo3 = int(0)

print ('-' *42)

print (' ' *3, 'Consulta da Sequência de Fibonacci')

print ('-' *42)

Valor = int(input('Digite um número: '))

while Valor > Termo3:

Termo3 = Termo1 + Termo2

Termo1 = Termo2

Termo2 = Termo3

if Valor == 0 or Valor == 1:

print ('O número faz parte da sequência de Fibonacci.')

elif Valor == Termo3:

print ('O número faz parte da sequência de Fibonacci.')

else:

print ('O número digitado não faz parte da sequência de Fibonacci.')

//Questão 3

a) 9
b) 128
c) 49
d) 100
e) 13
f) 200

//Questão 4

Para determinar o local em que o carro e o caminhão se cruzam podemos colocar o ponto de referência em Ribeirão Preto, então, a equação horária do carro é: x1 = v1.t

Como o caminhão sai de um local 100 km distante do ponto de referência e se aproxima dele, sua equação horária é: x2 = 100km-v2.t

Como o caminhão tem 2 pedágios como obstáculo e perde 5 minutos em cada um deles, podemos calcular o tempo de viagem sem os obstáculos: Tso = 100km / 80(km/h) = 1,25h

Porém, como perde 10 minutos (ou 0,17 horas) nos pedágios, o tempo de viagem para o caminhão será de 1,25h+0,17h=1,42h. Sua velocidade média é: 72,6 km/h

Nas equações horárias podemos limpar o tempo e igualar ambas para achar o ponto em que o carro e o caminhão se cruzam: t = x1/v1
t = x2-100km/-v2
x1 = x2=> x/v1 = x-100km/-v2
-v2.x = v1.x - v1.100
x = v1.100/v1+v2 = 110.100/110+70,6
x = 60,98 km

//Questão 5

   string novaStr=string.Empty;
   string strOriginal;
   int i;
   
   strOriginal = "TesteInverter";
   for (i = strOriginal.Length-1; i >=0; i--)
   {
   novaStr += strOriginal[i];
   }

