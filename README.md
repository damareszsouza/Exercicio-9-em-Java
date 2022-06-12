# Exercicio-9-em-Java
# Exercicio Replicado do livro Tutorial de Programação em Java e Orientação a Objetos


class VetorTest {
 public static void main (String args[]) {
 int vetor[] = new int[3];
 vetor[0] = 0; //indexacao semelhante a C , C++
 vetor[1] = 10;
 vetor[2] = 20;
 System.out.println(vetor[0] + " " + vetor[1] + " " + vetor[2] + " "); 
 }
}

Resumo da sintaxe de vetores:
int a[]; //declara vetor de inteiros a
a = new int[10]; //aloca vetor a com dez posicoes
//as duas linhas anteriores podem ser abreviadas por:
int a[] = new int[10]; 
//alem disso se voce quiser inicializar o vetor a, ja’ na declaracao:
int a[3] = {0,10,20};
O análogo para matrizes é:
int a[][]; //declara matriz de inteiros a
a = new int[3][3]; //aloca matriz 3x3, 9 celulas
//as duas linhas anteriores podem ser abreviadas por:
int a[] = new int[3][3];
//alem disso se voce quiser inicializar a matriz a ja na declaracao:
int a[3][3] = {{0,10,20},{30,40,50},{60,70,80}};
Em métodos, argumentos e valores de retorno
