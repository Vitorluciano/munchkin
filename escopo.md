# Descrição do Escopo do Sistema

- o menu inicial do sistema deve conter a seguintes opções:
    - "iniciar partida"
    - "regras"
    - "sair do jogo"

- as regras e mecânicas do jogo serão as mesmas da versão digital

## Regras:

### visão geral:
    - criação de personagem:
        - começar com raça humano nível 1
        - começar sem classes
        - homem ou mulher
        
        - início da partida:
            - um jogador é escolhido aleatóriamente para ser o inicial
            - antes do 1° turno do jogador inicial todos os jogadores podem jogar cartas de raça, classe e item.

### objetivo do jogo:
    - ganha quem alcaçar o nível 10 primeiro
    - nível 10 só pode ser alcançado matando um monstro a menos que uma carta diga o contrário

### o turno é divido em fases:
    - fase I: abrir a porta
        - compre uma carta do deck da porta e vire-a para cima.
            - se for um monstro, enfrente-o
            - se for uma maldição, ela é aplicada ao jogador e é descartada. (a menos que o efeito da carta diga o contrário)
            - se for outro tipo de carta o jogador pode guardar na sua mão ou jogá-la imediatamente
    - fase II: arrumar encrenca/pilhar a sala
        - se o jogador enfrentou um monstro na fase I ele deve pular essa fase.
        - senão, o jogador deve escolher exclusivamente uma das seguintes opções:
            - arrumar encreca: o jogador enfrenta um monstro disponível em sua mão
            - pilhar a sala: o jogador deve comprar uma carta do deck da porta e guardar em sua mão
    - fase III: caridade
        - se o jogador tiver mais de 5 cartas em mãos ao finalizar o seu turno ele deverá doar as cartas excedentes para o jogador com o menor nível ou então deve jogá-las.

### quando ações são permitidas:
    - durante o turno do próprio jogador ou durante uma possibilidade de intromissão
        - descartar uma classe ou raça
        - jogar *go up a level* ou *hireling*
        - jogar uma maldição
    - mesmas condições anteoriores, mas não enquanto estiver em combate:
        - trocar item com outro jogador
        - trocar itens equipados
        - jogar cartas que tenha recebido
    - somente durante o próprio turno
        - jogar nova classe ou raça (a qualquer momento)
        - vender itens para ganhar níveis (não durante combate)
        - jogar um item (alguns poucos podem ser jogados durante combate)
