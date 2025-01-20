# Python Insights - Analisando Dados com Python

## Case: Cancelamento de Clientes

Este projeto utiliza **Python** para analisar dados de cancelamento de clientes e identificar ações estratégicas para reduzir a taxa de cancelamento de uma base com mais de 800 mil clientes. A análise é realizada por meio de ferramentas como **pandas**, **numpy** e **plotly**.

---

## Objetivo

Entender os principais motivos de cancelamento de clientes e propor soluções baseadas nos dados para reduzir a taxa de cancelamento, que atualmente é de **56,7%**.

---

## Tecnologias Utilizadas

- **Python**
- **Pandas**: Manipulação de dados
- **Plotly**: Criação de gráficos interativos
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo

---

## Passo a Passo do Projeto

### 1. Importação e Visualização dos Dados
- Importação do arquivo `cancelamentos_sample.csv`.
- Remoção de colunas irrelevantes para a análise.
- Verificação e exclusão de valores ausentes na base de dados.

### 2. Análise Inicial dos Cancelamentos
- Contagem total e percentual de clientes que cancelaram versus os que permaneceram ativos.

### 3. Identificação de Causas de Cancelamento
- Análise de como diferentes colunas impactam a decisão de cancelamento.
- Criação de gráficos interativos para explorar padrões.

### 4. Propostas de Soluções Baseadas nos Dados
A análise revelou os seguintes pontos críticos:
- **Clientes com contrato mensal**: Alta taxa de cancelamento.
  - **Solução**: Oferecer descontos em contratos anuais e trimestrais.
- **Clientes que ligam mais de 4 vezes para o call center**: Alta taxa de cancelamento.
  - **Solução**: Resolver problemas em até 3 ligações.
- **Clientes com atrasos superiores a 20 dias**: Alta taxa de cancelamento.
  - **Solução**: Implementar políticas para resolver atrasos em até 10 dias.

### 5. Simulação de Redução da Taxa de Cancelamento
Após aplicar as soluções:
- **Taxa de cancelamento antes**: 56,7%
- **Taxa de cancelamento após**: 18,3%
