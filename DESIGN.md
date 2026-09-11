# DESIGN.md — Steady

## Design reference and adaptation

**Reference:** The [Miro design-system analysis on Get Design MD](https://getdesign.md/miro/design-md): a white canvas, black pill actions, bright yellow accents, pastel sticky-note moments, and an infinite-canvas sensibility.

**Adaptation:** Steady applies these principles to individual planning. It is not a Miro clone and must not use Miro logos, product names, illustrations, or brand claims. Yellow highlights the first action; pastel task markers make a plan tangible; the surrounding canvas remains quiet for a user who feels overwhelmed.

## Product position

Steady is a focused planning layer, not a general AI agent. It reduces the work of structuring a plan while leaving every decision and action with the user.

## Experience principles

1. **Human in control:** Suggestions remain editable until confirmation.
2. **Reduce, do not add:** Low energy means fewer tasks and one clear first step.
3. **Visual momentum, not urgency:** Use accents to guide attention, never pressure or dense dashboards.
4. **Transparent simulation:** Documentation states that prototype AI output is scripted.

## Design tokens

| Token | Value | Use |
|---|---:|---|
| Canvas | `#FFFFFF` | Main surfaces |
| Surface | `#F7F8FA` | Quiet controls |
| Ink | `#1C1C1E` | Primary text and buttons |
| Yellow | `#FFD02F` | First action and emphasis |
| Yellow light | `#FFF4C4` | Selected capacity and task card |
| Blue | `#4262FF` | Focus, links, completion |
| Teal light | `#C3FAF5` | Completion feedback |
| Coral light | `#FFC6C6` | Secondary task marker |
| Hairline | `#E0E2E8` | Borders and grid |

Use DM Sans, a modern geometric sans serif. Hero text is 44–76px at 600 weight; body text is 16px at 1.5 line height; labels are 11px uppercase. Use a 4px spacing base and 8px increments. Inputs use 8px corners, task cards 12px, main containers 16px, and buttons full pills.

## Core flow and states

Natural-language input → optional capacity choice → processing → proposed plan → edit → confirmation → in progress → complete.

- **Empty/input:** Clear writing area and optional pill-shaped capacity controls.
- **Processing:** Compact yellow object with restrained motion.
- **Proposed plan:** White editable task stack; first action has yellow emphasis and others use pastels.
- **Confirmation:** Black pill button confirms the user—not the AI—is committing the plan.
- **In progress:** Blue completion feedback.
- **Error:** Concise inline message near input.

## Responsive behaviour

- **Mobile (<480px):** One column, 36px hero, stacked controls and full-width actions.
- **Tablet (480–1023px):** Single focused column; capacity choices wrap naturally.
- **Desktop (≥1024px):** Centred planning canvas with generous whitespace.

## Emotional-awareness boundary

Respond only to what the user explicitly expresses or selects. A low-energy choice can reduce task size and number. Never infer mood, diagnose conditions, provide therapy, or provide medical advice.
