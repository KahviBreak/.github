# Kahvi

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professor: [Marco André Mendes](https://github.com/marrcandre)

### Equipe:
- [Gustavo Correa Krüger](https://github.com/GustavoCKruger)
- [Eduarda Fernandes Heidemann](https://github.com/eduardafh)
- [Nathaly Caroline de Oliveira Adão](https://github.com/nathyadao)
- [Nicole Alves Brand](https://github.com/nicoleabrand)
- [Vallentini Gabrielli da Silva](https://github.com/Vallentini)
- [Yasmin Mello](https://github.com/melloyasminn)

### Links do projeto: 
- [Documentação](https://github.com/KahviBreak/.github/tree/main/profile)
- [BackEnd](https://github.com/)
- [FrontEnd](https://github.com/KahviBreak/Kahvi-frontend)

## Descrição do projeto:
> Nosso projeto foi pensado nas dificuldades que as cafeterias enfrentam para administrar a alta demanda de pedidos para entregas por delivery. O projeto é pensado para negócios que querem mudar sua forma de gerenciar seu negócio para algo inovador e tecnológico, mas também seguro. 

## Situação Problema(cenário):
### Cliente da Kahvi: um sistema de delivery
> Com o aumento da clientela, muitos clientes começaram a pedir um sistema de delivery com cardápio online. O projeto tem como objetivo criar um site que reunisse cardápio, pedidos, pagamentos e controle de estoque para a cafeteria Kahvi.
> Então, nós vimos a oportunidade de criar uma plataforma que auxilia no gerenciamento do estabelecimento, otimizando o dia a dia dos trabalhadores da cafeteria.

## Descrição da proposta:
> A Kahvi é uma cafeteria fictícia pensada pelos desenvolvedores para cafeterias que querem ter seu próprio sistema de delivery, sem depender de sistemas como "ifood, ubereats", que ficam com uma grande porcentagem do valor total da entrega e do pedido.
Nosso objetivo é criar uma solução inovadora e simplificada para a administração do estabelecimento, abrangendo diversas áreas do processo, desde o cadastro de produtos até o fechamento do pedido de forma online.


## Requisitos Funcionais (RF)

| RF01 | Permitir que administradores cadastrem, editem e removam produtos no cardápio. |
| RF02 | Permitir atribuição de nome, descrição, preço, foto e categoria aos produtos. |
| RF03 | Permitir a criação de categorias para os produtos (ex: café, sobremesas). |
| RF04 | Exibir o cardápio digital de forma intuitiva e organizada para os clientes. |
| RF05 | Permitir o filtro do cardápio por categoria de produto. |
| RF06 | Permitir que o cliente visualize detalhes sobre cada item do cardápio. |
| RF07 | Permitir que os clientes façam pedidos online. |
| RF08 | Permitir que o cliente escolha entre entrega (delivery) ou consumo no local (takeaway). |
| RF09 | Permitir que o cliente adicione observações ao pedido (ex: ingredientes, alergias). |
| RF10 | Permitir que o administrador visualize os pedidos em tempo real. |
| RF11 | Permitir que o administrador altere o status do pedido (pendente, em preparo, pronto). |
| RF12 | Gerar relatórios de pedidos passados com informações detalhadas. |
| RF13 | Permitir integração com métodos de pagamento (cartão, pix, dinheiro). |
| RF14 | Calcular automaticamente o valor total do pedido, incluindo taxa de entrega. |
| RF15 | Permitir que o administrador visualize e gerencie transações financeiras. |
| RF16 | Gerenciar o estoque de ingredientes e produtos de forma automatizada. |
| RF17 | Enviar alertas quando um produto estiver com o estoque baixo. |
| RF18 | Permitir o registro de entradas e saídas de produtos no estoque. |
| RF19 | Permitir que os clientes criem contas para facilitar futuros pedidos. |
| RF20 | Permitir que os clientes visualizem o histórico de pedidos anteriores. |
| RF21 | Permitir que os clientes salvem seus endereços de entrega. |
| RF22 | Gerar relatórios de vendas diárias, semanais e mensais. |
| RF23 | Gerar relatórios de desempenho de produtos (mais e menos vendidos). |
| RF24 | Gerar relatórios financeiros (receitas e faturamento). |
| RF25 | Enviar notificações aos clientes sobre o status dos pedidos (e-mail/SMS). |
| RF26 | Notificar os administradores sobre novos pedidos e eventos críticos. |


## Regras de Negócio (RN)
RN01 - Apenas usuários com perfil de administrador podem cadastrar, editar ou remover produtos, categorias e gerenciar pedidos.
RN02 - Um pedido só pode ser alterado (cancelado ou editado) pelo cliente enquanto estiver com status “Pendente”.
RN03 - O sistema só permite finalizar um pedido se todos os itens tiverem estoque suficiente.
RN04 - O valor total do pedido deve ser atualizado automaticamente sempre que o cliente adicionar, remover ou alterar itens no carrinho.
RN05 - A entrega só pode ser realizada para endereços dentro da área de cobertura definida pelo estabelecimento.
RN06 - O sistema deve exigir autenticação para visualizar pedidos anteriores e salvar endereços.
RN07 - Pedidos com pagamento online (pix, cartão) só devem ser enviados à cozinha após confirmação automática do pagamento.

## Requisitos Não Funcionais (RNF)

RNF01 - Suportar alto volume de pedidos simultâneos, especialmente em horários de pico. |
| RNF02 | Garantir segurança dos dados do usuário (senhas, informações pessoais). |
| RNF03 | Ter uma interface intuitiva para administradores e clientes. |
| RNF04 | Design responsivo para dispositivos móveis e desktop. |
| RNF05 | Compatível com os principais navegadores (Chrome, Firefox, Edge). |
