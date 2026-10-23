# Project Validation Record

Use this checklist before labeling a PLC project as **tested** or **completed**.

## Project details

- Software and version:
- PLC / simulator target:
- Project file:
- Date tested:

## Test cases

| Test | Expected behavior | Actual result | Pass / fail |
|---|---|---|---|
| Activate I1 only | OR output activates | Not tested yet | Pending |
| Activate I2 only | OR output activates | Not tested yet | Pending |
| Activate I3 only | OR output activates | Not tested yet | Pending |
| Activate I4 only | OR output activates | Not tested yet | Pending |
| Activate more than one input | OR output remains logically active while any input is active | Not tested yet | Pending |
| Check pulse-relay behavior | Output changes state according to the selected LOGO! block configuration | Not tested yet | Pending |
| Check Q1 | Q1 follows the configured output logic | Not tested yet | Pending |

## Evidence to attach

- Screenshot of the LAD circuit
- Screenshot of the equivalent FBD circuit
- Simulation screenshots for the test cases above
- Native LOGO! project file, if safe and possible to share

## Release rule

Do not mark the project as **tested** until the test cases have been run in the target software and the actual results have replaced the pending entries. The pulse-relay block's precise behavior must be checked against the selected LOGO! Soft Comfort version and configuration.