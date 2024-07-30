public class Main { # type: ignore
    public static void main(String[] args) {
        int numero = 10
        System.out.println("O número é: " + numero);
    }
}
public class Main {
    public static void main(String[] args) {
        int numero = 10; // Correção: Adicionar ponto e vírgula
        System.out.println("O número é: " + numero);
    }
}
import java.util.Scanner;

public class Labirinto {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Escolha uma direção (esquerda/direita): ");
        String direcao = scanner.nextLine();

        if (direcao.equals("esquerda")) {
            System.out.println("Você encontrou um baú!");
        } else if (direcao.equals("direita")) {
            System.out.println("Você caiu em uma armadilha!");
        } else {
            System.out.println("Direção inválida.");
        }

