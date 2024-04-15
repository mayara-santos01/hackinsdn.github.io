# AI-Powered Anomaly Detection

![Anomaly Detection Logo](/assets/img/anomaly-detection-logo.png){:.centered}

Artificial intelligence had a great development in the last few years due to factors that include the increasing amount of available data to study, improvements in algorithms and hardware. The progress of AI made it possible to compute tasks that were, so far, basically impossible to compute [Došilović et al, 2018]. In this sense, AI is already being used to promote cybersecurity and, for example, there are tools that use it to detect anomalies in traffic, working as an alternative to signature based detection.

From this perspective, it is valid to point out some advantages and challenges of AI use in anomaly detection.

## Advantages

- Possibility of unknown attacks detection, including zero day attacks (vulnerabilities not already known);
- Easier dealing with cryptographed traffic, applying techniques in packets headers to detect anomalies; 
- Signature based detection requires frequent updating in the databases that contain information about already known attacks, and with AI based anomaly detection, the use and updating of databases is not necessary.

## Challenges

- It is more difficult to apply scalability to the solutions, i.e., techniques that can be applied to track large amounts of traffic;
- Real time answers obtaining;
- Creation of databases to train Machine Learning algorithms.

## Anomaly detection tools

There are diverse tools to promote the traffic anomaly detection, and some of the ones that use AI techniques are:

- Hogzilla-IDS: Network anomaly detection tool that uses AI techniques (not specified);
- NeMo-DDoS: Software focused on DDoS attacks detection, works along with other software, such as Netflow and IPFIX to promote IP Flow reports. Uses Machine Learning to detect traffic patterns and, consequently, anomalies.
- Kentik: Software that detects DDoS attacks through the combination of data from BGP tables, IP Flows (Sflow, Netflow, IPFIX). Kentik makes use of Artificial Intelligence and Machine Learning techniques, however, there is no further explanation about applied techniques.


#### References:

1. F. K. Došilović, M. Brčić and N. Hlupić, "Explainable artificial intelligence: A survey," 2018 41st International Convention on Information and Communication Technology, Electronics and Microelectronics (MIPRO), Opatija, Croatia, 2018, pp. 0210-0215, doi: 10.23919/MIPRO.2018.8400040.

