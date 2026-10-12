# Document Templates

Use the template that matches the doc type. Replace placeholders. Mark unknowns as `[CONFIRM: ...]`.

---

## 1. Release notes

**Principles:** Lead with user benefit. Group by type. Be specific. Link to details. Date and version everything.

```markdown
# <Product> <version> release notes

**Release date:** <date>
**Applies to:** <editions / regions / deployment types>

## Highlights
<2-3 sentences on the most important changes and why they matter.>

## New features
### <Feature name>
<What you can now do and why it helps. 1-3 sentences.>
**Availability:** <plans / roles / regions>
[Learn more](link)

## Improvements
- <Area>: <What changed and the user benefit.>

## Fixed issues
- **<ID>**: <What was wrong, in user terms. What now works.>

## Known issues
- **<ID>**: <Symptom.> **Workaround:** <steps or "None".>

## Deprecations and removals
- <Item>: <What changes, when, and what to use instead.>

## Upgrade notes
<Prerequisites, breaking changes, required actions.>
```

**Tips**
- Write from the user's view, not the code view. Not "Refactored the parser" but "Imports now finish up to 3x faster."
- One change per bullet.
- Don't expose internal ticket jargon or confidential details.
- Call out breaking changes at the top.

---

## 2. Defect fix documentation

Use for resolved issues and known issues.

```markdown
# <Short, symptom-based title>

**Issue ID:** <ID>
**Status:** Resolved | Known issue | Workaround available
**Affected versions:** <range>
**Fixed in:** <version or "Not yet fixed">
**Severity:** <Critical | High | Medium | Low>

## Symptoms
<What the user sees. Include the exact error text in code font.>

## Cause
<Plain-language reason. Skip internals the user doesn't need.>

## Resolution
<What was fixed, or the steps to resolve.>

## Workaround
1. <Step>
2. <Step>

## Verify the fix
<How to confirm it worked.>

## Related
- <Links to related topics>
```

**Tips**
- Title with the symptom users would search for.
- Always include the exact error message text.
- Separate "Cause" from "Resolution" so readers can skip ahead.

---

## 3. Installation / setup guide

```markdown
# Install <Product>

<One sentence on what the reader will have when done.>

## Before you begin
### System requirements
| Component | Minimum | Recommended |
|---|---|---|

### Prerequisites
- <Accounts, permissions, network, ports, dependencies>

## Install <Product>
1. <Action.>
   ```
   <command>
   ```
   Expected output:
   ```
   <output>
   ```
2. <Action.>

## Verify the installation
<Command or UI check, and what success looks like.>

## Configure (optional)
<Link to configuration topic.>

## Troubleshooting
| Symptom | Cause | Fix |
|---|---|---|

## Uninstall / rollback
<Steps.>

## Next steps
- <Link: first task, quickstart>
```

**Tips**
- Separate OS-specific steps with tabs or clear sub-headings.
- State required permissions up front.
- Always include verify and rollback steps.

---

## 4. Feature documentation (concept + reference)

```markdown
# <Feature name>

<1-2 sentences: what it is and the problem it solves.>

## Benefits
- <Benefit>

## How it works
<Short explanation. Add a diagram if it helps.>

## Requirements and availability
- Plans / editions: <>
- Roles and permissions: <>
- Limits and quotas: <>

## Key concepts
| Term | Definition |
|---|---|

## Common use cases
- <Scenario>

## Settings reference
| Setting | Description | Default | Values |
|---|---|---|---|

## Limitations
- <Known limitations>

## Related tasks
- <Links to how-tos>
```

**Tips**
- Keep concept topics free of long procedures. Link to tasks instead.
- Put availability early so readers don't waste time.

---

## 5. Procedure / how-to (task topic)

```markdown
# <Verb> <object>

<One sentence on when and why to do this.>

## Before you begin
- <Prerequisite or permission>

## Steps
1. <Verb-first action.>
2. <Action.> <Result if not obvious.>
3. <Action.>

## Result
<What the user should see or have.>

## Troubleshooting
- **<Symptom>**: <Fix.>

## Related
- <Link>
```

**Tips**
- Title starts with a verb (gerund optional if your team uses it, but stay consistent).
- One goal per topic.
- 7 or fewer steps where possible.

---

## 6. Troubleshooting topic

```markdown
# Troubleshoot <problem>

## Symptoms
<What the user sees.>

## Possible causes
1. <Most likely cause>
2. <Next cause>

## Solutions
### Solution 1: <Name>
1. <Step>
### Solution 2: <Name>

## Still having trouble?
<Link to support, logs to collect, info to include in a ticket.>
```
