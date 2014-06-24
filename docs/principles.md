principles

- Patterns

Based on Alexander .. patterns applied to our goal are the minimum reusable unit that deliver 1 output.

The concept of pattern, will be different from the patterns applied to programming, or the pattern concept used in Object Oriented languages, is no the intention to create a new definition, we are using the concept straigth from the source.

As an intructory example, when we write an script, an script can be lineal, however, if the same piece of code can be reused, we will create a funtion. Later, if we find a piece of code can be reused in a new script, we will import the funtion and use it, so having this in mind, our scripts will be written with this idea in mind from the very beggining.

- Idempotency

Idempotency is ..., in our case, at different levels we will use the intention of idempotency as run once, skip if already there.

This concept exits in IT with several names, like desired state, ,..

- 12 factor app

12 factor app came from ... based on all the expertise from helping people to build good quality applications, ready for the cloud.

From here, we will use same ideas that will allow make our scripts reusables, either to be executed from the command line, or from other tool.

As an example, we will use the concepts like do not include hardcoded information in the scripts (like user and password), or have the option to overwrite default information from the command line.

- Aligned to ITIL

From the ITIL framework, we need to plan ahead that some of our work, may end being used for projects, and later into BAU/OPS, so we will document as much as possible, create templates for documentation, create templates for AsBuilts

- Recognize industry best practices over "just works"

After prototyping some of the requiremt, we may recieve feedback from our end users (Projects, Ops) and in some cases, the way we are doing something, may not be better to they have.

If our way of doit, is not better/quicker, or simply doesn't generate any value they won't use it.

- Chain of value

In today's competitive world, end to end deployments are expensive.
It cost money, time, resources in any combination of them.

So when possible, we will review at atomic level for each task, what's the value of the task vs other options, and we will try to go for those that:

* Doestn't cost money
* Doesn't require more time or can be automatized
* Add value

- Include the full cycle of IT

Some companys apply some areas of ITIL, for example on operations, others can use any of the several projects methodologies, or any of the developments metodologies.

In order to keep this methodology-free, we will just enumerate the areas that are involved, and provide a minimum set of information required, as input from previuos areas, and outputs for documentation and/or next area.

- Open to include new technologies
- Open to incorporate trends from DEVops
- Must be reproducible, we will try to time 5 continuous deployment


  

