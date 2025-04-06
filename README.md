# DesafioControleFluxo

Este projeto Java implementa um sistema de controle de fluxo que recebe dois parâmetros inteiros via terminal e imprime uma sequência de números incrementados.

## Descrição

O programa lê dois números inteiros do usuário e calcula a diferença entre eles. Em seguida, ele imprime uma sequência de números de 1 até a diferença calculada. Caso o primeiro número seja maior que o segundo, o programa lança uma exceção personalizada `ParametrosInvalidosException`.

## Como Executar

1.  **Pré-requisitos:**
    * Java Development Kit (JDK) instalado.
    * NetBeans IDE (opcional, mas recomendado).

2.  **Compilação e Execução:**

    * **Usando o NetBeans:**
        1.  Abra o projeto no NetBeans.
        2.  Clique com o botão direito no arquivo `Contador.java` e selecione "Run File".
        3.  Siga as instruções no console para inserir os parâmetros.

    * **Usando o terminal:**
        1.  Navegue até o diretório do projeto.
        2.  Compile os arquivos `.java`: `javac Contador.java ParametrosInvalidosException.java`
        3.  Execute o programa: `java Contador`
        4.  Siga as instruções no console para inserir os parâmetros.

## Exemplos de Uso

* **Entrada:**
    ```
    Digite o primeiro parâmetro: 5
    Digite o segundo parâmetro: 13
    ```

    **Saída:**

    ```
    Imprimindo o número 1
    Imprimindo o número 2
    Imprimindo o número 3
    Imprimindo o número 4
    Imprimindo o número 5
    Imprimindo o número 6
    Imprimindo o número 7
    Imprimindo o número 8
    ```

* **Entrada:**

    ```
    Digite o primeiro parâmetro: 15
    Digite o segundo parâmetro: 10
    ```

    **Saída:**

    ```
    O segundo parâmetro deve ser maior que o primeiro
    ```

## Estrutura do Projeto

DesafioControleFluxo/
├── src/
│   ├── Contador.java
│   └── ParametrosInvalidosException.java
└── README.md


## Requisitos

* Java 8 ou superior.

## Contato

Se tiver alguma dúvida, entre em contato comigo.
