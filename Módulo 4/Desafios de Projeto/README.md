# 🎯 Desafio de Power BI - Módulo 4

# Criação de um diagrama dimensional – star schema – com base no diagrama relacional disponibilizado

## 🚀 Descrição do desafio concluído

###   Analisou-se um diagrama relacional contendo diversos tipos de relacionamentos entre entidades.

###   Definiu-se o Professor como o foco principal da análise.

###   Com base nas informações do diagrama relacional, foram criadas as seguintes tabelas dimensão:

###    * Departamento
###    * Data
###    * Disciplina
###    * Curso
###   Essas tabelas foram estruturadas a partir de agrupamentos de dados relevantes. Cada tabela recebeu índices próprios e identificadores únicos (IDs) para permitir futuros relacionamentos.

###   Os relacionamentos foram estabelecidos de acordo com a quantidade de instâncias presentes nas tabelas.

###   Foi modelado um Star Schema, conectando as tabelas dimensão à tabela fato, de forma a viabilizar a análise centralizada no Professor.


# 🎯 Desafio de Power BI - Módulo 4 - Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

# Criação de Modelo Star Schema com Base em uma Tabela Única "Financial Sample"

## 🚀 Descrição do desafio concluído

###   Desenvolvimento
###   Definição do Interesse Central:

###   O foco da análise foi determinado como sendo as Vendas. Com base nisso, foi criada a tabela fato denominada F_Vendas.
###  Criação das Tabelas Dimensão:

#### Foram desenvolvidas várias tabelas dimensão para organizar as informações, divididas da seguinte forma:
#### *** D_Descontos: Tabela de descontos aplicados.
#### *** D_Detalhes: Informações detalhadas relacionadas às vendas.
#### *** D_Produtos: Detalhes dos produtos vendidos.
#### *** D_Produtos_Detalhes: Informações mais específicas dos produtos.

Essas tabelas foram geradas utilizando técnicas como agrupamentos de informações, colunas condicionais e mescla de consultas.
Para garantir relacionamentos futuros, cada tabela foi equipada com seus próprios índices e IDs.
Criação da Tabela de Dimensão Temporal:

Foi desenvolvida uma tabela de dimensão temporal denominada D_Calendar para permitir o relacionamento temporal com os dados de vendas.
A tabela foi criada utilizando o DAX (Data Analysis Expressions) e foi estruturada com base nos conceitos de hierarquia e granularidade temporal.
Estabelecimento dos Relacionamentos:

Os relacionamentos entre as tabelas fato e dimensão foram estabelecidos com base no número de instâncias e na adequação dos dados para análises corretas.
Modelagem do Star Schema:

Foi feita a modelagem do Star Schema, conectando todas as tabelas dimensão à tabela fato F_Vendas, formando um modelo adequado para análise de vendas com base em diversas perspectivas (tempo, descontos, produtos, etc.).
Essa abordagem cria um modelo de dados eficiente para análise de vendas, permitindo consultas e relatórios otimizados no contexto de um ambiente analítico como o Power BI ou outro software de BI.
