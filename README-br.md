Teste para Desenvolvedor Back-end Java Auth0

Olá ! 
Bolamos esse teste pra entender melhor como você aborda o problema proposto, e como você gosta de codificar. Tentamos aproximar o máximo possível da nossa realidade, utilizando tecnologias que usamos e que facilmente podem ser encontrados tutoriais na internet.
Caso não consiga ou queira fazer algum passo, não tem problema. Não vamos te desqualificar por isso. Nesse caso você pode comentar sobre o ponto e o porquê não o fez. Esperamos que goste!

Seguem as tarefas. As tarefas consideradas bônus, caso não tenha tempo ou prefira não fazer, por favor comentar como faria ou como seria a arquitetura técnica:

- Criar uma API simples de users. Deve permitir essas funções: listar users, deletar users, fazer login e fazer logout. Utilizar Spring BOOT. 
- Login social usando Auth0 - https://auth0.com (apenas Google já tá bom);
- Adicionar funcionalidade de envio de link de ativação;
- Adicionar funcionalidade MFA (https://auth0.com/docs/mfa)
- DB pode ser a vontade (sugestão h2, postgres ou mongo).
- Adicionar swagger, como não teremos front-end, devemos poder fazer todo o flow pelo swagger. Dica: documentar todos os campos. 
- Não esquecer dos unit tests. 
- Criar dockerfile e docker-compose.yaml pra fazer o deploy local como container do docker.
- Entregar o link do repositório em modo privado (preferência gitlab) com readme.MD com instruções de como rodar localmente e resumo técnico.
- Escrever o Readme.md Instruções do flow de login

Bônus:
- Criar arquivo CI/CD do gitlab com 3 stages: compile, tests (caso tenha unit + integration, 1 stage pra cada) e dockerize (gerar container do docker). 
- Deploy em algum cloud provider (preferência AWS, pode ser no EC2 mesmo, ou Azure ou Heroku)
