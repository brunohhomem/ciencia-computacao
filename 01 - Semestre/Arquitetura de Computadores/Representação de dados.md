## Representação de dados

# Módulo 1 - Sistemas de computação

	- Unidades de informação
		- bit (binário 0/1)
		- byte (8 bits)
		- Para transformar de bit para byte, multiplicar por 8
		- Para transformar de byte para bit, dividir por 8
		
	"Um sistema de computação precisa usar representações simbólicas para que o processamento dos dados seja realizado corretamente e em conformidade com as expectativas de seus projetistas e usuários."
	
	Apontaremos, a seguir, quatro conjuntos formados nas unidades de informação:

	- Um conjunto ordenado de bytes, que representa uma informação útil para os computadores, constitui uma palavra.
	- Um conjunto estruturado de palavras forma um registro.
	- Um conjunto organizado de registros forma um arquivo.
	- Um conjunto organizado de arquivos forma um banco de dados.
	
# Módulo 2 - Sistemas de numeração e operações aritméticas

	# Sistema Posicional
	- Base 10 (decimal): 0, 1, 2, 3, 4, 5, 6, 7, 8, 9.
	- Base 2 (binária): 0, 1.
	- Base 8 (octal): 0, 1, 2, 3, 4, 5, 6, 7.
	- Base 16 (hexadecimal): 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F.
	
Em qualquer sistema posicional, o número é formado da seguinte maneira:

	- Da direita para a esquerda
Cresce a partir do valor 0 (seguido do 1 até o último algarismo válido).
Exemplo: bases 3 (algarismos 0 a 2) e 10 (algarismos 0 a 9).
	
	- Retorna a 0
Quando a contagem chega ao último algarismo válido de uma posição, ela retorna a 0 e cresce uma unidade para a esquerda.
Exemplo: base 10 — cresce de 0 a 9. Depois, 10, 11, …, 19 — Na direita, retorna a 0 e cresce 1 para a esquerda: 20.

	# Sistema não posicional

Todo algarismo tem valor fixo independentemente de sua posição no número.
No sistema de numeração romano, o algarismo X vale sempre 10.

* Dentro de uma unidade especializada (unidade lógica e aritmética), o processador usa seus circuitos lógicos digitais para realizar operações lógicas e aritméticas, tendo o bit como unidade para representação de dados. *

	
# Módulo 3 - Conversão

Embora os sistemas de computação expressem seus valores na base 2 (binária), eles poderão ser representados em outras bases quando houver a necessidade de promover uma melhor visualização e compactar os seus valores. 
Geralmente, são usadas as bases 8 (octal) e 16 (hexadecimal), pois ambas são múltiplas de 2.

Esta tabela mostra a equivalência dos valores nas bases 2, 8, 10 e 16:

| Base 2 	| Base 8 	| Base 10 	| Base 16 	|
|--------	|--------	|---------	|---------	|
| 0      	| 0      	| 0       	| 0       	|
| 1      	| 1      	| 1       	| 1       	|
| 10     	| 2      	| 2       	| 2       	|
| 11     	| 3      	| 3       	| 3       	|
| 100    	| 4      	| 4       	| 4       	|
| 101    	| 5      	| 5       	| 5       	|
| 110    	| 6      	| 6       	| 6       	|
| 111    	| 7      	| 7       	| 7       	|
| 1000   	| 10     	| 8       	| 8       	|
| 1001   	| 11     	| 9       	| 9       	|
| 1010   	| 12     	| 10      	| A       	|
| 1011   	| 13     	| 11      	| B       	|
| 1100   	| 14     	| 12      	| C       	|
| 1101   	| 15     	| 13      	| D       	|
| 1110   	| 16     	| 14      	| E       	|
| 1111   	| 17     	| 15      	| F       	|
| 10000  	| 20     	| 16      	| 10      	|
| 10001  	| 21     	| 17      	| 11      	|

# De uma base X para outra Y
 - A conversão sempre precisa ser realizada tendo a base 10 como intermediária, pois ela é a utilizada para efetuar cálculos aritméticos.
 
 - Lógica Booleana
 * Os valores binários seguem a lógica booleana. Nela, dois valores são referidos como verdadeiro e falso, sim e não ou 0 e 1. Não importa a escolha feita para essa referência: seu conceito é o mesmo.*
 