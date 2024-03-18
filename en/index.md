HackInSDN is a framework that provides programmable infrastructure for teaching/learning networking and cybersecurity using testbed environments. Leveraging the network programmability provided by SDN environments, along with modern and classic network security tools, the HackInSDN framework enables enriched teaching and learning environment for advanced topics in Cybersecurity and Networking. A few examples of areas for studying, experimentation and research using HackInSDN include: Intrusion Detection Systems, Anoumaly Detection supported by Artificial Intelligence and Machine Learning, Dynamic Attack Mitigation, Isolated attacks simulation, Threat Intelligence information sharing, etc.

The HackInSDN can be instantiated on distributed testbed environments such as RNP's national testbed infrastructure, as well as other testbed enivonments.

# Overview

The following picture ilustrates overall HackInSDN architecture.

![HackInSDN big picture](/assets/img/hackinsdn.png){:.centered}

The main components are presented below:

- **Programmable Network Orchestrator**: the network Orchestrator plays a central role on HackInSDN architecture by enabling provisioning, management and monitoring services, as well as integrating all other components. The Kytos-ng (https://kytos-ng.github.io) SDN orchestrator is used in HackInSDN framework, because it provides at-scale production-grade SDN orchestration along with a robust and flexible software layer.
- **Adaptive Mirroring**: this compoment will be developed to allow granular traffic mirroring on the services provisioned by the network Orchestrator for traffic inspection and monitoring.
- **Intelligent Containment and Filtering**: the goal here is to enable attack mitigation and filtering from the anoumaly events and alerts detected, or even from network operator requests through the API.

- **AI-Powered Anomaly Detection**: (translation peding - work in progress) este componente será integrado ao Orquestrador de redes e receberá uma série de métricas de rede para então processar algoritmos de detecção de anomalias via Aprendizagem de Máquina Estatística e então gerar Alertas de Anômalia.
- **Zeek Network Security Monitoring**: (translation peding - work in progress)A solução de IDS Zeek é uma plataforma aberta que permite integração com outros sistemas para detecção de anomalias customizadas ou com base em assinaturas conhecidas de ataques.
- **MISP Threat Intelligence and Sharing**: (translation peding - work in progress)mecanismos de inteligência de ameaça e compartilhamento de informações de segurança são essenciais para defesa e pesquisa em segurança atualmente.
- **Adversary Simulator**: (translation peding - work in progress)um conjunto de ferramentas do estado da arte e voltadas para offensive security será disponibilizada como parte do projeto HackInSDN para ser utilizadas na perspectiva de hacking ético e simular tráfego malicioso no ambiente descrito acima.

# Partern Organizations

{:.text-align-center}
[![UFBA logo](/assets/img/ufba.png)](https://www.ufba.br)
[![IFBA logo](/assets/img/ifba.png)](https://www.ifba.edu.br)
[![FIU logo](/assets/img/fiu.png)](https://www.fiu.edu)

{:.text-align-center}
[![INSERT logo](/assets/img/insert.png)](http://insert.ufba.br)
[![Amlight Logo](/assets/img/amlight.png)](https://www.amlight.net)


# Acknowledgements

HackInSDN is funded by *Chamada Hackers do Bem* open call, [chamada pública para Pesquisa e Desenvolvimento 2023](https://www.rnp.br/noticias/hackers-do-bem-resultado-da-chamada-publica-para-pesquisa-e-desenvolvimento-2023){:target="_blank"}.

Read more about the [Hackers do Bem project](https://hackersdobem.org.br){:target="_blank"}.

# Additional information

 - [Getting started](./getting-started.html)
 - [Publications](./publications.html)
 - [Technical guides](./technical-guides.html)
 - [HackInSDN team](./hackinsdn-team.html)
 - [Source code and Licensing](./source-code-license.html)

# Support

Have you found a bug or wants to request a feature? [Open an issue!](https://github.com/hackinsdn/hackinsdn/issues)

To contact our team, send an e-mail to **hackinsdn [AT] ufba.br**.
