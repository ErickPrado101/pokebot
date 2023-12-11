# pokebot

bot programado para jogar roms de Pokémon de Nitendo DS feito em Python, ele farma xp e money, ainda não desenvolvi esse hack para vida real,calma!

o bot salva o jogo e caminha o jogador da esquerda para a direita, se o pixel abaixo do cursor do mouse for da mesma cor que a cabeça do sprite no jogo (ou seja, se o mouse passar sobre o personagem). Quando uma batalha é iniciada, o bot pressiona a tecla X (o botão A) até que a batalha termine. Porém, se a batalha durar mais de 3 minutos, bot assume que o movimento líder está sem PP, fugindo posteriormente e mudando a ordem do movimento. Se a tag switch estiver definida, o Bot troca as posições do primeiro e do segundo Pokémon no grupo.
