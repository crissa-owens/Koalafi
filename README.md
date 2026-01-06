# 🐨 Koalafi — Career Matching Assistant

**Live Demo:** [https://crissa-owens.github.io/Koalafi/](https://crissa-owens.github.io/Koalafi/)

Koalafi (featuring Ozzie the koala 🐨✨) is an interactive web app that helps users explore potential careers through guided questions and AI-powered insights. Users answer a series of basic and detailed questions, and Koalafi generates personalized career suggestions using the OpenAI API.

This project was originally developed as part of a **Software Engineering course**, created collaboratively by a **team of four students (including myself)**. After the course ended, I **forked the repository and continued developing the project independently, with full permission from the other group members**.

### Original Team Members

* Kevin Pinkett: [https://github.com/kevin-pinkett](https://github.com/kevin-pinkett)
* Nolan Vasil: [https://github.com/nolanv45](https://github.com/nolanv45)
* Asher Mills: [https://github.com/asher013](https://github.com/asher013)
* **Crissa Owens**

### Artwork Credit

**Ozzie the Koala — character design and artwork were created by one of my teammates:** Kevin Pinkett

---

## Features

* AI-powered career recommendations
* Guided multi-step question flow (basic → detailed → results)
* Create-your-own AI-generated questions
* Dark mode support
* Adjustable text size for accessibility
* User-provided OpenAI API key stored securely in Local Storage
* Easy page navigation + persistent state
* Custom mascot + UI theme
* FAQ page for user help

---

## 🏗️ Tech Stack

| Tool              | Purpose             |
| ------------------| ------------------- |
| React / Typescript| UI Framework        |
| OpenAI API        | AI-driven responses |
| CSS + Bootstrap   | Styling             |
| React Context API | Theme + Text Size   |
| GitHub Actions    | Deployment pipeline |
| GitHub Pages      | Hosting             |

---

## API Key Handling

Koalafi requires users to provide their **own OpenAI API key**. The key is:

* Stored only in `localStorage`
* Validated before use
* Not transmitted anywhere except to OpenAI
* Required to unlock the question pages

If a key is invalid, the user is prompted to retry.

---

## App Flow

1. Visit the site: [https://crissa-owens.github.io/Koalafi/](https://crissa-owens.github.io/Koalafi/)
2. Enter your **OpenAI API key**
3. Answer **basic questions**
4. Continue to **detailed questions** (optional)
5. View **career recommendations**
6. Explore FAQs or try **custom AI questions**

---

## Running Locally

```bash
git clone https://github.com/crissa-owens/Koalafi.git
cd Koalafi
npm install
npm start
```

App runs at:

```
http://localhost:3000
```

---

## Deployment — GitHub Pages via GitHub Actions

This project deploys automatically to: [https://crissa-owens.github.io/Koalafi/](https://crissa-owens.github.io/Koalafi/)

Deployment is handled using **GitHub Actions**, which:

1. Builds the React app
2. Publishes the `/build` output to GitHub Pages

No manual deployment required

---

## Background & History

Koalafi began as a **Software Engineering class project** with a team of four developers. After the course ended, I:

* Forked the repo
* Continued development independently
* Made UI + accessibility improvements
* Expanded AI functionality
* Cleaned + reorganized code

— all **with the full permission and support of my teammates**.

---

## AI Assistance & Documentation
AI tools supported parts of this project:

* GitHub Copilot helped generate documentation sections
* GitHub Copilot assisted with debugging and CSS improvements
* ChatGPT assisted with completing and polishing this README.md document
All logic, design choices, and code structure decisions were controlled and reviewed by myself and my team.

---

## Acknowledgements

**Huge thanks to my original teammates.**
Special appreciation to **the teammate who designed Ozzie the Koala:** Kevin Pinkett

Thanks also to:
* OpenAI Developer Docs
* React community tutorials
* Everyone who tested and provided feedback

