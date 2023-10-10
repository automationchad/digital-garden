An organized collection of design patterns that relate to a particular field is called a [[pattern language]]. This language gives a common terminology for discussing the situations designers are faced with.

> The elements of this language are entities called patterns. Each pattern describes a problem that occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice. — Christopher Alexander, _[A Pattern Language](https://en.wikipedia.org/wiki/A_Pattern_Language "A Pattern Language")_[[1]](https://en.wikipedia.org/wiki/Design_pattern#cite_note-Alexander,_A_Pattern_Language-1)

Documenting a pattern requires explaining: 

1. Why a particular situation causes problems, and 
2. How the components of the pattern relate to each other to give the solution 

[Christopher Alexander](https://en.wikipedia.org/wiki/Christopher_Alexander "Christopher Alexander") describes common design problems as arising from "conflicting forces"—such as the conflict between wanting a room to be sunny and wanting it not to overheat on summer afternoons. 

A pattern would not tell the designer how many windows to put in the room; instead, it would propose a set of values to guide the designer toward a decision that is best for their particular application. Alexander, for example, suggests that enough windows should be included to direct light all around the room. He considers this a good solution because he believes it increases the enjoyment of the room by its occupants. Other authors might come to different conclusions, if they place higher value on heating costs, or material costs. These values, used by the pattern's author to determine which solution is "best", must also be documented within the pattern.

Pattern documentation should also explain **when it is applicable**. Since two houses may be very different from one another, a design pattern for houses must be broad enough to apply to both of them, but not so vague that it doesn't help the designer make decisions.

The range of situations in which a pattern can be used is called its context. Some examples might be "all houses", "all two-story houses", or "all places where people spend time". For instance, in Christopher Alexander's work, bus stops and waiting rooms in a surgery center are both within the context for the pattern "A PLACE TO WAIT".

### Generic structure and layout

Usually the author of a pattern language or collection chooses a generic structure for all the patterns it contains, breaking each into generic sections like context, problem statement, solution etc.

Christopher Alexander's patterns, for instance, each consist of:
1. a short name, 
2. a rating (up to two '*' symbols)
3. a sensitizing picture, 
4. the context description, 
5. the problem statement,
6. a longer part of text with examples and explanations, 
7. a solution statement, 
8. a sketch and further references. 

This structure and layout is sometimes referred to as the "Alexandrian form".
### Simple example of a pattern

- _Name_: ChocolateChipRatio
- _Context_: You are baking chocolate chip cookies in small batches for family and friends
- _Consider these patterns first_: SugarRatio, FlourRatio, EggRatio
- _Problem_: Determine the optimum ratio of chocolate chips to cookie dough
- _Solution_: Observe that most people consider chocolate to be the best part of the chocolate chip cookie. Also observe that too much chocolate may prevent the cookie from holding together, decreasing its appeal. Since you are cooking in small batches, cost is not a consideration. Therefore, use the maximum amount of chocolate chips that results in a really sturdy cookie.
- _Consider next_: NutRatio or CookingTime or FreezingMethod