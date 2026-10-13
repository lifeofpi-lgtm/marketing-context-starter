# Handoff

## 2026-10-05 session

### Changes made
- Created `outputs/first-outline.md`, a draft five-point newsletter outline on
  keeping AI context across tools. The five points are: (1) your best AI context
  is trapped in chat history, (2) put the context in plain files you own,
  (3) reuse the same files in any AI tool, (4) use GitHub as a save history, not
  a developer tool, (5) start small with one project. It also has headline
  options, an opening hook placeholder, a call-to-action placeholder, and a list
  of six missing items.
- In `outputs/first-outline.md`, marked four claims with **[FACT-CHECK]**: three
  chat-memory claims in Point 1 ("every new chat starts from zero", "switching
  tools means losing that background entirely", "context in a chat box belongs
  to that chat") and the "point a tool at the folder" method in Point 3. Added a
  note above Point 1 saying several AI tools now offer memory or project features.
- Rewrote `handoff.md` with current status, next action, and six open questions.
- Added a "Suggestions (not approved)" section to `decisions.md` with three
  unapproved suggestions taken from the outline.
- The user committed these changes in GitHub Desktop as commits 734f812 and
  279ef28 in the `marketing-context` repository.

### Verified
- Ran `git status --short` in the project folder after editing: exactly
  `handoff.md`, `decisions.md`, and `outputs/first-outline.md` were modified.
- Searched all three files for em-dash characters with grep: none found.
- The outline contains no statistics, quotes, customer results, or sources.

### Not verified
- None of the [FACT-CHECK] claims have been checked against any AI tool's
  documentation. Do not draft prose from Points 1 or 3 until they are.
- Point 4's description of GitHub and GitHub Desktop (stores folders, keeps every
  saved version, lets you review and save without typing commands) was not
  checked against GitHub's documentation.
- The user has not reviewed or approved the outline content.

### Deferred
- Review `outputs/first-outline.md` and approve, cut, or reorder the five points.
- Fact-check every [FACT-CHECK] item, then narrow the wording (for example,
  "often" or "by default") wherever a tool has memory or project features.
- Answer the six open questions listed below.

## Objective
Create a practical newsletter outline about keeping AI context across tools.

## Current status
A first five-point outline exists in outputs/first-outline.md. It is a draft for
review and has not been approved.

## Confirmed decisions
- Write for marketers who have never used GitHub.
- Keep the first demonstration small and free of client information.

## Next action
Review outputs/first-outline.md. Approve, cut, or reorder the five points, then
answer the open questions below. After that, fact-check every [FACT-CHECK] item
against current product documentation before drafting.

## Open questions
- Which personal example should introduce the finished article?
- Which claims will need sources before publication? (Start with the
  [FACT-CHECK] items in Points 1 and 3.)
- Which AI tools have you personally used this workflow with?
- What should the call to action be?
- Will you share starter templates, and where would they live?
- What is the target length, and is this one issue or a series?
