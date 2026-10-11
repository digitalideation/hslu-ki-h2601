# Lecturer's Notes: Session 01

[Student session outline](./session01.md) · [Student workshop](./session01_03_04.md) · [Resource guide](./session01_03.md)

## Purpose and Timing

Session 01 lasts **140 minutes including a 10-minute break**, leaving **130 minutes of teaching**. The perception activities and creative closing occupy 85 minutes after the break.

The recurring question is whether we mean the same thing when we say humans and AI learn or perceive. AI appears first as a system to examine, then as a description students compare with experience, and finally as an interpreter whose claims they check against a source.

Look for students who can make a useful distinction, support it with an observation or source, and explain what remains uncertain. Agreement about whether AI “really perceives” is not required.

## Prepare

- For Part 1, show a few [Session 01 slides](../slides/session01.html) first (9 min), especially the contrast between classical programming and machine learning. Then have students use the two cat images on the [Session 01 page](./session01.md#part-1-ai-learning-20-min) to discuss three simple questions in pairs (7 min), followed by a short class comparison (4 min). Focus on the idea of **programming explicit rules vs. learning patterns from examples**, not technical vocabulary or model evaluation. There is no need for coding or a live demo; leave neural networks and deep learning as optional context.
- For human learning, use the [English Pépin transcript](../slides/static/vids/philo_en.md), from “Well, because we don't know how to do things instinctively” through “So there are virtues in failure.” If playing audio instead, locate the corresponding passage in advance. The selected passage concerns culture and trial and error; there is no need to cover the entire human-learning resource page.
- Treat Pépin's argument as a philosophical proposal to question, not a biological account students must accept. The longer material's numerical claim about walking is not needed for this activity.
- Open the [public course board][miro-board] for the opening work and the [Maurice vs George board][miro-perception] for perception. Provide a small area per group for initial ideas, observations or sources, revised ideas, and open questions. Paper is a fallback.
- Prepare an opaque bag and a few safe objects per pair, or enough sets to share without a long queue. Use objects students cannot already see. Check whether the touch activity is suitable for everyone and prepare an alternative.
- Make [Berkeley's section 6][berkeley-section-6] available on screen or as a short handout. This is the default verification route because it is brief and available in English.
- If using Merleau-Ponty for source verification, prepare the specified [French Preface paragraph][merleau-ponty-preface] or a corresponding English excerpt with edition and page. Otherwise use the short course introduction in Activity 3 and Berkeley for Activity 4.
- If using the NotebookLM podcast, select a 2–3-minute passage beforehand. Use it within the resource time as an alternative explanation, not an additional listening task. Retain the original-source check in Activity 4.
- Check access to the notebooks, boards, and an LLM. Save a short response to each student prompt as a fallback. A shared screen can replace individual accounts.

## Facilitation Schedule

Times are minutes from the start and include transitions and sharing.

| Time | Facilitation | Focus |
| --- | --- | --- |
| 0–5 | 1 minute individual reflection, then 4 in pairs | A concrete learning experience to return to |
| 5–25 | 9 minutes presenting selected slides, 7 discussing three cat-recognition questions in pairs, 4 sharing with the class | Why explicit rules are difficult; how machine learning uses examples; what a mistake means |
| 25–45 | 4 minutes on a group's failure example, 4 with Pépin, 8 comparing, 4 hearing two contrasting positions | What failure means in a human context |
| 45–55 | Break | |
| 55–65 | 7 minutes classifying in pairs, 3 discussing one disagreement | Different criteria for perception |
| 65–80 | 4 minutes responding, 5 with Berkeley, 6 reconsidering and discussing | Room, representation, input, and possible experience |
| 80–100 | 3 minutes with an AI description, 6 experimenting, 4 comparing accounts, 3 with Merleau-Ponty, 4 exchanging with another pair | How AI might influence attention and interpretation |
| 100–120 | 4 minutes generating, 8 checking one claim, 5 revising, 3 exchanging between pairs | A source-based correction or a clearly stated limit |
| 120–140 | 7 minutes sketching, 6 exchanging between groups, 5 in class discussion, 2 writing individually | Connect an investigation to creative practice and revisit initial positions |

## Part 1: Cat Recognition Discussion

Use the image pair to make the limitations of hand-written rules tangible. Ask students to propose simple conditions (`if/else` rules) before discussing how a model might learn from labeled examples. The goal is curiosity, not a correct algorithm.

The images are illustrations, not the tested outputs of an actual model. The task is to identify **real cats** in photographs, so the plush toy is a possible confusing example. Encourage students to suggest their own tricky examples and to explain why they might be hard to classify.

During the four-minute share-out, invite one pair to share a rule and another to explain where it could fail. Ask whether showing a model an example of a mistake automatically makes it learn; if useful, briefly clarify that a trained model does not necessarily update itself when used. Keep testing procedures, detailed distinctions between training and inference, and network architecture out of the required student activity.

End with **"When a computer makes a mistake, does that mean it has learned something?"** Save the deeper comparison with human failure for Part 2.

## Groups and Sharing

Keep stable pairs. Two neighboring pairs form a group of four when needed; adjust to a group of three for odd numbers. In AI tasks, one person operates the tool while the other records observations or checks the source. Swap those roles between Activities 3 and 4.

There are no formal presentations. During class discussion, invite a 30–60-second contribution that adds a disagreement, correction, or changed position. Select contrasting examples rather than hearing a report from every group.

At the end, each group presents its rough idea to another group. Each gets two minutes to explain and one minute for feedback, six minutes total for the exchange. Arrange these group pairings before the closing block. If there is an odd group out, hear its pitch yourself while the others exchange. For a very small class with only one group, hear its pitch and use the remaining time for discussion.

Everyone has a chance to explain work to peers; only a few examples need whole-class attention.

## Activity 3: AI, Attention, and Experience

The default student sequence uses touch recognition. Students read an AI description, try the activity, note observations individually, compare accounts, then bring in Merleau-Ponty. This directly addresses how AI might mediate experience and its interpretation.

Do not treat agreement with the model as a successful outcome. Ask what its account made easier to notice and whether its language shaped students' own descriptions. Separate observation, interpretation, and claims about causation.

An optional variation is to have one partner read the AI description before touching an object and the other read it only afterward. Assign roles before displaying the response, keep it out of the second partner's view, and have both record observations before talking. Use separate unseen objects or reset the bag without revealing its contents. This is an exploratory comparison: differences could also reflect the objects, prior knowledge, order, or individual variation. Do not present it as proof of an AI effect.

### Alternative: Blind Navigation

Replace touch recognition within the same time allocation. In a clear, level space, one volunteer closes their eyes while a partner guides them 3–4 meters with voice instructions. The partner stays within reach; stop whenever either wants to. Participation is voluntary.

Adapt the AI prompt to ask what someone might notice while being guided with eyes closed. Compare the description with observations about movement, trust, and memory of the room. This brief exercise does not reproduce living with blindness.

### Alternative: Design Analogy

For students who prefer a design task, ask the model what a robot would need to find and pick up a coffee cup. Students sketch their own proposal, then remove the robot's ability to move around the cup. Compare what their design and the AI account assume about sensors, action, and success.

This examines assumptions about embodiment rather than comparing a description with lived touch. Keep that distinction explicit when groups share findings.

## Conceptual Guardrails

**Berkeley:** avoid “the world disappears when nobody looks.” His account includes an eternal spirit. The robot is our analogy; a map stored in memory is not automatically a mind or an act of perception.

**Merleau-Ponty:** bodily experience is more than adding sensors. Ask how action and situation shape what appears.

**AI:** distinguish systems and architectures. A stationary classifier, interactive robot, and text-only chatbot do not all have the same access to the world. Separate observable performance from claims about subjective experience.

**Sources:** an LLM speaking “as Berkeley” produces an interpretation. Inspect an underlying passage and distinguish historical claims from speculative applications. NotebookLM can help locate and unpack sources, but a generated answer is not independent confirmation of another generated answer.

## If More Time Is Needed

The first two content blocks are deliberately focused on one example and one short resource each. If technical teaching needs another 20 minutes, move Activity 4 to a later session and use that time earlier. Keep the break, embodied comparison, and closing reflection. Do not squeeze source verification into a vote on which answer sounds convincing.

For smaller overruns, reduce the number of plenary contributions rather than the time needed to read a source. Students can leave with unresolved questions.

## Review After Teaching

Keep a few examples of initial and revised positions, including disagreement. Ask:

- Did a resource change the argument or only add a philosopher's name?
- Could students point to evidence for a claim?
- Did they distinguish an experience from an AI description of it?
- Did the discussion produce a useful creative question?
- Which activity needed more time, and which resource was actually helpful?

[miro-board]: https://miro.com/app/board/uXjVGtZoflg=/
[miro-perception]: https://miro.com/app/board/uXjVIMRGp4w=/?share_link_id=956730497904
[berkeley-section-6]: https://celt.ucc.ie/published/E710001-001/text005.html
[merleau-ponty-preface]: https://classiques.uqam.ca/classiques/merleau_ponty_maurice/phonomenologie_de_la_perception/phonomenologie_de_la_perception_avant_propos.html
