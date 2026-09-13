# Autodesk Certified Professional (ACP) for Revit Mechanical Design — Learner Guide

TGS-2023036661 · v7.0 · 14 September 2026

TERTIARY INFOTECH ACADEMY PTE LTD

LEARNER GUIDE

Autodesk Certified Professional (ACP) for Revit Mechanical Design

WSQ Course Code: TGS-2023036661

Version v7.0 · 14 September 2026

UEN 201200696W

## Document Version Control Record

TABLE OF CONTENTS

## Course learning outcomes

- LO1: Execute mechanical calculations and build conceptual duct and piping designs with a Basis of Design.

- LO2: Produce coordinated mechanical schedules, plans, sections, sheets and revisions.

- LO3: Create and validate MEP families, connectors and parameters for accurate BIM models.

- LO4: Review analytical spaces, zones, energy inputs and calculated values against project criteria.

- LO5: Coordinate linked models, clashes, standards and handover evidence efficiently.

## Required environment

- Licensed desktop Autodesk Revit with Mechanical/MEP tools and compatible RVT version.

- A new Mechanical project file for each lab. The supplied architectural RVT is only a coordination starter.

- Use the same project units, linked coordinates, equipment schedule and Basis of Design throughout.

## Topic 1: Modeling for mechanical design

Criteria: K1 K2 A1 A2

### Mechanical equipment and system classification

Inspect the Revit object and its category/system assignment for Mechanical equipment and system classification. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if mechanical equipment and system classification is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Air terminals and design airflow

Inspect the Revit object and its category/system assignment for Air terminals and design airflow. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if air terminals and design airflow is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Supply, return and exhaust duct systems

Inspect the Revit object and its category/system assignment for Supply, return and exhaust duct systems. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if supply, return and exhaust duct systems is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Duct types, routing and fittings

Inspect the Revit object and its category/system assignment for Duct types, routing and fittings. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if duct types, routing and fittings is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Duct sizing and pressure loss

Inspect the Revit object and its category/system assignment for Duct sizing and pressure loss. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if duct sizing and pressure loss is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Plumbing fixtures and pipe systems

Inspect the Revit object and its category/system assignment for Plumbing fixtures and pipe systems. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if plumbing fixtures and pipe systems is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Hydronic equipment and pipe sizing

Inspect the Revit object and its category/system assignment for Hydronic equipment and pipe sizing. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if hydronic equipment and pipe sizing is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Fire protection sprinklers and branch flow

Inspect the Revit object and its category/system assignment for Fire protection sprinklers and branch flow. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if fire protection sprinklers and branch flow is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### System Browser and unassigned connectors

Inspect the Revit object and its category/system assignment for System Browser and unassigned connectors. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if system browser and unassigned connectors is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Lab 01: Establish MEP project and link architecture

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for linked architecture, levels, shared coordinates; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Manage > Project Units: verify length, airflow and pressure units.

6. Insert > Link Revit: place the architecture file; compare levels and grid intersection.

7. Manage > Coordinates: record the positioning method and shared-coordinate status.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 02: Place equipment and air terminals

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for AHU, diffusers, flow assignment; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Systems > Mechanical Equipment: place the AHU family.

6. Systems > Air Terminal: place three terminals in the occupied spaces.

7. Properties > Flow: set 250, 300 and 350 L/s and check connector classifications.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 03: Build and size a duct system

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for supply duct, branches, fittings and sizing; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Select terminals > Create Duct System > Supply Air.

6. Select equipment > Generate Layout; inspect proposed route and finish layout.

7. Select the system > Duct/Pipe Sizing; compare sizes with the velocity target and warnings.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

## Topic 2: Documentation for mechanical design

Criteria: K3 K4 A3 A4

### View templates and discipline visibility

Inspect the Revit object and its category/system assignment for View templates and discipline visibility. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if view templates and discipline visibility is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Mechanical plans, sections and callouts

Inspect the Revit object and its category/system assignment for Mechanical plans, sections and callouts. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if mechanical plans, sections and callouts is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Duct and pipe schedules

Inspect the Revit object and its category/system assignment for Duct and pipe schedules. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if duct and pipe schedules is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Equipment schedules and calculated fields

Inspect the Revit object and its category/system assignment for Equipment schedules and calculated fields. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if equipment schedules and calculated fields is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Sheets, titleblocks and viewports

Inspect the Revit object and its category/system assignment for Sheets, titleblocks and viewports. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if sheets, titleblocks and viewports is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Revision clouds and issue metadata

Inspect the Revit object and its category/system assignment for Revision clouds and issue metadata. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if revision clouds and issue metadata is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Phasing for existing and new systems

Inspect the Revit object and its category/system assignment for Phasing for existing and new systems. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if phasing for existing and new systems is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Tags, keynotes and annotation families

Inspect the Revit object and its category/system assignment for Tags, keynotes and annotation families. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if tags, keynotes and annotation families is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Drawing QA and coordination notes

Inspect the Revit object and its category/system assignment for Drawing QA and coordination notes. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if drawing qa and coordination notes is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Lab 04: Create mechanical views and templates

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for floor plan, section, view template; treat values as a teaching brief that must be checked against the project Basis of Design.

5. View > Plan Views: create a mechanical floor plan for each relevant level.

6. View > Section: cut through the AHU and main duct.

7. View > View Templates: apply a mechanical template and inspect Visibility/Graphics.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 05: Schedule equipment ducts and pipes

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for equipment, duct and pipe schedule fields; treat values as a teaching brief that must be checked against the project Basis of Design.

5. View > Schedules > Schedule/Quantities: make equipment, duct and pipe schedules.

6. Add System Name, Type, Size, Flow, Level and Mark fields with units.

7. Sort/group and filter to compare schedules with the model and project brief.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 06: Issue sheets tags and revisions

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for sheet, viewport, tags, revision cloud; treat values as a teaching brief that must be checked against the project Basis of Design.

5. View > Sheet: select the current titleblock and place plan/section viewports.

6. Annotate > Tag by Category: label AHU, terminals and ducts.

7. Annotate > Revision Cloud: identify one controlled change and update sheet revision.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

## Topic 3: Families for mechanical design

Criteria: K5 K6 A5 A6

### Family category and part type

Inspect the Revit object and its category/system assignment for Family category and part type. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if family category and part type is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Hosted versus non-hosted equipment

Inspect the Revit object and its category/system assignment for Hosted versus non-hosted equipment. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if hosted versus non-hosted equipment is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Duct connectors and flow direction

Inspect the Revit object and its category/system assignment for Duct connectors and flow direction. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if duct connectors and flow direction is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Pipe connectors and system classification

Inspect the Revit object and its category/system assignment for Pipe connectors and system classification. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if pipe connectors and system classification is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Connector dimensions and associations

Inspect the Revit object and its category/system assignment for Connector dimensions and associations. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if connector dimensions and associations is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Family type and instance parameters

Inspect the Revit object and its category/system assignment for Family type and instance parameters. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if family type and instance parameters is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Shared parameters and schedule identity

Inspect the Revit object and its category/system assignment for Shared parameters and schedule identity. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if shared parameters and schedule identity is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Visibility controls and detail levels

Inspect the Revit object and its category/system assignment for Visibility controls and detail levels. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if visibility controls and detail levels is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Family formulas and flex validation

Inspect the Revit object and its category/system assignment for Family formulas and flex validation. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if family formulas and flex validation is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Lab 07: Build an equipment family

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for family category, types and host; treat values as a teaching brief that must be checked against the project Basis of Design.

5. File > New > Family: choose a Mechanical Equipment template.

6. Set Family Category and Parameters; create two family types and geometry.

7. Load into Project; verify category, host and schedule row.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 08: Configure HVAC and pipe connectors

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for connector classification, flow direction, dimensions; treat values as a teaching brief that must be checked against the project Basis of Design.

5. In Family Editor, add an HVAC connector on the intended face.

6. Set System Classification, Flow Direction, dimensions and flow configuration.

7. Add piping connectors where required, associate family parameters, reload and test.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 09: Flex test parameters and annotation

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for shared parameter, formula, visibility; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Create a shared identity parameter and assign it to the family category.

6. Use Family Types to define type and instance values plus a valid formula.

7. Flex at least two types; verify annotation, coarse/fine visibility and schedule identity.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

## Topic 4: Analysis for mechanical design

Criteria: K7 A7

### Energy settings and analytical model

Inspect the Revit object and its category/system assignment for Energy settings and analytical model. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if energy settings and analytical model is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Rooms, spaces and analytical boundaries

Inspect the Revit object and its category/system assignment for Rooms, spaces and analytical boundaries. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if rooms, spaces and analytical boundaries is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### System zones and zone equipment

Inspect the Revit object and its category/system assignment for System zones and zone equipment. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if system zones and zone equipment is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Supply air and ventilation loads

Inspect the Revit object and its category/system assignment for Supply air and ventilation loads. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if supply air and ventilation loads is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Heating and cooling load checks

Inspect the Revit object and its category/system assignment for Heating and cooling load checks. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if heating and cooling load checks is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Duct velocity and pressure-drop checks

Inspect the Revit object and its category/system assignment for Duct velocity and pressure-drop checks. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if duct velocity and pressure-drop checks is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Hydronic flow and pipe loss checks

Inspect the Revit object and its category/system assignment for Hydronic flow and pipe loss checks. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if hydronic flow and pipe loss checks is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Thermal properties of constructions

Inspect the Revit object and its category/system assignment for Thermal properties of constructions. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if thermal properties of constructions is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Calculated values and exception review

Inspect the Revit object and its category/system assignment for Calculated values and exception review. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if calculated values and exception review is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Lab 10: Create spaces zones and energy model

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

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 11: Review airflow loads and duct sizing

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for terminal flow, zone loads, sizing constraints; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Set terminal design flows and confirm connected system totals.

6. Review space/zone loads and compare to the 900 L/s teaching brief.

7. Run Duct Sizing and review warnings where constraints override flow targets.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 12: Build hydronic piping and check pressure

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for pump, hydronic circuit, pipe sizing; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Systems > Mechanical Equipment: place pump and hydronic equipment.

6. Create a compatible piping system and route supply/return branches.

7. Review pipe type, fluid temperature, size and pressure-loss report.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

## Topic 5: Collaboration for mechanical design

Criteria: K8 A8 A9

### Link architecture and shared coordinates

Inspect the Revit object and its category/system assignment for Link architecture and shared coordinates. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if link architecture and shared coordinates is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Worksets and central model ownership

Inspect the Revit object and its category/system assignment for Worksets and central model ownership. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if worksets and central model ownership is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Copy/Monitor of levels and grids

Inspect the Revit object and its category/system assignment for Copy/Monitor of levels and grids. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if copy/monitor of levels and grids is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Interference checks and clash records

Inspect the Revit object and its category/system assignment for Interference checks and clash records. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if interference checks and clash records is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Model review and issue assignment

Inspect the Revit object and its category/system assignment for Model review and issue assignment. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if model review and issue assignment is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Design options for route alternatives

Inspect the Revit object and its category/system assignment for Design options for route alternatives. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if design options for route alternatives is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Project standards transfer

Inspect the Revit object and its category/system assignment for Project standards transfer. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if project standards transfer is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### IFC, PDF and schedule export

Inspect the Revit object and its category/system assignment for IFC, PDF and schedule export. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if ifc, pdf and schedule export is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Revision handover and evidence register

Inspect the Revit object and its category/system assignment for Revision handover and evidence register. Record the type or instance parameters, units, element ID and model view in the evidence register. Confirm that the relevant schedule and drawing reproduce the intended project state.

Diagnostic: if revision handover and evidence register is absent from a view or calculation, compare connector classification, host, phase, workset, view template and linked model state before changing geometry.

### Lab 13: Link and coordinate discipline models

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for architecture link, workset, copy-monitor; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Insert > Link Revit: position architecture with the agreed coordinates.

6. Collaborate > Worksets: separate mechanical ownership and check central/local status.

7. Collaborate > Copy/Monitor: review levels and grids, then log monitored changes.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 14: Resolve clashes and evaluate options

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for interference report, design options, issue owner; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Collaborate > Interference Check: test mechanical against linked architecture.

6. Record both element IDs, clash location and issue owner.

7. Create two route options and compare clearance, material quantity and effort.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

### Lab 15: Export and defend the mechanical package

1. Open Architectural-Starter.rvt in a compatible licensed desktop Revit installation. Review levels, grids, room-bounding elements and units; record any missing links. Do not overwrite the starter.

2. Create a new Mechanical project from your installed MEP template. Save it in this lab folder as Mechanical-Working.rvt and set project units to the agreed metric units.

3. Link Architectural-Starter.rvt into Mechanical-Working.rvt with the project coordination positioning strategy. Verify levels and one known grid intersection in plan and 3D.

4. Read assets/design-brief.csv. Record assumptions for project standards, IFC, PDF, final QA; treat values as a teaching brief that must be checked against the project Basis of Design.

5. Manage > Transfer Project Standards: transfer only approved settings.

6. File > Export: produce PDF and IFC or schedule files with revision and units.

7. Reopen model and exported evidence; reconcile issue register and sign off.

8. Inspect connector classification, direction, flow and size where applicable. In System Browser, resolve unassigned components before accepting any calculation.

9. Generate a model schedule or analytical report with units. Compare model counts and calculated totals with the brief; document differences rather than silently adjusting inputs.

10. Create a plan or 3D coordination view with the relevant linked architecture visible. Mark at least one design decision and one failure condition in a text note or issue register.

11. Run an interference or clearance review where geometry crosses disciplines. Record the affected element IDs and owner in the evidence register.

12. Save the working RVT, export one PDF evidence sheet, and complete assets/evidence-register.csv with observed values and pass/fail.

13. Reopen the saved RVT to confirm link resolution and that schedules/views still regenerate. Submit the working RVT, PDF and completed evidence register.

Acceptance: working RVT, schedule/view evidence, PDF sheet and completed evidence register. See the same-numbered lab folder for assets and troubleshooting.

## Assessment and submission

Written Assessment: 8 open-ended questions, 60 minutes. Practical Performance: 3 integrated tasks, 120 minutes. Submit completed papers through https://lms-tms.tertiaryinfotech.com/.

## Technical sources

https://help.autodesk.com/cloudhelp/2026/ENU/Revit-MEPEng/files/GUID-99B57EF9-BBDD-4C34-8AE2-50EA6AE446E7.htm

https://help.autodesk.com/cloudhelp/2026/ENU/Revit-MEPEng/files/GUID-63CD36A5-10F8-4A9D-B858-03DD3989A9AF.htm

https://help.autodesk.com/cloudhelp/2026/ENU/Revit-Analyze/files/GUID-3222ECCA-9140-4EF4-8A68-3856C7AC93C7.htm
