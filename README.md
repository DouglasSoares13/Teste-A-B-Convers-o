# 🧪 Análise de Teste A/B para Conversão no E-commerce
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![CRISP--DM](https://img.shields.io/badge/Metodologia-CRISP--DM-blue?style=for-the-badge)


Este projeto tem como objetivo avaliar, por meio de um teste A/B, se uma nova versão da página inicial de um site de e-commerce impacta positivamente a taxa de conversão dos usuários.

## 📊 Ferramentas utilizadas
- Excel (análise estatística e tratamento de dados)
- PowerPoint (comunicação dos insights)
- Metodologia CRISP-DM

## 🎯 Objetivo
Analisar se a nova versão da página (tratamento) gera aumento significativo na taxa de conversão em relação à versão atual (controle).

## 🧩 Descrição dos dados
Fonte: Dataset de A/B testing (Kaggle – 2022)

| Coluna         | Descrição                                |
|----------------|--------------------------------------------|
| user_id        | ID único do usuário                        |
| group          | Grupo de alocação (controle ou tratamento) |
| landing_page   | Página acessada (old_page ou new_page)     |
| converted      | Se o usuário converteu (1 = sim, 0 = não)  |
| total_rows     | 289.539 usuários                           |

## 🧠 Metodologia (CRISP-DM)

1. **Entendimento do Negócio:** definir objetivo e métrica principal
2. **Entendimento dos Dados:** explorar estrutura da base, grupos e variáveis
3. **Preparação dos Dados:** limpeza, segmentação e cálculo da taxa de conversão
4. **Modelagem / Análise:** teste Z para proporções e p-valor (Excel)
5. **Validação dos Resultados:** análise estatística e consistência dos dados
6. **Apresentação:** visualização dos resultados em slides e recomendações

## 📈 Resultados

- A taxa de conversão do grupo **controle** foi ligeiramente maior.
- Diferença absoluta de **0,15 ponto percentual**
- O teste Z indicou que a diferença **não é estatisticamente significativa** (p > 0,05)

## 📝 Conclusão

- A nova versão da página **não apresentou ganho significativo de conversão**
- Recomenda-se manter a versão atual do site
- Sugere-se testar novas hipóteses e melhorias mais ousadas no layout

## 🔮 Próximos passos

- Repetir este projeto com Python e Power BI
- Aprofundar conhecimentos em testes estatísticos e visualização interativa
- Explorar segmentação de usuários e testes multivariados

---

👤 **Autor:** Douglas Soares da Silva  
📅 **Data:** Julho de 2025  
