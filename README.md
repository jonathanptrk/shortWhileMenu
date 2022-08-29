# ShortWhileMenu
Versão otimizada do menu feito com o comando While, estudo de estruturas de repetição utilizando o comando while. Crie um menu navegável que repita em quanto o usuário não digitar o número "3".

package aula03.estruturasDeRepeticao;
import java.util.Scanner;

public class WhileExercise {
    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);
        int opcao = 0;
        while(opcao != 3){
            System.out.println("Digite uma opção: ");
            System.out.println("1. Depositar");
            System.out.println("2. Sacar");
            System.out.println("3. Sair");
            opcao = scan.nextByte();
        }
    }
}
