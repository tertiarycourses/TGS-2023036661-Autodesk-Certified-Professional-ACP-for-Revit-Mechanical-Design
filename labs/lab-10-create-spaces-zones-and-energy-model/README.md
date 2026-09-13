# Lab 10 — Create spaces zones and energy model

**Course:** Autodesk Certified Professional (ACP) for Revit Mechanical Design (TGS-2023036661) · **Topic 4:** Analysis for mechanical design · **Version:** v7.0

## Starting model and assets

`Architectural-Starter.rvt` is an architectural coordination starter, not a completed MEP model. `assets/design-brief.csv` gives exercise values; `assets/evidence-register.csv` captures acceptance evidence.

## Goal

Create energy model and zone mapping. Primary focus: rooms, spaces, analytical surfaces and zones.

## Detailed procedure

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for rooms, spaces, analytical surfaces and zones; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Analyze > Energy Settings: record model mode and assumptions.

6. Analyze > Spaces: verify enclosed boundaries on linked architecture.

7. Create Energy Model; inspect analytical spaces, surfaces and zone assignment.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

## Acceptance checks

- Working RVT opens without unresolved link warnings.

- New mechanical elements are in Mechanical-Working.rvt; architectural starter remains unchanged.

- System Browser, schedule, relevant view and evidence register agree.

- Exported PDF carries the same model revision and units.

## Troubleshooting

- If the architectural file upgrades on open, save a separate upgraded copy and record its Revit version.

- If a connector is unassigned, check family connector classification, direction and system type before re-creating the system.

- If flow or load differs, trace terminal settings, space/zone assignment, units and sizing constraints.

## Source

Autodesk Revit 2026 Mechanical Engineering and Analysis Help: https://help.autodesk.com/view/RVT/2026/ENU/
