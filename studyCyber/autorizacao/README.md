---
description: Processos de autenticação e autorização do usuário
---

# Autorização



### Autenticação x Autorização

<mark style="background-color:blue;">**Diferença:**</mark>

<mark style="color:blue;">Autenticação:</mark>  verifica e confirma a identidade do usuário <mark style="color:blue;">(quem é)</mark>

<mark style="color:blue;">Autorização:</mark> verifica e confirma as permissões do usuário <mark style="color:blue;">(o que pode fazer)</mark>



{% embed url="https://auth0.com/pt/intro-to-iam/authentication-vs-authorization" %}



### Tipos de Autorização

1. Autorização baseada em função: Definição: A autorização baseada em função envolve atribuir permissões com base nos cargos ou funções dos usuários dentro de uma organização. Exemplo: Um gerente pode ter permissão para aprovar despesas, enquanto um funcionário comum pode ter permissão apenas para enviar solicitações de despesas.
2. Autorização baseada em atributos: Definição: A autorização baseada em atributos leva em consideração as características específicas dos usuários, como idade, localização ou nível de acesso. Exemplo: Um sistema pode conceder permissão para acessar determinados dados apenas a usuários maiores de 18 anos.
3. Autorização baseada em contexto: Definição: A autorização baseada em contexto leva em consideração o ambiente em que o acesso está sendo solicitado. Exemplo: Um usuário pode ter permissão para acessar determinados recursos apenas quando estiver em um local específico, como o escritório da empresa.
4. Autorização baseada em política: Definição: A autorização baseada em política envolve a definição de regras e políticas que determinam quem tem permissão para acessar determinados recursos. Exemplo: Uma política pode ser estabelecida para permitir que apenas funcionários de determinados departamentos acessem informações confidenciais.

{% embed url="https://docs.infor.com/ln/10.5.1/pt-br/lnolh/help/tc/onlinemanual/000765b.html" %}

{% embed url="https://www.keepersecurity.com/blog/pt-br/2024/03/19/the-different-types-of-authorization-models/" %}

