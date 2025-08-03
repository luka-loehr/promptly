<!--
Modified: Changed references from Gemini CLI to Promptly
Original work Copyright Google LLC
Licensed under Apache License 2.0
-->

# Ignoring Files

This document provides an overview of the Promptly Ignore (`.promptlyignore`) feature of the Promptly.

The Promptly includes the ability to automatically ignore files, similar to `.gitignore` (used by Git) and `.aiexclude` (used by Promptly Code Assist). Adding paths to your `.promptlyignore` file will exclude them from tools that support this feature, although they will still be visible to other services (such as Git).

## How it works

When you add a path to your `.promptlyignore` file, tools that respect this file will exclude matching files and directories from their operations. For example, when you use the [`read_many_files`](./tools/multi-file.md) command, any paths in your `.promptlyignore` file will be automatically excluded.

For the most part, `.promptlyignore` follows the conventions of `.gitignore` files:

- Blank lines and lines starting with `#` are ignored.
- Standard glob patterns are supported (such as `*`, `?`, and `[]`).
- Putting a `/` at the end will only match directories.
- Putting a `/` at the beginning anchors the path relative to the `.promptlyignore` file.
- `!` negates a pattern.

You can update your `.promptlyignore` file at any time. To apply the changes, you must restart your Promptly session.

## How to use `.promptlyignore`

To enable `.promptlyignore`:

1. Create a file named `.promptlyignore` in the root of your project directory.

To add a file or directory to `.promptlyignore`:

1. Open your `.promptlyignore` file.
2. Add the path or file you want to ignore, for example: `/archive/` or `apikeys.txt`.

### `.promptlyignore` examples

You can use `.promptlyignore` to ignore directories and files:

```
# Exclude your /packages/ directory and all subdirectories
/packages/

# Exclude your apikeys.txt file
apikeys.txt
```

You can use wildcards in your `.promptlyignore` file with `*`:

```
# Exclude all .md files
*.md
```

Finally, you can exclude files and directories from exclusion with `!`:

```
# Exclude all .md files except README.md
*.md
!README.md
```

To remove paths from your `.promptlyignore` file, delete the relevant lines.
