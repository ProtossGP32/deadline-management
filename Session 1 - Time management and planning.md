# Time management and planning

Trainer: Marc Ambit Fernández
Mail: marcambit@gmail.com

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

#### Applicable graphic techniques

- Gantt
- PERT / CPM

#### Duration estimation (bottom-up, parametric, historical, PERT weighting, etc.)

- Duration estimation is different from work estimation!

##### Contingency margin

- This is a defense mechanism, it really doesn't work.
- Risk estimation is already included in duration estimation

### Planning #3: Tools and techniques to improve efficiency

#### Efficient planning techniques

- Worries / Time chart
  - We end up wasting time in the end of the project with non-planned tasks and worries.
  - We are looking for a more plain project course.

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

#### Techniques for delivering time before the delivery date

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

<!-- IMAGES -->
[project-chronology]: /images/project_chronology.png