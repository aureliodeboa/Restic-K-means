# 🔍 Análise e Clusterização de Dados com K-means, PCA e t-SNE
## 🎯 Objetivo do Projeto
O objetivo deste projeto é explorar e analisar um conjunto de dados de alta dimensionalidade utilizando técnicas de clusterização e redução dimensional. A proposta inclui a identificação de padrões ou grupos presentes nos dados através de algoritmos como Clusterização Hierárquica, K-Means, PCA (Análise de Componentes Principais) e t-SNE, buscando entender melhor a estrutura dos dados e a separação entre os clusters.

### ✍️ Instruções para Executar o Código
Para reproduzir o projeto, siga os passos abaixo:

### 👨‍💻 Execução do Código:

- Baixe o arquivo "Atividade2Restic.ipynb" do projeto e abra-o no Google Colab.
- Execute as células na sequência em que estão dispostas no notebook.

### 📐 Ajuste de Parâmetros:

Caso necessário, ajuste os parâmetros de clusterização, como o número de clusters no K-Means ou o valor de perplexity no t-SNE, para testar diferentes cenários.

### 📊 Visualização dos Resultados:

O código gera gráficos e métricas que ajudam a interpretar a estrutura dos dados e a qualidade dos clusters identificados.

## 📑 Principais Conclusões e Considerações sobre os Resultados Obtidos

### 📈 Clusterização Hierárquica e Determinação de Clusters:

A análise visual do dendrograma sugeriu que 3 clusters representavam bem a estrutura dos dados.

### 📉 Redução Dimensional (PCA e t-SNE):

O PCA revelou que 60% da variância dos dados pode ser explicada pelos três primeiros componentes principais.
A aplicação do t-SNE possibilitou uma visualização mais detalhada em dimensões reduzidas, facilitando a análise visual da separação entre os clusters.

### 🧾 Resultados do K-Means:

O algoritmo K-Means mostrou uma boa separação visual dos clusters, mas o baixo valor de Silhouette Score e a alta Inércia sugerem que alguns pontos estão mal posicionados ou em zonas de transição entre clusters.

### 📝 Limitações e Sugestões Futuras:

A alta dimensionalidade dos dados e a presença de correlações entre variáveis podem ter influenciado a qualidade dos clusters.
Testar outros algoritmos de clusterização, como DBSCAN ou Gaussian Mixture Models, pode trazer resultados complementares.
Investigar a viabilidade de incluir mais variáveis ou ajustar a forma como os dados foram processados pode ajudar na obtenção de clusters mais bem definidos.

### 👥 Autores  

- 🎯 **Andressa**   
  - 🐙 [GitHub](https://github.com/xndrxssx)
- 🎯 **Aurélio**   
  - 🐙 [GitHub](https://github.com/aureliodeboa)
