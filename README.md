/*# README.md
PODERIAM ME PASSAR COMO FAZ O DESAFIO UM, DOIS E TRÊS POR FAVOR, AGRADECIDO :)
Desafio 01
Dado uma palavra qualquer p, construa um algoritmo que calcule a pontuação da palavra de acordo com a pontuação informada na tabela abaixo:
Por exemplo, se a palavra “desafio” for digitada, a pontuação esperada será 11:
D E S A F I O
2+1+1+1+4+1+1= 11
*/
//aperta f6, e tecle a letra D, o resultado vai ser 1 1
 /*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package atividade1;

import java.util.Scanner;

/**
 *
 * @author SeuTosé(Xendrio)
 */
public class Atividade1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int D = 1;
        int r = 0;
        Scanner teclado = new Scanner (System.in);
        System.out.println("Escreva uma letra maiúscula: ");
        String letra = teclado.nextLine();
        String toString = Integer.toString(D);
        System.out.println(D);
    }
}
