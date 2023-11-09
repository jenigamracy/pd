# Agile Project Management

# Module 1

## Introduction to Agile

### Waterfall

- sequential/linear

### Agile

- able to move quickly/easily
- iterations (think lots of waterfalls)
- adaptive
- flexible, repetitive
- based on Agile Manifesto
- incorporates necessary changes throughout life cycle
- came about to innovate products as well as processes
    - needed to please customers
- applicable not just to software
- draws on lean principles (Toyota, 1930s)

| Agile | vs | Waterfall |
| --- | ---- | --- |
| follow informal process to change in requirements; frequent | Requirements | follow formal approval processes to initiate changes; infrequent |
| Use more in-person communication than documentation | Documentation | Use many types of documentation |
| Use stages | Deliverables | At end as a major event |

### Agile Manifesto

#### [4 Values](https://agilemanifesto.org/)

- **Individuals and interactions** > processes and tools
    - when communicating, a simple conversation is more effective than a lengthy email thread
    - work together, collaborate
    - help each other achieve the best outcomes

- **Working software** > comprehensive documentation
    - create value for the customer

- **Customer collaboration** > contract negotiation
    - customer satisfaction has the highest priority
    - no value customer? no point in working on it
    - collaborate early and often
    - focus on what's really needed
    - identify needs, leave space for collaborative work
    - make use of prototypes, ask lots of questions

- **Responding to change** > following a plan
    - change happens quickly
    - change is inevitable
    - expect uncertainty
    - most successful teams are the ones who can integrate changes smoothly

IOW: values on left > values on right

#### [12 principles](https://agilemanifesto.org/principles.html), 4 themes

- **Value Delivery**
    - highest priority? customer
    - delivery frequently (shorter timeframes better than longer ones)
    - progress measured by working SW
    - simplicity - what matters most
    - continuous attention to technical excellence and good design
    - **deliver quickly, mitigate risk, get feedback**

- **Business Collaboration**
    - welcome changing requirements
        - emphasizes collaboration to bring value
    - must work together daily to create business value
    - **help team get info quickly**
    - work near each other, have easy access between business people and devs
    - weekly huddle to explore ideas

- **Team Dynamics and Culture**
    - **create effective team culture by being inclusive, supportive, and empowering**
    - teams need to be motivated and trusted to do the right thing
    - teams must feel that their input is valued

- **Retrospective and Continuous Learning**
    - **reflect on how to become more effective, then adust**
    - always figure out better ways to work
    - how is the team?
    - is the customer happy?
    - are we following values?
    - are we accumulating (technical) debt?

### VUCA

- defines conditions that can affect organizations

Volatility - rate of change and churn, seems like things never settle into a normal rhythm

Uncertainty - lack of predictability

Complexity - high number of things that would affect a project

Ambiguity - possibility of misunderstanding

## Popular Agile Frameworks

### Scrum

- based on rugby
    - a group of players have their heads together and down
    - work together to move ball down the field

- terms
    - daily scrum
        - 15 min
        - inspect progress
    - product backlog
        - central artifact
        - contains all possible ideas, deliverables, features, tasks
        - prioritized and managed continuously
    - sprint
        - time-boxed iterations, typically 2 weeks long

- roles
    - scrum master
        - ensure agile values/principles are followed
    - development team
    - product owner

- size: 3-9 members, enough to share a large pizza
- not just applicable to software

### Kanban

- from Japanese kan (sign) and ban (board)
- provides transparent visual feedback
- split up to To Do - In Progress - Done
- accept only a sustainable amount of IP work (Work-in-progress - WIP - Limit)
    - WIP limit decided on by team
- focus on less work to get it done faster

### XP (Extreme Programming)

- aims to improve product quality
- relies on TDD
    - test more and smaller features
- activities
    - designing
        - KISS (keep it stupidly simple)
        - small designs are easier to complete
    - coding
        - aim for clear and concise code
            - easier to troubleshoot
    - testing
        - MORE TESTING!!!
        - eliminate flaws before moving on
    - listening
        - to the customer!
        - ensure requirements are met
- practices
    - pair programming
    - continuous integration and continuous refactoring
    - avoid big design up front
    - write tests, not requirements

### Lean

- based on the context of Lean 6 Sigma
- principles
    - define value
        - identify and focus on customers
    - map value stream
        - map out steps
    - create flow
    - establish pull
    - pursue perfection

### The Spotify Model

- organized as follows:
    - squads
        - like a scrum team
        - feels like its own startup company
        - work together for a long-term mission
        - no formal leader, but has a product owner
    - tribes
        - group of squads that work in a specific area
        - less than 100 people total
    - chapters
        - small group of people (someone from each squad) within a tribe
        - people with similar skills and work in the same general competency area
    - guilds
        - group of people from across tribes
        - share knowledge, tools, code, and practices
