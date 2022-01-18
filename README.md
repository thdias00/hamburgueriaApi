# hamburgueria api

A API possui 4 endpoints, register, login, endereço e produtos

### Cadastro

POST /register <br/>

Para realizar o registro é necessário informar o email e a senha da seguinte maneira:<br/>
{<br/>
"email": "exemplo@email.com",<br/>
"password":"123456"<br/>
}<br/>

### Login

POST /login <br/>

A realizção do login deve ser feita de maneira análoga ao de registro, passando as mesmas informações:<br/>
{<br/>
"email": "exemplo@email.com",<br/>
"password":"123456"<br/>
}<br/>

### Endereço

POST /adsres <br/>

O cadastro do endereço deve ser feito passando as informações:<br/>
{<br/>
"addres": "Av. Afonso Penna",<br/>
"number":"726"<br/>
}<br/>

### Produtos

-> Carregamento

GET /produtos <br/>

É necessário a autorização pelo token para visualização<br/>
