# nfa_design_exercises_1
Summary of Learning
1) Which problem(s) gave you the most trouble? Did you avoid any problem that is too challenging to finish by deadline? Did you ask
questions to AI/instructor?

None of the problems I chose gave me significant challenge. After I finished, I asked AI why there are some cases where an NFA ends up
being identical to its DFA. I learned that for counting or modular arithmetic languages, nondeterminism doesn’t reduce the number of
states because the machine still has to keep exact track of the count. In the future, I plan to try all of the problems, especially the AND/OR cases, to get a better understanding of NFAs.

2) Which problem(s) surprised you with a "gold-st-ring"? Which next state(s) did you not account for in the subset of next states? why?
How to make sure you avoid such errors in your future flight/traffic/compiler state controller tasks, or in the near future, the course
projects/exams?

For problem 12, when I first tested 1110, I was surprised that it was rejected. I had been thinking only about counting the number of 1s,
so I only added transitions for 1 and forgot about 0s. I did not realize that without '0' transitions, the machine would immediately
reject as soon as it read a 0. Once I understood that zeros are allowed and should not change the count, I saw that I needed a 0 loop on
each state. For the remaining problems, no test string necessarily surprised me in terms of the final result, because I thought out the
transitions more clearly this time. However, a few inputs interested me, like 11011 for problem 15 and 111111 for problem 19, so I
decided to draw out their transitions in a computation tree and check out the step by state run.

To avoid these kinds of errors in the future, I will continue testing short, typical, and edge case strings and trace them carefully.

3) Other insights/comments/questions that you want the grader/instructor to know.

No other insights/comments/questions.
