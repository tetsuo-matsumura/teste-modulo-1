# Teste frontend

## Comece por aqui
- Acesse o [mock](https://www.figma.com/file/al3lkp4AiTWVWbz2Ji9jrk/Teste-Frontend---Organize.Me?node-id=0%3A1&t=yUqMsu3jLR22iMhy-1) e implemente os componentes usando HTML e CSS.
- Os componentes devem ser responsivos.

## Interações
### Login
- Ao adicionar um e-mail que não é e-mail, o campo deve invalidar os dados
- No caso de erro, deve promptar um ```alert``` com a razão do erro.

### Index
- Caso o usuário não esteja logado, deve ser redirecionado para o login.
- No início deve aparecer Olá, <Nome do usuário>. Futuramente esta informação virá da API.
- Ao clicar no item da lista de atividades ele deve ir para o final da lista e ficar no estilo desabilitado.
- Ao clicar no item desabilitado ele deve voltar para a lista
- A lista é organizada por ordem de criação.
- Caso não hajam items pendentes o texto de atividades pendentes deve mostrar: "Você não tem itens pendentes, crie um novo agora!".
- Ao criar uma nova atividade, ela deve aparecer na lista abaixo.
- No fundo da página tem um link escrito Excluir tudo, ao clicar nele, toda a lista deve ser deletada.
