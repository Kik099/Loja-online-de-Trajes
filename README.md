# Loja-online-de-Trajes

A aplicação(TP2.rar) tem uma base de dados para persistir a informação, term uma interface web em Java Server Faces, usando “entities” e “enterprise java beans”. Esta loja é uma aplicação que permite gerir a partilha de recursos entre uma população.Opções do site:

Aparece um menu, onde pede para fazer Login, registar ou entrar no modo visitante(consultar imagem).

Caso se entre pelo Login aparecem as seguintes opções:

Op1 - Inserir Traje. O processo cliente fornece ao servidor os dados do recurso que disponibiliza.

Op2 – Consultar Trajes. O processo cliente fornece um valor do tipo String, o método devolve todos os recursos que na sua descrição contêm essa String.

Op3 – Requisitar/Reservar um Traje. O cliente envia o identificador do Traje que pretende. Se o Traje estiver disponível, o Traje fica assinalado no servidor como passando a estar “requisitado”. Se o Traje já estiver atribuído a um cliente, passará ao estado “reservado”.

Op4 – Devolver um Traje. Um utilizador devolve um Traje que requisitou.

Op5 – Listar Trajes. O servidor envia ao cliente uma lista de todos os recursos disponíveis.

Caso se entre pelo Modo Vistitante aparecem as seguintes opções:

Op1 – Consultar Trajes. O processo cliente fornece um valor do tipo String, o método devolve todos os recursos que na sua descrição contêm essa String.

Op2 – Listar Trajes. O servidor envia ao cliente uma lista de todos os recursos disponíveis.



