# Performance

## 🎯 Objetivo

Documentar as principais decisões adotadas para tornar o modelo mais organizado, eficiente e escalável.

---

## Principais Otimizações

| Decisão | Benefício |
|----------|-----------|
| Modelagem em Star Schema | Simplificação dos relacionamentos |
| Criação da DimCliente | Centralização dos atributos dos clientes |
| Utilização da DimCalendario | Consistência nas análises temporais |
| Medidas DAX reutilizáveis | Redução de duplicidade de lógica |
| Direção única dos filtros | Melhor desempenho das consultas |

---

## 🔍 Bastidores da Solução

Ao longo do desenvolvimento, a arquitetura do modelo foi revisada para reduzir a complexidade dos cálculos e facilitar a manutenção da solução. A criação da **DimCliente** representou a principal evolução estrutural do projeto, contribuindo para uma organização mais eficiente da camada analítica.

---

## ✅ Principais Decisões

- Separação entre fatos e dimensões.
- Redução da complexidade do modelo.
- Centralização das regras analíticas.
- Estrutura preparada para futuras evoluções.

---

## ✅ Conclusão

As decisões de modelagem adotadas contribuíram para uma solução mais performática, organizada e alinhada às boas práticas de Business Intelligence.