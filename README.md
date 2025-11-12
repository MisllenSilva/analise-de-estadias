# 🧠 Análise de Feedbacks – Automação e Insights com Python 💬

![Badge Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Badge Status](https://img.shields.io/badge/status-Concluído-success)
![Badge License](https://img.shields.io/badge/Licença-MIT-green)
![Badge Colab](https://img.shields.io/badge/Executar%20no-Colab-orange?logo=googlecolab&style=flat-square)
---
## 📋 Sobre o Projeto

O **Análise de Feedbacks** é um projeto desenvolvido por **Misllen Abreu Silva** com o objetivo de **coletar, tratar e visualizar feedbacks automaticamente**, integrando dados do **Google Sheets** e processando informações via **Python**.

O notebook realiza uma análise exploratória e automatizada de respostas textuais, permitindo uma visão clara sobre a **satisfação dos usuários**, **tendências de opinião** e **possíveis melhorias** — tudo em poucos cliques e sem necessidade de planilhas manuais.

> Projeto com foco em **automação de processos e análise de dados aplicada à experiência do usuário**.
---
## 🎯 Objetivos Principais

- Automatizar a importação de dados de feedbacks do Google Sheets  
- Tratar e limpar os dados utilizando **pandas**  
- Gerar visualizações gráficas com **matplotlib**  
- Facilitar o compartilhamento de resultados diretamente na nuvem  
- Apoiar decisões com base em dados reais e atualizados
---
## 🧩 Tecnologias Utilizadas

| Categoria | Ferramentas |
|------------|-------------|
| 💻 Linguagem | **Python 3.10+** |
| 🧮 Análise de Dados | `pandas`, `numpy` |
| 📊 Visualização | `matplotlib` |
| ☁️ Integração Google | `gspread`, `gspread_dataframe`, `google.auth` |
| 🌐 Requisições Web | `requests` |
| 🧠 Ambiente de Execução | Google Colab |
---
## ⚙️ Como Executar o Projeto

1. **Acesse o notebook no Google Colab**  
   👉 [misllenanalise.ipynb](./misllenanalise.ipynb)

2. **Autorize a conexão com sua conta Google**
   - O Colab solicitará acesso para autenticação via `google.colab.auth`  
   - Isso permite o uso da API do Google Sheets

3. **Instale as dependências**
   ```python
   !pip install gspread gspread_dataframe google-auth pandas matplotlib requests
4. Execute as células passo a passo

O script fará login na sua conta Google

Buscará a planilha de feedbacks

Gerará gráficos e tabelas de insights automáticos.

📊 Exemplos de Visualização

O notebook gera visualizações como:

📈 Gráficos de tendência de satisfação
🧩 Distribuição de sentimentos ou categorias de resposta
📊 Resumo estatístico dos feedbacks recebidos

📁 Estrutura do Projeto
analise-feedbacks/
 ┣ 📓 misllenanalise.ipynb        → Notebook principal com o código e visualizações
 ┣ 📜 README.md                   → Documento de apresentação do projeto
 ┣ 📄 requirements.txt             → Lista de dependências (opcional)
 ┗ 📂 assets/                      → Imagens e gráficos gerados
📈 Resultados e Impacto

Com este projeto foi possível:

Automatizar a coleta e atualização de feedbacks sem esforço manual

Reduzir tempo de análise e melhorar a visualização de resultados

Facilitar a comunicação de insights em tempo real para equipes

Mostrar domínio em integração de APIs, Python e Google Cloud

🧑‍💻 Autora

Misllen Abreu Silva
💼 Estudante de Análise e Desenvolvimento de Sistemas
📊 Analista de Dados e entusiasta em Inteligência Artificial
📍 Recife – PE
📧 misllenfranciane@outlook.com
🌐 LinkedIn https://www.linkedin.com/in/misllen-silva-6bb082212/

🧾 Licença

Este projeto está sob a licença MIT – sinta-se livre para aprender, adaptar e contribuir.
Feito com 💙 por Misllen Abreu Silva

💡 Insight Final

“Feedbacks são bússolas que mostram o caminho da melhoria.
A análise inteligente transforma dados em direção.” 📈✨
