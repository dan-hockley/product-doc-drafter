Copy your compiled context file into this repo's context.md.

If you have a separate context repo with a compile script, run the compile first, then copy the output here. Example:

```
python3 /path/to/your-context-repo/scripts/compile-context.py
cp /path/to/your-context-repo/context-compiled.md ./context.md
```

Then report the file size of the updated context.md using `wc -c`.

Note: This updates the compiled context file used when `.context-mode` is set to `compiled`. When in `internal` mode, the source directory is read directly instead.
