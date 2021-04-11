# [Leadership principles](https://leetcode.com/discuss/interview-question/437082/amazon-behavioral-questions-leadership-principles-lp)
### 1. Tell me about a situation where you had a conflict with someone on your team. What was it about? What did you do? How did they react? What was the outcome?
(S) I got conflict with one of my team mates during pair review. (T)Before pushing my changes to remote I ask my team member for peer review. He told me to change the commit message that he provided after reviewing. I could not agree with him as I think my message was enough descriptive to me. (A)So we showed both messages to manager. After reviewing both messages he changed into new one. (R) Now we follow a format provided by my manager for commit messages. This happens because English isn't our native language and sometimes we face problems to describe.

(S) Got conflicted with my manager. (T) On the eve of my religious festival he told me to work on festival day. (A) I didn't agree with him because if I would work during that time then it would take my happiness with my family far apart and that would give me suffer in the long run. So I explained why I was not interested to work during that time. (R) He understood my point and told me to reach him if I need any extra leaves for this.

### 2. Give an example of when you saw a peer struggling and decided to step in and help. What was the situation and what actions did you take? What was the outcome?
(S) One of my team members / colleagues was struggling in his assigned task. (T) He was assigned to understand a feature and implement another feature which was almost similar to that. (A) The assigned person wasn't fresher in job experience. He worked in R&D team and them he joined my team. So was new in SDE. When I saw that he was struggling and might miss the release date so I decided to step in and helped him. First I understood his knowledge about the project and SDE. Then when I found both of them were not sufficient to complete the feature so I helped him explaining my knowledge about my project in simple way and then provided him some useful links(gRPC, Singleton, OOP Basic) which needs for my project. We also had lunch for several times and discussed in case of any confusion.
(R) As a result I saw that he could meet his deadline and was interested to take new challanges willingly. I also learned many things and became clear about some concepts.

### 3. Tell me about a time you committed a mistake?
(S) In my current job once I had to fetche all AiModels assigned to a specific tenant. (T) So I had to write a sql query to fetch the aimodel list. (A) I wrote the query in inefficient way. My plan was to make query on indexed column. But when I wrote the code I forgot to create index at that column. When describing to my manager I explained that it would be indexed column. It was fine in local machine but taking long time in live application.
I rechecked all the code if I made any mistakes. I found nothing in the source code. Then I checked my documentation about the process and found that I forgot to add index. Then I wrote down that mistakes into my list so that I never repeat them again. (R) Now before submitting any changes of my code I recheck if source code and planned (Documents) are same or not. Also check my mistake list so that I never repeat those mistakes again.

### 4. Tell me about a time when you earned your teammate's trust?
(S) It was after joining to my current company. As I am new here so it is not obvious that he knows me well. (T) So I need to earn his trust by my work. (A) I asked my co-worker about my boss activities. I mean what he likes or dislikes and which approaches he follows. I found something useful that must be acquied to earn his trust like letting him know which tickets I am working right now, what's the ticket status, constant update, constant check-in, and letting him know then task is finished. Also he likes to be consistant on those. Above all, I need to communicate with him by myself. (R) I heared once he told to my team-mates that I the Sachin TendulKar (!) of my team. By following these process, right now I am used to these process in my personal life !

### 5. Tell Me About a Time When You Failed to Meet a Deadline. What Things Did You Fail to Do? What Were the Repercussions? What Did You Learn?
(S) In my current project when I was working on Graphical view of endpoints (Cameras) I had to write the code flow for that module. In my team it is strictly followed that everyone should write the code flow after implementation. I follow this so that any new guy in my team can understand source code easily. (T) So I also needed to write code flow of that feature. I had 3 days in my hand. (A) So I wasn't much serious about it because I thould I would be able to finish that within single day. So I spent first two days with some less important taks like refactoring my code, changing into more meaningful variable name etc. At 3rd day when I started writing code flow I saw that there are lot of things that I need to write also. And I was not concern about those. (R) So basically I failed to deliver that task on that day. I needed one more day to complete. After explaing this, I requested my boss to increse it for one more day. He agreed with me as it was a mistake and told me not to repeat the same again. There are several thinkgs that I learned from it.
> 1. Never think anything less important unless you are familiar to it
> 2. Try to complete your task at the first part of assigned time
> 3. Make a priority list to complete your task
> 4. Update your plan to boss so that he can guide you in any time
I write down all my mistakes in a list so that I never repeat them.

### 6. Tell me about a time when you invented something?
(S) When I worked on Samsung, during developemt, one device could get only one time data for testing. In order to get new data we needed to reinstalled the app. It was boring. Besides, server provided data only one time because that server was using for another large application (S-Health). (T) So we needed to do some mechanism so that server doesn't get load and from mobile site we get latest data. (A) I thought a mechanism that I will shift the data from old to new. I did this by myself. But I face serveral challanges because every table's timestamp was unique. When I tried to shift them I got serveral exception because of unique constrant. So I took a backup of data to temp, then delete all the data from main database then tried to add timestamp with each entry. (R) By this way, we could solve our problem and it saved our time to negotiate with server team and also it decreased server load time and increased our productivity. 

### 7. Tell me about a time when you took important decision without any data?
(S) When I was fresh student of my graduation time I participated serveral online programming competitions. (T) Suddenly some of my friends stopped participating in the competitions. I asked them the reason of not participating. They told me that there is not future of this kind of competitions. (A) As my dept is Information Technology I am interested to software Engineering and logic is called the brain of a software so I continued it. They told me that it will be useless of my hard works. During that time I didn't have any sufficient data to prove that competitions is really important for increasing thinking capabilities of an engineer. But I continued it as I love it and I have great enthuasism on it. (R) After participating many competitions in online and onsite I could make some good positions. I got offer from serveral local companies before competing my post graduation. And now as a software engineer I believe that business logic is the core part of a software. 

### 8. Tell me about a time when you helped one of your teammates?
(S) In my current project when I work on a service then sometimes I need to call another service through gateway. When I was about to finish a task I saw that some test cases were not passing. (T) I rechecked everything and found okay from my side. But as in the service layer I need to call another service so it might had some possibilites that that service was providing wrong data. (A) So I by myself check that service and found that there are some missing cases there. I walked to him and informed about it. He also checked it and found the problems. But he was busy with other task. So I offered him that I could do it for him because at the end of the we had to finish the project before the deadline. After fixing those bugs I pushed that changes and added him as a reviewer . He reviewed and merged that changes. (R) Then the bugs were fixed and my module also passed for all cases.

### 9. Have you ever failed at something? What did you learn from it?
The interviewer wants to check these 3 topics -
1. Did you own it?
2. What did you learn from this mistakes/failure
3. What was the recovery/success?

(S) In second year of my graduation, I had a team of 4 people to complete our semester project. (T) We planned to make a management type project. We had only two weeks at our hand. I took the responsibility to implement the backend. Others also took their interested part. (A) I was confident about my task. But after that I got two assignments to complete whose deadline were before the project submit date. I tried my best to complete all of them according to priorities. I could complete the assignments but could realised that I might fail to complete my part. And that's it. I couldn't complete it. (R) Although we were marked well enough for designing, documentations, presentation, but I felt like I let everyone down.
Learnings -
1. 


# Company Specific Questions
### 1. Why do you want to work here?

> Do not talk about salary Talk about product, culture, job description Talk about mutual connection's feedback who works at their company Long term goal

* Evaluate your intensions: make a quick list for why you want to work for the company and what inspire you most about the positions.

* Do your Research: Find out everything about the company and the positions

* Show that you're the solution to their problem:

* Be yourself and show your passion:

* Be specific with your examples:

 > Small company: "I want to be in a place where I'm not just a cog in the machine, and can have plenty of opportunities to grow."

 > Big company: "I want to be in a place where my work has an impact on millions of users."

## Quora
### 2. Why Do you want to work at Quora?

>Quora has a millions of user and I always wanted to work in a global company where my work will create an impact on these huge number of people. I wanna grow myself as a full stack software engineer. And in quora I'll get the opportunity to work with from Machine Learning to Distributed Systems. Also If I'm not wrong, then quora uses Continous Integration, so I don't have to wait weeks before I can see my code live. That's very fascinating to me.


[Behavioral interview](https://linlaw0229.github.io/2019/06/29/Amazon-behavioral-prepare/)

[All questions that are asked in Amazon LP](https://www.youtube.com/watch?v=RMA7tI-LTWY&ab_channel=DanCroitor)
[In text](https://pastebin.ubuntu.com/p/vBGThQzyvg/)
> Check it's description

> SBI = Situation Behavior Impact rules

## Importants things to keep in mind
* STAR = Situation, Task, Action, Result
* Research the company and your interviewers
* Get a list of 10 interesting questions
* You are almost certain to encounter certain questions, for example, a quick overview of your recent project, your top strengths, your development areas, why you apply to this role. You should have very crisp answers to these questions.
* Bigest strength -> Related to roles with story (Taking initiative)
  1. Started System test for my team
  2. Started weekly practice session
  3. Started feeback session anonymously
  4. Started weekly knowledge transer with my team so that everyone becomes up to date with latest code
  
* Weakness -> Don't relate too much with roles
  1. Feel sleepy during metting if meeting helds right after lunch
* 

### 3. Do you have any questions?
Ask critical/hard questions.
1. What's the work expectation here? How does that balance with life?
2. How does the reward structure work there? I mean if people do really good job's then how does the company reward them?
3. If I pass phone interview, Where will my onsite interview be held?
4. What's the training proccedures for freshers.
5. As far as I know it is hard to get Switzerland's visa from BD when I have experience less than 5 years. So what will happen if I don't get visa?
6. What do you expect from me after 5 years?
7. What does google do for career growth of an employee?
8. What will be the focus area during the interviews? How do you decide who interviews candidates?
9. What is the expected time to come back with a solution during the interview?
10. What should I prepare for the interview?
11. What are the most likely reasons candidates get rejections?

