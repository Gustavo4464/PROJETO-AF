# PROJETO-AF 
# ✔ Projeto Calculadora – Refatoração e Documentação

Este projeto implementa uma calculadora simples em Java,
com operações matemáticas básicas e tratamento de exceções.

## 📌 Estrutura
- Métodos isolados para cada operação
- Classe de testes separada
- Tratamento de exceções
- Documentação JavaDoc incluída

---

## 🧪 Testes no Terminal

### Resultado da execução:

<img width="589" height="155" alt="image" src="https://github.com/user-attachments/assets/4cf72596-f8d2-447a-9714-d898439b1537" />

---

## 📚 Documentação JavaDoc

*Package calculadora*

Class Calculadora
java.lang.Object
  ↳ calculadora.Calculadora

Descrição

Classe responsável por realizar operações matemáticas básicas.
Suporta soma, subtração, multiplicação e divisão.
Em caso de erro, lança exceções tratadas pela classe de teste.

Métodos
public int calcular(int a, int b, String op)

Descrição:
Executa a operação matemática indicada pelo operador.

Parâmetros:

a – primeiro número

b – segundo número

op – operador matemático (+, -, *, /)

Retorno:

valor da operação realizada

Exceções:

IllegalArgumentException – operador inválido

ArithmeticException – divisão por zero

public int soma(int a, int b)

Retorna a soma entre dois números.

public int subtracao(int a, int b)

Retorna a subtração entre dois números.

public int multiplicacao(int a, int b)

Retorna a multiplicação entre dois números.

public int divisao(int a, int b)

Retorna a divisão entre dois números.
Lança exceção caso o divisor seja zero.



Class TesteCalculadora
java.lang.Object
  ↳ calculadora.TesteCalculadora

Descrição

Classe utilizada para testar a classe Calculadora.
Executa todas as operações válidas e testa as exceções, exibindo os resultados no terminal.

Métodos
public static void main(String[] args)

Método principal da aplicação.
Executa:

soma

subtração

multiplicação

divisão

teste de operador inválido

teste de divisão por zero

Exibe mensagens em caso de erro.




JAVADOC


✔ Classe Calculadora

Realiza operações matemáticas básicas

Métodos isolados

Tratamento de exceções

Documentação em padrão JavaDoc

Principais métodos:

Método	Descrição
calcular(int a, int b, String op)	Executa a operação indicada (+, -, *, /)
soma(int a, int b)	Realiza soma
subtracao(int a, int b)	Realiza subtração
multiplicacao(int a, int b)	Realiza multiplicação
divisao(int a, int b)	Realiza divisão com tratamento de divisão por zero
✔ Classe TesteCalculadora

Executa todos os testes da Calculadora

Garante que exceções são tratadas corretamente

main(String[] args)
Executa todas as operações e imprime o resultado no terminal.

✔ Estrutura final do JavaDoc 
docs/
 ├── index.html
 ├── calculadora/
 │     ├── Calculadora.html
 │     └── TesteCalculadora.html
 └── stylesheet.css
