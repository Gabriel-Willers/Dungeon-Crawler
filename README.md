# Dungeon-Crawler
Trabalho do segundo bimestre de Gabriel Willers e Juan Correa

História: Em Dungeon Crawler você é um humano comum que despertou na única aldeia de um mundo que foi tomado por dois demônios, "X" e "V". Esses demônios se tornaram reis crúeis, porém, após o primeiro viajante/guerreiro que apareceu nesse mundo travar uma sangrenta batalha e ferir gravemente X, ele enlouqueceu e agora se move freneticamente e sem rumo no mundo; agora, apenas V comanda o planeta. Com isso, você agora tem a missão de escapar desse mundo distópico e retornar para casa com vida.

Jogo: O jogo em si tem 4 fases: fase de aldeia/tutorial aonde o NPC "P" te explica o básico do jogo como locomoção pelas teclas W, A, S e D, e um pouco do local, dos objetos e inimigos(demônios); a fase 1 que é de fato o início da jornada, lá você vê realmente como será o jogo adiante, temos paredes em "*" e as portas "D" fechadas e apos interagir com a chave "@" você a libera para "="; a fase 2 já possui o demônio louco X, ele não irá focar em te atacar, por se mover de maneira aleatória no mapa, lá tembém é introduzida a funcionalidade dos espinhos "#" que te tiram uma vida das suas 3 e te fazem resetar a fase, lá também temos o "O", que assim como a chave, ao utilizar "i" você interage com ele e ou desativa todos os espinhos ou desativa alguns e ativa outros; e a fase final/fase 3, lá temos o inimigo mais perigoso que é o V, ele te segue e te mata tirando uma das suas vidas, assim como o # e o X, ká você também encontra os teleportes "<" e ">", que te trazem e levam pra outras salas no mapa, o O dessa fase abre e fecha algumas paredes além de remover e adicionar alguns espinhos pelo mapa, após sua fuga você pode voltar ao menu e restartar o jogo. 





Sobre a mecânica em si, utilizamos majoritariamente funcões para executar os comandos e criação de mapas, açterações de fase e cconstrução das paredes, espinhos e para a colisão; para limitar aonde o personagem se move nós utilizamos char, assim aonde o "&" do nosso herói se move, se tivermos um "*" presente na coordenada do local que iriamos nos posicionar, ele não conseguirá cumprir o comando de locomoção por conta de um if que traz esta condição, foi um sistema similar para os inimigos, onde ao suas coordenadas se encontrarem com a do jogador (JogX e JogY) a colisão seria ativada e perdemos uma vida

