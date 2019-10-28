# tprm
Projeto desenvolvido em PHP para o processo seletivo de estágio da Bernhoeft
Este projeto foi desenvolvido por Paulo Lima como parte do processo seletivo de estágio da empresa Bernhoeft em outubro de 2019.

prmlimajr@hotmail.com
(81)99981-3319

#############################################################
Instruções
#############################################################

O conteúdo do site foi publicado no servidor online 000webhostapp.

Acesssar através da url: 

https://tprmprmlimajr.000webhostapp.com/index.php

---------------------

Extrair o conteúdo do arquivo tprm.rar na pasta www do servidor Wamp.

O caminho deve ficar c:/.../wamp64/www/tprm

-----------------------
Montar o servidor Apache no Wamp;

Para montar o banco de dados, acessar no navegador o endereço:

localhost/phpmyadmin

Entrar com utilizador root e deixar o campo palavra-passe em branco e o campo Server Choice marcado com MySQL

Clicar em Base de dados;
No campo Nome da base de dados escrever tprm;
Apertar no botão criar;

Importar as tabelas salvas no arquivo tprm.zip;

Criar a tabela users com os seguintes atributos:
idUsers int(11) AUTO_INCREMENT Primary Key
uidUsers tinytext
emailUsers tinytext
pwdUsers longtext

Criar a tabela clientes com os seguintes atributos:
idCliente int(11) AUTO_INCREMENT Primary Key
uidCliente varchar(30)
emailCliente varchar(30)

-----------------------
Para acessar o site, acessar no navegador o endereço:

localhost/tprm/index.php

-----------------------
Eu publiquei o site no servidor online 000webhost, acesse através do site:

https://tprmprmlimajr.000webhostapp.com/index.php
