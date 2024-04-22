# Programmable Network Orchestrator

![Kytos-ng logo](/assets/img/kytosng-logo.png){:.centered}

Software-defined Networking is a new paradigm for orchestrating networks in which the data plane is separated from the control plane. In this sense, the control plane is represented by the SDN controller, while the routers and switches are only dedicated to forward packets according to the strategy applied by the controller [SALMAN et al, 2020]. SDN opens new possibilities to make the network much more flexible and programmable, enabling innovation at scale.

The HackInSDN project uses Kytos-ng as its SDN controller. Kytos-ng is an SDN controller focused on stability, scalability, and extensibility, being the result of a collaborative work between the Universidade de São Paulo (UNESP), the Rede Acadêmica de São Paulo (rednesp) and the Florida International University (FIU). 

One of the main features of Kytos is the possibility of creating diverse Network Apps (Napps), which produce excellent operational flexibility. Moreover, Kytos has a lightweight core application, which requires few computational resources for execution.

Kytos-ng is being used in projects such as [AmLight](https://www.amlight.net/), [AtlanticWave-SDX](https://github.com/atlanticwave-sdx) and [Q-Factor](https://www.q-factor.io/).

Some of the main functions of a SDN controller:

- Management: The controller needs to have knowledge about the topology of the network, and also should be able to recognize new links, in order to guarantee the connection of all nodes. Beyond that, the controller needs to have statistics about the components of the network;
- Stability: The controller must be able to keep the circuit of the network running, in other words, being able to detect failures and keep supplying the network, in order to not completely interrupt the services. 
- Data: The controller needs to guarantee the persistence of user requests data, which means that, in case of abrupt failures, the system will be able to continue the processes due to the stored data. This is possible when the coherence and safety of requisitions are guaranteed. Another aspect of data management is the control of the coherence of data, i.e., the data obtained by the controller needs to be consistent with the real data from network components.
- Services: The controller must be able to optimize the providing of services, as well as promoting the maintenance of the network, in order to keep services running. Another important service that should be supplied by the controller is the computation of paths for the packets.

#### References

1. O. Salman, I. H. Elhajj, A. Kayssi and A. Chehab, "SDN controllers: A comparative study," 2016 18th Mediterranean Electrotechnical Conference (MELECON), Lemesos, Cyprus, 2016, pp. 1-6, doi: 10.1109/MELCON.2016.7495430.

