# FeiFood
Acompanhamento sobre a evolução do projeto em Java

## 14/10/2025

Comecei o projeto mudando quase tudo o que tinha sido feito em aula.
Eu estava tendo dificuldade em seguir o modelo com JFrame pelo editor visual, então decidi fazer de outro jeito: criei as telas pelo código direto, usando JavaClass em vez de arrastar e soltar componentes.

Isso me deu mais liberdade, mas também me obrigou a mudar praticamente todo o esqueleto do projeto — principalmente a parte de view, mas acabei alterando também os models, controllers e até a conexão com o banco.

<img width="601" height="370" alt="image" src="https://github.com/user-attachments/assets/a9669067-7fbd-46aa-92f7-f25a321fd977" />
<img width="748" height="451" alt="image" src="https://github.com/user-attachments/assets/92d37e38-ef60-49a5-9c7a-028a80e8e15c" />

## 07/11/2025

Nessas últimas semanas avancei bem mais.
Terminei de fazer as telas que faltavam, como a de pedidos, avaliação e também o catálogo de alimentos.
Foi nessa parte que o projeto começou a tomar forma de verdade.

Comecei a trabalhar também no banco de dados, criando todas as tabelas, populando com dados e fazendo os relacionamentos entre elas.
Usei o ERDPlus pra montar o modelo relacional, e depois o próprio site gerou os códigos SQL que usei no PostgreSQL.

Agora o sistema já tem as seguintes tabelas principais:

usuarios

alimentos

pedidos

pedidos_alimentos

avaliacoes

Cada uma com suas colunas, chaves e relacionamentos.
Depois disso, passei um bom tempo arrumando problemas com a conectividade com o banco de dados, tive muitos problemas na parte de cadastro de usuário, onde constava que meu banco de dados nao existia, depois vi que apenas o nome do banco estava errado no codigo

## 10/11/2025

Na ultima etapa do projeto acabei deixando para tras  algumas coisas, entao tive que alterar algumas pastas, acabei fazendo mais do que precisava, implementei a parte de 5 itens melhores avaliados e 5 piores, que era só para para admin, não vou tirar pois acho que coisas a mais não influenciarão na avaliação

## O que aprendi com o projeto

Esse projeto me ajudou a entender melhor várias coisas:

Como montar interfaces em Java sem usar o editor visual (tudo na mão)

Como funciona o JDBC e a conexão com o banco de dados

Como usar o MVC de verdade, separando o código certinho por camadas

Como criar e popular bancos relacionais

E, principalmente, como resolver erros de driver, conexão e SQL 

Foram muitos testes e tentativas até tudo funcionar certinho, mas valeu a pena.
No final, deu pra entender como um sistema completo funciona, do código até o banco de dados.

## Considerações finais

O FeiFood começou como um exercício simples de login e cadastro e acabou virando um sistema completo, com várias telas, banco de dados e lógica funcionando de verdade.
Mesmo tendo começado pequeno, o projeto foi crescendo e me ajudou muito a entender melhor o Java, o PostgreSQL e a importância de organizar o código em camadas.

Hoje o projeto está finalizado e funcionando bem, e serviu como uma ótima base pra consolidar tudo o que aprendi sobre programação orientada a objetos e integração com banco de dados.
