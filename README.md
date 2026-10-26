# Brasil Manager 2000

Jogo de carreira de técnico do futebol brasileiro em pixel art. Escolha um clube, monte o time, treine, negocie jogadores e dispute estaduais, Brasileirão, Copa do Brasil, Libertadores e Sul-Americana.

O jogo inteiro é um único arquivo, `index.html`. Não precisa instalar nada: abra o arquivo no navegador ou publique pelo GitHub Pages.

## Jogar online

Em **Settings > Pages**, escolha **Source: GitHub Actions**. A cada push na `main` o workflow publica o `index.html` em `https://capelovwski.github.io/brasilmanager/`.

## Salvamento

O jogo salva sozinho no navegador (localStorage). O salvamento na nuvem (3 espaços) só funciona dentro do claude.ai; fora de lá use o arquivo de exportação.

## Telas

- **Celular:** uma coluna, barra de abas embaixo.
- **Desktop (a partir de 900 px):** menu lateral, duas colunas com painel de informações e janelas em pop-up.

## Novidades

- **0.27.0:** versão desktop em tela cheia, sem rolagem: menu lateral com a bandeira tremulando, painéis que se ajustam à altura da tela.
- **0.26.0:** pré-temporada com amistosos opcionais; modo leve (estádio a 30 fps, animações pausam em segundo plano, pixel arts com bem menos nós no DOM).

Veja `docs/backlog.md` para o que vem a seguir.
