# SNHU_CS_230

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**
The Gaming Room client was a hypothetical client who already had an existing game "Draw It or Lose It" on Android platforms. The goal was to expand this into more platforms like traditional web browsers and iOS platforms. To accomplish this we were tasked with evaluating the potential ways we could do it, mostly focusing on the game being run on a client-server basis. The game itself followed a singleton design pattern for each instance of the game. Then the teams and players would follow an iterator design pattern.

**What did you do particularly well in developing this documentation?**
I was able to weigh different platforms strengths and weakness against each other and determine the best ones for our use cases.

**What about the process of working through a design document did you find helpful when developing the code?**
It provides a solid starting block to get the project off on the right foot. I'm sure as you develop new ideas to solve problems pop up but at least starting with the design document gives you a good understanding of all the factors involved in the project.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**
I think evaluating platforms for the client side felt very weak and I didn't fully grasp all the challenges that might be posed due to inexperience in developing directly on all of them.

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**
The user's needs are how you start building your requirements for what a piece of software should do when it's completed. In this case the need to be able to play with people on different platforms was a large reason why I went with a client-server approach so I could leverage a RESTful API on the server and provide the same game experience to each platform's interface. 

It's important to consider the user's needs when creating software because without that you're creating software for the sake of it. If you want your software to actually solve problems for people, then it needs to keep how the end user will interact with it in mind.

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**
Designing software starts with building out a list of requirements from the customer/end user's needs. From there you start to solve each problem that arose during the requirements building. During this stage it's important to keep in mind not just how the code is going to be written but also how we will deploy it and what platforms/architecture will be involved. In many cases, this can inform the code you're going to write so it's important tackle these distribution questions early on.
