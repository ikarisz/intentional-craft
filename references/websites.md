# Website and interface craft

Read alongside SKILL.md when the artifact is a website or application interface. Scale this review to the requested change.

## Compose around the real task

Identify the first useful action and the information needed to take it confidently. Build the page order from that decision process. A booking site, publication, operational dashboard, and artist's portfolio need different structures.

For new work, compare directions in concrete terms. A ceramics workshop might use a documentary studio visit, a functional class timetable, or a process-led visual essay. Select based on visitors' needs and available content; do not automatically select warm beige, a serif headline, or a three-card layout because the subject is handmade.

Define the primary journey through completion and recovery. Put price, availability, terms, location, or other decisive facts where the user needs them. If facts are unavailable, mark them as missing rather than inventing plausible values.

## Give the project a visual grammar

- **Composition:** establish a clear first focal point, supporting information, and intentional quiet space. Vary density with content importance. Avoid repeating the same section container down the whole page.
- **Typography:** choose for reading, language support, tone, and contrast between roles. Test actual headlines and realistic long content. Check Thai marks, line height, wrapping, mixed numerals, and fallback fonts when Thai is used.
- **Color:** give each color a function. Maintain readable text and discoverable interactive states. Do not communicate status through color alone.
- **Imagery:** use relevant, permitted assets with purposeful crop and focal point. Keep image treatment consistent. Never invent client logos, customer portraits, awards, or evidence of real work.
- **Rhythm:** align spacing, widths, baselines, borders, and corner treatments into a small coherent system; allow intentional exceptions where content benefits.
- **Motion:** clarify causality, hierarchy, or orientation. Keep essential information available without animation and honor reduced-motion settings. Avoid scroll hijacking, forced preload spectacles, and custom cursors that impair ordinary use.
- **Copy:** use specific nouns, concrete benefits, useful labels, and an appropriate voice. Replace unsupported superlatives and generic marketing prose with actual information.

Write the distinctive gesture as a reasoned choice: “Use a contact-sheet sequence to help visitors compare the actual workshop stages,” rather than “make it premium and cinematic.” Expressive structure must also work on small screens.

## Make interaction trustworthy

Every visible control needs a clear outcome and feedback. Use semantic elements and accessible names. Preserve input after failures, explain how to recover, prevent accidental duplicate submission where relevant, and distinguish a pending request from a completed action.

Make key actions work without hover. Check keyboard order, visible focus, touch operation, escape and focus restoration for overlays, browser back behavior, and navigation consistency where applicable. Do not hide meaningful content in decorative interactions.

## Verify by attempting real tasks

Select representative narrow and wide viewports from the target audience. Add an intermediate width when the layout changes. Test actual content extremes, text enlargement, and slow or failed loading where they affect the journey.

Use this as a selection guide, not a claim that automated checks cover everything:

| Check | Evidence to collect |
| --- | --- |
| Main journey | Reach its actual success state using real controls; identify mock or unavailable external steps |
| Recovery | Trigger applicable invalid, unavailable, failed-network, or empty states; retry successfully without avoidable data loss |
| Responsive layout | Inspect rendered screens for overflow, clipped content, unreadable type, obscured actions, and awkward image crops |
| Input access | Complete the relevant journey with keyboard and touch; inspect focus and labels; test assistive technology when available |
| Reduced motion and zoom | Confirm essential content and controls remain reachable and understandable |
| Content integrity | Verify links, language, factual copy, images, status messages, and truthful loading or completion feedback |
| Performance | Measure loading and interaction on a stated device/profile; connect problems to assets, fonts, scripts, or rendering |
| Art direction | Compare the actual rendered result with the direction card and substitution test |

Capture representative renders and record environment, action, observed result, and unresolved issue. Do not equate a desktop browser resized to a phone width with testing on an actual phone. Distinguish measured results, expert inspection, and feedback from real people.

## Release decision

Fix broken journeys, misleading controls, inaccessible primary actions, and unreadable content before decoration. When the user requested a narrow repair in an established system, preserve that system and demonstrate the repair; stylistic novelty is not a release requirement for that task.
