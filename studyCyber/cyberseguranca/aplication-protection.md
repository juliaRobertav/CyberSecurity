---
description: Proteção de aplicativos
---

# Aplication Protection

<figure><img src="../.gitbook/assets/image (10).png" alt="" width="375"><figcaption></figcaption></figure>

* <mark style="background-color:yellow;">Code Review</mark>

<mark style="color:yellow;">Definição:</mark> code review ou revisão de código é o processo pelo qual visa garantir que uma aplicação é desenvolvida sem bugs ou vulnerabilidades de segurança

<mark style="color:yellow;">Principais checagens:</mark>

* Melhores práticas de desenvolvimento
* Detecção de erros
* Vulnerabilidades

<mark style="color:yellow;">Objetivos de segurança:</mark> verificar o nível de segurança antes de ser publicado

Existem diversas soluções que automatizam o processo para citar uma das principais podemos mencionar o sonarqube

Site:&#x20;

{% embed url="https://www.sonarsource.com/products/sonarqube/" %}

Geralmente é verificada em todos os passos da esteira



* <mark style="background-color:yellow;">Web Applicantion Firewall (WAF)</mark>

<mark style="color:yellow;">Definição:</mark> firewall de aplicações que filtra e monitora tráfegos de camadas 7 como por exemplo HTTP e HTTPs

Função principal é proteger uma aplicação com bugs e/ou vulnerabilidade

Protege principalmente contra ataques do tipo: XSS (Cross Site Scripiting), injeção SQL etc.

<mark style="color:yellow;">Tipos:</mark> Serviço SaaS e virtual appliance e appliance físico

Serve como proxy reverso



* <mark style="background-color:yellow;">MFA</mark>

<mark style="color:yellow;">Definição:</mark> MFA é um mecanismo de autenticação que exige a apresentação de duas ou mais evidencias para permitir o acesso a um sistema

<mark style="color:yellow;">Exemplo:</mark> Além de prover seu usuário e senha você precisa prover um token (código randômico que expira geralmente de 4 a 6 dígitos) para acessar um sistema

Protege o vazamento de credenciais

<mark style="color:yellow;">Meios usados:</mark> aplicativo de celular (mais usado), SMS, ligação telefônica, e-mail, token físico, Smartcard, ou biometria como por exemplo impressão digital

Provedores de serviço em nuvem já possuem soluções gratuitas de MFA
