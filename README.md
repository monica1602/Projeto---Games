# Projeto Análise de Dados Games

## Descrição do Projeto
O projeto é sobre uma loja online, ICE, que vende videogames no mundo todo. A avaliações de usuários e especialistas, genêros, plataformas e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. O objetivo do projeto é identificar padrões que determinam se um jogo tem sucesso ou não. Isso permitiu identificar potenciais grandes vencedores e planejar campanhas publicitárias. 
Os dados disponíveis remontam a 2016. Vamos imaginar que estamos em dezembro de 2016 e precisamos planejar uma campanha para 2017

## As tarefas são:
- Preparação dos dados
- Modificação dos dados quando necessário: tipos de daos, nome de coluna, valores ausentes, valores duplicados
- Análise de dados: jogos lançados em anos diferentes, vendas por plataformas, quais dados são relevantes
- Criação de um perfil para cada região
- Conferir as hipóteses:
  - Hipótese 1: as classificações médias de usuários para as plataformas XBox One e PC são as mesmas
  - Hipótese 2: as classificações médias de usuários para os gêneros Ação e Esportes são diferentes

 ## Dicionário de dados
 - games.csv: dados sobre jogos
   - 'Name': nome
   - 'Platform': plataforma
   - 'Year_of_Release': ano de lançamento
   - 'Genre': gênero
   - 'NA_sales': vendas norte-americanas em milhões de USD
   - 'EU_sales': vendas na Europa em milhões de USD
   - 'JP_sales': vendas no Japão em milhões de USD
   - 'Other_sales': vendas em outros países em milhões de USD
   - 'Critic_Score': pontuação crítica
   - 'User_score': pontuação do usuário
   - 'Classificação: ESRB (Entertainment Software Rating Board)

  ## Ferramentas e Bibliotecas utilziadas
  - Pyhton: Linguagem principal utilizada para análise
  - Pandas: Biblioteca para manipulação e análise de dados
  - Matplotlib: Biblioteca para gerar gráficos
  - Numpy: Biblioteca que permite trabalhar com objetos multidimensionais, como matrizes e sequências
  - Math: Biblioteca que permite usar funções matemáticas
  - Seaborn: Biblioteca de visualização de dados baseada no Matplotlib
  - Scipy: Biblioteca que fornece uma manipulação conveniente e rápido de um array N-dimensional
  - Ploty.express: Biblioteca que permite criar visualizações rápidas e eficientes
  - Datetime: Biblioteca para manipulação de datas e horas

## Resultados 
- Muitos jogos recebem uma segunda edição
- Need for Speed Most Wanted, um jogo do gênero de corrida, liderou em termos de lançamentos em várias plataformas
- As plataformas PS2 e DS receberam a maioria dos jogos
- Os dados abrangem entre 1980 e 2016, com um pico de lançamentos em 2010
- Jogos dos gêneros Action e Sports receberam mais lançamentos
- Em termos de preferências de gêneros e plataformas, foi possível observar grandes diferenças entre os mercados da América do Norte, Japão e Europa
- A preferência do mercado japônes é por plataformas portáteis
- Os gêneros de Puzzle e Strategy são os menos lucrativos
- É possível observar o impacto das avaliações profissionais nas vendas
- Nem todas as regiões classificam jogos por faixa etária ou têm o hábito de avaliá-los
- As avaliações mais altas dados por profissionais são para jogos dos gêneros Shooter e Racing
- Houve um aumento grande no lançamento de jogos a partir de 1995
- Existe uma variação nas vendas totais entre as plataformas, necessitando com isso de uma estratégia personalizada para cada mercado
- Através do teste da hipótese 1, foi possível ver que as classificações médias dos usuários e as plataformas indicadas não são iguais
- Através do teste de hipótese 2, foi possível ver que as classificações médias dos usuários e os gêneros indicados não são diferentes

## Aprendizados
- Análise de dados
- Qualidade dos dados
- Tratar os dados modificando o tipo de dados, nome das colunas, valores ausentes, valores duplciados
- Pré-processamento de dados
- Contrução e análise de dados
- Análise de hipóteses

## Como executar o Projeto
- Clone o repositório
- Navegue até o duretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
