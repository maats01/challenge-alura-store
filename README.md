# challenge-alura-store

# Propósito da Análise
Esse notebook tem como objetivo analisar dados de vendas de quatro filiais e decidir qual delas é a menos eficiente, com o intuito de vendê-la.

# Gráficos gerados
## 1. Faturamento
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Loja</th>
      <th>Preço</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Loja 1</td>
      <td>1534509.12</td>
    </tr>
    <tr>
      <td>Loja 2</td>
      <td>1488459.06</td>
    </tr>
    <tr>
      <td>Loja 3</td>
      <td>1464025.03</td>
    </tr>
    <tr>
      <td>Loja 4</td>
      <td>1384497.58</td>
    </tr>
  </tbody>
</table>

<img src="https://github.com/maats01/challenge-alura-store/blob/main/assets/faturamentos_por_loja.png" width="60%">

## 2. Faturamento por categoria
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Categoria do Produto</th>
      <th>Faturamento Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>eletronicos</td>
      <td>2214099.72</td>
    </tr>
    <tr>
      <td>eletrodomesticos</td>
      <td>1766337.03</td>
    </tr>
    <tr>
      <td>moveis</td>
      <td>1010214.00</td>
    </tr>
    <tr>
      <td>instrumentos musicais</td>
      <td>465029.67</td>
    </tr>
    <tr>
      <td>esporte e lazer</td>
      <td>190635.39</td>
    </tr>
    <tr>
      <td>brinquedos</td>
      <td>98140.86</td>
    </tr>
    <tr>
      <td>utilidades domesticas</td>
      <td>76773.38</td>
    </tr>
    <tr>
      <td>livros</td>
      <td>50260.74</td>
    </tr>
  </tbody>
</table>

<img src="https://github.com/maats01/challenge-alura-store/blob/main/assets/faturamentos_por_categoria.png" width="60%">

## 3. Frete médio por loja
<table id="T_dc375">
  <thead>
    <tr>
      <th class="blank level0" >&nbsp;</th>
      <th id="T_dc375_level0_col0" class="col_heading level0 col0" >Loja</th>
      <th id="T_dc375_level0_col1" class="col_heading level0 col1" >Frete médio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="T_dc375_level0_row0" class="row_heading level0 row0" >0</th>
      <td id="T_dc375_row0_col0" class="data row0 col0" >Loja 1</td>
      <td id="T_dc375_row0_col1" class="data row0 col1" >34,69</td>
    </tr>
    <tr>
      <th id="T_dc375_level0_row1" class="row_heading level0 row1" >1</th>
      <td id="T_dc375_row1_col0" class="data row1 col0" >Loja 2</td>
      <td id="T_dc375_row1_col1" class="data row1 col1" >33,62</td>
    </tr>
    <tr>
      <th id="T_dc375_level0_row2" class="row_heading level0 row2" >2</th>
      <td id="T_dc375_row2_col0" class="data row2 col0" >Loja 3</td>
      <td id="T_dc375_row2_col1" class="data row2 col1" >33,07</td>
    </tr>
    <tr>
      <th id="T_dc375_level0_row3" class="row_heading level0 row3" >3</th>
      <td id="T_dc375_row3_col0" class="data row3 col0" >Loja 4</td>
      <td id="T_dc375_row3_col1" class="data row3 col1" >31,28</td>
    </tr>
  </tbody>
</table>

<img src="https://github.com/maats01/challenge-alura-store/blob/main/assets/frete_medio.png" width="60%">

# Instruções para executar o notebook
Para visualizar e executar a análise diretamente no seu navegador, clique no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maats01/challenge-alura-store/blob/main/AluraStoreBrasil.ipynb)
