---
name: flashcards
description: Turn notes or a topic into a set of question/answer study flashcards. Use when the user wants to revise or memorise material.
license: MIT
uses: create-flashcard
---

# Study flashcards

From the user's notes or topic, produce 8–15 flashcards.

Format each as:
```
Q: <one clear question>
A: <concise answer>
```

Rules:
- One idea per card.
- Questions should test recall, not be answerable with yes/no.
- Cover the material evenly; don't cluster on one sub-topic.
- Keep answers short enough to memorise.
- If the source is thin, make fewer high-quality cards rather than padding.
- End with nothing but the cards.

If the user has an app that provides the `create-flashcard` capability (you'll be
told the exact tool name when this skill loads), offer to add the cards straight
into it instead of only printing them — one tool call per card.
