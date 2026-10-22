<img src="assets/header.svg" width="100%" alt="Cabeçalho">

<p align="center">
  <img src="assets/typing.svg" alt="Godot 4 e GDScript, combate, inimigos e chefes">
</p>

<p align="center">
  <a href="[link do itch.io]">itch.io</a> &nbsp;|&nbsp;
  <a href="[link do portfólio]">Portfólio</a> &nbsp;|&nbsp;
  <a href="mailto:[seu e-mail]">E-mail</a> &nbsp;|&nbsp;
  <a href="[link do LinkedIn]">LinkedIn</a>
</p>

<p align="center">
  <sub>[Cidade, Estado], Brasil</sub>
</p>

---

## Sobre mim

Desenvolvo jogos 2D com foco em sistemas de jogo: combate, comportamento de inimigos, chefes e feedback visual e sonoro. Escrevo meu código em GDScript e documento tudo em português.

Meu projeto principal é um jogo de ação e plataforma protagonizado por um pombo, com combate corpo a corpo inspirado em metroidvanias, inimigos com comportamentos próprios e chefes com mecânicas de cenário. Também desenvolvo interfaces web com HTML, CSS e Bootstrap.

## Projeto em destaque

### [Nome do jogo]

Jogo 2D de ação e plataforma em Godot 4.

- Combate corpo a corpo com pogo, recuo e hitstop
- Inimigos com estados, fúria e fintas
- Chefes com fases e lógica anti-camping
- Estamina compartilhada entre voo e rajada
- Diálogos com texto digitado e retratos dos personagens
- Portais de caverna com transição em blocos de pedra

[Repositório](https://github.com/SEU-USUARIO/[nome-do-jogo]) | [Jogar no itch.io]([link do itch.io]) | [Releases](https://github.com/SEU-USUARIO/[nome-do-jogo]/releases)

<!-- Para mostrar um GIF do jogo, envie o arquivo para a pasta assets e descomente a linha abaixo:
<img src="assets/gameplay.gif" width="100%" alt="Gameplay">
-->

## Stack

| Área | Ferramentas |
| :--- | :--- |
| Engine | Godot 4 |
| Linguagens | GDScript, HTML, CSS, JavaScript |
| Front-end | Bootstrap 5 |
| Arte | [Aseprite / Krita / outro], pixel art 32x32 |
| Áudio | [Audacity / outro] |
| Versionamento | Git e GitHub |

## Projetos

| Projeto | Descrição | Tecnologias |
| :--- | :--- | :--- |
| [nome-do-jogo](https://github.com/SEU-USUARIO/[nome-do-jogo]) | Jogo 2D de ação e plataforma com chefes | Godot, GDScript |
| [site-de-jogos](https://github.com/SEU-USUARIO/[site-de-jogos]) | Site de jogos com carrossel, cartões e login | HTML, CSS, Bootstrap 5 |
| [outro-projeto](https://github.com/SEU-USUARIO/[outro-projeto]) | [Descrição curta] | [Tecnologias] |

## Detalhes técnicos do jogo

<details>
<summary><strong>Combate</strong></summary>

<br>

- Golpe corpo a corpo estilo espada, com hitbox por direção (frente, cima e baixo)
- Pogo: ao acertar para baixo, o jogador recebe um impulso para cima
- Recuo no jogador e no inimigo atingido
- Hitstop para dar peso aos acertos
- Pisão em inimigos com quique e invencibilidade curta após o dano

</details>

<details>
<summary><strong>Inimigos</strong></summary>

<br>

- Base comum de inimigo, com herança para variações (aranha, escorpião, atirador, minhoca)
- Máquina de estados por inimigo: parado, preparando, ataque, recuperação, morto
- Modo de fúria com mais velocidade e menos tempo de recuperação
- Escorpião que se enterra e emerge, com proteção contra empurrão ao emergir
- Atirador à distância com projétil próprio
- Regras anti-abuso para impedir que o jogador fique saltando sobre o inimigo

</details>

<details>
<summary><strong>Chefes</strong></summary>

<br>

- RayCast2D para detectar paredes e pular obstáculos
- Ataques variados: investida, sorvo, erupção, rugido, ondas de choque e furacões
- Fases por vida restante, com fúria e desespero
- Sistema anti-camping e empurrão para impedir que o jogador fique sobre o chefe

</details>

<details>
<summary><strong>Mundo e progressão</strong></summary>

<br>

- Portais de caverna com teleporte na mesma cena ou troca de cena
- Transição de tela com blocos de pedra
- Checkpoints globais e controle de fase
- Dicas de tutorial com ícones de tecla que reagem às ações reais do InputMap

</details>

<details>
<summary><strong>Interface e áudio</strong></summary>

<br>

- Barra de vida com animação por tween e feedback de dano e cura
- Barra de estamina compartilhada entre voo e rajada
- Diálogos com texto digitado, rolagem automática e retrato do personagem
- Música dinâmica que acelera conforme a fase da luta
- Passos por superfície (grama, pedra, madeira) via Custom Data Layers

</details>

## Como eu trabalho

- Entrego scripts completos e testáveis, não trechos soltos
- Separo cada sistema em um script com uma responsabilidade
- Uso variáveis `@export` para ajustar valores no editor sem mexer no código
- Comento em português e nomeio estados e sinais de forma legível
- Depuro com cenas de teste isoladas

## Roadmap

- [x] Combate corpo a corpo com pogo e hitstop
- [x] Primeiros chefes e inimigos de caverna
- [x] Sistema de diálogo e dicas de tutorial
- [ ] [Nova fase]
- [ ] [Novo chefe]
- [ ] [Menu de opções e configurações de áudio]
- [ ] Lançamento da demo no itch.io

## Contato

Aberto a colaborações, feedback sobre os jogos e oportunidades na área.

- E-mail: [seu e-mail]
- itch.io: [link]
- LinkedIn: [link]
- Portfólio: [link]
