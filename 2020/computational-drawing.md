# Computational Drawing: From foundational exercises to theories of representation

## Acknowledgments 

At RISD, the book was borne out of these courses: *Computing Drawing: Animating the Thick Surface*, *Computing Drawing: Inhabiting Surface*, *Computing Drawing: Similarly Different Lines*, and *Architecture Based on Drawing Buildings*

## Preface

> Computing and drawing have intertwined histories. The first computer art was drawn. Limits on processing power and memory storage precluded pixels and images. Instead, computers were programmed to control machines that moved pens to make marks on paper. Soon thereafter, the trajectories of computing and drawing diverged. **The aim of this book, and the work within it, is to explore the implications of bringing them back together.** (10)

> I think everyone should code, at least a little, and I *know* everyone can do it. However, the best way to learn in any creative field, no matter what type of learner one is, involves a messy integration with an existing creative practice. (11)

In the preface, Lostritto begins with an exercise to fuel an internal discourse:

- List all the reasons you draw
- List all the reasons you write code
- What items are on one list and not the other?
- How would drawing/coding in your practice be different if their roles were more similar?

## Chapter 1: Definitions

### On what is drawing?

> Attempting to clarify any of those definitions [of what drawing is] leads us to Petherbridge's web [of disclaimers]. However, without limits, it's easy to see how almost anything can be a drawing. While Petherbridge proceeds by identifying a drawing continuum, another option is the definitions of drawing not in terms of *what it can be, mean, or do*, but *what it cannot.* (15-16)

1. **A drawing cannot be edited** — Or, more specifically, it cannot be edited down or operated on, only built up ... [it] is a matter of building up rather than editing down ... Once the mark is made, there is no going back (20)
2. **A computer cannot draw** — [It is] neither fully autonomous nor do they meet most of the many definitions of intelligence ... [it is] programmed by humans, which a drawing can be mediated by a computer, but ultimately a drawing is a human activity ... an important key difference between drawings that cannot be reduced to discrete elements and images that is organized by pixels. (25)
3. **A drawing is not final** — All drawings are works in progress ... the ambiguity of a line leaves open the capacity for multiple interpretations. (28)

> Both models and drawings can serve as representations, but while models exist for the purposes of operation, drawing exist for the purposes of perception. (20)

### On a misunderstanding about computing

> Computing is often conflated with the personal computing era ... [however] computing was used in literature as early as 1579, which reinforces the notion that the kind of processing, calculation, procedures, reckoning or reasoning that are normally associated with personal computers need not involve any machines (29) 

### On defining the use of algorithm in computational drawing

While the book focuses on the craft of writing computer code, it is not the programming language (in theory, algorithms are independent of programming language, even computers; in addition, without needing for author/reader to be fluent in the same programming language) that is important, but the *underlying procedures, logic and rules*, which constitute an algorithm. For example, Sol LeWitt wrote hundreds of algorithms for drawings intended for humans to execute with a pen or pencil. [With this in mind] ... gives rise to new kinds of thinking that change and expand what a drawing can be. (32) 

When coding, the actions are called functions (aka "methods" in some languages) = When beginning, what are the fundamental actions necessary to draw?

A scenario:
- A straight mark might take two coordinates, a start point and an point, as input
- Additional input — Its appearance may be affected by its speed at which the mark is made
- Additional input — The mark might be radial in nature (in terms of radii and angular length)
- Additional input — The mark changed by thickness throughout or at certain moments
- Additional input —The mark is governed by goals or patterns rather than reference points

^ Leads to thinking, "What if the library of functions is the work?" (34)