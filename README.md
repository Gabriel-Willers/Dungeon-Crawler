# Dungeon-Crawler
Projeto do segundo bimestre de Gabriel Willers e Juan Correa.

História: Em Dungeon Crawler você é um humano comum que despertou na única aldeia de um mundo que foi tomado por dois demônios, "X" e "V". Esses demônios se tornaram reis crúeis, porém, após o primeiro viajante/guerreiro que apareceu nesse mundo travar uma sangrenta batalha e ferir gravemente X, ele enlouqueceu e agora se move freneticamente e sem rumo no mundo; agora, apenas V comanda o planeta. Com isso, você agora tem a missão de escapar desse mundo distópico e retornar para casa com vida.

Jogo: As devidas regras e itens/objetos e personagens são: As paredes em que são definidas pelos "*" são sua maior proteção contra os demônios e que te ajudam a montar uma ótima estratégia de fuga; os espinhos "#" são um tipo de parede que se encostar você perde uma das suas três vidas; as chaves "@" e "O" que servem para, o @, abrir a porta "D" (quando aberta "=") e o O serve para alterar caraterísticas do mapa, como alocar outras paredes e remover algumas além de mudar espinhos de lugar e remove-los, como em todos itens de interação, utilizamos o "i" como caractere de ação; na vila em que spawnamos há um aldeão que explica as regras básicas como andar, que utilizamos W, A, S e D; também, como antes dito, os inimigos "X" e "V", onde X se movimenta de forma aleatória e V te segue pelo mapa; e por último, os teletransportes "<"">", que te ajudam a se locomover pelo mapa. Não há um sistema de combate já que o jogo é baseado em escapar. 

Obs: O jogo deve ser rodado em C++, utlizamos as bibliotecas <time.h> <stdio.h> <conio.h> <stdlib.h> <locale.h> <windows.h>. Além disso, se utilizarmos qualquer variável não presente no jogo não irá constar como ação existente e a ignorará.

Fases:
  - Fase Vila/Tutorial: Está é a fase inicial onde apredemos alguns conceitos básicos do jogo, como a movimentação, espinhos, chaves (@ e O), além disso nós é introduzido o conceito dos demônios. Seu mapa tem 
    dimensões 10x10. E após interagir com o NPC e abrir a porta atrás dele, passamos pro início real do jogo, a fase 1;


![image](https://github.com/user-attachments/assets/bb091fda-6023-4a11-a033-9917a36659f5)  ![image](https://github.com/user-attachments/assets/99975f1f-d866-41df-a591-737786a1bc2d)


  - Fase 1: Também 10x10, nessa fase, já presenciamos como o sistema de chaves e paredes serão, pois lá, a chave está posicionada em uma área similar a um mini labírinto e após interagir com ela, liberamos a fase 2.
 


![image](https://github.com/user-attachments/assets/d091d050-f41b-45b5-9090-aff88f13a38f)  ![image](https://github.com/user-attachments/assets/f68800a3-1f4c-469d-9bff-8bed1ac0b660)


    
  - Fase 2: Nela, o mapa já aumenta pra 20x20, já é possível ver os espinhos e o demônio louco X, lá, devemos nos esgueirar com cuidado para não sermos atingidos por ele e nem pelos espinhos, assim, ao conseguir 
    alcançar a chave O, liberamos a passagem para a chave da porta, após a nossa interação com ela, poderemos passar para a última fase;
  


![image](https://github.com/user-attachments/assets/f32f1aaa-97cf-4161-b8de-d2929627b1db)  ![image](https://github.com/user-attachments/assets/e72511e5-aad4-40cc-b1f2-2aeb5152e295)


 
 - Fase 3: Nessa fase final de dimensões 40x40! Enfrentaremos o rei demônio que nos segue, V. Temos que passar por ele e chegar até a área dos teletransportes, para conseguirmos liberar a porta, após isso, devemos 
   utilizar a chave O para alterar o mapa e mexer nos espinhos e paredes, para então, fugirmos da dungeon!



![image](https://github.com/user-attachments/assets/66a0f750-d885-4200-b6b1-648ca2b57c0d)  ![image](https://github.com/user-attachments/assets/fa6989b9-e8e4-475b-9d87-1054afc6f1a8)



Após finalizar todas as fases, você escapa da dungeon e pode retornar ao menu para visulizar os créditos, jogar novamente ou sair.

Créditos: 

![image](https://github.com/user-attachments/assets/7f0b0aa2-20aa-4cc8-85e4-3a5a29e129ea)
