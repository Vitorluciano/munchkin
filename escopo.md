# Escopo do Jogo Munchkin


Ao entrar no jogo, o usuário deve encontrar encontrar duas opções disponíveis: nova partida e sair.

Ao selecionar a opção nova partida, o usuário poderá **escolher a quantidade de IAs contra as quais irá jogar** (de 2 a 5) e **iniciar partida**.

Ao selecionar a opção **iniciar partida** o jogador receberá 8 cartas (4 da pilha de tesouros e 4 da pilha da porta) e terá a oportunidade de jogar algumas delas (de raça, classe e itens). Após isso, se ele não não for o jogador sorteado para abrir a partida, ele deverá aguardar a sua vez até que alguns de seus adversários finalizem seus respectivos turnos, tendo possibilidade de inteferência em algumas oportunidades específicas.

Quando chegar a sua vez, o turno será dividido em 3 fases:
**na primeira**, o jogador poderá jogar mais algumas cartas e então deve clicar na opção "abrir porta". 
O turno transitará então para a **segunda fase**, onde o jogador irá exclusivamente receber uma nova carta para sua mão ou enfrentar um monstro. Caso o primeiro evento descrito ocorra, o jogador terá a opção de *lootear* a sala ou jogar um monstro de sua mão para combate-lo. Durante os combates, adversários poderão interferir, por iniciativa própria ou solicitação do jogador.
Por fim, a partir da **terceira fase**, o jogador terá uma outra oportunidade para jogar suas cartas, sabendo que ele só poderá ter 5 cartas em mãos antes de encerrar seu turno, sob pena de ser obrigado a doar cartas excendentes aos jogadores com o nível mais baixo da partida.

A partida acaba quando alguém alcançar o nível 10. Além disso, durante a partida o jogador terá a opção de desistir e voltar ao menu inicial.

A principal tecnologia e ser utilizada durante o desenvolvimento será a engine Unity 6.
