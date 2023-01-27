# Context Free

##  Who is this programming language for?

I would say its for a very similar audience as the supercollider is for audio as context free is for visuals. It allows for the use of algorithms and code to generate images.

## What is easy to do in this language? Why is it easy?

Recursive structures and mechanical looking shapes. The ability to use loops and mathematics to define the shapes of the generated picture allows for more complex and quick repetitions of the same general structure. This allows for literal recursive trees of images that are much easier to string together in a loop then to create one by one. 



## What is hard to do in this language? Why is it hard?

Anything natural looking is incredibly difficult in this language, since you have to start with a set of basic shapes and straight lines. Even with curve packages, it may be difficult to create anything that feels like a hand made stroke. In addition, small variations (like painterly looks) are also difficult to manufacture, since every non repetitive section must be coded by hand. 

## How did you learn how to program in this language?
Honestly the documentation was hard to get through. I mainly used the examples they gave and changed their variables to see how the resulting image changed. 
I did check the documentation when needed but it was mainly adjustment and iteration. 



## What is the underlying _computational model_ for this programming language? 

It runs the code and step by step edits an image to add and remove colored pixels. This means that it would place a black box on a black box even if that doesnt actually change the image. It is simply a sequential steps for 

_We don't yet have a great definition of the term "computational model". 
For now, try to come up with the clearest, most concise explanation of what 
happens when a ContextFree program runs._


## What do you think is interesting about the ContextFree program you wrote?

The main example is of the shape system where each level of the code is a shape built of shapes. 

I think it clearly shows how the sequential rotation of individual images changes. Also it is a literaly tree! Great example for recursive generation (although I borrowed alot of the structure of the code from an example)