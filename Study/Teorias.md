## 1.0 - O que é Business Intelligence
#### Área responsável por auxiliar na tomada de decisões e criação de estratégias, levando em consideração dados e informações do passado, para que se possa planejar o futuro.
* Conjunto de técnicas e conceitos voltados para a Análise de Dados;
* Não é uma ferramenta;
* Coletar e organizar dados para facilitar a transoformação dos dados em informações; 
* Analisar esses dados e transformar informações que possam ser visualizadas;
* Compartilhar essas informações e monitorar a evolução dos KPIs.          
                            
<i>"Entregar a informação correta, para a pessoa correta, no tempo correto."</i>

## 2.0 - Etapas 
### 2.1 - (ETL) Fonte de Dados | Extração dos Dados
Identificação das fontes de dados. (Arquivos locais em pastas, arquivos em nuvens e Banco de dados)
* SQL Server
* MySQL
* CSV
* JSON
* XLS
* etc

### 2.2 - (ETL) Estrturação | Modelagem de Dados
Processo onde os dados são estruturados, organizados e relacionados em diversas tabelas(fato e dimensão) de uma forma lógica, tornando possivel transformar esses dados em informações coerentes e fazer as devidas ligações entre tabelas, garantindo uma boa perfomance.

<i>Cada coluna deve falar sobre um determinado assunto, a modelagem de dados serve para garantir que isso aconteça.</i>

## O que é o Modelo de Dados ? ##
Estrutura Lógica com <b> tabelas relacionados </b> que representa os processos de negócios.

### Tipos de Modelagem
<b>Dimensional </b> - Power BI
* <b> Usado em </b>: Repositório de dados (DW) ou modelos do PBI
* <b> Tipo de Sistemas </b>: Análiticas - OLAP
* <b> Nível de Organização </b>: Tático/Estratégico
* <b> Tipo de Modelagem </b>: Desnormalizado
* <b> Conceito Chave </b>: <b> Fato e Dimensão </b>
* <b> Foco </b>: Consultiva rápida de dados
* <b> Ao realizar consultas </b>: Alto Desempenho

<b>Relacional </b>
* <b> Usado em </b>: Banco de Dados Relacionais
* <b> Tipo de Sistemas </b>: Transacionais - OLTP
* <b> Nível de Organização </b>: Operacional
* <b> Tipo de Modelagem </b>: Normalizado
* <b> Conceito Chave </b>: Entidade / Relacionamento
* <b> Foco </b>: Armazenamento consistente, inserir, alterar e deletar dados
* <b> Ao realizar consultas </b>: Baixo Desempenho

#### Data Quality | Validação dos Dados ####
Manter a qualidade e veracidade dos dados, garantino que estejam prontos para serem analisados corretamente.

<i>Pior do que não ter dados, é ter dados errados. </i>

#### Star Schema - Mais Otimizado, modelo mais utilizado.
Diversas <b>tabelas dimensões</b> ligadas a apenas uma <b>tabela fato</b>

#### Snowflake Schema - Menos otimizado, utizado em determinados casos.
As <b>tabelas dimensões</b> são ligadas a uma <b>tabela fato</b> e em outras <b>tabelas dimensões</b>, formando um tipo de hierarquia.

#### Tabela Fato ####
* Tabela que apresenta os dados, valores e estatísticas principais que serão transformados em informações.
* Contém uma ou mais colunas chaves <b> relacionadando a tabela dimensão </b> e colunas de medidas numéricas. 
* <b> Valores utilizados como chave aparecem diversas vezes </b>
* Não contém descrições

#### Tabela Dimensão ####
* Tabela com a funcionalidade de fornecer os dados que na maioria das vezes são transformados em filtros, que segmenta os dados para uma melhor análise.
* Contém uma ou mais colunas chaves, que atuam como uma referência exclusiva, e colunas descritivas.
* <b> Valores utilizados como chave são únicos </b>
* As descrição ficam na tabela dimensão

#### Tabela Calendário(Dimensão) ####
Ideal para quando a inteção é realizar análises temporais.

####  OLAP - Processamento analítico online


### 2.3 - Métricas | Cálculos
<b> Onde é traduzido a regra de negócio</b>, e é identificado o problema e sua solução.

### 2.4 - Visualização
Processo responsável pela criação dos:
* Relatórios
* Dashboards

#### Storytelling ####

#### Data Viz ####

#### UX/UI ####
Levar em consideração a melhor experiência do usuário e facilidade/acessibilidade ao utilizar o dashboard.

### 2.5 - Distribuição | Compartilhamento

### 2.6 - Automatização
Automatizar alguns do processos anteriores para que não seja necessários realizar novamente manualmente.

## 3.0 - Áreas de Aplicação
<b> Financeiro </b>
* Margem de Contribuição
* Fluxo de Caixa

<b> Logística </b>
* Monitoramento de Ordem
* Nível de Serviço

<b> Estoque </b>
* Custo de Inventário
* Giro de Estoque

<b> RH </b>
* Turnover
* Taxa de absenteismo

<b> Processos </b>
* Índices de qualidade
* Leade Time
* OEE

<b> Vendas </b>
* Total de Vendas
* Quantidade de Vendas
* Total de Custo




