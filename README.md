# Exercicio9-
Exercicio9 

package exercicios;

import java.util.Scanner;

//Escreva um algoritmo para ler salario mensal atual de um funcionario e o percentual de reajuste 
//calcular e escrever o valor do novo salario

public class Exercicio9 {

	public static void main(String[] args) {
		Scanner scanner = new Scanner (System.in);
		
		//float salarioMensal;
		
		System.out.println("Digite seu salario mensal atual : R$  ");
		float salario = scanner.nextFloat();
		
		System.out.println("Digite a porcentagem de reajuste do salario :  ");
		float porcentagem = scanner.nextFloat();
		
		float aumentoReal= salario*porcentagem/100;
		float salarioFinal= aumentoReal+salario;
		
		System.out.println("O valor do novo salario e : R$ " + salarioFinal);
		

	}

}
