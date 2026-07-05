# Regras de Negócio

## 🎯 Objetivo

Documentar as regras de negócio utilizadas para classificar os clientes e gerar os indicadores apresentados no dashboard.

---

## 📖 Visão Geral

A segmentação dos clientes foi construída com base na metodologia **RFM (Recência, Frequência e Valor Monetário)**, complementada por um **Score de Ativação**, desenvolvido para apoiar a priorização das ações comerciais.

---

## 📝 Segmentos de Clientes

| Segmento | Objetivo |
|----------|----------|
| Premium | Clientes de maior valor para o negócio |
| Fiéis | Clientes recorrentes com bom histórico de compras |
| Oportunidade | Clientes com potencial de crescimento |
| Em Risco | Clientes com redução recente na atividade de compra |
| Novos | Clientes em início de relacionamento |
| Churn | Clientes sem compras dentro da janela de retenção |

---

## 📊 Indicadores Utilizados

| Indicador | Finalidade |
|-----------|------------|
| Recência | Tempo desde a última compra |
| Frequência | Quantidade de compras realizadas |
| Monetário | Valor financeiro acumulado |
| Score de Ativação | Priorização das ações comerciais |

---

## 🔍 Bastidores da Solução

As regras foram centralizadas na camada analítica para garantir consistência entre KPIs, gráficos, tabelas e segmentações, reduzindo duplicidade de lógica e facilitando futuras manutenções.

---

## ✅ Conclusão

A padronização das regras de negócio garantiu uma classificação consistente dos clientes e uma base sólida para as análises estratégicas apresentadas no dashboard.