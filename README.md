# 🎓 UC Berkeley Insider Quiz

![UC Berkeley Campus](https://drive.google.com/uc?export=view&id=1STKF9bG-Xv4yr2_W69ek1mXfy-NAap3y)

## About This Quiz

Think you know UC Berkeley? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know UC Berkeley?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **What do Cal students traditionally do at '4.0 Hill' to boost their GPA luck?**
> - **A.** Sing 'Hail to California' at dawn
> - **B.** Roll down the grass before exams
> - **C.** Balance textbooks on the Oski statue
> - **D.** Circle the Campanile three times counterclockwise
> - **E.** Toss pennies into Strawberry Creek

<details>
<summary>🔍 Click to reveal answer</summary>

**B** — Rolling down 4.0 Hill is a good-luck GPA ritual before exams.

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: UC Berkeley Insider Quiz -->
<!-- og:description: Think you know UC Berkeley? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=1STKF9bG-Xv4yr2_W69ek1mXfy-NAap3y -->
<!-- og:type: website -->
