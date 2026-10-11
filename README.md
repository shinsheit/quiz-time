# Quiz Time

A small, self-contained quiz app you can use on your phone — paste a question, add the choices, mark the correct one, and watch the **wrong** choices light up in green when you check.

It runs entirely in the browser (no server, no build, no dependencies). Everything is saved in your browser's local storage.

## How it works

- **Edit view**: add one or more quizzes. In each quiz, add questions; for every question, type the question and its choices. A radio button marks the answer you consider correct.
- **Quiz view**: start a quiz and answer each question, then press **Check answer**. Every choice that is **not** the correct one turns green (`✓` on the correct one, `✗` on the wrong ones) so you can see at a glance which ones are *not* the answer — exactly what you described.
- Add more questions, more quizzes, or a new quiz anytime. Data persists in `localStorage`, so a refresh won't wipe it.

The app ships with one sample quiz (Astronomy Quick) so you can see it working immediately.

## Run it

Just open `index.html` in any modern browser (double-click the file, or drag it into a tab).

## Deploy to GitHub Pages (your "domain")

1. Create a new GitHub repository, e.g. `quiz-time`.
2. Upload the folder contents (just `index.html` and optionally the README) to the repo.
   - If you put `index.html` at the repo root, GitHub Pages will use it directly.
   - Or enable **Settings → Pages**, choose the branch, and set the folder to `/ (root)`.
3. GitHub Pages will publish it at `https://<your-username>.github.io/quiz-time/`.

To reuse it on your phone, sync that same folder later (or re-upload) whenever you add quizzes.

## Notes

- The sample "Astronomy Quick" quiz is just a starter. Replace or delete it with your own quizzes.
- Wrong answers show green as a **review hint**; the correct answer is shown with a check and the word "correct".
