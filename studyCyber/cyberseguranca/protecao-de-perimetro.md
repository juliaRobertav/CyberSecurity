# Proteção de Perímetro

* <mark style="background-color:orange;">Firewall</mark>

<mark style="color:orange;">Definição:</mark> solução que monitora tráfego de entrada e saída de rede permitindo ou bloqueando através de políticas de segurança com o objetivo de estabelecer uma barreira de segurança contra tráfegos maliciosos entre a rede de uma empresa e redes externas como a internet.

<mark style="color:orange;">Inspeciona:</mark>  Origem, destino, porta e protocolo.

<mark style="color:orange;">Gerenciamento padrão:</mark> Bloqueia tudo e permite progressivamente.

<mark style="color:orange;">Tipos:</mark> Software, applicance físico, appliance virtual ou solução em nuvem.

<mark style="color:orange;">Funções:</mark>  IDS/IPS, inspeção de malwares, inspeção de SSL, concentrados de VPN etc.

<mark style="color:orange;">Firewall leste-oeste:</mark>  Tipo de firewall que implementa a mesma proteção entre servidores geralmente dentro do mesmo Data Center.

* <mark style="background-color:orange;">IDS/IPS</mark>

<mark style="color:orange;">Definição:</mark> Proteção de segurança que analisa pacotes em um nível de profundidade maior que um firewall, sua existência não elimina a necessidade de um firewall.

<mark style="color:orange;">Como trabalha?</mark>&#x20;

Inspecionando a assinatura do pacote.

Geralmente instalado junto com o firewall mas pode funcionar em dispositivos específicos.

<mark style="color:orange;">Resumo:</mark> Faz uma analise mais comportamental.

* <mark style="background-color:orange;">Sandbox</mark>

<mark style="color:orange;">Definição:</mark>  Solução de segurança hospedada em ambiente isolado em uma rede que imita os ambientes operacionais e comportamentos de um usuário utilizada para executar conteúdos desconhecidos ou suspeitos com segurança.

Pode ser usado com SaaS ou on premise.

<mark style="color:orange;">Beneficios:</mark> &#x20;

* Evita que malwares tragam danos ao dispositivos do usuário ou rede corportativa.
* Protege contra ataques zero-day.
* Utiliza analise avançada (comportamental).
* Protege contra ataques avançadas (APT).

{% embed url="https://www.virustotal.com/gui/home/url" %}

* <mark style="background-color:orange;">Antiphishing</mark>

<mark style="color:orange;">Definição:</mark> Solução que visa proteger a empresa contra e-mails indesejados (spams) e ataques efetuados por e-mail através de filtrar e técnicas de varredura do conteúdo de mensagens.

<mark style="color:orange;">Tipos:</mark>  Softwares, appliance físico, virtual appliance ou PaaS.

Varredura no corpo e anexo da mensagem detectando malwares.

<mark style="color:orange;">Métodos de checagem:</mark>  Estatística, heurística ou predativo.

* <mark style="background-color:orange;">DLP</mark>

<mark style="color:orange;">Definição:</mark>  Solução para prevenir vazamento de informações e movimentação inadequadas de dados sensíveis ao negócio (número de cartões, informações estratégicas) através de monitoramento, detecção e bloqueio.

Pode ser instalado em outras camadas da rede.

<mark style="color:orange;">Protege dados em várias etapas:</mark> em armazenamento, em transito ou em uso.

Técnicas para identificar e classificar tipos de dados e advertir.

Pode educar os colaboradores para manejar dados de forma cuidadosa.

<mark style="color:orange;">Protege dados em diversas mídias:</mark>  e-mail, pen drives, dispositivos móveis, servidores de arquivos, IM, cloud services, OS clipboard e até mesmo impressora.

* <mark style="background-color:orange;">Segurança Física</mark>

<mark style="color:orange;">Definição:</mark> O departamento de Cyber Security precisa se preocupar não somente com a segurança lógica mas também com a segurança física, de nada adianta você ter as melhores soluções e controles lógicos se você não protege seu data center fisicamente por exemplo. Muitas vezes essa responsabilidade é dividida com a área administrativa ou facilities da empresa.

<mark style="color:orange;">Objetivo:</mark> proteger e prevenir contra ameaças as dependências físicas de uma organização incluindo espionagem, sabotagem terrorismo, danos e roubos.

<mark style="color:orange;">Proteger o que?</mark>&#x20;

Ameaças como roubo e dano, a bens como pessoal (Ex: escritório da empresa) equipamentos (nos Data Centers e salas técnicas), instalações, materiais e informações.

<mark style="color:orange;">Soluções utilizadas:</mark>  Câmeras de vigilância (para verificar quem esta acessando ou que aconteceu, quem cometeu o delito), controle de acesso, extintores de incêndio, detectores de fumaça, ar condicionado, no-breaks cages, segurança patrimoniais.

* Boa parte do trabalho do profissional de cybersecurity é verificar se tem alguma falha nas instalações como por exemplo falta de câmeras ou ponto cego e auditar se somente pessoas autorizadas estão acessando áreas restritas como por exemplo a data center da empresa.
