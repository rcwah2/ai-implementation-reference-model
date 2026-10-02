# Article Archive — Versioning and Archive Policy

This folder keeps every superseded version of the articles in this series. The current version of each article stays in [`articles/`](../) at the same file name and the same Substack link. When an article changes, the previous version is copied here first, unchanged, so readers can see exactly what an earlier version said.

All changes are recorded in the [Article Change Log](../CHANGELOG.md).

## Version Numbers

| Change | Version increase | Examples |
|---|---|---|
| Substantive revision | Major: v1.x → v2.0 | Restructured argument, new or removed sections, changed conclusions |
| Regulatory update, correction, or clarification | Minor: v1.0 → v1.1 | Revised regulatory dates or requirements, corrected facts or links, clarified wording that changes meaning |
| Editorial | None; logged only | Typos, formatting, or grammar that do not change meaning. No archive copy is made |

## File Naming

Archived copies use the article's file name with its version number:

```
archive/article-<number>-<slug>-v<major>.<minor>.md
```

Companion articles follow the same pattern with a `companion-<number>` prefix, for example `archive/companion-1-your-ai-model-works-but-does-the-system-v1.0.md`.

Example: when Article 3 moves from v1.0 to v1.1, the v1.0 text is saved as
`archive/article-3-phase-0-enterprise-discovery-and-readiness-v1.0.md`.

Each archived copy begins with a notice:

```markdown
> **Archived version.** This is v1.0 of this article, superseded on YYYY-MM-DD by v1.1.
> Read the [current version](../article-3-phase-0-enterprise-discovery-and-readiness.md).
> See the [change log](../CHANGELOG.md) for what changed and why.
```

Apart from that notice, archived copies are not edited.

## Update Process

1. **Propose.** A proposed change, such as one from the monthly regulatory review, is listed under Pending Changes in the change log.
2. **Approve.** The author approves, rejects, or holds it. Nothing is published before approval.
3. **Archive.** Copy the current article into this folder with its version number and add the archive notice.
4. **Update.** Edit the current article in `articles/` and update its version.
5. **Update Substack.** Edit the published post in place, keeping the same link, and add a dated update note at the top that links to the change log. Optionally add a comment or Substack Note announcing the update.
6. **Log.** Record the change in the change log with the commit, the Substack update date, and a link to the archived version.

## Update Note Format for Substack

```markdown
**Updated YYYY-MM-DD (v1.1):** [One-sentence description of the change and the regulation involved.]
See the [change log](https://github.com/rcwah2/ai-implementation-reference-model/blob/main/articles/CHANGELOG.md)
and the [previous version](https://github.com/rcwah2/ai-implementation-reference-model/blob/main/articles/archive/<file>).
```

## Archived Versions

| Article | Version | Superseded on | Superseded by | File |
|---|---|---|---|---|
| Article 3 — Phase 0 — Enterprise Discovery and Readiness | v1.0 | 2026-10-02 | v2.0 | [article-3-phase-0-enterprise-discovery-and-readiness-v1.0.md](article-3-phase-0-enterprise-discovery-and-readiness-v1.0.md) |
