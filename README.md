# Relatório de Vendas Online 


**📖 Contexto do Negócio**

A área comercial identificou a necessidade de acompanhar o desempenho das vendas realizadas pelos canais digitais, permitindo uma visão consolidada sobre produtos, clientes e mercados atendidos pela empresa.

Para apoiar a tomada de decisão estratégica, foi desenvolvida uma solução de integração entre SQL Server e Excel, centralizando os dados de vendas em uma estrutura analítica capaz de fornecer indicadores de desempenho atualizados e confiáveis.

O escopo da análise contempla as vendas realizadas durante o ano de 2013, considerando informações de produtos, clientes, territórios de vendas, custos e receitas.

<br>

**🎯 Objetivo**

Desenvolver uma base analítica que permita monitorar o desempenho das operações de vendas online por meio de indicadores estratégicos, apoiando decisões relacionadas a crescimento de mercado, gestão comercial e rentabilidade.

<br>

**📊 Indicadores Analisados**

<br>

- Vendas por Categoria de Produto

Avaliar quais categorias apresentam maior volume de vendas e contribuição para o faturamento da empresa, permitindo identificar os segmentos mais relevantes para o negócio.

- Receita por Mês

Analisar a evolução das receitas ao longo do período estudado, identificando sazonalidades, tendências de crescimento e períodos de maior desempenho comercial.

- Receita e Custo por País

Comparar o desempenho financeiro entre os diferentes mercados atendidos pela empresa, avaliando não apenas a geração de receita, mas também os custos associados às operações.

- Vendas por Perfil de Cliente

Analisar a distribuição das vendas entre diferentes grupos de clientes, possibilitando a identificação de padrões de consumo e oportunidades de segmentação comercial.

<br>

**🏗️ Metodologia**

Foi desenvolvida uma view analítica denominada VENDAS_INTERNET, responsável por consolidar dados provenientes de diferentes áreas do negócio.

A solução integrou informações de:

Pedidos de venda;
Cadastro de clientes;
Categorias de produtos;
Estrutura de produtos;
Territórios de vendas.

A consolidação dos dados foi realizada por meio de consultas SQL utilizando múltiplos relacionamentos entre tabelas fato e dimensão.

<br>

🔄 Processo de Integração
Extração

Coleta dos dados transacionais relacionados às vendas realizadas pela internet.

Transformação

Aplicação de regras de negócio para consolidação dos dados e construção da visão analítica.

Disponibilização

Publicação da view para consumo em ferramentas de análise, permitindo atualização rápida dos relatórios e dashboards.

📈 Benefícios Gerados

A solução desenvolvida proporciona:

Centralização das informações comerciais.
Redução do tempo de preparação de relatórios.
Maior confiabilidade dos indicadores.
Facilidade na identificação de tendências de vendas.
Apoio à tomada de decisão baseada em dados.
🚀 Conclusão

A implementação da estrutura analítica permitiu transformar dados operacionais em informações estratégicas, oferecendo uma visão integrada das vendas online da empresa.

Por meio da utilização de SQL Server para consolidação dos dados e Excel para consumo das informações, foi possível criar uma solução simples, eficiente e escalável para acompanhamento do desempenho comercial, servindo como base para futuras iniciativas de Business Intelligence e Analytics.
