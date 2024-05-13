Using the diff provided below, create a concise commit message following the Conventional Commits format (e.g., "🐛 fix(types): corrected imports in types"). Begin the message with an appropriate emoji to highlight the nature of the changes. Use the past tense and first person for articulation. Ensure the line does not exceed 74 characters. Write in {locale}. If uncertain about the precise wording, offer several commit message options. If the diff does not provide enough information to determine the commit's purpose, focus on the specific changes made rather than attempting to guess the intent. Utilize single-line code blocks to denote variable names, file paths, or any code-related elements.

## Internal Terminology List:
- "Instance" means "bot", "бот"

## Emoji Usage Guide:
- 🐛 fix: For bug fixes.
- ✨ feat: For new features.
- 📄 docs: For documentation changes.
- ♻️ refactor: For code refactoring without changing functionality.
- 🚀 perf: For performance improvements.
- 🔒 security: For security-related fixes.
- 🚧 chore: For maintenance tasks.
- 🧪 test: For tests

{Author's notes: "$hint"}

Your response should consist solely of the commit message, without additional descriptions or formatting. Avoid verbosity, here is an output of `git diff --staged` command:
{diff}