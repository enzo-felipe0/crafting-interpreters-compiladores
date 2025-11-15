# jlox - Interpretador da Linguagem Lox

Este projeto é uma implementação de um interpretador para a linguagem de programação Lox, como parte da disciplina de Compiladores. O desenvolvimento é baseado no livro [*Crafting Interpreters*](https://craftinginterpreters.com/) de Robert Nystrom.

## 🚀 Tecnologias e Dependências

*   **Java**.
*   **Maven:** Usado para gerenciamento de dependências e automação do build.

## ⚙️ Como Compilar e Executar

1.  **Clone o repositório:**
    ```
    git clone https://github.com/enzo-felipe0/jlox.git
    cd jlox
    ```

2.  **Compile o projeto com Maven:**
    O comando a seguir irá compilar o código-fonte e empacotar tudo em um arquivo `.jar` executável na pasta `target/`.
    ```
    mvn clean package
    ```

3.  **Execute o interpretador:**
    Você pode executar o interpretador em modo interativo (REPL) ou passando um arquivo de script como argumento.

    *   **Modo Interativo (REPL):**
        ```
        java -jar target/jlox-1.0-SNAPSHOT-jar-with-dependencies.jar
        ```

    *   **Executar um arquivo de script:**
        ```
        java -jar target/jlox-1.0-SNAPSHOT-jar-with-dependencies.jar /caminho/para/seu/script.lox
        ```

## 👨‍💻 Autores

| Nome                                | GitHub                                     |
| ----------------------------------- | ------------------------------------------ |
| Enzo Felipe Prudencio Avelino Lima  | [enzo-felipe0](https://github.com/enzo-felipe0) |
| Francisco Elias da Silva Fernandes  | [Elias66Fernandes](https://github.com/Elias66Fernandes) |

