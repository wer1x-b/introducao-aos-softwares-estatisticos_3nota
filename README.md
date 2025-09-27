# 3º Avaliação: plotagem e aceleração computacional em Python

Este repositório apresenta um material didático sobre visualização de dados e aceleração computacional utilizando Python, abordando os principais pacotes do ecossistema científico.

## Conteúdo

- **Visualização de dados**:
  - [Matplotlib](https://matplotlib.org/): biblioteca base para gráficos em Python.
  - [Seaborn](https://seaborn.pydata.org/): gráficos estatísticos sofisticados e integração com DataFrames.
  - [Plotly](https://plotly.com/python/): gráficos interativos e dashboards.
  - [Plotnine](https://plotnine.org/): gramática de gráficos inspirada no ggplot2 do R.

- **Aceleração computacional**:
  - [Numba](https://numba.pydata.org/): compilação JIT para acelerar código Python, especialmente útil para simulações e processamento numérico.

## Estrutura

- `index.qmd`: documento principal em Quarto, com exemplos, explicações e gráficos.
- `imagens/`: logos dos pacotes utilizados.
- `.venv/`: ambiente virtual Python (crie com `python -m venv .venv`).

## Como visualizar

Acesse pelo link: [https://wer1x-b.github.io/introducao-aos-softwares-estatisticos_3nota/](https://wer1x-b.github.io/introducao-aos-softwares-estatisticos_3nota/)

Ou siga os passos abaixo para renderizar localmente:

1. Instale o [Quarto](https://quarto.org/docs/get-started/).
2. Ative o ambiente virtual:
   ```
   .\.venv\Scripts\Activate
   ```
3. Instale as dependências:
   ```
   pip install matplotlib seaborn plotly plotnine pandas numpy numba
   ```
4. Renderize o documento:
   ```
   quarto preview index.qmd
   ```
   Ou exporte para HTML/PDF:
   ```
   quarto render index.qmd
   ```

## Referências

- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [Plotnine](https://plotnine.org/)
- [Numba](https://numba.pydata.org/)

---

Material produzido por Wericky Barbosa de Melo.