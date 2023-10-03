# Apis-Melifera-Honeybee

**Este projeto tem como objetivo desenvolver vários modelos de aprendizagem automática para prever a ocorrência de uma espécie de abelha em diferentes regiões da Península Ibérica, a fim de determinar qual deles apresenta o melhor desempenho na tarefa de predição**.

<hr>

- O conjunto de dados (_dataset_bees.csv_) utilizado possui informações sobre as características climáticas e geográficas, bem como dados de observação da presença (1) ou da ausência/pseudo-presença (0) da espécie em questão. Um dos desafios reside na abordagem do desequilíbrio entre classes nos dados, onde a classe minoritária (ocorrência da espécie) é rara em comparação com a classe majoritária (pseudo-presença).

<p align="center">
  <img src="https://github.com/AfonsoPaula/Apis-Melifera-Honeybee/assets/67978137/36c8c24e-ac2a-4aa6-b78b-c46710289372">
</p>

<hr>

- O projeto inclui várias etapas, nomeadamente no que diz respeito ao pré-processamento, normalização e divisão dos dados, assim como a aplicação da melhor técnica (_undersampling_ ou _oversampling_) para equilibrar as classes nos conjuntos previamente divididos, de modo a conseguir desenvolver modelos mais precisos.

<table align="center">
    <tr>
        <td>Atributos</td>
        <td><strong>Baseline</strong></td>
        <td><strong>RO</strong></td>
        <td><strong>SMOTE</strong></td>
        <td><strong>RU</strong></td>
        <td><strong>NM</strong></td>
    </tr>
    <tr>
        <td><strong>Nº de dados (1)</strong></td>
        <td>89</td>
        <td>6515</td>
        <td>6515</td>
        <td>89</td>
        <td>89</td>
    </tr>
    <tr>
        <td><strong>Nº de dados (0)</strong></td>
        <td>6515</td>
        <td>6515</td>
        <td>6515</td>
        <td>89</td>
        <td>89</td>
    </tr>
    <tr>
        <td><strong>Precision (1)</strong></td>
        <td>0.07</td>
        <td>0.03</td>
        <td>0.09</td>
        <td>0.03</td>
        <td>0.01</td>
    </tr>
    <tr>
        <td><strong>Recall (1)</strong></td>
        <td>0.03</td>
        <td>0.08</td>
        <td>0.08</td>
        <td>0.62</td>
        <td>0.62</td>
    </tr>
    <tr>
        <td><strong>Accuracy</strong></td>
        <td>98.23</td>
        <td>95.23</td>
        <td>97.73</td>
        <td>68.88</td>
        <td>36.98</td>
    </tr>
</table>

<hr>

- Após a aplicação dos modelos, é elaborado um gráfico que contém todas as curvas ROC (_Receiver Operating Characteristic_) e, consequentemente, as suas AUC (_Area Under the Curve_), com o propósito de comparar e entender qual dos modelos abordados possui um melhor desempenho. Esta análise permitirá selecionar o modelo mais adequado para fornecer previsões precisas sobre a presença da espécie _Apis-Melifera-Honeybee_ em diferentes regiões da Península Ibérica.

<p align="center">
  <img src="https://github.com/AfonsoPaula/Apis-Melifera-Honeybee/assets/67978137/571e8097-f1ce-4580-a67d-7799f37108ac">
</p>

<hr>
