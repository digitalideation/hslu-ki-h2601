# Part 3: Perception: From Data to Experience

**What would count as perception in an AI system?**

Start with the [perception workshop](./session01_03_04.md). This page supports the activities: consult a short introduction when it becomes useful, and return to the longer materials when you want to explore further.

By the end, you should be able to distinguish sensing, representation, and lived experience; use a philosophical idea to question an AI example; and check an AI-generated explanation against a source.

## Resources during the workshop

You do not need to consume all these materials. The short introductions below are the core reading; the workshop specifies when to use them.

| Resource | When and why to use it |
| --- | --- |
| [Maurice vs George Miro board][miro-perception] | Record initial positions, observations, disagreements, and revisions throughout the workshop |
| [Berkeley introduction](#berkeley-perception-and-existence) and [section 6][berkeley-section-6] | Activity 2: distinguish existence from an individual observer's access |
| [Merleau-Ponty introduction](#merleau-ponty-the-lived-body) | Activity 3: interpret an observation about movement, touch, or bodily context |
| [NotebookLM notebook][notebooklm-notebook] | Ask a focused question, find a relevant source, or unpack a difficult passage |
| [NotebookLM podcast][notebooklm-podcast] | An alternative explanation; use a short passage selected in class, or listen afterward |
| [Verification routes](#verification-routes) | Activity 4: check one claim in an LLM response against an identifiable passage |
| [Public course Miro board][miro-board] | Carry a question or design idea into the wider course |

NotebookLM explanations and audio are generated interpretations. When using them as evidence, follow their references to the underlying material. You can use the short introductions and linked text without access to NotebookLM.

## Philosophical lenses

These perspectives help us formulate questions. Applying them to AI is a contemporary interpretation, not something either philosopher wrote about today's systems.

### Berkeley: Perception and Existence

Berkeley questions the idea of sensible objects existing independently of any perceiving mind. His account does not imply that a room vanishes when one person leaves: section 6 also invokes an eternal spirit. Read [that section][berkeley-section-6] to see why “not perceived by me” and “not perceived by any mind” are different claims.

**Use in Activity 2:** distinguish the room, the robot's stored map, and its current access to the room. Which of these are we calling its “world”? Treating a stored representation as a perceiving mind would require a further argument.

### Merleau-Ponty: The Lived Body

For Merleau-Ponty, perception is rooted in our bodily involvement in the world. The body is more than an instrument delivering measurements: our situation and possibilities for action shape how things appear to us. See the [publisher's introduction to *Phenomenology of Perception*][merleau-ponty-edition] and the original text's [Preface, in French][merleau-ponty-preface].

**Use in Activity 3:** consider how moving your hand changes what you can discover by touch, or how a robot's possible movements affect its access to a cup. This is a way into the question of embodiment; successful sensing and action alone do not settle whether a machine has subjective experience.

## Verification routes

Choose one route for Activity 4. Check a small claim carefully rather than trying to summarize an entire philosophy.

- **Berkeley: default route in English:** read **section 6** of [*A Treatise Concerning the Principles of Human Knowledge*][berkeley-section-6]. Test a claim about what happens when an individual stops perceiving an object. Look for the distinction between individual minds and an eternal spirit.
- **Merleau-Ponty: original text in French:** in the [Preface to *Phenomenology of Perception*][merleau-ponty-preface], find **“La perception n'est pas une science du monde”** and read that paragraph. Test whether the LLM treats perception primarily as explicit knowledge or judgment. An English excerpt supplied in class can serve the same purpose; record the edition and page.
- **If the original text is inaccessible:** use the short course introduction to identify a question to check, then switch to the Berkeley route for source verification. A course summary or another AI answer should not be presented as the philosopher's original text.

A source may support the historical claim while leaving its application to AI undecided. Keep that distinction in your assessment.

## Questions to return to

- What does a system's behavior let us observe, and what are we inferring about its experience?
- Does a camera classifier, a robot moving through a room, and a text-only chatbot each have the same relation to the world?
- In a virtual environment, how do we distinguish stored state, rendered appearance, and someone's experience?
- How does an AI explanation influence which philosophical interpretation we find convincing?

## Synthesis: Make the Comparison Specific

Use this table to question an example after the workshop. It is a guide for discussion, not a classification of all humans and all AI systems.

| Dimension | Human example | AI example | Open question |
| --- | --- | --- | --- |
| Sensing and action | Moving a hand to explore an object | A robot changes position to gather sensor data | How does action change what can be detected? |
| Representation | Describing a familiar room from memory | Using a stored map without live camera input | How does a representation differ from current access? |
| Lived experience | Describing how an encounter feels | Producing a description of an encounter | What evidence would justify attributing experience? |
| Context | Recognizing a cup through habits and purposes | Identifying a cup for a specified task | What gets lost when we reduce recognition to a label? |

Keep one distinction that helps your design practice and one question you cannot yet settle. Return to the [closing reflection](./session01_03_04.md#collective-reflection-what-changed) to turn them into an interaction or artwork idea.

## Further exploration

- [How to make AI that's good for people][google-how-to-make-ai-good-for-people]
- [George Berkeley][wikipedia-george-berkeley]
- [Three Dialogues Between Hylas and Philonous][three-dialogues]
- [Maurice Merleau-Ponty][wikipedia-merleau-ponty]
- [Physiognomy's New Clothes][physiognomys-new-clothes]
- [Our machines now have knowledge we'll never understand][wired-machines-knowledge]
- [Can you trust AI? Here's why you shouldn't][conversation-can-you-trust-ai]
- [The seven deadly sins of predicting the future of AI][rodneybrooks-seven-deadly-sins]
- [Facial recognition’s dirty little secret][nbcnews-facial-recognition]
- [Yuval Harari on ChatGPT][nytimes-harari-ai-chatgpt]
- [You can have the blue pill or the red pill...][criticalai-blue-pill]
- [The mind‑expanding ideas of Andy Clark][newyorker-andy-clark]
- [The history of open‑source LLMs][history-open-source-llms]

[notebooklm-notebook]: https://notebooklm.google.com/notebook/af5ed21e-57cd-4d0a-b2a1-8c96e3e75d74 'NotebookLM - notebook'
[notebooklm-podcast]: https://notebooklm.google.com/notebook/af5ed21e-57cd-4d0a-b2a1-8c96e3e75d74?artifactId=4f0253fe-b5c6-4697-8177-92c4323405b0 'NotebookLM - podcast excerpt'
[miro-perception]: https://miro.com/app/board/uXjVIMRGp4w=/?share_link_id=956730497904 'Miro board - Maurice vs George'
[google-how-to-make-ai-good-for-people]: https://blog.google/technology/ai/how-make-ai-good-for-people/ "How to make AI that's good for people - Google"
[wikipedia-george-berkeley]: https://en.m.wikipedia.org/wiki/George_Berkeley 'George Berkeley - Wikipedia'
[three-dialogues]: https://en.wikisource.org/wiki/Three_Dialogues_Between_Hylas_and_Philonous 'Three Dialogues Between Hylas and Philonous - full text'
[wikipedia-merleau-ponty]: https://en.wikipedia.org/wiki/Maurice_Merleau-Ponty 'Maurice Merleau-Ponty - Wikipedia'
[physiognomys-new-clothes]: https://medium.com/@blaisea/physiognomys-new-clothes-f2d4b59fdd6a "Physiognomy's New Clothes - Medium"
[wired-machines-knowledge]: https://www.wired.com/story/our-machines-now-have-knowledge-well-never-understand/ "Our machines now have knowledge we'll never understand - Wired"
[conversation-can-you-trust-ai]: https://theconversation.com/can-you-trust-ai-heres-why-you-shouldnt-209283 'Can you trust AI? - The Conversation'
[rodneybrooks-seven-deadly-sins]: https://rodneybrooks.com/the-seven-deadly-sins-of-predicting-the-future-of-ai/ 'The seven deadly sins of predicting the future of AI - Rodney Brooks'
[nbcnews-facial-recognition]: https://www.nbcnews.com/tech/internet/facial-recognition-s-dirty-little-secret-millions-online-photos-scraped-n981921 'Facial recognition’s dirty little secret - NBC News'
[nytimes-harari-ai-chatgpt]: https://www.nytimes.com/2023/03/24/opinion/yuval-harari-ai-chatgpt.html 'Yuval Harari on ChatGPT - NYTimes opinion'
[criticalai-blue-pill]: https://criticalai.org/2023/04/06/noah-giansiracusa-on-you-can-have-the-blue-pill-or-the-red-pill-and-were-out-of-blue-pills-in-the-new-york-times-3-24-2023/ 'Blue pill / red pill - Critical AI'
[newyorker-andy-clark]: https://www.newyorker.com/magazine/2018/04/02/the-mind-expanding-ideas-of-andy-clark 'The mind‑expanding ideas of Andy Clark - The New Yorker'
[history-open-source-llms]: https://cameronrwolfe.substack.com/p/the-history-of-open-source-llms-better 'The history of open‑source LLMs - Substack'
[miro-board]: https://miro.com/app/board/uXjVGtZoflg=/ 'Miro Board'

[berkeley-section-6]: https://celt.ucc.ie/published/E710001-001/text005.html "Berkeley: Principles of Human Knowledge, section 6"
[merleau-ponty-preface]: https://classiques.uqam.ca/classiques/merleau_ponty_maurice/phonomenologie_de_la_perception/phonomenologie_de_la_perception_avant_propos.html "Merleau-Ponty: Preface (French)"
[merleau-ponty-edition]: https://www.routledge.com/Phenomenology-of-Perception/Merleau-Ponty/p/book/9780415834339 "Phenomenology of Perception: publisher's introduction"
