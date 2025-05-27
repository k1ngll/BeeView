BeeView: Desvendando o Oscar e o Cenário Cinematográfico Global
🚀 Sobre o Projeto
O BeeView é um projeto de Big Data dedicado a explorar e analisar o vasto universo dos filmes, com um foco especial na performance do cinema brasileiro no Oscar. Nosso objetivo é ir além dos dados brutos e entender as nuances que impactam o reconhecimento internacional, utilizando uma abordagem de análise de dados robusta e multifacetada.

🎯 Justificativa da Escolha do Tema
Escolhemos o tema "Filmes" pela sua imensa relevância cultural, social e econômica. O cinema não apenas reflete, mas também molda o imaginário coletivo, abordando desde questões históricas até tendências contemporâneas. Essa ubiquidade e impacto tornam os filmes um campo de estudo dinâmico e rico. Além disso, a paixão da equipe pela sétima arte foi um fator motivador para essa exploração aprofundada.

📊 Bases de Dados Utilizadas
Para realizar este trabalho, empregamos uma variedade de bases de dados abrangentes e ricas em informações sobre o universo cinematográfico:

The Movie Database (TMDB): Uma vasta base de dados colaborativa de filmes, programas de TV e celebridades, acessada via API oficial.

IMDb Datasets: Contém dados de filmes, séries, elencos e equipes do Internet Movie Database (IMDb), adquiridos por download direto.

Rotten Tomatoes: Oferece informações sobre filmes, incluindo críticas de críticos e do público, com coleta de dados realizada via web scraping para informações complementares (rottentomatoes.com).

Kaggle - Full TMDB Movies Dataset 2024 (1M Movies): Um abrangente dataset consolidado com mais de um milhão de filmes do TMDB, incluindo metadados detalhados, elenco, equipe técnica, gêneros, orçamentos, receitas e popularidade. Sua vasta dimensão permitiu análises mais robustas e a identificação de padrões em larga escala (Kaggle Dataset).

AdoroCinema: Utilizado para informações gerais sobre filmes, lançamentos e avaliações no contexto brasileiro, com coleta de dados pontual para filmes específicos (adorocinema.com).

Wikipedia (versão em português): Fonte para contexto de premiações (como o Oscar de Melhor Filme Estrangeiro) e informações gerais sobre filmes e personalidades (pt.wikipedia.org/wiki/Oscar_de_melhor_filme_internacional).

Papo de Cinema: Site de notícias e críticas de cinema brasileiro, utilizado para análises complementares.

G1 (Globo): Cobertura de notícias sobre o Oscar e filmes de destaque em festivais.

Mídia Internacional (The Hollywood Reporter, Variety, Le Monde, Libération): Fontes para cobertura detalhada de festivais (como Cannes) e notícias do Oscar.

🛠️ Tecnologias e Ferramentas Aplicadas
Para o desenvolvimento e a análise deste projeto, utilizamos as seguintes tecnologias e ferramentas:

Linguagem de Programação: Python (versão 3.9)

Bibliotecas Python para Análise de Dados:

Pandas: Manipulação e análise de dados tabulares.

NumPy: Suporte a operações numéricas.

Matplotlib e Seaborn: Visualização de dados.

Ambiente de Desenvolvimento: Google Colab

Versionamento de Código: Git

Hospedagem de Repositório: GitHub

🌐 Metodologia Utilizada
A metodologia empregada seguiu um pipeline de dados estruturado e iterativo para garantir a robustez e a confiabilidade das análises:

Coleta e Aquisição de Dados: Dados foram coletados de diversas fontes, com destaque para a API do TMDB e downloads diretos de IMDb e Kaggle.

Pré-processamento e Limpeza de Dados: Rigoroso processo para garantir qualidade e consistência, incluindo tratamento de valores ausentes, remoção de duplicatas, padronização e consolidação de diferentes fontes. A escala do dataset do Kaggle exigiu técnicas otimizadas para grandes volumes.

Análise Exploratória de Dados (EDA): Etapa fundamental para compreender a estrutura, tendências e padrões, utilizando estatísticas descritivas e visualizações.

Engenharia de Features: Criação de novas variáveis e transformação das existentes para potencializar a capacidade preditiva dos modelos, como features temporais e proporções.

Modelagem e Análise: Definição do problema, seleção de modelos, divisão de dados, treinamento e avaliação. Análises de correlação e testes de hipótese foram utilizados para quantificar relações e comparar grupos.

