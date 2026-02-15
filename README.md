# 📊 TelecomX - Análise de Churn de Clientes

Análise exploratória de dados para identificar os principais fatores que levam à evasão de clientes na empresa TelecomX.

---

## 🎯 Objetivo

Entender os padrões de comportamento dos clientes que cancelam seus serviços e propor estratégias para reduzir a taxa de churn.

---

## 📁 Estrutura do Projeto

```
TelecomX-Churn-Analysis/
│
├── TelecomX_BR.ipynb          # Notebook principal com toda a análise
├── README.md                  # Este arquivo

```

---

## 📊 Dataset

- **Fonte:** API TelecomX (JSON)
- **Total de Registros:** 7.267 clientes
- **Período:** Base histórica de clientes
- **Variáveis:** 22 features incluindo dados demográficos, serviços contratados e informações financeiras

---

## 🔍 Principais Insights

✅ **Taxa de Evasão:** 25,7% dos clientes  
✅ **Fator Crítico:** Tempo de contrato (correlação -0,35)  
✅ **Contratos Mensais:** 42% de evasão vs 3% em contratos bienais  
✅ **Impacto Financeiro:** R$ 2,86 milhões perdidos com churn  

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação de dados
- **NumPy** - Operações numéricas
- **Matplotlib** - Visualizações
- **Seaborn** - Gráficos estatísticos
- **Requests** - Extração de dados via API

---

## 🚀 Como Executar

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/telecomx-churn-analysis.git
cd telecomx-churn-analysis
```

### 2. Instale as dependências
```bash
pip install pandas numpy matplotlib seaborn requests
```

### 3. Execute o notebook
```bash
jupyter notebook TelecomX_BR.ipynb
```

---

## 📈 Visualizações Principais

O projeto inclui:

- 📊 Distribuição de evasão por perfil demográfico
- 💰 Impacto financeiro do churn
- 🔥 Matriz de correlação entre variáveis
- 📉 Análise de tempo de contrato vs evasão
- 🎯 Taxa de churn por tipo de contrato
- 💳 Evasão por forma de pagamento

---

## 💡 Recomendações

1. **Programa de retenção** nos primeiros 12 meses
2. **Incentivos** para contratos anuais/bienais
3. **Revisão de preços** dos planos de maior valor
4. **Promoção** de pagamento automático
5. **Cross-sell** de serviços adicionais

---

## 📄 Relatório Completo

Para mais detalhes, consulte o Relatório Final com análises aprofundadas.

---

## 👤 Autor

**Diego Alves**  
📧 admdiegoalves@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/admdiegoalves/)
