# Entrega da Global Solution da matéria Enterprise Application Devlopment

Eduarda Mariano de Oliveira 	RM88066
Enzo Wuillaume Marino 		    RM87077
Gustavo Carneiro Alves 		    RM88392
João Pedro Milani 		        RM88132
Luccas Vergueiro de Oliveira 	RM87037 

## Usuarios cadastrados:
### -EliasAdmin
CPF: 12345678901
Senha: 123
### -EliasPadrao
CPF: 45678900000
Senha:456

Requisitos:

• Na página inicial, descrever as funcionalidades implementadas e o motivo que contribuem na solução do problema proposto; -- Campo descrição da index home criado para atender esse tópico.

• Implementar pelo menos 6 entidades relacionadas; -- Entidades criadas na pasta Model: Bicicleta, Patins, Patinete, Empresa, Usuario e Reservas.

• Criar TagHelper; -- TagHelper de suporte criada na index Home.

• Desenvolver pelo menos dois CRUD completos com as entidades relacionadas; -- CRUD de Usuario e de Reservas.

• Implementar o cadastro e a listagem de pelo menos 1 tipo de cada relacionamento (1:1, 1:N e N:M); -- 1:1 -> Usuario e Bicicleta 1:N -> Usuario e reserva N:N -> Reserva e bicicletas

• Implementar 2 funcionalidades além do CRUD (pesquisa, alteração de status, dashboard, etc.); -- Funcionalidade de pesquisa e de login criadas. ATENÇÃO: só será mostrada as reservas criadas conforme o login no momento de criação, ou seja, caso troque de conta as reservas feitas na outra conta não aparecerão. Além disso os usuários Padrão não tem acesso ao cadastro de Usuarios.

• Apresentar as mensagens de feedback para o usuário; -- Mensagens de confirmação no CRUD. 

## Informações importantes

Optamos por usar o sql server, e para que o mesmo seja possível de ser usado de forma online subimos o banco na nuvem da azure. Por causa disso não será necessária configuração do banco localmente.

