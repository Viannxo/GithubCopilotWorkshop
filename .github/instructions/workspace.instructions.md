---
description: Workspace map and development checklist for the Soc Ops Java workshop repository.
---

# Workspace Instructions

## Required development checklist
- [ ] Lint or inspect code for formatting or obvious errors
- [ ] Build the project: `cd socops && ./mvnw clean package`
- [ ] Run tests: `cd socops && ./mvnw test`

## Quick repo map
- `socops/` — Spring Boot app with Thymeleaf UI
- `workshop/` — guided lab content and exercises
- `README.md` — quick start instructions

## Key files
- `socops/pom.xml` — Maven config
- `socops/src/main/java/com/socops/SocOpsApplication.java` — entry point
- `socops/src/main/java/com/socops/web/BingoRestController.java` — web controller
- `socops/src/main/resources/templates/game.html` — UI template

## Notes for agents
- Keep changes small and aligned with current UI styling
- Prefer existing utility CSS over new frameworks
- Use workshop tasks to guide development and feature additions
