# Prompt Pack: Token Contrast Demos

This pack demonstrates prompting contrasts for the same objective: implement and improve an issue by applying local changes.

Shared objective:

- 01 works on issue #1.
- 02-08 work on issue #13.
- All prompts apply the solution as local changes.
- None of them commit, push, or create issues/PRs, so changes can be reverted before testing another prompt.

Recommended pairs:

1. Scope and style: 01 (issue #1, freeform) vs 02 (issue #13, concise)
2. Format: 03 (freeform output) vs 04 (fixed table)
3. Restriction: 05 (open) vs 06 (1 sentence + 3 bullets)
4. Verbosity: 07 (explanation + code) vs 08 (code only)

How to use:

1. In chat, type `/` and select a prompt from this pack.
2. Run the prompt (01 for issue #1, the rest for issue #13).
3. Review and compare the local changes.
4. Revert the changes before trying the next prompt.

What to compare:

- Response length and clarity
- Actionability and quality of the applied change
- Token cost
