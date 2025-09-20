---
repeat: spaced every 9 days in the evening
due_at: 2025-09-29T18:00:00.000-03:00
hidden: true
---
#http #programação

Fonte: [Curso Udemy](https://www.udemy.com/course/java-backend-360-web-services-api-com-spring-boot-e-jpa/)
MOC Relacionado: [[Fundamentos_MOC]]

A comunicação na internet, como quando você acessa um site, ocorre entre um **cliente** (seu navegador) e um **servidor** (onde o site está hospedado). Essa interação é estabelecida através de um canal bidirecional.
#### **Protocolos de Rede e Portas**

Para que essa comunicação aconteça, o servidor precisa estar **"no ar"**, ou seja, ativo e ouvindo em uma **porta** específica. Essa porta é identificada por meio do protocolo **TCP/IP**, que é a base da internet.

- **TCP** (Protocolo de Controle de Transmissão) é o protocolo responsável por garantir que os dados sejam enviados e recebidos de forma confiável e ordenada.
#### **O Protocolo HTTP**

O **HTTP** (Protocolo de Transferência de Hipertexto) é o protocolo de transporte de dados usado na web. Ele define as regras para a comunicação entre cliente e servidor.
![[Pasted image 20250919211827.png]]

Uma mensagem HTTP é sempre composta por duas partes:

1. **Header (Cabeçalho):** É a parte obrigatória da mensagem. Ele funciona como uma "ficha de identificação", carregando metadados sobre a requisição ou a resposta, como o método usado, o tipo de conteúdo e o tamanho dos dados.
    
2. **Data (Dados):** É a parte opcional que carrega a informação real que está sendo enviada (por exemplo, um formulário preenchido ou o conteúdo de uma página web).
#### **Requisições e Respostas**

A comunicação entre cliente e servidor é um ciclo de **requisições** e **respostas**:![[Pasted image 20250919212318.png]]

- **Request (Requisição):** É a mensagem enviada do **cliente** para o servidor. O **Header** da requisição contém informações essenciais, como o **método HTTP** (por exemplo, **GET**, para obter dados; **POST**, para enviar dados).

- **Response (Resposta):** É a mensagem enviada do **servidor** de volta para o cliente. O **Header** da resposta contém o **status code**, que informa se a requisição foi bem-sucedida ou não (por exemplo, **200 OK**, sucesso; **404 Not Found**, página não encontrada).

    ![[Pasted image 20250919212955.png]]

Em resumo, o TCP/IP estabelece a conexão, enquanto o HTTP define o formato das mensagens (compostas por Header e Data) que trafegam por essa conexão, permitindo que o cliente e o servidor "conversem" de forma estruturada.