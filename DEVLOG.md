#Devlog

Nested routes need to have their parents with full closing tags.

Differences to note between Link and, Navigate and useNavigate. The former belongs to declerative programming whereas the other belongs to imperative programming. Basically, one passively sets up routes whereas the other actively forces one into routes. Links have to be issued on the DOM, wheras navigations need not. A better explanation provided online on StackOverflow of these different paradigms:

"""
- Imperative programming – focuses on how to execute, defines control flow as statements that change a program state.
- Declarative programming – focuses on what to execute, defines program logic, but not detailed control flow.
"""

"Declarative programming is a paradigm describing WHAT the program does, without explicitly specifying its control flow. Imperative programming is a paradigm describing HOW the program should do something by explicitly specifying each instruction (or statement) step by step, which mutate the program's state."

The <Outlet> component tells React Router “where” to render nested child <Route> elements.

A lot of the logic here is similar to my experience with Django: a lot of the interaction is taken care of by importing various components from react. It would be good to get to know these ready-made components in more depth.

# Info
"The useParams() method returns the URL parameters as key/value pairs in an object. In this case, you could access the songId by writing const { songId } = useParams()."

# Questions
So it's possible to be "logged in", but my question is where is one logged in if there is no server? Or does React simulate a server locally? Or is the "logged in" state saved into the browser? Homework for me to figure out. 
