# Contenção e Filtragem Inteligente

![Contanment and filetering logo](/assets/img/conteinment-filtering-logo.png){:.centered}

A função do módulo de Contenção e Filtragem Inteligente é mitigar ataques identificados por outros módulos ou em resposta a uma solicitação direta de API do Orquestrador de Rede. Neste contexto, contenção e filtragem podem ser discutidas como duas técnicas de mitigação de ataques.

## Contenção

As técnicas de contenção geralmente estão relacionadas ao uso de ferramentas IPS e se baseiam na manipulação do tráfego originado do atacante. Algumas delas são:

- Encerramento da conexão, por meio do envio de pacotes TCP RST;
- Aplicação de regras de firewall para bloquear todo o tráfego proveniente de um usuário previamente identificado como atacante;
- Limitações de banda e requisição, ou seja, criar um limite na quantidade de dados transmitidos entre o atacante e a vítima, bem como limitar a quantidade de conexões em andamento entre eles;
- Redirecionamento do tráfego para uma máquina de quarentena, isolando assim o tráfego malicioso do restante da rede;
- Redirecionamento do tráfego para um sistema honeypot, que consiste em um sistema que emula alvos para receber ataques propositalmente, a fim de promover seu estudo.
- Remoção de trechos de tráfego malicioso.

## Filtragem / Scrubbing

Os serviços de scrubbing estão relacionados ao envio do tráfego para servidores DNS ou BGP, a fim de promover a filtragem do tráfego e, assim, o alvo do ataque receberá apenas tráfego legítimo. Uma das diferenças entre essa técnica e a contenção de tráfego é a manipulação direta do tráfego realizada nas técnicas de contenção, enquanto nos serviços de scrubbing as ações de mitigação são tomadas pelos servidores DNS ou BGP.

Neste contexto, podemos concluir que a filtragem de tráfego é uma técnica que requer menos configuração do que a técnica de contenção de tráfego.
