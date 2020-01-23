*Date read - XX 2020*

-----

# Computational Drawing: From foundational exercises to theories of representation - By Carl Lostritto

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

> Computing is often conflated with the personal computing era ... [however] computing was used in literature as early as 1579, which reinforces the notion that the kind of processing, calculation, procedures, reckoning or reasoning that are normally associated with personal computers need *not* involve any machines (29) 

### On defining the use of algorithm in computational drawing

While the book focuses on the craft of writing computer code, it is not the programming language (in theory, algorithms are independent of programming language, even computers; in addition, without needing for author/reader to be fluent in the same programming language) that is important, but the *underlying procedures, logic and rules*, which constitute an algorithm. For example, Sol LeWitt wrote hundreds of algorithms for drawings intended for humans to execute with a pen or pencil. [With this in mind] ... gives rise to new kinds of thinking that change and expand what a drawing can be. (32) 

When coding, the actions are called functions (aka "methods" in some languages) = When beginning, what are the fundamental actions necessary to draw?

A scenario:
- A straight mark might take two coordinates, a start point and an point, as input
- Additional input — Its appearance may be affected by its speed at which the mark is made
- Additional input — The mark might be radial in nature (in terms of radii and angular length)
- Additional input — The mark changed by thickness throughout or at certain moments
- Additional input — The mark is governed by goals or patterns rather than reference points

^ Leads to thinking, "What if the library of functions is the work?" (34)

## Chapter 2: Structures

On the difference between a mark and a line (80)

- Mark is literal, direct and unambiguous in its creation, and is not always registered as a line, no matter how bombastic, trail-like, curvy or straight it is
- Line is what we read into marks, and can exist because of the tension between marks — when our mind connects the dots

> Mentioning that a drawing can be read differently than the code opens the door to analogies with poetry and literature. If literature is used as an analogy, it can be theorized that computational drawing is like a writing a story story (more developed, longer, and immersive than how poetry is often treated) ... [it does] not need to come to a clear conclusion, and not every aspect of the story needs resolution or even explanation ... [keeping the same analogy] using drawing software is not drawing. One can produce a drawing with drawing software in the same way that when reading a choose your own adventure novel one is creating a story. (86)

On four types of line taxonomy (80-115)

1. **The existence taxonomy:** Lines are organized based on whether and how they correspond directly to things that exist materially
2. **The temporal taxonomy:** Lines are distinguished based on their relationship to time, e.g. path lines can trace a record of time, or serve as a one-dimensional temporal space or snapshots of a moving particle
3. **Geometry-material taxonomy:** Lines are categorized based on the relationship between geometry, which is understood to be the reader's mental construct of form or shape, and material, which is defined as the help by the substrate (canvas, paper, etc.), e.g. creating a correlation between geometry and matter
4. **Behavior scope taxonomy:** Lines are organized on a spectrum relative to their local verses global behavior. Global, or compositional (are constructed systematically), behavior would be characterized by equations or logic that are defined outside of the line and imposed on the line while the local behavior (based on a vicinity or scope) is exhibited when the lines themselves are imbued with goals, rules and traits

Q: Are lines automatic, autographic, automated, or autonomous?

## Chapter 3: Strategies

On what makes a good computational drawing / what over-arching principles guide the creation of computational drawing projects: 

When informed by architecture as a discipline (architects have been drawing much longer than writing computer programs): 

1. Architecture thrives within media that extend the capacity of individual human author while simultaneously limiting, filtering, or structuring the domain of inquiry
2. Requires a mastery of instruments, the deployment of knowledge, the definition of mark, and the structure of line (architectural endeavor with architectural outcomes)

[In general] ... a good drawing ... affects our ideas ... transforms conceptions, architectural actions, ordering principles, and even the nature of the world ... [that] allows us to cultivate ideas in the pursuit of new art, architecture, and design. (173)

Strategies to apply when drawing:
- **Re-code a digital tool** to reveal some changes to ways of thinking about tools
- **Misuse a digital tool** to make [^]those changes salient in the kind of work that can be produced / to create opportunistic surprises
- **Misplacing intelligence** / making a "dumb" algorithm (depends heavily on human input vs. "smart" algorithm [side note: not always more valuable than the former] that functions as an autonomous human-replacement; both reside on a spectrum, not binary classifiers)

Q: [When misusing a digital tool] Can the code be modified to expand the set of possible inputs beyond what would've made sense within the narrower scope of possibilities when interpreted as a mere tool?
 
When artists report epiphanies from the accidental blot of ink = when creative writers stumble upon new meanings only after writing or speaking = when computational designers discover projects, agendas, and opportunities in what, at first, might have been a logical flaw, or even a typo in the code (175)

> Computers actually have almost limitless tolerance for errors (as opposed to humans, who are error averse). Encountering an error, as opposed to, say, a computer crashing, is welcome when computer programing. Of course, repeated errors can be frustrating, just as teaching  while students seem to be missing the lesson. Just as an unformed idea sometimes becomes obviously flawed only as it is spoken out loud, **the discovery of errors is fuel for, not an impediment to, creativity**. (176)

> Unlike a drop of ink or the smug of a mark, computation accidents can be at profound scale. They tend to illicit utterances like "oh damn" rather than "hmmm." (176)

^ It me

> The value of process also explains why some computational artists and designers are rationally nostalgic for eras of slower computing ... [Example] "Flood fill" algorithm is virtually instantaneous, but in early computer graphics software it was possible to see the algorithm in process (175)

[Artificial intelligence is] ... often measured in terms of performance and autonomy rather than knowledge, understanding, or awareness ... [in art and design] algorithms are classified in terms of their capacity to operate in place of a human (178) 

> Computing drawing externalizes and records the thinking of the author. Coding drawing means writing the story of the drawing in explicitly textual languages (180)

Q: What is the difference between tool user, human agent and artist?

## Chapter 4: Form

> [Quoted JFK's "We chose to go to the moon in this decade ... not because they are easy, but because they are hard..."] Difficulty engenders innovation. Hard problems often bring out the best in us. How can we make drawing difficult? (215)

^ Built on the idea of self-imposed restraint [Athlete as an example: body requires resistance in order to grow]

Difficulty that computation brings to drawing? **Depth** ...
- Relating to *projection*: Allows more ambiguous relationships between objects in space and matter and machines ... uses projective representation as a way to speculate, interpret, analyze, and perceive > [rather than] a method to assert or communicate (216)
	- *Pseudo-projection rules*, e.g. perspective, orthographic and oblique parallel projects, often contain hints about depth cues
	- Drawing computationally and without representation -> representational systems are something to be designed / discovered, not imposed = matter + machines play a role in disrupting and advancing conventional representation (217)
	- Two over-arching charges to computational drawing: 1) representational systems can be authored and critiqued; 2) representational systems often are most enlightening when they don't correspond to the way we see and think about the word = both creates friction that provokes reflection and innovation
- Being *inherently difficult*: [With screen (as opposed to paper)...] Depth can be implied, and our perception of depth can be triggered, but depth is in a constant, but productive, battle with flat reality (218)
- Relating to *cues*: 
	- Occultation (overlapping objects in a field-of-view) as perhaps the most straightforward of the depth cues
	- Perspective, e.g. parallel lines converging
	- Size, e.g. small objects appear farther away than closer objects
	- Fading, e.g. lighter lines appear farther 

> If one can code depth cues, one can conceive of and discover new spatial relationships (220)

