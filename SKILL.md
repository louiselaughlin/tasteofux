---
name: tasteofux
description: Guide product and UI feature generation with a short, interactive UX intake and a review of the result. Use when asked to design, prototype, or build a new or materially changed feature, screen, or user flow. Reuse answers from the brief and conversation, and ask only about relevant gaps.
---

# Taste of UX

Before generating the feature, review the current request, earlier turns about the same feature, and supplied designs or briefs. Use the questions below as a checklist.

- Treat an answer as covered when the user states it or it follows clearly from what they shared. A single statement can answer multiple questions. Accept answers in free text, in any order.
- Keep track of covered, partial, and open answers within the conversation. Use the latest clarification when the user changes an answer. If an answer is partial or conflicts with another source, ask only about the part that affects the feature.
- Ask the most consequential open questions first, in small batches of up to three. Use the available interactive input tool when appropriate, or ask in chat. Tailor the wording to the feature. After each reply, apply it to the whole checklist before deciding what to ask next.
- Begin generating once you have enough to make the material design decisions. If the user delegates an answer, defers it, or asks you to proceed, use a reasonable assumption where needed and disclose it with the result.

## Context

- Who is the user?
- How and when will they be using this feature?
- What is their intention?
- What problem is this solving?

## Content

- What data do we want to show?
- What information is most important?

## Consistency

- Is a design system available to use?

Honor a system the user already chose and accept an explicit answer that there is none. Otherwise, check the brief, supplied references, and relevant local project before asking. Look for design-system documentation, Storybook configuration and stories, shared UI packages, and theme or token files. Check what the target app actually imports or documents as supported. Treat a library, its tokens, and its Storybook as one system. A dependency or Storybook configuration by itself is only a lead. Limit discovery to the current project and local locations the user supplied.

- If you find one applicable system, name it and reuse its components and tokens.
- If you find multiple applicable systems and the user has not chosen one, ask which to use. List the systems by name with a short note about where each is used.
- If you find no applicable system and availability is unknown, ask the question above. If the user already said a system exists but you cannot locate it, ask where to find it instead.

Resolve any open design-system question in an intake batch before generating, even if the other answers are sufficient. If the user defers the question or asks you to proceed, continue with the information available and disclose any assumption.

## Click throughs

- Where does the feature live in the product?
- What actions can the user take?
- Where can they go from here?

## Quality control

- Does it solve the problem?
- What are our measures of success?

Ask about missing success measures during intake when they would change the design or how it will be evaluated. After generating the feature, use the agreed problem and success measures to review the result. Walk through the main user action and destination where possible. Report what you verified and flag any measures that require user feedback or live data. If the user's judgment is needed to establish whether the result solves the problem, ask a focused follow-up about the generated feature.
