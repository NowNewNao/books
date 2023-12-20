## Working Code isn't enough(Strategic vs. Tactical Programming)

 This is a concept that will be important in the stream that says, "Just make it work" or "Release it as soon as possible", which is called as _tactical programming_ by the author.


### 3.1  Tactical programming
> You tell yourself that it’s OK to add a bit of complexity or introduce a small kludge or two, if that allows the current task to be completed more quickly. This is how systems become complicated.

This happens quite easily, especially when I am in a hurry to release the product. I think this is a good point to keep in mind.


> complexity is incremental. It’s not one particular thing that makes a system complicated, but the accumulation of dozens or hundreds of small things.

> Each of them probably seems like a reasonable compromise in order to finish the current task quickly. However, the complexities accumulate rapidly, especially if everyone is programming tactically.


> Refactoring may help out in the long run, but it will definitely slow down the current task.

This is very true. But if the codebase that I am working on has already been complicated, what is the best approach? 
For now, what I can think of is
- Small refactoring any time I touch the code
- Pay attention to the complexity when reviewing the code


I'm really interested in it. Hopefully, the following chapters will cover this topic.


> Almost every software development organization has at least one developer who takes tactical programming to the extreme: a tactical tornado. The tactical tornado is a prolific programmer who pumps out code far faster than others but works in a totally tactical fashion. When it comes to implementing a quick feature, nobody gets it done faster than the tactical tornado. In some organizations, management treats tactical tornadoes as heroes. However, tactical tornadoes leave behind a wake of destruction.


### 3.2  Strategic programming

> The first step towards becoming a good software designer is to realize that working code isn’t enough. It’s not acceptable to introduce unnecessary complexities in order to finish your current task faster.

> Most of the code in any system is written by extending the existing code base, so your most important job as a developer is to facilitate those future extensions.

> Your primary goal must be to produce a great design, which also happens to work. This is strategic programming.


What is the great design?
From my experience, it is a design that is easy to understand and easy to extend.
- Maintainability
- Extensibility
- Readability 


### 3.3  How much to invest?

> the best approach is to make lots of small investments on a continual basis. I suggest spending about 10–20% of your total development time on investments. 

8 hours work, approx. 60 to 90 mins for the investment. This is a good amount.

Also, trying to re-design whole system is water-fall, and it won't work as we know.

### 3.4  Startups and investment

Facebook example in interesting.
It starts with "Move fast and break things." and then changed to "Move fast with stable infrastructure.", after realizing that is not sustainable.


### 3.5  Conclusion

> The most effective approach is one where every engineer makes continuous small investments in good design.


I urge myself to do this. I think this is the most important thing to do as a software engineer.



<sub>\*All Imaeges and Refereces are from:
Ousterhout, John K. . A Philosophy of Software Design, 2nd Edition. Yaknyam Press. Kindle Edition. </sub>