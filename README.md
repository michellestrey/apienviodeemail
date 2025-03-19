# API de Envio de E-mail 📧

Uma pequena API para envio de e-mails utilizando JavaMailSender.

🛠 Tecnologias Utilizadas

✅ Spring Boot

✅ JavaMailSender

✅ Mailtrap (para testes)

✅ HTTPie (para requisições via terminal)


📌 Considerações
Utilização de record para facilitar a implementação.

Configurado para testes com Mailtrap (mailtrap.io).

Para uso real, substitua as credenciais (usuário e senha) fornecidas pelo Mailtrap.


🚀 Como Testar a API


1️⃣ Instalar o HTTPie


Caso ainda não tenha instalado, use:

sh

Copiar

Editar

```pip install httpie```


2️⃣ Executar o Teste via Terminal

Com a API rodando, execute o seguinte comando:

sh

Copiar

Editar

```http POST :8080/email to="email@email.com" subject="Demo Spring" body="Alive"```


Se tudo estiver correto, a API retornará status 200 ✅ e o corpo da mensagem será exibido no Mailtrap.

📥 Como Clonar o Repositório

Para baixar o código-fonte, execute:

sh

Copiar

Editar

```git clone https://github.com/michellestrey/apienviodeemail.git```

