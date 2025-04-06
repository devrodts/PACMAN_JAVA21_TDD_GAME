pacman-java-21/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── pacman/
│   │   │   │   │   ├── Main.java                    # Ponto de entrada da aplicação
│   │   │   │   │   ├── GameLoop.java                # Loop principal do jogo
│   │   │   │   │   ├── GamePanel.java               # Painel de renderização do jogo
│   │   │   │   │   │
│   │   │   │   │   ├── model/                       # Pacote para classes de modelo
│   │   │   │   │   │   ├── Direction.java           # Enum para direções
│   │   │   │   │   │   ├── Position.java            # Classe para posições no labirinto
│   │   │   │   │   │   ├── Tile.java                # Enum para tipos de células do labirinto
│   │   │   │   │   │   ├── Level.java               # Classe para representar um nível
│   │   │   │   │   │   │
│   │   │   │   │   ├── entity/                      # Pacote para entidades do jogo
│   │   │   │   │   │   ├── Entity.java              # Classe base para entidades
│   │   │   │   │   │   ├── MovableEntity.java       # Classe base para entidades móveis
│   │   │   │   │   │   ├── Pacman.java              # Classe para o jogador Pacman
│   │   │   │   │   │   ├── Ghost.java               # Classe base para fantasmas
│   │   │   │   │   │   ├── Blinky.java              # Implementação do fantasma vermelho
│   │   │   │   │   │   ├── Pinky.java               # Implementação do fantasma rosa
│   │   │   │   │   │   ├── Inky.java                # Implementação do fantasma azul
│   │   │   │   │   │   ├── Clyde.java               # Implementação do fantasma laranja
│   │   │   │   │   │   ├── Fruit.java               # Classe para frutas/itens especiais
│   │   │   │   │   │   │
│   │   │   │   │   ├── maze/                        # Pacote para o labirinto
│   │   │   │   │   │   ├── Maze.java                # Classe do labirinto
│   │   │   │   │   │   ├── MazeLoader.java          # Carregador de labirintos de arquivos
│   │   │   │   │   │   │
│   │   │   │   │   ├── util/                        # Pacote para utilitários
│   │   │   │   │   │   ├── SpriteLoader.java        # Carregador de sprites
│   │   │   │   │   │   ├── SoundPlayer.java         # Reprodutor de sons
│   │   │   │   │   │   ├── ScoreManager.java        # Gerenciador de pontuação
│   │   │   │   │   │   │
│   │   │   │   │   ├── state/                       # Pacote para estados do jogo
│   │   │   │   │   │   ├── GameState.java           # Interface para estados do jogo
│   │   │   │   │   │   ├── PlayingState.java        # Estado de jogo ativo
│   │   │   │   │   │   ├── MenuState.java           # Estado de menu
│   │   │   │   │   │   ├── GameOverState.java       # Estado de fim de jogo
│   │   │   │   │   │   ├── StateManager.java        # Gerenciador de estados
│   │   │   │   │   │
│   │   ├── resources/                               # Recursos do jogo
│   │   │   ├── sprites/                             # Sprites do jogo
│   │   │   │   ├── pacman.png
│   │   │   │   ├── ghost_blinky.png
│   │   │   │   ├── ghost_pinky.png
│   │   │   │   ├── ghost_inky.png
│   │   │   │   ├── ghost_clyde.png
│   │   │   │   ├── walls.png
│   │   │   │   ├── dots.png
│   │   │   │   ├── power_pellet.png
│   │   │   │   ├── fruits.png
│   │   │   │
│   │   │   ├── sounds/                              # Sons do jogo
│   │   │   │   ├── start.wav
│   │   │   │   ├── munch.wav
│   │   │   │   ├── death.wav
│   │   │   │   ├── eat_ghost.wav
│   │   │   │   ├── eat_fruit.wav
│   │   │   │   ├── power_pellet.wav
│   │   │   │
│   │   │   ├── levels/                              # Arquivos de níveis
│   │   │   │   ├── level1.txt
│   │   │   │   ├── level2.txt
│   │   │   │
│   ├── test/                                        # Testes unitários
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── pacman/
│   │   │   │   │   ├── entity/
│   │   │   │   │   │   ├── PacmanTest.java
│   │   │   │   │   │   ├── GhostTest.java
│   │   │   │   │   ├── maze/
│   │   │   │   │   │   ├── MazeTest.java
│   │   │   │   │   ├── util/
│   │   │   │   │   │   ├── ScoreManagerTest.java
│
├── pom.xml                                          # Arquivo de configuração Maven
├── README.md                                        # Documentação do projeto