## List of meeting minutes with the supervisor

* [First Contact - 7/October/2021 ](#first-contact-with-supervisor)
* [Meeting 1 - 8/October/2021](#meeting-1)
* [Meeting 2 - 15/October/2021](#meeting-2)
* [Meeting 3 - 19/October/2021 - agreed on the thesis topic](#meeting-3)
* [Meeting 4 - 2/November/2021](#meeting-4)
* [Meeting 5 - 23/November/2021](#meeting-5)
* [Meeting 6 - 7/December/2021](#meeting-6)
* [Meeting 7 - 5/January/2022](#meeting-7)
* [Meeting 8 - 18/January/2022](#meeting-8)
* [Meeting 9 - 1/February/2022](#meeting-9)


<hr>
<br>

# Meeting 9
### *1/February/2022 - from 4:00 pm to 4:53 pm - via Skype* (duration approx. 52 minutes)
<br>

Agenda

- The draft document now includes Abstract, Introduction, Background and Method sections (link)
- New demo video of the experiment (link)
- Next meetings plan below

Plan

- Methodology (1/Feb)
- Results (15/Feb)
- Conclusion (1/Mar)

* Supervisor mentioned that he had reviewed both the video and the document and there will be comments on those.
* Methododoly is not yet clear.
* The project has different dimentions, or different modules, but not different scenarios as I was suggesting.
* Need to design the experiment.
* There are 4 attempts, so need a table to summarise all settings.
* Instead of scenario we should call it condition, lower light and high light.
* We have 4 different conditions, we could increase the data and have more conditions but there is no time. 
* For each model there is a hypotheses
* Definition of different models and conditions of the experiment.

| Type of Model  | Condition #1 - Low Light (L) | Condition #2 - Low Light Attacked (LA) | Condition #3 - High-Light (H) | Condition #4 - High-Light Attacked (HA) |
| :---: | :---: | :---: | :---: | :---: |
| Model Training Small Dataset (M-TS) - 20 laps | Hypotheses OK | Not good with collisions | Don't know results | Bad |
| :---: | :---: | :---: | :---: | :---: |
| Model Training Large Dataset (M-TL) - 40 laps | Hypotheses OK  | Collide | Bad but better | :---: |
| :---: | :---: | :---: | :---: | :---: |
| Model Training Large Dataset Defense Training(M-TSA) - 20 laps | Hypotheses OK  | Collide | OK | :---: |
| :---: | :---: | :---: | :---: | :---: |
| Model Training Large Dataset Defense Training (M-TLA) - 40 laps | Hypotheses OK  | Collide | OK | :---: |

* After presenting the experiment start with discussin results.
* Describe te main lessons, such as incresing the data doesn't help.
* Adversarial attacks helped a lot. 
* Helped a bit also in LA.
* But surprisingly is not perfect.
* This is not easy to explain, however, I have to come up with speculations of whyit didn't work.
* Perhaps, trainer adversarial attacks has to be done smarter, some ideas could incude using image augmentation techniques such as cropping, flipping and blur. 
* Need to fill all gaps in my research. There is the need to explain the 4x4 = 16 set up experiment.
* In method session must formulate speculation about the results.
* Whereas in the results session simply recall the results. Full stop. 
* Later, in the discussion sessino, I go back to the results, point out highlights such as the observation that more train no help as I thought.
* It is disappointing that adv training didn't help more when under attack, explain the limitations and possible solutions such as image augmentation, training in a smarter, more realistit fashion, but time run out. 
* The background section need more explanation, and much more detail. However, it is not as important as create a complete and more systematic method section. 
* The next 2 weeks must focus on method and results, but already write some ideas for discussion.
* Supervisor sent PDF with personal feedback.
* Need to improve.
* Explain fig 3 in text, I can't do that, I need to explain in more detail why this image is there and it is doing what. 
* Compare collisions of th four different modules of experiemtn 4 X 4. 
* The experiment has two independent parameters - The size of the dataset Small and Large.
* Adv attack in both yes or not. 
* It is a classic factorial design which two independent variables combine all possible test ommde in all settings.
* So, 16, need to describe the method.
* Results, start model 1, show resuls for 4 different conditions.
* Model 2, do the same.
* End summary table highlighting results.
* In discussion point the numbers of the results.
* Point out what did work.
* Mention what I would do if have more time.
* After these two parts are done, then talk and ask help maybe naveed or other expert about the adversarial attack, as supervisor mentioned not being a expert in the ML field. 
* It is good to have a sanity check with an expert and check to see if there is not a very obvious mistake in the end. 
* People are busy, might be hard to find time to do this, if I can't find then supervisor will try to find an expert that can help. 
* Supervisor can help with the experiment ideas, but cannot judge the quality of trh training, the tech is being trusted to the master student candidate. 
* I might get a softer or a super hardcore opponent.
* The full final document must be ready by the end of April.
* Supervisor mentioned it would be okay until the 3rd of May, after not okay.
* Need to present the final document for supervisor feedback before end of March so 29/03, also the okay from an expert with sanity check.
* Need to extend background and follow supervisor's feedback.
* Need to remake video with final experiment. 

## Results

| Type of Model  | Condition #1 - Low Light (L) | Condition #2 - Low Light Attacked (LA) | Condition #3 - High-Light (H) | Condition #4 - High-Light Attacked (HA) |
| - | - | - | - | - |
| Model Training Small Dataset (M-TS) - 20 laps | Hypotheses OK | Not good with collisions | Don't know results | Bad |
| **Collisions** | **0** | **12** | **5** | **7** |
| Model Training Large Dataset (M-TL) - 40 laps | Hypotheses OK  | Collide | Bad but better | :---: |
| **Collisions** | **0** | **10** | **4** | **9** |
| Model Training Large Dataset Defense Training(M-TSA) - 20 laps | Hypotheses OK  | Collide | OK | :---: |
| **Collisions** | **0** | **3** | **0** | **5** |
| Model Training Large Dataset Defense Training (M-TLA) - 40 laps | Hypotheses OK  | Collide | OK | :---: |
| **Collisions** | **0** | **3** | **0** | **5** |



<hr>
<br>



<hr>
<br>

# Meeting 8
### *18/January/2022 - from 4:00 pm to 5:41 pm - via Skype* (duration approx. 1 hour and 40 minutes)
<br>

* Agenda

- Document includes updated Abstract, Introduction, and Related Work sections (link)[https://github.com/mikecamara/adversarial-machine-learning-attacks/blob/main/PDF/Camara_Software_Engineering_2022.pdf]
- New demo video of the progress with the baseline experiment (link)[https://youtu.be/uxeazjQ9aNI]
- Experiment is not successful so far - after a staggering 18 hours of training, the model trained with adversarial images performed very poorly. I'm now trying to identify possible causes for the failure.

Plan

- Related Work section (18/Jan)
- Methodology and Implementation (1/Feb)
- Evaluation (15/Feb)
- Conclusion and Results (1/Mar)

* Supervisor background is fine. However, adding more info is appropriate. 
* Supervisor mentioned the importance of discussing the methodology.
* Need to define the two different light scenarios precisely, perhaps call it A and B.
* Explain how many pictures are used per round define the number of laps used. 
* Create a baseline using a standard approach.
* Be precise with training data set and define what exactly will be improved.
* Explain what data is being collected while driving.
* We need to expose the limitations of the technique earlier.
* Need to investigate the limitations of the FGSM, opportunities, and challenges, and justify the use in the background section.
* I explained how the experiment was currently failing. The supervisor found it suspicious and speculated about possible issue diagnosing techniques, possible causes, and solutions.
* Supervisor explained how a failed experiment might not be worthy of a master's degree.
* If failure becomes inevitable, then a plausible explanation must be created to address the question of why it didn't work. The failure must be described in detail.
* To seek advice from an expert could help find technical mistakes. 
* A reduction in the test set could make it easier to pinpoint possible mistakes. 

<hr>
<br>


# Meeting 7
### *5/January/2022 - from 4:00 pm to 4:57 pm - via Skype* (duration 57 minutes)
<br>

* Agenda

- First draft version of the document 
- Demo video of the progress 
- Next meetings plan below

Plan

- Abstract, Table of Contents, Introduction (5/Jan - Today)
- Background and Methodology (18/Jan)
- Implementation (1/Feb)
- Evaluation (15/Feb)
- Conclusion and Results (1/Mar)

* Supervisor mentioned that the structure of the doc is okay
* Goal had some comments to make later but no big deal, small
* The supervisor could not understand the video
* What was missing is to show some cases with traditional training but situations where the car did not perform so well
* create a comparison with the baseline
* Next stage change lights and have issues model fails
* what happens if cover stop sign by half
* ideally the special training will overcome the issue with the light difference
* could be light, a color in the wall
* I have to have clarity about of the control the car, the pre-trained components, an algorithm for object detection, steering, and throttle
* change something in the situation that the model stops being smart, list them, also mention a situation where it is not so nice
* Obstacles means they are moving, not static such as the ones I use; in my case is just an extension for the track, so keep it out of my thesis, not at this point
* forget about traffic lights and stop signs and limit the scope to the lanes
* check if coco mobile net was trained with adversarial attacks
* add IMU Background on how it works
* How car perform with path attacks, remove lane, add pepper to the lane, dimmer light
* training car in different lights becomes an endless economic questions
* I might be proposing a shortcut
* improve algorithm with adversarial attack
* simplify experiment
* direction of steering concerning the lights
* document all that very carefully
* document how many laps the model was trained
* steering vs. light
* good light vs. adv attack
* if it does not help, disappointment, discussion, speculate why not helping, this is okay too.
* people use adv attack, limitation literature, and save thesis project.
* IN the background, explain the functions I could have used but did not so to do not mix subjects.
* don not use IMU, so you can focus solely on the light


<hr>
<br>

# Meeting 6
### *7/December/2021 - from 4:00 pm to 4:57 pm - via Skype* (duration 57 minutes)
<br>

* We started the meeting, supervisor shared his screen and opened the agenda

* Agenda

- Data Extraction Table 
- Demo experiment for baseline creation (autonomous driving for 14 laps and 2 laps)
- Simplified access to thesis document links (link)
- Enrolment to Master's Thesis course in spring 2022 is it LTAT.00.002 or other?
- Confirm next meeting on the 5/Jan
- Confirm methodology below:

First Methodology I have suggested:
• Research questions.
• Data search.
• Study selection and quality assessment.
• Data extraction.
• Analysis and classification to find methods for the creation of a deep neural network (DNN) for driving the toy car
• Creation of a baseline for the DNN model. (I'm currently here)
• Define safety
• Implement adversarial attacks
• Implement defences methods.
• Evaluate and compare the results to validate the safety of the DNN model.

* Supervisor mentioned that he had a look at the extraction table and also at the videos.

* Supervisor started with the "easiest" topic to cover which was the enrolment to master thesis course during spring. The supervisor clarified that I don't need to take any actions, or enrol on any course, the enrolment is all done via supervisor and admin, I would be awarded the 30 ECTS after defending the thesis. 

* Supervisor addressed the Data Extraction Table topic, and was interesting to find out more about the results of my mapping study, and asked if the results summarized in a document, and I explained how the results of the mapping study were available at the Distributed System Seminar. 

* Supervisor opened the document, and then we discussed the answers for my RQs, supervisor explained that we should now focus on polishing the RQ for the thesis and work on a well-defined thesis goal, he then asked me to explain what was my research goal. 

* I answer defining the research goal in simple words: 

"I would like to first learn what's the best way to train a car to drive autonomously (RQ), with that done I could define a baseline and define safety, after that I would apply selected adversarial machine learning attacks that would compromise and deteriorate the car performance. After that, I would then implement selected defences. In the end, I would compare and evaluate the performance of the car in these three different scenarios. Trained but no attacks, with attacks, with attacks and defences."

* After understanding my purpose supervisor help me to create the appropriate methodology for such a study, thus the notes below reflect the brainstorm with the supervisor. 

* The goal is to demonstrate how adversarial machine learning can be used to improve the deep learning component in autonomous driving vehicles.

* I must research the field to pick methods of adversarial attacks to improve a standard normally trained baseline. 

* The study is a **Design Science Master Thesis**, which shows my capacity to implement and handle modern technological concepts in a toy car and report it as an engineering master thesis, therefore, deserve to receive the master diploma. However, this is not research. 

* The report will demonstrate how using specific adversarial techniques we can make the vehicle safer. 

* In the introduction find a way to make the title clear and understandable and define a method. 

* Define method:

* 0 step - Literature review - how to train a car, analyse overview of existing metrics to evaluate performance. And select an adversarial attack, pick one and check metrics. 

- Build baseline car
- Check baseline
- Improve car baseline
- Check to improve baseline

The Design Science is composed of for steps (design, check, improve, check)

Step 0 RQ1
To analyse and justify the methods selected as an answer to RQ1 and to 

Step 1 
results mapping study create the baseline, also how to evaluate

results describe how trained cars look like R1 and R2

Step 2 RQ3
Analyse list of attacks to evaluate pick 1 or 2 and user

Last step another check and hopefully the car will be better

While writing the thesis making a clickable link to a video would be nice

How to train this driving model

How to describe the toy car

what do I do to train model?

Describe if you would like to watch the results click on the link.

The project has to be crystal clear

Train baseline

add special train

watch differences and compare, very clearly describing everything.

All the metrics have to be very precise, the committee will be asking why I used this or that. 

Since the 14 laps video proved that there is little or almost nothing to improve in that model, then we should add some obstacles in the circuit so is more difficult and there is more data to compare in the baseline. Then use attacks and compare again.

The track is well designed and relatively simple, add signs, check suddenly hitting dings. I have to define what I will be using to check the performance. 

Hit wall less often.

The supervisor mentioned a study from Cambridge, or oxford in which they add a sticker to the stop sign and misclassified it, so the classification was easily fooled.

But it was not perceivable to humans. 

We could transfer this idea to a toy stop sign. Train the car to signs, and with attacks make it evade with little unperceivable manipulation. But detect with adversarial defence training. 

The study has to be easily replicable and works well-ish. 

The baseline manipulates slightly and doesn't detect the signs.

What would happen if add a mirror to a wall, or change the colour, manipulate a little bit and see if the baseline changes. 

Small change, confuses the model. After the defence training, it should perform normally. 

The disturbance is too small, but not for the car model. Find a sweet spot where I can fix it and the disturbance is not too big. Argue that humans wouldn't be confused with disturbance but the model is. 

Maybe if change the location of the disturbance in the circuit is not so difficult anymore. Find out the perfect setup.

This might be useful later in the competition. 

Make sure to scientifically show fair comparison and clearly define the situation and baseline. 

3 scenarios

1 - Baseline track without confusion

2 - Small disturbance baseline get confused

3 - Bigger disturbance get more confused

4) better training car not confused with small disturbance but still confused with bigger disturbance

Document all different elements and methods


Step zero is the theory over deep learning models, adversarial attacks and metrics to define safety.

Design science steps:

1 - Baseline
2 - Evaluate baseline training and evaluate baseline training disturbed
3 - New better training with adversarial attacks
4 - baseline disturbed will have a better car performance

* Next meeting is 5th January a 4 pm to 5 pm. 

* I should create an event and invite the supervisor. 

* Supervisor requested to if possible send the agenda email earlier than only a few hours the meeting.

<hr>
<br>

# Meeting 5
### *23/November/2021 - from 4:02 pm to 5:02 pm - via Skype* (duration 60 minutes)
<br>

* We started the meeting, supervisor shared his screen and opened the agenda

* Agenda

1) Sync in with the supervisor 
2) Data Extraction Table
3) Seminar report
4) Questions about choosing examiners and the norms for interaction with the thesis committee
5) Confirm the local rules for citation style
6) Plan next meetings (maybe 7/Dec and 4/Jan as the Christmas holiday begins on the 20th/Dec)

* Supervisor mentioned that he had reviewed the data extraction table available in the documents. However, there was nothing to give feedback on because the table was empty. 

* Supervisor mentioned how he had trouble finding the links and the files, so I should send them simply attached to every email I send so he doesn't waste time looking for them.

* Supervisor assisted in reviewing and reformulating the research questions displayed in the table. The research questions were not specific enough, there was a grammatical error, such as using capital letters unnecessarily. 

* I send the supervisor a link to the updated research questions file, but the inconsistency with the files was unacceptable and led to confusion. 

* Supervisor assisted me to finish drafting new reformulated research questions.

* We need to simplify the access to the files and keep them consistent.

* Supervisor explained how he was confused in regards to the consistency of the project, he mentioned that there was not enough clarity in regards to the goals of the project, the study itself.

* Supervisor clarified that the systematic mapping study of the seminar is only used to find the tools that answer that research questions, it is a part of the thesis. However, the master thesis should have its methodology which is crafted to answer the research questions. 

* We must define safety. What does safety mean in the context of scaled self-driving cars? 

* We must define a baseline that will provide the metrics for defining safety. 

* The supervisor mentioned how he had a look at the ART tool, but it seemed to be a tool to analyse the security of ML, not safety. 

* Security is different from safety, security could be related to the system authorization, access, identification, but safety is related to the loss of property, or lives, or endangers humans, so it is unsafe. 

* Supervisor explained how one could argue that faults in security could lead to unsafety. So we should look at ART and check which security features are relevant to safety. 

* Supervisor explained the local protocol to deliver and defend a thesis. The only person that I need to interact with until the day of the defence is my supervisor. The committee is already defined but no interaction with them is needed. 

* Supervisor explained how the methodology of the project should be created surrounding the object of safety analyses.

* What is safe and what is not safe.

* Reliability related to how often it happens

* Run the circuit for 1 minute and having ten hits is not safe, we need to define safety and not safe, only then we can measure.

* Define where it starts, the certain types of hit, side or front, for instance, then create a time distribution table.

* If hit obstacles, left or right, if in opposite direction does it changes hits patterns

* Create thesis baseline. It's not fully deterministic.

* Change speed of the car, compare differences. 

* Describe how the method consists of recording the behaviour and safety of the vehicle without safety training.

* What can we use to make it safer.

* Compare different performance and baseline. 

* The overall method there is nothing special and is quite naive.

* In the background section explains the background of the car, and define safety. 

* The methodology sections, which is long and important, describes the main 4 sections: 

1) Find a method with a scaled car that supports the creation of DNN models - Create the circuit and find methods that support training DNN models
2) Creation of baseline - how to capture and define safety and profile hits 
3) Explain how to apply the methods to improve car safety - find methods that disturb safety. Explain how to apply those methods. Explain how to improve the car model.
4) How to evaluate improvement, run the experiment again with safety profile and compare safety (results). 

* Overall the study is about safety and not security

* Supervisor clarified the local rules about citation. There is no one style that is required, most citation styles are accepted as long as there is consistency across the paper. 

* Supervisor already added the dates of 7/Dec and 4/Jan to his calendar at the same time. I must send the updated agenda by the previous day of the meeting.

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
