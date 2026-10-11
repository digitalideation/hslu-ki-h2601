# Session 01: Learning, Failure, and Perception

**Big question:** When humans and AI "learn" or "perceive," do we mean the same thing?

Today we explore this through three investigations. **No advance reading or special materials needed.** Work with the same partner, use AI when prompted, and join three short whole-class discussions. You do not have to present a project or submit a report.

**Duration:** 140 minutes, including a 10-minute break.

| Duration | What we'll do | Format |
| --- | --- | --- |
| 10 min | Opening: a learning mistake and a cat-recognition challenge | Pairs |
| 15 min | How machine learning uses examples and feedback | Short introduction + pairs |
| 12 min | Pépin: does failure help humans learn? | NotebookLM + pairs |
| **8 min** | **Discussion 1: What does it mean to learn?** | **Whole class** |
| **10 min** | **Break** | |
| 15 min | Berkeley: if the sensors go dark | Thought experiment + pairs |
| 20 min | Touch recognition and Merleau-Ponty | Physical experiment + pairs |
| **15 min** | **Discussion 2: What does it mean to perceive?** | **Whole class** |
| 15 min | Check one AI interpretation of philosophy | LLM + original source |
| 10 min | Turn a question into a creative idea | Pairs |
| **10 min** | **Discussion 3: What have we learned?** | **Whole class** |

Need more context? The optional [Session 01 resource library](./session01_resources.md) has the notebooks, podcasts, texts, and further readings. **You only need the links mentioned in the activities below.**

## Investigation 1: How do we learn? (45 min)

### 1. Start with a mistake and a cat (10 min)

Think of one thing you learned through trial and error. Tell your partner what actually helped you improve.

Now imagine programming a system to identify **real cats** in photos, not plush toys.

| Real cat | Plush cat |
| :---: | :---: |
| <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Tabby_cat_on_a_chair_%28Unsplash%29.jpg?width=480" width="230" alt="Real tabby cat"> | <img src="https://commons.wikimedia.org/wiki/Special:FilePath/TCMI_Cheshire_Cat_2.jpg?width=480" width="230" alt="Plush Cheshire cat toy"> |

*Images: [Sarah Dorweiler (CC0)](https://commons.wikimedia.org/wiki/File:Tabby_cat_on_a_chair_%28Unsplash%29.jpg) and [Daniel Schwen (CC BY-SA 3.0)](https://commons.wikimedia.org/wiki/File:TCMI_Cheshire_Cat_2.jpg). These are examples, not outputs from a classifier.*

**In pairs:** What rules would you write? Where might those rules fail?

### 2. Learning from examples (15 min)

Follow a short selection from the [AI Learning slides](../slides/session01.html). Compare two approaches:

- **Explicit programming:** people write rules to recognize a cat.
- **Machine learning:** a model is trained on examples and feedback.

Return to your cat rules. What examples would help a model improve? **If a model makes a mistake, does that automatically mean it learns from it?**

### 3. Human learning: Pépin (12 min)

Open the [Human Learning NotebookLM](https://notebooklm.google.com/notebook/f147adf8-e289-4bc4-938e-350a61e5a484) with your partner and ask:

> Why does Charles Pépin think failure can be useful for learning? Give one example from the provided sources.

Compare his argument with your own learning experience. What role did feedback, other people, or repeated attempts play? Do you agree that failure is useful?

If NotebookLM is unavailable, use the [short transcript section on culture and failure](../slides/static/vids/philo_en.md#learning-through-culture-and-failure).

### Discussion 1: What does it mean to learn? (8 min)

**Is making a mistake enough to learn something, for a human or for a machine?**

We'll hear a few different answers and connect them to examples, feedback, and context. No pair presentations.

**Break (10 min)**

## Investigation 2: What does it mean to perceive? (50 min)

### 4. Berkeley: If the sensors go dark (15 min)

Imagine a robot with a camera and a saved map of a room. Its camera is disconnected, but its computer still runs.

**Does its world still exist?** Distinguish the physical room, the map in memory, and the robot's current access to the room. Does your answer change if the computer is switched off but the map remains stored?

Discuss your initial answer before opening [Berkeley's *Principles*, section 6](https://celt.ucc.ie/published/E710001-001/text005.html). Berkeley questions whether sensible objects exist independently of perceiving minds, but he does **not** say that a room disappears when one person leaves it; his account also invokes an eternal spirit.

**Reconsider:** Does the stored map count as perception? Which part of your answer is a technical claim, and which is a philosophical interpretation?

### 5. Touch recognition: experience vs. description (20 min)

First, ask an LLM:

> How might someone identify a familiar object using only touch? Describe the hand movements and clues in under 100 words.

Then **try it yourselves**. Use safe, everyday objects you already have (for example, a pen, eraser, keyring, or charging cable). One partner selects an object and keeps it out of sight; the other closes their eyes, explores it by touch, and guesses. Swap roles using another object. Only share or touch objects you're comfortable with.

Each partner notes **one observation** before comparing: What did moving your hand reveal? What did you recognize before you could describe it?

Compare these observations with the LLM's description. What did it capture, miss, or make you notice?

**Merleau-Ponty's idea:** Perception is shaped by our lived bodily involvement in the world, not simply by receiving measurements. Does your experiment help explain that idea? Would a robot reproducing your movements necessarily have your experience?

If the touch exercise is not suitable, sketch how a robot would find and pick up a cup; then remove its ability to move and reconsider the design.

### Discussion 2: What does it mean to perceive? (15 min)

**What did the experiment reveal that a description or a stored map cannot necessarily capture?**

We'll compare a few observations and connect them to Berkeley and Merleau-Ponty. Can a machine reproduce perceptual behavior without sharing human experience? What evidence would we need to make a stronger claim?

## Investigation 3: How does AI shape our understanding? (35 min)

### 6. AI as an interpreter (15 min)

Ask an LLM:

> Explain how Berkeley's account of perception might help us question the robot with its camera disconnected. Keep it under 120 words. Separate Berkeley's own claims from your interpretation about AI.

Choose **one claim** from its answer. Look for support or a limitation in [Berkeley's *Principles*, section 6](https://celt.ucc.ie/published/E710001-001/text005.html). If you need help locating the passage, use the [Perception NotebookLM](https://notebooklm.google.com/notebook/af5ed21e-57cd-4d0a-b2a1-8c96e3e75d74), but check the original text yourself.

With your partner, finish these sentences:

- "The AI claimed..."
- "The source supports / complicates / does not settle this because..."
- "We would say it more carefully as..."

Agreement between two AI tools is not the same as checking a source.

### 7. A creative response (10 min)

Sketch or briefly describe an artwork, interface, or robot that lets people explore **one question** from today's investigations.

What does someone do? What does the system detect or respond to? What might participants discover or question? Use an observation or argument from the session to guide one design choice.

A rough sketch or a few sentences is enough.

### Discussion 3: What have we learned? (10 min)

**Did AI help us understand the world, or did it also influence how we described and interpreted it?**

We'll hear two or three ideas or disagreements. Then revisit the opening question about human and AI learning and perception.

To finish, write just three short lines for yourself: **I first thought... / I now think (or still think)... / I am unsure about...**

---

**Optional follow-up:** Explore the [resource library](./session01_resources.md) or add a question to the [Maurice vs George Miro board](https://miro.com/app/board/uXjVIMRGp4w=/?share_link_id=956730497904). You don't have to use Miro to complete the session.

[Back to the course homepage](../readme.md)
