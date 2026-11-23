# 📊 Relatório Gerencial de Vendas e Análise de Lucro - Power BI (Versão Atualizada com UX/UI)

Projeto desenvolvido como parte do Desafio de Projeto do curso **Formação Power BI Analyst** na [Digital Innovation One (DIO)](https://dio.me).
Esta atualização evolui a primeira versão do relatório financeiro aplicando boas práticas de experiência do usuário (UX), interface (UI) e navegação entre páginas.

O objetivo deste projeto foi estruturar um relatório interativo e multinível a partir de dados financeiros, aplicando boas práticas de ETL, modelagem e visualização de dados.

---

## 🖼️ Páginas do Relatório

### Capa
- Tela inicial de apresentação do **Report Financeiro** com identidade visual da formação e botão transparente sobreposto com estado de foco para acesso direto ao painel analítico.

### Página 1: Relatório de Vendas
- **Cartões de KPI principais:** **Soma de Vendas**, **Soma de Unidades Vendidas**, **Soma de Descontos** e **Soma de COGS** com alinhamento e contraste aprimorados.
- **Evolução Mensal:** Gráfico de área (*Soma de Vendas por Mês*) atualizado com rótulos de dados visíveis para leitura imediata.
- **Distribuição e Alternância Visual:** Gráficos por segmento, produtos e países com botões interativos para alternar tipos de visualização (rosca/barra e treemap/mapa).
- **Navegação e Filtros:** Menu lateral unificado com estados de foco e seleção ativa (`Capa`, `Vendas`, `Lucro`) e segmentação por período.

### Página 2: Relatório de Lucro Detalhado
- **Árvore de Decomposição:** Análise hierárquica do lucro por Ano e País com expansão interativa.
- **Matriz de Descrição:** Detalhamento tabular hierárquico (`Segmento` > `Produto`) exibindo **Soma de Vendas**, **Unidades Vendidas** e **Profit** com expansão por nível.
- **Gráfico de Cascata (Waterfall):** Análise do comportamento do lucro ao longo dos trimestres (`Trimestre 1` a `Trimestre 4`) com ordenação personalizada no Power Query.
- **Análise por Produto e Segmento:** Gráficos complementares e segmentação por ano (`2013` e `2014`) alinhados ao padrão visual do relatório.

---

## 🛠️ Tecnologias e Técnicas Aplicadas
- **Power BI Desktop:** Construção do layout, visuais, navegador de páginas, indicadores/botões com estados de interação e diretrizes de UX/UI.
- **Power Query (M):** Limpeza de dados, padronização de rótulos e criação de coluna personalizada para trimestres.
- **DAX & Modelagem:** Medidas agregadas e estruturação da hierarquia de datas.
