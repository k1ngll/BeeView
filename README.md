BeeView: Análise de Dados no Universo Cinematográfico
📖 Sobre o Projeto
BeeView é um projeto de análise de dados que investiga o universo do cinema sob duas perspetivas principais:

Análise Estratégica de Franquias: Uma investigação comparativa entre os mercados do Brasil e dos EUA para responder à pergunta: "Vale a pena fazer uma sequência?".

Análise de Competitividade: Uma avaliação do desempenho e dos desafios do cinema brasileiro na categoria de Melhor Filme Internacional do Oscar.

Este projeto foi motivado pela relevância cultural e económica do cinema e pela paixão da equipa pela sétima arte, com o objetivo de extrair insights valiosos através da análise de dados.

🚀 Tecnologias e Ferramentas Utilizadas
Este projeto foi desenvolvido utilizando o seguinte conjunto de tecnologias:

Linguagem de Programação: Python (3.9)

Bibliotecas de Análise: Pandas, NumPy

Bibliotecas de Visualização: Matplotlib, Seaborn

Coleta de Dados: Requests (para APIs), Web Scraping

Ambiente de Desenvolvimento: Google Colab

Versionamento: Git & GitHub

📂 Estrutura do Repositório
A organização das pastas e ficheiros dentro deste repositório segue a estrutura abaixo:

/beeview - app/                   # Contém a aplicação em Python e Tkinter
/beeview notebooks/               # Contém os notebooks e datasets principais
    /analise franquia/
        /datasets/                # Contém os datasets usados para a análise de franquias
        /resultado/               # Contém o ficheiro Excel com o resultado da análise
        02_analise_Franquia.ipynb # Notebook com a análise de franquias
    /analise oscar/
        /datasets/                # Contém os datasets usados para a análise do Oscar
        01_analise de dados_Oscar.ipynb # Notebook com a análise do Oscar
/documentação/                    # Contém a documentação técnica detalhada
/readme.md                        # Este ficheiro

🛠️ Instruções de Execução
Para replicar a análise, siga os passos abaixo:

1. Pré-requisitos:

Python 3.9 ou superior.

Acesso a um ambiente que suporte Jupyter Notebooks (como o Google Colab ou uma instalação local).

2. Instalação de Dependências:
Clone o repositório e instale os pacotes necessários. Recomenda-se criar um ambiente virtual.

pip install pandas numpy matplotlib seaborn requests openpyxl streamlit tkinter

3. Execução da Análise:
A análise principal está contida nos Jupyter Notebooks (.ipynb) localizados nas pastas /beeview notebooks/analise franquia/ e /beeview notebooks/analise oscar/. Abra os notebooks e execute as células sequencialmente. Certifique-se de que os caminhos para os datasets estão corretos.

4. Execução da Aplicação:
A aplicação em Tkinter pode ser executada a partir da pasta /beeview - app/.

👥 Equipa
Este projeto foi desenvolvido por:

Christian Oliveira Jorge Moreira 

Rafaela de Jesus Soares

Uiles dos Santos

Maria Eduarda Dias Alves da Silva

Antonio Carlos Sena da Conceição Junior
