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
* [Meeting 10 - 15/February/2022](#meeting-10)
* [Meeting 11 - 1/March/2022](#meeting-11)
* [Meeting 12 - 15/March/2022](#meeting-12) 
* [Meeting 13 - 5/April/2022](#meeting-13) 
* [Meeting 14 - 19/April/2022](#meeting-14) 
* [Meeting 15 - 10/May/2022](#meeting-15) 
* [Meeting 16 - 24/May/2022](#meeting-16) 


<hr>
<br>

# Meeting 16
### *24/May/2022 - from 4:02 pm to 17:08 pm - via Skype* (duration approx. 1 hour 07 minutes)
<br>

Agenda

- Defense presentation rehearsal feedback

- Review the plan below


Plan

- Meeting to review presentation slides (24/ May - Tuesday)

- Thesis defense (Someday from 31/May to 7/June)

- Master's degree graduation ceremony 2022 (21/June - Tuesday at 2 p.m.)


<hr>

Meeting

- Currently taking 19 minutes to present, which is unacceptable, should do in 15 minutes. Sixteen minutes is okay-ish. Over 16, it is an offense.
- Goal should come before RQ.
- Brief stop.
- Start explaining the method.
- Should use the term imitation learning instead of behavioral cloning because it is more well-known and intuitive overall.
- Explain how I apply imitation learning in the real world.
- Up to this moment, I had already taken 7 min, a bit too much.
- The method should be reduced. Mention how we train the CNN model for the control group using a standard setup
- Even though it is okay is not explicitly displayed on the slides, I must know the number of images in the dataset by heart and have a backup slide with the figures
- Now, move the entire large dataset and explain that it is the same setup. This will save me some time.
- It has been just duplicated. Everything is the same but with more data.
- In the slide about the conditions, first, isolate L and H conditions, and explain how all the four models will be tested in this main experiment.
- Then, on top of that, we add LC and HC conditions to check how robust the model is when dealing with a corrupted vision.
- This is an add-on for the project
- Throw the hope and expectation emojis
- For these other two?
- Max two sentences
- The final evaluation slide explains shortly that it runs for two laps, and collisions are used to check the quality of the models. 
- Results section needs reorganization
- First, start with results in all L
- Then only show the results of standard methods in H to raise the suspense
- Then, to keep the storyline now, let's see how these new methods work with corruption
- Show 2 5 - 3 5 section together
- It was not perfect but better than 5 and 4 in H
- Then jump to standard results
- In the results is expected that adversarial models would have a better performance than standard
- In adversarial methods is expected HC to have more collisions
- What is intriguing is that in standard conditions, LC has more collisions than HC, only this we did not understand well.
- One can speculate 
- Having more data only helps to slight in 5-4 H
- 0 - 0 quite excellent and convincing that the adversarial method is valid.
- Then, I should put all the future work together in one slide, and this slide will be either shorter or longer depending on how much time is remaining.
- This is the moment that I have to check the watch.
- I should make sure I try on the mirror or standing in the room.
- Control the time.
- The company's slides have to be removed to the backup section. It's taking time and is irrelevant to the thesis.
- I tend to talk too much. I should avoid that and make sure I plan what to say and say exactly that.
- During Q & A, make sure I understand precisely the question and give a short exact answer for that, do not deviate and start to talk about myself and my opinion. 
- So listen carefully and answer the question.
- Questions can be immersive, going back and forth with the audience

<hr>
<br>


# Meeting 15
### *10/May/2022 - from 4:30 pm to 18:04 pm - via Skype* (duration approx. 1 hour 34 minutes)
<br>

Agenda

- Thesis changes 

- Defense presentation 

- Review the plan below


Plan

- Review feedback on the latest changes on the thesis document and presentation slides (10/May - Today)

- Deadline thesis submission (until 17/ May - Tuesday) - IMPORTANT to forward the email confirmation message to the supervisor immediately after the thesis submission.

- Meeting to review final presentation slides (24/ May - Tuesday)

- Thesis defense (Someday from 31/May to 7/June)

- Master's degree graduation ceremony 2022 (21/June - Tuesday at 2 p.m.)


<hr>

Meeting

- Thesis PDF doc is fine for submission.
- Presentation needs improvement and clarity
- I should start the presentation by bringing the issue with the end-to-end driving (maybe a rapid intro difference between modular and end-to-end)
The problem is complicated and needs many data. One suggestion about tackling this issue is what I do in the thesis, which is to augment the dataset with synthetically generated data by manipulating the data. 
- Create a graph with the basic idea of manipulating the data.
- I should use the first 3 minutes to expose the main point of the thesis without rushing.
- This brings to the research question, which I should state but not read, rephrase, and focus on the main point, which is to improve the performance of the CNN in unseen lighting conditions.
- The main goal and exact scope are to improve the performance in unseen lighting conditions.
- Explain in detail how to do that. I have an experiment in which I compare standard approaches with a different training approach that I did not invent. The experiment was split and compared.
- Use the application to refer to the inference time.
- Machine learning inference is the process of running data points into a machine learning model to calculate an output such as a single numerical score. This process is also referred to as "operationalizing a machine learning model" or "putting a machine learning model into production."
- Explain how I started with the same data, and then we augment.
- Methods
- Slide 8 - The purpose of this slide is to expose the background and the elements I use to train my car.
- Explain how the car collects data.
- Only show the lower lights
- In the following slides about the different pieces of training show the tradition but also add the corruption
- I should add an image with dots to graphically represent the corruption.
- Explain how I merge and join the bash datasets making them more prominent.
-  Not to mention high lights so far.
- Make here a good distinction between the purpose of the background to train the car, what the car is, the data, label, and the low light conditions.
- The new method uses low light data corrupted. Then double the dataset with corrupted data. It is crucial to explain how we do not mix high lights in the dataset.
In slide 8, compared with the new and the old model, add some spots on the image to illustrate the idea of corrupted data. 
- In Slide 9 - Not only low light but also low light with corruption
- Data is augmented
- I must explain that T= Training consists of Small, Large, and Augmented.
- M goes for model and train with augmented corrupted data. 
On slide 10, I must explain the concept of higher lights and what the abbreviations HC and LC mean. So I should start from the bottom corner and go to the high lights.
- Explain how in principle, is expected in L; it should work fine for the four models because it was trained with that condition. 
- For the highlight is a question mark ??? We just don't know.
- Would this work? We do not know.
- Explain the corruption and the high light with corruption, and LC - We have no idea what will happen in those cases.
- Then, I move to the light levels, and I explain how it is not uniform levels.
- Explain how later, when we analyze the performance, if not ideal, then inspect if the crashes are random or if there are patterns of failure. 
- In the lux table, I should bring emphasis the significant differences.
- Training condition standard VS training condition corrupted
- On slide ten is crucial to mention the number of corrupted images. In that case, all images could be corrupted.
- In the next slide, 11 - explain how this is the overview of the complete evaluation conditions where the car runs for two laps. We discussed lights and vision in the previous slides, so here I add the laps to the context.
- Add the as a yardstick. I use the collision number.
- Mention how the corrupted pixels are changed.
- Make all the titles the same big size and make them stand out on the slide
- In the results section
- Start how lower light all performed well, which is what we expected.
- Then, jump to highlight - the major success of the new model training, which is not the case when using the standard methods.
- Mention how adding more data to the standard approach only improve insignificantly.
- The new approach works fine.
- Move to the HC worst. It is expected not to work perfectly but is still better than the conventional approach.
- Then move to LC, which is strange.
- It is surprising how it works worse than HC.
- DNN is black boxes, and I can only speculate about why LC is worse than HC.
We could speculate that the evaluation corrupts the HC. It resembles the L training conditions more.
- So the LC would be more different from the training data than H or HC
- Key concept is that during the method used during corruption in the evaluation time, the corruption is freshly created on the flight. What the model is seeing could be different from the corruption.
- So, possibly the LC is more different from L than HC is.
- I admit I did not have enough time, in the end, to investigate deeply why corrupt LC image is more complex than higher lights.
- Higher lights are a type of corruption.
- A pure speculation could be that the High light has a systematically smaller corruption than the one corruption artificially generated in LC and HC.
- The corruption gets stronger when adding the Hight light.
- It is easier for the models to navigate H than LC or HC.
- A hypothesis is that the systematic corruption on the fly is different from the corruption on the dataset.
- I did not have time to check but to check, I could measure the pixels in the data and find the differences in measurements for LC in Training and H data evaluation.
- It is essential to mention that the corruption is much higher in LC and HC than in H condition, which again is some sort of natural corruption. 
- The difference between LC and HC may have happened that the systematically shift corruption effect in HC somehow the corruption becomes smaller or less effective, and that is why it is smaller. 
- So, the highlights reduce the effect of corruption.
- Summary of how to explain the results:
- Start L column
- Main goal H achieved, standard no good, proposed great.
- When corrupting data during evaluating intriguing results.
- HC more data made it even worse
- The same in adversarial models where more data decreases performance.
- The speculation is that more data makes the model overfit even more than the training data. 
- The crashes in adversarial models could be related to the corruption on the fly, showing pictures of the model different from the data. The data is not the same. 
- With standard methods, LC is the worse. It's hard to explain. I can only speculate about why LC is worse than HC if I compare pixels' differences in the image from training and application running time.
- The post hoc analysis shows intriguing results. 
- For slide 13, there is too much text. It needs improvement.
- I should briefly say that the CNN standard model only works well in low light
- This is not the same for the proposed method, which also performs well in L but for the High is succeeded, the standard fails in H. 
- Creating corruption on the fly it is better but still not perfect
- 1) The main goal was to improve in unseen conditions. The proposed method worked fine. The standard did not.
- 2) Increasing the volume of data was not enough to perform well in H; increasing the amount of data did not substantially improve the performance.
- 3) For the evaluation with the corruption on the fly, all data given to the model is corrupted, while during training, only half of the data was corrupted. The new models, although still not perfect, they worked better.
- 4) I did not analyze how the corruption data was so bad for standard. One needs to have a better understanding. The post hoc analysis should look into differences between training and evaluation data to comprehend the strange behavior in a deeper analysis.



<hr>
<br>


# Meeting 14
### *19/April/2022 - from 4:20 pm to 5:03 pm - via Skype* (duration approx. 43 minutes)
<br>

Agenda

- Review the plan below


Plan

- Review feedback on the latest changes on the thesis document, repository, video, and presentation slides (19/Apr - Today)
- Deadline thesis submission - (17/ May - Tuesday)
- Thesis defense (Someday from 31/May to 7/June)
- Master's degree graduation ceremony 2022 (21/June - Tuesday at 2 p.m.)

<hr>

Meeting

- Table 1 - The caption - most tables in journals have the caption on top, and figures have the caption on the bottom.
- Usually, people add short captions. My captions are too big, and I should incorporate the information in paragraphs and write something like "Table shows independent variables and results." 
- Long tables are more common in books. 
- Also, the table caption font should be smaller and appropriately indented. 
- The formalities of the document and content look okay.
- It is unnecessary to add the presentation to the submitted material or repository.
- All the additional material can be on the repo, but I have to be very specific in the thesis document about what is available in the repository, for instance, "There is this, and this, and these additional materials in the repo."
- Always only refer to my supervisor using Name Last Surname format. 
- Because of the nature of my project, I should not add any attached document, a zip file, or folder with my submission. However, I should be particular and precise in the document, in-text, but mainly in the appendix, and visible in the table of contents that there is a video available and all additional material. I should make it a short headline mentioning that all code and additional material is in the GitHub link.
- It should be in the following format:
- (A1) GitHub repository
- (A2) Video
- I should have a license in the table of contents
- I should look for references from a recently submitted thesis. 
- So A1 and A2 are better and also have the license
- Have to make it easy for people to access. 
- Remove Lisad part, as it is unnecessary.
- So my appendix will be 1) Terms, 2) Repo list what is the link, 3) Video, 4) License (look at examples of other students), and check if I need to add the license in Estonian too.
- In-text, also remember to add ref to GitHub in text. 
- At the exact moment that I submit, I might receive an email notification. I should forward this email to my supervisor with whatever documents I have submitted attached, in my case, the link to the thesis. 
- There is a delay in the system, and this confirmation from my side will trigger the supervisor to find an opponent and communicate with the administration.
- After that, besides preparing for my presentation, all I have to do is wait for the opponent's review, which usually is ready only a few days before the defense. 
- Date and time also are only available a few days before the defense.
- After the presentation, there is a Q&A session with unlimited time. However, after the open floor, the supervisor statement, I will have about a minute to say a few positive words in which I should politely acknowledge the people involved in my work and the institutions. Then they move to the next candidate if there is any. 
The day's grades will be delivered after the meeting is closed. 
- In my presentation, I should explain why machine learning achieves my goal, which translates into a research question. 
- Maybe spend about one minute introducing the topic
- I should really focus on the Method, describe the experimental setup, the artifacts I used, etc
- The supervisor agreed to extend his support with my presentation.
- The next version of the presentation should be complete, so we can discuss it and make adjustments.
- The thesis is looking good. I could make the few necessary adjustments and submit it. However, there is also the opportunity to fix the mistakes, make a bullet list of the changes, and send feedback to the supervisor. 
- The following meetings are on 10/May and 24/May at 4 pm.


<hr>
<br>

# Meeting 13
### *5/April/2022 - from 4:00 pm to 4:27 pm - via Skype* (duration approx. 27 minutes)
<br>

Agenda

- Feedback on the thesis document's latest updates
- Review the next meetings plan below

Plan
- Deliver completed thesis document ready for supervisor's final feedback (5/Apr - Today)
- Review feedback on the document. Review presentation slides, video, repository (19/Apr - Tuesday)
- Doc ready for final submission. Focus on the slides and presentation - (3/ May - Tuesday)
- Deadline thesis submission - (17/ May - Tuesday)
- Thesis defense (Anytime from 31/May to 3/June or 6 and 7/June )
- Master's degree graduation ceremony 2022 (21/June - Tuesday at 2 p.m.)

<hr>

Meeting
- I had sent the document ready a few hours before the meeting, and the supervisor needed more time to analyze the document.
- The proposed schedule seems okay.
- Need to polish and submit it, but overall is okay.
- We don't know the opponent yet, and there are several possible options.
IMPORTANT - When I submit the document ready to the University of Tartu, I must submit an email to the supervisor saying that I have submitted the final paper to the University of Tartu and send all the files attached in the submission. 
- Sending an email warning to the supervisor will trigger him to write his opinion and send it to the people in charge of this. Then the opponent is also informed, and hopefully, we have the supervisor on the committee, but it's not guaranteed. 
- Overall, I must keep the supervisor in the loop. 
- The exact date for defense I will know is around 28.
- However, even with an exact date scheduled, there are chances of changing due to date change, opponent issues, or personal issues. 
- Opponents will send questions in their report before the presentation day.
- Next meeting is on the 19/of April.
- Supervisor will return his feedback this coming Sunday.
- This is not a problem to submit documents earlier than the deadline.
Remind that when the supervisor receives my email with all the submitted documents, the supervisor will forward them to the opponent.
- About the presentation, it should be delivered ideally in 14 min and 55 seconds.
- It's no good to go over time, but it is also no good to not use the time fully.
- I must read the opponent report carefully.
- The presentation consists of 5 steps. 
- First, briefly introduce the topic and motivate content explaining the problem (1 - 2 min)
- Then Goal I wanted to achieve, explain the RQ, and I should have one slide dedicated to the RQ solely. (2 - 3 min)
- Next, the method I should show the setup experiment, the toy car (3 - 4 min).
- Results, this is the main part (3 - 4 min)
- End summarise and wrap up words, say what interesting could be done if I had more time, END. (1 min)
- I should set the scene. Many candidates have the misconception that the committee or opponent read their thesis, but they did not. I should assume that no one read it, but I should know the document in detail. The opponent might quickly browse the thesis prior to the defense, and I should remember what I wrote in my thesis. 
- If I cannot remember three times, it is a bad sign.
- I should focus on the audience. They should quickly know why I did all that. This is no good when 5 minutes into your presentation and the committee still doesn't know what that is about. 
- So, set the scene, method, results. 
- Showing video or simulation is risky and utterly unnecessary for the nature of my project, but photos are okay and recommended. 
- Show a picture, explain how the car looks, how often it crashes, and what a crash means, like when the vehicle drives into a wall, then it is clear.
- I will only know the defense date 2 or 3 days before the actual date. 

Update (7 April):

- Supervisor sent his feedback on the document, and his notes are marked in yellow marked text -> attached comments).
- Overall, we did a great job. But I have 50 comments that I must address.
- I need to add the abstract in Estonian.
- I need to add the CERCS code.

<hr>
<br>

# Meeting 12
### *15/March/2022 - from 4:03 pm to 4:32 pm - via Skype* (duration approx. 28 minutes)
<br>

Agenda

- Feedback on the thesis document latest updates 
- Review next meetings plan below

Plan

- Deliver thesis document ready for supervisor's final feedback (5/Apr - Tuesday)
- Final wrap up meeting before document submission (15/Apr - Friday)
- Final thesis submission - (17/ May - Tuesday)
- Thesis defense (From 31/May to 3/Jun)

<hr>

Meeting

- It would have been better if I had specified better which parts were complete and which parts were not, instead only mentioning that 80% of the suggestions had been implemented.
- The supervisor reviewed the document and sent me before the meeting.
- Then, we went ahead with the supervisor's notes.
- The title should be changed to Using Adversarial Defence Methods to Improve the Performance of DNN-Controlled Automatic Driving Systems (ADS).
- Controlled Automatic Driving System is a common term currently used in the industry.
- Watch out to keep consistency with the spelling of the term "defense" either use the British spelling or American, but keep consistency.
- Use ADS after introducing it
- In the abstract, I use CNN, but I should use DNN, and then the type of DNN ADS is CNN, and then use CNN from then on.
- 2. The self Driving platform is fully fine
- Method table 1 fine
- Need to fix the distance after table and paragraphs, which seems to be an overleaf bug. It isn't very pleasant.
- Train - CNN (better CNN Model Training)
- 3.3 Design an Implementation evaluation
- 3.2 CNN Model table
- 3.3.5 Baseline metric, not metricS, also it is a big sentence at the moment. Break it down. 
- Baseline point in evaluation section
Value of metric is a metric system, maybe use measure is fine, metric lookup mathematical definition.
- Measure needs integral measurement
- Metric is more precise than measure, like the euclidean metric, etc. However, outside the field of mathematics, it is not so relevant.
- 4.2 THE is not capitalized ... CNN Model
- 4.3 Reporting the performance of the CNN Models
- MTS performance in the results section
- 4.4 "to" preposition in article's title is not capitalized
- Next meeting, I should anticipate in the email what are the changes I've made in the document.
- Meeting again on the 5th of April - three weeks away from now. 
- Then keep the biweekly meetings on the 19/of April and 3/May (last meeting)
- The GitHub repo must have the code related to the thesis
- The thesis document content-wise is ready.
- When I submit the material, it's enough to say that the code can be found at the repo, and then there is a video.
- I must be clear about where the code is.
- In the appendix of the thesis add a sentence saying Here is the readme file, including the linked video 


<hr>
<br>

# Meeting 11
### *1/March/2022 - from 4:00 pm to 6:06 pm - via Skype* (duration approx. 126 minutes)
<br>

Agenda

- Feedback on the thesis document latest updates (link)
- New demo video of the experiment (link)
- Review next meetings plan below

Plan

- Review title, abstract, bibliography, and appendix (15/Mar - Tuesday)
- Deliver thesis document ready for supervisor's final feedback (1/Apr - Friday)
- Preliminary thesis defense (12/Apr - Tuesday)
- Opponent submits my thesis review to the board committee and to me (10/May - Tuesday)
- Final thesis submission - (17/ May - Tuesday)
- Thesis defense (From 31/May to 3/Jun)

<hr>

Meeting

- The thesis need revamp write up
- Video is OK
- There is a need to make the thesis like the video
- Including Intro and Background
- There is nothing right with the bibliography, there is an issue with the reference style in overleaf that needs to be fixed.
- I should look into examples of good referencing style.
- Like classic journal
- Author, year, the name journal or conference number, year, page issue, typical avenue, journal, book
- It is described somewhere in the University of Tartu guidelines
- Same goes for blogs that need UTL, name, if there is no name you add one base on the person blog or topic, last access that when you looked at it. 
- Supervisor mention one particular reference paper I should  look into
- I need to properly add reference
- I talk about self driving models, but what is model, is it a CNN model?
- How does NVIDIA call it? Is it linear, it needs some definition of what is model in self-driving vehicles
- In the expert demonstration explanation, is nice the picture, but needs standards in how I'm naming it a) clean dataset, b) train c)...
- Autonomous first CNN
- Digg deeper difference CNN architecture linear very common related. 
- Then explain how it needs to be trained, difference standard training and improve how adversarial attack method can be used for training
- The subsection would be: - training standard cnn, expose weaknesses of this approach, how it could be improved - Next propose different training method
- Platform Donkey nice intro
- Self-driving NN on Vehicle
- Training NN for self driving vehicle
- General approach
- 2.3 need to change for training
- 2.4 scale car platform
- self driving platform
- 2.4 platform CNN real car using model describe
- Method
- Crashes are evaluation
- First explanation methods
- First train the SD NN Model
- Check how different are the models
- Different data collection and different training
- how behave in different condition
- PROBLEM WORD **TESTING** I'm not using it properly
- Testing is different, before testing overall steps design methods
- I should have two high level blocks 1) Developing the  model, 2) Evaluate the models
- In developing the model we have collect data and training, but aalso different data collections and different training methods.
- In evaluation block explain the models, explore with the different settings
- The goal is to answer the RQ
- Intro overview method
- RQ1 too similar to RQ2 - Remove RQ2
- Different models tested in varying settings
- Goal is to answer the RQ
- Say how I do develop data collection and organize in different combinations
- In the evaluation each model measure performance in different settings
- I should show how car standandard setting works in same conditions it was trained, but when change light conditions the HYPOTHESIS is will fail.
- Present some solutions
- 1) More data, expectation train model with standard approach, more training data hope it would become better
- Nevertheless, interested to see a method in case it not help.
- Check adversarial trainig method
- Principle low light should be fine
- Hope better with hight light condition
- See smaller set is better
- Need block about evaluation
- Go back to research questions
- What we do, how model can handle unseen 
- Evaluation focus on light condition
- Traditional training know now
- High light
- Amount data collected
- All the 8 cases described
- Also like to see on top of just changing light condition also add noise vision capability
- During evaluation
- Check low light
- Very briefly begining method why we need 4 different methods
- Need to explain the differences why have 4 models
- Decide the order to present what
- Start for answer RQ
- Evaluation model
- 1 influence - 2 lights + noise
- Evaluate in all kind of settings
- Low light should be fine
- Exposed low light
- Model development
- Model evaluation
- In order to build model CNN data collection and model training
- The type of data is input from camera in constant low light at 20 images per seconds.
- The laps and data set is redundant
- Need to review laps counts, put original size without cleaning so 40 laps
- Data collection and labelling, collect by remote control, the light is always low, say light variant
- Labels are automatically attached to images while driving the laps. It includes steering angle and throttle
- Table summarize data, it's called data colletion and labeling
- When I first time I mention light condition as LOW I have to describe what low means, different range of lamps.
- While training models there was two types of traininig, thus it depends on 2 factors: - data size and data augmentation
- For each training output name them, small low x and MT
- Explain how evaluation works
- How each of the four models is motivated by RQ
- TO answer RQ first compare behviour wth autgmentat and without
- And for each of them , the light change but we can on top corrput the vision
- Remove work testing and all is evaluation of 4 models
- Now I have to develop 4 models
- Evaluate them in the exact same settings
- Models are the independent variables
- 2 evaluations setting to see if work or not - hypothesis check.
- Low light corrupt expect could be handled
- Evaluation is when you RQ answer not in results
- Respond in model - Discussion - answerto research question
- Kind of interpretation - result performance of 4 models in 4 different conditions.
- Start with extreme cases
- Low light no corruption
- Expect everything is fine
- All 4 models should be all good
- Move to next extreme high light + corrupt vision
- Training is similar but not replicating the conditions
- You see model all have problems
- Testing Model MTS, MTA
- Results data
- Need better names fo L, L, H, need a bullet list what differences applied
- Give the 4 models characteristics TS, - Low 
- In data collection have 4 datasets
- Table training data
laps | augmentation -> yes or no

- table datasets and model
- Training laps | Augmentation | Images -> 4750 D-S, D-SA, D-LA
- Detail of dataset
- Training method then don't mention images, different settings 20 and 37, augmentation is double image size.
- I need to explain the actual right total of images, laps driven, number images
- If remove images then mention
- "Testint dar" is no good instead "Evaluation results"
- Evaluation MTS/MTS
- Discussion + subsection
- 4.1 data colletion, model training
- 4.2 Evaluation
- I need to figure out ROC how to measure performance model
- Performance evaluation of CNN - this is crucial I need to knwo how good model is, need to check precision, a quantitative measure to evaluate NN, ROC eavaluate
- Classification problem discretee
- Recall for regression problem
- It checks how often you have good steering compared to how often it had bad and it has tolerance
- NOT "Evaluation" it is ANSWER TO RQ
- Use table to answer question, go back an forth in the tabel, preliminar expectation all good.
- Did it help
- It seems to help when changing light condition
- Preliminar L case, before answer increasing size data not super hepful.
- L - H
- But how aout corrput doe help
- LC corrupt
- HC corrupt
- Adversarial training help more in light used for training
- 1 L - H
- LA bad
- Adv trainig H
- On topd of data in addddtion to addung data it setil lhave probelms this answer RQ1
- Answer to RQ
- Link to this table
- Look small case
- Low light for hight ligt not good
adv traning vision corrupt
- Standard worse
- Adv training hellsp not perfect but beter
- lets compare data help double
- No, it does not
- Then pphenomenca corrup vision
- Light change
- Discussion after the RQ ansereed
- Addition corrupt vision better but not perfect
- Results first dataset have been generated
- Training metod output
- Shich models
- Carachterization recall precision
- ROC independent variables
- baseileine
- input output relation
- Results four models
- Last sum up evaluation behavioiurs
- Anser RQ
- Discussion check references
- Video is a bit repetitive but is nice
- The thesis is sent to opponnent 3 days before defense
- Meeting again on 15 april

<hr>
<br>

# Meeting 10
### *15/February/2022 - from 4:00 pm to 5:00 pm - via Skype* (duration approx. 60 minutes)
<br>

Agenda

- Feedback on the the thesis document latest updates
- New demo video of the experiment
- Review next meetings plan below

Plan

- Review Results, Discussion and Conclusion sections and get feedback on the overall document (15/Feb - Tuesday)
- Review implementation of the previous supervisor's feedback (1/Mar - Tuesday)
- Review bibliography, references, title and abstract (15/Mar - Tuesday)
- Deliver thesis document ready for supervisor's final feedback (1/Apr - Friday)
- Thesis preliminary defense (17/Apr)
- Opponent submits my thesis review to the board committee and to me (14/May)
- Submit thesis - Final - (17/ May)
- Thesis defense (From 31/May to 3/Jun)

<hr>

Meeting minutes

* The supervisor mentioned that he noticed that I had progressed a lot, and overall, it was exciting and promising. 
* However, there was still confusion around the video, models, conditions, and thesis in general.
* There is confusion about identifying and defining the training and the test sections.
* By the videos, the supervisor noticed two different sets of data: one with 20 laps and another one with 37 laps, and the data includes images. 
* There was a second set of lights used in the experiment but not used for the training.
* There are four different settings, and the car runs for two laps.
* There is the need to clarify the independent and dependent variables of the experiment. 
* There is the need to clarify what the training consists of and distinguish from the previous stage, "data collection" or "expert demonstration."
* The training used the built-in CNN.
* In terms of "tests", there are the tests performed by the car in the circuit and the tests performed to plot the NN against the track performed by the expert.
* The NN consists of a supervised classifier that classifies ten images per second, thus in every 10th of a second, a new image is classified and decides the steering and throttle.
* The data collection consists of capturing 20 and 37 laps at a rate of 10 images per second, creating two labels one is throttle from 0 to 1, and second is steering angle -1 to 1.
* A question arises regarding the max steering angle: Is it 60 or 90 degrees for left and right turn? I need to confirm this.
* Two sets of data, small and large, are tested in 16 conditions in total.
* Independent variables include four different models.
* The dependent variables are the crashes.
* One condition includes testing the car attacking every image received by the camera while testing the model. This approach is quite brutal because the car was not trained only with the attacked images, but in a mix with normal and attacked, future work could include testing a partial set of attacks.
* The experiment tests how the data collection plays a role in the performance.
* four different training processes generated four different models, which will be tested in four different conditions.
* The video is not explaining enough. It is better to give more context than only showing the model's name. The videos themselves are okay. Just the cards explaining them are not yet. 
* When sending the submission package, I should also send this video to the opponent and to the committee
* I need to speculate about where the accidents more happen in the track. Does it coincide with the places where the light was brighter? I need to analyze this.
* In one of the conditions, all the images used by the model to classify are corrupted. However, only 50% of the images were corrupted during training, and a random selection of images was taken, keeping balance 80%, 20% training, and testing set, respectively.
* Future work could include different combinations of perturbed images and not. 
* Need to clarify the different meanings of the four different data sets.
* The crashes are dependent variables and my quality yardstick.
* In the method section, describe the independent variables 1) Data Collection, 2) Training, 3) How will evaluate.
* Keep those headlines in the result section, and the results of data collection are the characterization of the dataset.
* An example of the phrase is "...after collecting data as described in section 3.3.2, the dataset resulted in the following characteristics."
* In training, explain how the learning takes place, then training outcomes is the headline in results.
* 4.3 should be evaluated (without results)
* Four models tested in 4 different conditions, explain this clearly in the intro of the sections even it becomes repetitive, but it needs a brief intro about what are the models in intro 4.3, 4 models, four conditions, explain the four settings
* Instead of Testing 1 - Use evaluation of model MTSA
* Subsection 4.1, 4.3.5 summary, evaluation.
* Overall, the research is very nice.
* Increasing training data do not help, point and explain how to interpret the improvement in the discussion.
* 1) Should have adversarial hope training helped with changing light difference
* 2) Vision corruption, using it in every image was different from training which had only 50% images corrupted, therefore is expected the model still not perfect.
* To explain the increase in crashes from 7 to 8 is that vision corruption in all images is very strong, and the addition of high light makes it very different from the dataset because the high light alone was not a problem.
* Good progress so far!
* Need to update video labels and update structure document

## The following is the new structure suggested by the supervisor


I would distinguish between 'data collection (expert demonstration)', 'training (of the built-in CNN)' and 'testing (of the car)':

data collection:
- light = {low}
- laps = {20, 37}
- 10 images per sec
- label 1 (throttle): position in [0, full speed]
- label 2 (steering wheel): angle in [-1, 1] where -1 is 60 degrees left turn and 1 is 60 degrees right turn
=> 2 datasets (small, large)

variable settings in training:
- dataset = {small, large}
- image data augmented by adv attack data = {no, yes}
=> 4 different settings = {small, small_advA, large, large_advA}

variable settings in testing:
- laps = {2}
- light = {low, high}
- vision = {uncorrupted, corrupted} NB: corrupted vision is created by adversial attack like modifications of the real-time image; NB: in case of corruption, every single image is corrupted
=> 4 different settings

--

Independent variable: training dataset (4 different values)

Dependent variable: # crashes


<hr>
<br>



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
