# 📊 Análise de Evasão de Clientes (Churn) - Telecom X

Este repositório contém um notebook Jupyter (`TelecomX_BR.ipynb`) que realiza uma análise concisa da evasão de clientes (Churn) da Telecom X. O objetivo é identificar os principais fatores que levam os clientes a cancelar seus serviços e fornecer insights acionáveis para a retenção.

## 🎯 Objetivo

*   **Extrair, limpar e transformar** dados de uma API.
*   Realizar **Análise Exploratória de Dados (EDA)** com visualizações chave.
*   Identificar **correlações** e **padrões de evasão**.
*   Gerar **conclusões e recomendações** diretas.

## 📁 Conteúdo

*   `TelecomX_BR.ipynb`: Notebook Jupyter com todo o código e análise.

## 🚀 Como Usar

### Pré-requisitos

Python 3.7+ e as bibliotecas:

*   `pandas`
*   `requests`
*   `matplotlib`
*   `seaborn`
*   `nbformat` (para manipulação programática de notebooks, já instalado no ambiente)

Instale com pip:

```bash
pip install pandas requests matplotlib seaborn
```

### Execução

1.  **Baixe o Notebook:** Faça o download de `TelecomX_BR.ipynb`.
2.  **Abra no Jupyter/Colab:** Carregue o arquivo em um ambiente Jupyter ou Google Colab.
3.  **Execute as Células:** Rode as células sequencialmente para reproduzir a análise.

## 💡 Conclusões e Recomendações

**Perfil de Risco:** Clientes com contrato mensal, pouco tempo de casa, fatura alta (fibra óptica) e pagamento via cheque eletrônico.

**Recomendações:**

*   **Incentivar Contratos Longos:** Migrar clientes de planos mensais para anuais/bianuais.
*   **Onboarding Eficaz:** Focar na satisfação nos primeiros 3 meses.
*   **Otimizar Fibra Óptica:** Investigar e ajustar a oferta para este serviço.
*   **Promover Pagamentos Automáticos:** Reduzir o atrito do cheque eletrônico.
*   **Incentivar Serviços Adicionais:** Clientes com mais serviços tendem a ser mais leais.

