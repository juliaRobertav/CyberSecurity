# Descrever a defesa em profundidade

A defesa em profundidade usa uma abordagem em camadas de segurança, em vez de depender de um único perímetro. Uma estratégia de defesa em profundidade usa uma série de mecanismos para reduzir o avanço de um ataque. Cada camada fornece proteção para que, se uma camada for violada, uma camada subsequente impedirá que um invasor receba acesso não autorizado aos dados.

Camadas de exemplo de segurança podem incluir:

* Segurança **física**, como limitar o acesso a um datacenter para apenas o pessoal autorizado.
* Controles de segurança de **identidade e acesso**, como autenticação multifator ou acesso baseado em condição para controlar o acesso à infraestrutura e controle de alterações.
* A segurança de **perímetro** de sua rede corporativa inclui a proteção contra DDoS (ataque de negação de serviço distribuído) para filtrar ataques em grande escala antes que eles possam causar uma negação de serviço para os usuários.
* Segurança de **rede**, como segmentação de rede e controles de acesso à rede, para limitar a comunicação entre os recursos.
* A segurança da camada **Computação**, como a proteção do acesso a máquinas virtuais, local ou na nuvem, fechando determinadas portas.
* A segurança da camada **Aplicativo** garante que os aplicativos estejam seguros e livres de vulnerabilidades de segurança.
* A segurança da camada **Dados**, incluindo controles para gerenciar o acesso aos dados de negócios e clientes e à criptografia para proteger os dados.

![Diagram showing defense in depth layers of security which are used to protect sensitive data.](https://learn.microsoft.com/pt-br/training/wwl-sci/describe-security-concepts-methodologies/media/4-defense-depth.png)

#### Confidencialidade, Integridade, Disponibilidade (CIA) <a href="#confidentiality-integrity-availability-cia" id="confidentiality-integrity-availability-cia"></a>

Como descrito acima, uma estratégia de defesa em profundidade usa uma série de mecanismos para reduzir o avanço de um ataque. Todos os diferentes mecanismos (tecnologias, processos e treinamento) são elementos de uma estratégia de segurança cibernética, cujos objetivos incluem garantir a confidencialidade, integridade e disponibilidade; muitas vezes referidas como CIA (confidentiality, integrity e availability).

![Diagram showing the Confidentiality, Integrity, Availability (CIA) triangle.](https://learn.microsoft.com/pt-br/training/wwl-sci/describe-security-concepts-methodologies/media/4-confidentiality-integrity-availability.png)

* A **Confidencialidade** se refere à necessidade de manter os dados confidenciais, como informações do cliente, senhas ou dados financeiros. Você pode criptografar os dados para mantê-los confidenciais, mas também precisa manter as chaves de criptografia confidenciais. Confidencialidade é a parte mais visível da segurança. Podemos ver claramente a necessidade de dados confidenciais, chaves, senhas e outros segredos que devem ser mantidos confidenciais.
* A **Integridade** se refere à manutenção de dados ou mensagens corretas. Ao enviar uma mensagem de email, você deve ter certeza de que a mensagem recebida é igual à mensagem enviada. Ao armazenar dados em um banco de dados, você deve ter certeza de que os dados recuperados são os mesmos que os dados armazenados. A criptografia de dados mantém a confidencialidade, mas você deve ser capaz de descriptografar os dados de forma que eles se mantenham tal como eram antes de serem criptografados. Integridade trata-se da confiança de que os dados não foram adulterados ou alterados.
* **Disponibilidade** refere-se a tornar os dados disponíveis para aqueles que precisam deles, quando eles precisam. É importante para a organização manter os dados do cliente seguros, mas ao mesmo tempo eles também devem estar disponíveis para os funcionários que lidam com os clientes. Embora possa ser mais seguro armazenar os dados em um formato criptografado, os funcionários precisam acessar dados descriptografados.

Embora os objetivos de uma estratégia de segurança cibernética sejam preservar a confidencialidade, integridade e disponibilidade de sistemas, redes, aplicativos e dados; o objetivo dos cibercriminosos é interromper esses objetivos. O portfólio da Microsoft inclui as soluções e tecnologias para permitir que as organizações cumpram os objetivos da tríade da CIA.
