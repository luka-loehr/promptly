<!--
Modified: Changed references from Gemini CLI to Promptly
Original work Copyright Google LLC
Licensed under Apache License 2.0
-->

# Promptly

Within Promptly, `packages/cli` is the frontend for users to send and receive prompts with the Promptly AI model and its associated tools. For a general overview of Promptly, see the [main documentation page](../index.md).

## Navigating this section

- **[Authentication](./authentication.md):** A guide to setting up authentication with Google's AI services.
- **[Commands](./commands.md):** A reference for Promptly commands (e.g., `/help`, `/tools`, `/theme`).
- **[Configuration](./configuration.md):** A guide to tailoring Promptly behavior using configuration files.
- **[Token Caching](./token-caching.md):** Optimize API costs through token caching.
- **[Themes](./themes.md)**: A guide to customizing the CLI's appearance with different themes.
- **[Tutorials](tutorials.md)**: A tutorial showing how to use Promptly to automate a development task.

## Non-interactive mode

Promptly can be run in a non-interactive mode, which is useful for scripting and automation. In this mode, you pipe input to the CLI, it executes the command, and then it exits.

The following example pipes a command to Promptly from your terminal:

```bash
echo "What is fine tuning?" | promptly
```

Promptly executes the command and prints the output to your terminal. Note that you can achieve the same behavior by using the `--prompt` or `-p` flag. For example:

```bash
promptly -p "What is fine tuning?"
```
