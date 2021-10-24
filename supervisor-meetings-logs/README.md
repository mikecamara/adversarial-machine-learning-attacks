## List of meetings minutes with the supervisor

* [First Contact](#first-contact-with-supervisor)
* [Meeting 1](#meeting-1)
* [Meeting 2](#meeting-2)
* [Meeting 3](#meeting-3)

<hr>
<br>

# Meeting 3
### *19/October/2021 - 1 pm (duration 45 minutes) - via Skype*
<br>

* We started the meeting with Dietmar asking to see the results from the assigned task and he also mentioned some concerns in relation to my work ethics and my motivation for studies. 

* Dietmar explained how I seemed to jump from one project to the other as soon as I encountered dificulties. 

* I explained, how this was not the case, and I had serious reasons to choose the new topic, including being a very close match to my skills and interests. 

* Then I also explained my participation in the ADL project, particularly in the DeltaX track. 

* We then discussed the paper [Attack and Fault Injection in Self-driving Agents on the Carla Simulator – Experience Report](https://doi.org/10.1007/978-3-030-83903-1_14) which was used as the [first refence to the available topic](https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl2) and contains the application of the IBM Adversarial Robustness Toolbox.

* Dietmar mentioned how we now need to answer two questions:

* 1) Which attacks from the IBM ART are relevant for our project?
* 2) Could we use the IBM ART approach to add robustness and improve the performance to the self-driving toy car?

* Some other considerations were if using the IBM ART would make the car have less colisions.

* We agree that I would create a repository and would document the process of understading better the ART toolbox to improve the performance of the neural networks. 

* Dietmar requested me to create a 10 lines bullet point list to remember him what we discussed and what I will do next week as well as the report dates, the results of ART toolbox investigation, create a living document to keep track of what I did.

* Before meeting him, tell as well what worked and what didn't.

* We agreed to meet again via Skype on the 2nd of November at 4 pm.

**We agreed that by the 27th of October, I would share with Dietmar:**
```
- Report on DonkeyCar Delta track
- Link to living document
- Bullet points list of what I did last week and what I'm planning to do next week
```
<hr>
<br>

# Meeting 2 
### *15/October/2021 - 5 pm (duration 30 minutes) - via Skype*
<br>
* Dietmar had send a reference paper about Mutation Testing on the 12th of October, and some PIT mutation test tool reference.

* I read the paper prior the meeting, investigate the framework and got aquainted with mutation testing.

* During the meeting, Dietmar highlighted how he had found and would then forward to me a paper (https://dl.acm.org/doi/10.1145/3412841.3442027) that had used four different programs as test-bed to implement and analize mutation testing techniques, namely:

>- Ethereum Aleth https://github.com/ethereum/aleth#building-from-source
>- PyTorch Intrusive framework library https://github.com/pytorch/pytorch/blob/master/c10/util/intrusive_ptr.h
>- Microsoft SEAL encryption library  https://github.com/Microsoft/SEAL
>- Sed stream editor https://linux.die.net/man/1/sed

* Dietmar then assigned my first task which was to investigate the libraries, run the tests and get back to him with the findings and results. 

* I asked Dietmar what was the process for finding, selecting and reading papers.

* He mention how we should first read the Abstract and try to find the 5 elements that all abstracts should have:

>- Context
>- Problem
>- Motivation and Goals
>- Method Used
>- Summary with Main Results

Then if it is still interesting to you we should read the paper in the following order:

>- Introduction
>- Conclusion
>- Summary results

* He first recommended me to have a look at the MTAT.03.270 Seminar on Enterprise Software (https://courses.cs.ut.ee/2021/enterprise/spring/Main/HomePage) as the first reference, especially the introduction slides and the section on Mapping Studies in SE.

* Dietar mentioned how is crucial to be able to answer what you want to know, search literature databases, search terms, define what papers to include and exclude, read other papers methods and tools used. 

* So I went ahead and after spending the weekend investigating the frameworks, I noticed that Aleth had been deprecated, and running the tests in the other programs wouldn't be a trivial task, it had been built on top of complex C++ code strucure, and faced some compatibility issues with my Macbook M1 processor. 

* After spending several hours debugging without success and adding the fact that I wouldn't be able to perform my initial idea to implement mutation tests in the company that I work for I started to lose the motivation for the topic. 

* I decided to have another search for available topics and found another topic offered by Dietmar which was an incredible and surprisingly close match to my studies and skills. 

https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl2

* The topic Safety Analysis of Autonomous Vehicle Systems Software (in collaboration with the Autonomous Driving Lab) was a strong candidate to be a good match since I am currently working in the ADL, and after readind the reference paper Attack and Fault Injection in Self-driving Agents on the Carla Simulator https://doi.org/10.1007/978-3-030-83903-1_14 I became extremely interested in the topic.

* I've emailed Dietmar on the 18th of October and asked if the topic was still available. He replied that we could meet in the next day to discuss my experience in the ADL and the possibility of working on the topic.
<hr>
<br>

# Meeting 1 
### *8/October/2021 - 3 pm (duration 15 minutes) - via Skype*
<br>
* In a brief meeting, Dietmar explained the nature of Mutation Testing research, wich requires the student to have a solid code base with testing implemented, so we could apply Mutation Testing tools, such as PIT (for java), to measure the robustness of the testing structure. 

* I then explained to Dietmar how the company that I work for does not had a testing structure implemented, which would disquilify them for a test-bed for the research. 

* However, Dietmar explained that such study could be performed in a open-source project and he would send me a topic proposal early in the following week. 

<hr>
<br>

# First contact with supervisor 
### *7/October/2021 - via email*
<br>

* When I was researching for available masters thesis topics in the University of Tartu Software Engineering Group it came across a Case Study in Software Testing or Software Analytics (focus on software quality)  https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl1 which was a "placeholder" Masters project topic, it caught my attention because I thought I could apply it in my current job.

* I've reached out to the topic supervisor Dietmar Pfahl and we agreed to meet to discuss the possibility in the next day.
