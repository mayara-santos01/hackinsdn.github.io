# Suricata

![Suricata logo](/assets/img/suricata-logo.png){:.centered}

## O que é Suricata?

- Suricata é um mecanismo de alta performance para IDS (Sistema de Detecção de Intrusão), IPS (Sistema de Prevenção de Intrusão) e Monitoramento de Segurança de Rede. É um software open source mantido por uma fundação sem fins lucrativos administrada pela comunidade, a Open Information Security Foundation (OISF). O Suricata é desenvolvido pela OISF.
- Sendo assim, como um IDS, o Suricata pode ser usado para analisar tráfego de rede ao vivo, a partir de uma interface do dispositivo escolhido, ou para analisar pacotes que contêm tráfego, como arquivos *.pcap*.
- O Suricata contém um amplo conjunto de regras, frequentemente atualizadas, e os usuários também podem criar suas próprias regras, ampliando as possibilidades de detecção de ataques.
- A partir das regras, alertas são gerados, e assim as possibilidades de ataques podem ser analisadas por outros programas, caso o Suricata esteja sendo usado apenas como um IDS. 

## Uso do Suricata no projeto HackInSDN

- O HackInSDN tem como objetivo criar uma solução de segurança de rede, que poderá ser utilizada por instituições de ensino para treinar alunos que serão capazes de trabalhar com segurança de rede. Também pode ser usado por empresas para promover a segurança em suas redes.
- Nesse sentido, o Suricata será utilizado como um IDS para analisar o tráfego de dados ao vivo de interfaces específicas. Dessa forma, o Suricata será essencial para detectar ataques que estão entrando na rede analisada, e a possibilidade de integração com o controlador SDN e outros módulos será fundamental para promover a prevenção de ataques. Em outras palavras, o Suricata detectará ataques que serão analisados e mitigados por outros módulos.

**Referências:**

1. Documentação Oficial do Suricata: [https://docs.suricata.io/en/latest/](https://docs.suricata.io/en/latest/)
