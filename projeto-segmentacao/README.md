# Projeto de Segmentação - Análise de Dados para "O Mercado"

## Sobre o Projeto

Este projeto realiza uma análise de segmentação de clientes para o estabelecimento especializado em produtos alimentícios importados chamado **“O Mercado”**. O objetivo é identificar grupos de clientes com comportamentos e perfis semelhantes para apoiar estratégias de marketing e vendas mais assertivas.

---

## Equipe

- Thayna Moreira

---

## Ferramentas e Tecnologias

- Google Sheets  
- Google Slides  


---

## Processamento e Análises

### 1. Importação dos Dados  
- Utilização da fórmula `IMPORTRANGE` para unir três planilhas: Clientes, Transações e Resumo de Compras em abas diferentes de uma mesma planilha.

### 2. Tratamento dos Dados  
- Preenchimento de 24 valores nulos de salário usando a média por nível de escolaridade com auxílio de tabelas dinâmicas.  
- Exclusão de 7 transações sem ID de cliente para garantir integridade das relações.  
- Remoção de 9 linhas duplicadas com filtros e formatação condicional do Google Sheets.  
- Criação da planilha “Unificada” com fórmula `PROCX`, consolidando informações importantes por `id_cliente`.  
- Cálculo de número de compras e data da última compra via tabelas dinâmicas para clientes com múltiplas transações.

### 3. Criação de Variáveis  
- Variáveis derivadas como idade, faixa etária, número de filhos, gasto total, ano da última compra e dias desde a última compra.  
- Classificação dos clientes por tipo de canal de compra (loja física, online ou ambos) usando tabelas dinâmicas.

### 4. Análise com Variáveis Categóricas  
- Análises por nível de escolaridade, estado civil, renda média, número médio de filhos, resposta a campanhas e frequência de compra por canal.

### 5. Segmentação RFM  
- Criação da análise RFM com colunas para Recência (dias desde última compra), Frequência (número de transações) e Monetário (gasto total).  
- Cálculo dos quartis para R, F e M usando fórmula `=QUARTIL()`.  
- Classificação dos clientes por score RFM (combinação dos quartis) e segmentação em grupos como:  
  - Melhores Clientes  
  - Clientes Leais  
  - Clientes Regulares  
  - Clientes em Alerta  
  - Clientes Recuperáveis  
  - Clientes Potenciais  
  - Clientes Inativos

### 6. Dashboard Final  
- Desenvolvimento de um painel simples com gráficos destacando os segmentos e seus comportamentos.

---

## Resultados e Conclusões

- Predominância de clientes adultos, com ensino superior ou pós-graduação, em sua maioria casados e com família pequena (média de 1 filho).  
- Maior parte das compras realizadas em lojas físicas.  
- Aplicação bem sucedida da técnica RFM para segmentar clientes segundo recência, frequência e valor gasto.  
- Segmentos Melhores Clientes, Leais e Regulares são os que mais contribuem para o faturamento, evidenciando que qualidade supera quantidade.  
- Potencial para campanhas e estratégias focadas em engajamento e recuperação de clientes.

---

## Limitações e Próximos Passos

- Dados incompletos e ausentes exigiram tratamentos manuais, especialmente IDs e salários.  
- Segmentação feita manualmente, com intenção futura de automação.  
- Próximo passo: criação de dashboards interativos no Looker Studio para facilitar a interpretação dos dados.

---

## Link para a Planilha

[Google Sheets - Projeto Segmentação](https://docs.google.com/spreadsheets/d/1BsY1DHiE9KHkabO_-tFloohEfxQvfkKzXGOjXmJ1OCc/edit?usp=sharing)

---

## Como usar este repositório

- Navegue pela planilha no link acima para entender as análises.  
- Confira as abas e fórmulas para acompanhar o passo a passo da segmentação.  
- Use o dashboard para visualizar o resumo dos segmentos.

---

## Contato

Thayna Moreira 
Thaynamoreira845@gmail.com 
https://www.linkedin.com/in/thaynamoreira/

