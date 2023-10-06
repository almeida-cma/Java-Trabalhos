Vamos descrever didaticamente o funcionamento deste código Java:

Nome da Classe:
App1Loop - é o nome da classe onde o código está inserido.

Funcionalidade Principal:
Apresentar um menu para o usuário com as opções: inserir notas, calcular média e sair. 
O programa aguardará uma entrada do usuário (um número que representa uma das opções) e executará a ação correspondente.

Detalhamento:

1)Importação da Biblioteca:
import java.util.Scanner; //Estamos importando a classe Scanner do pacote java.util, que é uma ferramenta para ler a entrada do usuário.

2) Início da Classe:
public class App1Loop { //Declaração da classe App1Loop.

3) Método Principal:
public static void main(String[] args) { //Este é o ponto de entrada do programa. Quando executamos a classe, este método é chamado.

4) Criação do Scanner:
Scanner sc = new Scanner(System.in); //Criamos um objeto 'sc' da classe Scanner para ler a entrada do usuário.

5) Loop Infinito:
while (true) { //Aqui começamos um loop que irá se repetir indefinidamente, mostrando o menu para o usuário até que ele escolha sair.

6) Menu:
System.out.println(...)  //Estas linhas mostram as opções do menu para o usuário.

7) Leitura da Opção:
int opcao = sc.nextInt(); //O programa aguarda o usuário digitar um número (opção) e armazena na variável 'opcao'.

8) Switch Case:
switch (opcao) { ... } (Dependendo do número digitado pelo usuário, o programa entrará em um dos casos (case) do switch:
case 1: Se o usuário digitar 1, o programa imprimirá "Inserir notas".
case 2: Se o usuário digitar 2, imprimirá "Calcular média".
case 3: Se o usuário digitar 3, o programa imprimirá "Até logo!" e encerrará a execução com o comando return;.
default: Se o usuário digitar qualquer outro número que não seja 1, 2 ou 3, o programa imprimirá "Opção inválida!".

Em resumo, este programa mostra um menu simples ao usuário, aguarda uma entrada numérica e, em seguida, 
realiza uma ação (no momento, apenas impressões na tela) com base na opção escolhida. 
A única forma de encerrar o programa é escolhendo a opção 3.
-------------------------------------------------------------------------------------------------------------------------------------------

O código de App2Matriz é uma implementação simples em Java que lida com uma matriz 2x2 e realiza algumas operações com ela. 
Vamos detalhar seu funcionamento de forma didática:

Nome da Classe:
App2Matriz - é o nome da classe onde o código está inserido.

Funcionalidade Principal:
Permite ao usuário inserir valores para uma matriz 2x2, exibe essa matriz e, finalmente, calcula e exibe a média dos valores de cada linha da matriz.

Detalhamento:

1) Importação da Biblioteca:
import java.util.Scanner; //Importa a classe Scanner do pacote java.util, utilizada para ler as entradas do usuário.

2) Início da Classe:
public class App2Matriz { //Declaração da classe App2Matriz.

3) Método Principal:
public static void main(String[] args) { //Este é o ponto de entrada do programa.

4) Criação do Scanner:
Scanner sc = new Scanner(System.in); //Cria um objeto 'sc' da classe Scanner para ler as entradas do usuário.

5) Declaração da Matriz:
double[][] matriz = new double[2][2]; //Declara e inicializa uma matriz 2x2 de números decimais (double).

6) Preenchendo a Matriz:
Há dois loops for aninhados que percorrem a matriz, permitindo ao usuário inserir um valor em cada posição [i][j] da matriz.
Para cada posição, o programa imprime uma mensagem solicitando ao usuário que digite o valor para aquela posição específica e, 
em seguida, lê esse valor e armazena na matriz.

7) Exibindo a Matriz:
Outros dois loops for aninhados são usados para percorrer a matriz e imprimir cada um de seus valores, 
separando os elementos de uma mesma linha por " | " e mudando de linha após imprimir todos os elementos de uma linha.

8) Calculando e Exibindo a Média das Linhas:
Um loop for percorre as linhas da matriz e, para cada linha, calcula a média dos seus dois valores. 
Depois, o programa exibe essa média, indicando a qual linha ela pertence.

Em resumo, o programa App2Matriz permite ao usuário inserir valores para uma matriz 2x2, 
exibe essa matriz formatada e, finalmente, calcula e mostra a média dos valores de cada linha dessa matriz.
------------------------------------------------------------------------------------------------------------
