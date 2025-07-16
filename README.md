# CASE-ANS

# ANS - Análise de Beneficiários na Região Sul (Unimed)

Projeto de análise e visualização de dados da saúde suplementar brasileira com foco nos beneficiários da região Sul, utilizando dados abertos da ANS.

## 📊 Objetivo

Explorar os dados de beneficiários por UF, faixa etária e mês, com foco na Unimed, a fim de construir indicadores estratégicos como churn, aderência e evolução de base ativa.

## 🔧 Tecnologias utilizadas

- [PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Google Colab](https://colab.research.google.com)
- [Power BI](https://powerbi.microsoft.com)
- [GitHub](https://github.com)

## 📁 Estrutura do projeto


## 🔄 Pipeline de dados

1. Leitura de arquivos `.zip` do FTP da ANS
2. Filtro por estados do Sul (RS, SC, PR)
3. Extração e unificação dos dados de beneficiários
4. Cálculo de indicadores:
   - Churn rate
   - Aderência
   - Base ativa
5. Exportação em `.csv` para uso no Power BI

## 📌 Principais KPIs

- Total de beneficiários ativos por mês
- Churn rate por UF e faixa etária
- Evolução mensal da base
- Comparativo de operadoras

## 📎 Fonte dos dados

Dados extraídos diretamente do FTP público da ANS:  
[https://dadosabertos.ans.gov.br/FTP/PDA/informacoes_consolidadas_de_beneficiarios-024/](https://dadosabertos.ans.gov.br/FTP/PDA/informacoes_consolidadas_de_beneficiarios-024/)

## 📊 Visualização

![Dashboard Power BI]([dashboard_unimed.png](https://ibb.co/MxrZZLD0))

## 🙋‍♀️ Autora

Ingrid Iplinsky  
📍 Uberlândia - MG  
📚 Pós-graduação em Arquitetura de Dados | PUC Minas




