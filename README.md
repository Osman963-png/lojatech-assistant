LojaTech Assistant

Assistente virtual desenvolvido para a UC10 utilizando Python, Flask, Pandas e Scikit-Learn.



Funcionalidades

Atendimento automatizado via chatbot

Consulta de status de pedidos

Sistema de recomendação de produtos

Classificação de intenções com Machine Learning

API REST para integração com sistemas externos

Interface Web para interação com usuários

Testes de API utilizando Insomnia

Tecnologias Utilizadas

Python 3

Flask

Pandas

Scikit-Learn

HTML5

CSS3

JavaScript

Git

GitHub

Insomnia

Estrutura do Projeto

assistente/

│

├── app.py

├── gerar\_dados.py

├── teste.py

│

├── dados/

│   ├── produtos.csv

│   ├── clientes.csv

│   ├── pedidos.csv

│   ├── interacoes.csv

│   └── ...

│

├── templates/

│   └── index.html

│

└── static/

&#x20;   ├── css/

&#x20;   │   └── style.css

&#x20;   ├── js/

&#x20;   │   └── script.js

&#x20;   └── image/

&#x20;       └── robot.png

Instalação

Clone o repositório:



git clone https://github.com/Osman963-png/lojatech-assistant.git

Entre na pasta:



cd lojatech-assistant

Instale as dependências:



python -m pip install flask pandas scikit-learn

Gerar Base de Dados

Execute:



python gerar\_dados.py

O comando criará automaticamente os arquivos CSV utilizados pela aplicação.



Executar o Projeto

python app.py

O sistema iniciará em:



http://127.0.0.1:5000

Testar no Navegador

Acesse:



http://127.0.0.1:5000

Exemplos de mensagens:



oi

status do pedido 1002

me indica um mouse

quero trocar um produto

Testar no Insomnia

Método:



POST

URL:



http://127.0.0.1:5000/api/chat

Exemplo de Body:



{

&#x20; "mensagem": "status do pedido 1002",

&#x20; "id\_cliente": "C03"

}

Exemplo de Resposta

{

&#x20; "intencao": "status\_pedido",

&#x20; "texto": "O pedido 1002 está: EM TRANSPORTE.",

&#x20; "sugestoes": \[]

}

GitHub

Repositório:



https://github.com/Osman963-png/lojatech-assistant

Autor

Luiz Oscar da Costa



Projeto acadêmico desenvolvido para estudos de Inteligência Artificial, APIs REST, Machine Learning e Sistemas de Recomendação.

