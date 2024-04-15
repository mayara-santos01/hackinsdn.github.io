# Detecção de Anomalias com Inteligência Artificial (IA)

![Anomaly Detection Logo](/assets/img/anomaly-detection-logo.png){:.centered}

A inteligência artificial teve um grande desenvolvimento nos últimos anos devido a fatores que incluem a quantidade crescente de dados disponíveis para estudo, melhorias em algoritmos e hardware. O progresso da IA possibilitou a realização de tarefas que eram, até então, basicamente impossíveis de serem calculadas [Došilović et al, 2018]. Nesse sentido, a IA já está sendo usada para promover a segurança cibernética e, por exemplo, existem ferramentas que a utilizam para detectar anomalias no tráfego, funcionando como uma alternativa à detecção baseada em assinaturas.

Nessa perspectiva, é válido destacar algumas vantagens e desafios do uso de IA na detecção de anomalias.

## Vantagens

- Possibilidade de detecção de ataques desconhecidos, incluindo ataques *dayzero* (vulnerabilidades ainda não conhecidas);
- Maior facilidade em lidar com tráfego criptografado, aplicando técnicas em cabeçalhos de pacotes para detectar anomalias;
- A detecção baseada em assinatura requer atualização frequente nos bancos de dados que contêm informações sobre ataques já conhecidos, e com a detecção de anomalias baseada em IA, o uso e a atualização de bancos de dados não são necessários.

## Desafios

- É mais difícil aplicar escalabilidade às soluções, ou seja, técnicas que possam ser aplicadas para rastrear grandes quantidades de tráfego;
- Obtenção de respostas em tempo real;
- Criação de bancos de dados para treinar algoritmos de Aprendizado de Máquina.

## Ferramentas de detecção de anomalias

Existem diversas ferramentas para promover a detecção de anomalias de tráfego, e algumas das que utilizam técnicas de IA são:

- Hogzilla-IDS: Ferramenta de detecção de anomalias de rede que usa técnicas de IA (não especificadas);
- NeMo-DDoS: Software focado na detecção de ataques DDoS, funciona em conjunto com outros softwares, como Netflow e IPFIX, para promover relatórios de Fluxo de IP. Utiliza Aprendizado de Máquina para detectar padrões de tráfego e, consequentemente, anomalias.
- Kentik: Software que detecta ataques DDoS através da combinação de dados de tabelas BGP, Fluxos de IP (Sflow, Netflow, IPFIX). O Kentik utiliza técnicas de Inteligência Artificial e Aprendizado de Máquina, porém, não há explicação adicional sobre as técnicas aplicadas.

#### Referências:

1. F. K. Došilović, M. Brčić and N. Hlupić, "Explainable artificial intelligence: A survey," 2018 41st International Convention on Information and Communication Technology, Electronics and Microelectronics (MIPRO), Opatija, Croatia, 2018, pp. 0210-0215, doi: 10.23919/MIPRO.2018.8400040.
