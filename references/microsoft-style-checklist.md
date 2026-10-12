# Style Checklist (Microsoft Writing Style Guide principles)

Quick reference. Summarized in original wording. For the full guide, see the official Microsoft Writing Style Guide.

## 1. Voice
- Warm and relaxed, crisp and clear, ready to lend a hand.
- Write the way people talk. Contractions are fine ("you'll", "don't").
- Lead with what matters to the reader.

## 2. Grammar
| Rule | Do | Don't |
|---|---|---|
| Active voice | The system sends an email. | An email is sent by the system. |
| Present tense | The app opens the dialog. | The app will open the dialog. |
| Second person | You can export reports. | Users can export reports. |
| Positive phrasing | Use a supported browser. | Don't use an unsupported browser. |
| Short sentences | Split at 25+ words | Long chained clauses |
| Conditions first | If you have admin rights, select **Edit**. | Select **Edit** if you have admin rights. |

## 3. Word choice
| Prefer | Avoid |
|---|---|
| use | utilize, leverage |
| start | initiate, commence |
| help | facilitate |
| need | require |
| before | prior to |
| about | approximately |
| can | is able to |
| select | click on |
| go to | navigate to |

Also avoid: "please", "simply", "just", "easy", "obviously", "etc.", "e.g.", "i.e.", "via", "and/or", "whitelist/blacklist" (use allowlist/blocklist), "master/slave" (use primary/secondary).

## 4. Capitalization and punctuation
- Sentence-style capitalization for headings, titles, button labels in text only if the UI uses it.
- Oxford comma in series.
- No periods in headings or short list items that are fragments.
- Use periods in list items that are full sentences.
- One space after a period.
- Avoid exclamation marks. Avoid ampersands in running text.
- Spell out numbers one to nine in prose. Use numerals for 10 and above. Always use numerals for versions, measurements, and UI values.

## 5. UI and interaction verbs
| Action | Verb |
|---|---|
| Click, tap a button, link, tab | **select** |
| Type in a field | **enter** |
| Choose from a list | **choose** or **select** |
| Turn a setting on or off | **turn on / turn off** |
| Check or clear a check box | **select / clear** |
| Open a menu | **open** |
| Move through UI | **Go to Settings > Users** |

- Bold UI labels exactly as shown in the product.
- Use `>` between menu levels: **Settings** > **Users** > **Add user**.
- Use code font for text the user must type exactly.

## 6. Procedures
1. Introduce with a goal: "To add a user:"
2. One action per step, verb first.
3. Put the location before the action: "On the **Users** page, select **Add**."
4. Add the result only if useful: "The **Add user** dialog opens."
5. Sub-steps use letters (a, b, c).
6. Optional steps start with "(Optional)".

## 7. Lists, tables, notes
- Intro sentence before every list.
- Keep list items parallel.
- Tables need headers. Don't use tables for layout.
- Note types: **Note** (helpful info), **Important** (needed to succeed), **Warning** (risk of data loss or harm).

## 8. Links and images
- Descriptive link text: "See [Configure SSO](#)" not "Click [here](#)".
- Don't put links inside procedure steps unless needed.
- Alt text describes purpose, not appearance.
- Don't rely on color alone to convey meaning.
- Avoid text inside images.

## 9. Accessibility and global readiness
- Plain language. No idioms, slang, or culture-specific references.
- Keep sentence structure simple and consistent for translation.
- Don't use directional words alone ("see below", "on the right"). Name the element.
- Write dates unambiguously (e.g., 12 October 2026 or 2026-10-12).

## 10. Technical content
- Code, commands, file paths, and parameters in code font.
- Placeholders in angle brackets and italic where supported: `<your-api-key>`.
- Use fictional, safe example data (Contoso, example.com, 203.0.113.0/24).
- Never show real keys, passwords, or customer data.
- Include language tags on code blocks.
- Show expected output for commands where it helps.
