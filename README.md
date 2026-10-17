# 🏎️ Dashboard de Vendas Porsche - Inteligência Artificial

Este repositório contém o desafio concluído de criação de um dashboard interativo de vendas da Porsche, desenvolvido a partir de dados sanitizados e construído de forma 100% web utilizando Inteligência Artificial (ChatGPT com recurso Canvas).

## 🌐 Link do Dashboard no Ar
🔗 [Acesse o Dashboard Interativo Aqui](https://github.io)

---

## 📊 1. Perguntas de Negócio Escolhidas
O painel foi estruturado para responder a três perguntas fundamentais de negócio, separando um amontoado de gráficos de uma ferramenta útil de tomada de decisão:
1. **Faturamento por Modelo:** Identifica qual modelo da Porsche gera o maior volume de receita para focar esforços de marketing.
2. **Distribuição Regional:** Descobre quais estados lideram o consumo de carros de luxo para otimizar a logística e distribuição de estoque.
3. **Preferência de Pagamento:** Analisa a modalidade financeira mais utilizada pelos compradores para negociar melhores taxas bancárias.

## 🛠️ 2. Tratamento dos Dados antes da IA
Antes de submeter os dados para a Inteligência Artificial estruturar o código, a base passou pelo seguinte filtro:
* **Exclusão de Dados Inválidos:** Todas as linhas contendo a marcação `INVALID` na coluna `SaleDateSanitized` foram descartadas, resultando em **76 registros válidos**.
* **Foco em Dados Sanitizados:** Ignorou-se as colunas de dados "crus", utilizando exclusivamente os campos finais limpos (`Sanitized`).
* **Tipagem Correta:** Garantia de que valores de preço e ano fossem interpretados puramente como numéricos para evitar quebras em cálculos matemáticos de topo.

## 🤖 3. Processo de Geração com IA
* **Ferramenta Utilizada:** ChatGPT com interface Canvas (Arquivo Único).
* **Estratégia do Prompt:** Foi aplicado um prompt de engenharia de dados sênior detalhando a persona (Front-end e Analista Sênior), restrições técnicas (uso de Chart.js via CDN, recálculo em tempo real nos filtros), escopo de negócios (cards de faturamento e 3 gráficos específicos) e guia visual rígido (Dark Mode minimalista premium, paleta de cores institucional Porsche com detalhes em vermelho esportivo).
* **Refinamento:** Os dados foram embutidos diretamente no código em formato JavaScript, eliminando qualquer dependência de servidores externos ou banco de dados físico.

---
Desenvolvido por cesarbh1 para o desafio de Agentes de Dados na DIO.
