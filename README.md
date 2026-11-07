# SURVIVAL ISLAND

Protótipo de um jogo 3D de sobrevivência, exploração e construção para PC e telemóvel.

## Estado actual — Protótipo 0.1
- Ilha 3D com mar, terreno, árvores, rochas e arbustos.
- Personagem provisória em terceira pessoa.
- Movimento, salto e recolha de madeira, pedra e alimento.
- Inventário básico.
- Controlos de teclado/rato e botões tácteis.

## Testar localmente
Como o jogo usa módulos JavaScript, abre a pasta através de um servidor HTTP local (não directamente por `file://`).

Com Python instalado:
```bash
python -m http.server 8000
```
Depois abre http://localhost:8000.

Também pode ser publicado como site estático. O jogo online multijogador exigirá posteriormente um servidor próprio.

## Ficheiros
- `index.html` — protótipo jogável.
- `GAME_DESIGN.md` — documento mestre das regras e visão do jogo.

## Direcção
A visão completa prevê 100 ilhas, até 30 jogadores por ilha, sobrevivência, combate, monstros, construção, reinos, eleições, vassalagem, tributos, revoltas e guerras. Estas funcionalidades serão adicionadas por etapas e não estão todas implementadas no protótipo 0.1.
