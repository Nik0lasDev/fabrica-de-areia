# ⛏️ Fábrica de Areia

Sandbox de mineração, física de partículas e automação para navegador, inspirado no gênero de jogos de fábrica com mundo granular.

**Jogar:** https://nik0lasdev.github.io/fabrica-de-areia/

## Ciclo de jogo

1. Cave areia, água, rocha e madeira usando a ferramenta apropriada.
2. Colete água com o balde e despeje-a perto da areia para criar areia molhada.
3. Cave um espaço e coloque um **Shaker** sob a areia molhada.
4. O Shaker transforma areia molhada em resíduo e tem 25% de chance de liberar ouro.
5. Coloque um coletor perto do ouro para recolhê-lo automaticamente.
6. Invista ouro em pesquisas para desbloquear esteiras, tochas e prensas.
7. Queime resíduos e processe resíduos queimados na prensa para produzir mais ouro.

## Controles

- **A/D** ou **setas:** mover o personagem.
- **W**, **seta para cima** ou **Espaço:** pular.
- **E:** tentar recolher ouro próximo.
- **Clique/toque no mundo:** usar a ferramenta selecionada ou colocar a máquina.
- **Botões na tela:** controles básicos para dispositivos móveis.

## Ferramentas e máquinas

- **Pá:** escava areia, areia molhada e resíduos.
- **Picareta:** escava rocha e ouro.
- **Machado:** coleta madeira.
- **Balde:** coleta água e permite despejá-la em espaços vazios.
- **Shaker:** processa areia molhada em resíduo e ouro ocasional.
- **Coletor:** recolhe ouro próximo automaticamente.
- **Esteira:** transporte horizontal, desbloqueado pela pesquisa Logística.
- **Tocha e prensa:** processamento de resíduos, desbloqueado pela pesquisa Refino.

## Desenvolvimento

O jogo está em protótipo e ainda precisa de testes em diferentes navegadores e tamanhos de tela. O mundo é gerado localmente no navegador; o botão **Novo mundo** reinicia a partida atual.