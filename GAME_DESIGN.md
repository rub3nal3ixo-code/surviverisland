# SURVIVAL ISLAND — Documento Mestre
**Estado:** em desenvolvimento · **Versão:** 0.1

## Visão
Jogo 3D de sobrevivência e estratégia multijogador. Cada jogador começa numa ilha e pode evoluir até construir um reino, conquistar outros territórios e participar na formação de um mundo dominado por reinos.

## Mundo
- Visão de longo prazo: 100 ilhas diferentes.
- Cada ilha terá as mesmas categorias fundamentais de recursos, mas geografia e aparência próprias.
- Máximo previsto: 30 jogadores por ilha.
- O jogador escolhe uma ilha no início. Mudar de ilha implica começar de novo e eliminar a personagem anterior.
- Ambientes: praias, florestas, montanhas e cavernas.

## Sobrevivência
- Fome, sede, energia e saúde.
- Recolha de madeira, pedra e outros recursos.
- Caça, alimentação, abrigos, ferramentas, armas, armaduras, construção e criação de objectos.
- Animais e monstros; os monstros aparecem durante a noite e podem detectar e atacar jogadores próximos.

## Personagens e progressão
- Movimentos e animações humanas naturais para deslocação, recolha, combate e interacções.
- Sem níveis de personagem. A força depende do equipamento utilizado.
- Evolução de construção definida inicialmente de madeira até pedra.

## Combate e multijogador
- PvP sempre activo.
- Ao morrer, o jogador não perde os itens que transporta (regra actualmente definida).
- Comunicação por texto e voz de proximidade: o volume da voz diminui com a distância.
- Controlos para PC (teclado/rato) e telemóvel (toque).

## Reinos e liderança
- O objectivo de longo prazo é transformar a ilha num reino e expandir o seu domínio.
- O rei é escolhido por votação e tem mandato de 15 dias.
- Pode existir eleição antecipada para destituir o rei.
- Um rei destituído ou derrotado mantém a personagem, mas passa a jogador normal e pode voltar a candidatar-se numa eleição futura.
- A conquista de uma ilha é feita através da conquista do seu território central.
- O rei vencedor decide inicialmente se o território será aliado, vassalo ou totalmente integrado.
- Para alterar posteriormente o estatuto do território, o rei convoca uma eleição e os jogadores dessa ilha decidem por maioria.
- Numa ilha vassala, os jogadores elegem um governador por mandatos de 15 dias, com possibilidade de reeleição.
- O governador gere construções, recursos e organização interna. Não dispõe de exército próprio; a defesa é feita pelos próprios jogadores.
- O rei pode exigir tributos entre 0% e 35% dos recursos produzidos por cada ilha vassala, definindo a percentagem e podendo alterá-la a qualquer momento.
- Os jogadores de uma ilha vassala podem iniciar um processo de revolta se reunirem apoio de pelo menos 30% dos jogadores da ilha. Atingido o mínimo, abre-se uma votação a todos os jogadores. Se a maioria aprovar, a revolta é aprovada. As condições militares e o resultado final da independência ainda serão definidos.

## Protótipo 0.1 — âmbito implementado
- Ilha 3D procedural simples, mar, árvores, rochas e arbustos.
- Personagem provisória com movimento, salto e câmara em terceira pessoa.
- Recolha de madeira, pedra e alimento para inventário local.
- Controlos de teclado/rato e controlos tácteis básicos.
- Interface adaptável a ecrãs de computador e telemóvel.

## Plano de desenvolvimento
1. Validar o protótipo 3D e a jogabilidade básica.
2. Melhorar personagem, animações, colisões e câmara.
3. Implementar sistemas de sobrevivência, crafting e construção.
4. Introduzir animais, monstros, ciclo dia/noite e combate.
5. Desenvolver contas, persistência e servidor multijogador autoritativo.
6. Implementar ilhas, reinos, eleições, vassalagem, tributos, revoltas e guerras.
7. Optimizar e testar em PC e telemóvel.

## Notas técnicas
O protótipo inicial é uma aplicação web 3D com Three.js. O alojamento estático pode servir o cliente, mas o multijogador real exige um serviço de servidor dedicado/autoridade de jogo. A escala de 100 ilhas e até 3.000 jogadores simultâneos não é adequada a um alojamento gratuito simples. A arquitectura e os custos de produção serão validados antes de activar funcionalidades online.
