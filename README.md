# exercicio_MVC_modulo_2

segue o link do draw.io contento o MVC:

https://drive.google.com/file/d/13XLpgMgSB4TJxhPpb0YMqRPSTOXxX_8R/view?usp=sharing



   No design do meu MVC, implementei o padrão com exemplos de cada componente. Ele funciona como um garçom em um restaurante, onde ações do usuário acionam o banco de dados quando o Modelo do MVC identifica a necessidade. Além disso, a solução inclui exemplos de como um site real poderia ser estruturado:

  - Modelo (Model): Representa os dados e a lógica de negócios. No caso do restaurante, o Modelo pode incluir classes que representam os pratos do cardápio, os pedidos dos clientes e as operações relacionadas ao gerenciamento do estoque.
  - Visão (View): Responsável por exibir a interface do usuário. No contexto do restaurante, as Views podem ser as páginas web onde os clientes podem visualizar o cardápio, fazer pedidos e acompanhar o status de seus pedidos em tempo real.
  - Controlador (Controller): Coordena as interações entre o Modelo e a Visão. No restaurante, os Controladores seriam responsáveis por receber os pedidos dos clientes, atualizar o Modelo com as informações do pedido e selecionar a View apropriada para exibir a confirmação do pedido ao cliente.
Essa arquitetura facilita a manutenção do código, pois separa claramente as responsabilidades e torna o sistema mais modular e escalável. Além disso, permite uma fácil integração com o banco de dados quando necessário, sem comprometer a estrutura geral do MVC.

A conexão entre os componentes ocorre da seguinte maneira:

  - Visão (View) para Controlador (Controller):
Quando o usuário interage com a interface do usuário, como clicando em um botão ou preenchendo um formulário, essa interação é capturada pela View.
A View então encaminha essa interação para o Controlador, geralmente por meio de eventos ou chamadas de função.
  - Controlador (Controller) para Modelo (Model):
O Controlador recebe a interação do usuário da View e decide qual ação tomar com base nela.
Ele então interage com o Modelo, solicitando atualizações, consultando ou modificando os dados conforme necessário.
  - Modelo (Model) para Visão (View):
Após o Modelo ser atualizado pelo Controlador, ele notifica a View sobre as mudanças relevantes nos dados.
A View então atualiza sua representação da interface do usuário para refletir essas mudanças, garantindo que o usuário veja a informação mais recente.
