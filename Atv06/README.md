## Notebook Atv06

<hr>

> Descrever os passos realizados para a resolução da atividade.
  - Dados os valores de um depósito fixo mensal e um montante desejado, crie uma classe para determinar quantos meses serão necessários para acumular o montante desejado,considerando juros mensais de 0,5%.
  - As variáveis "valorAtual" e "meses" são inicializadas com os valores zero.

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
