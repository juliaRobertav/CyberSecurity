# Conceitos de Autorização SAP

Os sistemas SAP são conhecidos por seus recursos de segurança robustos e no centro dessa segurança está o conceito de autorização. Autorização no SAP refere-se ao processo de conceder aos usuários o acesso necessário para executar suas tarefas, garantindo ao mesmo tempo que eles não sejam capazes de acessar dados confidenciais ou restritos.&#x20;



### Componentes da Autorização SAP



<mark style="color:blue;">**Objetos de Autorização**</mark>&#x20;

Os objetos de autorização são os blocos de construção da autorização SAP. Cada objeto representa uma área específica de funcionalidade ou um processo de negócios. Por exemplo, existem objetos de autorização para acessar transações específicas, para visualizar ou modificar certos tipos de dados e para executar funções particulares dentro do sistema.

<mark style="color:blue;">**Campos de Autorização**</mark>&#x20;

Os campos de autorização são os atributos de um objeto de autorização que definem os direitos de acesso específicos concedidos a um usuário. Por exemplo, um campo pode especificar se um usuário tem permissão para criar, ler, atualizar ou excluir dados relacionados a um objeto específico.

<mark style="color:blue;">**Perfis de Autorização**</mark>&#x20;

Os perfis de autorização são coleções de objetos e campos de autorização que são atribuídos a usuários ou funções. Eles determinam os direitos de acesso que um usuário ou função tem dentro do sistema. Os perfis são atribuídos com base na função do usuário na organização e nas tarefas que precisam realizar.

<mark style="color:blue;">**Funções**</mark>&#x20;

As funções são coleções de perfis de autorização que são atribuídos a usuários. Elas representam a função ou cargo do usuário dentro da organização. Atribuindo funções aos usuários, as organizações podem simplificar a gestão dos direitos de acesso e garantir que os usuários tenham as permissões necessárias para realizar suas tarefas.

<mark style="color:blue;">**Registros Mestres de Usuário**</mark>&#x20;

Os registros mestres de usuário contêm informações sobre cada usuário, incluindo seu ID de usuário, senha e as funções e perfis atribuídos a eles. Os registros mestres de usuário são usados para autenticar os usuários e determinar seus direitos de acesso dentro do sistema.

<mark style="color:blue;">**A Hierarquia**</mark>&#x20;

A hierarquia de funções para objetos de autorização na SAP começa com objetos de autorização, que são agrupados em perfis de autorização. Esses perfis são então atribuídos a funções, que por sua vez são atribuídas a usuários. Essa hierarquia ajuda as organizações a gerenciar efetivamente os direitos de acesso e garantir que os usuários tenham as permissões apropriadas para realizar suas funções.

<mark style="color:blue;">**Níveis Organizacionais**</mark>&#x20;

Além das funções, a SAP também considera níveis organizacionais para determinar os direitos de acesso. Os níveis organizacionais representam a estrutura hierárquica de uma organização, como códigos de empresa, organizações de vendas e plantas. Os direitos de acesso podem ser restritos com base nesses níveis organizacionais, garantindo que os usuários tenham acesso apenas a dados relevantes para sua unidade organizacional.

<mark style="color:blue;">**Arquitetura da Autorização SAP**</mark>&#x20;

A autorização SAP é baseada em um modelo de controle de acesso baseado em funções (RBAC). Neste modelo, os usuários são atribuídos funções que correspondem às suas funções de trabalho, e cada função é atribuída aos perfis de autorização necessários para realizar essas funções. Esta abordagem ajuda a simplificar a gestão dos direitos de acesso agrupando os usuários com base em suas funções, em vez de gerenciar autorizações individuais.



