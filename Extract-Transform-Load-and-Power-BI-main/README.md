# ETL e Modelagem de Banco de dados
Este projeto de Business Intelligence foi desenvolvido para modernizar a gestão estratégica de um salão de beleza, superando as limitações analíticas do sistema de agendamento original, que carecia de relatórios visuais.

Utilizando Pentaho Data Integration e MySQL, foi construído um fluxo de ETL para consolidar dados de planilhas em um Data Warehouse robusto. Um dos maiores desafios técnicos superados foi a higienização da base de dados, corrigindo inconsistências geradas por falhas manuais no cadastro feito pela recepção.

O resultado final é um dashboard interativo no Power BI composto por cinco visões estratégicas: métricas de Vendas, Produtividade da Equipe, Volume de Atendimentos e Análises de Desempenho (Mensal e Anual). Toda a arquitetura, incluindo o dicionário de dados, está documentada no arquivo 'Visão Produto.pdf'.

### Documentação

Dicionário de dados, explicação dos tratamentos realizados e registro dos paineis elaborados no Power BI constam no documento "Visão Produto.pdf"

#### Modelagem Fato Atendimentos

<img src="Modelagem/dw_salao_fato_atendimentos.png" alt="Descrição" width="300">

#### Modelagem Fato Vendas

<img src="Modelagem/dw_salao_fato_vendas.png" alt="Descrição" width="300">


#### ETL

<img src="ETL/IMAGENS_JOBS/CARGA_DW.png" alt="Descrição" width="300">




