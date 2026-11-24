---
name: random-number
description: Generate a random number within a specified range. Use when asked to generate a random number or simulate a random event.
---

To generate a random number, use the following command that generates a random number from 1
to the given number, max at 1000:

```bash
echo $((RANDOM % <number> + 1))
```

```powershell
Get-Random -Minimum 1 -Maximum (<number> + 1)
```

Replace `<number>` with the maximum number you want to generate (e.g., 1000).
