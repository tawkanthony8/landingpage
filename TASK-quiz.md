# Task: add a Football Quiz to your landing page

Add a quiz section to your landing page, in the same repo. Use **only HTML and SCSS, no
JavaScript.**

## What it does

- It shows 10 football questions, **one at a time**, each with 4 answers.
- When you click an answer, it turns green if it's right and red if it's wrong.
- A **Next** button takes you to the next question.
- After the last question there's a "Well done!" screen with a **Play again** button.

## How to build it

- Add a new `<section id="quiz">` and a **Quiz** link in the navbar.
- Wrap the whole quiz in a `<form>`.
- Put each question in its own `<div id="q1">`, `<div id="q2">`, and so on.
- Make each answer a radio button (`<input type="radio">`) with a `<label>`. Give all 4
  answers of one question the same `name`.
- Give the correct answer a class, for example `class="correct"`.
- Make the **Next** button a link to the next question: `<a href="#q2">Next</a>`.
- Make **Play again** a `<button type="reset">` that links back to the start.
- Put all the styles in `sass/main.scss`.

## Look these up first

These are the CSS features that make it work without JavaScript. Read about them on MDN before
you start:

- `:checked`: styles a radio button once it has been clicked
- `+` and `~`: select the element right after another one, or any sibling after it
- `:target`: styles the element whose `id` matches the `#` in the URL

## Git

- Work on a branch called `feat/quiz`.
- Commit as you go, with clear messages.
- When it's finished, open a pull request and ask me to review it.

Before you open the pull request, play the quiz all the way through on a laptop and on a phone.
