# References

Here I will document the work related to the literature review and previous works in the field.

[Included Publications](#included-publications)

[Candidate Publications](#included-publications)

[Excluded Articles](#excluded-articles)

<hr>
<br>

# Included Publications

 ## [Attack and Fault Injection in Self-driving Agents on the Carla Simulator – Experience Report](https://link.springer.com/content/pdf/10.1007%2F978-3-030-83903-1_14.pdf)

- This paper was the first reference to the topic
- The author uses the IBM Adversarial Tool Box to attack Machine Learning models 
- The ML models are used to steer and drive an autonomous car in a simulation environment
- The attacks lead the car to increase collisions. 
- report our experimental campaign on the injection of adversarial attacks and software faults in a self-driving agent running in a driving simulator
- show that adversarial attacks and faults injected in the trained agent can lead to erroneous decisions and severely jeopardize safety.
- Machine Learning (ML) is at the foundation of the most relevant autonomous driving
applications, with more and more usage in safety critical functionalities as for example
obstacle detection, lane detection, traffic sign recognition, and ultimately self-driving
- Adversarial attacks could be applied as well to the inputs of a driving task
- Adversarial attacks could be applied as well to the inputs of a driving task
- To the best of
our knowledge, no works experimented with end2end self-driving agents including both
faults and attacks perspectives. Consequently, this experience report provides a guide as
well as practical evidence of a method easy-to-implement that allows to rapidly deploy
tests for self-driving agents under various adversarial attacks and faulty conditions,
in an entirely simulated (and reproducible) environment. 
- More in details, the paper
explains how to configure, inject and ultimately collect evidences of the effects of attacks
and faults injected. We show how to manipulate a driving simulator to perform the
experiments and to execute the experimental campaign. Results give evidence of the
effects of attacks and faults injection, especially measured in terms of wrong decisions
of the trained agent that lead to collisions or traffic offences; we show that the trained
agent fails under multiple injection conditions. 
-In this work, we are relying only on evasion attacks, which have the likelihood to
be carried out on a self-driving agent while it is executing, thus compromising safety.
We consider both white-box and black-box attacks. White box attacks need internal
details of the target model: when these details are available, they certainly pose a bigger
threat. However, often the model layout can not be easily obtained. In these situations,
black box attacks prove to be much more flexible, requiring only the final output of the
decision process. A different approach can be to use an extraction attack to approximate
the unknown target model and base a white box attack on this model instead of the
original.
- We do not consider poisoning attacks because they operate during the training phase
of an agent: this type of attacks was not relevant to our objectives, because we are
interested in investigating a trained model that runs on a vehicle. 
- Extraction attacks are
instead discarded as we are interested in safe operations rather than secrecy theft, and
for the purpose of our work it is sufficient to consider the evasion attacks as explained
above.
- Evasion attacks modify the input to a model, typically a classifier, such that its
prediction is erroneous, while keeping the modification as small as possible. Evasion
attacks can be black-box or white-box: in the white-box case, the attacker has full
access to the architecture and parameters of the model, and exploits this information to
construct the adversarial image. In case of black-box attacks, the attacker does not have
knowledge on the internals of the model; the attacker usually needs many more tries
(and computational time or resources) to construct an effective adversarial image

![ART](../adversarial-robustness-toolbox/tools-art.png "ART")
[Source](https://www.youtube.com/watch?v=4oUGUC4hIhI)

- The four
attacks are chosen because they represent different approaches to the same problem, 

### Keywords: 
Self-driving, Machine Learning,Trained agent,Adversarial
attacks,Faults, Injection,Simulation

### Article references

An analysis of adversarial attacks and defenses on autonomous driving models
- Adversarial attacks could be applied as well to the inputs of a driving task


<hr>
<br>

# Candidate Publications

[DeepPicar: A Low-cost Deep Neural Network-based Autonomous Car](https://arxiv.org/pdf/1712.08644.pdf)
```
Add the main reason that justifies this paper to be here
```

[Explaining How a Deep Neural Network Trained with End-to-End Learning Steers a Car](https://arxiv.org/pdf/1704.07911.pdf)
```
Add the main reason that justifies this paper to be here
```

[Implementation of the above paper with the DonkeyCar](https://github.com/nikkkkhil/self-driving-car-implementaion-based-on-nvidia-paper-using-keras)
```
Add the main reason that justifies this paper to be here
```

[Training Neural Networks to Pilot Autonomous Scaled Vehicles](https://digitalcommons.bard.edu/cgi/viewcontent.cgi?article=1222&context=senproj_s2018)
```
Add the main reason that justifies this paper to be here
```

[Optimizing Deep-Neural-Network-Driven Autonomous Race Car Using Image Scaling](https://www.shs-conferences.org/articles/shsconf/pdf/2020/05/shsconf_etltc2020_04002.pdf)
```
Add the main reason that justifies this paper to be here
```

<hr>
<br>

# Research Processes Articles


* [What makes good research in software engineering?](https://link.springer.com/article/10.1007/s10009-002-0083-4)



<hr>
<br>

# Excluded Articles
[Self-driving scale car trained by Deep reinforcement Learning](https://arxiv.org/pdf/1909.03467.pdf)
```
Here add the reason for the removal
```