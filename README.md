# 🛸 Projeto-Mobile - Space-Invaders
Este projeto é uma recriação do clássico jogo Space Invaders, desenvolvido especificamente para dispositivos móveis utilizando o GameMaker Studio. O jogo mantém a essência do original enquanto adiciona controles otimizados para touchscreen e alguns recursos modernos.

👨‍🏫 Professor responsável
Carlos Eduardo Duque Polito

🎯 Objetivo do projeto
Recriar o clássico jogo Space Invaders com mecânicas modernas e controles otimizados para dispositivos móveis, utilizando o GameMaker Studio 2.

✖️ O que não é planejado para o projeto

Jogo com gráficos 3D complexos

Sistema multiplayer online

Microtransações ou compras dentro do aplicativo

👥 Público-alvo
Jogadores casuais e fãs de jogos retrô que desejam uma experiência nostálgica mas adaptada para smartphones modernos.

🔨 Requisitos funcionais

Sistema de movimento: Controles touch para mover a nave

Sistema de disparo: Botão de tiro intuitivo

Geração de inimigos: Ondas progressivas de aliens

Sistema de pontuação: Contagem de pontos por inimigos derrotados

Menu de pause: Opção para pausar o jogo durante a partida

Seleção de dificuldade: Diferentes níveis de desafio

☑️ Requisitos não funcionais

Desempenho: 60 FPS em dispositivos Android/iOS medianos

Compatibilidade: Funcionar em versões Android 8+ e iOS 12+

Otimização: Consumo de bateria eficiente

Controles: Responsivos e adaptáveis a diferentes tamanhos de tela

📑 Matrizes de Requisitos
(Inserir tabelas específicas para seu projeto aqui)

📱 Mockup do Jogo
(Inserir imagens ou links para protótipos de tela)

📊 Estrutura do Projeto

Copy
/Sprites
  - Player
  - Enemies
  - Bullets
  - Backgrounds
/Scripts
  - Movement
  - Shooting
  - EnemyAI
  - GameManager
/Sounds
  - Effects
  - Music
/Rooms
  - MainMenu
  - GameLevels
  - GameOver
📖 Dicionário de objetos

obj_player: Entidade controlada pelo jogador

Variáveis: lives, speed, fireRate

obj_enemy: Inimigos básicos

Variáveis: health, points, movementPattern

obj_bullet: Projéteis do jogador

Variáveis: speed, damage

obj_gameController: Controla lógica do jogo

Variáveis: score, level, difficulty

🧍 Diagramas UML
(Inserir diagramas específicos para seu jogo)

🛢️ Requisitos Técnicos

Resolução: 1280x720 (adaptável)

Taxa de atualização: 60Hz

Armazenamento: ~50MB (Android/iOS)

API necessárias: Vibrate, Touch Input

🧰 Tecnologias Utilizadas

Desenvolvimento: GameMaker Studio 2

Programação: GML (GameMaker Language)

Arte: Aseprite (pixel art) / Photoshop

Áudio: BFXR (efeitos sonoros)

Versionamento: GitHub

⚠️ Limitações conhecidas

Não suporta tablets muito antigos

Efeitos especiais podem reduzir performance em dispositivos básicos

🛡️ Estratégia de Otimização

Pooling de objetos para balas e inimigos

Spritesheets para animações

Pré-carregamento de assets

Redução de chamadas desnecessárias de draw

💻 Desenvolvedores
[Seu Nome] - Programação e Design
[Outros membros] - [Suas funções]
