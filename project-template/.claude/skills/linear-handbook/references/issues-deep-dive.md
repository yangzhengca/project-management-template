# Issues — Deep Dive

## Tags/Labels

Tags exist to provide additional context and filtering, not to replace structure.

Tags should: add clarity, improve reporting, enable filtering, indicate type or category of work.

Use workspace-wide tags for cross-functional understanding. Team-specific tags can extend this within a given domain.

### When to Use Tags
- Work type: Bug, Tech Debt, Research, Optimization
- Cross-functional visibility
- Temporary classifications (e.g., "Launch Support")

### Tag Discipline
- Use standardized tags only (no custom one-offs without collective agreement)
- Avoid duplicate tags with slightly different wording
- Remove outdated tags when scope changes
- Do not use tags to group strategic work — use Projects or Initiatives instead

Tag sprawl reduces clarity.

## Q&A

**Q: Can an Issue exist without a Project?**
Yes. Standalone operational or small-scope work does not require a Project. Only assign to a Project if it directly contributes to a defined outcome.

**Q: Can an Issue have multiple owners?**
No. Exactly one accountable owner. Collaboration is allowed; accountability is singular.

**Q: What if I'm unsure about the estimate?**
If the estimate cannot be assigned confidently, the issue is under-scoped. Clarify scope before committing.

**Q: What if scope grows mid-cycle?**
Reassess the EU. If the issue exceeds 8 EU, split it. Do not silently expand scope.

**Q: What qualifies as Done?**
Done means: acceptance criteria fully met, required review complete, stakeholders validated (if required). Done does NOT mean "I stopped working on it."

**Q: Can I add work mid-cycle?**
Yes, but: it must be visible, sized, trade off against existing committed work, and the lead must be aware. Silent additions distort forecasting.

**Q: What if an issue was in progress then stopped?**
"In Progress" means active execution is happening. If work pauses:
- Blocked by dependency → Move to Blocked (include written explanation)
- Deprioritized → Move back to Planned
- Intentionally paused, expected to resume → Leave a comment, reassess within 48 hours

Issues must never sit In Progress without visible activity or explanation.
