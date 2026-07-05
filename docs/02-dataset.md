# Conjunto de Dados

## 🎯 Objetivo

Descrever a origem, a estrutura e as características do conjunto de dados utilizado na solução.

---

## 📖 Visão Geral

O projeto utiliza dados transacionais de vendas da empresa fictícia **Maison Liora**, permitindo analisar o comportamento de compra dos clientes por meio da metodologia RFM.

Cada registro representa uma transação realizada por um cliente durante o período analisado.

---

## 📝 Estrutura dos Dados

| Campo | Descrição |
|--------|-----------|
| CustomerID | Identificador único do cliente |
| Data da Compra | Data da transação |
| Valor da Compra | Valor financeiro da venda |
| Pedido | Identificador da compra |
| Produto | Item comercializado |

---

## 🔍 Preparação dos Dados

Antes da modelagem analítica foram realizados:

- Padronização dos tipos de dados.
- Tratamento de valores inconsistentes.
- Remoção de atributos sem relevância analítica.
- Criação do identificador único (**CustomerID**).

---

## 🔍 Bastidores da Solução

Os dados foram preparados para favorecer uma modelagem dimensional simples, reduzindo a complexidade do modelo e facilitando a construção das medidas DAX.

---

## ✅ Conclusão

A preparação dos dados estabeleceu uma base consistente para a construção do modelo analítico e das regras de segmentação implementadas no projeto.