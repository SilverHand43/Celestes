Primeira versao do Celestes! um simulador do sistema solar comproporção fisica real!
# Celestes — Simulador do Sistema Solar

Simulador interativo do sistema solar em HTML/CSS/JavaScript puro (sem dependências, sem build — é um único arquivo). Feito para rodar direto no navegador ou publicado via GitHub Pages.

## Funcionalidades

- **Órbitas reais**: os 8 planetas orbitam o Sol com velocidades relativas fiéis aos períodos orbitais reais.
- **Dados físicos reais** de cada planeta: gravidade de superfície, raio, massa, distância do Sol, período orbital, velocidade orbital.
- **Rotação real**: velocidade de rotação no equador (km/h), sentido de rotação (prógrado/retrógrado) e inclinação axial de cada planeta, com uma pequena esfera que gira na velocidade e no ângulo corretos.
- **Zoom com scroll do mouse** e **arraste para navegar** pelo sistema, com duplo clique para reenquadrar.
- **Clique em um planeta** para dar um zoom cinematográfico nele e ver a **malha de distorção gravitacional** (um "poço gravitacional" estilizado) que ele cria no espaço, com profundidade proporcional à massa real do corpo.
- **Luas galileanas de Júpiter** (Io, Europa, Ganimedes e Calisto): aparecem orbitando Júpiter visivelmente a partir de um certo nível de zoom, e são clicáveis — mostrando as mesmas informações físicas dos planetas (gravidade, massa, raio, período orbital).

## Como usar

Basta abrir o arquivo `index.html` em qualquer navegador moderno. Não há passos de instalação nem dependências externas (exceto fontes do Google Fonts, carregadas via CDN).

## Controles

| Ação | Como fazer |
|---|---|
| Selecionar um planeta | Clicar nele (no desenho ou na lista lateral) |
| Ver a distorção gravitacional | Clicar no planeta (zoom automático) |
| Sair do zoom | Botão ✕ ou clicar novamente |
| Zoom livre no sistema | Rolar o scroll do mouse |
| Navegar pelo sistema | Clicar e arrastar |
| Reenquadrar tudo | Duplo clique |
| Ver as luas de Júpiter | Aproximar o zoom (scroll) até elas aparecerem, ou clicar em Júpiter |
| Ver dados de uma lua | Clicar nela |
| Ajustar velocidade da simulação | Slider "velocidade" no topo |
| Pausar/retomar | Botão ❙❙ / ▶ |

## Sobre os dados

Os valores de gravidade, massa, raio, período orbital/rotacional e inclinação axial são baseados em dados astronômicos reais (fontes como a NASA/JPL). Distâncias e tamanhos exibidos no mapa usam escalas não lineares para caberem na tela — os números mostrados nos painéis são sempre os valores reais.

## Tecnologias

HTML5 Canvas, CSS3 e JavaScript vanilla. Sem frameworks, sem bundlers, sem dependências de build.
