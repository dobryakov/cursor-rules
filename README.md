# cursor-rules
A collection of rules and guidance for the Cursor environment, designed to help streamline development workflows and enforce consistent patterns across your codebase.

## 🚀 What this is
This repository hosts a set of rule files (typically in `.mdc` format) under `.cursor/rules`, intended for use with the Cursor IDE (or similar AI-assisted development environments). These rules define project-wide or module-specific instructions such as coding standards, architecture guidelines, workflow automations, and more.

## 🎯 Why use it
By embedding rules into your project:

- Your AI assistant (via Cursor) has **contextual, version-controlled guidance** specific to your project.
- You enforce **consistency** across team workflows, coding style, architecture decisions.
- You reduce repetitive decision-making by codifying best practices and patterns.
- You make onboarding smoother: new contributors inherit the same rule set from day one.

## ✅ Getting started
1. Clone this repository (or add it as a submodule) into your project’s `.cursor/rules` directory:
   git clone https://github.com/dobryakov/cursor-rules.git .cursor/rules
   (or make a symlink)

2. Make sure your project structure and rule-paths align with how your Cursor environment expects rules to be found.

3. Inspect or adapt the rule files to fit your project’s specifics (naming conventions, file patterns, workflows).

4. Commit the rules into version control so the whole team uses the same guidance.

5. In Cursor, confirm the rules are being recognized and applied (often via “Rules” or context settings in the UI).

## 🚀 What this is
This repository hosts a set of rule files (typically in `.mdc` format) under `.cursor/rules`, intended for use with the Cursor IDE (or similar AI-assisted development environments). These rules define project-wide or module-specific instructions such as coding standards, architecture guidelines, workflow automations, and more.

## 🎯 Why use it
By embedding rules into your project:

- Your AI assistant (via Cursor) has **contextual, version-controlled guidance** specific to your project.
- You enforce **consistency** across team workflows, coding style, architecture decisions.
- You reduce repetitive decision-making by codifying best practices and patterns.
- You make onboarding smoother: new contributors inherit the same rule set from day one.

## 🛠 Customizing for your team
- Add or remove rule files as needed — keep them **focused**, **actionable**, and **scoped** (good rules tend to be < 500 lines).
- For new domains or frameworks, create a new subdirectory (e.g., `framework/python/`, `domain/analytics/`).
- Document clearly in each rule: what it enforces, **why** it exists, and **how** to use/adhere to it (include examples and anti-patterns).
- Use metadata (globs, alwaysApply flags) to control when a rule is applied or triggered.

## 🤝 Contributing
Contributions are welcome! Here’s how you can help:

- Fork this repository and create a branch for your feature or rule improvement.
- Add a new `.mdc` file (or update an existing one) with clear description, scope, and examples.
- Ensure your changes align with the existing naming and structuring conventions.
- Submit a pull request with a meaningful commit message describing the rule’s purpose or modification.
