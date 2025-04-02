# Sudoku - Java 

## 📜 Descrição
Este projeto implementa um jogo de tabuleiro no estilo Sudoku, desenvolvido em Java, como parte de um desafio da **DIO - BRADESCO CLOUD NATIVE**. O jogo é exibido exclusivamente no terminal, sem interface gráfica, visando a aprendizagem de desenvolvimento _backend_ em Java. Ele fornece funcionalidades para criação e gerenciamento de jogos, permitindo que os jogadores insiram e removam valores, verifiquem erros e o status atual do jogo, e muito mais.

## ⚙️ Estrutura do Projeto
O projeto está dividido em pacotes para facilitar o gerenciamento das responsabilidades:

### Pacote `br.com.dio`
- **Classe `Main`**: Ponto de entrada do programa. Gerencia o fluxo do jogo e fornece um menu interativo para o usuário.

### Pacote `br.com.dio.model`
- **Classe `Board`**: Representa o tabuleiro do jogo e encapsula a lógica de controle do jogo, como validação, mudança de valores e reinício.
- **Classe `Space`**: Representa cada espaço no tabuleiro, incluindo propriedades como valor atual, valor esperado e se é fixo ou não.
- **Enum `GameStatusEnum`**: Enumeração que define os possíveis estados do jogo: **não iniciado**, **incompleto** e **completo**.

### Pacote `br.com.dio.util`
- **Classe `BoardTemplate`**: Define um modelo visual do tabuleiro, usado para exibir o estado atual do jogo no console.

## 🎮 Funcionalidades
- **Início do jogo**: Criação de um novo tabuleiro a partir de configurações pré-definidas.
- **Inserção de números**: Possibilidade de adicionar valores em posições específicas, respeitando as regras do jogo.
- **Remoção de números**: Capacidade de limpar valores, exceto os fixos.
- **Visualização do tabuleiro**: Exibe o estado atual do jogo em um formato visual atraente.
- **Verificação de status**: Avalia se o jogo está completo, incompleto ou contém erros.
- **Limpar o tabuleiro**: Reinicia o jogo, apagando todo progresso não fixo.
- **Finalização do jogo**: Verifica se o tabuleiro foi preenchido corretamente para concluir o jogo.

## 💻 Tecnologias Utilizadas
- **Java**: Linguagem de programação para implementação do projeto.
- **Java Collections e Streams**: Para manipulação eficiente de listas e objetos.
- **Scanner**: Para interação com o usuário via terminal.
- **Programação Orientada a Objetos (POO)**: Design modular e organizado.

## 🚀 Como Executar
1. Certifique-se de ter o [Java JDK](https://www.java.com/pt-BR/) instalado.
2. Clone este repositório:
   ```bash
   git clone https://github.com/PatrickyLucas/sudoku-dio.git
   ```
3. Acesse a pasta do projeto:
   ```bash
   cd sudoku-dio
   ```
4. Compile o código-fonte:
   ```bash
   javac -d bin src/br/com/dio/**/*.java
   ```
5. Execute o jogo:
   ```bash
   java -cp bin br.com.dio.Main
   ```

## 🏆 Contribuição
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Basta abrir uma _issue_ ou enviar um _pull request_! 🎯


---
🎲 Divirta-se jogando Sudoku! 🚀
