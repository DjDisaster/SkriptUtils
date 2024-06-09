# Skript Utilities

**Authors:** DjDisaster, ThatOneDevil  
**Description:** A collection of Skript utilities designed to make scripting easier by providing a set of expressions and effects.

---

## Usage
You are welcome to use and modify this code as long as you do not change any of the provided links, such as the update fetching link. You may remove the updating features, but altering the links is not permitted.

## Requirements
To use this you will need Skript and Skript-Reflect
Addons may require different addons which will be shown in the comments of the file.

---

## Syntax

### Small Caps
- **Expression:** `small [caps] of %string%`
- **Example:** `small caps of "hello world"`
- **Output:** `ʜᴇʟʟᴏ ᴡᴏʀʟᴅ`

### Number Formatting
- **Expression:** `formatted %number%`
- **Examples:**
  - `formatted 5123`
    - **Output:** `5.12k`
  - `formatted -1234`
    - **Output:** `-1.23k`

### Alts of a Player
- **Expression:** `alts of %offlineplayer%`
- **Examples:**
  - `alts of ("DjDisaster" parsed as player)`
    - **Output:** `DjDisaster, any alts of DjDisaster`
  - `ban alts of ("DjDisaster" parsed as player)`
    - **Output:** `bans any alts from "DjDisaster" and them.`

### Midpoint of Two Locations
- **Expression:** `midpoint (of|between) %location% and %location%`
- **Example:** `midpoint between location(1,1,1) and location(3,3,3)`
  - **Output:** `location(2,2,2)`

### Formatting Time
- **Expression:** `formatted %timespan%`
- **Examples:**
  - `send formatted 1000 seconds`
    - **Output:** `16m 40s`
  - `send formatted 10000 seconds`
    - **Output:** `2h 46m 40s`
  - `send formatted 30 seconds`
    - **Output:** `30s`

---
