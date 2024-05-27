### Skript utilities 
- By DjDisaster, ThatOneDevil 
- Designs to make skripting easier 
- By providing a set of expressions 
- and effects.

## Usage
#### Small Caps
- Small-Caps: `small [caps] of %string%`
- Example: `small caps of "hello world"`
- Output: `ʜᴇʟʟᴏ ᴡᴏʀʟᴅ`

#### Number formatting
- Number-Formatting: `formatted %number%`
- Example: formatted 5123
- Output: `5.12k`
- Example: formatted -1234
- Output: `-1.23k`

#### Alts of a player
- Alts: `alts of %offlineplayer%`
- Example: `alts of ("DjDisaster" parsed as player)`
- Output: DjDisaster, any alts of DjDisaster 
- Example: `ban alts of ("DjDisaster" parsed as player)`
- Output: bans any alts from "DjDisaster" and them.

#### Midpoint of 2 locations
- Midpoint: `midpoint (of|between) %location% and %location%`
- Example: `midpoint between location(1,1,1) and location(3,3,3)`
- Output: `location(2,2,2)`

#### Formatting time
- Formatting-Time: `formatted %timespan%`
- Example: `send formatted 1000 seconds`
- Output: `16m 40s`
- Example: `send formatted 10000 seconds`
- Ouptut: `2h 46m 40s`
- Example: `send formatted 30 seconds`
- Output: `30s`