## Requisitos

### Metodologia

 Apartir de uma reunião feita no hangouts com todos os membros do grupo foi gerado um [brainstorm](../geracao-alternativas/) e analisando este documento foram gerados os seguintes requisitos que aqui estão separados por categoria do app.

### Elicitação

**MoSCoW**

|Código|Descrição|Prioridade|
|--|--|--|
|AD01|O app irá notificar o usuário quando o prazo de retirada de seu pedido estiver acabando|Should|
|AD02|O app irá notificar o usuário quando houverem promoções|Could|
|AD03|O app irá notificar o usuário quando houverem novos itens no cardápio|Could|
|AD04|O usuário poderá se cadastrar no app|Must|
|AD05|O usuário poderá recuperar sua senha caso tenha esquecido|Must|
|AD06|O app irá criar cartões de fidelidade|Should|
|AD07|O app irá salvar crédito|Should|
|AD08|O app irá aceitar pagamentos com cartão de crédito|Must|
|AD09|O app irá aceitar pagamentos com dinheiro|Could|
|AD10|O app irá criar uma sacola com itens de um pedido|Must|
|AD11|O app irá solicitar a data de retirada do pedido (Hoje/Amanha)|Must|
|AD12|O usuário irá ter a possibilidade de favoritar um item|Should|
|AD13|O usuário irá ter a possibilidade de dar uma nota para um item|Should|
|AD14|O usuário irá ter a possibilidade de comentar sobre um item|Could|
|AD15|O usuário irá ter a possibilidade de colocar uma observação em um item|Would|
|AD16|O usuário irá ter a possibilidade de escolher diferentes combinações/tipos/sabores para um item|Must|
|AD17|O usuário irá ter a possibilidade de editar um item na sacola|Must|
|AD18|O usuário irá ter a possibilidade de remover um item na sacola|Must|
|AD19|O usuário irá ter a possibilidade de buscar um item pelo nome|Would|
|AD20|Os pedidos feitos pelo app irão ser somados a um cartão fidelidade|Should|
|AD21|O usuário irá completar um cartão quando atingir 10 pedidos|Should|
|AD22|Existirá um cartão fidelidade para compra de sanduíches gregos e outro para almoços que poderá ser usado em um pedido pelo usuário|Should|
|AD23|O admin poderá editar, criar ou apagar itens no cardápio|Must|
|AD24|O admin poderá marcar um item como esgotado para o dia atual|Must|
|AD25|O admin poderá criar categorias para o cardápio|Must|
|AD26|O app terá um histórico de pedidos do usuário|Must|
|AD27|O app irá separar os pedidos em fechados, abertos e expirados|Must|
|AD28|O app fornecerá dados resumidos sobre os pedidos para o admin|Must|
|AD29|O admin irá ler os QR-codes dos pedidos para validá-los e realizar uma ação de finalizar ou adiar o pedido|Must|
|AD30|O app irá organizar os pedidos em ordem cronológica de tempo|Must|
|AD31|Cada pedido terá informações relevantes (Itens do pedido, total, forma de pagamento, data do pedido, dia de retirada, telefone do grego)|Must|
|AD32|O usuário poderá avaliar um pedido|Must|
|AD33|O usuário terá a possibilidade de cancelar um pedido caso esteja dentro do prazo de cancelamento|Must|
|AD34|O usuário terá a possibilidade de refazer o mesmo pedido|Must|
|AD35|O usuário irá ter a possibilidade de adicionar uma foto de perfil|Would|
|AD36|O app irá ter uma sessão para a politica de privacidade e termos de uso|Must|
|AD37|O usuário irá ter a possibilidade de avaliar o fast food do grego|Must|
|AD38|O usuário irá ter a possibilidade de editar seus dados (Nome, Email, CPF, Celular)|Must|
|AD39|O usuário irá ter a possibilidade de ver, adicionar e editar suas formas de pagamento|Must|
|AD40|O usuário terá a possibilidade de visualizar seus pedidos favoritos|Must|
|AD41|O usuário terá a possibilidade de checar seus cartões de fidelidade|Should|


### Pontos importantes

|Q01||
|--|--|
|**Questão**|Como proceder quando ocorrerem fraudes nos pedidos feitos com dinheiro?|
|**Explicação**|Ao fazer um pedido com dinheiro, o usuário só terá que pagá-lo na hora de buscar o lanche. Usuários mal intencionados podem realizar vários pedidos e não irem buscá-los. Isto iria projudicar o grego em questões de lojistica e reservas desnecessárias de lanches.|
|**Solução**|Caso um cliente cometa 3 fraudes com pedidos de dinheiro, ele somente poderá fazer pedidos com cartão de crédito.|

--- 

|Q02||
|--|--|
|**Questão**|Como proceder quando o cliente deseja cancelar o pedido?|
|**Explicação**|Ao fazer um pedido com dinheiro, o usuário só terá que pagá-lo na hora de buscar o lanche. Usuários mal intencionados podem realizar vários pedidos e não irem buscá-los. Isto iria projudicar o grego em questões de lojistica e reservas desnecessárias de lanches.|
|**Solução**|Se o cliente fazer o pedido para o mesmo dia, poderá cancelar o pedido neste dia e receber um estorno (caso tenha pedido pelo cartao). Caso tenho pedido para o próximo dia, poderá cancelar o pedido apenas no mesmo dia.|

---

|Q03||
|--|--|
|**Questão**|Qual a capacidade de atendimento do grego em um dia?|
|**Explicação**|A quantidade máxima de vendas por dia do fast food deve ser mensurada. Visto que haverá a possibilidade de realizar reservar de lanches, o cliente não pode ficar sem seu pedido. Portanto caso o limite de reservas seja excedido, o app não deverá permitir realizar novos pedidos.|
|**Solução**| A se definir em reunião com o admin |

---

|Q04||
|--|--|
|**Questão**|Qual a quantidade máxima permitida de itens em um pedido?|
|**Explicação**| |
|**Solução**| |

---

|Q05||
|--|--|
|**Questão**|Como um pedido pode expirar?|
|**Explicação**| |
|**Solução**| |

---

|Q06||
|--|--|
|**Questão**|Como o usuário pode entrar em contato com o grego?|
|**Explicação**| |
|**Solução**| |

---

|Q07||
|--|--|
|**Questão**|Como o cliente deve proceder quando um pedido expirar?|
|**Explicação**| |
|**Solução**| |

---

|Q08||
|--|--|
|**Questão**|Como proceder quando um cliente fizer um pedido e quando for retirado-lo o produto estar esgotado?|
|**Explicação**| |
|**Solução**| |

---

|Q09||
|--|--|
|**Questão**|Como o admin deve proceder quando um produto se esgotar?|
|**Explicação**| |
|**Solução**| |

---
