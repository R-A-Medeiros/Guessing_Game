# 🎯 Guessing Game

Projeto simples de **adivinhação de números** desenvolvido em **Go**, criado como exercício de aprendizado da linguagem.  
Simple **number guessing game** built with **Go**, created as a learning exercise.

---

## 📖 Descrição / Description

- 🇧🇷 O jogo escolhe um número aleatório dentro de um intervalo definido e o jogador deve tentar adivinhar qual é.  
- 🇺🇸 The game picks a random number within a given range and the player must try to guess it.  

O programa informa se o palpite é **maior** ou **menor** que o número secreto, até que o usuário acerte ou as tentativas acabem.  
The program tells if the guess is **higher** or **lower** than the secret number until the player gets it right or runs out of attempts.

---

## 🚀 Como executar / How to run

Instale o Go (versão recomendada: **1.20+**).  
   Install Go (recommended version: **1.20+**).  
   [Download Go](https://go.dev/dl/)

### Clone este repositório / Clone this repository:

   ```
   git clone https://github.com/R-A-Medeiros/Guessing_Game.git
   ```
### Acesse a pasta / Go into the folder:
  ```
  cd Guessing_Game
  ```
### Execute diretamente / Run directly:
  ````
  go run main.go
  ````
### Ou compile / Or compile:
````
go build -o guessing_game
./guessing_game
````

---
# 🕹️ Exemplo de jogo / Game example

### 🎉 Bem-vindo ao Guessing Game! / Welcome to Guessing Game!
Adivinhe o número entre 1 e 100 / Guess the number between 1 and 100

👉 Seu palpite / Your guess: 50
O número é maior! / The number is higher!

👉 Seu palpite / Your guess: 75
Acertou! 🎯 Parabéns! / Correct! 🎯 Congratulations!

# 📂 Estrutura / Structure
main.go → código principal / main game logic

go.mod → módulo Go / Go module

### 💡 Possíveis melhorias / Possible improvements
Intervalos customizados / Custom ranges

* Níveis de dificuldade / Difficulty levels

* Contagem de tentativas e ranking / Attempts counter and ranking

* Validação de entradas inválidas / Invalid input handling

* Testes automatizados / Automated tests

* Mensagens multilíngues / Multi-language messages

# 🤝 Contribuindo / Contributing

🇧🇷 Contribuições são bem-vindas! Para isso:

🇺🇸 Contributions are welcome! To do so:

Faça um fork / Fork the repo

Crie uma branch / Create a branch: git checkout -b minha-feature / my-feature

Commit suas alterações / Commit your changes

Envie um pull request 🚀 / Open a pull request 🚀

