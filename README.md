
# Projeto: Gerenciamento de Dados em Estudo Clínico Simulado sobre Hipertensão

## 📌 Objetivo do Projeto  
Desenvolver um sistema integrado para coleta, tratamento, análise e modelagem preditiva de dados clínicos simulados, com foco em hipertensão. O projeto demonstra competências em pesquisa clínica, ciência de dados e boas práticas em saúde.

---

## 🧭 Visão Geral do Pipeline

1. **REDCap:** Criação e estruturação de um banco de dados clínico padronizado.  
2. **ETL com Python:** Exportação e transformação dos dados para análise.  
3. **Dashboard com Power BI:** Visualização interativa dos dados.  
4. **Modelo Preditivo:** Aplicação de IA para prever risco de complicações.  

---

## 🏥 Etapa 1: Configuração do Banco de Dados no REDCap

### ✅ Estrutura dos Campos Criados

- **Informações Demográficas:**  
  - `patient_id`, `idade`, `sexo`, `imc`  
- **Medidas Clínicas:**  
  - `pressao_sistolica`, `pressao_diastolica`, `frequencia_cardiaca`, `medicacao`  
- **Desfecho Clínico:**  
  - `complicacao`, `tipo_complicacao`  

**✔ Resultado:** Base compatível com análise estatística e preditiva, promovendo padronização e qualidade dos dados.

---

## 🧪 Etapa 2: Geração de Dados Fictícios

### 📋 Inserção Manual  
- 20 a 30 registros fictícios no REDCap.

### 🤖 Geração com Python  
- Script para gerar dados aleatórios realistas seguindo a estrutura do banco.

**✔ Resultado:** Base ampliada e diversificada para validação do pipeline.

---

## ⚙️ Etapa 3: ETL e Análise com Python e Power BI

### 📥 Coleta dos Dados  
- Exportação do REDCap em formato `.csv`.

### 🔧 Processamento ETL (Python)  
- Limpeza, normalização, enriquecimento e tratamento de faltantes.

### 📊 Visualização (Power BI)  
- Métricas apresentadas:
  - Distribuição por sexo e idade
  - Médias de pressão arterial
  - Correlação entre IMC e pressão
  - Complicações por tipo de medicamento
  - Tendência temporal da pressão arterial

**✔ Resultado:** Transformação de dados brutos em insights visuais e acionáveis.

---

## 🤖 Etapa 4: Modelo Preditivo (IA)

### 🎯 Objetivo  
Prever risco de complicações em pacientes hipertensos com base em variáveis clínicas.

### 🧹 Preparação dos Dados  
- Seleção de 5 variáveis  
- Tratamento de faltantes  
- Normalização  
- Divisão treino/teste  

### 🧠 Modelagem  
- Algoritmo: Random Forest  
- Ajustes para dados desbalanceados  
- Avaliação: Acurácia, Recall, Precisão, F1-score  
- Interpretação: Importância das variáveis  

### 🚀 Deploy  
- Salvamento do modelo  
- Função de previsão com tratamento de erros  

**✔ Resultado:** Solução preditiva robusta, clara e reutilizável.

---

## ✅ Boas Práticas Implementadas

- **Documentação:** Código comentado e README completo  
- **Qualidade dos Dados:** Tratamento de valores ausentes e inconsistências  
- **Segurança:** Dados anonimizados (uso de IDs)  
- **Reprodutibilidade:** Uso de `random seed` e `requirements.txt`  

---

## 📽 Como Apresentar o Projeto

### 🔄 ETL  
- Comparação entre dados brutos e tratados  
- Justificativas para cada transformação  

### 📈 Dashboard  
- Filtros por idade, sexo, risco  
- Insights visuais (ex: IMC x pressão arterial)  

### 🧮 Modelo Preditivo  
- Resultados das métricas  
- Simulações (ex: “Paciente X com 30% de risco”)  
- Interpretação das variáveis mais relevantes  

---

## 🎯 Objetivo Final  
Construir um pipeline de ponta a ponta para dados clínicos simulados, garantindo **qualidade, segurança e reprodutibilidade**, com entrega de valor por meio de dashboards interativos e modelos de IA aplicáveis à prática clínica.
