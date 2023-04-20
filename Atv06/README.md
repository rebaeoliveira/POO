## Notebook Atv06

<hr>

> Descrever os passos realizados para a resolução da atividade.
  - Dados os valores de um depósito fixo mensal e um montante desejado, crie uma classe para determinar quantos meses serão necessários para acumular o montante desejado,considerando juros mensais de 0,5%.
  - O usuário informa o valor do depósito fixo mensal e valor do montante que deseja acumular.
  - As variáveis "saldoAtual" e "meses" são inicializadas com os valores zero.
  - É considerado juros mensais de 0,5% multiplicando o valor acumulado ao mẽs por 0.005.
  - Ao final é informado a quantidade de meses necessários para acumular o montante desejado.

> Inserir o código Java criado para a resolução da atividade. 
  - import java.util.Scanner;
  - Scanner scanner = new Scanner(System.in);
  - System.out.println("Valor do depósito: ");
  - float depositoFixo = scanner.nextFloat();
  - System.out.println("Valor do montante: ");
  - float saldoDesejado = scanner.nextFloat();        
  - float saldoAtual = 0;
  - int meses = 0;        
  - while (saldoAtual < saldoDesejado) {
  - saldoAtual += depositoFixo;
  - saldoAtual += saldoAtual * 0.005;
  - meses++;
  - }
  - System.out.println("Será preciso " + meses + " meses para chegar ao valor de R$ " + saldoDesejado);      
  - scanner.close();

<hr>
