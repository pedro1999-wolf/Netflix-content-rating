#📊 Análise de Dados e Boas Práticas: Classificação de Conteúdo da Netflix
Este repositório contém um projeto de análise de dados sobre a classificação de conteúdo da Netflix, abordando técnicas de pré-processamento, visualização de dados e boas práticas de análise.

##🚀 Objetivo do Projeto
O principal objetivo deste projeto é explorar a classificação de conteúdo da Netflix e identificar padrões entre diferentes faixas etárias e regiões. Para isso, utilizamos técnicas de ciência de dados para limpar, organizar e visualizar os dados, extraindo insights relevantes sobre o catálogo da Netflix.

##🛠️ Tecnologias e Ferramentas Utilizadas
Linguagem: Python
Bibliotecas principais:
pandas → Manipulação e análise de dados
matplotlib e seaborn → Visualização de dados
numpy → Operações matemáticas e estatísticas
sklearn → Pré-processamento de dados
Jupyter Notebook → Desenvolvimento e execução dos códigos

##📦 Netflix-content-rating  
 ┣ 📜 MVP_Análise_de_dados_e_boas_práticas.ipynb   # Notebook principal com toda a análise  
 ┣ 📜 dataset.csv  # Conjunto de dados utilizado na análise  
 ┣ 📜 README.md  # Documento atual explicando o projeto  
 ┗ 📜 requirements.txt  # Bibliotecas necessárias para rodar o projeto  

##📊 Metodologia
###Coleta e limpeza de dados

###Leitura e tratamento do dataset
Remoção de valores ausentes
Ajuste de tipos de dados
Análise Exploratória de Dados (EDA)

###Estatísticas descritivas
Distribuições e padrões da classificação de conteúdo
Comparação entre diferentes faixas etárias
Visualização de Dados

###Gráficos para identificar padrões
Comparação entre classificações etárias por região
Conclusões

###Principais achados da análise
Insights sobre a classificação etária do catálogo da Netflix

##🔧 Como Rodar o Projeto

###📥 1. Clone o repositório
git clone https://github.com/pedro1999-wolf/Netflix-content-rating.git
cd Netflix-content-rating

###🛠️ 2. Crie um ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

###📦 3. Instale as dependências
pip install -r requirements.txt

###▶️ 4. Execute o Jupyter Notebook
jupyter notebook
Abra o arquivo MVP_Análise_de_dados_e_boas_práticas.ipynb e execute as células.

##📈 Resultados e Insights
A maioria dos conteúdos da Netflix são voltados para o público jovem-adulto.
Existe uma grande variação na classificação etária entre países devido a normas culturais.
O gênero de um filme/série influencia diretamente sua classificação indicativa.

##📌 Possíveis Melhorias
Expansão da análise para outros serviços de streaming.
Aplicação de modelos preditivos para prever a classificação etária de novos conteúdos.
