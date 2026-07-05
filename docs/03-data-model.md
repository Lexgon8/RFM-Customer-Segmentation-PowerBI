# Modelo de Dados

## 🎯 Objetivo

Apresentar a arquitetura do modelo de dados e as decisões de modelagem adotadas para garantir desempenho, organização e escalabilidade.

---

## 📖 Visão Geral

A solução foi desenvolvida utilizando a abordagem **Star Schema (Esquema em Estrela)**, separando a tabela fato das dimensões responsáveis pelos atributos analíticos.

Essa arquitetura simplifica os relacionamentos, melhora o desempenho das consultas e facilita a manutenção do modelo.

---

## 🏗️ Estrutura do Modelo

| Tabela | Tipo | Finalidade |
|---------|------|------------|
| Clientes_SIDE_B | Fato | Transações de vendas |
| DimCliente | Dimensão | Atributos dos clientes |
| DimCalendario | Dimensão | Inteligência temporal |

---

## 📊 Modelo Dimensional

> **Figura 1 — Modelo dimensional do projeto.**

<p align="center">
  <img src="../images/modelo_dados.png" alt="Modelo de Dados" width="900">
</p>

---

## 🔍 Bastidores da Solução

A criação da **DimCliente** foi uma decisão arquitetural importante para centralizar os atributos dos clientes, simplificar os relacionamentos e reduzir a complexidade das medidas DAX.

---

## ✅ Conclusão

A adoção do Star Schema tornou o modelo mais organizado, performático e preparado para futuras evoluções.