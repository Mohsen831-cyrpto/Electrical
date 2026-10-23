# LOGO! Soft Comfort — Push-Button Pulse-Relay Exercise

**Status:** Learning exercise / implementation documentation in progress  
**Environment:** Siemens LOGO! Soft Comfort  
**Languages:** LAD and FBD

## Objective

Build and test a small control circuit in which four push-buttons feed an OR function, and the resulting signal controls a pulse relay whose output drives `Q1`.

This page records the exercise requirements. It does **not** claim that a finished LOGO! program or a verified simulation has been uploaded yet.

## Functional concept

- Inputs: four push-buttons (`I1`–`I4`)
- Logic: OR function
- Switching element: pulse relay / latching toggle function, as required by the assignment
- Output: `Q1`

Conceptually:

```text
I1 ─┐
I2 ─┤
I3 ─┼──> OR ──> Pulse relay ──> Q1
I4 ─┘
```

## Important implementation note

The exact behavior of a pulse relay depends on the LOGO! function block and its parameters. Before treating the circuit as complete, verify in LOGO! Soft Comfort that:

1. Each intended button press produces the expected input pulse.
2. The OR output behaves correctly when any one of the four inputs is activated.
3. The pulse relay changes state as intended.
4. `Q1` follows the relay state.
5. Simultaneous button presses and button-release behavior do not create unexpected switching.

## Verification

Use the [test plan](TEST-PLAN.md) to record the software version, expected behavior, actual results, and evidence. Do not label the exercise as tested until it has been simulated and the results have been recorded.

- [ ] Draw the circuit in LAD.
- [ ] Recreate the equivalent logic in FBD.
- [ ] Simulate each input individually.
- [ ] Check simultaneous inputs.
- [ ] Save screenshots of the final LAD and FBD diagrams.
- [ ] Add the tested project file or screenshots to this folder.

## Next steps

Once the circuit is built and tested, add the actual block configuration, screenshots, test results, and the LOGO! project file if it can be shared safely.

---

*Educational documentation only. Confirm the block behavior in the target LOGO! Soft Comfort version before using the design in any real installation.*