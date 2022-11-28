<h2 align = "center"> Dengue: O uso de ferramentas estatísticas para a propensão de uma das doenças mais negligenciadas do Brasil. </h2>
<h3 align = "center"> Utilizando Machine Learning para a previsão de casos de Dengue em Campinas/SP </h3>

<p align = "justify"> Entende-se que a Dengue é uma das doenças mais negligenciadas do Brasil, visto que, em todos os anos se observa um pico no número de casos confirmados. Observou-se que o padrão dos picos está relacionado com características climáticas de determinadas épocas do ano. Com base nisso, concretiza-se a ideia de desenvolver um plano preventivo baseado nos dados coletados. </p>

<h3 align = "center"> Fontes: </h3>
<p align = "justify"><i> https://www.kaggle.com/datasets/renangomes/dengue-temperatura-e-chuvas-em-campinassp
<br> https://clima.iac.sp.gov.br/
<br> http://www.ciiagro.org.br/ema/ </i></p>

<p align = "justify"> Os dados de casos confirmados na cidade de Campinas/SP durante os anos de 1998 à 2014 foram coletados do SINAN (Sistema de Informação de Agravos de Notificação). Os dados pluviais foram colhidos do IAC (instituto Agrônomico de Campinas) e do Ciiagro (Centro Integrado de Informações Agrometeorológicas) </p>

<h3 align = "center"> Desenvolvimento: </h3>
<blockquote> Projeto para a Disciplina de Aprendizado de Máquina da ILUM - Escola de Ciências </blockquote>

<p align = "justify"> Professores: Daniel Cassar e James Moraes </p>
<p align = "justify"> Alunos: </p>
<ul>
  <li> Ana Clara Batista Loponi </li>
  <li> Ana Clara Santos Brandão </li>
  <li> Heitor Ribeiro Bernardes </li>
  <li> Lorraine Cristina Silva Casseano </li>
</ul>

<h3 align = "center"> Guia do Repositório: </h3>

<h5 align = "center"> Blocos de Desenvolvimento </h5>

<details><summary> Análise de Dados - Bloco 1 </summary> 
<p align = "justify"> Coleta de Dados:
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/An%C3%A1lise%20de%20Dados.ipynb"> Bloco 1 </a>
<br> - Breve descrição sobre o projeto, motivação e objetivos;
<br> - Análise Exploratória do Dados;
<br> - Métodos de normalização e tratamento do Dataset original;
<br> - Ferramentas Estatísticas: Matriz de Correlação;
<br> - Gráficos de Análise;
<br> - Classificação e Categorização.
</p>
</details>
  
<details><summary> Modelos de Treinamento 1 - Bloco 2 </summary> 
<p align = "justify"> Interpretação e Treino dos Dados:
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/Modelos%20de%20Treinamento%20.ipynb"> Bloco 2 </a>
<br> - Treinando Modelos: Aprendizado Supervisionado;
<br> - Definindo dataset de Treino e Teste;
<br> - Baseline;
<br> - K Vizinhos mais próximos;
<br> - Regressão Linear;
<br> - Árvore de Decisão;
<br> - Floresta Aleatória;
<br> - Desempenho dos modelos de Regressão;
<br> - Dados Categóricos;
<br> - Matriz de Confunsão;
<br> - Avaliação de Hiperparâmetros.
</p>
</details>
  
<details><summary> Modelos de Treinamento 2 - Bloco 3 </summary> 
<p align = "justify"> Interpretação e Treino dos Dados:
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/Modelos%20de%20Treinamento_2.ipynb"> Bloco 3 </a>
<br> - Aprendizado Não-Supervisionado;
<br> - Dataset de Treino, Teste e Hiperparâmetros;
<br> - Transformação PCA;
<br> - Análise de Features x Componentes;
<br> - Análise Variância;
<br> - K-Means;
<br> - WSS (Within-Cluster-Sum of Squared Errors);
<br> - LOF (Algoritmo Local Outlier Factor);
<br> - IF (Algoritmo Isolation Forest).
</p>
</details>

<details><summary> Validação Cruzada - Bloco 4 </summary> 
<p align = "justify"> Melhores Técnicas usadas no Dataset:
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/Valida%C3%A7%C3%A3o%20Cruzada.ipynb"> Bloco 4</a>
<br> - Validação Cruzada;
<br> - Árvore de Decisão;
<br> - Modelo K-NN.
</p>
</details>
  
<h5 align = "center"> Banco de Dados </h5>

<details><summary> dataset_dengue </summary>
<p align = "justify"> Dataset
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/dataset_dengue.xlsx"> Aqui! </a>
<br> - Data Mensal entre os anos de 1998 à 2014
<br> - Número de Casos Confirmados 
<br> - Temperatura Média, Mínima e Máxima
</p>
</details>
  
<details><summary> dataset_categorico </summary>
<p align = "justify"> Dataset Categórico
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/blob/main/dataset_dengue_categorico.xlsx"> Aqui! </a>
<br> - A categorização, é uma alteração no dataset feita internamente, porém necessária para outros processamentos, assim para o processo de desenvolvimento, este ficará separado por didática. No entanto, ao executar o código do Bloco 1 no seu computador, tal dataset é gerado automaticamente.
</p>
</details>

<h5 align = "center"> Diários de Bordo </h5>
  
<details><summary> DiarioAprendzMaquina </summary>
<p align = "justify"> Diários de Bordo:
  <a href="https://github.com/AnaLoponi/Machine_Learning_Casos_de_Dengue/tree/main/DiarioAprendzMaquina"> Desenvolvimento Semestral </a>

  </br>
  <br> Bloco 1:
<br> - 08_02
<br> - 08_09
<br> - 08_16
<br> - 08_23
  </br>
  <br> Bloco 2:
<br> - 08_30
<br> - 09_13
<br> - 09_20
  </br> 
  <br> Bloco 3:
<br> - 10_04
<br> - 10_25
<br> - 11_01
  </br>
  <br> Bloco 4:
<br> - 11_08
<br> - 11_22
<br> - 11_29
</p>
</details>
