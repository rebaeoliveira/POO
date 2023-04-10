## Notebook Atv01

<hr>

> Descrever os passos realizados para a resolução da atividade.
  - Argumentos inválidos devem ser desconsiderados sem provocar a exibição de erros ou exceções com a função throws IOException.
  - As variáveis são inicializadas com o valor zero.
  - As variáveis de "a' até "e" recebem os valores.
  - A variável "soma" soma todos os valores das variáveis "a" até "e".

> Inserir o código Java criado para a resolução da atividade. 
import java.util.Scanner;
import java.io.IOException;
public class Atv01 {
public static void main(String[] args) throws IOException {
double a, b, c, d, e, soma = 0;
Scanner s = new Scanner(System.in);
System.out.println("Digite números inteiros ou reais: ");
a = s.nextDouble();
b = s.nextDouble();
c = s.nextDouble();
d = s.nextDouble();
e = s.nextDouble();
soma = a + b + c + d + e;
System.out.println("A soma dos números é: " + soma); // O valor da soma é exibido na tela usando o método System.out.println().
   }
}

<hr>
