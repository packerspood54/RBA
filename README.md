#  RBA: TOWARDS ROBUST AND STEALTHY BACKDOOR ATTACK IN FEDERATED LEARNING

##  Abstract

Federated learning (FL) enables collaborative model training with out sharing local data. However, its distributed nature makes it sus ceptible to backdoor attacks, where malicious clients implant trig gers to manipulate model predictions. While prior studies have ex plored various backdoor designs, they often overlook trigger robust ness under realistic conditions such as distribution shifts and com mon image corruptions. In these scenarios, triggers can become dis torted, and prior studies have demonstrated that backdoor activation often relies partially on co-adapted non-trigger features, which are vulnerable to disruption, potentially leading to a drop in attack suc cess rates. To address these issues, we propose the Robust Backdoor Attack (RBA), which integrates (i) a robust adaptive trigger gener ator to produce corruption-resilient, instance-specific triggers, (ii) a stealthy logits calibration mechanism to suppress abnormal acti vations, and (iii) a trigger dependency eliminator to minimize re liance on non-trigger features. Experimental evaluations on bench mark datasets indicate that RBA generally outperforms or matches state-of-the-art attacks under various corruptions, while maintaining stealthiness against FL defenses.

## Release Plan (ToDo)

- [ ] Pretrained models
- [ ] Full training & evaluation code
- [ ] Reproduction scripts and configs
- [ ] Documentation for datasets and corruption benchmarks
