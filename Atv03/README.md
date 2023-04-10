## Notebook Atv03

<hr>

> Descrever os passos realizados para a resolução da atividade.
  - Importado a função JOptionPane.
  - Código recebe as notas das 1ª e 2ª provas e do trabalho.
  - A média é calculada somando todas as notas e dividindo pela quantidade de notas fornecidas.

> Inserir o código Java criado para a resolução da atividade. 
  - import javax.swing.JOptionPane;
  - public class Atv03 {
  - public static void main(String[] args) {
  - String prova1 = JOptionPane.showInputDialog("Digite a nota da 1ª prova: "); // Recebe a nota da 1ª prova.
  - double nota1 = Double.parseDouble(prova1);
  - String prova2 = JOptionPane.showInputDialog("Digite a nota da 2ª prova:"); // Recebe a nota da 2ª prova.
  - double nota2 = Double.parseDouble(prova2);
  - String trabalho = JOptionPane.showInputDialog("Digite a nota do trabalho:"); // Recebe a nota do trabalho.
  - double notaTrabalho = Double.parseDouble(trabalho);
  - double media = (nota1 + nota2 + notaTrabalho) / 3; // Calcula a média, somando as notas das provas e do trabalho e dividindo pela quantidade de notas.
  - JOptionPane.showMessageDialog(null, "A média é: " + media); // Mostra a média, utilizando o método showMessageDialog da classe JOptionPane.
  - }
  - }
  
<hr>
