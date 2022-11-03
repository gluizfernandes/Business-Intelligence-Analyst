* <b> Filtro Power Query </b>

Quando filtramos no Power Query, as informações não serão carregadas para o PowerBI, dessa forma podemos filtrar tudo que for <i> null </i>
  
* <b> Analise Temporal </b>
  
Indicado que seja utilizado gráfico horizontais
  
* <b> Renomear Colunas </b>

Não é recomenando alterar o nome das colunas da base de dados, caso isso acontença, <b> basta procurar a ultima etapa que não possui o erro, e alterar o nome da coluna no código </b>

* <b> Desabilitar Carga </b>
  
Quando desabilitams a carga no Power Query, as informações não serão carregadas para o PowerBI
  
* <b> Estrutura da Modelagem de Tabelas </b>

  <b> Tabelas Fatos </b>: Na Esquerda
  
  <b> Tabela Dimensão </b>: Na Direita

* <b> Mesclar Consulta x Acrescentar Consulta </b>

  <b> Mesclar </b>: Acrescentar novas <b>colunas</b> de uma outra tabela
  
  <b> Acrescentar Consulta </b>: Adicionar novas <b>linhas</b> em colunas já existentes.

* <b> Inserir Dados Manuais </b>
É possísvel criar um tabela manual e informar quais dados estarão nela pelo DAX/PowerBI, basta criar uma nova tabela e preencher.

* <b> Utilizar Métricas em vez das Colunas </b>
Mesmo se a métrica for básica, como um simples <b>SUM</b>, o ideal é criar uma medida pois deixa o desempenho melhor e a métrica fica dinâmica.

* <b> Validação de Dados </b>
Sempre conferir se as métricas estão corretas na tabela, utilizando os filtros.

* <b> Encontrar KPis </b>
<b>Google</b> tem diversos Exemplos de KPI do tema escolhido e podemos utilizar em nossos BI

* <b> Percentual das Metas </b>
% da meta é sempre o Real ÷ Planejado

* <b> Métricas de Operações Básicas </b>
Ideal é utilizar as Fórmulas DAX das <b> Operações Matemáticas </b> no lugar dos simbolos <b>(+ - * /)</b>

* <b> Remover Espaçamento dos Dados </b>
Alguns dados possuem <b>espaço</b> incorreto antes ou depois de uma palavra, para remover basta apertar com o direito na coluna e <b>Cortar</b>

* <b> Escolher Colunas </b>
Ferramenta que tem a função de escolher quais colunas ficaram visiveis, <b>evitando que seja necessario excluir as colunas que não seram utilizadas.</b>

* <b> Função Calculate </b>
Os argumentos dos Filtros da Fórmula DAX CALCULATE só recebem <b>tabelas</b>

ex: Função MAX retorna um <b>número</b>, então não pode ser utilizada no CALCULATE; já a função LASTDATE retorna uma <b>tabela</b>, então pode ser utilizada no CALCULATE
