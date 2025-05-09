# EmpyrionScripts

A personal collection of Empyrion scripting examples and my notes as I learn to use them.

---

## 📂 Original Repository

The original author’s repo is available here:  
[GitHub-TC/EmpyrionScripting](https://github.com/GitHub-TC/EmpyrionScripting)

---

## 📝 What I’ve Learned So Far

### Handlebars‐Style Syntax
- **Script blocks** are wrapped in double curly braces:  
  `{{ scriptCode }}`
- **Comments** start with `!--` immediately after the opening braces:  
  `{{!-- this is a comment --}}`

### Variables
- Use the `~set` keyword to declare or assign a variable:  
  `~set 'varName' 'value'`
- To assign a list (array), separate items with commas:  
  `~set 'myList' '1,2,3'`

### Naming Conventions
To avoid conflicts with in-game items, use this pattern when renaming:
```
<ItemType>-<YourInitials>-<ShipOrBaseName>-<Number>
```
Example:
```
Container-GM-MyShip-1
```

---

## 🔌 Sanity Checks
- **Power**: Ensure your ship or base has power, or your LCD panels will display nothing.
- **Grouping**: Move your LCD panels into a named group so you can easily find and rename them.

---

## ⚠️ Caution
Renaming objects in-game may break existing scripts if they reference that item in multiple places.

---

## 💡 Notes & Tips
- **Script Delay**  
  It may take a few seconds for a script to start updating its LCD panels.
- **Quick-Select Device**  
  While looking at an item, press **P** to open the Devices tab and jump directly to that object.
- **Lock Down Scripts**  
  Assign a code to your script-hosting LCD and set it to **Private** to prevent accidental edits.
- **Performance Switch**  
  Add an on/off switch that controls the LCD panel running your script.  
  Flip it on only when you need the script to run, reducing server load.

---
