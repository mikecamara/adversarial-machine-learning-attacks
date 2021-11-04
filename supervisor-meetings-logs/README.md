## List of meeting minutes with the supervisor

* [First Contact](#first-contact-with-supervisor)
* [Meeting 1](#meeting-1)
* [Meeting 2](#meeting-2)
* [Meeting 3](#meeting-3)
* [Meeting 4](#meeting-4)

<hr>
<br>

# Meeting 4
### *2/November/2021 - 4 pm - via Meet* (duration 30 minutes)
<br>

* Supervisor mentioned that he had reviewed the submitted documents.

* The initial feedback was positive. 

* Mentioned that there was a crucial document missing - the Data Extraction Table.

* Recommended looking into first seminar material the slides of data extraction

* Each research question should have a data extraction table that includes what items  I should look for to analyse the selected paper.

* For instance look for papers on how to test deep learning, network test techniques.

* If paper excluded say something why 

* Create one column for test methods, if they are the same as other papers.

* What are the different methods they have used

* Have column in data extraction table - table summary, which is one table for each paper trace back to what I found.

* Synthesis info, duplicate cells, update content. 

* If I don't find anything tells as well that the paper didn't mention any test methods.

* End table result for each RQ found papers

* This gives traceability to the outcome

* Check adversarial tests of deep learning papers

* Present summary

* appendix table 

* While reading paper might have to add columns to table, for instance, tools that they use to extract what I want to know

* Each RQ guides what info I'm looking to find

* Example counting phenomena - Technology A yes or no used out of 15 7 didn't use. Test technique used, etc.

* We agreed that for our next meeting I would request the data and time on-demand as I needed. 

* We agreed that if necessary we could meet every second week. However, I would remember the supervisor of our meetings one week in advance and one day before the meeting and quickly summary what we will be discussing. 

* A possible date would be on the 16/November/2021 at 4 pm. This means I would remind the professor on the 9th and 15th of November with a short email. 

* It seems like Skype is a good tool to communicate and we could use it for our meetings going forward. I also should mention this in the first email on the 9th.

* These emails serve as a weekly report to the supervisor, so I must format it nicely, encouraging easy access to the information. 


<hr>
<br>

# Meeting 3
### *19/October/2021 - 1 pm (duration 45 minutes) - via Skype*
<br>

* We started the meeting with the supervisor asking to see the results from the assigned task and he also mentioned some concerns to my work ethic and my motivation for studies. 

* The supervisor explained how I seemed to jump from one project to the other as soon as I encountered difficulties. 

* I explained, how this was not the case, and I had serious reasons to choose the new topic, including being a very close match to my skills and interests. 

* Then I also explained my participation in the ADL project, particularly in the DeltaX track. 

* We then discussed the paper [Attack and Fault Injection in Self-driving Agents on the Carla Simulator – Experience Report](https://doi.org/10.1007/978-3-030-83903-1_14) which was used as the [first reference to the available topic](https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl2) and contains the application of the IBM Adversarial Robustness Toolbox.

* The supervisor mentioned how we now need to answer two questions:

* 1) Which attacks from the IBM ART are relevant for our project?
* 2) Could we use the IBM ART approach to add robustness and improve the performance of the self-driving toy car?

* Some other considerations were if using the IBM ART would make the car have fewer collisions.

* We agree that I would create a repository and would document the process of understanding better the ART toolbox to improve the performance of the neural networks. 

* The supervisor requested me to create a 10 lines bullet point list to remember him what we discussed and what I will do next week as well as the report dates, the results of ART toolbox investigation, create a living document to keep track of what I did.

* Before meeting him, tell as well what worked and what didn't.

* We agreed to meet again via Skype on the 2nd of November at 4 pm.

**We agreed that by the 27th of October, I would share with the supervisor:**
```
- Report on DonkeyCar Delta track
- Link to a living document
- Bullet points list of what I did last week and what I'm planning to do next week
```
<hr>
<br>

# Meeting 2 
### *15/October/2021 - 5 pm (duration 30 minutes) - via Skype*
<br>
* The supervisor had sent a reference paper about Mutation Testing on the 12th of October, and some PIT mutation test tool references.

* I read the paper prior to the meeting, investigate the framework and got acquainted with mutation testing.

* During the meeting, the Supervisor highlighted how he had found and would then forward to me a paper (https://dl.acm.org/doi/10.1145/3412841.3442027) that had used four different programs as test-bed to implement and analyze mutation testing techniques, namely:

>- Ethereum Aleth https://github.com/ethereum/aleth#building-from-source
>- PyTorch Intrusive framework library https://github.com/pytorch/pytorch/blob/master/c10/util/intrusive_ptr.h
>- Microsoft SEAL encryption library  https://github.com/Microsoft/SEAL
>- Sed stream editor https://linux.die.net/man/1/sed

* The supervisor then assigned my first task which was to investigate the libraries, run the tests and get back to him with the findings and results. 

* I asked the supervisor what was the process for finding, selecting and reading papers.

* He mentioned how we should first read the Abstract and try to find the 5 elements that all abstracts should have:

>- Context
>- Problem
>- Motivation and Goals
>- Method Used
>- Summary with Main Results

Then if it is still interesting to you we should read the paper in the following order:

>- Introduction
>- Conclusion
>- Summary results

* He first recommended having a look at the MTAT.03.270 Seminar on Enterprise Software (https://courses.cs.ut.ee/2021/enterprise/spring/Main/HomePage) as the first reference, especially the introduction slides and the section on Mapping Studies in SE.

* The supervisor mentioned how is crucial to be able to answer what you want to know, search literature databases, search terms, define what papers to include and exclude, read other papers methods and tools used. 

* So I went ahead and after spending the weekend investigating the frameworks, I noticed that Aleth had been deprecated, and running the tests in the other programs wouldn't be a trivial task, it had been built on top of complex C++ code structure, and faced some compatibility issues with my Macbook M1 processor. 

* After spending several hours debugging without success and adding the fact that I wouldn't be able to perform my initial idea to implement mutation tests in the company that I work for I started to lose the motivation for the topic. 

* I decided to have another search for available topics and found another topic offered by the supervisor which was an incredible and surprisingly close match to my studies and skills. 

https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl2

* The topic Safety Analysis of Autonomous Vehicle Systems Software (in collaboration with the Autonomous Driving Lab) was a strong candidate to be a good match since I am currently working in the ADL, and after reading the reference paper Attack and Fault Injection in Self-driving Agents on the Carla Simulator https://doi.org/10.1007/978-3-030-83903-1_14 I became extremely interested in the topic.

* I've emailed the supervisor on the 18th of October and asked if the topic was still available. He replied that we could meet the next day to discuss my experience in the ADL and the possibility of working on the topic.
<hr>
<br>

# Meeting 1 
### *8/October/2021 - 3 pm (duration 15 minutes) - via Skype*
<br>
* In a brief meeting, the supervisor explained the nature of Mutation Testing research, which requires the student to have a solid code base with testing implemented, so we could apply Mutation Testing tools, such as PIT (for java), to measure the robustness of the testing structure. 

* I then explained to the supervisor how the company that I work for does not have a testing structure implemented, which would disqualify them for a test-bed for the research. 

* However, the supervisor explained that such a study could be performed in an open-source project and he would send me a topic proposal early in the following week. 

<hr>
<br>

# First contact with supervisor 
### *7/October/2021 - via email*
<br>

* When I was researching for available masters thesis topics in the University of Tartu Software Engineering Group I came across a Case Study in Software Testing or Software Analytics (focus on software quality)  https://sep.cs.ut.ee/Main/StudentProjects2021#Pfahl1 which was a "placeholder" Masters project topic, it caught my attention because I thought I could apply it in my current job.

* I've reached out to the topic supervisor and we agreed to meet to discuss the possibility the next day.
