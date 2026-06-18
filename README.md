Projeto de Análise de Dados da Pecuária Brasileira
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

Linguagem de programação utilizada para o desenvolvimento de todo o projeto. Sua simplicidade e ampla disponibilidade de bibliotecas tornam o Python uma das principais ferramentas para análise de dados e ciência de dados.

Pandas

Biblioteca utilizada para leitura, organização e manipulação dos dados. Permite importar arquivos CSV, criar tabelas (DataFrames), filtrar informações, realizar análises estatísticas e organizar os dados para visualização.

NumPy

Biblioteca voltada para computação numérica. Fornece suporte para operações matemáticas, cálculos estatísticos e manipulação eficiente de grandes conjuntos de dados.

Matplotlib

Biblioteca responsável pela criação de gráficos e visualizações. Foi utilizada para gerar gráficos de barras e outras representações visuais que auxiliam na interpretação dos dados da pecuária.

Folium

Biblioteca utilizada para criação de mapas interativos. Permite representar espacialmente os estados brasileiros, inserir marcadores geográficos e visualizar a distribuição do rebanho bovino em um mapa dinâmico.

OpenPyXL

Biblioteca utilizada para manipulação de arquivos Excel. Possibilita exportar tabelas, resultados e relatórios gerados durante as análises para planilhas no formato XLSX.

Jupyter Notebook

Ambiente interativo utilizado para desenvolver e executar o projeto. Permite combinar código, resultados, gráficos e documentação em um único arquivo, facilitando o aprendizado e a apresentação dos resultados.

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

Graduando em Agronomia

Licença

Projeto desenvolvido para fins acadêmicos e educacionais.