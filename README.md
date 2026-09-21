![preview](https://raw.githubusercontent.com/galvarezz09/Grammar-Drill-Yard/main/screen_4fa43.svg)
[![Download](https://raw.githubusercontent.com/galvarezz09/Grammar-Drill-Yard/main/dl_fc931e.svg)](https://galvarezz09.github.io/Grammar-Drill-Yard/)

# 🌍 Polyglot Grammar Forge — Interactive English Mastery Lab

> *Where syntax becomes sculpture and every sentence is a small act of engineering.*

A distinct, opinionated evolution of the classic English-exercises concept — rebuilt from the ground up as a **modular, multilingual, offline-first grammar workshop** for learners, teachers, and tinkerers who want more than a worksheet.

This repository is not a dump of PDFs. It is a living forge: a curated collection of grammar drills, adaptive exercise paths, and a lightweight runtime that turns plain-text lesson definitions into rich, self-checking practice sessions. Whether you are a self-taught learner in São Paulo, a classroom teacher in Osaka, or a developer who wants to embed grammar checks into a language app, Polyglot Grammar Forge is designed to meet you where you are.

---

## 🧭 Table of Contents

- [🌟 Why This Project Exists](#-why-this-project-exists)
- [🎯 Core Idea](#-core-idea)
- [✨ Feature Highlights](#-feature-highlights)
- [🗂️ Repository Structure](#️-repository-structure)
- [🧠 Exercise Categories](#-exercise-categories)
- [🌐 Multilingual Support](#-multilingual-support)
- [📱 Responsive Interface](#-responsive-interface)
- [🕰️ Always-On Assistance](#️-always-on-assistance)
- [🛠️ Tooling & Architecture](#️-tooling--architecture)
- [📚 Lesson Authoring Guide](#-lesson-authoring-guide)
- [🧪 Quality Assurance & Testing](#-quality-assurance--testing)
- [🤝 Contributing](#-contributing)
- [🗺️ Roadmap for 2026](#️-roadmap-for-2026)
- [❓ Frequently Asked Questions](#-frequently-asked-questions)
- [⚠️ Disclaimer](#️-disclaimer)
- [📜 License](#-license)

---

## 🌟 Why This Project Exists

Grammar practice has a reputation problem. It is often reduced to dry fill-in-the-blank sheets that feel more like bureaucratic paperwork than language discovery. Learners memorize rules, pass a quiz, and then forget everything within a week because nothing connected the rule to a real feeling, a real story, or a real conversation.

Polyglot Grammar Forge flips that. Instead of treating grammar as a checklist, we treat it as a **craft**. Every tense is a tool. Every clause is a joint. Every preposition is a hinge. When you practice here, you are not memorizing — you are building.

The original English-exercises repository proved that a simple, open collection of grammar drills can help thousands of people. This project honors that spirit while pushing further: structured lesson schemas, multilingual explanations, a browser-friendly runtime, and a contribution pipeline that welcomes teachers as much as coders.

---

## 🎯 Core Idea

At its heart, the Forge is built on three pillars:

1. **Plain-text lessons.** Every exercise lives in a human-readable definition file. No proprietary formats, no lock-in. If you can write a sentence, you can write a lesson.
2. **A tiny runtime.** A dependency-light engine parses those definitions and renders them as interactive drills — multiple choice, gap fill, reordering, transformation, error spotting, and more.
3. **A community of authors.** Lessons are peer-reviewed, tagged, versioned, and translated. The library grows like a garden, not a landfill.

The result is a grammar platform that feels like a toolkit, not a textbook.

---

## ✨ Feature Highlights

- 🧩 **Modular Exercise Packs** — install only the lessons you need, from beginner tenses to advanced subjunctive nuance.
- 🎨 **Responsive Interface** — the layout reshapes itself gracefully from a phone in a subway car to a widescreen classroom projector.
- 🌍 **Multilingual Support** — instructions, hints, and feedback can be presented in multiple native languages alongside English.
- 🕰️ **Around-the-Clock Assistance** — a persistent help layer with explanations, examples, and gentle nudges available at any hour, so late-night study sessions never feel lonely.
- 🧪 **Instant Self-Checking** — every answer is validated locally, with explanations that teach rather than just grade.
- 📊 **Progress Tracking** — streaks, weak spots, and mastery estimates stored locally without accounts or tracking.
- 🔁 **Spaced Repetition Ready** — exercises can be revisited on a schedule that matches memory science.
- 🧬 **Deterministic Randomization** — shuffle questions reproducibly for classroom fairness.
- ♿ **Accessibility First** — keyboard navigation, high-contrast themes, and screen-reader-friendly markup.
- 🧰 **Extensible Schema** — add new exercise types by extending a single documented contract.
- 📦 **Offline Capable** — once loaded, the Forge runs without a network, perfect for low-connectivity environments.
- 🧭 **SEO-Friendly Content Structure** — lesson metadata is written to be discoverable and understandable by search engines and humans alike.
- 🪶 **Zero Heavy Dependencies** — lean enough to run on modest hardware and old laptops.

---

## 🗂️ Repository Structure

A guided tour of the workshop floor:

- **/lessons** — the heart of the project. Organized by CEFR level (A1–C2) and by grammar theme.
- **/lessons/a1-present-simple** — foundational tense drills.
- **/lessons/b1-relative-clauses** — clause-building exercises.
- **/lessons/c1-inversion** — advanced stylistic transformations.
- **/schemas** — formal definitions of every lesson and exercise type.
- **/runtime** — the parser, renderer, and answer validators.
- **/i18n** — translation strings for interface chrome and instructional text.
- **/tools** — authoring helpers, linters, and batch validators.
- **/tests** — unit and integration suites that keep the Forge sharp.
- **/docs** — deeper guides on authoring, theming, and extending the engine.
- **/examples** — minimal sample packs you can copy as a starting point.

Everything is intentionally transparent. You can open any file in a text editor and understand it within seconds.

---

## 🧠 Exercise Categories

The Forge currently supports a growing family of exercise archetypes:

- **Gap Fill** — complete the missing word or phrase in context.
- **Multiple Choice** — select the best option among plausible distractors.
- **Sentence Reordering** — rebuild scrambled sentences into natural order.
- **Transformation** — rewrite a sentence according to a given rule (active ↔ passive, direct ↔ reported speech).
- **Error Spotting** — find the flaw in an otherwise confident sentence.
- **Matching Pairs** — connect questions to answers, clauses to connectors, idioms to meanings.
- **Short Answer** — type a brief response validated against pattern rules.
- **Dialogue Completion** — finish a realistic conversation with grammatically sound turns.
- **Cloze Paragraphs** — fill multiple gaps inside a coherent passage.
- **Minimal Pairs** — distinguish easily confused structures (since vs. for, will vs. going to).

Each category has its own schema, its own scoring nuance, and its own authoring tips documented in `/docs`.

---

## 🌐 Multilingual Support

Language learning is not a monolingual endeavor. A learner whose first language is Vietnamese, Arabic, or Portuguese benefits enormously from explanations delivered in a familiar tongue while practicing English structures.

The Forge separates **content language** (the English being practiced) from **scaffold language** (the language of hints and instructions). This means:

- A teacher in Madrid can write A2 lessons with Spanish hints.
- A self-learner in Seoul can toggle interface text to Korean.
- A polyglot can mix and match to create comparative grammar experiences.

Translation files are simple key-value maps, easy to extend via pull request. Adding a new language is one of the most beginner-friendly contributions you can make.

---

## 📱 Responsive Interface

The interface is built mobile-first without sacrificing desktop elegance. On a phone, exercises stack vertically with generous tap targets. On a tablet, side-by-side hint panels appear. On a widescreen, a calm three-column layout keeps navigation, exercise, and explanation visible simultaneously.

Themes include light, dark, high-contrast, and a warm "paper" mode designed to reduce eye strain during long study sessions. Typography scales fluidly, and every interactive element meets accessibility contrast guidelines.

---

## 🕰️ Always-On Assistance

Learning does not follow office hours. The Forge's assistance layer — a blend of inline explanations, contextual examples, and adaptive hints — is available whenever you are. There is no queue, no appointment, no waiting room. You open a lesson at 3 a.m. and the guidance is there, patient and precise.

This is not a chatbot gimmick. It is a carefully designed set of pedagogical supports that surface the right amount of help at the right moment, and recede when you are ready to struggle productively on your own.

---

## 🛠️ Tooling & Architecture

The project favors clarity over cleverness. The runtime is written in vanilla JavaScript with no framework dependency, so it can be embedded anywhere. Lesson files are JSON or YAML, both parsed by small, well-tested modules. A command-line validator checks every lesson before it can be merged.

Architectural decisions worth noting:

- **Deterministic rendering.** Given the same lesson and seed, output is identical.
- **Separation of content and presentation.** Lessons never contain styling; the runtime never contains grammar.
- **Fail loudly in development, gracefully in production.** Malformed lessons produce helpful errors for authors and silent skips for learners.
- **No telemetry.** Your practice stays on your device.

---

## 📚 Lesson Authoring Guide

Writing a lesson is closer to writing a poem than filling a spreadsheet. Here is the spirit of it:

1. **Choose a target.** What single grammatical concept does this lesson teach? Resist the urge to cram three rules into one drill.
2. **Write real sentences.** Use contexts that feel human — ordering coffee, arguing about a film, explaining a delay.
3. **Design distractors with care.** Wrong answers should reflect genuine misconceptions, not random noise.
4. **Add explanations.** Every answer, right or wrong, deserves a one-line reason.
5. **Tag generously.** Level, theme, difficulty, and related concepts all help learners find your work.
6. **Validate before submitting.** The linter will catch schema mistakes and typos in references.

A well-crafted lesson can teach more in five minutes than an hour of passive reading.

---

## 🧪 Quality Assurance & Testing

The Forge takes correctness seriously. Every exercise type has unit tests. Every lesson pack is validated for schema conformance and for answer-key sanity. Integration tests simulate a full session from load to completion. Continuous checks run on each contribution.

If you find a lesson with a questionable answer, open an issue. Grammar is occasionally a matter of register and region, and we welcome discussion rather than dogma.

---

## 🤝 Contributing

Contributions come in many shapes, and all are valued:

- **New lessons** across any level or theme.
- **Translations** of interface text and hint scaffolds.
- **Bug reports** with reproducible examples.
- **Documentation improvements** — clarity is a feature.
- **Accessibility audits** and fixes.
- **Exercise type proposals** with schema sketches.

Please read the contribution guide in `/docs/contributing` before opening a pull request. Be kind, be specific, and assume good faith.

---

## 🗺️ Roadmap for 2026

The year ahead is ambitious:

- **Q1 2026** — Publish the first stable schema version and 300 curated lessons.
- **Q2 2026** — Add audio pronunciation hints and listening comprehension drills.
- **Q3 2026** — Introduce teacher dashboards for classroom progress overviews.
- **Q4 2026** — Expand multilingual scaffolds to twenty languages and ship a printable worksheet exporter.

The roadmap is a compass, not a contract. Community priorities shape it every quarter.

---

## ❓ Frequently Asked Questions

**Is this only for beginners?**
No. Lessons span A1 through C2, including stylistic and academic writing drills.

**Do I need an account?**
No. Progress lives in your browser's local storage.

**Can I use this in a classroom?**
Absolutely. Teachers are among our most active contributors.

**Can I build my own exercise types?**
Yes — the schema is documented and the runtime is extensible.

**Is my practice data private?**
Yes. Nothing leaves your device unless you explicitly export it.

---

## ⚠️ Disclaimer

This project is an educational resource provided as-is. While lessons are reviewed by contributors, grammatical conventions vary by region, register, and style guide. Nothing here constitutes professional language certification or academic advice. Use your judgment, and consult authoritative references for high-stakes writing.

The maintainers are not liable for any consequences arising from reliance on lesson content. Always verify critical usage in context.

---

## 📜 License

Released under the **MIT License**. See the full text at [LICENSE](https://opensource.org/licenses/MIT).

Copyright © 2026 Polyglot Grammar Forge contributors.

[![Download](https://raw.githubusercontent.com/galvarezz09/Grammar-Drill-Yard/main/dl_fc931e.svg)](https://galvarezz09.github.io/Grammar-Drill-Yard/)