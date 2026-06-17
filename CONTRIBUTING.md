# Contributing to Pitt Document Checker

Thank you for helping keep this tool accurate and useful. Contributions fall into a few categories — here's how to handle each.

---

## Reporting a Bug

If something isn't working (the PDF won't load, annotations appear in the wrong place, the tool crashes), please open a GitHub Issue using the **Bug Report** template. Include:

- What browser and version you're using
- What type of PDF you uploaded (exported from Word, InDesign, Google Docs, etc.)
- What you expected to happen vs. what actually happened
- A screenshot if possible — you do not need to share the actual PDF

---

## Suggesting a New or Updated Style Rule

Pitt's brand guidelines and writing style manual are updated periodically. If you've noticed a rule is missing, outdated, or incorrect:

1. Open a GitHub Issue using the **Style Rule** template
2. Describe the rule and where it comes from (link to brand.pitt.edu or cite the Style Manual edition and page number if you have it)
3. If it's a 3rd Edition update, note what changed from the previous edition

Rules will only be added if they can be sourced to official Pitt documentation.

---

## Suggesting a UI or Feature Improvement

Open a GitHub Issue with the label `enhancement`. Describe:

- What you're trying to do that the tool doesn't currently support
- Why it would be useful for others, not just your specific use case

Good examples of feature requests:
- "Support Word (.docx) uploads in addition to PDF"
- "Add a way to export the annotated document"
- "Show a summary score card at the end"

---

## Submitting a Pull Request

If you'd like to fix something yourself:

1. Fork the repo
2. Make your changes in a branch named something descriptive (`fix/annotation-overlap`, `feature/docx-support`)
3. Test in at least Chrome and Firefox before submitting
4. Open a PR with a clear description of what changed and why
5. Link to any related Issue

Since this is a single-file HTML tool, keep changes self-contained. Do not add build systems, bundlers, or npm dependencies — the whole point is that it works by just opening `index.html`.

---

## What We Won't Accept

- Changes that embed or expose an API key in any form
- Changes that send document content anywhere other than directly to the Anthropic API
- Adding tracking, analytics, or any external services beyond PDF.js and the Anthropic API
- Style rule additions that aren't sourced to official Pitt documentation

---

## Code of Conduct

Be direct and respectful. This is a tool for a professional context — keep issues and PRs focused on the work.
