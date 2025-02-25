# Projeto Análise de Dados - Games

## Descrição do Projeto
Este projeto envolve a análise de dados históricos de vendas de jogos da loja online ICE, especializada na venda de videogames globalmente. O objetivo principal é identificar padrões de sucesso nos jogos, utilizando informações como avaliações de usuários e especialistas, gêneros, plataformas e dados de vendas passadas, para prever quais jogos têm maior potencial de sucesso.
O projeto considera dados de 2016 e visa ajudar a loja a planejar campanhas publicitárias eficazes para o ano de 2017. Um dos atributos importantes nos dados é a classificação ESRB (Entertainment Software Rating Board), que atribui uma classificação etária aos jogos, como "Teen" (adolescente) ou "Mature" (adulto), influenciando o público-alvo e as estratégias de marketing.
O processo envolverá a análise dos dados para determinar fatores que podem indicar o sucesso de um jogo, como gênero, plataforma, avaliações e a relação entre essas variáveis.

## As tarefas são:
- Preparação dos dados: Consiste no processo de organização e limpeza dos dados antes de serem analisados, garantindo que estejam em um formato adequado para análise e modelagem. Isso inclui a remoção de valores ausentes, correção de tipos de dados e ajustes nos nomes das colunas.
- Modificação dos dados quando necessário: Ajustes nas colunas para garantir que os dados estejam corretos, como a conversão de tipos de dados (por exemplo, de string para numérico), padronização de nomes de colunas e tratamento de valores ausentes ou duplicados, para evitar distorções na análise.
- Análise de dados:
  - Analisar jogos lançados em anos diferentes para identificar tendências de vendas ao longo do tempo.
  - Estudar vendas por plataformas para entender quais são as mais populares e rentáveis.
  - Determinar quais dados são relevantes para o sucesso de um jogo, como gênero, plataforma, e a relação com a classificação ESRB.
  - Criação de um perfil para cada região: Analisar as preferências e comportamentos de compra por região, considerando fatores como popularidade de determinados jogos, gêneros preferidos e plataformas predominantes.
- Conferir as hipóteses:
  - Hipótese 1: As classificações médias de usuários para as plataformas Xbox One e PC são as mesmas. Para testar essa hipótese, pode-se realizar um teste de hipóteses comparando as médias das avaliações dos usuários para ambas as plataformas.
  - Hipótese 2: As classificações médias de usuários para os gêneros Ação e Esportes são diferentes. Um teste de hipótese será conduzido para verificar se há uma diferença estatisticamente significativa entre as classificações médias desses gêneros.

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
- Python: Linguagem principal utilizada para análise de dados, com uma vasta gama de bibliotecas e recursos que permitem realizar manipulação, visualização e modelagem de dados de maneira eficiente.
- Pandas: Biblioteca fundamental para manipulação e análise de dados, proporcionando estruturas de dados flexíveis como o DataFrame, essenciais para o tratamento de grandes volumes de dados.
- Matplotlib: Biblioteca poderosa para geração de gráficos estáticos, oferecendo uma ampla gama de opções para criação de visualizações customizáveis.
- NumPy: Biblioteca que simplifica o manuseio de vetores e matrizes, acelerando cálculos matemáticos e estatísticos nos dados.
- Math: Biblioteca que oferece funções matemáticas básicas, como operações de álgebra e trigonometria, essenciais para realizar cálculos e análises numéricas.
- Seaborn: Biblioteca de visualização de dados baseada no Matplotlib, especializada em gráficos estatísticos mais sofisticados e com uma interface mais amigável, ideal para análise exploratória de dados.
- SciPy: Biblioteca que disponibiliza recursos avançados para análise e processamento de matrizes N-dimensionais, incluindo funções matemáticas, estatísticas e de álgebra linear.
- Plotly Express: Biblioteca para criação de visualizações rápidas, interativas e eficientes, que permite explorar os dados de forma dinâmica com gráficos de alta qualidade.
- Datetime: Biblioteca especializada no tratamento de datas e horários, permitindo a conversão, edição e análise temporal em conjuntos de dados.

## Imagens

### Tabela de dados
<img src="https://github.com/user-attachments/assets/97eae905-e07e-482d-8491-c041ddaaf2d6" alt="Projeto 6" width="1000"/>

### Gráfico - Quantidade de jogos lançados por ano
<img src="https://github.com/user-attachments/assets/0a3ef072-cdc1-4cbb-8de4-032600f20cf4" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de jogos por plataforma
<img src="https://github.com/user-attachments/assets/0232cce5-ca70-4ce5-a48e-cb425444832e" alt="Projeto 6" wodth="200"/>

### Gráfico - Quantidade de vendas por ano por plataforma (3DS)
<img src="https://github.com/user-attachments/assets/b3c62f48-26f9-462f-aa41-93489742cf33" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (DS)
<img src="https://github.com/user-attachments/assets/f52f5947-4d20-4079-8921-4e0f4e5a5401" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (PC)
<img src="https://github.com/user-attachments/assets/2453305c-aec9-46c5-9466-9ecd2c03df53" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (PS3)
<img src="https://github.com/user-attachments/assets/b434a358-f873-415d-9ff5-734ca94bd6b2" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (PS4)
<img src="https://github.com/user-attachments/assets/61432a3e-f763-4a8d-a72b-ff906f4237ac" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (PSP)
<img src="https://github.com/user-attachments/assets/f6fb8ac8-3ba9-42a7-9eb8-335cdfda2332" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano po plataforma (PSV)
<img src="https://github.com/user-attachments/assets/50e58f5d-deb5-4b27-b4fe-f2ad687be290" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (Wii)
<img src="https://github.com/user-attachments/assets/e37e5bae-7404-4c3a-bd5c-13464017c709" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (WiiU)
<img src="https://github.com/user-attachments/assets/1c291d62-8b39-43ba-a33b-32f84e24e99f" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (X360)
<img src="https://github.com/user-attachments/assets/dd45101b-c4e4-46cf-92c5-ca7571326f6a" alt="Projeto 6" width="800"/>

### Gráfico - Quantidade de vendas por ano por plataforma (XOne)
<img src="https://github.com/user-attachments/assets/92b243e6-ac4f-4c6b-8352-4a631cf27c60" alt="Projeto 6" width="800"/>

### Gráfico - Diagrama de caixa das vendas globais de jogos por plataforma e total de vendas
<img src="https://github.com/user-attachments/assets/895072f9-fa63-490a-94d8-96c20dac0757" alt="Projeto 6" width="800"/>

### Código - Perfil por plataforma (NA)
<img src="https://github.com/user-attachments/assets/468b31a3-d5f0-4446-a094-b7eb4a3f7ecb" alt="Projeto 6" width="1000"/>

### Código - Perfil por plataforma (EU)
<img src="https://github.com/user-attachments/assets/462a55b7-2c70-40e7-8846-b06e871896d7" alt="Projeto 6" width="1000"/>

### Código - Perfil por plataforma (JP)
<img src="https://github.com/user-attachments/assets/954fee45-1985-409d-9cdb-49a1f77dcc90" alt="Projeto 6" width="1000"/>

### Código - Hipótese 1
<img src="https://github.com/user-attachments/assets/7eb5a1e5-53fa-4999-9e46-40bc55510a1a" alt="Projeto 6" width="1000"/>

### Código - Hipótese 2
<img src="https://github.com/user-attachments/assets/9609fbbc-a7cc-4b9a-ba6d-1399c33f8aa4" alt="Projeto 6" width="1000"/>

## Resultados 
- Edições de jogos: Muitos jogos recebem uma segunda edição, indicando uma tendência de continuidade e popularidade, além de um possível aumento de vendas com o lançamento de versões subsequentes.
- Need for Speed Most Wanted: Esse jogo, do gênero corrida, se destacou por liderar os lançamentos em várias plataformas, mostrando que a franquia foi um grande sucesso em diversos mercados.
- Plataformas PS2 e DS: Estas plataformas receberam a maior quantidade de jogos, indicando que foram as mais populares durante um período considerável de tempo.
- Período de lançamentos (1980-2016): A análise dos dados mostra um pico de lançamentos em 2010, sugerindo um momento de grande atividade na indústria de videogames.
- Gêneros mais populares: Action e Sports foram os gêneros mais lançados, refletindo uma forte preferência do público por esses tipos de jogos.
- Diferenças de preferências entre mercados: Observou-se grandes diferenças nas preferências de gêneros e plataformas entre as regiões da América do Norte, Japão e Europa, o que demanda estratégias personalizadas de marketing e lançamento.
- Mercado japonês: A preferência do mercado japonês recai sobre plataformas portáteis, o que é uma característica distinta em relação a outros mercados.
- Gêneros menos lucrativos: Puzzle e Strategy foram identificados como os gêneros com menor rentabilidade, sugerindo que jogos desses tipos não atraem tantos consumidores quanto outros gêneros.
- Impacto das avaliações profissionais nas vendas: É possível observar que as avaliações dos críticos têm um impacto direto nas vendas dos jogos, com jogos bem avaliados obtendo um desempenho superior no mercado.
- Classificação por faixa etária: Nem todas as regiões possuem o hábito de classificar jogos por faixa etária ou de fornecer avaliações profissionais, o que pode afetar o comportamento de compra e a estratégia de marketing para jogos.
- Gêneros mais bem avaliados: Shooter e Racing foram os gêneros com as avaliações mais altas por parte dos críticos, indicando um maior reconhecimento e aprovação desses tipos de jogos.
- Aumento de lançamentos após 1995: A partir de 1995, houve um aumento considerável no número de lançamentos de jogos, o que pode ser associado ao crescimento e popularização dos videogames.
- Variação nas vendas por plataforma: As vendas totais de jogos variam significativamente entre plataformas, o que demanda uma estratégia personalizada de marketing para cada mercado.
- Teste de hipótese 1: O teste de hipótese 1 indicou que as classificações médias dos usuários para plataformas como Xbox One e PC são diferentes, sugerindo que as preferências variam de acordo com a plataforma.
- Teste de hipótese 2: O teste de hipótese 2 revelou que as classificações médias para os gêneros Ação e Esportes não apresentam diferenças significativas, indicando que, em termos de avaliação de usuários, esses gêneros são igualmente apreciados.

## Aprendizados
- Análise de dados: Envolve a inspeção detalhada dos dados coletados para entender padrões, tendências e características importantes, além de realizar a exploração inicial para detectar insights relevantes.
- Qualidade dos dados: Refere-se à avaliação e melhoria da precisão, consistência, completude e confiabilidade dos dados, garantindo que as informações estejam aptas para análise.
- Tratamento dos dados: Inclui a modificação do tipo de dados, alteração de nomes de colunas, e a limpeza de valores ausentes ou duplicados para assegurar a integridade do conjunto de dados.
- Pré-processamento de dados: Envolve a preparação dos dados para análise, como a transformação de dados brutos em formatos utilizáveis, normalização, padronização e outras etapas necessárias para o uso eficaz das informações.
- Construção e análise de dados: Envolve a criação de modelos, visualizações e gráficos para compreender e representar as informações, auxiliando na descoberta de padrões e percepções.
- Análise de hipóteses: Envolve a formulação de hipóteses de pesquisa, seguida pela realização de testes estatísticos para determinar se há evidências suficientes para apoiar ou refutar essas hipóteses.

## Contexto real
- Novas lojas online: Para entender o comportamento de consumo e como as campanhas publicitárias podem ser ajustadas de acordo com o perfil do cliente.
- Lojas físicas que desejam criar lojas online: Para identificar padrões de sucesso e adaptar estratégias de vendas e marketing para o mundo digital.
- Lojas online que desejam entender melhor o comportamento de seus usuários: A análise pode ajudar a mapear os gostos dos clientes, ajustar ofertas e otimizar a experiência de compra.
- Empresas que buscam compreender as vendas de seus produtos ao longo dos anos e em diferentes regiões: A análise histórica dos dados pode revelar tendências sazonais e regionais, possibilitando a adaptação estratégica da oferta de produtos.
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o duretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
