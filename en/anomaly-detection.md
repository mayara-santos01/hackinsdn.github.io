# AI-Powered Anomaly Detection

![Anomaly Detection Logo](/assets/img/anomaly-detection-logo.png){:.centered}

Artificial intelligence has had a great development in the last few years due to factors that include the increasing amount of available data to study and improvements in algorithms and hardware. The progress of AI has made it possible to compute tasks that were, so far, much more difficult to compute [Došilović et al., 2018]. In this sense, AI is already being used to promote cybersecurity and, for example, some tools use it to detect anomalies in traffic, working as an alternative to signature based detection. One of the objectives of HackInSDN is to promote diversity in the defense systems, thus, AI anomaly detection will be used along with other techniques, such as the signature based ones.

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
- Scikit-Learn: is a well-known software library for machine learning. It supports both supervised and unsupervised learning and has many tools for fitting models to data, preparing data, selecting and evaluating models, and selecting models.


#### References:

1. F. K. Došilović, M. Brčić and N. Hlupić, "Explainable artificial intelligence: A survey," 2018 41st International Convention on Information and Communication Technology, Electronics and Microelectronics (MIPRO), Opatija, Croatia, 2018, pp. 0210-0215, doi: 10.23919/MIPRO.2018.8400040.

