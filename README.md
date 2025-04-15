Mapa Interativo de Árvores Mapeadas - Cornélio Procópio, PR

Este projeto desenvolveu um mapa interativo para visualizar árvores mapeadas em uma propriedade em Cornélio Procópio, Paraná, Brasil. Utilizando a biblioteca Mapbox GL JS, o mapa exibe pontos que representam árvores, organizados por categorias como "Acesso Principal e Ilha da Loja", "Vila Bromélia" e outras, com cores distintas para cada trecho. Além disso, apresenta três limites de propriedade com bordas coloridas, permitindo uma análise espacial clara.
O objetivo do trabalho foi criar uma ferramenta intuitiva para explorar os dados das árvores, incluindo informações detalhadas como espécie, altura, diâmetro, grau de risco e ação recomendada, acessíveis por popups ao clicar nos pontos. A interface inclui filtros para selecionar árvores por categoria, grau de risco ou faixa de altura, além de opções para alternar estilos de mapa, exportar a visualização como imagem e controlar a exibição de camadas. O projeto organiza os dados em arquivos GeoJSON, garantindo uma estrutura modular e fácil de atualizar, com o propósito de apoiar a gestão ambiental e o planejamento da propriedade.
Funcionalidades

Visualização de árvores com cores por categoria.
Filtros por categoria, grau de risco e altura.
Popups com detalhes (espécie, nome científico, CAP, DAP, etc.).
Exibição de limites da propriedade (borda sem preenchimento).
Controles para centralizar o mapa, exportar imagem e mudar estilos.
Opções para mostrar/esconder pontos e limites.

Estrutura do Projeto
├── index.html                   # Interface principal do mapa
├── arvores.json                 # Dados das árvores (GeoJSON)
├── limite_propriedade.geojson   # Primeiro limite da propriedade
├── limite_propriedade_2.geojson # Segundo limite
├── limite_propriedade_3.geojson # Terceiro limite
└── README.md                    # Documentação

Como Usar

Clone o repositório.
Coloque os arquivos em um servidor local (ex.: http-server).
Acesse via navegador (ex.: http://localhost:8080).
Substitua o token do Mapbox em index.html, se necessário.

Tecnologias

Mapbox GL JS
HTML, CSS, JavaScript
GeoJSON

Licença
Licenciado sob MIT License.

Desenvolvido por João Pedro da CS Consultoria Ambiental.
