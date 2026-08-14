Atividade- Making History

História de Usuário:
Acompanhar pedido:
Como usuário do app, eu quero acompanhar o status do meu pedido em tempo real, 
para que eu saiba quando meu pedido vai chegar.

1. Dado que eu fiz um pedido e o pagamento foi aprovado, Quando eu abrir a tela do pedido, Então devo ver os 
status: "Preparando", "Saiu para entrega" e "Entregue" com horário atualizado.

2. Dado que o entregador está a caminho, Quando eu acessar o mapa, 
Então devo ver a localização do entregador atualizada a cada 15 segundos.

3. Dado que o pedido foi entregue, Quando o status mudar para "Entregue", 
Então devo receber uma notificação push de confirmação.

**Must**

História de Usuário:
Como restaurante parceiro, eu quero marcar um item do cardápio como indisponível, 
para que o usuário não faça pedidos de itens que não tenho no momento.

1.Dado que estou logado no painel do restaurante, Quando eu clicar em "Indisponível" em um item, 
Então o item deve sumir do cardápio do app em até 1 minuto.

2.Dado que um usuário tem um item indisponível no carrinho, Quando o restaurante marcar como indisponível, 
Então o usuário deve receber um alerta e o item deve ser removido do carrinho.

3.Dado que eu marquei um item como indisponível, Quando eu clicar em "Disponível" novamente, 
Então o item deve voltar a aparecer no cardápio.

**Should**

História de Usuário:
Como entregador, eu quero reportar um problema durante a entrega, 
para que o suporte possa me ajudar e o usuário seja avisado do atraso.

1. Dado que estou com uma entrega em andamento, Quando eu clicar em "Reportar Problema", Então devo conseguir escolher 
entre: "Endereço incorreto", "Cliente não atende", "Problema com veículo" e "Outro".

2. Dado que eu selecionei um problema, Quando eu enviar o relatório, 
Então o suporte e o usuário devem receber uma notificação com o motivo do atraso.

3. Dado que eu enviei o relatório, Quando o suporte responder, 
Então devo receber a orientação direto no app.

**Could**
