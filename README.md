# Wáàlá.dev – Learn Code Anywhere

> **Wáàlá** means *"You will succeed"* in Yorùbá. This repository is the public home for everything we teach on [waala.dev](https://www.waala.dev): the mission, the learning flow, and a transparent breakdown of our Python for Kids & Beginners curriculum with practice-ready examples.

## Why this repo exists

- 📣 **Open story:** Explain what the app does, who it serves, and why we obsess over mobile-first learning.
- 🧭 **Curriculum tree:** Show parents, teachers, and partners how each topic stacks on the previous one.
- 🧪 **Practice-first:** Publish real exercises, snippets, and walkthroughs you can run on any phone or browser.
- 🤝 **Community-friendly:** Make it easy to request lessons, report bugs, and share wins without digging through private code.

## What is Wáàlá?

| Pillar | What it means |
| --- | --- |
| **Phone-first** | Every lesson runs beautifully on a smartphone. No laptop, no downloads, no excuses. |
| **3-minute episodes** | Short, focused drops. Learn before school, during lunch, or on the bus. |
| **Real Python** | We teach the actual language used at Google, NASA, and Instagram—explained like you're brand new. |
| **Beginner love** | Ages 7+ to adults starting over. No jargon, no shame, no gatekeeping. |
| **Global mindset** | Designed for London, Lagos, Manchester, Nairobi, and everywhere in between. Low-bandwidth friendly. |

## Learning flow (high-level)

```
Start ➜ Pick a Track ➜ Daily 3-min Episode ➜ Practice Question ➜ Micro Project ➜ Reflection + Streak ➜ Share/Remix ➜ Next Episode
```

### Tree of the app experience

```
waala.dev
├── Hero & Waitlist
├── Learn (tracks)
│   ├── Python Basics (live)
│   ├── AI Sprints (coming soon)
│   ├── Web Studio (coming soon)
│   └── Data Story (coming soon)
├── Episodes (day-by-day lessons)
├── Library (deep dives + examples)
├── Mission / Vision / FAQ
└── Blog + Community updates
```

### Repository map (public docs)

```
waala-dev/
├── README.md  (you are here)
├── app-notes/ (copy for public pages: mission, vision, faq, etc.)
├── curriculum/
│   └── python-for-kids/
│       ├── week-01-intro-to-python/
│       │   ├── README.md            # learning goals + recap questions
│       │   ├── practice/            # mcq, predict output, debug, rearrange
│       │   └── micro-projects/      # tiny builds you can ship in minutes
│       ├── week-02-variables-and-data/
│       ├── ...
│       └── week-06-mini-projects/
├── practice-lab/                    # runnable snippets + solutions
└── community/
    ├── requests.md                 # lesson ideas & shoutouts
    └── contributors.md             # how to help
```

> The tree above is the structure we publish as we migrate materials from the internal monorepo. Feel free to open issues suggesting improvements or requesting topics.

## Python for Kids & Beginners (Flagship Track)

**Duration:** 42 days · **Daily Time:** 3 minutes (episode) + 5 minutes practice · **Prereqs:** curiosity only.

| Week | Theme | Core Topics | Practice Snapshot |
| --- | --- | --- | --- |
| 1 | Getting Comfortable | `print()`, storytelling with code, mindset | ```python
print("Hello, I'm Zara")
print("I learn in 3 minutes a day")
```
|
| 2 | Variables & Data Types | Strings, ints, floats, conversions | ```python
name = "Sade"
age = 11
future_age = age + 5
print(f"Hey {name}, you'll be {future_age} soon!")
```
|
| 3 | Inputs & Decisions | `input()`, type casting, `if/else` | ```python
score = int(input("Quiz score? "))
if score >= 10:
    print("Legend status unlocked!")
else:
    print("Try again, champion.")
```
|
| 4 | Loops & Collections | `for`, `while`, lists, slicing | ```python
playlist = ["Afrobeats", "Grime", "Jazz"]
for track in playlist:
    print("Now playing:", track)
```
|
| 5 | Functions & Reuse | Parameters, return values, scope | ```python
def hype(name):
    return f"{name}, you will succeed."

print(hype("Ngozi"))
```
|
| 6 | Mini Projects | Quiz apps, calculators, streak trackers | ```python
print("Habit Tracker")
streak = int(input("Days coded this week: "))
if streak >= 4:
    print("🔥 Keep going!")
else:
    print("Start a new streak today.")
```
|

### Episode anatomy (applies to every topic)

1. **Hook (20 sec):** relatable story or question.
2. **Concept drop (60 sec):** one idea, zero fluff.
3. **Code walkthrough (60 sec):** show + run + explain.
4. **Practice prompt (1–2 min):** MCQ, predict output, debug, rearrange.
5. **Mini challenge:** something they can brag about immediately.

### Practice formats we publish

- **MCQ:** Check concept understanding quickly.
- **Predict the output:** Read code, imagine the console, gain confidence.
- **Debug me:** Spot-fix real mistakes to build resilience.
- **Rearrange:** Drag-and-drop style thinking—great for younger learners.
- **Short answer:** Explain in your own words; clarity beats memorization.

## Example detailed topic: Week 2 – Variables

**Objective:** Name things clearly, store information, update values, and understand types.

**Flow:**
1. **Story:** “If your backpack could talk, what would it remember?”
2. **Teach:** `name = "Maya"`, best practices (`snake_case`, no spaces, no starting numbers).
3. **Run:** Update values, concatenate strings, convert user input to integers.
4. **Practice:**
   - MCQ → *Which variable name is valid?*
   - Predict → `x = 5; x = x + 2; print(x)` → `7`
   - Debug → remind learners to wrap strings in quotes.
   - Rearrange → order lines to print "Python Rules".
5. **Challenge:** Build a “Dream Board” that stores three variables and prints them creatively.

```python
hero = "Grandma"
dream_job = "Software Artist"
fav_food = "Jollof"

message = f"{hero} says I can be a {dream_job} who still enjoys {fav_food}."
print(message)
```

## Coming next

1. **AI Sprints:** GenAI prompts + Python tooling to build copilots from a phone.
2. **Web Studio:** HTML, CSS, Tailwind, and interactive components that feel premium on mobile.
3. **Data Story:** Python + Pandas visual storytelling for early-career analysts.

> Want to vote on what ships next? Open an issue titled `Course Request: <topic>` and tell us why it matters.

## Contributing

1. **Fork** this public repo.
2. **Add** practice ideas, explainers, or translations under the relevant week/topic folder.
3. **Open a PR** with screenshots or Loom clips if possible.
4. **Be human:** Our tone is hopeful, clear, and culturally rich.

Questions? DM [@waala_dev](https://www.youtube.com/@waala_dev), email `michael.adeleye@waala.dev`, or start an issue titled `Question: …`.

Together, we’ll turn every phone into a coding classroom.
