# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Olá! Este é o meu repositório do projeto de previsão de estoque usando o Amazon SageMaker Canvas. O objetivo deste projeto é mostrar como construir um modelo de Machine Learning sem a necessidade de programação, com foco na previsão de estoque para uma empresa. Estou feliz em compartilhar esta demonstração com você!

## 🚀 Sobre o Projeto

No âmbito deste projeto, explorei o Amazon SageMaker Canvas, uma plataforma de Machine Learning que facilita a criação de modelos preditivos de maneira visual e intuitiva. Uma grande vantagem é tornar o Machine Learning acessível a todos, possibilitando que pessoas sem experiência em programação possam desenvolver, treinar e implantar modelos de previsão de forma eficiente.

## 🎯 Objetivo

O foco principal deste projeto é antecipar as necessidades de estoque de uma empresa, auxiliando na formulação de estratégias para compras, armazenamento e distribuição de produtos. Com isso em mente, meu objetivo foi:

- Minimizar o excesso de estoque
- Prevenir escassez de produtos
- Aperfeiçoar a utilização do espaço de armazenamento
- Aumentar a eficiência operacional


## 🛠️ Tecnologias Utilizadas no Projeto

- **Amazon SageMaker Canvas**: Plataforma empregada para criação e treinamento do modelo preditivo.
- **Amazon S3**: Armazenamento de dados utilizado para guardar o dataset de treino e demais arquivos necessários.
- **Amazon QuickSight**: Ferramenta de visualização de dados utilizada para criar dashboards interativos com os resultados das previsões.


## 📊 Dataset

Os dados utilizados neste projeto incluem registros históricos de estoque, abrangendo:

- Identificação do Produto
- Data
- Quantidade Disponível em Estoque
- Vendas Diárias
- Reposições

Essas informações são fundamentais para analisar padrões de consumo e realizar previsões precisas da demanda futura de cada produto.


## 🔍 Etapas do Projeto

1. **Coleta de Dados**: Obtive os registros históricos de estoque da empresa.  
2. **Upload dos Dados**: Carreguei o conjunto de dados no Amazon S3.  
3. **Criação do Modelo**: Utilizei o SageMaker Canvas para importar e configurar os dados, além de construir o modelo de Machine Learning.  
4. **Treinamento do Modelo**: Realizei o treinamento do modelo utilizando os dados históricos para identificar padrões e tendências relevantes.  
5. **Avaliação do Modelo**: Avaliei a eficácia do modelo utilizando métricas de desempenho apropriadas.  
6. **Previsão**: Gerando previsões de estoque para períodos futuros utilizando o modo **Time Series Forecasting**.  
7. **Visualização dos Resultados**:  Utilizei o Amazon QuickSight para criar dashboards interativos e facilitar a interpretação dos insights obtidos.

## 📈 Análise de Previsões

Durante a avaliação do modelo, foram realizadas várias previsões de estoque com base nos dados históricos disponíveis. Aqui estão alguns exemplos dessas previsões:

1. **Produto A**: Identificamos um aumento na demanda prevista para o próximo mês, sugerindo ajustes no reabastecimento para evitar possíveis faltas de estoque.  
2. **Produto B**: Detectamos um padrão sazonal nas vendas, permitindo uma previsão precisa para o período de pico de vendas no final do ano.  
3. **Produto C**: Observamos uma redução no estoque médio necessário, indicando oportunidades para otimizar a gestão de inventário e reduzir custos operacionais.  

Cada uma dessas previsões foi realizada utilizando o modelo treinado no Amazon SageMaker Canvas, com base em análises detalhadas e métricas de avaliação para garantir a confiabilidade das recomendações.  
