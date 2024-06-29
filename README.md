
# Jogo do Número Secreto 🎮

Este é um simples jogo em JavaScript onde você deve tentar adivinhar um número secreto entre 1 e 10.

### Funcionalidades do Jogo:

- Número Secreto: Um número aleatório é escolhido pelo computador entre 1 e 10.
- Tentativas: Você tem múltiplas chances para adivinhar o número correto.
- Feedback: Após cada tentativa, o jogo informa se o número secreto é maior ou menor que o seu chute.
- Finalização: Quando você acerta o número secreto, o jogo exibe quantas tentativas foram necessárias para descobrir.
- Reiniciar: Após acertar, você pode reiniciar o jogo para jogar novamente.
### Como Jogar:
- Escolha um Número: Insira um número entre 1 e 10 no campo de entrada.
- Verifique o Chute: Clique no botão para verificar se acertou o número secreto.
- Feedback: O jogo indicará se o número secreto é maior ou menor que o seu chute.
- Continue Tentando: Repita os passos 1 a 3 até acertar o número secreto.
- Reinicie: Após acertar, clique no botão "Reiniciar" para jogar novamente.
### Tecnologias Utilizadas:
- JavaScript
- HTML
- CSS 




#### Detalhes Técnicos
- A função gerarNumeroAleatorio() é utilizada para escolher o número secreto inicial de forma aleatória.
- A função verificarChute() compara o número inserido pelo jogador com o número secreto e fornece feedback adequado.
- A função reiniciarJogo() permite iniciar um novo jogo, gerando um novo número secreto e reiniciando as tentativas.


### Obs:
Este jogo faz uso da API responsiveVoice para sintetizar voz em português brasileiro, dando feedback sonoro conforme o jogo progride.
