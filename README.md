# FeiFood
Acompanhamento sobre a evolução do projeto em Java

## 14/10/2025

Comecei o projeto mudando quase tudo o que tinha sido feito em aula.
Eu estava tendo dificuldade em seguir o modelo com JFrame pelo editor visual, então decidi fazer de outro jeito: criei as telas pelo código direto, usando JavaClass em vez de arrastar e soltar componentes.
Isso me deu mais liberdade, mas também me obrigou a mudar praticamente todo o esqueleto do projeto — principalmente a parte de view, mas acabei alterando também os models, controllers e até a conexão com o banco.]                                                       

<img width="402" height="255" alt="Captura de tela 2025-11-11 165945" src="https://github.com/user-attachments/assets/ebbd1599-5935-4716-b157-7b5d70b61dd3" />

<img width="440" height="276" alt="Captura de tela 2025-11-11 165956" src="https://github.com/user-attachments/assets/b99526ec-0181-4b66-94c4-c36b25b426d1" />


## 07/11/2025

Nessas últimas semanas avancei bem mais.
Terminei de fazer as telas que faltavam, como a de pedidos, avaliação e também o catálogo de alimentos.
Foi nessa parte que o projeto começou a tomar forma de verdade.

<img width="885" height="587" alt="Captura de tela 2025-11-11 170225" src="https://github.com/user-attachments/assets/2c281d49-11c9-470a-ad8e-19e787655349" />


Comecei a trabalhar também no banco de dados, criando todas as tabelas, populando com dados e fazendo os relacionamentos entre elas.
Usei o ERDPlus pra montar o modelo relacional, e depois o próprio site gerou os códigos SQL que usei no PostgreSQL.

Agora o sistema já tem as seguintes tabelas principais:

usuarios

alimentos

pedidos

pedidos_alimentos

avaliacoes

<img width="656" height="485" alt="image" src="https://github.com/user-attachments/assets/40bedb99-5911-49f4-b124-c0387d71f4fc" />


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
Tive várias dificuldades pelo caminho, a maior de todas sendo a criação das telas, onde tive que adapatar o projeto todo a um novo modelo que tive que aprender do zero, e também varias dificuldades sobre o banco de dados.

Hoje o projeto está finalizado e funcionando bem, e serviu como uma ótima base pra consolidar tudo o que aprendi sobre programação orientada a objetos e integração com banco de dados.

## Arquivos do projeto 

[Projeto.jar.zip](https://github.com/user-attachments/files/23486789/Projeto.jar.zip)  =======
[javadoc.zip](https://github.com/user-attachments/files/23486798/javadoc.zip)  ======
[Esqueleto PROJ JAVA.zip](https://github.com/user-attachments/files/23486808/Esqueleto.PROJ.JAVA.zip) (código fonte) ======
https://youtu.be/KMJ5RU6joQI (link video teste)



