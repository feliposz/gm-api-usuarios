/
    package.json
    /src
        app.js
        /controllers
            index.controller.js
            usuarios.controller.js
            grupos.controller.js
            

Listar todos os usu�rios
GET /usuarios

Cadastrar novos usu�rios
POST /usuarios

Alterar usu�rio
PUT /usuarios/:id

Excluir usu�rio
DELETE /usuarios/:id

N�o pode haver um grupo sem pelo menos um usu�rio;
Ao excluir o �ltimo usu�rio de um grupo o grupo deve ser exclu�do junto;

Listar grupos
GET /grupos

Criar grupo
POST /grupos

S� � poss�vel criar um grupo com dois ou mais usu�rios;

Adicionar um usu�rio � um grupo
POST /grupos/:id/usuarios

Listar usu�rios de um grupo
GET /grupos/:id/usuarios

Listar grupos de um usu�rio
GET /usuarios/:id/grupos

Excluir grupo
DELETE /grupos/:id

Alterar grupo
PUT /grupos/:id
