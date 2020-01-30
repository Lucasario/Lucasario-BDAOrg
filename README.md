# Lucasario-BDAOrg

So, why did I, Cassius Peter, a grad student in ORIE, take this course?

Well, the thing that put this course on my radar was that I needed a requirement
to complete my Masters of Engineering in ORIE. But there were a lot of classes
that could have fulfilled that requirement, so why Bayesian data analysis?

There's two answers to that question. The first is that I've been a fan of probability
for a ling time. I aced probability in junior year of undergrad, and then helped the
teacher teach it the next year. Not only is it a really fun field of mathematics, as
I am a big fan of board games of chance, but it's also a highly useful field of mathematics. 
I ask you to find me one field of engineering for which computer simulation isn't used,
and computer simulation is nothing without probability, which is a long-winded way of saying
that probability is required for every field of engineering. 

That's only half the story, however. In the two seperate times I took intro to probability, there
was one topic that was mentioned, but was never covered in enough detail for me to understand.
If you haven't guessed it by now, that subject was bayesian versus non-bayesian probability. As far 
as I could tell, this bayesian versus non-bayesian probability was a debate on the level of AC versus
 DC, but again, Bayesian probability wasn't even covered. And the word "frequentist" was 
never even uttered. So I'm taking this could to learn about bayesian probability, learn more skills 
that will be useful both in my chosen field of energy engineering, and any other field I find myself working 
in. 

Oh, right, I need to talk about my favorite type of statistical problem. I've kind of beat it to death
at this point, but my favorite statistical problem of all time is the monty hall paradox.
(Editor's note: this was written before we covered the monty hall problem in class)
I first heard the problem Mythbusters, where they ran the experiment 
100 times, switching 50 times, and sticking 50 times, and found that the guy switching was more than twice as likely
to win. 
![](montyhall.png)
Although their statistical evidence was pretty conclusive, their explanation of said phemonemom was 
barely existent, so I had to think it through myself. Here's the best explanation I've derived:
Since we have 3 doors, and the prize is equally likely to be behind any door, the odds of you picking the right door
first time around is 1 in 3. We'll call this event A. We also need to define event B as the event that the prize is behind
the last door; the one you didn't pick, that you could switch to. Since there's always at least one empty door you didn't
pick, and the host will never accidentally reveal the prize, opening the losing door doesn't change the probability of A. 
So P(A) is still 1 and 3. But A and B are mutually exclusive, and collectively represent the entire sample space, so P(A)+P(B) = 1
Since P(A) is 1 in 3, P(B) clearly has to be 2 in 3.

Hey, I said it was the most concise way I could describe it, not that it's a concise way to explain it!
