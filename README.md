# ChatBotW-Json

Esse código é um simples chatbot implementado em Python, que utiliza um arquivo JSON como base de conhecimento para responder perguntas dos usuários. Segue uma explicação breve do que cada parte faz e como você pode usá-lo.

Importação de Bibliotecas:
        O código importa as bibliotecas json e get_close_matches da biblioteca padrão do Python. json é usada para lidar com arquivos JSON, enquanto get_close_matches é usada para encontrar perguntas similares às fornecidas pelos usuários.
Função carregarconhecimento:
        Esta função recebe o caminho de um arquivo JSON como entrada e retorna os dados contidos nesse arquivo como um dicionário Python.
Função salvarconhecimento:
        Esta função recebe um caminho de arquivo e um dicionário como entrada e salva o dicionário no arquivo JSON especificado.
Função identifica_melhor:
        Esta função recebe uma pergunta do usuário e uma lista de perguntas conhecidas. Ela usa a função get_close_matches para encontrar a pergunta mais similar à fornecida pelo usuário.
Função resposta_para_pergunta:
        Esta função recebe uma pergunta e a base de conhecimento. Ela procura a pergunta na base de conhecimento e retorna a resposta correspondente, se existir.
Função chat_bot:
        Essa é a função principal do chatbot. Ela carrega a base de conhecimento, inicia o loop de conversação com o usuário e responde às perguntas ou aprende novas respostas se não souber responder.
Como utilizar:
        Para usar esse código no Google Colaboratory, você precisa ter um arquivo JSON com a base de conhecimento e fazer o upload desse arquivo para o ambiente do Colab.
Você pode adicionar uma célula de código no Colab e colar esse código.
Certifique-se de que o arquivo JSON da base de conhecimento está no mesmo diretório do seu notebook do Colab.
Execute as células do notebook, e o chatbot será iniciado.
Você pode interagir com o chatbot fornecendo perguntas e recebendo respostas correspondentes. Se o chatbot não souber responder, ele pedirá que você ensine uma nova resposta.







