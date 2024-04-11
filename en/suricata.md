# Suricata 

![Suricata logo](/assets/img/suricata-logo.png){:.centered}

**What is Suricata?** 

- Suricata is a high performance Network IDS, IPS and Network Security Monitoring engine. It is open source and owned by a community-run non-profit foundation, the Open Information Security Foundation (OISF). Suricata is developed by the OISF.
- In this sense, as an IDS, Suricata can be used to analyse live data traffic, from an interface of the chosen device, or to analyse packets that contain traffic, such as *.pcap* files.
- Suricata contains a wide set of rules, which is often updated, and the users can also create their own rules, amplifying the possibilities of detecting attacks.
- From the rules, alerts are generated, and thus the possibilities of attacks can be further analyzed by other programs, in the case that Suricata is being only used as an IPS.

**Use of Suricata in HackInSDN project:**

- HackInSDN aims to create a network security solution, which will be able to be used by educational institutions to train students that will be capable of working with network security. It can also be used by enterprises to promote safety in their networks.
- In this sense, Suricata will be used as an IDS to analyse live data traffic from specific interfaces. Thus, Suricata will be essential to detect the attacks that are coming into the analysed network, and the possibility of integraion with the SDN controller and other modules will be used to promote the prevention of attacks. In other words, Suricata will detect attacks that will by analysed and mitigated by other modules. 
