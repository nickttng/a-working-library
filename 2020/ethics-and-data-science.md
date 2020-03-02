*Date read - XX 2020*

-----

# Ethics and Data Science — By Mike Loukides, Hilary Mason, and DJ Patil

**On why are we now seeing an explosion of interest in data ethics** — "Because data has been integrated into every aspect of our life: the friends and business connections we’re asked to make, the shopping circulars we receive in the mail, the news we see, and the songs we’ve played. Data is collected from us at every turn: every trace of our online presence, and sometimes even traces of our physical presence. We’ve gained some advantages from data, but we’ve also seen the damage that the misuse of data has caused." (Preface)

**On what has been missing** (Preface) — "An understanding for how to put ethics into practice in data as well as the overall product development process. *Ethics really isn’t about agreeing to a set of principles. It’s about changing the way you act.* 
- Example: It'’s one thing to say that you should get permission from users before using their data in an experiment. It’s quite another thing to get permission at web scale. And it’s yet another thing to get permission in a way that explains clearly how the data will be used, and what the expected consequences are. That’s what we need to explore. 
- Important note: We should realize that ethics isn’t about a fixed list of do’s and don’ts. It’s primarily about having a discussion about how what you’re doing will affect other people, and whether those effects are acceptable. 
- The purpose of this book: Putting ethics into practice, e.g. what does it mean for hiring, how do you teach ethics in an academic setting, etc.

## Chapter 1: Doing Good Data Science

> The hard thing about being an ethical data scientist isn’t understanding ethics. *It’s the junction between ethical ideas and practice*. It’s doing good data science.

**Scenarios: Questions we need to answer**

- Example #1: "Informed consent"
	- Any code of data ethics will tell you that you shouldn’t collect data from experimental subjects without informed consent. But that code won’t tell you how to implement “informed consent.” 
		- Informed consent is easy when you’re interviewing a few dozen people in person for a psychology experiment. Informed consent means something different when someone clicks an item in an online catalog (hello, Amazon), and ads for that item start following them around ad infinitum. 
			- Do you use a pop-up to ask for permission to use their choice in targeted advertising? 
			- How many customers would you lose if you did so? 
		- Informed consent means something yet again when you’re asking someone to fill out a profile for a social site, and you might (or might not) use that data for any number of experimental purposes. 
			- Do you pop up a consent form in impenetrable legalese that basically says “we will use your data, but we don’t know for what”? 
			- Do you phrase this agreement as an opt-out, and hide it somewhere on the site where nobody will find it? 
- Example #2: "Sensitive data"
	- How do we manage any sensitive data that we acquire? 
	- It’s easy to say that applications shouldn’t collect data about race, gender, disabilities, or other protected classes. 
		- But if you don’t gather that data, you will have trouble testing whether your applications are fair to minorities.
		- Machine learning has proven to be very good at figuring its own proxies for race and other classes. Your application wouldn’t be the first system that was unfair despite the best intentions of its developers. 
		- Do you keep the data you need to test for fairness in a separate database, with separate access controls?

> To put ethical principles into practice, we need space to be ethical. We need the ability to have conversations about what ethics means, what it will cost, and what solutions to implement.

- Following the quote above: Having a space for these ...
	- Need corporate cultures in which discussions about fairness, about the proper use of data, and about the harm that can be done by inappropriate use of data can be considered. In turn, this means that we can’t rush products out the door without thinking about how they’re used. **We can’t allow “internet time” to mean ignoring the consequences.** [Emphasis mine]
	- [Personal thought: Potential criteria to consider for threat/hostile model for designers — gauging on fairness, accountability, and unintended consequences]
	- Need to think about the unintended consequences of our use of data. It will never be possible to predict all the unintended consequences; we’re only human, and our ability to foresee the future is limited, e.g. Facebook's "Year in Review" reminding users of painful events. Moving fast and breaking things is unacceptable if we don’t think about the things we are likely to break. And **we need the space to do that thinking: space in project schedules, and space to tell management that a product needs to be rethought.** [Emphasis mine]
	- Need space to stop the production line when something goes wrong. This idea goes back to Toyota’s Kanban: any assembly line worker can stop the line if they see something going wrong. The line doesn’t restart until the problem is fixed. Workers don’t have have to fear consequences from management for stopping the line; they are trusted, and expected to behave responsibly. What would it mean if we could do this with product features? If anyone at Facebook could have said “wait, we’re getting complaints about Year in Review” and pulled it out it out of production until someone could investigate what was happening?

> Users want to engage with companies and organizations they can trust not to take unfair advantage of them. Users want to deal with companies that will treat them and their data responsibly, not just as potential profit or engagement to be maximized.

Summary: What it means to do *good* data science
- Live ethical values, not just talk about them
- Think carefully about the consequences of our work
- Create space for ethics within our organizations

## Chapter 2: Of Oaths and Checklists

Being skeptical about the value of "oaths" in data science similar to the concept of Hippocratic oath
- They are one-shots. You don't remind yourself daily or continually evaluate whether you are living to to it
- *Very* general and broad principles, which are likely to result in "nice idea, but short on execution"
- Could give cover to people and organizations to do unethical work. It is not enough to say, "don't be evil." You have to not be evil
- Do very little to connect theories / principles to practice

On the other hand, oaths are good at creating discussion.

**What is better than oaths? Checklists**

> Unlike oaths, checklists connect principle to practice. Everyone knows to scrub down before the operation [Reference to surgery activity]. That’s the principle. But if you have to check a box on a form after you’ve done it, you’re not likely to forget. That’s the practice. And checklists aren’t one-shots. **A checklist isn’t something you read once at some initiation ceremony; a checklist is something you work through with every procedure.**

Examples of checklist in data science:
- The UK Government’s Data Ethics Framework
- Data Ethics Workbook

Checklists are built around simple, “have we done this?” questions — and they are effective because they are simple: They don’t leave much room to wiggle. 
- You’ve analyzed how a project can be abused, or you haven’t 
- You’ve built a mechanism for gathering consent, or you haven’t

**A checklist for working on data projects:**
- [ ] Have we listed how this technology can be attacked or abused?
- [ ] Have we tested our training data to ensure it is fair and representative?
- [ ] Have we studied and understood possible sources of bias in our data?
- [ ] Does our team reflect diversity of opinions, backgrounds, and kinds of thought?
- [ ] What kind of user consent do we need to collect to use the data?
- [ ] Do we have a mechanism for gathering consent from users?
- [ ] Have we explained clearly what users are consenting to?
- [ ] Do we have a mechanism for redress if people are harmed by the results
- [ ] Can we shut down this software in production if it is behaving badly?
- [ ] Have we tested for fairness with respect to different user groups?
- [ ] Have we tested for disparate error rates among different user groups?
- [ ] Do we test and monitor for model drift to ensure our software remains fair over time?
- [ ] Do we have a plan to protect and secure user data?

## Chapter 3: The Five Cs

What does it take to build a good data product or service that is not just useful or commercially viable, but uses data ethically and responsibly, which puts the user in the center of the conversation?

Users lose trust because ...
- They feel abused by malicious ads
- They feel abused by fake and misleading content
- They feel abused by “act first, and apologize profusely later” cultures at many of the major online companies 
- They feel abused by many abuses they don’t even know about, e.g. Why was their insurance claim denied? Why weren’t they approved for that loan? Were those decisions made by a system that was trained on biased data? 

> The slogan goes, “Move fast and break things.” But what if society is broken?

### Five frameworks when building data products:
1. **Consent**
	- **Ideally**: Trust begins on an agreement between both parties (In this case, between the people who are providing data and the people who are using it) -> Agreement starts with obtaining consent to collect and use data
	- **Hostile pattern**: "Unfortunately, the agreements between a service’s users (people whose data is collected) and the service itself (which uses the data in many ways) are binary (meaning that you either accept or decline) and lack clarity. In business, when contracts are being negotiated between two parties, there are multiple iterations (redlines) before the contract is settled. But when a user is agreeing to a contract with a data service, they either accept the terms or they don’t get access. It’s nonnegotiable."
	- **In practice**: At every step of building a data product, it is essential to ask whether appropriate and necessary consent has been provided.
2. Clarity
	- **Ideally**: Clarity is closely related to consent. You can’t really consent to anything unless you’re told clearly what you’re consenting to. *Users must have clarity about what data they are providing, what is going to be done with the data, and any downstream consequences of how their data is used*.
	- **Hostile pattern**: All too often, explanations of what data is collected or being sold are buried in lengthy legal documents that are rarely read carefully, if at all.
		- This isn’t to say that such usage [of tweets being collected for research or for sale] is unethical; but as Casey Fiesler points out, the need isn’t just to get consent, but to inform users what they’re consenting to. That’s clarity.
		- Unfortunately, the process of consent is often used to obfuscate the details and implications of what users may be agreeing to. And once data has escaped, there is no recourse. You can’t take it back. Even if an organization is willing to delete the data, it’s very difficult to prove that it has been deleted.
	- **In practice**: Work to develop models that help users to understand the implications of their choices.
3. **Consistency and trust**
	- Trust requires consistency over time. You can’t trust someone who is unpredictable [e.g. Facebook]... Restoring trust requires a prolonged period of consistent behavior. Consistency, and therefore trust, can be broken either explicitly or implicitly; intentionally or unintentionally
4. **Control (and transparency)**
	- Once you have given your data to a service, you must be able to understand what is happening to your data. 
		- Can you control how the service uses your data?  
		- What happens if you change your mind about the data you’ve provided?
	- Often, users have no effective control over how their data is used — 1) Given all-or-nothing choices; or 2) Controlling access is overwhelming or confusing
5. **Consequences (and harm)**
	- All too often, unknown unknowns are unknown because we don’t want to know.
		- **Example of technology + policies:** Technology rapidly outpaces [laws/regulations] being adopted by society. The Obama administration creates tech-related roles, e.g. technology officer and chief data scientists (40+) across the federal government to ensure that the regulatory process fosters innovation while ensuring the question of potential of harm is asked regularly and often
		- **Example of exposed Strava data:** In 2018, Strava opened up their data to allow users to discover new places to run/bike, which exposed members of the US military who were using GPS-enabled wearables and their activities / locations of bases / patrol routes. 
		- Ask ourselves: By [doing this], how might we trigger [unintended / unforeseen / harmful consequences]

### Implementing the Five Cs

In addition to designers (assumed responsibility), it’s the responsibility of the entire team. The five Cs need to be part of every organization’s culture.
- The data scientists need to approach the problem asking “what if” scenarios that get to all of the five C’s. 
- Also true for the product managers, business leaders, sales, marketing, and also executives. 
- Product and design reviews should go over the five Cs regularly. They should consider developing a checklist before releasing a product to the public. All too often, we think of data products as minimal viable products (MVPs: prototypes to test whether the product has value to users).