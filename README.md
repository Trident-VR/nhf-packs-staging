# No Hard Feelings: community prompt packs

Prompt packs made by players of the VRChat world "No Hard Feelings".
The world reads these files; nothing here is code.

- `packs/NNNN.txt` is one pack. A host enters the four-digit code in Host options to load it.
- Codes run from 1000 to 9999. New packs are numbered upward from 1000. 9999 is the example pack.
- `index.txt` is the list the game shows on its Community Prompts page.
- Every pack is public. There are no private packs: anyone can read these files.

## Pack file format

```
name=Pack name
author=Display name
mature=0
---
One prompt per line.
```

## index.txt format

One listed pack per line: `code|name|author|prompt count|mature (0 or 1)|featured (0 or 1)`
