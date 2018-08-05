# Compartilhamento da Pagina Com Whats App
Este é um projeto simples, que tem como objetivo auxiliar desenvolvedores na criação de links na página, para compartilhamento de artigos no whatsapp ou incluir um link / botão para que o usuário possa entrar em contato direto com o whatsapp da empresa.

## O que é preciso para implementar?
Para implementar o código é necessário apenas os seguintes passos:

* Criar uma ou mais páginas em html (que receberão o link para compartilhamento)
* Criar o link para compartilhamento da página ou o link para o usuário entrar em contato

## Qual comando será usado?
O comando usado para executar essa função será o `.api`, que é disponibilizado diretamente pelo whatsapp, sem a necessidade de criação de funções em JS, PHP ou instalação de plugins (quando for WordPress).

## Código de Exemplo
Caso você já seja experiente e queira simplesmente utilizar o código sem seguir o passo a passo, poderá utilizar o script:

```
<a href="https://api.whatsapp.com/send?phone=text=MENSAGEM-AQUI target="_blank">Link para Compartilhar a Página</a>

<a href="https://api.whatsapp.com/send?phone=55DDDNUMERO-TELEFONE&text=MENSAGEM-AQUI target="_blank">Link para Entrar em Contato Com a Empresa</a>
```

***

###### Autor
Rahel William

###### Fonte
[Escola Ninja WP](https://www.youtube.com/watch?v=T4wTeBZRXZQ)

###### License
ISC

