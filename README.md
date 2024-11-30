# Paper-Slash
![Menu do Jogo](Paper-Slash-Menu.jpeg)

**Link da Demo do Jogo no Youtube**: https://youtu.be/BTOfhvGqPmI

**Link de Dowload do Jogo via Mediafire**: https://www.mediafire.com/folder/97ynwcs3gdaxe/Paper-Slash

  **Obs**: O arquivo do jogo ficou muito grande para o github e então foi feito upload no mediafire. Baixe cada um dos arquivos e coloque em uma pasta. Inicie o jogo clicando duas vezes no executável.

## 🍁 Sobre o repositório
Este repositório contém a documentação e demonstração do jogo criado na disciplina de Computabilidade e Complexidade de Algoritmos - Centro Universitário do Distrito Federal, durante o 6° semestre.

## 👥 Participantes
- 👩‍🏫 Prof. Kadidja Valéria
- 👤 Lucas Albuquerque 
- 👤 Saulo Silva 
- 👤 Pedro Mateus 
- 👤 João Marcos
- 👤 Lucio Roberto 

## 📰 Sobre o Jogo
 **Paper Slash**: é um jogo em perspectiva 2D em que o jogador controla um papel que usa uma espada para eliminar outros papéis. Existe, no jogo, um sistema de pontuação baseado na quantidade de inimigos derrotados dentro do tempo limite que é de 5 minutos. Ao finalizar uma tentativa, o jogador será colocado no sistema de ranking do jogo e conseguir uma boa posição é a forma mais clara de vitória.
 
 ![Dentro do Jogo](Game-Image.jpeg)

## 💡 Inspiração
Foram utilizados como inspiração alguns jogos em universo 2D e com características de Hack and Slash.

 **Dead Cells**: jogo eletrônico roguelike-metroidvania desenvolvido e publicado pela Motion Twin.

 **Hollow Knight**: jogo indie de gênero metroidvania desenvolvido e publicado pela Team Cherry.

 **Diep.io**: jogo multijogador massivo online em que o jogador controla um tanque em movimento em torno de uma superfície plana que representa um campo de batalha preenchido com vários polígonos.

## ⚙️ Tecnologias
 **Game Maker Studio**: é uma engine de criação de jogos 2D de fácil uso e aprendizado e suporta plataformas como Windows, Mac, Linux, Android, iOS e HTML5.
 
 **Game Maker Language(GML)**: é uma linguagem de programação utilizada pelo Game Maker Studio.

 **Protocolo HTTP**: Para o sistema de pontuação e ranking foi utilizado servidores de conexão em protocolo HTTP. Cada pessoa pode baixar o jogo em sua própria máquina e a pontuação será atualizada via internet no ranking global.

 **Efeitos Visuais**: Na parte gráfica do jogo foi utilizado um efeito de luz para ambientação. Essa configuração dificultou a jogabilidade em computadores menos potentes. Para solucionar esse problema foi criado uma configuração gráfica sem esse efeito de luz, possibilitando a execução do jogo em máquinas mais fracas. As duas opções gráficas estão dentro do jogo.

## ♾️ Complexidade
 **Pontuação**: pontos são adquiridos ao derrotar inimigos. Os pontos adquiridos são proporcinais à dificuldade do inimigo.
 
 **Tempo**: a partir de um tempo limite e do sistema de pontos, o jogo desafia o jogador a conseguir a maior quantidade de pontos.

 **Stamina**: existe uma mecânica de fôlego que consiste em dar um limite para as ações do jogador. Há uma quantidade específica de fôlego e todas as ações do jogador, exceto andar, gastam esse recurso. Depois de um pequeno tempo sem executar nenhuma dessa ações, a quantidade de fôlego é recuperada lentamente.

 **Vida**: ganhar ou perder depende da vida. Cada entidade do jogo possui uma quantidade diferente de vida e não foi implementada uma forma de recuperá-la, tornando-a o recurso mais importante do jogo. Os ataques diminuem a quantidade de vida das entidades (jogador e inimigos).

## 🎮 Jogabilidade
 **Movimentação**: o jogo é em perspectiva 2D com uma visão de cima. O jogador se mexe utilizando as teclas (W, A, S, D) e pode correr seguranto a tecla (SHIFT). Além disso, o jogador pode dar um dash (um movimento rápido para avançar ou escapar de um inimigo) utilizando a barra de (Espaço).
 
 **Ações**: o jogador mira os seus ataques usando o mouse e o botão esquerdo para efetuar o ataque. 


## 📝 CheckList


**Fase 1: Análise**
- [ Lucas ] Problema selecionado e definido claramente.
- [ Saulo ] Compreensão aprofundada da natureza e desafios do problema.
- [ Lucio ] Objetivos do algoritmo definidos com clareza.

**Fase 2: Planejamento** 
- [ Lucio e Lucas ] Game estilo' Hack and slash
- [ Lucio ] Escolha da IDE Game Maker Studio.
- [ Lucas ] Desenvolvimento do game na IDE.
- [ Lucas ] Estrutura geral do algoritmo esboçada.

**Fase 3: Programação e Testes**
- [ Pedro ] Algoritmo traduzido com precisão.
- [ Lucas ] Código de programação escrito de forma clara e organizada.
- [ Lucas ] Testes rigorosos realizados em uma variedade de casos de teste.
- [ Lucas e Lucio ] Casos limite e situações especiais testados.
- [ João ] Erros e problemas durante o teste de programa identificados e corrigidos.

**Fase 4: Documentação e Avaliação do Projeto** 
- [ João e Pedro ] Documentação completa, incluindo especificação do algoritmo e análise de complexidade.
- [ João e Pedro ] Documentação revisada para clareza e rigor técnico.
- [ Saulo ] Avaliação da eficácia do algoritmo em termos de tempo de execução, uso de recursos e precisão na resolução do problema.
- [ Pedro ] Avaliação da colaboração da equipe e cumprimento dos prazos.



