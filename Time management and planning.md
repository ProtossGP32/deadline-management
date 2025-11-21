# Time management and planning

Trainers: 
- Project management:
  - Trainer: Marc Ambit Fernández
  - Mail: marcambit@gmail.com
- Time management skills:
  - Trainer: Lourdes López Barbosa
  - Mail: lourdes.

## Goals

- Train students to use a set of planning tools and techniques that allow them to organize themselves better as well as improve their efficiency.
- Learn clear guidelines to organize our day in a more efficient way.
- Apply a results-focused methodology.

## Resources
Shared folder: [LINK](https://bit.ly/pmsharedfolder)

## Contents

### Planning #1: Inefficiency in our jobs

#### Possible consequences of poor planning

- Why plan at all?

  > _"A goal without a plan is only a wish."_
  > 
  > Antoine de Saint Éxupéry

#### Acquire the planning mindset

-  How do we categorize our tasks?

   - Define priorities
   - Make to-do lists
   - Tasks representations through Gantt charts

#### The basics of good planning

- Order
- Information and documentation
- Communication
- Historical experience

### Planning #2: Tools and techniques for creating a schedule

1. Define tasks
2. Task sequencing: trying to find tasks dependencies
   > These two steps should be immutable during the whole project!
3. Assign resources: Knowing the tasks allows to know how many resources (people, machinery, etc...).
   1. Budget will be a consequence of this.
4. Duration estimation: given the assigned resources we can know the limits of our project time requirements.
5. Chronogram: it is necessary to see the plan and be able to understand it.
6. Improve plan: using chronogram as the base, we can find where to improve steps

#### Chronology of planning

- How do we plan our project?

  https://bit.ly/chronoproject
  
  ![Project chronology][project-chronology]

  ```mermaid
  graph TB
    CI[Collect Info]
    A[Analysis]
    DP[Design Proposal]
    SPB[Simple Plan and Budget]
    PD[Project Draft]
    DPB[Detailed Plan and Budget]
    ET[Execute Tasks]
    M[Monitoring]
    RP[Re-Plan]
    E[Evaluation]

    CI --> A --> DP --> SPB --> PD --> DPB --> ET --> M --> RP --> E
  ```

- Mistakes in a project
  - In which part of a project is it worse to make mistakes?

#### How to cover a large project (Work Breakdown Structure)

- Defining tasks
  - How do we define tasks?
    - Break down requirements into feasable tasks
    - Detailed planning: division of a project
      - Project divided into subprojects.. 
        - ... Then into phases
          - ... and these into tasks that define with enough detail the work to be done in order to attain the goals.
      - **Work Breakdown Structure (WBS):** try to break down things
        - If we forget to go deeper on complex tasks is not going to be included on the plan...
        - Then it wont be done and will be improvised in the execution stage...
        - And consequences will be less scope covered, more time and more costs.
        - Here we still don't take into account dependencies between projects.
    - 2 methods to deal with uncertainty:
      - Waterfall methodology: whole project planned since the beginning. Hard to deal with uncertainty.
      - Agile methodology: small iterations and re-evaluating to plan again. Easier to deal with uncertainty.

- WBS example
  - Music bar: Question
    - What do we have to do to open a music bar?
    - Initial idea of tasks:
      - Previous procedures
      - Bar works: deliverables, etc.
        - Design
        - Work permits
        - Works and Decorations
          - Reception area
          - Public
      - Staff
        - Profile definition
        - Ad publishing
        - Personal interviews
        - Final selection
      - Etc.
    - Some tasks might be better outsourced, but what about the rest? 
    - Three things to have very clear when dividing project and knowing when and where to stop:
      - Time
      - Resources
      - Scope of the task

#### Sequencing tasks (Network Diagram)

> :warning: Not explained?

#### Applicable graphic techniques

- Gantt
- PERT / CPM

#### Duration estimation (bottom-up, parametric, historical, PERT weighting, etc.)

- Duration estimation is different from work estimation!

- Duration = Work + Margin
  - Work: Time to do the task
  - Margin: Time to do other things and be able to insert the taskin the schedule
    - Margin is the hardest part to calculate and what makes the planning of a task fail
- Inability to properly estimate work!
  - We are trained to work asynchronously, so we always think there'll always be time to do tasks at any time

##### Contingency margin

> :information_source: It should be included to accomodate **identified risks**, not to compensate for a lack of planning skills

- This is a defense mechanism, it really doesn't work.
- Risk estimation is already included in duration estimation

> :information_source: **Hint:** when planning, assign 80% of availability to all your resources, this way you have a 20% of resource to accomodate them for uncertainty or unforeseen events.
> - For each possible unforeseeable event or context switching a resource might be exposed to, reduce the maximum availability of that resource a little bit more.
> - Think about the busiest time of the year and define max resources accordingly.

- Example: try to define work and margin times for the following tasks:
  - TASK 1: "Write a list of your 10 all time favourite movies"
    - Work time: 1 hour
    - Margin: 1 day?
  - TASK 2: "Organize a birthday party for one of your teammates"
    - Work time: ??
    - Margin: ??

The most important thing to take into account is **commitment**! Without it, we can't ensure the task will be done.

Bad way to plan:
- Go for the big picture
- Break down into details

It's the other way around!
- Go for defining details
- Then go for the whole picture

> :information_source: **8-80 RULE:** Try to deliver the task between 1 day (8 hours) and 10 days (80 hours, 2 weeks).
> - If a task is longer than this, then start splitting it! [WBS](#how-to-cover-a-large-project-work-breakdown-structure)
> - **You need the feeling that at the end of the day, you've completed some tasks!**
> - Using the 8-80 rule doesn't mean you can't fit multiple tasks in one single day, as long as (work + margin) sum of all of them fit in the 

##### Historic experience

Two kinds of historic experience:
- **Technical:** the more you work on a particular type of work, the faster you should be able to do it and you'd be better at estimating the time it will take
- **Context:** knowing the kind of environment you'll be working in allows you to better dimension the time it will take to execute tasks (interruptions, noisy environment, etc...)

> :warning: **HOW TO DEAL WITH INTERRUPTIONS IN ONLINE MEETINGS?**
> People aggressively interrupting while you're speaking, use diplomacy:
> - Be polite but firm, setting meeting guidelines at the beginning of it and remind them to the interrupting people

##### Setting the scope

Example task: _Arrange the classrom properly, to get ready for the next training._

- If the task is not properly specified, you have to improvise and then results won't match the client's expectations.

> :information_source: **Definition of Done (DoD)**
>
> This includes all the requirements of a task that must be self-evaluated, and once all are completed we can consider the task as **DONE**.

##### Delegation

From full to none:
- Full delegation
- Decide, act and report
- We decide together
- Decide, I give the OK, and act
- Do it more or less like this
- Do it like this (micro-management)

##### Responsibles

> :warning: Every level of multitasking added to ourselves, we lose 1/3 of our efficiency

**Ask yourself:** what's the level of multitasking you're comfortable with? How many tasks at the same time and what type?

- The length of your acceptable pending/in progress task list should be short!
- Task complexity must also be taken into account. Try to estimate task complexity to combine them more efficiently

> :information_source: All your tasks lists should have assigned a limit of some kind (complexity, time, resources, etc...) so you don't overburden them and put them elsewhere (next week list, for example).

**Wired article:**
- Most of the tasks put on a list are done in 5 minutes and then marked as completed immediately.
- Only the three top-most tasks are the ones progressing; the rest tend to stall

> :warning: **More multitasking means more disruptions!**

Tasks must be splitted into smaller tasks to avoid _marrones_.
- The bigger the task is, the less probable to work on it.
- When splitting it, don't overwhelm people with it! It would be the same as the big task.

### Planning #3: Tools and techniques to improve efficiency

#### Efficient planning techniques

- Worries / Time chart
  - We end up wasting time in the end of the project with non-planned tasks and worries.
  - We are looking for a more plain project course.

- Example: how not to be late to a critical appointment?
  - Some actions to do:
    - Get up sooner
    - Shorten time dedicated to usual tasks
    - Change transportation means
  - This doesn't really work, because **any new change to a well known and tested plan will introduce uncertainty**!
  - Longer duration doesn't ensure safer delivery!
    - Longer duration leads to relaxation
  - Shorter duration doesn't ensure faster delivery!
    - Shorter duration leads to rushed executions and makes things worse

> :information_source: **INTERMEDIATE DEADLINES ARE AS IMPORTANT AS THE FINAL DEADLINE!!**

#### How to be efficient by planning

##### Critical path

- Tasks that will delay the project's deadline.
- What do we do with the critical plan? What's going to change?
  - Put more resources if short on time,
  - Prioritize better the tasks,
  - Marta's technique to avoid problems: granularizing task (split long tasks onto little ones)
    - An 11-day task might be too long
  - Monitor more intensively the critical tasks.
    - Careful with micro-managing it!!
  - Negotiate priorities on other tasks

##### Risk management

Identify tasks with:
- Zero experience
- Risk time and cost estimations
- No substitute resources
- Multiple predecessors
- Long duration: _marrones_

Any combination of the previous tasks is a risk!

Quantify the risk:
- Probability: How probable it is to affect the plan?
- Impact: What's the scope of its impact?
- Trigger: combination of probability and impact, what wil make it happen

Soften the risk:
- Dissipate
- Compensate
- Alternative plan

Control the risk:
- ???

Risk matrix:
- Columns
  - Risk
  - Category
  - Description
  - Probability (1-3)
  - Impact (1-3)
  - Risk Level (P x I)
  - Classification (High, Medium, Low)

Example of risk management:
- Organize an open house event at BSC

Solution before, during and after the plan execution:
- Don't try to improvise!! This should be the last resource
- Dissipation: soften the execution of the tasks to reduce the impact if something goes wrong.

#### Techniques for delivering before the delivery date

- Be safe and realistic in times' tasks:
  - Ask for realistic time windows and dates (next Monday, etc...)
  - Ask again, remind them after some days to feel the pressure
  - Be clear with dates and priorities
- Negotiation:
  - What are the work priorities for every team member?
  - If given enough authority and if needed, jump to bosses to manage task priorities of some members
  - Try to make it as safe as possible
- Have always uncertainty into account:
  - What are the busiest month of the year? And the busiest weeks of those months?
  - Don't rush things, again make it safe
- Contingency:
  - Careful with overspending!! Knowing the risks allows you to better dimension your needs.

#### Planning methodologies

##### Predictive method (classic way)
- We work in a linear way and don't have margin of correction

##### Agile planning
- Iterative process, we can plan, execute and test it quickly, and when analysing it we can change things through feedback and start again.

##### What to choose?
- Predictive:
  - Scenario: complicated
  - Necessity: analise, understand, control
  - Example: ???

- Agile:
  - Scenario: complex, vuca(?)
  - Necessity: experiment, perceive, adapt
  - Example: City traffic lights, too complex to properly regulate traffic jams
  - The only way to solve things is trial-and-error

#### Techniques to get cheaper projects

##### Project triangle
- Time
- Resources
- Scope

These define the quality of the project. Changing any of these, the other two must adapt:

- (+) Scope --> More resources or more time
- (-) Time --> More resources and/or less scope
- (-) Resources --> More time and less scope

##### We do projects, not magic
Clients ask for:

- Fast
- Cheap
- Good

Looking for any combination leads to:

- Fast + Cheap --> Badly done
- Fast + Good --> Expensive
- Cheap + Good --> Slow
- Fast + Cheap + Good --> Magic!

We can't deliver all of them!

#### Reduction of bottlenecks

##### Theory of Constraints (TOC)

- Theory: a chain breaks from the weakest link.
- Applied to planning:
  - We have to find the most demanding task
  - Maximize the task:
    - Put as many resources as you can
  - Balance the plan:
    - The problem is that we have a bottleneck in a task
    - Granularize / split into smaller, less complicated pieces
  - Objective: make the plan execution as steady as possible
- Example: traffic jam
  - Cars trying to change lanes create bottlenecks, making the transit less steady and creating peaks and valleys

### Planning #4: Computer software for planning

#### Paid programs

- Primavera
- MS Project

#### Free programs

- Project Libre
- OpenProject

#### Other available software

- Trello
- Slack
- Asana

#### Basic introduction to the use of the tools

- Introduction of complete schedules (tasks, durations, resources, dependencies, etc.)
- Information extraction and analysis of schedules
- Improving efficiency with computer tools

### Planning #5: Planning improvement workshop

#### Individual work on one's own plan

- Applying the tools, techniques and methods included in the sessions

#### Overwork exercise

Techniques:
- Exercise 1 - Postponing: not a problem if task isn't included in the critical path
  ```mermaid
  gantt
    title Postponing tasks
    dateFormat YYYY-MM-DD
    todayMarker off

    section Overwork
    Task 1.1  :a1, 2025-11-12, 5d
    Task 1.2  :a1, 2025-11-12, 5d

    section Postpone
    Task 1.1  :a1, 2025-11-12, 5d
    Task 1.2  :after a1, 5d
  ```

- Exercise 2 - Combining: split day in two and work on both tasks every day. Careful with context switching!
  ```mermaid
  gantt
    title Combining tasks, both tasks must start on the same day
    dateFormat YYYY-MM-DD
    todayMarker off
    
    section Overwork
    Task 2.1  :a1, 2025-11-12, 5d
    Task 2.2  :a1, 2025-11-12, 5d

    section Combining
    Task 2.1 (Half day) :a1, 2025-11-12, 1d
    Task 2.1 (Full day) :a2, after a1, 4d
    Task 2.1 (Half day) :after a2, 1d

    Task 2.2 (Half day) :a4, 2025-11-12, 1d
    Task 2.2 (Half day) :a5, after a2, 1d
    Task 2.2 (Full day) :a6, after a5, 4d
  ```

- Exercise 3 - Dividing: useful when you have immovable tasks
  ```mermaid
  gantt
    title Dividing tasks, when you have immovable ones
    dateFormat YYYY-MM-DD
    todayMarker off
    
    section Overwork
    Task 3.1  :a1, 2025-11-12, 3d
    Task 3.2  :a2, after a1, 4d
    Task 3.3  :a3, 2025-11-13, 1d

    section Dividing
    Task 3.1  :b1, 2025-11-12, 1d
    Task 3.1  :b2, after b4, 2d
    Task 3.2  :b3, after b2, 4d
    Task 3.3  :b4, 2025-11-13, 1d
  ```
- Exercise 4 - Parallelizing and crushing: when having enough resources, execute tasks at the same time; effort-driven tasks allow to assign more resources to reduce time
  - Review v2.0, it might be wrong
  ```mermaid
  gantt
    title Parallelizing and Crushing, with 2 resources available with same skills
    dateFormat YYYY-MM-DD
    todayMarker off
    
    section Overwork
    Task 4.1 - A :a1, 2025-11-12, 4d
    Task 4.2 - B :a2, after a1, 1d
    Task 4.3 - A :a3, 2025-11-12, 2d
    Task 4.4 - B :a4, after a3, 3d
    Task 4.5 - B :a5, after a1, 4d

    section Crush + Parallel
    Task 4.1 - A :b1, 2025-11-12, 4d
    Task 4.2 - B :b2, after b4, 1d
    Task 4.3 - B :b3, 2025-11-12, 2d
    Task 4.4 - B :b4, after b3, 3d
    Task 4.5 - A :b5, after b1, 4d

    section Cr + P v2.0
    Task 4.1 - A+B  :c1, 2025-11-12, 2d
    Task 4.2 - A    :c2, after c1, 1d
    Task 4.3 - B    :c3, after c1, 2d
    Task 4.4 - A+B  :c4, after c3, 2d
    Task 4.5 - A+B  :c5, after c4, 2d
  ```


### Time management and self-efficacy #1
#### Goals
- Raise conciousness about how we manage our time and what we can do differently to:
  - Live our day to day witgh less stress
  - Gain effectiveness with the same resources
- Identify what behaviours/attitudes kae us less efficient when it comes to managing your time

#### Exercise
- To-Do list:
  - Read mails: DONE
  - Read Slack messages: DONE
  - Check project's infrastructure status: PENDING
  - Check internal infrastructure status: PENDING
  - Check CI/CD status: PENDING
  - Video editing: PENDING
  - Work on internal platform deployment: PENDING
  - Work on woffu-client: PENDING

#### Can we manage time?
> :information_source: Time can't be managed! We manage what we do with time (taks, life, events, etc...)

Every day we have 1440 minutes:
- How many of them do we give away?
- ... do we throuw away?
- ... are stolen from us?
- ... do we let others steal from us?

> :warning: **I HAVE NO TIME**: that's a false statement. We dedicate time to something else or don't put enough time to that particular task.

Two main points:
1. Being busy is not the same as being **effective**
2. Shift focus from activities to **results**

When feeling that we're not in control fo what

##### Work smarter, not harder

We need to switch off the "Auto-pilot", start making decisions conciously:
- Be conscious when you interrupt your focus on your work to answer a colleague's question
- Be conscious when you decide not to answer anyone when you've stated your indisponibility in your communication channels

You have to weigth the cost of these decisions.

##### Myth of activism
> :warning: __"Being busy is not the same as being effective"__

We have to reflect on what that task that is keeping us busy is leading us:
- This task is preventing us to think about other things
- We can analyse how the task is being done to improve it and make us less busy

##### Myth of control
> :warning: __"If you want things to happen, do it yourself"__

Bad sentencies:
- _It takes me less time to do it myself than explaining it to you_
- _If others do things instead of me, they won't do it the way I want_

This doesn't help the team to develop and grow, they will always depend on you.

We need to **deletage**, small steps to let things go. Accept that not everything has to be done your way or results you like.

##### Myth of information
> :warning: __"Without information, we cannot decide."__

We can move forward in our tasks without having to wait for other's input or data. Just put placeholders for these pending data.

Don't wait for the perfect, ideal situation for us to keep working. It's better to have something done than nothing at all.

##### Myth of workload

> :warning: **The results we obtain are directly proportional to the amount of time we dedicate to the task.**

That's not true:
- Quality time: investing time improving processes can save us time in the future and avoid repeating the same monotonous tasks. A small task can lead to better quality time in the long term.
- Being conscious of how effective we are being with a task: we shall know when to pause from that task and do something different, and getting back to it (i.e: _am I using my time well?_).
- Creative tasks and time: 
- Having long To-Do lists can make you anxious and block us from doing any task:

##### Myth of urgency

> :warning: **The unexpected needs to be resolved immediately**

When something unexpected happens, we emotionally react and focus all our attention to it.

We need to go the other way around:
- Analyse it
- Decide the priority of this unexpected issue compared to your own tasks

What's the meaning of urgency for everyone?
- We're managing emotions, and that's very contagious
- Everybody rushes when not understanding the importance of that crisis
- This doesn't mean we have to stop our tasks to reduce nervousness of the rest of the people

##### Myth of the open door

> :warning: **We must be always available for everybody.**

False! What we need to do is **negotiate** with the other people on your needs and theirs:
- Concious decision
- Give options
- Help people: yes, attending people: yes, but not always because constant interruption of your work is bad for you
- 95% of people can wait.

#### Time wasters

> :information_source: **_"The main time waster is our own mind."_**

##### Internal wasters:
These come from our own minds. 

- Unclear or undefined goals:
  - The worst use of time is to do very well things that aren't that relevant or are unnecessary. 
  - Don't lose sight of the **goal**!
  - We usually mistake **tasks** with **goals**
  - We need to understand if **tasks** are that critical
    - I.e: _Coordinating_ is a **tasks**, not a **goal**
    - We might be able to find other tasks or ways to do things that leads us equally to the final goal
  - **Pareto's principle:** 20% effort leads to 80% results
  - Quality decisions, not quantity!
  - What things make sense to do today and what don't?
    - What are the critical ones?
    - What are not required now?
  - Stating daily goals help us being less exposed on divert too much from them.
    - We can clearly delay other's requests without doubts.
  - Exercise: decide your "_super-objective of the day_":
    - **Marc:** finish video editing so it doesn't chase you afterwards
  - Short-term requests with a quick time reaction make us act only reactively; this affects negatively on your performance
    - We need to find ways to balance them with our priorities and tasks, like delegating whenever we can
    - **This can't be the norm!** When we plan, we need to plan realistically
    - Not all the time of the day is ours, we need to be aware of this to ancticipate unforeseen things
    - **A To-Do list is not a Planning list!**
      - A To-Do list is a living list without priorities
- Procrastination:
  - TBD
- Multitasking habits:
  - TBD
- Not able to say NO:
  - TBD
- Lack of motivation:
  - TBD
- Precarious planning:
  - Bad planning is counterproductive
    > :information_source: 10% of planning save 90% of execution time!
  - Planning gives you clarity of mind when executing tasks, then it's very clear what's your path and how to deal with the rest of tasks
    > :information_source: **_"Focus on what you want your day to become"_**
  - How to improve your planning:
    - Start by assuming that **you don't have 8 hours a day for you**!
    - Organize your tasks based on your available time slots (1 hour, 2 hours, 30 minutes...) on each day (Monday, Tuesday, Thursday, etc...)
    - Account for the probability of interruptions on each time slot and see if your tasks fit on them
    - In the end, **each day might have assigned 1 or 2 realistic tasks**
    > :warning: **TODO: Add a picture of a day timetable split into available time slots** 
    - We'll be able to **negotiate** the really critical need of external interruptions
    - Also take into account your own energy levels during the day: see what levels of energy do your tasks need and what's the best moment of the day to tacke them
    - **USE AN AGENDA!!** The idea is to put things you've made the decision to do (conciousness)
    - At the end of the day, make a To-Do list for the next day
      - This clears your mind for the rest of the day. Since it's already organized, you don't have to think about it anymore
    - Spend the last hour of the week planning the next week
      - Decide what should be done next week, trying to think when it would be the best time slots; this also helps negotiating tasks with others
    - The more visibility you give others of yourself, the better time management others and you will have.
      > :information_source: **Be concise and specific about the expected timings of your demands to others so they can fit it into their own agenda!**

      This avoids others stressing out and pressing you without any need. Calls and interruptions that take you and others time.
      - Example: mail with ASAP in it
        - Option 1: don't tackle it. The sender will keep pushing you if no news are sent
        - Option 2: ask for concrete times. Make it visible for the sender when you'll be available for that task (i.e: _The sooner I can have it is next Thursday_)
    - Point out completed tasks
      - It gives you sense of control, dopamine and time management skill gain
    - Prioritize task orders:
      > :information_source: _There's never enough time to do everything, but there's always enough time to do **the most important thing.**_
      - Exercise: do an estimation of the duration of your tasks:
        - Mail reading: 15 minutes
        - Replying mails: 30 minutes
        - Read Slack messages: 10 minutes
        - Check project's infrastructure status: 30 minutes
        - Solve project's infrastructure issues: 1 hour and a half
        - Check internal infrastructure status: 30 minutes
        - Solve project's infrastructure issues: 1 hour and a half
        - Check CI/CD status: 10 minutes
        - Solve CI/CD issues: 1 hour
        - Video editing: 4 hours
        - Work on internal development platform: 2 hours
        - Work on woffu-client: 1 hour
        - **TOTAL:** X hours
      - Use the **Eisenhoure matrix** to set priorities to tasks and how to cope with them:
        > :warning: **TODO: Attach an image of the Eisenhower matrix** 
        - :red_square: Do (Important + Urgent) --> **Fire fighting**
          - Crises
          - Pressing prolemes
          - Projectws with deadlines
          > Analyze first, act now
        - :green_square: Decide (schedule) (Important + Not Urgent) --> **Quality time**
          - Productive activities
          - Capability improvement
          - Relationship building
          - Recognizing opportunities
          - Planning, recreation
          > Take your time planning them and find the exact moment to do it
        - :blue_square: Delegate (Not important + Urgent) --> **Distraction**
          - Interruptions
          - Some email, some reports
          - Some meetings
          - Proximate, pressing matters
          - Popular activities
          > Decide if you dedicate your time to this or delegate them.
          >
          > **Two-minutes rule:** if it can be done in that amount of time, do it; else, delegate.
          >
          > **Isolate tasks:** Determine communication channels based on urgency and be pedagogical with your team members about this; let them know so they respect your time.
          >
          > Example: urgent things --> Call. Not urgent things --> Mail. Decide with what periodicity should you check those based on their urgency level.
        - :orange_square: Delete (Not important + Not urgent) --> **Time wasting**
          - Trivia
          - Some email
          - Some phone calls
          - Time wasters
          - Pleasant activities
          > Don't do them
        > :information_source: **DEFINITION OF URGENT TASK:** concious decision of what's the best time to tacke a job thinking on the time you need to do a good job within its deadline.
        >
        > :information_source: **DEFINITION OF IMPORTANT TASK:** awareness of criticallity of tasks that either block other tasks or are mandatory for the project's goal or improve productivity.
- Project leaders/Team leaders, etc... must define guidelines, ensure punctuality, set limits, and make people accountable for not following the rules all the team agreed on, and that this has consequences.
  - Be strict when rules aren't abided by.
- If the company doesn't have any kind of protocol for leading projects and tasks, then **do it yourself and try to set some standard.**

##### External wasters:
- Unproductive meetings, interruptions

#### Wrapping up

- Setting objectives
- Planning
- Prioritizing tasks --> Being aware of the criteria, the important things (_super-objective of the day_)
- Programming, scheduling --> When things make sense to happen in terms of time slots, similar tasks, more efficient, same brain activity tasks, etc...
  - How can we improve time assestment of tasks? By experience.
    > :information_source: **"TIME BOXING" TECHNIQUE:** Make a guess about how much time a task takes; then make the task and compare the real time with the estimation and learn from it for future plans. This makes us better and better at estimating time.
    >
    > This also helps discovering what tasks that are cumbersome for us might be the quickest ones to complete and better plan after that.
- Protect your plan by setting limits --> Learn to say 'No' and do pedagogy about this, so others understand everybody's time usage.
  - Learn when there are better ways to do things, like meetings that might be done through mails.
  - Learn how to **set time limits between meetings** in order to organize your notes and ideas before tackling a different issue.
  - Explain others when is the best moment for you to address others' issues.
  - **Give options to other people** so they can choose if you're not available:
    - _I have this --> I offer you this_
  - Minimum unit to protect --> Task
- **Avoid multitasking!** Isolate yourself during your task
  - Example: put the phone in your drawer, silence any notifications, etc... You decide when you go look at them
  > :information_source: **"POMODORO" TECHNIQUE:** Set yourself time slots where you solely focus on that job in order to have it DONE.
  >
  > Protocols can also be set to find time windows for helping others.
- **Be always aware that you take conscious decisions!**
- Procrastination: leaving things undone for tomorrow is not procrastination, is precarious planning!
  - Procrastination is dragging a task during a long time without doing it, and ask yourself if this really needs to be done
  > :information_source: **"CHEESE" TECHNIQUE:** Instead of addressing the whole task, just _take a bite_ of it. Program some time to ask others about their experience about these kind of tasks (and this is a task itself).
  >
  > It is demonstrated that 50% of the time is destined to do the first step. Make it easier for you to make this first step or, always. The brain only changes by repetition, doing feasible things and repeating it. Ensure persistence and eliminate obstacles.



#### Initial points of the session

- Beliefs associated to time management that make us being less efficient
- The thieves of time - identify and fight them
- Self-assessment of the main habits that prevent us from being effective
- The importance of setting goals
- Good planning - the secret of success
- Importance versus urgency
- Criteria to establish priorities
- Organization of our agenda - "Timeboxing" technique
- Fight the "multitasking" - "Pomodoro" technique
- When e-mail is an "enemy" - some tips to fight accumulation
- How to manage interruptions
- Set limits - Learn to say 'no'
- How to optimize time of meetings
- Coping with procrastination

#### Bibliography

- _Atomic habits_

---
---

# Extra stuff

## AI on Project Planning

### PM+AI: WBS

- https://bit.ly/iawbsxprojectlibre
- You're the one that knows the project the best.

### Inverted prompting

- Ask AI to ask you questions to do something
  - Questions about the project: look for missing points in the project not covered yet.

## ProjectLibre tips

### Changing project's schedule type

- Project information --> General:
  - Forward scheduled: this allows to plan by defining the start of the project

### Define available resources

- Resources tab: define new resources (workers or material) on each row
  - Type: used to calculate costs
    - Work: cost by work hour
    - Material: cost by unit (meters, items, etc...)
  - Max. units (%): only applicable to Work type, percentage of work-day availablility of a person

### Reports

- Reports tab:
  - Task information --> Columns:
    - Cost: it acts as a budget report

### Exploring available views

- View tab --> Gantt:
  - Histogram (upper-right icons): shows daily distribution of every resource in a calendar; it helps identifying overwork.
    - You can change the information shown in the calendar by right-click this corner box:
      ![ProjectLibre - Hidden view change box][projectlibre-hidden-view-change-box]

### Tasks

- Indent / outdent: it allows to apply the [WBS](#how-to-cover-a-large-project-work-breakdown-structure) principles to tasks by creating subgroups.
- Intraphase / Extraphase dependencies: you can define different dependency relationships with the predecessor tasks:
  - Naming goes like this: (XY), where X defines the Predecessor condition and Y the dependant task condition
  - Double-click task --> Predecessors --> Type:
    - FS (Finish-Start): Predecessor must finish so current task can start
    - FF (Finish-Finish): Predecessor must finish so current task can finish
    - SF (Start-Finish): Predecessor must start so current task can finish
    - SS (Start-Start): Predecessor must start so current task can start
- Assigning availability of resources on a per-task basis:
  - Double-click task --> Resources tab --> "Assign resources" button:
    - For each available resource, you can define its available _units_ in percentage (green resources are the ones already assigned to the task)
    - Define 80% to account for the task margin; reduce the percentage for each unforeseeable risk that might occur.

<!-- IMAGES -->
[project-chronology]: /images/project_chronology.png
[projectlibre-hidden-view-change-box]: /images/hidden_view_change_box.png