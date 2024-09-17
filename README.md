import java.util.Locale;
import java.util.Scanner;

public class ContaBanco {
    public static void main(String[] args) {
        //TODO:Conhecer e importar a classe Scanner
        Scanner scanner = new Scanner(System.in).useLocale(Locale.US);

        System.out.println("Digite seu nome");
        String nome = scanner.next();

        System.out.println("Digite seu sobrenome");
        String sobrenome = scanner.next();

        System.out.println("Digite a agencia");
        String agencia = scanner.next();

        System.out.println("Digite sua conta");
        int conta = scanner.nextInt();

        System.out.println("Saldo disponivel");
        double saldo = scanner.nextDouble();

        //imprimindo os dados obtidos pelo usuário
        System.out.println("Olá obrigado por criar uma conta em nosso banco" + nome + " " + sobrenome);
        System.out.println("Sua agencia é" + agencia);
        System.out.println("Conta" + conta);
        System.out.println("Seu saldo já está disponivel para saqueEverton" + saldo);
        //Exibir as mensagens para o nosso usuário

        //Obter pela scanner os valores digitados no terminal

        //Exibir a mensagem conta criada


    }

}
