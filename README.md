# PocketPal bot prompts

Ready-to-paste system prompts for [PocketPal AI](https://github.com/a-ghorbani/pocketpal-ai) on iPhone. These are characters and tutors for chatting with a small local model, fully offline, after you download the model once over Wi-Fi.

They were collected for Dave Schwartz's PocketPal setup on an iPhone 16e. Most prompts are copied from earlier chats. A few ideas were described without a full prompt; those files include a concise ready-to-paste version and are marked **Newly written**.

## How to paste a prompt into PocketPal (iPhone)

1. Open **PocketPal AI**.
2. Download a small model over Wi-Fi if you don't have one yet. **Gemma 3 4B** or **Qwen 3 4B** are a good fit for an iPhone 16e. Use a 1–2B model if you want more speed.
3. Go to **Pals**, then create a new Pal or open one to edit it.
4. Give it a name (for example, "Socratic tutor").
5. Paste the prompt into the **System Prompt** box and save.
6. Start a chat with that Pal. After the model is on your phone, it works in airplane mode.

A short, specific prompt that sets the role and the format ("one question at a time," "keep answers under 5 sentences") usually works better on small models.

Small models can get facts wrong, especially recent news, numbers, or anything after their training. Double-check anything important.

## Prompts

| Pal | File | Purpose | Source |
| --- | --- | --- | --- |
| Socratic tutor | [prompts/socratic-tutor.md](prompts/socratic-tutor.md) | Asks guiding questions and never hands you the answer | Existing prompt |
| Life simulator | [prompts/life-simulator.md](prompts/life-simulator.md) | Month-by-month life sim with choices, money, and stress | Existing prompt |
| Interview coach | [prompts/interview-coach.md](prompts/interview-coach.md) | Dealership service manager interview practice, one question at a time | Existing prompt |
| Car buddy | [prompts/car-buddy.md](prompts/car-buddy.md) | Auto mechanic who explains problems and warning lights in plain words | Existing prompt |
| Customer service coach | [prompts/customer-service-coach.md](prompts/customer-service-coach.md) | Role-plays an upset customer, then gives feedback | Existing prompt |
| Budget helper | [prompts/budget-helper.md](prompts/budget-helper.md) | Weekly budget planning from hourly pay and shifts | Existing prompt |
| Trivia and quiz partner | [prompts/trivia-quiz.md](prompts/trivia-quiz.md) | MLB history quiz, one question at a time, with a running score | Existing prompt |
| Learn-to-code tutor | [prompts/python-tutor.md](prompts/python-tutor.md) | Python from zero, one tiny lesson a day | Existing prompt |
| Daily journal | [prompts/daily-journal.md](prompts/daily-journal.md) | Three questions about your day, then a short summary | Existing prompt |
| Spanish practice | [prompts/spanish-practice.md](prompts/spanish-practice.md) | Speaks simple Spanish and corrects mistakes | Existing prompt |
| Dungeon master | [prompts/dungeon-master.md](prompts/dungeon-master.md) | Text adventure set in 1970s Philly, three choices per turn | Existing prompt |
| Argue with me | [prompts/argue-with-me.md](prompts/argue-with-me.md) | Takes the opposite side and pushes back hard | Existing prompt |
| Historical interview | [prompts/historical-interview.md](prompts/historical-interview.md) | Interview Benjamin Franklin about Philadelphia today | Existing prompt |
| Invention partner | [prompts/invention-partner.md](prompts/invention-partner.md) | Turns a daily annoyance into a named gadget and sales pitch | Existing prompt |
| Roast mode | [prompts/roast-mode.md](prompts/roast-mode.md) | Lightly roasts your outfit or plans | Existing prompt (light cleanup) |
| Writing helper | [prompts/writing-helper.md](prompts/writing-helper.md) | Makes a text or email clearer and more polite | Newly written |
| Dream decoder | [prompts/dream-decoder.md](prompts/dream-decoder.md) | Three playful interpretations of a dream | Newly written |
| Emergency field guide | [prompts/emergency-field-guide.md](prompts/emergency-field-guide.md) | Short offline steps for first aid, snow, or a power outage | Newly written |
| Think before you agree | [prompts/think-before-you-agree.md](prompts/think-before-you-agree.md) | Helps you spot weak evidence, a missing side, or a sales pitch | Newly written |

## License

[MIT](LICENSE)
