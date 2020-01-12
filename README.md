# Project of the year

A board game for programmers

*The project manager has quit.
The heavy responsibility falls on you to deliver "the project of the year".
The top management is counting on _you_,
because, frankly, they got nobody else to get this done.*

---

(=) The symbol `(=)` marks sentences and sections as "secret" notes for game masters.
Do not read them out loud to players, let them discover on their own, through playing.

---

(=) Alternative back story, not used for this game.

*Your time has finally come. You have found the genius idea you were looking for all your life.
You quit your job to have the time to make it happen, and you have the funding to do it.
You start alone, so no politics and project managers can get in your way this time.
This time, everything will be different. This time, you can do it right.*

## Game overview

Players (ideally played by programmers) take on the (reluctant) role of managers.
Their goal is to build "the project of the year" before another competitor does it,
or before the 12 rounds run out.

To make this happen, you will need to gather a team of programmers and deliver features,
while battling with technical debt, accumulating bugs, and pointy haired bosses.

In each round players take an action, implement new features or fix bugs,
and face some event.

(=) *"No need to explain more at this point, you know how this all works!"*

---

(=) Many details of the game should not be explained to the players,
but left up for discovery. For example, what exactly is "the project of the year",
and what exactly it means that "it is built", are intentionally undefined.
This is an ironic reference to reality, and the game tries to pack as many of those as possible.

## Components

A. Programmer tokens. During a live session, it's better to use real physical programmers,
   instead of tokens, recruited from the audience during the course of the game.

B. Intern tokens. Like programmers, best to recruite from the audience.

C. Productiviy tokens. Programmers and interns have productivity,
   which an be used to implement features and squash bugs.

D. Sanity tokens. Programmers and interns have sanity,
   which helps them do their jobs.

E. Feature tokens. Features are implemented by programmers and interns,
   and increase the value of the product.

F. Bug tokens. Bugs are created by programmers and interns,
   and decrease the value of the product.

G. Event deck. In each round some (unfortunate) event occurs to each player.

H. Training cards.
   (=) Training increases the sanity of programmers and interns.
   The front of the card tells only the name, such as "unit testing",
   the effect is described on the backside, and remains hidden until the card is taken as an action.
   Taking the same training card again will have no additional effect.
   All training cards are available to all players.

I. Starting player token.

## Setup

### Receive starting elements

Each player chooses a starting programmer and a target product to build.

Programmer archetypes:

- Neckbeard
- FGITW (fastest gun in the west)
- BOFH (bastard operator from hell)
- ...

(=) This "choice" is just for fun. All archetypes are the same.
*They are all highly productive but dirty programmers*,
designed to cause more problems than they solve.

Target products: (WIP)

- ...
- TODO: see Code Complete section 3.2 for product type ideas

(=) Again, the target product "choice" can be just for fun, for now.
Find choices that make programmers smile.
Later they could affect the gameplay.

The programmer starts with 5 productivity tokens and no skills.

## Goal of the game

Develop a star team to build "the project of the year" before another competitor does it,
or before the 12 rounds run out.

## Playing the game

There are 12 rounds to play.

Each round consists of 3 phases:

A. Action phase: take one of the possible actions

B. Production phase: programmers and interns implement new features and/or fix bugs

C. Event phase: some event happens

In each phase, the starting player acts first, followed by next player in clockwise order.

When a phase is completed by all players, they do the next phase.

At the end of the round, the starting player passes the starting player token
to the next player in clockwise order.

### Actions

- Hire and fire: hire one programmer or two interns. Fire any number of programmers or interns.
  (=) Only half of the players (rounded up) can hire a programmer, because the job market is not so big.

- Get a training: choose a training card. Flip the card to read and apply its effects.

- Deliver undelivered features

- ...

## Underlying notions

Some ideas to be revealed by playing, for learning or amusement about the way software development and project management works.

SonarSource mantra:

- Fix the leak: It's better to prevent new problems from arising than fixing existing quality issues.

- Baby steps: It's better grow feature incrementally

- Never develop purely technical work with no marketable value

- Choose your battles

- Less is more, KISS

- Using a quality management tool is a net positive without a shadow of a doubt.

- It's crucial to work on the right problem (and to find out what it is really)

Other ideas:

- Trainees reduce the productivity of their mentors, while the mentors solidify their knowledge.

- Trainees left unchecked may wreak havoc later ("reckoning")

- Some rock star developers are highly productive but not good team players

- Some rock star developers are good at raising the level around them, but not very productive

- Changing a tool (or anything) may increase productivity in the long run at some initial cost

- Software upgrades may have an increased cost as well as risk

- New features may bring new bugs too

- Community backlash may be unpleasant but harmless

- Adding more people on a project does not increase productivity linearly (diminishing returns, communication overhead)

- Write-only code is unmaintainable

- Certain practices are always net positive virtually without bounds: code reviews, unit tests, coding standards

- Technical debt has similarities with real-life debt

- The requirements for any project may be difficult to grasp, and take a lot of work to clarify

- A waterfall-style development is likely to result in something that cannot be extended

- Certain designs may make a very likely extension easy to do, or extremely hard to do

- If the requirements are not well understood, the developers may completely miss the target

- Discovering the real requirements may be a fun sub-plot adventure on its own

- How does a well-engineered code base decay after it's abandoned?

- Broken windows principle: unsolved problems draw more problems

## [Mechanics](https://boardgamegeek.com/browse/boardgamemechanic)

Possibly mechanics to include, combine.

- Action points: decide the allocation of resources to tasks
- Card drafting: decide the best action from an available set
- Critical hits and failures: ex: the trainee project may bring new insight or be a complete loss
- Hand management: in case of card game, but preferably not...
- Income: ... budget? time? (action points)
- Market: of available programmer archetypes for hire
- Solo mode: for testing?
- Sudden Death Ending: when the project is done (= all requirements complete), the game ends immediately
- Worker placement ~ action points
- Automatic resource growth: time? bugs? skills? experience?
- Campaign: extending the project, or maintaining the project
- Chaining: ...
- Events: reckoning!
- Increase value of unchosen resources: increase risk of unattended bugs
- Prisoner's Dilemma: ...
- Time Track: increasing pressure
- Variable Player Powers: one manager may inspire its workers, another may get more funding
- Victory points as a resource: completed features

Requirements to complete for project of the year?

- Variable: select k cards from n
- Variable: let players lobby for k cards from n
- Variable: let requirements be fuzzy in the beginning, and emerge during the game
- Requirements ideas: see Code Complete, 3.1 What Kind of Software...?
  - business system, mission-critical system, embedded life-critical system
  - different planning, management, and design is appropriate
