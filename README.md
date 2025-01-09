# Projeto Análise de Dados Games

## Descrição do Projeto
O projeto é sobre uma loja online, ICE, que vende videogames no mundo todo. A avaliações de usuários e especialistas, genêros, plataformas e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. O objetivo do projeto é identificar padrões que determinam se um jogo tem sucesso ou não. Isso permitiu identificar potenciais grandes vencedores e planejar campanhas publicitárias. 
Os dados disponíveis remontam a 2016. Vamos imaginar que estamos em dezembro de 2016 e precisamos planejar uma campanha para 2017.
O conjunto de dados contém  uma coluna de "rating" (classificação) que armazena a classificação ESRB de cada jogo. O Entertainment Software Rating Board avalia o contéudo de um jogo e atribui uma classificação etária, como Teen (adolescente) ou Mature (adulto).

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

## Imagens

### Tabela de dados
<img src="https://github.com/user-attachments/assets/97eae905-e07e-482d-8491-c041ddaaf2d6" alt="Projeto 6" width="200"/>

### Quantidade de jogos lançados por ano
<img src="https://github.com/user-attachments/assets/0a3ef072-cdc1-4cbb-8de4-032600f20cf4" alt="Projeto 6" width="200"/>

### Quantidade de jogos por plataforma
<img src="https://github.com/user-attachments/assets/0232cce5-ca70-4ce5-a48e-cb425444832e" alt="Projeto 6" wodth="200"/>

### Quantidade de vendas por ano por plataforma (3DS)
<img src="https://github.com/user-attachments/assets/b3c62f48-26f9-462f-aa41-93489742cf33" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (DS)
<img src="https://github.com/user-attachments/assets/f52f5947-4d20-4079-8921-4e0f4e5a5401" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (PC)
<img src="https://github.com/user-attachments/assets/2453305c-aec9-46c5-9466-9ecd2c03df53" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (PS3)
<img src="https://github.com/user-attachments/assets/b434a358-f873-415d-9ff5-734ca94bd6b2" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (PS4)
<img src="https://github.com/user-attachments/assets/61432a3e-f763-4a8d-a72b-ff906f4237ac" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (PSP)
<img src="https://github.com/user-attachments/assets/f6fb8ac8-3ba9-42a7-9eb8-335cdfda2332" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano po plataforma (PSV)
<img src="https://github.com/user-attachments/assets/50e58f5d-deb5-4b27-b4fe-f2ad687be290" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (Wii)
<img src="https://github.com/user-attachments/assets/e37e5bae-7404-4c3a-bd5c-13464017c709" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (WiiU)
<img src="https://github.com/user-attachments/assets/1c291d62-8b39-43ba-a33b-32f84e24e99f" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (X360)
<img src="https://github.com/user-attachments/assets/dd45101b-c4e4-46cf-92c5-ca7571326f6a" alt="Projeto 6" width="200"/>

### Quantidade de vendas por ano por plataforma (XOne)
<img src="https://github.com/user-attachments/assets/92b243e6-ac4f-4c6b-8352-4a631cf27c60" alt="Projeto 6" width="200"/>

### Diagrama de caixa das vendas globais de jogos por plataforma e total de vendas
<img src="https://github.com/user-attachments/assets/895072f9-fa63-490a-94d8-96c20dac0757" alt="Projeto 6" width="200"/>

### Perfil por plataforma (NA)
<img src="https://github.com/user-attachments/assets/468b31a3-d5f0-4446-a094-b7eb4a3f7ecb" alt="Projeto 6" width="200"/>

### Perfil por plataforma (EU)
<img src="https://github.com/user-attachments/assets/462a55b7-2c70-40e7-8846-b06e871896d7" alt="Projeto 6" width="200"/>

### Perfil por plataforma (JP)
<img src="https://github.com/user-attachments/assets/954fee45-1985-409d-9cdb-49a1f77dcc90" alt="Projeto 6" width="200"/>

### Hipótese 1
<img src="https://github.com/user-attachments/assets/7eb5a1e5-53fa-4999-9e46-40bc55510a1a" alt="Projeto 6" width="200"/>

### Hipótese 2
<img src="https://github.com/user-attachments/assets/9609fbbc-a7cc-4b9a-ba6d-1399c33f8aa4" alt="Projeto 6" width="200"/>

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

## Contexto real
- Novas lojas online
- Lojas físicas qie desejam criar lojas online
- Lojas online que desejam entender melhor o comportamento de seus usuários
- Empresas que desejam entender as vendas de seus produtos em diferentes anos e/ou região
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o duretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
