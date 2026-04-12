Toggle the context mode between `compiled` and `internal`.

1. Read `.context-mode` in the repo root.
2. If it currently says `compiled`, change it to `internal`. If it says `internal`, change it to `compiled`.
3. Write the updated value back to `.context-mode`.
4. Report the new mode to the user:
   - **compiled**: "Context mode set to **compiled**. Will read `context.md` in the repo root."
   - **internal**: "Context mode set to **internal**. Will read all files in your context source directory. Make sure the path in this command file points to the right location."
