# EcoBot - Dashboard & Chatbot de Sustentabilidade (ODS 12)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido para a disciplina de Engenharia de Software e visa atender ao **Objetivo de Desenvolvimento Sustentável 12 (Consumo e Produção Responsáveis)**. O **EcoBot** é uma aplicação web que combina um dashboard informativo e um chatbot interativo para auxiliar cidadãos no descarte correto de resíduos eletroeletrônicos.

## ❓ O Problema
Muitos cidadãos não sabem onde descartar lixo eletrônico ou desconhecem o impacto ambiental do descarte incorreto. A falta de uma interface centralizada que registre e informe sobre esses processos dificulta a produção e o consumo responsáveis.

## 🚀 Solução Proposta
A aplicação é um **Chatbot Web** desenvolvido com **Python** e a biblioteca **Streamlit**. 
* **Justificativa:** A solução foi escolhida por permitir uma interface web moderna e responsiva de forma rápida, integrando lógica de backend e persistência de dados em uma única plataforma acessível via navegador.

## 🛠️ Requisitos da Aplicação

### Requisitos Funcionais (RF)
* **RF01:** O sistema deve permitir que o usuário informe seu nome para personalização do atendimento.
* **RF02:** O chatbot deve responder a dúvidas sobre tipos de materiais recicláveis.
* **RF03:** O sistema deve permitir o registro de itens descartados (armazenando em banco de dados).
* **RF04:** A aplicação deve exibir um resumo visual (dashboard) do total de resíduos registrados.

### Requisitos Não Funcionais (RNF)
* **RNF01:** A aplicação deve ser desenvolvida em Python utilizando o framework Streamlit.
* **RNF02:** O armazenamento dos dados deve ser feito em **SQLite**.
* **RNF03:** A interface deve ser amigável e adaptável a diferentes tamanhos de tela.

## 📊 Modelagem: Diagrama de Caso de Uso
O diagrama de caso de uso descreve as interações do usuário, como o registro de descartes e a consulta ao dashboard de impacto ambiental.
*(O diagrama encontra-se na pasta /docs deste repositório)*

## ⚙️ Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Interface Web:** Streamlit
* **Banco de Dados:** SQLite
* **Gerência de Configuração:** Git & GitHub

## 📋 Como Configurar o Projeto
1. Clone o repositório.
2. Crie um ambiente virtual: `python -m venv venv`.
3. Ative o ambiente e instale as dependências: `pip install streamlit`.
4. Execute a aplicação: `streamlit run app.py`.

---
**Desenvolvido por:** Marcos Paulo Miranda Pereira  
**Instituição:** PUC Minas - Engenharia de Software
