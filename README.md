# Batalha de Monstros

Bem-vindo à Batalha de Monstros! Aqui, você pode cadastrar monstros únicos informando nome, ataque, defesa, velocidade e pontos de vida. Após cadastrar apertando o botão submit, o jogo determinará automaticamente quem ataca primeiro, considerando a velocidade e, em caso de empate, o ataque. O dano será calculado com base nas estatísticas de cada monstro, e o resultado será mostrado abaixo. 

Para determinar o vencedor é levado em conta as seguintes regras:
- O monstro com a maior velocidade faz o primeiro ataque; se ambas as velocidades forem iguais, o monstro com o maior ataque vai primeiro.
- Para calcular o dano (`damage`), subtraia a defesa do ataque (`atack - defense`); a diferença é o dano; se o ataque for igual ou menor que a defesa, o dano é 1.
- Subtraia o dano do `hp` do monstro que sofreu o ataque (`hp = hp - damage`).
- Os monstros batalharão em rounds até que um vença; todos os rounds devem ser calculados de uma vez só
- Quem vence a batalha é o monstro que subtraiu o `hp` do inimigo a zero primeiro

## A aplicação esta live no seguinte link abaixo:
https://caioteixeira10.github.io/monster-game/

## Para rodar a aplicação localmente, é necessário rodar os seguintes passos:
`git clone https://github.com/caioteixeira10/monster-game.git`

`cd monster-game`

`npm install`

`npm run dev`

Após feito esses passos, a aplicação deverá estar disponível para acesso através do seguinte link abaixo:
`http://localhost:5174/monster-game`
