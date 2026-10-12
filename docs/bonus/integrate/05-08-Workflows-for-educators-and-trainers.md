# Chapter 5.8: Workflows for educators and trainers

Teaching and training take a lot of preparation. For every hour in front of learners, there are plans to write, materials to make, activities to design, and versions to adapt for people who learn at different speeds. Copilot can produce a first draft of almost any of these. What it produces has to be right, because learners trust what they're taught and often can't tell when it's wrong. It also has to be usable by every learner, and it has to fit the rules of your school, college, or organization. In this chapter, you'll see three workflows for developing plans and supporting materials, adapting explanations and practice activities, and checking the result. By the end, you'll have a session plan with a handout and a set of practice questions, checked for accuracy and accessibility.

> **Plan note**: These workflows use Chat, Word, PowerPoint, and file uploads, which work with every plan covered in this book. If you work in a school, college, or university, your institution decides which Copilot features staff and students may use, and many have a policy on AI. Read it before you start. Copilot for students has age limits set by Microsoft and by your institution.

## Where Copilot fits in teaching and training

| Copilot helps with | Keep with yourself |
| --- | --- |
| Drafting a session plan from learning objectives | Choosing what to teach, and in what order |
| Producing handouts, slides, and examples | Checking that every fact and answer is right |
| Rewording an explanation for a different level | Knowing which learner needs which version |
| Writing practice questions with answers | Assessing learners' work, and grading |
| Suggesting activities and discussion questions | Feedback to an individual learner |
| Checking materials for reading level and accessibility | Decisions about a learner's progress or support |

## Workflow 1: Develop plans and supporting materials

A good session starts from what learners should be able to do by the end. Give Copilot that, and it can draft the structure around it.

| | |
| --- | --- |
| **When** | Planning a lesson, a workshop, or a course |
| **Inputs** | The learning objectives, the syllabus or specification, the time available, what learners already know, and your own source materials |
| **Tool** | Copilot Chat for the plan. Word for handouts (Chapter 2.3). PowerPoint for slides (Chapter 2.6) |
| **Check** | Every fact, example, and answer. The fit with the syllabus. The timing |
| **Stays with you** | What to teach, and your knowledge of the group |

Ask for a session plan built from objectives and your own material:

```
Draft a plan for a [length] session on [topic] for [learners: age or role, and what they already know]. By the end, learners should be able to: [two or three objectives]. Base the content on the attached [syllabus extract or source material] and don't go beyond it. Give a timed outline with: a short starter that checks what learners already know, the main explanation in steps, one activity where learners practice, and a way to check understanding at the end. For each part, say what the learners are doing, not only what I'm doing.
```

Starting from objectives and your own sources keeps the session on the syllabus. Without them, Copilot will write a general lesson on the topic, which may cover the wrong content at the wrong depth.

From the plan, ask for the materials one at a time:

- `Write a one-page handout for learners that covers the main explanation. Use short sentences and one worked example.`
- `Create six slides for this session. One idea on each slide, with no more than 20 words.`
- `Suggest three discussion questions that have more than one reasonable answer.`

You know things that the plan can't: that this group is tired on a Friday afternoon, that two learners missed last week, that the room has no projector. Adjust the plan to the people in front of you.

## Workflow 2: Adapt explanations and practice activities

Learners in the same room are rarely at the same level. Preparing several versions of one explanation takes time that few teachers have. This is one of the most useful things Copilot does in this role.

| | |
| --- | --- |
| **When** | A group has mixed levels, or a learner needs a different approach |
| **Inputs** | Your original explanation or activity, and a description of what the learner or group needs |
| **Tool** | Copilot Chat |
| **Check** | That each version is still accurate, and still teaches the same thing |
| **Stays with you** | Deciding who gets which version, and how to offer it |

Ask for the same content at different levels:

```
Here is my explanation of [concept]: [paste it]. Write three versions that teach the same idea:
1. For a learner who's new to the topic, with everyday words, one concrete example, and no technical terms without a definition.
2. For a learner who's ready for more, with the precise terms and one extension question.
3. For a learner whose first language isn't English, with short sentences, common words, and no idioms.
Keep the facts identical in all three.
```

Practice questions adapt in the same way:

```
Write eight practice questions on [topic], based only on the attached material. Start with two that check recall, then four that ask learners to apply the idea, then two that ask them to explain or compare. Give the answer to each, with the working shown, and say which part of the material it comes from.
```

Check every answer yourself before learners see it. Copilot makes mistakes in worked answers, especially in mathematics, science, and anything with several steps. A wrong answer in an answer key teaches the mistake to every learner who trusts it.

Describe what a learner needs without identifying them. "A learner who reads slowly and loses track of long instructions" gives Copilot what it needs. A name, a diagnosis, or a home circumstance doesn't belong in a prompt.

> **Watch out**: A simplified explanation can become a wrong one. In making an idea easier, Copilot may drop a condition, or use an analogy that misleads. Compare each adapted version with your original, and ask yourself whether a learner who believed the simple version would have to unlearn something later.

## Workflow 3: Check accuracy, accessibility, and institutional policy

Materials for learners need three checks before use.

| | |
| --- | --- |
| **When** | Before any material reaches learners |
| **Inputs** | The material, your sources, and your institution's policies |
| **Tool** | Copilot Chat for a first pass. The accessibility checker in Word and PowerPoint |
| **Check** | The three checks below |
| **Stays with you** | The final judgment on each |

**Accuracy.** You're the subject expert. Read the material as a learner would, and check:

- Every fact, date, name, formula, and definition against a source you trust.
- Every worked example and answer, by working it through.
- Every reference or reading suggestion. Copilot can invent a book or a paper, as Chapter 1.1 warned.
- Whether the material is current. A model's knowledge has a cut-off date.

**Accessibility.** Every learner should be able to use the material.

- Run **Check Accessibility** on the **Review** tab in Word and PowerPoint.
- Add alt text to images and diagrams, as in Chapter 2.8.
- Use heading styles, so that screen readers can navigate.
- Check contrast and font size. Don't rely on color alone to carry meaning.
- Ask Copilot about reading level: `What reading level is this handout? List the sentences and words that are hardest, and suggest simpler versions.`
- Provide captions or a transcript for any audio or video.

**Institutional policy.** Check your institution's rules on:

- Which AI tools staff may use, and for what.
- What must never be entered into an AI tool. This usually includes learners' names, work, grades, and any personal or safeguarding information.
- Whether you should tell learners or parents that AI helped to prepare materials.
- How AI may be used in assessment. Many institutions don't permit AI to grade work or to give feedback that counts toward a result.
- Copyright. Uploading a whole textbook chapter or a paid resource may breach its license.

## Keep assessment and learners' data with people

Two boundaries apply in this role.

**Assessment is a judgment about a person.** Grading a learner's work, deciding whether they've passed, and writing a report about them are decisions with consequences. Keep them with a qualified person. You can use Copilot to draft a marking guide from your criteria, or to produce a bank of general feedback comments that you choose from and edit. Don't paste a learner's work into Copilot to ask for a grade.

**Learners' data needs strong protection**, and more so for children. Don't put a learner's name, work, results, behavior, health, or home situation into a prompt. If your institution provides an approved tool with specific protections for this purpose, follow its rules exactly.

There's also a wider question of how your learners use AI themselves. That's a matter for your institution's policy and your own teaching. If you permit it for a task, say plainly what's allowed, and design the task so that learners still have to think.

> **Good practice**: Teach from materials you could explain without them. If Copilot produces an activity or an example that you don't fully understand, don't use it. Learners will ask questions, and "the handout says so" isn't an answer.

## Try it now

Prepare one session with a plan, a handout, and practice questions, and check them:

1. Choose a session you'll teach or deliver soon. Write its two or three learning objectives.
2. Gather your source material for the topic.
3. Send the session plan prompt from this chapter. Adjust the timings and the activity to suit your group.
4. Ask for a one-page handout based on the plan.
5. Send the practice questions prompt. Work through every answer yourself, and correct any that are wrong.
6. Take one explanation from the handout, and send the three-level prompt. Compare each version with your original for accuracy.
7. Open the handout in Word, and run **Check Accessibility**. Add alt text and heading styles where needed.
8. Read your institution's AI policy, and note anything in your materials or your process that it affects.

You should now have a timed session plan, a handout, eight practice questions with answers you've checked, three versions of one explanation, and a handout with no accessibility problems.

> **What to ask next**: Ask Copilot where learners are likely to go wrong: `What are the most common misunderstandings that learners have about [topic]? For each one, suggest a question I could ask that would reveal it.`

### Check the result

- [ ] Did you work through every answer in the practice questions yourself?
- [ ] Do the three versions of the explanation all state the same facts?
- [ ] Does the handout pass the accessibility check, with alt text and heading styles?
- [ ] Is every prompt you sent free of learners' names, work, and personal details?

> **Real-world example**: A trainer who runs health and safety courses for a building company asks Copilot for a quiz on working at height. One answer gives a maximum ladder height that he doesn't recognize. He checks the current regulations, and finds that the figure comes from guidance that was replaced several years ago. He corrects the answer, and adds a line to his prompt: "Use only the attached current regulations. Don't use general knowledge." He now checks every figure in a quiz against the regulations before each course.

Teachers and trainers often work within an institution's rules. The next group of roles often work alone, for several clients at once, with nobody else to set the rules for them. [*Chapter 5.9, Workflows for writers, researchers, consultants, and freelancers*](05-09-Workflows-for-writers-researchers-consultants-and-freelancers.md), covers research, drafting, and protecting what belongs to your clients and to you.

[Go to next chapter >>](05-09-Workflows-for-writers-researchers-consultants-and-freelancers.md)
