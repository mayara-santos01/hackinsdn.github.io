# Intelligent Containment and Filtering

![Containment and filtering logo](/assets/img/containment-filtering-logo.png){:.centered}

The Intelligent Containment and Filtering module aims to provide means for mitigating attacks identified by other modules or in response to a direct API request from the Network Orchestrator. In this context, containment and filtering can be discussed as two techniques of attack mitigation. 

## Containment

Containment techniques are generally related to the use of IPS tools, and are based in the manipulation of attacker sourced traffic. Some of them are:

- Closure of the ongoing connection, through the sending of TCP RST packets;
- Application of firewall rules to block all traffic coming from a user previously identified as an attacker;
- Bandwidth and requisition limitations, i.e., creating a limit in the amount of data transmitted between the attacker and the victim, as well as limiting the amount of connections ongoing between them;
- Traffic redirection towards a quarantine machine, thus, isolating the malicious traffic from the rest of the network;
- Traffic redirection towards a honeypot system, which consists in a system that emulates targets to receive attacks purposely, in order to study them.
- Remotion of malicious traffic excerpts.

## Filtering / Scrubbing Services

Scrubbing services are related to the sending of the traffic towards DNS or BGP server, in order to promote traffic filtering and, thus, the attack target will only receive legitimate traffic. One of the differences between this technique and traffic containment is the direct traffic manipulation that is taken in containment techniques, while in  scrubbing services the mitigation actions are taken by DNS or BGP servers.

In this context, we can conclude that traffic filtering is a technique which requires less configuration than the traffic containment technique.
