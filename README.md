# Burp Suite Hotkeys Cheat Sheet

## Table of Contents  
- [General Shortcuts](#general-shortcuts)  
- [Navigation Shortcuts](#navigation-shortcuts)  
- [Proxy Tab](#proxy-tab)  
- [Repeater Tab](#repeater-tab)  
- [Intruder Tab](#intruder-tab)  

---

## General Shortcuts  

| **Action**                    | **Shortcut**         |
|--------------------------------|----------------------|
| Start/Stop Interception        | `Ctrl` + `I`        |
| Forward Request                | `Ctrl` + `F`        |
| Drop Request                   | `Ctrl` + `D`        |
| Send to Repeater               | `Ctrl` + `R`        |
| Send to Intruder               | `Ctrl` + `T`        |
| Send to Scanner                | `Ctrl` + `U`        |

---

## Navigation Shortcuts  

| **Action**                    | **Shortcut**         |
|--------------------------------|----------------------|
| Toggle Proxy Interception      | `Ctrl` + `Space`    |
| Search (Current Tab)           | `Ctrl` + `F`        |
| Toggle Line Numbers            | `Ctrl` + `L`        |
| Open Target in Sitemap         | `Ctrl` + `Shift` + `J` |
| Navigate Tabs (Next)           | `Ctrl` + `Tab`      |
| Navigate Tabs (Previous)       | `Ctrl` + `Shift` + `Tab` |

---

## Proxy Tab  

| **Action**                    | **Shortcut**         |
|--------------------------------|----------------------|
| Open Intercept Tab             | `Ctrl` + `Shift` + `I` |
| Open HTTP History Tab          | `Ctrl` + `Shift` + `H` |

---

## Repeater Tab  

| **Action**                    | **Shortcut**         |
|--------------------------------|----------------------|
| Open Repeater Tab              | `Ctrl` + `Shift` + `R` |
| Send Request                   | `Ctrl` + `Enter`    |

---

## Intruder Tab  

| **Action**                    | **Shortcut**         |
|--------------------------------|----------------------|
| Open Intruder Tab              | `Ctrl` + `Shift` + `T` |
| Start Attack                   | `Ctrl` + `Shift` + `A` |


## IDEAS

- Switch between top-level tabs `Ctrl Shift (D|T|P|I|R|L|E)`
- Send to a tool, then switch to its tab `Ctrl (R|I) then Ctrl Shift (R|I)` (Here R is for repeater and I for intruder)
- Cycle through 2nd-level tabs `Ctrl Equals and Ctrl Right_Parenthesis`
- Close (and re-open) 2nd-level tabs `Ctrl [Shift] W`
- URL encoding `Ctrl [Shift] U`
- HTML encoding `Ctrl [Shift] H`
- Base64 encoding `Ctrl [Shift] B`
- Close pop-up `Alt F4`
- Colorize (with the last color used) `Ctrl K`
- Add a comment `Ctrl Shift K`
- Copy request as URL `Ctrl Shift C`
- Paste URL as request `Ctrl Shift V`
- Cut | Copy | Paste `Ctrl (X|C|V)`
- Undo | Redo `Ctrl (Z|Y)`
- Select all `Ctrl A`
- Search among 2nd-level tabs `Ctrl Shift S` (Repeater, Intruder and Collaborator)
- Jump to the search field `Ctrl Tab`
- Search for the highlighted text `Ctrl S`
- Go to the (previous|next) match `Ctrl (Left|Right)`
- Go to top [and extend selection] `Ctrl [Shift] Home`
- Go to bottom [and extend selection] `Ctrl [Shift] End`

### Repeater

- Issue request `Ctrl G`
- Paste URL as request `Ctrl Shift V`
- Use the history `Ctrl Shift (Left|Right)`

### Intruder

- Start attack `Ctrl Space`
- Add payload position marker `Ctrl M`
- Clear all markers `Ctrl Shift M`

### Scanner

- Open scan launcher `Ctrl Shift Space`
- Open launcher with selected insertion point `Ctrl Shift Enter`

### Collaborator

- Switch to Collaborator `Ctrl Shift O`
- Insert unique Collaborator payload `Ctrl O`

### Proxy Interception

- Switch interception status `Ctrl T`
- Drop message `Ctrl D`
- Forward message `Ctrl F`
- Forward request + intercept response `Ctrl Shift F`


