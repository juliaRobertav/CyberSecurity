---
description: O que é ABAC, RBAC e como decompor mecanismos AuthZ
---

# Decompor mecanismos de autorização

Conteúdo baseado nesse vídeo:

{% embed url="https://youtu.be/FthMYA_OHC8?si=Yih546KvpldSNPH1" %}

### Acessos

Nem sempre autorização é definir os acessos por cargo (admin por exemplo), as vezes é preciso decompor esse mecanismo de autorização.

Definir quais são ações em específico e essas coleções de ações específicas são vinculadas as funcionalidades e então são criadas políticas de acesso aonde o grupo dessas permissões vão formar um cargo, role dentro do sistema.

As vezes essas ações não são apenas para um único serviço, mas para várias aplicações dentro do sistema, sejam autorizações externas ou internas.

Por exemplo, quem trabalha com contas a pagar dentro da empresa, poderia ver os recursos de RH?



### Subject, Object & Activity

**Subject:** A pessoa ou entidade que concede a autorização.

**Object:** A pessoa, entidade ou atividade que recebe a permissão para ser realizada.

**Activity:** A ação, operação ou procedimento que requer permissão ou consentimento para ser realizada.
