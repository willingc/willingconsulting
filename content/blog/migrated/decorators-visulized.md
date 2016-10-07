<html><body><p>Decorators make code more readable. When learning how decorators work, it's easy to get confused. When teaching decorators, students often ask "but how does it work" and "why does it work". Magic, it just does, and follow the pattern of the example could be reasonable though less than satisfying responses.
</p><h3>Online Python Tutor</h3>
Learning to use decorators can be frustrating until the learner understands how decorators work. To build mastery, students want to visualize what the computer is doing when using a decorator. Fortunately, <a title="Phillip Guo" href="http://www.pgbovine.net/" target="_blank">Phillip Guo</a> has developed <a title="Online Python Tutor" href="http://pythontutor.com/" target="_blank">Online Python Tutor</a> to improve the student's learning experience.

Online Python Tutor lets users enter code and interactively see what is happening when the code executes. It breaks things down to a step by step visual of how data moves behind the scenes when a program executes.
<h3>Sharing and embedding visualizations</h3>
Two great features of Online Python Tutor are the user can share live visualizations of the code and can embed the visualizations in any web page. The emphasis on sharing and collaboration helps teachers to easily communicate concepts to their students.
<h4>Let's look at a decorator example</h4>
To use the interactive demo, simply click on the 'next' and 'back' buttons to move through the code step by step.

[iframe src="http://pythontutor.com/iframe-embed.html#code=def+make_bold(fn)%3A%0A++++return+lambda+%3A+%22%3Cb%3E%22+%2B+fn()+%2B+%22%3C/b%3E%22%0A%0Adef+make_italic(fn)%3A%0A++++return+lambda+%3A+%22%3Ci%3E%22+%2B+fn()+%2B+%22%3C/i%3E%22%0A%0A%40make_bold%0A%40make_italic%0Adef+hello()%3A%0A++return+%22hello+world%22%0A++%0AhelloHTML+%3D+hello()&amp;origin=opt-frontend.js&amp;cumulative=false&amp;heapPrimitives=false&amp;textReferences=false&amp;py=3&amp;rawInputLstJSON=%5B%5D&amp;curInstr=0&amp;codeDivWidth=350&amp;codeDivHeight=400" width="800" height="500" frameborder="0"]
 
<h3>Phillip Guo's research publication</h3>
For the those that are curious, <a title="Phillip Guo's research paper" href="http://pgbovine.net/publications/Online-Python-Tutor-web-based-program-visualization_SIGCSE-2013.pdf" target="_blank">Phillip Guo's research paper</a> presents why and how Online Python Tutor improves learning. Thank you for this wonderful program!</body></html>