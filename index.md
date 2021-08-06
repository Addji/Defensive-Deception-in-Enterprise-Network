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

Defensive deception attracts much attention from research communities. Unlike traditional cybersecurity techniques, such as firewall and intrusion detection systems (IDS), defensive deception lets the defender participate in attack processes to lure and mislead the adversaries. Therefore, defensive deception shows effectiveness when detecting or mitigating stealthy attacks, such as malicious reconnaissance and insider threats.

Although defensive deception is a promising approach, it has shortcomings and brings overhead. Thus, some researchers leverage game theory and machine learning to assist the defender in optimizing the defenders' resources and improving deception techniques. 

To better understand how defensive deception works, we first investigate different defensive deception techniques and analyze their (dis)advantages. We survey current game theory (GT) and machine learning (ML) based defensive deception research and discuss them by considering 1) what GT/ML is used, 2) what kind of attack is discussed, 3) what defensive deception technique is proposed, and 4) how the authors simulate or evaluate their schemes.

As a popular defensive deception approach, honeyfile systems are commonly used to detect stealth threats, such as insider attacks. Although deployed honeyfiles uncover attackers, they disturb legitimate users and generate false-positive alarms, which may confuse administrators. Unlike some current research, which focuses on analyzing the interaction between attacker and defender, we involve regular users to evaluate the impacts of honeyfiles on users. Our research objective is to increase the effectiveness of honeyfile and reduce false positive alarms from regular users.
We propose a novel honeyfile system that relies on decentralize deployment and centralize control.
To assist the defender in making the optimal strategy, we model the interaction between the attacker, the defender, and the users with the Bayesian game. We expand this work with deep reinforcement learning (DRL) and propose a more complicated environment (e.g., multiple users and attackers involved).

In this proposal, we discuss the basic concepts and thoughts about defensive deception. We improve the current deception system with reliable and practical designs. We adopt game theory and deep reinforcement learning for assisting the defender in searching for the optimal decision.

<hr />
### Proposal:

[Version 1](./oral_proposal/first_version.pdf)

### Slide:

