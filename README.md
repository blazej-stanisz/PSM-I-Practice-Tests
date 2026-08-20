# PSM I - Practice Tests

## 🙏 Data source & credits

**All exam questions used by this app come from the
[Ditectrev/Scrum-Master-I-PSM-I-Practice-Tests-Exams-Questions-Answers](https://github.com/Ditectrev/Scrum-Master-I-PSM-I-Practice-Tests-Exams-Questions-Answers)
repository. Huge thanks to [Ditectrev](https://github.com/Ditectrev) and its contributors for creating and
sharing this material with the community!**

This repository **does not contain, copy or redistribute any of those questions**. They are downloaded
directly from Ditectrev's repository in your browser, at runtime, every time the app loads. This project only
provides the user interface.

If you find the material useful, please support the original authors — they sell it in EPUB/PDF form and run a
matching Udemy course; the links are in [their README](https://github.com/Ditectrev/Scrum-Master-I-PSM-I-Practice-Tests-Exams-Questions-Answers#-support).
⭐ A star on their repository costs nothing and helps a lot.

---

A zero-dependency, single-page practice-test app for the **Professional Scrum Master I (PSM I)** certification.
No build step, no npm, no framework - just open `index.html`.

**Live demo:** go to URL https://blazej-stanisz.github.io/PSM-I-Practice-Tests/

---

## Features

- **250 questions, fetched live** from the upstream repository - the bank stays up to date automatically.
- **Configurable test** - number of questions (default **5**) and pass rate (default **90 %**).
- **Immediate feedback** - after each answer the correct options are highlighted and the choice is locked.
- **Result screen** - score ring, pass/fail verdict, statistics and a review of every question.
- **Three themes** - Dark (default), Sepia, Light; stored in `localStorage`.
- **Offline-friendly** - the downloaded source is cached in `localStorage`, so a network hiccup doesn't stop you.
- **Randomised twice** - both question order and option order are shuffled (Fisher–Yates).

---

## Source Repository Usage Notice

As of **August 20, 2026**, the authors of the original repository from which this application retrieves its questions have **not stated any restriction prohibiting the remote retrieval of questions from their public repository by external applications**.

This application does not host or redistribute a local copy of the question set. Instead, the questions are retrieved remotely from the original repository at runtime.

The original repository remains the property of its respective authors. This application is an independent project and is not affiliated with, endorsed by, or officially associated with the authors of the original repository.

**Source repository:**  
https://github.com/Ditectrev/Scrum-Developer-I-PSD-I-Practice-Tests-Exams-Questions-Answers

> **Note:** The absence of an explicit prohibition should not be interpreted as an explicit license or authorization to reproduce, redistribute, or otherwise use the original content beyond the described remote retrieval.
