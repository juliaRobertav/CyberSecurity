# Descrever o modelo de responsabilidade compartilhada

Em organizações que executam apenas hardware e software locais, a organização é 100% responsável por implementar segurança e conformidade. Com os serviços baseados em nuvem, essa responsabilidade é compartilhada entre o cliente e o provedor de nuvem.

O _modelo de responsabilidade compartilhada_ identifica quais tarefas de segurança são tratadas pelo provedor de nuvem e quais tarefas de segurança são tratadas por você, o cliente. As responsabilidades variam dependendo de onde a carga de trabalho está hospedada:

* SaaS (software como serviço)
* PaaS (plataforma como serviço)
* IaaS (infraestrutura como serviço)
* Datacenter local

O modelo de responsabilidade compartilhada torna as responsabilidades claras. Quando as organizações movem dados para a nuvem, algumas responsabilidades são transferidas para o provedor de nuvem e outras para a organização do cliente.

O diagrama a seguir ilustra as áreas de responsabilidade entre o cliente e o provedor de nuvem, de acordo com o local em que os dados são mantidos.

![Diagram showing the Shared responsibility model responsibilities by type.](https://learn.microsoft.com/pt-br/training/wwl-sci/describe-security-concepts-methodologies/media/3-shared-responsibility-model.png)

* **Datacenters locais**. Em um datacenter local, você tem a responsabilidade de tudo, desde a segurança física até a criptografia de dados confidenciais.
* **IaaS (Infraestrutura como Serviço)**. De todos os serviços de nuvem, a IaaS requer o máximo de gerenciamento pelo cliente de nuvem. Com a IaaS, você está usando a infraestrutura de computação do provedor de nuvem. O cliente de nuvem não é responsável pelos componentes físicos, como computadores e rede, ou pela segurança física do datacenter. No entanto, o cliente da nuvem ainda é responsável pelos componentes de software executados nessa infraestrutura de computação, como sistemas operacionais, controles de rede, aplicativos e proteção de dados.
* **PaaS (Plataforma como Serviço)**. O PaaS fornece um ambiente para criação, teste e implantação de aplicativos de software. A meta da PaaS é ajudar você a criar um aplicativo rapidamente sem a necessidade de gerenciar a infraestrutura subjacente. Com o PaaS, o provedor de nuvem gerencia o hardware e os sistemas operacionais, e o cliente é responsável por aplicativos e dados.
* **SaaS (Software como Serviço)**. O SaaS é hospedado e gerenciado pelo provedor de nuvem para o cliente. Normalmente, ele é licenciado por meio de uma assinatura mensal ou anual. O Microsoft 365, o Skype e o Dynamics CRM Online são todos exemplos de softwares SaaS. O SaaS requer a menor quantidade de gerenciamento pelo cliente de nuvem. O provedor de nuvem é responsável por gerenciar tudo, exceto dados, dispositivos, contas e identidades.

Para todos os tipos de implantação de nuvem você, o cliente de nuvem, possui seus dados e suas identidades. Você é responsável por proteger a segurança de seus dados e identidades e recursos locais, incluindo dispositivos móveis, computadores, impressoras e muito mais.

Em resumo, as responsabilidades sempre retidas pela organização do cliente incluem:

* Informações e dados
* Dispositivos (móveis e PCs)
* Contas e identidades

O benefício do modelo de responsabilidade compartilhada é que as responsabilidades das organizações são claras, assim como as do provedor de nuvem
