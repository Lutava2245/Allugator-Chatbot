# Allugator-Chatbot

Este projeto apresenta o **Aligator**, um simples chatbot criado para a plataforma **Allugator**, um sistema fictício de aluguel de itens entre usuários.
O chatbot foi desenvolvido para responder dúvidas básicas sobre o funcionamento da plataforma com base em um contexto pré-definido.

## Como rodar

### 1. Acesse o Google Colab
Abra o [Google Colab](https://developers.google.com/colab) no navegador.

### 2. Faça upload do arquivo `aligator.ipynb`
Envie o notebook do projeto para o Colab.

### 3. Configure sua chave de API do Gemini
No notebook, localize a célula onde a chave de API é definida e insira sua chave da API do **Gemini**.

Exemplo:
```python
# aligator.ipynb                            vvvvvvvvvvvvv
client = genai.Client(api_key=userdata.get('FATEC_API_KEY'))
