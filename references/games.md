# Game design and development craft

Read alongside SKILL.md when making or revising a game. Treat the game as an experience with decisions, rules, feedback, and progression. An attractive scene with moving objects is not evidence of a playable game.

## Understand the game before styling it

For a new concept, record a compact design brief:

- **Player fantasy:** who the player is and what they want to feel capable of doing.
- **Core verbs:** what the player repeatedly does and what feedback makes those actions readable.
- **Core loop:** action -> feedback -> consequence -> next meaningful decision.
- **Tension:** what competes for attention, resources, position, information, or time. Identify the tradeoff that makes choices interesting.
- **Rules and boundaries:** available actions, constraints, progression, and completion. State win/loss/retry rules where applicable; for an open-ended game, state goals, consequences, and restart behavior instead of forcing competition.
- **Design pillars:** a few priorities that can reject an attractive but inappropriate feature.
- **Constraints:** target device, input, session length, audience, asset budget, performance, and accessibility.

For existing games, inspect the established loop and pillars before changing mechanics or presentation. Ask about contradictions that prevent a coherent design; do not turn every unknown into a discovery meeting.

## Derive the art from the mechanics

Compare plausible visual and interaction directions against what the player must perceive and decide. A stealth game needs readable visibility and threat cues; a precision platformer needs readable collision boundaries and landing surfaces; a contemplative puzzle needs legible state changes and thinking space. Do not assign neon, pixel art, low-poly models, or particle effects by default.

Define silhouette, scale, contrast hierarchy, camera, environment density, interface placement, animation timing, and audio roles. Give hazards, goals, interactables, and background detail distinct visual or auditory priorities. Keep effects from concealing information necessary for fair play. Make the HUD answer player questions rather than imitate a generic game dashboard.

Example: for navigation by sound, compare a spatial landscape, a tactile map, and a restrained acoustic visualization. Choose according to the intended uncertainty and available input/audio. Specify how players learn the sound grammar, what choice each cue enables, and which alternatives preserve play for people who cannot use stereo audio. Avoid claiming lived-experience authenticity without appropriate research or feedback.

## Prove one complete slice

Build a small playable sequence that includes entry, learning, meaningful play, consequences, completion or intentional continuation, and restart. Implement reliable rules and input before expanding content or adding cosmetic effects.

Teach through a safe first action, clear feedback, a small variation, and then a meaningful combination. State what the first minute should teach and how the player demonstrates understanding. Introduce difficulty through decisions and mastery; do not substitute unexplained numerical increases.

Make movement, collision, interaction range, timing, camera, and feedback consistent. Add buffering, forgiveness, or aim assistance only where the intended experience benefits. Preserve intentional challenge while removing accidental confusion.

Check pause, resume, reset, loss of focus, audio activation, mute, and supported input transitions where applicable. Restart must reset gameplay state, timers, spawned objects, score, and input correctly. Avoid creating a technically complete loop whose only activity is waiting or performing a trivial repeated action.

## Playtest as a developer and designer

Actually play the slice when runtime tools permit. Use debug controls for inspection, then play through ordinary controls as well. Observe what happens; do not infer fun from source code or the presence of effects.

| Session | Observe |
| --- | --- |
| First entry | Can a new player identify an available action, its effect, and the immediate goal? |
| Ordinary play | Are choices meaningful and consequences understandable? Where does pacing stall? |
| Failure and recovery | Can the player understand what happened, retry, and improve? Is state clean after restarting? |
| Boundary behavior | Do rapid inputs, collisions, leaving bounds, repeated retries, and interrupted play break the rules? |
| Input and accessibility | Are the supported controls reachable and readable? Can essential cues survive relevant sound, color, or motion limitations? |
| Performance | Does the busiest representative sequence stay within the chosen device/frame budget? Are simulation and controls stable across frame rates? |

Record device, input, scenario, observed behavior, and concrete issues. Measure performance instead of inferring it from an empty scene. Use the findings to adjust readability, timing, challenge, or controls before producing more levels.

Separate bugs, comprehension failures, balance problems, and taste preferences. When real players are available and participation is authorized, observe without explaining every action. Do not report self-play as an independent user study or invent completion rates. If real playtests are unavailable, label the result as developer-tested and leave audience appeal unvalidated.

## Completion standard

Deliver a working loop with understandable goals, meaningful agency, responsive controls, coherent art, readable consequences, appropriate progression, and reliable recovery. Identify which claims were tested and which remain hypotheses. Present unfinished content, placeholder assets, unsupported devices, and untested accessibility honestly.
