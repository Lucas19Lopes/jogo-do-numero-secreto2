# 🎯 Jogo do Número Secreto  

Este é um jogo interativo desenvolvido como parte do **curso para iniciantes em programação da Alura**.  
O objetivo é simples: o jogador deve adivinhar o número secreto gerado aleatoriamente pelo sistema.  

## 📜 Como funciona  
- O sistema gera um número secreto entre **1 e 10**.  
- O jogador insere um palpite e recebe dicas se o número secreto é **maior** ou **menor**.  
- Ao acertar, o jogo informa o número de tentativas usadas.  
- É possível iniciar um **novo jogo** sem recarregar a página.  
- O jogo também conta com **leitura por voz** (via Web Speech API) para tornar a experiência mais interativa.  

## 🛠 Tecnologias utilizadas  
- **HTML5** → Estrutura da página.  
- **CSS3** → Estilização e responsividade.  
- **JavaScript** → Lógica do jogo, geração de números aleatórios e interações dinâmicas.  
- **Web Speech API** → Reprodução de mensagens por voz.  

## 📂 Estrutura do código  
- **index.html** → Estrutura principal da página, incluindo campos de entrada, botões e imagem ilustrativa.  
- **style.css** → Estilo visual do jogo, com design responsivo e elementos posicionados para melhor experiência.  
- **app.js** → Lógica do jogo, incluindo:  
  - `gerarNumeroAleatorio()` → Gera números aleatórios sem repetição até o limite.  
  - `verificarChute()` → Verifica o palpite do jogador e fornece feedback.  
  - `exibirTextoNaTela()` → Atualiza mensagens e utiliza voz para narrar o texto.  
  - `reiniciarJogo()` → Reseta o jogo para uma nova rodada.  

## 🚀 Como executar  
1. Baixe ou clone este repositório:  
   ```bash
   git clone https://github.com/Lucas19Lopes/jogo-do-numero-secreto2.git

   ## 🎮 Demonstração online

Você pode jogar diretamente acessando:  
👉 **[Clique aqui para jogar]()**
