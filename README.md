# ChatPDF

O aplicativo PDFChat permite que você converse com seus arquivos PDF usando o poder do langchain, OpenAI Embeddings e GPT no backend. Ele utiliza o Streamlit para a interface do usuário.

## Instalação

Para instalar e executar o aplicativo, siga as instruções abaixo:

1. Clone o repositório usando o Git:

   ```bash
   git clone https://github.com/marcelosiqueira/ChatPDF.git
   ```

2. Acesse o diretório do repositório:

   ```bash
   cd ChatPDF
   ```

3. Instale os pacotes necessários:

   ```bash
   pip install -r requirements.txt
   ```

4. Obtenha sua chave de API da OpenAI seguindo estes passos:
   - Acesse o site da [OpenAI](https://platform.openai.com/account/api-keys)
   - Crie uma conta ou faça login
   - Navegue até a seção "API Keys"
   - Clique no botão "Create new secret key" (ou use uma chave existente)
   - Copie a chave de API

5. No arquivo `app.py` e substitua `<sua-chave-de-api>` pela sua chave de API real:

   ```bash
   os.environ["OPENAI_API_KEY"] = "sua-chave-de-api"
   ```

8. Execute o aplicativo usando o streamlit:

   ```bash
   streamlit run app.py
   ```

O aplicativo agora deve estar sendo executado em http://localhost:8501.

## Uso

Uma vez que o aplicativo esteja em execução, você pode fazer upload de seus arquivos PDF e começar a conversar com eles usando a interface de chat integrada.

Aproveite a conversa com seus arquivos PDF!