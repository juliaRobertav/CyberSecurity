---
description: Proteção de Rede
---

# Network Protection

<figure><img src="../.gitbook/assets/image (6).png" alt="" width="375"><figcaption></figcaption></figure>

* <mark style="background-color:purple;">SBC</mark>

Proteção de tráfego de voz (<mark style="color:purple;">Session Border Controller</mark>)

<mark style="color:purple;">Definição:</mark> Proteção de segurança para redes de voz principalmente protegendo o protocolo SIP (Session Initiation Protocol) utilizando em plataformas que usam VOIP (Voice over Internet Protocol.)

Protege ligações que podem conter dados sensíveis como por exemplo número de cartão de créditos

<mark style="color:purple;">Principais proteções:</mark> ACL, ataques DDoS, gerencia sessões SIP evitando fraudes e taxas com ligações, criptografia de sinalização

Também pode servir para interconectar diferentes sistemas com diferentes sinalizações de telefonia de forma segura



* <mark style="background-color:purple;">Mobile Security/MDM</mark>

<mark style="color:purple;">Definição</mark>: solução de segurança e gerenciamento de dispositivos móveis que certifica que os dispositivos que acessam os sistemas de uma empresa seguem a política de segurança

<mark style="color:purple;">Quais requisitos de segurança podem ser checados/aplicados?</mark>

* Aplicativos permitidos&#x20;
* Versão de Sistemas Operacional e Patchs&#x20;
* Gerenciar atualizações
* &#x20;Wipe de dispositivos&#x20;
* Isolar dados corporativos de dados pessoais&#x20;
* Se possui as políticas aplicadas&#x20;
* Se o dispositivos tem criptografia habilitada&#x20;
* Monitoramento e rastreamento do equipamento



* <mark style="background-color:purple;">Proxy</mark>

<mark style="color:purple;">Definição:</mark> solução de segurança que monitora a navegação e/ou acesso a web bloqueando conteúdos maliciosos ou impróprios

Virtual appliance é o tipo mais comum de implementação mas pode também estar agregado a um firewall UTM (Unified threat management/Gerenciamento Unificado de ameças.

<mark style="color:purple;">Método:</mark> utiliza uma base de dados mantidos por fabricantes classificando a categoria e reputação de websites

Faz varreduras por malwares

Pode ser usado também para manter a produtividade da força de trabalho de uma empresa



* <mark style="background-color:purple;">NAC (Networking acess control)</mark>

<mark style="color:purple;">Definição:</mark> Solução de segurança que se propõe a verificar a conformidade do endpoint como antivírus, IPS, análise de vulnerabilidade, autenticação e aplicação de políticas de segurança

Analisa se um dispositivo esta saudável para por exemplo decidir se permite a conexão a rede

Permite rastrear uma conexão, quando aconteceu, que IP usava, que usuário estava logado

Uso comum é verificar se o dispositivo esta autorizado a conectar em uma rede

Faz a verificação de pre-admissão e pós –admissão



* Wireless Security

Segurança em rede wireless pode ser protegida por soluções como WIPS e por práticas de aplicar políticas fortes de segurança;

<mark style="color:purple;">Tipos de ameaça cobertos pelo WIPS:</mark>&#x20;

* Rogue access points
* &#x20;Access Point Mal configurado&#x20;
* Associação não autorizada&#x20;
* Ataque man in the Middle&#x20;
* MAC spoofing&#x20;
* Ataque de DdoS

<mark style="color:purple;">Práticas de segurança em rede wireless:</mark>&#x20;

* Ocultar SSIP
* Filtrar MACs
* Protocolos seguros de criptografia
* Autenticação por certificado



* <mark style="background-color:purple;">Remote Access Security</mark>



* VPN cliente
* Single sign-on (SSO)
* PAM (Privileged access management)
* VDI (Virtual Desktop Infrastructure) ou DaaS (Desktop as Service)
* Soluções zero trust
