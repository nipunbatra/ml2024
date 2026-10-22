# ES 335 · Machine Learning (2024)

Course website for ES 335 Machine Learning at IIT Gandhinagar, Semester II 2023–24:
<https://nipunbatra.github.io/ml2024/>

The site is a [Quarto](https://quarto.org) website in the same design as
[ES 667 Deep Learning](https://nipunbatra.github.io/dl-2026/). GitHub Actions renders it and publishes it to the
`gh-pages` branch (`quarto publish gh-pages`) on every push to `main`.

| File | Contents |
|---|---|
| `index.qmd` | Home: course facts, course record, module overview, questions, references, teaching assistants |
| `schedule.qmd` | Lectures: one row per lecture with slides, recordings, notebooks and reading |
| `assessment.qmd`, `_dates.qmd` | Grading, every dated event, quizzes and assignments |
| `faq.qmd` | All questions |
| `exams/prereq.qmd` | Prerequisite test |
| `grading.qmd`, `tentative.qmd`, `quizzes.qmd` | Redirects from old URLs to Assessment |
| `styles.scss`, `course.scss` | Shared theme (`styles.scss` is identical to dl-2026) and small additions |
| `rail.html`, `course-theme.html`, `course-tools.html` | Side rail, light and dark switch, footer, copy-link buttons and date handling |

Slides and notebooks live in [ml-teaching](https://github.com/nipunbatra/ml-teaching). Preview locally with
`quarto preview`.
