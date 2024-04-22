# Orquestrador de redes programável

[![Kytos-ng logo](assets/img/kytosng-logo.png){:.centered}](https://github.com/kytos-ng/kytos?tab=readme-ov-file#kytos-ngkytos)

Uma rede definida por software (SDN) é uma rede mais centralizada, em comparação com as tradicionais, na qual o plano de dados é separado do plano de controle. Nesse sentido, o plano de controle é representado pelo controlador SDN, enquanto os roteadores e switches, nessa estrutura, se dedicam exclusivamente às transferências de dados [SALMAN et al, 2020]. A comunicação entre controladores, switches e roteadores pode ser feita usando o protocolo OpenFlow.

O projeto HackInSDN utiliza o Kytos-ng como seu controlador SDN. Kytos-ng é um controlador SDN focado em estabilidade, escalabilidade e extensibilidade, sendo resultado de um trabalho conjunto entre a Universidade de São Paulo (UNESP), a Rede Acadêmica de São Paulo (rednesp) e a Florida International University (FIU).

Uma das principais características do Kytos é a possibilidade de criar diversos Network Apps (Napps), o que confere grande flexibilidade operacional. Além disso, é uma aplicação central leve, o que significa que poucos recursos computacionais são necessários para a sua instalação.

O Kytos-ng está sendo utilizado em projetos como [AmLight](https://www.amlight.net/), [AtlanticWave-SDX](https://www.atlanticwave-sdx.net/) e [Q-Factor](https://www.q-factor.io/).

## Funções principais de um controlador SDN

- Gerenciamento: O controlador precisa ter conhecimento sobre a topologia da rede, e também deve ser capaz de reconhecer novos links, para garantir a conexão de todos os nós. Além disso, o controlador precisa ter estatísticas sobre os componentes da rede.
- Estabilidade: O controlador deve ser capaz de manter o circuito da rede em funcionamento, ou seja, ser capaz de detectar falhas e continuar fornecendo serviços para a rede, a fim de não interromper completamente os serviços.
- Dados: O controlador precisa garantir a persistência dos dados em algum nível, o que significa que, em caso de falhas abruptas, o sistema poderá continuar os processos graças aos dados armazenados. Isso é possível quando a coerência e a segurança das requisições são garantidas. Outro aspecto do gerenciamento de dados é o controle da coerência dos dados, ou seja, os dados obtidos pelo controlador precisam estar em consistência com os dados reais dos componentes da rede.
- Serviços: O controlador deve ser capaz de otimizar a prestação de serviços, bem como promover a manutenção da rede, para manter os serviços em funcionamento. Outro importante serviço que deve ser fornecido pelo controlador é o cálculo de caminhos para os pacotes.

#### Referências

1. O. Salman, I. H. Elhajj, A. Kayssi e A. Chehab, "Controladores SDN: Um estudo comparativo", 2016 18th Mediterranean Electrotechnical Conference (MELECON), Lemesos, Chipre, 2016, pp. 1-6, doi: 10.1109/MELCON.2016.7495430.
