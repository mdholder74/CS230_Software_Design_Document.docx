# CS 230 Software Design Document: The Gaming Room

## Reflection

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**

The client was The Gaming Room, which offers Draw It or Lose It as a game application. The game was originally available only as an Android application, and the client wanted to move to a web-based version that would allow them to serve more users across multiple platforms.

The main requirements were:

1. A game must support one or more teams.
2. Each team must have multiple players assigned to it.
3. Game and team names must be unique so users can check whether a name is already in use when choosing a team name.
4. Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.

**What did you do particularly well in developing this documentation?**

I did a good job with the final recommendations for The Gaming Room. I recommended using a Linux operating system on a cloud platform, specifically a Linux distribution such as Ubuntu LTS along with Amazon EC2. I explained why Linux was the best choice by discussing its operating system architecture, compatibility with various technologies, and cost-effectiveness.

In the storage management section, I discussed the Linux file system, cloud storage, and PostgreSQL for managing structured data. In memory management, I covered how developers can manage memory through techniques such as virtual memory, caching, and swap space. I also explained distributed systems and networks, including the server side and network connectivity. Finally, I covered security, including how it can be built into Linux and PostgreSQL, along with additional security features that could be added to the application.

**What about the process of working through a design document did you find helpful when developing the code?**

I found the design document very helpful because of its structure and the topics it guided me through. It ensured that I understood the client's needs, application requirements, and constraints before conducting research and comparing and justifying different platforms, programming languages, and operating systems.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**

I would choose the evaluation section, where I compared Mac, Linux, Windows, and mobile devices across multiple areas, such as operating systems, server-side capabilities, client-side capabilities, and development tools. I would take a closer look at what makes each platform truly different and evaluate its strengths and weaknesses in greater detail. This would give me an opportunity to improve the comparisons and provide stronger justification for my final recommendations.

**How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?**

I interpreted the user's needs by understanding their current state, the available resources, and the strengths of the existing IT or developer support before examining the application's requirements. Understanding these factors allowed me to move in the right direction when selecting the systems and tools for the application.

Considering the user's needs is important because it helps ensure that the software design aligns with the client's goals, available resources, and technical requirements. Without understanding these factors, I could have recommended solutions that do not meet the client's needs, are inappropriate for their situation, or are difficult to support and maintain after implementation.

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**

My approach to designing software is to first understand the client, determine the application's requirements and constraints, and evaluate the client's needs against them. After that, I can move on to selecting operating systems, cloud platforms, storage management solutions, and security measures. In the future, I would use a design template and take a similar approach when designing another software application because it creates structure and provides a clear process to follow. Understanding the requirements first, researching possible solutions, and evaluating the available options helps ensure that the final design is based on the client's needs and supported by sound reasoning.
