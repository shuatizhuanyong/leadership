
# answer behavier question principle 

## STAR
* situation  - background info
* task       - what you had to do 
* activity   - what you did - this should be the longest part of the answer
* result     - positive; quantifiable; what you learned; what you would do differently next time


# Amazon Leadership Principle 
## 1: Customer Obsession
> questions:
* Give me an example of a time when you did not meet a client’s expectation. What happened, and how did you attempt to rectify the situation?
```
  when I worked on blog migration system. 
situation: there was a very old and popular blog system, build on 2005/2006. on 2011/2012, we decide to do a big upgrade. the reason is it becamed too hard to maintain and no one real understand the logic inside, very old UI. DAU was going down,so the team spent 9-10month rewrite most components including back-end service and UI/UX. We thought it became much better than before. however, the user didn't think so.
 task: meet the user 's expectation
 activity: I follows lots of common users, read end user's feedback. discuss with product manager. i rememeber we always received some feedback like always they couldn't find certain links. customer service always give them the standard answers: like how to find it. I found it was a common issue may effect lots of our users.  
```

####

## 2. Ownership
Leaders are owners. They think long term and don’t sacrifice long-term value for short-term results.

* Tell me about a time when you had to leave a task unfinished.
* Tell me about a time when you had to work on a project with unclear responsibilities


## 3. Invent & simplify
* Tell me about a time when you gave a simple solution to a complex problem.
    --stub?
* Tell me about a time when you invented something
    -- term-finder
    -- config-center
    -- atom client trigger




## 4.Are right, a lot

* Tell me about a time when you were wrong
  story: build a service with dynamo, later adding a cache to handle most request
* Tell me about a time when you had to work with incomplete data or information
  ccp delivery message example:
    1. in the begining, pm want to check invoke vendor api every hour, and then compare what we have in the db. lastly, delivery informations which has difference. 



## 5. Learn & be curious 
* Tell me about a time when you influenced a change by only asking questions
* Tell me about a time when you solved a problem through just superior knowledge or observation.

## 6. Hire and develop the best
> Leaders raise the performance bar with every hire and promotion. They recognize exceptional talent, and willingly move them throughout the organization

* Tell me about a time when you mentored someone

## 7. Insist on the highest standards
> Leaders have relentlessly high standards – many people may think these standards are unreasonably high. Leaders are continually raising the bar and driving their teams to deliver high quality products, services and processes. Leaders ensure that defects do not get sent down the line and that problems are fixed so they stay fixed.


* Tell me about a time when you couldn’t meet your own expectations on a project.
* Tell me about a time when a team member didn’t meet your expectations on a project.

## 8. Think Big
* Tell me about your proudest professional achievement
* Tell me about a time when you went way beyond the scope of the project and delivered
  -- bpm tool


## 9. Bias for action
* Describe a time when you saw some problem and took the initiative to correct it rather than waiting for someone else to do it.
 small example: daily code refactor. after I found some common api designed really unfriendly, there is one case. for log with 6 parameters, Just did a wrapper for it 

* Tell me about a time when you took a calculated risk.

* Tell me about a time you needed to get information from someone who wasn’t very responsive. What did you do?

## 10. Frugality

## 11. Earn trust
* What would you do if you found out that your closest friend at work was stealing.
 
*  Tell me about a time when you had to tell someone a harsh truth.
Yes, like fire teamate. I did this for couple times before. The time we hired the person, we need a front end developer SAAP. after a couple month, we still don't have good candidate, then all teamates lower the bar . finally we got a guy, who looks ok, but may have small issues. after worked for the team in couple or 3 month, we started to dig into the code that he contributed and always has issues. At that moment, we found the problem: the code was no structured, and hard to maintain: no any standard for code style. different modules used different code styple, and lots of copy pasty code from internet which no one really understand the mean. we sad, and want him to change and follow the team's work styple. he defined and still want to keep in same style which he was comfortable. after couple times to trying, we gave up, and the team decided to fire him. and I was the person to tell him. keep professional and the reason, and why he is not the right person for the team. say sorry we gave him a bad  experience, and told him this is the team's fault: hiring too quickly only want to solve the emery issues not for long term.

## 12. Dive deep
* Give me two examples of when you did more than what was required in any job experience.

rsync data to temperal store vendor data in our side. in the begining, i worked for a small client, and the module only required to implement to support this client . I found 20% of our customers has the similar requirement. So I did a common solution with dynamo and cache which can support all clients via configs.


## 13. Have backbone; disagree & commit

• Tell me about a time when you did not accept the status quo.

• Tell me about an unpopular decision of yours.

• Tell me about a time when you had to step up and disagree with a team members approach.

• If your direct manager was instructing you to do something you disagreed with, how would you handle it?
like a**m system implementation phase, my boss wanted me to add some specific features only used to support the current vendors which is against our plan. I disagree with this point, and discuss with him. these happned more than once. Sometimes, I can use a common solution to cover the specific requirement. like he want to add one more column in dynamo which only used to track for business purpose. Actacully we has designed a http headers for this purpose which can be found in log system. however this log solution not working for business guys, but i still don't want to break the system. after couple days thinking and design, we build a sperate elastic search domain in in aws to support business guy which contains full datas in dynamo and nessary logs for them.

## 14. Deliver results
* By providing an example, tell me when you have had to handle a variety of assignments. Describe the results.
* What is the most difficult situation you have ever faced in your life? How did you handle it?
on account system migration, time is short, only 2 - 3 month left, 2 developers quit.
