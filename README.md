# 👑 Julia World

Jogo feito só com **HTML, CSS e JavaScript puro** (sem backend, sem bibliotecas). Funciona no navegador e pode ser instalado como app (PWA), inclusive offline.

## Modos de jogo
- 🏰 **Aventura**: 12 fases de plataforma (campo, floresta, praia, deserto, caverna, neve, vulcão, nuvens, pântano, cidade de doces, ruínas e galáxia), 4 chefes e fogo mágico limitado pelas bolinhas de fogo coletadas.
- 💥 **Arena Mágica**: sobreviva a ondas de monstros, escolha upgrades e use a Nova.
- 💎 **Cristais Mágicos**: quebra-cabeça de 3 em linha com combos e gemas especiais.
- 🃏 **Memória Mágica**: ache os pares de cartas; a grade cresce a cada nível.
- ⭐ **Chuva de Estrelas**: pegue estrelas caindo em 45 segundos e desvie das gosmas.
- 🧚 **Voo da Fada**: toque para voar entre os cristais e junte estrelas.
- 🐍 **Cobrinha Mágica**: coma estrelas, cresça e desvie dos cristais.

## Extras
Três princesas com nome personalizado, loja com mais de 80 itens (vestidos, cabelos, coroas, acessórios, sapatos, varinhas, rastros, cores de fogo e bichinhos), 32 conquistas, missões diárias, baú diário, tela de ajuda, bônus diário com sequência, configurações de volume, tela cheia, suporte a controle e progresso salvo no navegador.

## Controles
| Ação | Teclado | Celular |
|---|---|---|
| Andar | Setas ou A/D | Botões ◀ ▶ |
| Pular / Dash | Espaço | Pular / Dash |
| Fogo / Nova | F (ou X, Z) | 🔥 Fogo / 💥 Nova |
| Pausa / Som | P / M | ⏸ / 🔊 |

Na Arena, no celular, arraste o dedo na tela para mover. Nos Cristais, toque ou arraste as gemas.

## Como publicar no GitHub Pages
1. Crie um repositório e envie **todos** os arquivos desta pasta para a raiz.
2. Em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o link gerado (`https://seu-usuario.github.io/seu-repo/`). Para instalar como app, use o botão **Instalar app** em Config (no iPhone: Compartilhar → Adicionar à Tela de Início).

## Arquivos
- `index.html`: o jogo inteiro
- `manifest.webmanifest` e `sw.js`: PWA (instalação e modo offline)
- `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png`: ícones
- `.nojekyll`: evita processamento do Jekyll no GitHub Pages

> Ao alterar o jogo, troque o nome do cache em `sw.js` (`julia-world-v8` → `v9`) para os jogadores receberem a atualização.
