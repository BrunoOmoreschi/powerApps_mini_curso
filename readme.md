![header](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/header.png)

# MS Power Apps: App básico

O MS PowerApps é a plataforma de desenvolvimento de apps da Microsoft. Ele desenvolve aplicações que rodam dentro do app PowerApps da Microsoft e por isso gera aplicações integradas ao ambiente da Microsoft tais como Excel e outros, mas não limitado a essas opções. Também tem a vantagem de ser de rápido desenvolvimento e poder ser rodado em várias plataformas, seja android , apple ou mesmo web.

## Descrição do App:

![execution](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/execution.gif)

É um app simples simulando uma loja de produtos orgânicos. As imagens e informações foram coletadas na internet e não tem ligação com os sites de onde foram pegas.

A primeira tela é um splash screen para recepcionar o usuário:

![Print1](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/Print1.png)

A próxima tela é onde temos os produtos já cadastrados:

![Print2](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/Print2.png)

O botão voltar leva a splash screen.

As informações estão salvas num banco de dados em Excel, poderia ser um SQL ou outra fonte, mas por querer demonstrar a simplicidade da plataforma escolhemos o Excel. 

O botão atualizar busca se novos itens foram cadastrados no Excel. Também é possível fazer a busca dos produtos e também chamar a tela de cadastro de novos produtos.

Cada card com um produto é clicavel e leva a uma tela de detalhes do cadastro:

![Print3](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/Print3.png)

Aqui vemos os detalhes do item cadastrado. É possível fazer a exclusão do item ou chamar a tela de edição:

![Print4](https://github.com/BrunoOmoreshi/powerApps_mini_curso/blob/main/Print4.png)

A tela de edição é um formulário que envia os dados para uma tabela que pode ser acessada por vários usuários ao mesmo tempo, já que está no servidos do OneDrive. É possível se conectar ao Dropbox e outros.

Essa é a mesma tela que é usada para adicionar um novo item.
