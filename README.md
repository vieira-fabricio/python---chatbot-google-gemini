# python-chatbot-google-gemini

## Descrição
Este código utiliza a biblioteca `google-generativeai` para interagir com modelos de inteligência artificial generativa. Ele demonstra como configurar a biblioteca, listar os modelos disponíveis, utilizar um modelo específico para gerar conteúdo de texto e iniciar um chat com o modelo para interações em tempo real.

## Instalação de Dependências
Antes de executar o código, é necessário instalar a biblioteca `google-generativeai`. Você pode instalar esta biblioteca executando o seguinte comando:
!pip install -q -U google-generativeai


## Configuração da Chave da API do Google
Antes de utilizar a biblioteca `google-generativeai`, você precisa configurar uma chave de API do Google. Isso é feito atribuindo sua chave de API à variável `GOOGLE_API_KEY` no código.

## Utilização do Código
1. O código importa a biblioteca `google-generativeai` e configura a chave de API do Google.
2. Em seguida, ele lista os modelos disponíveis para geração de conteúdo de texto.
3. Define uma configuração de geração e configura as configurações de segurança para o modelo.
4. Inicializa um modelo específico para ser usado para geração de conteúdo.
5. Utiliza o modelo para gerar uma lista de compras de supermercado.
6. Inicia um chat com o modelo, permitindo interações em tempo real, onde o usuário pode fazer perguntas ao modelo e obter respostas relacionadas a finanças pessoais.
7. Exibe o histórico do chat em formato Markdown para melhor visualização.

## Observações
- Certifique-se de que possui uma chave de API do Google válida e substitua `MY_API KEY` pela sua chave.
- O modelo utilizado neste código é o `gemini-1.0-pro`, mas você pode escolher outro modelo da lista disponível, se desejar.
- Ao interagir com o modelo em tempo real, insira "fim" para encerrar o chat.

  



