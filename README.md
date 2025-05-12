# Whatsapp-bot-ai
# WhatsApp Bot com IA e Multimídia

Este bot para WhatsApp é baseado em **Node.js** e **whatsapp-web.js**. Ele responde perguntas utilizando **ChatGPT** da OpenAI e também manipula mídias como figurinhas, GIFs e áudios.

## Funcionalidades
- **Respostas com IA** utilizando ChatGPT
- **Criação de figurinhas**
- **Geração de GIFs a partir de vídeos**
- **Extração de áudio de vídeos**
- **Geração de imagens com IA**

## Instalação no Termux

1. **Instale o Termux** na Play Store ou F-Droid.

2. **Abra o Termux e execute os seguintes comandos**:

    ```bash
    pkg update && pkg upgrade
    pkg install nodejs
    pkg install git
    pkg install ffmpeg
    pkg install curl
    ```

3. **Clone o repositório**:

    ```bash
    git clone https://github.com/seu-usuario/whatsapp-bot-ai.git
    cd whatsapp-bot-ai
    ```

4. **Instale as dependências do Node.js**:

    ```bash
    npm install
    ```

5. **Configure sua chave da OpenAI**:

    Crie um arquivo `.env` na raiz do repositório com a sua chave de API do OpenAI:

    ```env
    OPENAI_API_KEY=coloque_sua_api_key_aqui
    ```

6. **Execute o bot**:

    ```bash
    node index.js
    ```

    Escaneie o QR Code com seu WhatsApp para conectar o bot.

---

## Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais informações.
