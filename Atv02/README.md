## Notebook Atv02

<hr>

> Descrever os passos realizados para a resolução da atividade.
  - Utiliza System.out.print() em vez de System.out.println() para manter o cursor na mesma linha.
  - Atribui o produto de b e c para a variável a utilizando o operador *.
  - Programa executa um cálculo de exemplo de folha de pagamento.

> Inserir o código Java criado para a resolução da atividade. 
  - import java.util.Scanner;
  - public class Atv02 {
  - public static void main(String[] args) {
  - System.out.print("Informe um inteiro: "); // Utiliza System.out.print() em vez de System.out.println() para manter o cursor na mesma linha.
  - int b, c, a = 0;
  - Scanner s = new Scanner(System.in);
  - b = s.nextInt();
  - c = s.nextInt();
  - a = b * c; // Atribui o produto de b e c para a variável a utilizando o operador *.        
  - System.out.println("O produto de b e c é: " + a);
  - }
  - }

<hr>
