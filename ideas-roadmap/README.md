# Introduction

I have tons of ideas. 

Unless I build momentum I cannot explore all the directions so I will need to prioritize.

If you have feedback, code, experimentations with some prompts to share, don't hesitate to shoot me an e-mail at martin.bruno.mail@gmail.com

# CORE IDEAS

## Engage a lot with the community and iterate like crazy

I want to build in the open, sharing as most as possible.

This serves both the optimization of having early feedback and matches my needs of having a framework forcing me to provide value as often as possible, and have undelayed feedback.

Also, I think that whatever happens to the business ideas, I'd be happy if I manage to help learners a lot.

I don't feel I have to build a "big" product until I really know what learners need. 
I will wait until have a strong conviction in this area.

### Digital places

I want a space where learners can share their prompts, tips and experimentations while working wich GPTs. 

Maybe a subreddit that I'd feed myself daily, and maybe a discord later.
Live Experimenting prompts can be funny enough to stream that on twitch. Or maybe not?

Maybe Discord is better as it's more interactive. I can also setup office hours where I play with prompts.

And Discord has bots.

Or, to avoid the desert township effect, setting up a whatsapp group?

I hate the fact that it somehow requires choosing a name. Should I stay with Flying-Lab? I like the name, it emphasises speed and experimentations.
But it's not appealing, what value would I get by joining such discord?

If my goal is to provide a great space so that learners share their prompt and their experimentations, the name should reflect that. 
Open Study Prompts could be a good name.

I also like names around "next gen learners", that can have multiple interesting meanings, but a bit pretentious maybe?

### Physical places

I'll try to work on this in Paris libraries or faculties to maximize my closeness with real students. 

If you have a spot for me where I can share LLM and non-LLM learning techniques and chat with students, shout me an e-mail.

I will also teach in schools or uni this mixed approach of learning techniques + LLMs.
This would provide me a lot of usecases to prepare, but also to iterate faster, and also a lot of joy. Do contact me if you are interested.

I have already some arrangements that will make it possible, but more is better.

## Actions & external UIs

Actions are GPT plugins that provide extra fonctionalities by calling APIs (that means other programs I could develop that could work with the discussion)

**anki deck generation**: This seems like an absolute must.

**study prompt library**: My ultimate.md prompt can't grow indefinetely. That would add space to contributed prompts and ease up automatic updates. Could be extended with user spaces or custom prompt building depending on some parameters, this would also gives room to user contributions.

**online web interface to discover and rate prompts**: related to the library.

**real mindmap generations**: OPML or xmind files. Xmind could support metadata, attached text, learning progress.... Other formats can be progressively supported.

**concept map generations**: mermaid renderer or other? 

**conversations to progress on an anki deck**: Study while walking! Credits to https://www.reddit.com/r/medicalschoolanki/comments/16ugoyd/gpt4_could_revolutionize_anki_with_voice/?context=3 for the idea

**Memory Frescos Generation**: Hard to explain in few lines, but the idea would be to build a large interactive scene with mnemonic images representing key concepts.

**spaced repetition support**: Doing spaced repetition but without anki.

**save to my workspace**: Save learners production to a workspace, and retrieve them to continue the learning experience. I like the vision, but that would require serious prototyping and user feedback.

**fact checking endpoint**


## Prompts to explore

**explore more role play**: Play the student that does not understand, play an oponnent that have a slightly incomplete of erroneous view of the subject.

**crank role play to the max**: build up a world where targeted knowledge is required to advance trough a real life adventure. Possible inspiration: https://github.com/microsoft/prompts-for-edu/blob/main/Students/Prompts/Simulator.MD

**Tests and solutions**: The learner uploads both tests and solutions, let the AI act as a mentor.

**Story Telling**: Turn dull informations in a story. inspiration from https://www.learningscientists.org/blog/2024/6/6-1

**Fix the mind map**: the AI provided an incomplete mindmap (flat as hell, details missing) and let the user attempt to fix it and a discussion takes place.

**Fix the concept map**: the AI provide an incomplete concept map (missing links) an the user attempt to fix it, and a discussion takes place.

**work with a special purpose chart**: For exemple the kind of maps that can be found at https://www.thinkingmaps.com/cdn/WhitePaper-BuildingBlocksofBrainBasedLearning.pdf

**Help learning this learning technique**: The world of learning techniques is richer that most people think. An interactive session where the technique is put in practice with student provided content would be an absolute blast.

**Challenge my production**: The AI look at the summary/mindmap/concept map and suggest corrections, improvements, or important missing parts. A discussion can take place.

Explore prompts from other sources https://github.com/microsoft/prompts-for-edu/blob/main/Students/README.MD


## Prompt engineering

**CI/CD**

**Prompts Evaluations and optimisations (promptfoo ? DSPY ?), support of different languages**

**Prompts composition**

**Dynamic prompt loading**. Use RAG to feed the context window with what's necessary. 


# OTHERs 

**fine tuning**: Probably an error to spend time now on this subject.

**random control trials**: That would be incredible to test the efficacy of a whole LLM based program compared to the usage of the same set of learning techniques. 
As I have a Phd, I could co-tutorate a student I guess.

**llm conversations as an alternative tests and homeworks**: I wont rant about how miss-aligned are these 4 guys: tests, teachers, students, real life outcomes. Maybe there is a shot with llms to provide different ways to test knowledge, geared toward a more practical use of the knowledge, more conceptual/understanding than detail oriented. I think tons of people are already experimenting things like that, I wish them the best. Please share if you found nice stuff in this area!


# BUSINESS

## What will be public and what won't

All the prompts and experimentations should stay public. I see this as a collective adventure. My fight is about to give learners more control, not less.

I might speak for myself, but I am the suspicous kind when I encounter a builder that want to engage the community but is not too transparent about their business plan,
or when they display statements too good to be true. Sustainability is important.


## Choice of chatgpt

I think having chatgpt as a plateform (compared to a home-grown assistant) is a good choice for the following reasons: 

- it's evolving fast. Multi-modality looks like a paradigm shift and I don't want to be 1 day late for this.
- Allows to iterative quickly
- Chatgpt is the place that everyone knows for the moment

It's not set in stone, but for now, moving quickly is my #1 concern.

Home grown chat interfaces could be a good continuation for these reasons:

- I can do a lot more behind the scene (chain call, api call)
- Privacy concerns
- Observability
- set up homegrown RAGs
- UI customisations
- Chatgpt as a plateform has risks about pricing evolutions

I bet there would be more and more ready-to-use stacks to bootstrap this kind of project, so that's another reason to wait a bit.

In the realm of interesting opportunities, the concept of artefact from Claude is very interesting.
https://support.anthropic.com/en/articles/9487310-what-are-artifacts-and-how-do-i-use-them


## Limits and obstacles

- There are some fields like Maths, Physics, Programming where "practicing" is very important. 
But LLMs are notoriously untrustworthy there.
To me, it's still an open question on how to really help here.

- Sell something one day. Students do not have too much money, and other actors have not the exact same incentives as learners.
