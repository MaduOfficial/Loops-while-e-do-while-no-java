# Loops-while-e-do-while-no-java

Anotações dos Loops while e do-while no java


                                                                 Loops while e do-while
Agenda

.Controle while
.Controle do-while

While que isso seria o enquanto alguma condição for verdadeira execute algum código ou o do-while que é bem parecido com o while mas é um pouquinho
diferente.

                                                                      Comando While

.Esse comando avalia uma expressão e caso verdadeira executa o bloco dentro do comando while.

Exemplo:

package com.madu.Loops.While;

public class LoopWhile {

	public static void main(String[] args) {
		
		int i = 1; //count ou cont
		int max = 10;
		
		System.out.println("Contando até " + max);
		
		while (i <= max) {
			System.out.println("Valor de i: " + i);
			i++; //i = i + 1; ou i += 1;


Console:
Contando até 10
Valor de i: 1
Valor de i: 2
Valor de i: 3
Valor de i: 4
Valor de i: 5
Valor de i: 6
Valor de i: 7
Valor de i: 8
Valor de i: 9
Valor de i: 10
11


Nas linguagens de programação é muito comum a gente útilizar o i como contador, então a variável i ela é muito útilizada pra gente fazer contagem
ou você pode criar uma variável chamada country ou uma variável chamada count que seria no inglês ou o cont no português.

                                                                     Comando do-while

.Esse comando executa o bloco dentro do comando do e depois avalia a expressão. D bloco deixa de ser executado após a expressão ficar falsa.

Exemplo:

package com.madu.Loops.While;

public class LoopWhile {

	public static void main(String[] args) {
		
		int i = 1; //count ou cont
		int max = 10;
		
		System.out.println("Contando até " + max);
		
		while (i <= max) {
			System.out.println("Valor de i: " + i);
			i++; //i = i + 1; ou i += 1;
		}
		
		System.out.println(i); //valor de 11
		
		do {
			i++;
			System.out.println("Valor de i: " + i);
		} while (i < 13);
		
		System.out.println(i);
	}

}


Console:
Contando at? 10
Valor de i: 1
Valor de i: 2
Valor de i: 3
Valor de i: 4
Valor de i: 5
Valor de i: 6
Valor de i: 7
Valor de i: 8
Valor de i: 9
Valor de i: 10
11
Valor de i: 12
Valor de i: 13
13
