# CS230
## Project Reflection – The Gaming Room Software Design

### Briefly summarize The Gaming Room client and their software requirements.  
The Gaming Room, the client, wanted to expand their Android-only game *Draw It or Lose It* into a cross-platform web-based game accessible from multiple operating systems and devices. The main requirements were to ensure that game, team, and player names remained unique, support multiple players and teams, and design the system so that only one active game engine instance could exist at a time. They also required strong security and scalability across platforms.

### What did you do particularly well in developing this documentation?  
I did particularly well in structuring the design document so that it was easy to follow and connected directly to the client’s requirements. I explained how patterns like the singleton and iterator ensured uniqueness and scalability, and I clearly described how the UML class diagram supported the logical design of the game. I also added detailed evaluations of operating platforms and system architecture that showed how the design would scale and remain secure.

### What about the process of working through a design document did you find helpful when developing the code?  
Working through the design document helped me think carefully about architecture before coding. By defining requirements, constraints, and UML models in advance, I avoided potential design flaws and had a clear reference for implementation. It also kept the focus on meeting the client’s needs rather than just jumping into code.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?  
If I could revise one part, I would refine the domain model section with more diagrams and interaction flows. Adding sequence diagrams or state diagrams would make it easier to visualize how users interact with the system and how objects communicate. This would help developers beyond me quickly understand the flow of operations.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?  
I interpreted the user’s needs by focusing on scalability, uniqueness of players/teams, and cross-platform access. These requirements shaped the decision to use the singleton pattern for a single game engine and Java for portability. Considering user needs is essential because software is only successful if it solves the real problems users face. Ignoring those needs would result in features that do not add value or in a system that fails to perform as expected.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?  
My approach combined requirements analysis, UML modeling, and evaluation of platforms and architectures. I used design patterns to enforce constraints and considered security, performance, and scalability from the start. In the future, I would continue using this structured process but also add more prototyping and user feedback earlier to validate assumptions. This would ensure the design is both technically sound and user-centered.
