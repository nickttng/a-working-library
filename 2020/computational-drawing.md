*Date read - Jan 2020*

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

### Objects

[Content] is the process and its own world (nothing outside of that world need enter), which may become incredibly complex and detailed ... > despite the suggestion that automatic drawings may be subconscious, it is nearly impossible to draw without some kind of indirect imagination, interpretation, and judgement = these behaviors tend to emerge because we cannot help but read into the drawing as we draw [furthermore, once those behaviors emerge, so does content] (221)

Create form => Drawing with respect to the form of existing or known objects = somewhat obvious approach to drawing come *after* depth cues and projection methods have been interrogated and critiqued (221)

### Surfaces

Like depth cues, surfaces can play a similar roles that are unique opportunities for computational drawing in that they sustain a threshold between legibility of objects and legibility of line in drawing (222):
- Emerge from a drawing to form objects and define space
- Structure the geometry computationally
- Be the subject of a drawing if modeled before projection, e.g. drawing sources via projection is a pre-digital cartographic technique for the rendering landform

### Two and a half dimension objects and pseudo-spaces

> ... pixel has been explored as a component of a kind of model—the digital age. But in considering the nature of pixels as immaterial, we must confront a casual myth: **that a pixel-based image can become ad drawing when it is printed. One might ask, why not?** The result of the digital print is material. (223)

### The Form of Ink

Bleeding ink leads to ...
- Each mark tends to be softened. The edges of the mark are not clearly defined, but tend to dissolve gradually. Lines drawn slower leave the pen in contact with the paper for longer, resulting in a more transfer of ink and thicker lines
- Ink from one mark can bleed into another causing them to blend
- Because the ink is initially wet, later marks can spread the ink left by earlier marks. The paper itself changes its nature as it interacts with the tip of the pen and the ink as well. Softer, thicker papers will have very subtle troughs left but the pressure of the pen ... many marks made over the same line can saturate the paper, weakening it

Behavior of ink can allow lines to call attention to themselves as material on paper = [similar condition] = signing simultaneously involves the sound of words and the meaning of words

> An ambiguity of the fifth type occurs when the author is discovering his idea in the act of writing, or not holding it all in his mind at once, so that, for instance, there is a simile which applies to nothing exactly, but lies half-way between two things when he author is moving from one to the other

^ Empson's ambiguity type five being applied to computational drawing and can serve as a basis for a theory of representation. Not a matter of multiple interpretations of definitions but rather it betrays a conflict in the author's mind. (Note to self: Read Empson's *‌Seven Types of Ambiguity* to getter understand this context) 

## Chapter 5: Futures

> Every year since 1978 the Post uses a list of paired terms, one is out—as in out of fashion—and the other is in [In/Out format]. Taken in the aggregate, these lists are more than a collection of passing trends, but a deep analysis of the direction and priorities of a nation ... positions macro economic trends along side matters of aesthetics and taste. The pairing is, of course, essential. *Much more interesting than just what's trendy now is what that is replacing, mitigating, or undermining* ... once relevant vs. what is now relevant = projecting that vector forward => taking the pulse of a culture also implicating predicts the future (277)

### Still on Paper, Still Difficult, Slower, Longer

What is the future of drawing? Addressing this is difficult because it doesn't look much different than its past = [similar] = "What is the future of voting" would address what might be possible quickly leads to an inquiry of what *should* be possible => Fixing the inherent limitations of drawing does not advance drawing, but rather it will advance and expand its duration, scale, indirection, and range of human engagement. 

> Technology, specifically computational technology, will not alleviate the difficulty of depth, automate the production of drawing, or make the interfaces of drawing more convenient or seamless. In some cases, the seams will be greater, the difficulty more palpable, and the process more layered and less direct. In other cases, the different ways we draw will cause cultural, theoretical, and conceptual shifts (279)

### Renewed Focus on Craft

[Post-post-digital era] Becomes comfortable again [unlike post-digital era] with the notion  that novel techniques can open the door to new theories and ideas:
- Post-digital projects avoided discourse about the digital at their peril => ironically, these projects can accidentally converge with one another = can describe a position, and unfortunately, an aesthetic
- Post-post-digital projects brings acceptance of digital expertise, but will expect that such expertise bring humor, critique, messiness, and artistry to the digital landscape

### Drawing will be disciplinary

Hybridization of computation with drawing will give renewed energy to the prospect that drawing can be understood as its own discipline, especially as an autonomous discipline prompting a reflection on nature and methods of computing 

### Making and Re-making Technology

> Focus on how authors make technology for their practice rather than use technology made by others. Relatedly, those who write code will be celebrated not just for what they enable others to do, but will be expected to create themselves (282

Today = We can shift to coding that bridges between scales, media, and formats

Possibly, what chasm that is dramatically narrowing: impersonal "make a tool for others" <> the hyper-personal "my work is a reflection of myself"

Be open to analysis, critique and discourse.

Look forward ===???>>> a possible future that celebrates the code written by artists, architects, and designers that make us think (with its strangeness, quickness or capacity) rather than impress with something marketable to a wide audience. :crosses-fingers: