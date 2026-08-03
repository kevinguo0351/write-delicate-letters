---
name: write-delicate-letters
description: Write, rewrite, or refine original Chinese personal letters with emotionally precise detail, sincerity, restraint, and a lingering ending. Offer three context-fit writing routes when the user wants to choose among 直白、含蓄、诗性、日常、机智、炽热或思辨 styles. Also turn highly oral journals or voice notes into an impressive, visibly prepared letter through the optional 郑重成章 personal overlay. Use for 情书、感谢信、道歉信、告别信、安慰信、纪念信, letters to family, friends, partners, former partners, or oneself, voice-note-to-letter editing, and removing generic AI tone.
---

# Write Delicate Letters

Turn lived details into an original Chinese letter that feels observed rather than generated. Preserve the user's emotional truth; improve its precision, rhythm, and aftertaste.

## Load the right references

- Read [references/style-patterns.md](references/style-patterns.md) before drafting or revising any letter.
- Read [references/style-library.md](references/style-library.md) whenever the user has not fixed a style, asks for options, names an admired writer or letter tradition, or wants 直白、委婉、诗性、炽热、日常、机智、思辨等不同写法.
- Read [references/lyrical-mode.md](references/lyrical-mode.md) when the user wants 更文学、更诗性、像散文式情书, supplies voice-transcribed reference samples, or wants emotion carried by seasons, objects, or recurring address.
- Read [references/examples.md](references/examples.md) when the user asks for examples, the input is sparse, or the first draft feels generic.
- Read [references/prepared-sincerity.md](references/prepared-sincerity.md) when the user asks for “我的升级版风格”, “impressive”, “看得出认真准备过”, “更正式但真诚”, or wants to turn a diary-like, highly oral draft into a composed literary letter.
- Give the user [references/standalone-prompt.md](references/standalone-prompt.md) when they explicitly want a portable prompt for another model.

## Follow the workflow

### 1. Identify the letter's emotional job

Determine:

- recipient and relationship;
- occasion or pressure point;
- what must finally be said;
- what the recipient should feel after reading;
- whether the user wants repair, gratitude, confession, comfort, remembrance, encouragement, or release.

Do not confuse the topic with the emotional job. “写给妈妈” is a topic; “让她知道我记得她那些没有被感谢的小事” is the job.

### 2. Offer three writing routes when choice is useful

If the user asks to choose a style or has not fixed one, do **not** draft the full letter yet. Use [references/style-library.md](references/style-library.md) to return exactly three compact route cards labeled A/B/C. Each card must combine:

- the emotional job or letter type;
- one named style variant;
- the reading effect in one sentence;
- a tiny structural preview, not a finished paragraph.

Select routes that would produce meaningfully different letters, usually one from each family: **赤诚直给**, **含蓄映照**, and **深情思辨**. Tailor the three routes to the user's relationship and boundary; do not dump the entire library.

Wait for the user's A/B/C choice. If the user says “直接写,” has already named a route, or needs an immediate draft, skip the menu and draft. Default to **日常知己** for warm relationships, **物件回声** for gratitude or apology, and **清醒自白** for difficult love or farewell.

### 3. Build a detail bank

Extract three kinds of evidence from the user's material:

1. **Scene** — a time, place, gesture, object, sound, temperature, or unfinished action.
2. **Change** — what the writer understood then versus now.
3. **Cost** — what the recipient quietly carried, gave up, protected, or endured.

If the user has already supplied enough detail, draft immediately. If the input is too abstract to support a truthful letter, ask at most three compact questions in one message. Prefer questions such as:

- “你一想到对方，最先出现的是哪个很小的画面？”
- “有没有一句当时没说、现在仍卡在心里的话？”
- “你希望对方读完更靠近你，还是更轻松地离开？”

If the user needs an immediate draft, state minimal assumptions and use restrained, replaceable details rather than inventing dramatic history.

### 4. Choose a register

Select one register from the user's request and material:

- **Grounded** — lead with lived scenes and plain speech; use imagery sparingly.
- **Hybrid** — balance relational evidence with one coherent image field. Use this by default for “细腻、感人、不像 AI.”
- **Lyrical** — allow recurring address, a private sense of season or time, sharper contradiction, and a more literary ending. Require at least two relationship-specific facts so the prose does not float away from the people involved.

Do not mistake “lyrical” for “more metaphors.” Follow [references/lyrical-mode.md](references/lyrical-mode.md) to control density and cadence.

If the user wants a visibly prepared, impressive letter, apply **郑重成章** after choosing the style and register. This is a revision overlay, not a tenth style route: preserve lived evidence and emotional truth, but replace diary chronology, repeated reassurance, fillers, asides, and live self-explanation with deliberate selection, delayed meaning, one earned core sentence, and a quiet afterimage. Follow [references/prepared-sincerity.md](references/prepared-sincerity.md).

### 5. Choose a narrative spine

Use one primary spine:

- **One object across time** — return to an ordinary object whose meaning changes.
- **Then / now** — revisit a past misunderstanding with present knowledge.
- **What I noticed late** — reveal the recipient's quiet effort gradually.
- **A small debt of language** — repay one unsaid thank-you, apology, or blessing.
- **Release without erasure** — honor what happened without asking for reunion.

Do not combine every spine. One clear emotional movement is stronger than many themes.

### 6. Draft the emotional arc

Build the letter in five movements, adjusting length as needed:

1. **Enter sideways** — begin with a small fact, memory, or admission; avoid announcing a grand theme.
2. **Return to a scene** — show one concrete moment before explaining it.
3. **Name the meaning** — say what the writer understood, misread, feared, or owed.
4. **Give the recipient freedom** — do not use tenderness to demand forgiveness, reunion, or reassurance.
5. **Leave an afterimage** — end on a quiet image, action, or plain sentence that changes the meaning of something earlier.

Let the strongest line arrive after evidence. Do not begin at maximum intensity.

### 7. Preserve human rhythm without preserving raw speech

For ordinary grounded or hybrid letters, keep a little spoken asymmetry: a short correction, a half-step backward, or a plain sentence after a lyrical one. Vary sentence length. Allow silence between emotional turns.

When **郑重成章** is active, sincerity does not require preserving raw speech. Remove `emm`, `哈哈`, emojis, drafting notes, repeated questions, stacked parentheses, and explanatory `PS` unless one rare aside carries irreplaceable intimacy. The letter should feel written for this recipient and revised before being sent.

Do not let polishing redefine an ambiguous relationship. Keep “我爱你” only when the user clearly wants that exact declaration; otherwise clarify whether the peak should be “爱” or the boundary-safer “珍惜/在意.” Never invent a shared quotation, scene, or creative detail to make the letter more impressive.

Prefer concrete nouns and verbs over stacked adjectives. Use no more than one sustained metaphor family in a short letter and at most two in a long letter. Make each metaphor answer to a real scene.

When editing voice transcription, separate intended letter prose from teaching commentary, fillers, English cues, false starts, and likely ASR errors. Preserve only deliberate self-correction that strengthens intimacy.

### 8. Revise against the anti-AI rubric

Run the checks in [references/style-patterns.md](references/style-patterns.md). Rewrite any paragraph that could be sent unchanged to ten different people.

Delete:

- generic life philosophy;
- repetitive praise;
- symmetrical slogan chains;
- inflated promises;
- decorative sadness with no event beneath it;
- conclusions that explain the emotion after the image has already carried it.
- last-minute advice about how the recipient should grow, heal, or behave after a breakup, unless the user explicitly asks for it.

### 9. Protect originality

Do not reproduce or closely imitate the distinctive style of a living writer or creator. If the user names one, acknowledge the admired qualities and translate them into high-level craft traits such as concrete observation, restrained escalation, oral cadence, or tension between two images. For historical writers, do not offer author-name imitation presets either. Combine transferable mechanisms from more than one tradition, then produce new wording, new imagery, and a structure fitted to the user's own memories.

## Return the result

By default, return:

1. the finished letter only;
2. a short optional note listing any details that would make a second version more personal.

When useful, offer two endings with different emotional temperatures: **更克制** and **更靠近**. Do not add a craft lecture unless the user asks for analysis.

Match the requested length and relationship boundary. For sensitive repair or apology letters, keep responsibility explicit and avoid emotional pressure.

For breakup and farewell letters, end with the writer's boundary, action, or self-placement. Do not turn the final paragraph into a lesson for the recipient.
