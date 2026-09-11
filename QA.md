# QA Evidence — Steady

## Completed QA rubric

| Check | Result | Evidence |
|---|---|---|
| Empty state explains the next action | Pass | “What needs your attention?” includes an example. |
| Empty input produces a clear error | Pass | A focused inline message appears without opening processing. |
| Natural-language input triggers a plan | Pass | Processing appears before an editable proposal. |
| User can change or remove suggestions | Pass | Task cards include a priority control and remove button. |
| Plan requires confirmation | Pass | The daily plan appears only after confirmation. |
| User can complete tasks | Pass | Confirmed cards toggle to a completed state. |
| Capacity changes the proposal | Pass | Low energy creates a shorter plan with one first action. |
| Mobile behaviour is supported | Pass | Controls and actions stack below 600px. |
| Adapted design is consistent | Pass | White canvas, black actions, yellow focus and pastel task markers follow DESIGN.md. |

## Before-and-after review evidence

Open [qa-evidence.html](qa-evidence.html) for the visual comparison.

### Before review

Four tasks had equal visual weight. For someone who said they felt overwhelmed, the next action was unclear.

### After review

The user can select **Low energy**. The plan then highlights a single “Start here” task and places the rest as secondary actions.

### Why it improved

The revised design lowers the effort of deciding what to do next, while responding only to user-selected capacity—not inferred mental state.

## Manual test path

1. Open `prototype.html` from the landing page, then enter a brain dump.
2. Select **Low energy** and build the plan.
3. Edit a priority or remove a task.
4. Confirm the plan and complete each task.
5. Repeat at narrow browser width.
