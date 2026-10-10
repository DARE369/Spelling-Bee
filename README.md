# 🐝 Spelling Bee Live

A two-screen spelling bee app for a Grade 4 vs Grade 7 match (Manitoba curriculum, Canadian spelling).

## Run it
Open `index.html` in Chrome or Edge (double-click it, no install needed). Keep `words.js` in the same folder.

## Keep the word secret while screen sharing
1. Click **📺 Open Stage Screen**. A second window opens. It never shows the word until the round is over.
2. In Zoom, Teams or Meet choose **Share → Window** and pick the **Stage** window only.
3. Keep the **Host Console** to yourself. If you can only share one screen, leave **Privacy blur** on and press and hold **Peek** (or hold **P**) to see the word.

## Round flow
Draw → word is crossed out → timer runs → **Correct** (+2) or **Incorrect / time out** → the other speller gets a **bonus steal** (+1, shorter timer) → the Stage reveals the spelling, meaning, origin and a tip → **Next**.

Shortcuts: `N` draw/next · `C` correct · `X` incorrect · `Space` pause · `S` say word · hold `P` peek.

Scores are saved automatically in the browser. **📋 Results** shows the scores and lets you copy or download them as a CSV.

## Word pool
`words.js` holds 50 words (25 Grade 4, 25 Grade 7). Each word has its pronunciation, syllables, part of speech, definition, an example sentence, origin and a spelling tip.
