# dio-trilha-java-basico
import java.util.Scanner;

public class Desafio {
    public static void main(String[] args){
        
        Scanner sc = new Scanner(System.in);

        System.out.println("Digite o número da Conta: ");
        int conta = sc.nextInt();

        System.out.println("Digite o número da Agencia: ");
        String agencia = sc.next();
        
        System.out.println("Digite o seu Nome: ");
        String nome = sc.next();
        
        double saldo = 237.48;
        
        System.out.println("\nOlá " + nome + ", obrigado por criar uma conta em nosso banco.");
        System.out.println("Sua agência é " + agencia + ", conta " + conta + " e seu saldo R$ " + saldo + " já está disponível para saque.");

        sc.close();
    }
}
