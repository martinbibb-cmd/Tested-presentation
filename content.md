# Welcome to the Grove 🌳
![](img/poc_welcome.png)
This is a self-building UI demo. Learn how to navigate, select, attach photos, log safety, and export your journey.

- Start by choosing a **path** below
- “**Double-click**” (or **Cmd/Ctrl-click**) tiles to open branches without selecting
- Click the floating **🧯 Safety** button anytime
- See photo – take a screenshot or snap a pic to try it

## Choose a Practice Path
::menu[single]
![](img/poc_paths.png)
Pick one to walk through a short tutorial.

### 1) Quick Tour (2 minutes)
![](img/poc_quicktour.png)
A fast way to learn the basics.

### 2) Deeper Dive (5–7 minutes)
![](img/poc_deeper.png)
Covers sub-menus, multi-select, and repeatable items.

### 3) Power User Track
![](img/poc_power.png)
Keyboard hints, branching tricks, and JSON export.

---

# Quick Tour (Basics) ✅
![](img/poc_quicktour.png)
We’ll cover: selecting tiles, opening branches, and logging a photo.

## Step 1 — Tap vs Open
::menu[single]
![](img/poc_tap_open.png)
- **Tap** a tile to select it (radio style here)
- **Double-click** (or Cmd/Ctrl-click) to open its branch without selecting

### Try It
![](img/poc_tryit.png)
Pick one, then double-click to open its child.

## Step 2 — “See photo”
::menu[multi]
![](img/poc_photo.png)
Select both items and try adding a photo.

- See photo – try attaching one now
- Add a note • optional

## Step 3 — Safety Banner
![](img/poc_safety.png)
Selecting certain phrases **auto-logs safety** and shows tags in the floating panel.

- Electrical socket near here – electrical
- Ladder needed for access – WAH
- Asbestos warning label seen – asbestos

---

# Deeper Dive 🧭
![](img/poc_deeper.png)
Now we’ll explore **menu types** and sub-menus.

## Menu Types (Parent controls Children)
::menu[single]
![](img/poc_menu_types.png)
Pick one to learn more.

### (A) Single Choice
::menu[single]
![](img/poc_single.png)
Choose exactly **one** child. Selecting another unselects the previous.

- Option A
- Option B
- Option C

### (B) Multiple Choice
::menu[multi]
![](img/poc_multi.png)
Choose **many** children. Click again to toggle off.

- Include screenshots – see photo
- Add checklist
- Mark electrical risk – electrical
- Flag height risk – WAH

### (C) Repeatable Items
::menu[repeat]
![](img/poc_repeat.png)
Tap the same tile again to **increase quantity** (×2, ×3…).

- Extra item
- Spare part
- Additional note page

## Nested Sub-Menus
::menu[single]
![](img/poc_nested.png)
Pick one and **double-click** to drill deeper.

### Level 2
::menu[multi]
![](img/poc_level2.png)
- Attach a diagram – see photo
- Record an issue – electrical
- Access via ladder – WAH

#### Level 3 (Optional)
::menu[single]
![](img/poc_level3.png)
- Confirm
- Skip

---

# Power User Track ⚡
![](img/poc_power.png)
Faster navigation and output controls.

## Fast Navigation
::menu[multi]
![](img/poc_fastnav.png)
- **Cmd/Ctrl-click** to open without selecting
- **Back** to go up one level
- **Root** to jump to the start

## Export & Hand-off
::menu[multi]
![](img/poc_export.png)
- Use **💾 Export JSON** (bottom toolbar)
- JSON contains selections, counts, safety tags, and logs
- Share JSON with colleagues for review

## Tips & Conventions
::menu[multi]
![](img/poc_tips.png)
- Use short **headings** as tiles
- Put `::menu[...]` in the parent section to control children
- Bullet points render as **chips** (good for hints & triggers)
- Keywords trigger safety: **electrical**, **WAH/ladder/roof**, **asbestos**
- “See photo” prompts image attachment

---

# Finish 🏁
![](img/poc_finish.png)
You’ve completed the POC journey. Try switching paths or exporting your JSON.

## What’s Next?
::menu[multi]
![](img/poc_next.png)
- Replace placeholder images in `/img/` with your own
- Start a real flow (e.g., survey → proposal → extras)
- Wire chips to validations or price data
- Share exported JSON with your team
