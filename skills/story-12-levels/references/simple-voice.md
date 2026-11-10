# The simple voice: how a script should sound

The goal is a script so simple and so human that it sounds like a friend telling you something, not a narrator reading. Slow, natural, full of feeling, and the viewer leaves with the payoff and the value.

## The 8 rules

1. **Talk like a friend, not a narrator.** If you wouldn't *say* a word out loud, cut it.
2. **No heavy words.** If a 12-year-old wouldn't get it, swap it (table below).
3. **Short lines, one idea per line.** Most lines are 4 to 10 words. A line is a breath.
4. **Slow.** About 140 to 150 words per 60 seconds. Leave room for pauses. Better to cut a fact than to rush.
5. **Start from something everyone already knows.** Explain the strange thing through a normal one. "You know the toilet on a plane? The loud one? Whoosh."
6. **Ask the question out loud, then answer it.** "So why does a toilet cost that much?" … "Not one toilet. The whole ship." The answer is the payoff.
7. **Every viewer leaves with 4 things:** 1 number, 1 simple why, 1 surprise, 1 line they'd repeat to a friend (the share line).
8. **End strong.** Set up a question, deny the obvious answer, then reveal something everyday with something absurd about it, and hard cut. "The craziest bill on a Navy ship? It's not a gun. (pause) It's the toilet."

## Heavy word → simple word

| Don't say | Say |
|---|---|
| approximately, an estimated | about |
| utilize | use |
| infrastructure | the pipes, the wiring, the parts |
| mechanism | how it works |
| procurement, acquisition | buying |
| expenditure | the bill, what it costs |
| subsequently | then, after that |
| significant(ly) | a lot, huge |
| in addition | and, also |
| commence | start |
| numerous | lots of |
| numbers in the voice | say them as words ("four hundred thousand dollars"), show digits on screen |

## Before → after

- ❌ "Its toilets work like an airplane's. Vacuum, skinny pipes, very little water. Calcium builds up."
- ✅ "You know the toilet on a plane? The loud one? Whoosh. This ship uses the same kind. But with more than four thousand people on board. So stuff builds up."

## Write the emotion into the script

Tag a line only where the feeling changes (about one tag every 1 to 2 lines).

- **Tags:** `[excited]` `[curious]` `[playful]` `[whispers]` `[chuckles]` `[laughs]` `[sighs]` `[serious]` `[disbelief]` `[deadpan]` `[amused]` `[shocked]` `[warm]` `[calm]`. For calm or sleep content use only `[calm]`, `[warm]` and `[whispers]`.
- `(pause)` = a real half-second to one-second stop: after the hook, before every punchline, before the reveal.
- `...` = a held beat inside a line ("four million dollars... on toilets").
- **CAPS** on the ONE word you'd stress ("cost THAT much?").
- `?` and `!` change the melody, so use them only for real questions and real surprise.

```
[excited] This Navy ship pays about four hundred thousand dollars... [disbelief] just to unclog its toilets.
(pause)
[curious] So why does a toilet cost THAT much?
[playful] You know the toilet on a plane? The loud one? [whispers] Whoosh.
[serious] That's what the four hundred thousand pays for. Not one toilet. The WHOLE ship.
```

If your text-to-speech model reads tags out loud instead of acting them, turn them into punctuation before generating: delete the tags, keep the `...`, `?`, `!` and CAPS, and make each `(pause)` a new paragraph. Generate the whole script in one call so the emotion flows. Then check every word with speech-to-text, because the tool can't hear itself. A human ear makes the final call.

## The 60-second check before handing over

- [ ] Could a 12-year-old follow every line?
- [ ] Does line 1 say the topic and the promise plainly?
- [ ] Is there a line that starts from something everyone knows?
- [ ] Is the question said out loud, and answered?
- [ ] Number + why + surprise + share line, all there?
- [ ] About 140 to 150 words per minute of video?
- [ ] Emotion tags, `(pause)` and one CAPS word written in?
- [ ] Every fact sourced?
