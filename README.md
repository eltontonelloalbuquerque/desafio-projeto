# desafio-projeto
Este projeto implementa um sistema de gestão de contas de clientes, permitindo que sejam cadastrados como PJ ou PF, com múltiplas formas de pagamento e acompanhamento de entregas (status e código de rastreio). O modelo visa flexibilidade e eficiência na administração de pedidos e transações.

Objetivos do Desafio:

Cliente PJ e PF: O modelo agora permite que um cliente seja classificado como Pessoa Jurídica (PJ) ou Pessoa Física (PF), mas nunca ambas as opções ao mesmo tempo.
Pagamento: Cada cliente pode cadastrar mais de uma forma de pagamento, permitindo maior flexibilidade no gerenciamento de suas transações.
Entrega: A funcionalidade de entrega foi aprimorada para incluir status da entrega e um código de rastreio, permitindo o acompanhamento da entrega de forma eficiente.
Como Funciona
Este sistema gerencia as contas de clientes, suas formas de pagamento e os detalhes das entregas realizadas. Aqui está a estrutura do modelo:

1. Cliente
O cliente pode ser registrado como PJ ou PF, com campos exclusivos para cada tipo de cliente. A conta do cliente não pode ser configurada para ser ambos ao mesmo tempo.

2. Pagamento
Cada cliente pode ter várias formas de pagamento, como cartão de crédito, débito, boleto, etc. Esse modelo permite a adição de múltiplos métodos, facilitando o processo de transações financeiras.

3. Entrega
Cada pedido realizado pode ser acompanhado por um status, que pode ser: "Em processamento", "Enviado", "Entregue" e outros, além de um código de rastreio para facilitar a localização do pacote.
