# Project of the year

A board game for programmers

*The project manager has quit.
The heavy responsibility falls on you to deliver "the project of the year".
The top management is counting on _you_,
because, frankly, they got nobody else to get this done.*

---

(=) Th symbol `(=)` marks sentences and sections as "secret" notes for game masters.
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

## Object of the game

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
