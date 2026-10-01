# GR-Access

Painel de edição alternativo, totalmente acessível por voz, para a pedaleira **Roland GR-55** (sintetizador de guitarra e baixo) — pensado desde o início para o [NVDA](https://www.nvaccess.org/), já que os editores existentes não são utilizáveis com leitor de tela.

Dá acesso, por teclado e com retorno falado, a tudo o que a GR-55 oferece pelo MIDI: timbres PCM (categoria e timbre em cascata), Modeling (guitarra, violão, baixo e synth), AMP, MOD, MFX, Delay, Reverb, Chorus, EQ, pedais CTL/EXP/GK, os 8 Assigns, V-LINK, afinação alternativa, todos os ajustes de sistema (perfis de GK, MIDI/USB, tabela RX PC MAP), gravação, troca e organização de patches, e backup/restauração em arquivo (.syx e .g5l do GR-55 Librarian). Os menus seguem exatamente o mapa da própria pedaleira — mesmas telas, mesmos ícones, mesma ordem — e tudo o que for mexido na pedaleira é anunciado na hora.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)** deste repositório. O pacote já vem pronto pra rodar no Windows — não precisa instalar Python nem compilar nada.

Cada Release traz as notas da versão com o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali — cópias obtidas por qualquer outro canal não têm garantia de integridade.

## Requisitos

- Windows 10/11 (64 bits), com o driver da Roland GR-55 instalado e a pedaleira conectada por USB.
- [NVDA](https://www.nvaccess.org/) é o leitor de tela com suporte principal (o programa também tem rotas alternativas pra leitores compatíveis com Tolk e pro SAPI do Windows).

## Manual

O manual completo, em English/Français/Español/Português, vem incluso dentro do zip do programa e também disponível como arquivo separado na página de Releases. Dentro do programa, F1 abre um guia rápido de teclas.

## Licença

Veja [LICENSE](LICENSE) para termos de uso e créditos de terceiros.
