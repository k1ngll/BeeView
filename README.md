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

⚙️ Funcionamento da Aplicação
Funcionalidades Principais:
Autenticação Segura: Login e registro de usuários com validação de entrada e feedback visual.

Design Moderno: Interface de usuário construída com CustomTkinter, apresentando elementos gráficos personalizados como hexágonos de fundo interativos na tela de login.

Análise Facial (Módulo Principal): Um aplicativo independente para processamento e análise de dados faciais, sugerindo o uso de algoritmos de visão computacional.

Estrutura Modular: Código bem organizado em módulos para facilitar a manutenção e escalabilidade.

Estrutura de Arquivos
A organização do projeto segue uma estrutura lógica para separar componentes da UI, módulos de lógica de negócio, dados e recursos visuais.

BEEVIEW - APLICATIVO DEFINITIVO/
├── contents/
│   ├── dataset/
│   │   └── Dataset_ADD.csv      # Exemplo de dataset para análise.
│   ├── icons/                   # Contém ícones da aplicação.
│   ├── images/                  # Contém outras imagens da aplicação.
│   └── modules/
│       ├── __pycache__/         # Cache de módulos Python.
│       ├── __init__.py          # Inicialização do pacote modules.
│       ├── homepage_model.py    # Lógica ou modelo para a página inicial (ainda não implementado na UI).
│       ├── login_page.py        # Implementação da tela de Login.
│       ├── registration_page.py # Implementação da tela de Registro.
│       └── standalone_search_app.py # Aplicação principal de análise facial.
├── face_app.py                  # Orquestra as diferentes telas da aplicação.
└── users_data.json              # Armazenamento (simulado) de dados de usuários.

Como Executar
Para rodar a aplicação BeeView em sua máquina, siga os passos abaixo:

Pré-requisitos
Certifique-se de ter o Python instalado (versão 3.x recomendada).

Você precisará instalar as bibliotecas necessárias:

pip install customtkinter

Passos para Executar
Clone o Repositório (se estiver em um sistema de controle de versão) ou faça o download de todos os arquivos.

Navegue até o Diretório Principal: Abra seu terminal ou prompt de comando e navegue até a pasta BEEVIEW - APLICATIVO DEFINITIVO/.

cd "BEEVIEW - APLICATIVO DEFINITIVO"

Execute o Aplicativo Principal:

python face_app.py

Isso iniciará a janela principal do BeeView, apresentando a tela de Login.

Detalhes das Telas
1. Tela de Login (login_page.py)
A tela de login é a porta de entrada para a aplicação, com um design moderno e elementos interativos.

Campos: Email, Senha.

Opções: Checkbox "Manter conectado", link "Esqueceu a senha?".

Ações: Botão "Entrar" para autenticação, link "Faça sua conta aqui" para redirecionar à tela de registro.

Feedback: Exibe mensagens de erro (e sucesso, em testes) para o usuário.

Animação: Possui hexágonos de fundo que interagem visualmente ao passar o mouse.

Mock de Login:
Para testar, você pode usar as seguintes credenciais (conforme o bloco if __name__ == "__main__": em login_page.py):

Email: test@example.com

Senha: 123

2. Tela de Registro (registration_page.py)
A tela de registro permite que novos usuários criem uma conta.

Campos: Email, Senha, Repetir Senha, Data de Nascimento (Dia, Mês, Ano via CTkOptionMenu).

Opções: Checkbox "Aceite os Termos".

Ações: Botão "Registrar" para submeter o registro, link "← Voltar pra tela de login".

Validação: Realiza validações básicas (campos preenchidos, senhas coincidentes, comprimento da senha, termos aceitos, e data de nascimento completa).

Feedback: Exibe mensagens de sucesso ou erro.

Mock de Registro:
Conforme o bloco if __name__ == "__main__": em registration_page.py:

Um email deve terminar com @example.com.

O email registered@example.com já está "registrado" para fins de teste.

3. Aplicação Principal / Análise Facial (standalone_search_app.py)
Este é o módulo central da aplicação após o login. Embora o código completo não tenha sido fornecido para esta parte, a nomenclatura sugere que ela lida com:

Pesquisa: Funcionalidades de busca.

Análise Facial: Interação com um modelo ou dataset (Dataset_ADD.csv) para operações relacionadas a reconhecimento ou análise de faces.

Independência: O nome "standalone" implica que pode ser executado separadamente para testes ou uso específico, mas é parte integrante do fluxo principal do face_app.py.

Desenvolvimento
Bibliotecas Utilizadas
customtkinter: Para a construção da interface gráfica do usuário.

datetime: Para manipulação de datas (usado na tela de registro).

Notas para Desenvolvedores
Callbacks: As telas de Login e Registro utilizam callbacks para comunicar eventos (tentativas de login/registro, troca de tela) de volta ao face_app.py, garantindo uma arquitetura limpa.

Estilo: Constantes de estilo (PRIMARY_YELLOW, TEXT_COLOR_LIGHT, etc.) são definidas em cada classe de página para manter a consistência visual.

Responsividade: O uso de grid_columnconfigure e grid_rowconfigure com weight e uniform ajuda na responsividade da interface.

Armazenamento de Usuários: Atualmente, users_data.json parece ser usado para um armazenamento muito básico (ou simulado) de usuários. Para uma aplicação real, considere um banco de dados adequado.
