# Italian Course — Learn, Practise, Review

An open, Markdown-based Italian study kit. This repository contains reusable learning notes, original practice activities, and templates for independent study or AI-assisted tutoring.

**How it works:** choose a topic → study one concept → practise without looking at answers → review mistakes → revisit the material later. Use GitHub to keep explanations and exercises organized and version-controlled. Optionally use a calendar to reserve study time and ChatGPT (or another tutor) for interactive feedback.

> [!IMPORTANT]
> **Privacy:** This repository is **public**. Do not commit personal schedules, certification plans or deadlines, exam registration information, assessment scores, individual learning history, private conversations, real identifying details, or confidential work material. The files `PROGRESS.md` and `reviews/queue.md` are **blank public templates**, not places to store your real progress. Keep personalized records in a **separate private repository** or a local folder outside this checkout.

## Table of contents

1. [Who this course is for](#who-this-course-is-for)
2. [How the learning method works](#how-the-learning-method-works)
3. [Set up your environment](#set-up-your-environment)
4. [Get started in 10 minutes](#get-started-in-10-minutes)
5. [Use the repository](#use-the-repository)
6. [Run a learning session](#run-a-learning-session)
7. [Use GitHub and contribute](#use-github-and-contribute)
8. [Use a calendar (optional)](#use-a-calendar-optional)
9. [Keep private progress records](#keep-private-progress-records)
10. [FAQ and troubleshooting](#faq-and-troubleshooting)

## Who this course is for

- Beginner Italian learners who want a structured but flexible path.
- Learners who prefer practice, self-testing, conversations, and review over passive reading.
- People who want versioned Markdown notes they can access from a browser, editor, or AI tutor.

The [roadmap](curriculum/roadmap.md) is a **generic suggestion**, not a personalized syllabus or a substitute for an official exam specification. You can skip topics you already know, revisit difficult ones, and select your own pace.

## How the learning method works

A study cycle has six parts:

1. **Choose a mission:** pick one small topic from the [roadmap](curriculum/roadmap.md), such as greetings, noun gender, or present-tense verbs.
2. **Learn:** read an original explanation in [grammar](grammar/README.md) or [vocabulary](vocabulary/README.md). Consult your own legitimately obtained textbooks if you have them.
3. **Retrieve:** hide the explanation and answer a question or produce sentences independently. Recognition alone is not mastery.
4. **Speak and shadow:** imitate a short, legally accessible Italian audio clip using the [five-pass shadowing method](shadowing/README.md), then create new sentences.
5. **Apply:** complete a simple role-play, reading task, or short writing activity. Use fictional details in any public examples.
6. **Review:** revisit difficult material after increasingly long intervals; see [spaced repetition](reviews/README.md).

**Suggested session format (adjust freely):**

| Part | Example duration | What to do |
|---|---:|---|
| Retrieval warm-up | 5 min | Recall vocabulary and grammar without notes |
| New topic | 15 min | Read one explanation and a few examples |
| Active practice | 15 min | Answer questions and write original sentences |
| Shadowing / speaking | 10 min | Listen, echo, shadow, transform |
| Check and review | 5 min | Correct answers and decide what to revisit |

The course may use **XP** as an optional motivational game mechanic. Points do not establish language proficiency. Example XP suggestions are in [AGENTS.md](AGENTS.md); keep **earned** XP and individual results private.

## Set up your environment

You have two options. **No coding experience is required.**

### Option A — Browser only (easiest)

Requirements:

- A web browser
- A free [GitHub account](https://github.com/signup) if you want your own repository
- A notebook or private document for your real answers and results
- Optional: ChatGPT, another AI assistant, or a teacher

Steps:

1. Browse the [repository files](https://github.com/pmembari/italian-course).
2. Start at [curriculum/roadmap.md](curriculum/roadmap.md) and choose a topic.
3. Open the matching note or exercise.
4. Write your answers **privately** (not in a public GitHub issue or discussion).
5. Return for review; optionally use the [lesson template](lessons/TEMPLATE.md) in a private document.

If you want to customize materials without changing this public repository, use GitHub's **Use this template** button *if enabled*, or create a **new private repository** and copy only the public-safe templates you need. A fork may be public; **check its visibility before adding personal records**.

### Option B — Local Markdown workspace (recommended for frequent editing)

Install:

- [Git](https://git-scm.com/downloads) — version control
- [Visual Studio Code](https://code.visualstudio.com/) — Markdown editor (any text editor works)
- Optional: [GitHub CLI](https://cli.github.com/) for authentication and pull requests
- Optional: ChatGPT or a coding assistant for tutoring and drafting
- Optional: audio player and headphones for shadowing

Clone this **public learning-material repository** in a terminal:

```bash
git clone https://github.com/pmembari/italian-course.git
cd italian-course
code .
```

If `code .` is not recognized, open the folder manually in your editor. In VS Code, select a Markdown file and use **Open Preview** (`Ctrl+Shift+V` on Windows/Linux, `Cmd+Shift+V` on macOS).

To receive later updates:

```bash
git pull --ff-only
```

**Keep private journals outside this cloned directory**, for example in a separate local folder or a distinct private repository. Files under this directory can accidentally be staged and pushed to the public repository.

### Optional — Create a private learning journal

For personal progress, create a separate repository with **Private** visibility. Copy the **blank templates** you want from this repository into that private location, then fill them in there. Do not copy personal data back to the public repo.

If using an AI tutor or GitHub integration, make sure it has access to the intended private repository. A connected app is not automatically authorized to read every repository.

## Get started in 10 minutes

1. Read the [generic roadmap](curriculum/roadmap.md) and pick a topic.
2. Open [Presentarsi — sample vocabulary](vocabulary/001-presentarsi.md) for introductory phrases.
3. Without looking, write three **fictional** introduction sentences in Italian in your private notes.
4. Check the examples and identify which verbs or constructions you need to study.
5. Try an original speaking or writing exercise based on the same topic.
6. Put any personal corrections and next-review dates in your **private** journal.

If you prefer live tutoring, give your AI assistant a prompt such as:

> Act as my interactive Italian tutor. Use the public materials in https://github.com/pmembari/italian-course as reference. Teach one concept at a time, ask me to answer before showing solutions, correct my Italian, and suggest a short shadowing task. Do not publish my responses, progress, exam plans, or personal information to the public repository. If I want persistent personal records, confirm a private destination first.

## Use the repository

| Path | Purpose | What belongs there |
|---|---|---|
| [`curriculum/`](curriculum/roadmap.md) | Topic roadmap and source-reference templates | General learning sequences; verified page references |
| [`lessons/`](lessons/README.md) | Lesson templates and general examples | Original, reusable lessons — **not identifiable session logs** |
| [`vocabulary/`](vocabulary/README.md) | Thematic word lists | Meanings and original example sentences |
| [`grammar/`](grammar/README.md) | Grammar explanations | Concise rules and original exercises |
| [`shadowing/`](shadowing/README.md) | Pronunciation and listening practice | Methods and authorized source links |
| [`mistakes/`](mistakes/README.md) | Common error patterns | Fictional/anonymized examples, never an individual's error log |
| [`exams/`](exams/README.md) | General practice tests | Original exercises and blank diagnostic templates |
| [`reviews/`](reviews/README.md) | Review methods | Blank queues and general recall strategies |
| [`PROGRESS.md`](PROGRESS.md) | Checkpoint template | **Blank template only** in this public repository |
| [`AGENTS.md`](AGENTS.md) | Instructions for AI assistants | Tutoring and privacy rules |

Markdown is plain text: `# Heading`, `- item`, `**bold**`, and `[link](path)` are enough for most edits. GitHub previews Markdown automatically.

## Run a learning session

**Before**

1. Decide what skill to practise (e.g., introduce a fictional character, ask directions).
2. Read related course notes.
3. In your **private** notes, look up outstanding review items and set a small objective.

**During**

1. Try to answer independently before viewing explanations.
2. Practise producing Italian, not only translating it.
3. Use a short, authorized audio recording for shadowing when available.
4. Ask your tutor for corrections and short explanations.

**After**

1. Summarize the grammar or vocabulary in your own words.
2. Write **general, non-personal** example content here only if it would help other learners.
3. Save your real answers, errors, practice duration, scores and spaced-repetition queue **privately**.
4. Choose the next topic; do not equate a scheduled session or a Git commit with mastered material.

### Working with an AI assistant

At the start of a chat: give it the repository URL, ask it to read [AGENTS.md](AGENTS.md), and specify the topic.

At the end of a chat: ask for a recap and general exercises. If you want the assistant to save personalized results, it must use a **verified private repository or another private storage destination**. No automatic saving is implied by chatting; confirm that each write actually succeeded.

## Use GitHub and contribute

The public repository is for reusable learning resources. You can propose corrections, original exercises, clearer explanations, or accessible source links.

1. Before editing, pull the latest changes (`git pull --ff-only`).
2. Create a topic branch:
   ```bash
   git switch -c docs/improve-present-tense
   ```
3. Edit the relevant Markdown file. Preview it and check grammar, links, and privacy.
4. Review your changes:
   ```bash
   git status
   git diff
   ```
5. Stage **only** the public-safe files you intend to contribute:
   ```bash
   git add grammar/README.md
   git commit -m "docs: clarify present-tense examples"
   ```
6. Push the branch (`git push -u origin docs/improve-present-tense`) **only if you have push permission**; otherwise create your own fork and open a pull request from it.
7. Open a pull request to `main`. Review the changed-file diff again before publication.

If you only use the browser, you can also propose an edit with GitHub's pencil icon and open a pull request.

**Contribution checklist:** no personal information, no private chat text, no real assessment results, no copyrighted textbook scans or long reproduced passages, no unauthorized audio, and no secrets or tokens.

## Use a calendar (optional)

Calendar and GitHub solve different problems:

| Tool | Responsibility |
|---|---|
| Calendar (Google Calendar or another app) | Remind you **when** to study |
| This repository | Provide reusable materials for **what** to study |
| Private notes or private repository | Record what **you personally** practised and need to review |
| Tutor or AI assistant | Explain, quiz, converse, and give feedback |

To set up a calendar:

1. Create a recurring event named something generic, e.g., **Italian practice**.
2. Choose a frequency and duration that fits your own schedule.
3. Include a link to [this repository](https://github.com/pmembari/italian-course) in the event description.
4. Configure reminders in your calendar.
5. At study time, open the event and choose a topic from the roadmap.

**There is no automatic Calendar ↔ GitHub synchronization in this repository.** Calendar events do not prove a lesson was completed, and Git commits do not automatically update calendar events. Use integrations only after explicitly setting them up and reviewing their permissions.

## Keep private progress records

Recommended private-only files:

```text
my-italian-journal/           # Different private repository or local folder
├── PROGRESS.md               # Current checkpoint
├── lessons/                  # Personal session notes
├── mistakes/                 # Actual errors and corrections
├── reviews/queue.md          # Due reviews
└── assessments/              # Individual scores and feedback
```

You can copy the **blank** [checkpoint template](PROGRESS.md) and [review queue template](reviews/queue.md) into that private location.

**Do not publish private data here, even in Git history:** deleting it in a later commit may not remove earlier copies.

## FAQ and troubleshooting

**Do I need Git or programming experience?**  
No. The browser-only workflow requires no Git installation. Git is useful for people who want to edit notes locally or contribute.

**What if `git clone` fails?**  
Check your connection and the repository URL, and [install Git](https://git-scm.com/downloads). You can still browse and download public Markdown files from GitHub.

**What if `git push` says "permission denied"?**  
You probably do not have write access to the upstream repository. Use a fork for public contributions or push to a repository you own. Never push a private journal to a public fork.

**Where do I write my actual mistakes or exam scores?**  
In a private repository or local journal, not in this public project.

**Does GitHub save everything from ChatGPT automatically?**  
No. Saving requires an explicit authorized write and verification. A summary in chat is not a committed file.

**Can I upload my textbook PDFs?**  
Only if you have permission to distribute them. Usually it is safer to keep copies privately and link to bibliographic details or checked page references rather than upload copyrighted materials.

**Can I use a different study schedule or exam path?**  
Yes. The course is flexible and does not presume a learner's personal goals, timeline or certification choices.

---

**Next step:** open [the roadmap](curriculum/roadmap.md), pick a topic, and complete one short interactive practice session.
