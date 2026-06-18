# Projeto_3Projeto de Análise de Dados da Pecuária Brasileira
Descrição

Este projeto foi desenvolvido em Python com o objetivo de realizar análises de dados da pecuária bovina brasileira, utilizando técnicas de ciência de dados e visualização geográfica. O sistema permite analisar informações sobre o rebanho bovino por estado, gerar estatísticas descritivas, criar rankings e visualizar os dados em um mapa interativo.

Objetivos
Analisar dados do rebanho bovino brasileiro.
Gerar estatísticas descritivas dos dados.
Criar rankings dos estados com maior rebanho bovino.
Produzir gráficos para visualização dos resultados.
Exibir informações geográficas em mapas interativos.
Aplicar conceitos de análise de dados utilizando Python.
Tecnologias Utilizadas
Python 3
Pandas
NumPy
Matplotlib
Folium
OpenPyXL
Jupyter Notebook
Estrutura do Projeto
ProjetoPecuaria/
│
├── pecuaria_estados.csv
├── pecuaria_mapa.ipynb
├── mapa_pecuaria.html
├── README.md
└── .venv/
Instalação
Criar ambiente virtual
python -m venv .venv
Ativar ambiente virtual
Windows (CMD)
.venv\Scripts\activate
Instalar dependências
pip install pandas numpy matplotlib folium openpyxl jupyter notebook
Base de Dados

O arquivo pecuaria_estados.csv contém informações dos principais estados produtores de bovinos no Brasil, incluindo:

Estado
Latitude
Longitude
Rebanho bovino
Funcionalidades
Análise Estatística
Média do rebanho bovino.
Valor mínimo e máximo.
Desvio padrão.
Quartis.
Ranking de Estados

Ordenação dos estados de acordo com o tamanho do rebanho bovino.

Visualização Gráfica

Geração de gráficos de barras para comparação entre estados.

Mapa Interativo

Visualização geográfica dos estados com marcadores proporcionais ao tamanho do rebanho.

Exemplo de Saída

O sistema apresenta:

Tabela dos dados carregados.
Estatísticas descritivas.
Ranking dos estados.
Gráfico de barras.
Mapa interativo.
Possíveis Melhorias
Integração com dados oficiais do IBGE.
Atualização automática das bases de dados.
Dashboard interativo.
Comparação entre diferentes tipos de rebanhos.
Análises temporais e previsões.
Autor

Gustavo Mendonça Ferreira

Licença

Projeto desenvolvido para fins acadêmicos e educacionais.