# README

primeiro inicio com rails new qlqnome, assim iniciara um aplicativo no padrao mvc,
posso colocar um --api no final, e ele criara um modelo mais especifico para apis.

tbm posso colocar o banco de dados no final, se eu não especificar ele usara o sqlite.

dentro das rotas posso definir o controller, e qual metodo do controler.
ex: root 'application#index'

para gerar um controller pelo terminal: rails generate controller qlqnomedocontroller
rails g controller qlqnomedocontroller

cai no routes, que redireciona para o controlador e o metodo especifico ex: pages#home,
onde eu posso criar um arquivo home.html.erb, que já esta vinculado com este metodo.

para criar uma nova pagina, começamos na rota com:
get 'rota', to: 'controller#metodo"
ex:get 'about', to: 'pages#about'
