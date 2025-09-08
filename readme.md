# Projeto CrecheBot

Este projeto demonstra um chatbot simples, o **CrecheBot**, que atua como um assistente interno para orientar funcionários de uma creche sobre regras e rotinas. O chatbot foi desenvolvido utilizando a API do Google Gemini.

---

### Pré-requisitos

Para executar este projeto, você precisa ter:

-   **Python 3.7** ou superior instalado.
-   Uma chave de API da Google Gemini. Você pode obtê-la no [Google AI Studio](https://aistudio.google.com/app/apikey).

---

### Configuração

Siga os passos abaixo para configurar e executar o chatbot:

#### 1. Clonar o Repositório

Abra o terminal e use o seguinte comando para clonar o projeto:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```
Navegue até a pasta do projeto:
```bash
cd seu-repositorio
```

#### 2. Configurar o Ambiente

Crie um ambiente virtual para o projeto (opcional, mas recomendado) e ative-o:

```bash
python -m venv venv
# No Windows
venv\Scripts\activate
# No macOS/Linux
source venv/bin/activate
```
Em seguida, crie um arquivo na raiz do projeto chamado .env e adicione sua chave de API nele:
```bash
GEMINI_API_KEY="SUA_CHAVE_DE_API_AQUI"
```
**Importante**: Substitua "SUA_CHAVE_DE_API_AQUI" pela sua chave real da API do Google Gemini.



#### 3. Instalar as Dependências

Instale as bibliotecas necessárias para o projeto usando o pip. Crie um arquivo chamado requirements.txt com o seguinte conteúdo:

```bash
pip install google-generativeai python-dotenv
```

#### 4. Executar o Chatbot

Para rodar o chatbot, execute o seguinte comando no terminal:

```bash
python chatbot.py
```
O programa irá iniciar e pedirá a você para fazer três perguntas. O chatbot responderá com base no contexto que foi definido no código, mantendo a fluidez da conversa. Ao final, ele gerará um resumo das interações.