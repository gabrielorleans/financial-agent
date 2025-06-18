# 💼 IA Analista Financeiro — Projeto Final UFSC

**Disciplina:** EEL510466 – Ferramentas Computacionais para Computação Científica e Aprendizado de Máquina  
**Curso:** Engenharia Elétrica – Universidade Federal de Santa Catarina (UFSC)  
**Autor:** Gabriel Duarte Guimarães Parish Orleans  
**Ano:** 2025

---

## 🧠 Descrição do Projeto

Este repositório apresenta o desenvolvimento de um **analista financeiro inteligente baseado em agentes LLM (Large Language Models)**. O sistema é capaz de interpretar, analisar e visualizar dados extraídos de relatórios financeiros de empresas listadas na bolsa de valores.

A proposta surge da necessidade de **tornar mais acessível a compreensão de documentos financeiros densos e técnicos**, como os releases trimestrais publicados por empresas da B3. Utilizando **modelos de linguagem, ferramentas de visualização e agentes coordenados**, o projeto automatiza etapas como leitura de arquivos, identificação de padrões e geração de gráficos interpretativos.

---

## 🎯 Objetivos

### Objetivo Geral:
Desenvolver um sistema interativo que atue como um analista financeiro virtual, gerando **análises textuais e visuais** a partir de relatórios financeiros em PDF ou `.csv`.

### Objetivos Específicos:
- Construir um pipeline de **extração e tratamento de dados** a partir de PDFs e arquivos estruturados;
- Implementar um **agente baseado em LLMs** para interpretar os dados financeiros;
- Gerar **insights interpretativos em linguagem natural** e gráficos visuais;
- Criar uma **interface conversacional simples** para interação com o sistema;
- Demonstrar o sistema com **dados reais de empresas da B3**.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **LangGraph** (arquitetura agêntica)
- **OpenAI API**
- **Pandas / Matplotlib**
- **Streamlit ou Gradio** (interface interativa)
- **Pydantic / FastAPI** (validação e estruturação opcional)
- **B3 Reports:** https://www.b3.com.br/pt_br/

---

## 🧪 Metodologia

1. **Leitura e estruturação de arquivos** (`.pdf` e `.csv`);
2. **Análise automatizada**: cálculo de indicadores e recomendações de visualizações;
3. **Recomendação de gráficos** com base na estrutura dos dados;
4. **Geração visual** usando ferramentas gráficas do Python;
5. **Interface de chatbot** com suporte a upload de arquivos e retorno em linguagem natural;
6. **Orquestração com agentes** utilizando LangGraph e OpenAI API.

---

## 📈 Exemplo de Funcionalidades
;
- Recomendação de tipo de gráfico apropriado com base nos dados;
- Geração de gráficos (linha, barras, pizza, histograma, dispersão);
- Geração de comentários interpretativos para os dados financeiros;
- (Futuro) Extração direta de dados estruturados a partir de PDFs.

---

## 🚀 Resultados Esperados

- Protótipo funcional de um **analista financeiro virtual automatizado**;
- Geração de insights acessíveis em **linguagem natural e visual**;
- Demonstração do uso prático de **arquiteturas agênticas com LLMs**;
- Interface amigável para interação com dados financeiros complexos.

---

## 📎 Estrutura do Repositório

```bash
📁 data/                  # Arquivos de entrada .csv ou simulados
📁 notebooks/             # Notebooks de desenvolvimento e testes
📁 agent/                 # Definições dos agentes e ferramentas
📁 interface/             # Protótipo da interface conversacional
📄 README.md              # Este documento
