# Weekly staff schedule overview for EMS
This repository contains UI screens and a small flow for resolving overlapping shifts in an EMS scheduling system. All visual designs were created in Figma and exported as image assets.
## Overview
A compact MVP screen set that demonstrates how non-technical staff can view a weekly schedule, detect shift conflicts, and resolve them either automatically or manually.

## Screens
1. **Main / Weekly Schedule (MVP)**
   - Header with EMS name and week navigation (previous / current / next).
   - 7-day grid with rows for shift periods (Morning / Day / Evening / Night).
   - Shift cards show employee name, role and status badges (Conflict / Overtime / Missing skill / Confirmed).
   - Action panel: Regenerate schedule, Export PDF, Print, Filters.
   - Purpose: present dense schedule data clearly and allow quick access to problem items.

2. **Conflict Card (tap / click)**
   - A shift card marked with a red badge: `Conflict: Overlapping shift`.
   - Tapping opens the conflict overview panel.

3. **Conflict Overview (side panel / sheet)**
   - Title: “Problem: Overlapping shifts”
   - Shows: employee name, date, Shift A time, Shift B time.
   - Clear note: how long the shifts overlap (e.g. “These shifts overlap by 2 hours”).
   - Primary actions:
     - Resolve automatically (system-adjust suggestion)
     - Edit shift manually (opens edit modal)

4. **Manual Edit**
   - Controls:
     - Employee selector (dropdown)
     - Time pickers for start / end
   - Actions: Save changes (primary), Cancel

5. **Confirmation (success modal)**
   - Simple confirmation with a check mark, text “Conflict resolved — Shift updated”, and a Close button.
  
  ## UI Kit (small)

- Colors :
#144F93
#83A4D4
#FF782F
#1C5AA3
#6D7881
#F2F7FC
#FFFCFC
#FFFFFF
- Fonts :
Baloo Da 2
Baloo Thambi 2
