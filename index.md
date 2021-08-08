## Defensive Deception in Enterprise Network

Student: Mu Zhu (mzhu5@ncsu.edu)

Advisor: Munindar P. Singh (mpsingh@ncsu.edu)

Exam time: August 20th, 2021, 3:00pm - 5:00pm on Zoom

## Commitee:
- Munindar P. Singh (Chair)
- Khaled Abdel Harfoush (GSR)
- Rudra Dutta
- William Enck

<hr />

### Abstract

Defensive deception attracts much attention from research communities. Unlike traditional cybersecurity techniques, such as firewall and intrusion detection systems (IDS), defensive deception lets the defender participate in attack processes to lure and mislead the opponents' perspective. Therefore, defensive deception shows effectiveness when detecting or mitigating stealthy attacks, such as malicious reconnaissance and insider threats.

Although defensive deception is a promising approach, it has shortcomings and brings overhead. Some researchers leverage game theory and machine learning to assist the defender in improving deception techniques and optimizing the defenders' resources. 

To better understand how defensive deception works, we first investigate different deception techniques and analyze their (dis)advantages. We survey current game theory (GT) and machine learning (ML) based defensive deception research and discuss them by considering 1) what GT/ML is used, 2) what kind of attack is discussed, 3) what defensive deception technique is proposed, and 4) how the authors simulate or evaluate their schemes.

As a popular defensive deception technique, honeyfile systems are commonly used to detect stealth threats, such as insider attacks. Although deployed honeyfiles uncover attackers, they disturb legitimate users and generate false-positive alarms, which may confuse administrators. To fill this gap, we propose a novel honeyfile system, named Mee, that relies on decentralized deployment and centralized control. 
%we involve regular users to evaluate the impacts of honeyfiles on users. 
This research includes two incremental components. First, we propose Mee structure and model the interaction between the attacker, the defender, and the users with the Bayesian game to assist the defender in making the optimal strategy. 
Then, we expand this work with deep reinforcement learning (DRL) and adopt a more complicated environment (e.g., multiple users and attackers involved) to increase the realization.
Our research objective is to increase the effectiveness of honeyfile and reduce false positive alarms from regular users.

On the other side, we propose honey traffic, which represents generated fake network flow, against malicious reconnaissance (e.g., such as packets sniffer and banner grabbing). This research adopts Generative Adversarial Network (GAN) architecture, which includes generator and discriminator. We utilize the generator of GAN to learn the features of network flows that come from actual servers and produce fake flows. In addition, we use GAN's discriminator to mimic an attacker, which needs to distinguish the natural flows from fake flows. 

In this proposal, we discuss the basic concepts and thoughts about defensive deception. We improve the current deception system with reliable and practical designs. We adopt game theory and machine learning for assisting the defender in searching for the optimal solution.

<hr />
### Proposal:

[Version 1 (Aug 6 th, 2021)](./oral_proposal/first_version.pdf)

### Slide:

