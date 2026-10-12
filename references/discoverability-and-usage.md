# Discoverability and Usage

Good docs that nobody finds don't help anyone. Use this reference in **Improve** mode, or to add extras to any draft.

## 1. Make content findable (SEO and in-product search)

**Titles**
- Put the user's words first. Match how people search: "Reset your password", not "Credential management".
- Keep titles under about 60 characters.
- Make every title unique.
- Use symptom-based titles for troubleshooting ("Error 403 when exporting reports").

**First paragraph**
- State what the topic covers in the first 1-2 sentences. Search engines and AI tools often use it as the summary.

**Headings**
- Descriptive, task-focused, in sentence case.
- Use a logical H1 > H2 > H3 order. One H1 per page.

**Keywords and synonyms**
- Include terms users actually use (support tickets and search logs are the best source).
- Cover synonyms once: "remove (delete) a user".
- Spell out the acronym once, then use it.

**Metadata**
- Meta description: 120-160 characters, benefit-first.
- Add tags/labels for product, version, role, and task type.
- Add the version and "last updated" date.

**Linking**
- Link related concepts, tasks, and reference topics.
- Add "Next steps" and "Related" sections.
- Avoid orphan pages. Every page should have at least one inbound link.

**Error messages**
- Include exact error text and codes in docs, since users paste them into search.

## 2. Make content usable

**Structure**
- Separate concept, task, and reference content.
- Put the answer first. Don't bury it under background.
- Use short paragraphs, descriptive headings, lists, and tables so readers can scan.

**Navigation**
- Organize by user goals and roles, not by internal feature names.
- Provide a quickstart, a getting-started path, and a top tasks list.
- Keep navigation depth to 3 levels where possible.

**In-product integration**
- Add contextual help links from the UI to the exact topic.
- Link from error messages to the matching troubleshooting topic.
- Use tooltips and empty states for short guidance. Link out for detail.

**Layout**
- Make code easy to copy (copy button, no prompts in command blocks).
- Provide tabs for OS, language, or deployment variants.
- Use consistent templates so readers learn the pattern.

## 3. Reduce support load

- Build a top-10 issues list from support tickets and turn each into a topic.
- Add a "Before you contact support" checklist with log locations and info to include.
- Document every user-visible error message.
- Add short FAQs only for real, repeated questions.
- Review ticket themes monthly and update docs.

## 4. Measure and improve

| Signal | What it tells you | Action |
|---|---|---|
| Search with no results | Missing content or wrong terms | Add topic or synonyms |
| Top search queries | What users want | Improve top pages, add shortcuts |
| Page feedback (thumbs, comments) | Clarity issues | Fix lowest-rated pages |
| Exit rate / bounce on tasks | Content didn't help | Rework or link better |
| Support tickets tied to a topic | Doc gaps | Add detail or troubleshooting |
| Time on page for tasks | Too long or confusing | Simplify steps |
| Broken links | Trust issues | Run a link check each release |

## 5. Maintain and govern

- Assign an owner and a review date to every topic.
- Update docs as part of the definition of done for each feature.
- Version content. Mark deprecated features with removal dates and alternatives.
- Run a quarterly audit: remove, merge, or update stale topics.
- Keep a terminology list and use it consistently.
- Keep a changelog for docs updates.

## 6. Docs-as-code practices (when applicable)

- Store docs in Git with pull request reviews.
- Add linting (Vale with Microsoft style rules, markdownlint, link checkers) to CI.
- Preview builds for reviewers.
- Use templates and reusable snippets to keep content consistent.
- Tag releases so docs match product versions.

## 7. AI and machine readiness

- Write self-contained topics. Don't depend on "as mentioned above".
- Use clear headings and consistent terms so retrieval returns the right chunk.
- Put prerequisites and version info in the topic itself.
- Use structured elements (tables, labeled steps) for facts.
- Keep an `llms.txt` or clean sitemap if your platform supports it.
- Review AI-generated answers about your product regularly and fix the source docs when answers are wrong.

## 8. Accessibility and localization

- Meaningful alt text, captions for video, sufficient color contrast.
- Don't rely on color or position alone.
- Keep strings simple and free of idioms to ease translation.
- Avoid text in images.
- Plan for text expansion in translated UI.
