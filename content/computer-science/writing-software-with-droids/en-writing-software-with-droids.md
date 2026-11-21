---
title: Writing Software w/ Droids
draft: true
authors: 
explanation: A long read, researched in depth, between an article and a book.
---

ChatGPT made large language models available to the general public in late 2022.

By late 2025, LLMs had become capable of contributing to software projects at the architectural level. Earlier that year, in February, Andrej Karpathy had coined the term "vibe coding."

Vibe coding is mostly associated with asking an LLM for software or a feature without looking at the code it produces. That's the scissors.

Let's look at the droids.

In 1797, Goethe wrote The Sorcerer's Apprentice.

The apprentice, tired of carrying water, enchants a broom to do the chore for him, with magic he has not fully mastered. Soon the floor is flooded, and he cannot stop the broom, because he does not know the spell that ends it.

In 1940, Disney made Fantasia, which tells the same story.

Writing software with droids is exactly the same.

Everything begins with knowing what to do and how to do it. With droids, you cannot write better software than you could write without them, should you have the time.

## Glossary

"AI" is a broad word: it covers chess engines, spam filters and protein folding too. This article is about something narrower.

- **Large language model:** a model trained on text that continues whatever is in front of it.
- **Harness:** the program around the model that reads files, runs commands and tests, and loops, such as Claude Code.
- **Droid:** a large language model in a harness.
- **AI:** the broad public word, used here only when the public debate is meant.

## TL;DR

Set the rules of the game. Write CONTRIBUTING.md.

### Readable at mid experience

You want a software which will be human readable. And you want it human readable at certain experience level. Do you want software which can be read only by the most experienced of developers who know every quirk of the language? Say so. And you will get it. Do you want it? I don't think so. Take a safe decision in line with the people you might be able to recruit. In case you cannot pay for AI, or in case AI vanishes from the face of the earth. Safe bet is mid. So say: I want software written so that people with mid experience can read it. Which doesn't mean to write software at the quality level of mid experience people. You can write software at the level of the most experienced people, but it should be readable by junior and by mid experienced people.

Some quantifications. It is difficult and counterproductive to instruct droids to maintain fixed numbers, for example: don't write a file longer than 199 lines, or don't write a function longer than this number of lines, or don't write code deeper than so and so many calls. But you can work with spirit, and droids are very good in understanding non-numeric instructions. The instruction should be that the total cognitive cost of code, including length of file, length of function, length of code block, depth of calls, should not exceed 7 ± 2 (George A. Miller, "The Magical Number Seven, Plus or Minus Two", 1956).

In 2001, Nelson Cowan corrected this number to four (Nelson Cowan, "The Magical Number 4 in Short-Term Memory: A Reconsideration of Mental Storage Capacity", Behavioral and Brain Sciences, 2001).

So whatever you do, find ways to resonate with your droids, so that they produce something you can work with on a human cognitive level. And they will do it for you.

### All good things are two

Droids can be described in many different ways, one such is a crane or a forklift or something which can lift immensely more than a person can. In software, there is such area, which is tests. Droids can write infinite number of tests of many different kinds. Use it.

### All good things are three. Have fun.

Computer languages have been invented for different reasons. Sometimes just because somebody didn't like the existing languages, or just because somebody's brain worked in a specific way.

Computer science, on another hand, has been trying and is still trying to find more efficient ways to write software.

Yet many things in software remain preference, as they are in other areas of life, such as politics, art, and taste in food.

So have fun.

Droids gives you the unique opportunity to do things the way you like, almost regardless of the effort, by following your vibe.

### Cancer

Droids have a dark side too. They could misunderstand, and if you don't watch it, misunderstandings can grow into software architecture, features and misfeatures.

If you visit an Austrian family owning a castle, you might or might not be surprised to see, for example, the lady of the house doing manual work together with the employed workers. This is an expression of ownership and owner responsibility. The land is hers. The responsibility is hers. The work is hers. She employs helpers, but she's the first who will go out and do things for which there is nobody to do.

Same is with software. The software is yours. It's your responsibility to accept the software from droids. Therefore, there are a few tips.

1. Droids might or can produce very long lists of recommendations. If this challenges you, ask them to save it as a recommendation file, in a folder with recommendations, and then later ask them to find you the best next recommendation.
2. Break work in small changes.
3. Ask them to focus on the task at hand, and do not accept every suggestion they give you. They are driven to give you suggestions. They're just driven to be helpful. Which could move the scope or defocus the scope, if one doesn't hold it well. Keep them focused on one task. Be disciplined. Finish one task well.
4. Droids get oriented from what's already there. Therefore, you have to create a good architecture from the beginning. If you create a good architecture, if you lead them in a good way, they will enhance the building in a way.

The droids, the AI, is like bees. If you let bees, they can build these perfect hexagonal cells. But they don't build them on a flat surface, as people need them to harvest the honey. They build them in whatever shape they have, in the hole in the tree or wherever. AI needs a shape it can fill perfectly. If the shape is crooked, or if you let AI crook the shape, you will get a crooked shape at the end. And AI will think that it has done a good job, and you will be unhappy.

## Drift

Loose notes, to work on later:

- Two things to know: drift and agreement.
- LLMs drift because they follow. Drift is central to how LLMs work: they continue whatever is in front of them.
- Agreement: they tend to agree with whoever they're talking to.
- Example: Snake, the old computer game. Only the head moves, and the rest follows where the head went.
- Why they drift: Dijkstra saw it coming. In "On the foolishness of 'natural language programming'" (EWD 667, late 1970s) he argued that ordinary language is too vague to instruct machines with, and that formal notation exists to escape that vagueness. Now we program droids in natural language, and we see it is too vague: a vague prompt drifts, like the Sorcerer's Apprentice's broom. The answer is his answer too: precise text, the rules of the game in CONTRIBUTING.md.
- Writing it down: "If you're thinking without writing, you only think you're thinking." (Leslie Lamport, computer scientist, Turing Award 2013)

## Quality

Technological progress needs the original thought. But some original thoughts come ahead of their time, and the technology to carry them is missing.

Mutation testing is one: plant small faults in the code and check that the tests catch them. Richard Lipton proposed it as a student in 1971, and DeMillo, Lipton and Sayward published it in 1978 ("Hints on Test Data Selection", IEEE Computer). For decades it was too expensive to write and to run.

Now droids write the tests, and running them is no longer a problem: many cores sit idle overnight, at home or in the office. Approaches to quality that waited fifty years become possible.

Stuart Kauffman called this the adjacent possible: an idea becomes real once the steps next to it exist. Gunther Stent called ideas that come too early premature ("Prematurity and Uniqueness in Scientific Discovery", Scientific American, 1972). A separate article takes this further: The Adjacent Possible.

## Learn

Ask the droid to explain to you what you're doing. Ask them to explain what roots it has. And you will be surprised. Learn what they tell you.

And not only software. One of the things which would have made me use LLMs earlier is if I knew that I could discuss with them Kierkegaard and Dijkstra, the computer scientist Dijkstra and the philosopher Kierkegaard, while debugging JavaScript.

Many of the things which one does have roots and explanations in computer science and life and psychology. So while doing something, one can actually learn how to do it. But if you don't ask the LLM, it will not tell you. So you have to ask. It's a bit like Neo and the Oracle in The Matrix: you have the skill, but it looks like you're waiting for something. So you have to ask.

## A Shared Language

Droids speak well, but not always in our words. Two things help.

1. One short rule in CONTRIBUTING.md: full sentences, proper nouns, as few pronouns as possible, and the language of computer science and of the domain. "The Battery must charge, because the Battery is empty" is better than "It must do this, because it is empty."
2. A dictionary of our own words. Even with proper nouns, a droid uses words which make sense to the droid but are not our jargon. Every misunderstanding becomes one line in a GLOSSARY.md: our word, what our word means, and the words a droid must not use instead. The dictionary lives in the repository, not in a session, because sessions forget and the repository does not.

Source:

* E. Evans, *Domain-Driven Design*, Addison-Wesley, 2003: the ubiquitous language, one language shared by the code and the people of the domain.

## The Invisible Puzzle

We do not use tickets. We have documentation: vision, mission, architecture, backlog, roadmap. Together these texts are the big picture, an invisible puzzle, a framework. Then we move in very small steps, each finished within a day, a week, or two weeks at most. Every step puts one piece of the puzzle onto the invisible framework. We do not build randomly; we gradually complete the picture. A diary, written every day, holds the tasks given and the feedback received.

Droids fit this way of working. A droid fills the shape a droid is given, as the bees above fill the hole in the tree. The invisible puzzle is that shape.

## Where the Words Live

1. CONTRIBUTING.md and GLOSSARY.md hold the rules and our words. Both rarely change, and a droid reads both every time.
2. The pull request holds the explanation of each change: the developer's rough notes at the bottom, the droid's draft in our words on top, approved by the developer.
3. A comment in the code holds only the why of a tricky spot, for example why a timeout is 300 ms.
4. A README next to a module explains that module: what the module does, how the module is used, and its quirks. The developer and the droid update the README in the same pull request as the code.
5. The documentation repository holds what spans several modules or faces the customer.

## The Translator

Some of the best developers find explaining hard. The developer knows exactly why the code works; turning that knowledge into the explanation other people expect is the hard part. A droid can take on that step.

The droid interviews the developer in writing: short, concrete questions, one at a time, such as "Why does the Battery Controller retry three times?" The developer answers in any form, even in fragments. The droid writes the answers up in our words, as documentation, a pull request description or a summary for the manager. The developer stays the author and approves the text. The developer's own words stay visible under the droid's version, so nothing gets lost and nothing gets invented.

Written, asynchronous channels serve better here than live meetings. And a short, blunt style is a style, not a fault to correct.

Source:

* D. Milton, *On the ontological status of autism: the "double empathy problem"*, Disability & Society 27(6), 2012: when two people who think differently misunderstand each other, the gap belongs to both. A translator serves both sides, and nobody has to be changed.

## The New Partner

A relationship begins with the exterior: the other person is funny, looks good. Then the two people discover other nice things about each other, rely on each other, and the relationship becomes a very nice one. But each also discovers the defects of the other. Then a new person appears, nice-looking and fun, whom nobody knows in depth yet. The new person might be wonderful or not at all. The new person threatens the relationship anyway.

The same happens with droids. A droid shines on quick work: the result looks good and presents well, even when the result is not perfect. The manager sees the new partner as nicer. The developers feel threatened and compared.

The comparison is not fair. The manager compares the droid's polished first impression with everything known about the developers after years, the flaws included. Psychology calls the first part the halo effect: polish and fluency make something seem competent overall. Everyday speech says the grass is greener; technology speaks of shiny object syndrome.

The metaphor ends here. The question is not a new relationship, but how the roles rearrange, and whether they rearrange fairly.

Sources:

* E. L. Thorndike, *A Constant Error in Psychological Ratings*, Journal of Applied Psychology 4(1), 1920: the halo effect.
* L. Festinger, *A Theory of Social Comparison Processes*, Human Relations 7(2), 1954: people judge themselves by comparison with others, so the developers feel compared even when nobody says a word.

## For Managers

1. Judge the droid by the same standard as the developers: bugs, rework and review time over months, not the first five minutes.
2. Watch your own enthusiasm. The excitement about the new is a known bias, not a measurement.
3. Never compare out loud. "The droid did that in ten minutes" hurts and teaches nothing.
4. Say in writing what the roles are and what happens to the jobs. Uncertainty hurts more than bad news.
5. Put the developers in charge of the droids: the droid proposes, the developer decides, above all in the Structured Text and in safety-critical code.
6. Introduce droids in small pilots, measure, and decide together.
7. Keep some work without droids, so the skills do not fade.

Source:

* A. Edmondson, *Psychological Safety and Learning Behavior in Work Teams*, Administrative Science Quarterly 44(2), 1999: teams learn when people can speak up without fear.

## For Developers

1. Choose where to use droids yourself: tests (the forklift above), boilerplate, and the explaining work (The Translator).
2. Keep a list of the mistakes you catch in a droid's output. The list makes your depth visible, to the manager and to yourself.
3. Keep the right to say "no droid here" for critical code, and say why.
4. Learn from the droid (Learn above): ask for the roots of what you do.
5. Move toward what stays scarce: knowing the domain, shaping the architecture, accepting the work as its owner (the castle above).
6. You do not have to change who you are. Write the way you think, and let the droid translate.

## A Tool, like a Hammer

AI is a tool, as a hammer is a tool. Every tool made certain jobs easier, and one way or another made people unemployed: the power loom, the tractor, the cash machine. People reoriented themselves. After cash machines arrived, the number of bank tellers grew for decades, and the teller's job moved from counting cash to advising customers. Automation usually replaces tasks, not whole jobs, and creates demand for the work around the machine.

The reorientation is real for society, and it can still be painful for a person. The handloom weavers of the 19th century did not all find a new place. Honesty belongs to this story.

The reorientation in software:

* Fred Brooks split the difficulty of software into the essential and the accidental. Droids take over much of the accidental: typing, syntax, boilerplate, tests. The essential stays: knowing what to build, for whom, in which domain, and why.
* Peter Naur described a program as a theory living in the heads of the people who built the program. A droid does not keep that theory between sessions. People keep the theory, and what people write down.
* William Stanley Jevons observed that when coal became cheaper to use, more coal was used, not less. When software becomes cheaper, more software is wanted, and more people are needed who can own it.

So the developer moves from writing code toward specifying, shaping the architecture, reviewing and accepting, testing, explaining, and standing behind the result.

Sources:

* J. M. Keynes, *Economic Possibilities for our Grandchildren*, 1930: the term technological unemployment, and the expectation that people adjust.
* D. Autor, *Why Are There Still So Many Jobs? The History and Future of Workplace Automation*, Journal of Economic Perspectives 29(3), 2015.
* J. Bessen, *Learning by Doing*, Yale University Press, 2015: the cash machines and the bank tellers.
* F. P. Brooks, *No Silver Bullet: Essence and Accident in Software Engineering*, 1986.
* P. Naur, *Programming as Theory Building*, Microprocessing and Microprogramming 15(5), 1985.
* W. S. Jevons, *The Coal Question*, 1865.

## The Direction

Careful, not bravado. AI is new and uncertain: providers change, funding may shrink, prices may rise, as TL;DR 1 says: in case you cannot pay for AI, or in case AI vanishes. But competitors use AI too, so standing still is also a risk.

The middle way:

* small pilots, measured;
* humans stay accountable;
* code readable by people of mid experience (TL;DR 1);
* no dependence on a single droid;
* skills kept alive.

## Value

In my words, as I said them on 18 November 2026:

<blockquote>It's part of my article actually, how to use AI. And value is important because now everybody can generate an image, everybody can write a text. And even recently, there was an article that marketplaces are full of AI stuff which nobody buys.</blockquote>

<blockquote>That's partially an economical problem because, what was it? Opulence, not opulence, but like oversupply kills the market, reduces the prices. You can generate your own image. Everybody can generate your own image. So a generated image costs nothing, but you can also not sell it because it carries no value.</blockquote>

<blockquote>People are flooded.</blockquote>

<blockquote>And here we come to the economy. And this is one of the first things, correct me if I'm wrong, also Samuelson, et cetera. And basically it's a value. That's one of the most basic economic concepts.</blockquote>

<blockquote>What stays scarce and what gives value to the people? So basically, what are people ready to pay for? Because their resources, their money, their exchange value, it is scarce. People have limited, like private individuals and businesses. They have limited amount of money, to achieve their goal. Their business goal or their private goals.</blockquote>

The words for it: abundance turns a product into a commodity, and a flood of goods is a glut. The flood of low-effort AI content has a name of its own: AI slop. Slop was once cheap, watery food for pigs.

Price comes from scarcity, not from usefulness. Adam Smith's example is the paradox of diamonds and water: water is essential and cheap, because there is plenty of water; diamonds are scarce and expensive. Droids make text, images and code plentiful, so text, images and code lose their price. What stays scarce with droids: trust, accountability, deep domain knowledge, and judgment. A customer of an energy system does not pay for lines of code, but for a system which works safely for years, and for someone who stands behind the system.

And a side thought, in my words:

<blockquote>I love to write, and I believe that written text has value. A well-written text has value. And it will remain like the Bible. So videos have value, but also the written text has value. So I think text production remains very valuable. Good text remains valuable.</blockquote>

The production of words loses value, because generic text is now nearly free. Good text, with real thinking, a voice of its own and an author who stands behind the text, becomes rarer in the flood, and so more valuable.

Sources:

* A. Smith, *The Wealth of Nations*, 1776, Book I, chapter 4: the paradox of water and diamonds.
* P. A. Samuelson, *Economics: An Introductory Analysis*, McGraw-Hill, 1948: scarcity as the first concept of economics.

## Trust

In my words:

<blockquote>The Hanseatic is a very good example. … The information traveled extremely slowly. And trust was absolute, had an absolute, extremely high value.</blockquote>

The Hanseatic League was at its height in the 14th and 15th centuries, and traded from London and Bruges to Bergen and Novgorod. A letter took weeks. A merchant in Lübeck could not check what a partner in Bergen did with the goods. Trust carried the trade: family ties, the merchant's mark on the goods, the Kontor abroad, reputation, and exclusion from the community for whoever cheated.

With droids, we come back to the situation of the Hansa. Producing has become nearly free; checking has become expensive again. Is this real? Who wrote this? Does this work? When buyers cannot check quality, bad offers drive out good ones, and buyers retreat to the sellers they know. Trust becomes scarce again, so trust becomes valuable again.

Why trust in people remains, and could become more important:

1. Trust reduces complexity. Nobody can check everything, so people rely on people. The more droids produce, the less anyone can check, and the more trust is needed.
2. Trust is limited by nature. A person keeps stable relations with about 150 people. Personal trust cannot be mass-produced, so personal trust stays scarce, unlike text, images and code.
3. Trust needs someone who can lose something: a name, a reputation, a livelihood. A droid can be wrong, but a droid cannot be ashamed, cannot be sued, and cannot lose its name in the town. The person who signs the work can. So accountability stays human, as the merchant's mark stood for the merchant.
4. Trust grows from meeting again and again over the years, as in the relationship above. The years with the developers are exactly the capital the new partner does not have.

Sources:

* P. Dollinger, *The German Hansa*, Macmillan, 1970 (*Die Hanse*, 1964).
* A. Greif, *Contract Enforceability and Economic Institutions in Early Trade: The Maghribi Traders' Coalition*, American Economic Review 83(3), 1993: the same mechanism among medieval Mediterranean traders, trust kept by reputation and collective exclusion.
* G. A. Akerlof, *The Market for "Lemons": Quality Uncertainty and the Market Mechanism*, Quarterly Journal of Economics 84(3), 1970.
* N. Luhmann, *Vertrauen: Ein Mechanismus der Reduktion sozialer Komplexität*, 1968.
* R. Dunbar, *Neocortex size as a constraint on group size in primates*, Journal of Human Evolution 22(6), 1992.
* N. N. Taleb, *Skin in the Game*, Random House, 2018.
