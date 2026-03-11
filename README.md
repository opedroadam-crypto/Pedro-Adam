# Exercícios de Programação em Java
import java.util.Scanner;

public class Uni3Exe02 {

    // Analise: calcular o desconto de 12% em um par de sapatos
    // Entrada: preco do par de sapatos
    // Saida: valor do desconto e preco final com desconto
    // Processo: desconto = preco * 0.12
    //           precoFinal = preco - desconto
    // Fluxograma: ler preco, calcular desconto, calcular precoFinal, mostrar desconto e precoFinal

    public static void main(String[] args) {

        Scanner leitor = new Scanner(System.in);

        double preco;
        double desconto;
        double precoFinal;

        System.out.println("Digite o preco do par de sapatos:");
        preco = leitor.nextDouble();

        desconto = preco * 0.12;
        precoFinal = preco - desconto;

        System.out.println("O valor do desconto é de R$" + desconto);
        System.out.println("O preço do par de sapatos com desconto é R$" + precoFinal);

        leitor.close();
    }
}

Este repositório contém um exercício desenvolvido durante as aulas da disciplina de programação.

## Objetivo

Praticar conceitos básicos de programação, lógica e desenvolvimento utilizando a linguagem Java.

## Conteúdo

- Cálculos simples
- Entrada e saída de dados
- Estruturas básicas da linguagem



Pedro Adam  
Estudante de Ciência da Computação - FURB
