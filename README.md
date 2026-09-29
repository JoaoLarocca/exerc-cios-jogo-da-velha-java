# Jogo da Velha em Java ❌⭕

Implementação do clássico **Jogo da Velha (Tic-Tac-Toe)** em Java, jogado no terminal contra o **computador**.

---

## 🎮 Como funciona

- O tabuleiro é representado por uma **matriz 3x3** de inteiros.
- O **jogador humano** usa `X` (valor `1`).
- O **computador** usa `O` (valor `0`).
- Casas vazias são representadas por `-1`.
- O jogador escolhe uma posição de **1 a 9** (como um teclado numérico):

  ```
   1 | 2 | 3
  ---+---+---
   4 | 5 | 6
  ---+---+---
   7 | 8 | 9
  ```

- O computador joga em uma posição **aleatória** disponível.
- O jogo termina quando alguém vence ou todas as casas são preenchidas (**empate**).

---

## 🧠 Conceitos praticados

- Matrizes bidimensionais (`int[][]`)
- Estruturas de repetição (`while`, `for`) e condicionais (`if/else`)
- Validação de entrada do usuário
- Modularização com métodos estáticos (`imprimirTabuleiro`, `verificarVitoria`, `verificarEmpate`)
- Uso das classes `Scanner` e `Random`

---

## 🛠️ Tecnologias

- **Linguagem:** Java 21
- **Build:** Maven
- **IDE:** NetBeans
- **Execução:** Terminal (linha de comando)

---

## 📂 Estrutura do Projeto

```
Jogo_Velha/
 ┣ 📂 src/
 ┃ ┗ 📂 main/
 ┃   ┗ 📂 java/
 ┃     ┗ 📂 com/mycompany/jogo_velha/
 ┃       ┗ 📄 Jogo_Velha.java
 ┗ 📄 pom.xml
```

---

## ▶️ Como executar

### Pelo NetBeans
1. `File → Open Project` e selecione a pasta do projeto.
2. Rode com **Run Project** (`F6`).

### Pelo terminal (Maven)
```bash
git clone https://github.com/seu-usuario/Jogo_Velha.git
cd Jogo_Velha
mvn compile exec:java
```

### Compilando manualmente
```bash
cd src/main/java
javac com/mycompany/jogo_velha/Jogo_Velha.java
java com.mycompany.jogo_velha.Jogo_Velha
```

---

## 🖥️ Exemplo de partida

```
Escolha uma posicao de 1 a 9:
5
   |   |
---+---+---
   | X |
---+---+---
   |   |

Computador jogou!
   |   | O
---+---+---
   | X |
---+---+---
   |   |
```

---

## 👤 Autor

Desenvolvido como parte das atividades de prática e retomada de conteúdo em Java.

---

## 📄 Licença

Este projeto é destinado a fins **educacionais**.
