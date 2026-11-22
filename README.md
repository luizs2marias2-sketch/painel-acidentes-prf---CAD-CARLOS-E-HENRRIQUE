# Painel de Acidentes nas Rodovias Federais (2026)

Painel interativo com os acidentes registrados pela Polícia Rodoviária Federal
de 01/01 a 31/10/2026 (arquivo `datatran2026`).

- Número total de acidentes, mortos, feridos, pessoas e veículos envolvidos
- Evolução mês a mês, com máximo e mínimo destacados
- Principais causas e municípios com mais acidentes
- Mapa por estado e mapa dos pontos de acidente nas rodovias
- Filtros por estado, classificação do acidente e mês, calculados no próprio navegador

Abra o `index.html` no navegador ou acesse o link do GitHub Pages deste repositório.
Os filtros ficam no endereço da página (ex.: `#uf=PB&mes=2026-03`), então dá para
compartilhar um link já filtrado.

Feito com Python, Pandas, Django e Plotly. Fonte dos dados: Polícia Rodoviária Federal (dados abertos).
