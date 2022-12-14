# todo-nodejs-v2

A Aplicação permite a criação de lista de tarefas. Existe perfil pago e gratuito com limite de criação de tarefas.

Abrir projeto com VSCode Online:

https://github1s.com/MyIgnite/todo-nodejs-v2

Clone o projeto, navegue até a raiz do projeto e execute:</br>

`yarn` </br>
`yarn dev` </br>

Execute o comando para testar a aplicação </br>
`yarn test` </br> </br>


- [x] Deve ser capaz de encontrar o usuário pelo nome de usuário no cabeçalho e passá-lo para request.user
- [x] Não deve ser capaz de encontrar um usuário não existente pelo nome de usuário no cabeçalho
- [x] Deve permitir que o usuário crie uma nova tarefa quando estiver no plano gratuito e tiver menos de dez tarefas
- [x] Não deve permitir que o usuário crie um novo afazer quando não for Pro e já tiver dez afazeres
- [x] Deve ser capaz de permitir que o usuário crie infinitos novos todos quando estiver no plano Pro
- [x] Deve ser capaz de colocar o usuário e todo no pedido quando ambos saem
- [x] Não deve ser capaz de colocar o usuário e todo o pedido quando o usuário não existe
- [x] Não deve ser capaz de colocar o usuário e o todo na solicitação quando o id do todo não é uuid
- [x] Não deve ser capaz de colocar o usuário e o todo na solicitação quando o todo não existe
- [x] Deve ser capaz de encontrar o usuário pelo parâmetro de rota id e passá-lo para request.user
- [x] Não deve ser capaz de passar o usuário para request.user quando ele não existe
