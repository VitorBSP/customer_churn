# 📞 Desafio Churn em Telecom

> **Objetivo de negócio:** diminuir o churn precoce de um serviço de telecom com alto custo de instalação  
> **Escopo preditivo:** somente variáveis **pré-instalação** – sem `tenure` nem `TotalCharges`

---

| Camada | Destaque |
|--------|----------|
| **EDA** | Drivers principais de churn → contrato mensal, método **Electronic check**, internet Fibra sem add-ons e `MonthlyCharges` (Q4). |
| **Modelagem** | Pipeline  → RFECV → XGBoost / RandomForest`. |
| **Simulação financeira** | Três cenários de custo de instalação (3 × / 6 × / 12 × mensalidade) → redução de perdas de até **32 %**. |
| **Plano de ação** | Ofertas de migração de contrato, bundle de add-ons, incentivo a débito automático, programa Early-Life. |

