# 系统设计：结构化地思考
[System Design Interview – Step By Step Guide](https://www.youtube.com/watch?v=bUHFg8CZFws)

系统设计的目标：功能性、非功能性（可靠性、可扩展性、可维护性）。

## Step By Step Guide
* Functional requirements (API)
  * discuss with interviewers with specific behaviors
  * write down verbs
  * define input and return values
  * make several iterations to brush up the APIs
  * **Now we know the scope of the design**
* Non-functional requirements
  * focus on scalability, availability, performance
  * **Goal**: figure out what qualities of the system she is most interested in.
* High-level design
  * think about how data gets in
  * how data gets out?
  * where data is stored?
  * draw these components
  * generic is OK, datails will follow later
  * **Goal**: get understanding of what components to focus on next. And the interviewer will help us.
* Detailed design
  * start with data (storage, transfer, processing)
  * knowledge and experience becomes critical
  * use fundamental concepts
  * apply relevant technologies
  * **Goal**: after technical details are discussed, we can move to discussing other important aspects.
* Bottlenecks and tradeoffs
  * Listen carefullty to the interviewer
  * In her questions there will be hints what these bottlenecks are.
  * know the tradeoffs. We just need to pick and apply a proper one.