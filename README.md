# SerLord Ministry – ABC Usher Certification Exam

An in-house online exam for ushers of **SerLord Ministry**, a ministry of
**Cathedral of Praise Church**.

**ABC** stands for:

- **A – Application**: putting what you know into practice in real situations during service
- **B – Basics**: the foundations of ushering: purpose, Scripture, standards
- **C – Checkpoint**: readiness checks, accountability and integrity before, during and after service

## Features

- 106 multiple-choice questions (A = 35, B = 35, C = 36)
- Every question, answer and explanation has an English and a Tagalog/Filipino version
- Mixed exam (4 random questions from each of A, B and C) or a single-section exam
- 70% passing mark
- English-only printable certificate of completion with the Cathedral of Praise, SerLord and Hupomone logos
- Runs entirely in the browser, with no backend or build step

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (layout, styles, questions, logic) |
| `cop_logo.jpg` | Cathedral of Praise logo |
| `serlord_logo.jpg` | SerLord Ministry logo |
| `hupomone_logo.jpg` | Hupomone logo |

Keep the logo files in the same folder as `index.html`.

## Run locally

Open `index.html` in a web browser.

## Hosted version

https://jv-hub07.github.io/SerLord-Assess/

## Limitations

- The questions and correct answers are stored in the page itself, so anyone who
  views the page source can read them. This is suitable for a friendly in-house
  exam, not for a verified or secured assessment.
- Certificates are generated in the browser and are not verified by any server.

## Adding or editing questions

Questions are in the `QUESTION_BANK` section of `index.html`. In each question,
the **first** option is the correct answer. Options are shuffled each time an
exam is created.
