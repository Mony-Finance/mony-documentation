****
# 1° Fase → Descrever o projeto


-  **PRD → Documento de Requisitos do Produto**
	 As principais features dessa aplicação serão:
	- Integração com cartão de Crédito e Débito
		 Isso será para mostras para o usuário a saldo que ele esta atualmente, o quanto de dinheiro ele movimentou e para onde foi o dinheiro, entre outras coisas.
		
		 Essa funcionalidade resolve o problema do usuário ter que ficar entrando no banco paraver quanto tem e no extrato para ver o quanto gastou sem organização nenhuma.
		 
	- Integração com I.A
		 Essa ia irá fornecer uma análise detalhada sobre a conta do usuário com uma dashboard mostrando ao mesmo seus gastos, lucros, fazendo comparações com os meses anteriores entre outras coisas.
		
		 Essa funcionalidade resolve o problema de  falta de tempo e detalhamento da carteira do mesmo. Ela deixa o usuário ter acesso a uma visão detalhada de sua carteira e caso ele tenha interesse em saber mais sobre edução financeira, a I.A irá ajuda-lo, ele terá aceso detalhado sobre sua saúde financeira ao mesmo tempo que recebe dicas para melhoras na mesma.
		 
	- Separador de Investimentos.
		 Uma “aba/seção” que o usuário poderá separar seus investimentos, ele poderá se organizar e deixar separado em onde quer investir, quanto ele vai investir nessa ação, cripto moeda etc e a data que será prevista para ele fazer esse investimento. Caso cheque a data prevista para o investimento ser realizado o mesmo receberá uma notificação na hora prevista para a ação ocorrer. Para modo de comprovação ele deverá marcar se de fato investiu na hora de logar no aplicativo, e iremos fazer uma análise parar ter a certeza, computar se saiu dinheiro do cartão dele e para onde foi. 
		 Não iremos ter aceso ao dinheiro do usuário, apenas aceso visual, ou seja, caso ele gaste 10 reais estará registrado, não guardaremos o dinheiro do mesmo.
		
		 Essa funcionalidade resolve o problema de organização dos investimentos do usuário, possibilitando que o mesmo faça a separação de seus investimentos de maneira simples e organizada.
		 
- O que é o projeto?
	 Um aplicativo de organização e gestão financeira, tanto para uso pessoal quanto para uso empresarial. Nele os usuários terão acesso a uma visão detalhada de seus dados financeiros, sejam ele na parte de investimentos, saldo bancário atual e até mesmos suas pendências.
	 
	 Existem alguns problemas que essa aplicação resolves, sendo alguns deles: O acesso a todos os cartão que o usuário possui em um aplicativo, o poder de organização e gestão das suas finanças sem o papel e caneta, o acesso rápido e prático as suas despesas, investimentos, contas entre outras coisas.
	 
	 Como diferencial teremos integração em tempo real com seus cartões, ou seja, caso o usuário tenha mais de um cartão, seja ele Nu Bank, Inter entre outros, haverá na home do aplicativo tipo de seções específicas para cada cartão e em cada cartão o aplicativo mostrará a saúde da conta, ou seja, se caso eu tenho o cartão Nu Bank e um da Inter e fiz a integração dele no aplicativo vou conseguir visualizar como está o andamento de cada conta separadamente e fazer certos tipos de separação seja para investimentos ou qualquer outra coisa.
	 Uma integração com I.A que será focada em gestão e organização financeira como também em conteúdos de finanças, ou seja se o usuário pedir informações sobre sua carteira e sobre seu modo de organização e gestão, a I.A irá lhe fornecer tudo o que for necessário. Se caso o usuário pedir um Dashboad e dicas para melhorar a a organização, também o será concedido.
	 Também teremos abas/seção para o usuário criar caixas de organização, com isso ele poderá ver onde investiu, onde está seus lucros e prejuízos, caso ele queria criar uma caixa para agendar onde pretende investir, basta a penas ele criar a caixa especificando onde ele pretende investir e programar, o aplicativo irá marcar a data e mandará uma notificação para o mesmo o avisando que ele deve investir. Tudo isso juntamente com um “bloco de anotação inteligente”, essa será uma feature que permitirá o usuário apena anotar onde gastou, o que comprou em um “bloco de notas” e o mesmo já fará os cálculos e o mostrará o quanto irá sobrar etc.
	 
-  Quem são os possíveis usuários??
	 Pessoas que precisam organizar suas finanças de uma maneira mais fácil e inteligente ou até mesmos pessoas que já organizam suas finanças porém em blocos de textos, papeis ou aplicativos que ela tem que inserir todos os dados de forma manual.
	 
- Quais tecnologias utilizar?
	- Mobile:
		- Desenvolvimento Front-End
			- Flutter → Um framework Dart que nos permite desenvolver interfaces de aplicativos sendo essas bonitas e modernas
			- Dart → A linguagem principal
		- Desenvolvimento Back-End
			- Java/Dart/Go → As linguagens principais
			- MySQL/PostgreSQL → Banco de Dados
	- Web
		- Desenvolvimento Front-End
			- HTML/CSS → Estruturação web básica
			- React → Framework Javascript
			- Tailwind → Biblioteca Javascript para front, ela nos permite desenvolver interfaces bonitas e modernas para web. 
		- Desenvolvimento Back-End
			- Javascript - Linguagem principal
			- Node.Js -> Ambiente de execução para servidor em JS
			- MySQL/ PostgreSQL → Banco de Dados
			
- Fazer um MVP → Produto Minimo Viável
	- Quais as funcionalidades serão as principais?
		 As principais features são: A integração em tempo real com seus cartões, ou seja, caso o usuário tenha mais de um cartão, seja ele Nu Bank, Inter entre outros, haverá na home do aplicativo tipo de seções específicas para cada cartão e em cada cartão o aplicativo mostrará a saúde da conta, ou seja, se caso eu tenho o cartão Nu Bank e um da Inter e fiz a integração dele no aplicativo vou conseguir visualizar como está o andamento de cada conta separadamente e fazer certos tipos de separação seja para investimentos ou qualquer outra coisa. Uma integração com I.A que será focada em gestão e organização financeira como também em conteúdos de finanças, ou seja se o usuário pedir informações sobre sua carteira e sobre seu modo de organização e gestão, a I.A irá lhe fornecer tudo o que for necessário. Se caso o usuário pedir um Dashboad e dicas para melhorar a a organização, também o será concedido. Também teremos abas/seção para o usuário criar caixas de organização, com isso ele poderá ver onde investiu, onde está seus lucros e prejuízos, caso ele queria criar uma caixa para agendar onde pretende investir, basta a penas ele criar a caixa especificando onde ele pretende investir e programar, o aplicativo irá marcar a data e mandará uma notificação para o mesmo o avisando que ele deve investir. Tudo isso juntamente com um “bloco de anotação inteligente”, essa será uma feature que permitirá o usuário apena anotar onde gastou, o que comprou em um “bloco de notas” e o mesmo já fará os cálculos e o mostrará o quanto irá sobrar etc.
		 
	-  Quais as funcionalidades colocar em produção inicialmente?
		 Inicialmente iremos implementar como MVP a funcionalidade de integração com os cartões do usuário e a parte de seção para a separação de investimentos.
		 
		 ## Funcionalidades do MVP
		 
		 - Autenticação → Cadastro, Login e Logout
		 - Dashboard → Visualização geral de saldo e cartões conectados
		 - Integração com Cartões → Conectar cartões, listar transações, categorizar despesas
		 - Investimentos → Criar caixas de investimento, agendar datas, marcar como concluído
		 - IA (versão inicial) → Análise mensal de despesas e geração de resumo em texto
		 - Notificações → Alerta de investimento agendado e movimentações incomuns
		 - Plano de Assinatura → Controle básico de plano Free e Pro
		 
		 ## Critérios de Sucesso do MVP
		
		- Ao menos 50 usuários ativos utilizando as funções principais.
		- IA fornecendo relatórios com 80% de acerto na categorização de gastos.
	    - Usuários interagindo com notificações e concluindo ações de investimento.
	      
	- Regra de Negócio da Mony
		## Objetivo do Sistema
		
		A **Mony** é uma plataforma SaaS (Software as a Service) que visa fornecer uma solução completa para gestão financeira pessoal e empresarial, automatizando processos, promovendo educação financeira e integrando múltiplas contas bancárias e cartões de crédito em uma única interface com auxílio de IA.
		
		## Regras de Negócio
		
		- RN001 → Cadastro e Acesso
			- O usuário deve realizar o cadastro com **nome, e-mail, senha** e **telefone**.
			- A senha deve conter no mínimo 8 caracteres.
			- O login será realizado via **e-mail e senha**.
			- Autenticação em duas etapas será disponibilizada para maior segurança.
		 
		- RN002 – Planos de Assinatura
			- A Mony oferece três planos: **Free, Pro e Business**.
			- O plano Free é gratuito, mas com limitações de integração e uso da IA.
			- O plano Pro é voltado a usuários individuais com funcionalidades completas.
			- O plano Business permite multiusuários e dashboards empresariais.
			
		-  RN003 – Integração com Cartões
			- O sistema pode ser conectado a múltiplos cartões de crédito/débito.
			- Os dados dos cartões são obtidos por meio de **integrações via APIs bancárias autorizadas**.
			- Para cada transação lida, será associada a uma categoria e uma data.
			  
		-  RN004 – Gestão de Investimentos
			- O usuário pode criar “**caixas de investimento**” contendo:
			    - Nome do investimento (ex: Ações XPTO)
			    - Valor estimado
			    - Data de aplicação prevista
			    - Status: Pendente / Concluído / Ignorado
			- O sistema notificará o usuário na data agendada.
			- Após o login no dia do agendamento, o sistema perguntará se o investimento foi realizado. O backend validará com base na movimentação dos cartões integrados.
			  
		-  RN005 – Inteligência Artificial
			- A IA irá analisar:
			    - Gastos recorrentes
			    - Categorias com maior gasto
			    - Lucro mensal
			    - Comparações entre meses
			- A IA poderá sugerir:
			    - Orçamentos mensais
			    - Ajustes de gastos
			    - Tipos de investimento
				- A IA responde perguntas e gera relatórios em tempo real via chat integrado.
				  
		-  RN006 – Notificações
			- Notificações serão enviadas:
			    - Ao identificar gastos fora do padrão
			    - No vencimento de faturas
			    - No dia de um investimento programado
				 
- Como Monetizar?
		 Nós faremos a monetização através de pagamentos mensais por planos de assinatura, ou seja o usuário escolherá qual o plano que cabe no bolse do mesmo e caso ele não consiga aderir a nenhum plano ele poderá usufruir do plano gratuito que será vitalicio, porém, esse plano não terá muitos benefícios.
		 

---
# 2° Fase → Análise de Mercado

-  Pesquisar sobre aplicações parecidas
	- Quem são nossos concorrentes? 
		 1. **Organizze**
		 2. **Mobills**
		 3. **Minhas Economias**
		 4. **Guiabolso**
		 5. **Grana Capital**
		 6. **YNAB**
		 7. **Mint**
		 8. **PocketGuard**
		 9. **Conta Azul**
		 10. **Nibo**
	 -  O que cada um deles fazem?
		 - **Organizze**
			 O **Organizze** é um aplicativo brasileiro de gestão financeira pessoal, lançado em 2009. Seu objetivo principal é auxiliar usuários a controlarem suas finanças de maneira simples e prática. Está disponível para plataformas **Android**, **iOS** e **Web**, oferecendo uma interface intuitiva e recursos voltados para o controle de receitas, despesas e planejamento financeiro.
			 
			 O **Organizze** é uma ferramenta eficaz para o controle financeiro pessoal, oferecendo recursos essenciais para o gerenciamento de receitas, despesas e planejamento orçamentário. Sua interface intuitiva e relatórios detalhados facilitam a compreensão da saúde financeira do usuário.
			 
			 **_Possui 3 planos principais_**
				 Mensais
					 1. → Plano Manual
					  Plano de 35,00 por mês, esse plano não possui conexão bancária e é grátis por apenas 7 dias, nesses dias free o usuário tem a oportunidade de ter relatórios completos e simples, alertas para contas que devo pegar no seu determinado dia, controle de cartões e criação de categorias e subcategorias
				  2.  → Plano Conectado
					  Plano de 45,00 por mês, sendo esse o plano que já tem a disponibilidade de integração com 3 catões ou contas conectadas, sendo separada por abas, ou seja, cada cartão tem um bloco/seção em box específico. Contém as outras coisas que o primeiro.
				 3. → Plano Conectado Plus
					 Plano mensal de 69,00 por mês, Contém tudo que os outros planos também possuem mas um adicional de 10 contas/cartões conectados.
					 
			 **_E 3 planos anuais_**
				 Anuais
					Tem os mesmos recursos que os mensais, porém vem com a diferença de pagar com preços diferentes. Como os preços são anuais, o usuário tem a possibilidade de efetuar o pagamento através de parcelar de até 12x, assim obtendo 15% de desconto pagando no plano mensal. A coisa que mais muda é o valor sendo ele o mais baixo dos planos que oferecem menas features, sendo eles: 
					1. 12x de 19,90/mês → 199,90 à vista 
					2. 12x de 39,90/mês → 399,90 à vista 
					3. 12x de 59,90/mês → 599,90 à vista.
		 - **Mobills**
			 O **Mobills** vem com a promessa de que a nossa organização financeira será  mais simplificada. Nele temos opções de criar metas e personalizar o nosso modo de organização e gestão financeira. Trás a notificação de cada transação que o usuário faz no app ou em outro lugar, tem uma boa interface, sendo essa limpa e intuitiva e é multiplataforma. 
			 
			 Nele podemos fazer diversas coisas, como: criai orçamentos, ou seja, definir limite de gastos por categorias, visualização intuitiva, nos permite ter acesso a gráficos e relatórios onde podemos acompanhar nossos investimentos, compras, gastos, lucro entre outras coias. Nele também podemos ter a definição de metas de investimentos, nos permitindo estabelecer metas de curto, médio e longo prazo, como viagens, compras etc, como as notificações de compras e limite de gastos e o mais importante, a sincronização com cartões que nos permite sincronizar cartões de crédito como NuBank, Inter etc, facilitando o acompanhamento das transações.
			 
			- **Vantagens:**
				- Interface intuitiva e amigável.
				- Excelente categorização de despesas.
				- Criação fácil de metas financeiras.
				
			- **Desvantagens:**
				- Não oferece integração direta com bancos.
				- Algumas funcionalidades são acessíveis apenas na versão paga.
				
			- **Possui 1 único plano**
				 Anual
					1. → Oferece todos os benefícios só que pagamos 12x de 19,90 ou à vista por 199,90. Isso sempre será cobrado, tendo em vista que, se eu fizer o pagamento a vista só irei pagar novamente, para renovação de assinatura, após 12 meses.
					
-  Fazer análise dos mesmos
	-  No que eles são bons?
		- **Organizze**
			 1. É multiplataforma, ou seja, está na Web, para aplicativos móveis e também para aplicativos Desktop
			 2. Interface clara e intuitiva
			 3. Planejamento de Despesas
			 4. Controle de receita
			 5. Controle financeiro, ou seja, podemos definir o quanto de dinheiro gastar para certa coisa, tendo assim um controle financeiro.
		- **Mobills**
			 1. Simplificação de Organização Financeira
			 2. Criar metas e personalizar o modo de gestão, ou seja, o usuário decide como ele irá se organizar, no que e como quer separar o seu dinheiro.
			 3. Notificação de transação, ou seja, o app avisa quando ele faz qualquer tipo de transação, seja para o próprio app ou para outro. Sendo assim ele se torna um aplicativo que guarda o nosso dinheiro.
			 4. Interface intuitiva
			 5. Multiplataforma
			 6. Criar orçamentos e definir um limite de gastos
			 7. Dashboard
			 8. Metas e investimentos
			 9. Sincronização com cartões de Crédito.
			 
	- No que eles são ruins?
		 Ambus, para o usuário iniciante ou jovem, não fornece algo inicial, uma apresentação do App, ou seja, quando eu entro no aplicativo pela primeira vez, não sei o que fazer ou por onde começar.
		
	- Principais reclamações? 
		- **Organizze**
			 Uma boa reputação → 8.3 de 10 no Reclame Aqui!! Eles tem um bom relacionamento com os clientes, responderam a maioria e tem uma boa pontuação.
			
		- **Mobills**
			 Uma boa reputação → 8.3 de 10 no Reclame Aqui!!  Vi algumas reclamações não respondidas, inclusive com cliente fieis de longo prazo, porém, em sua maioria tem uma boa avaliação e reputação com o usuário final.
		
	- Analisar os Anúncios
		- Como eles fazer marketing?
			
		- Onde eles publicam os anúncios?
			
		- Qual a estratégia do anúncio? 
			
		- Como eles vendem?
			
		- Quantos anúncios estão rodando?
			
	- Qual o CAC deles → Custo de Aquisição do Cliente?
		
	- Com base nos dados adquiridos → O que faremos de melhor e diferencial?
	
- Definir diferencias para sua aplicação com base nos concorrentes
	

---

# 3° Fase → Desenvolver UX/UI da aplicação

- Fazer wireframe de todas as telas junto com fluxo da aplicação
	
	 Link provisório [Wireframe](https://excalidraw.com/#json=LpXHR2Cx4HgKTF1aZobDG,t7L9yZptN08JmqMZPIralg) 
	
- Fazer designe dos wireframes no Figma