🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

A playful social bingo app for in-person mixers, team warmups, and hands-on workshops.

Meet people, spark small conversations, and race to complete a bingo line with fresh, fun prompts.

📚 **[Open the workshop guide](workshop/GUIDE.md)**

---

## Why this project?

- Lightweight Spring Boot + Thymeleaf experience with no extra frontend framework.
- Built as a learning lab for UI design, Java service wiring, and multi-agent collaboration.
- Perfect for workshops, icebreakers, and developer practice.

---

## Quick start

### Run locally
```bash
cd socops
./mvnw spring-boot:run
```
Open the app at `http://127.0.0.1:8080`.

### Build and test
```bash
cd socops
./mvnw clean package
./mvnw test
```

---

## Workshop path

| Part | Title |
|------|-------|
| [**00**](workshop/00-overview.md) | Overview & Checklist |
| [**01**](workshop/01-setup.md) | Setup & Context Engineering |
| [**02**](workshop/02-design.md) | Design-First Frontend |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development |

> 📝 You can also browse the full workshop content in the [`workshop/`](workshop/) folder.

---

## Project structure

- `socops/` — Spring Boot app and UI templates
- `workshop/` — guided lab content and exercises
- `.github/agents/` — custom agent definitions for task automation

---

## Prerequisites

- Java 21 JDK or higher
- Apache Maven 3.9+ (or use the included Maven Wrapper)

---

Deploys automatically to GitHub Pages on push to `main`.
