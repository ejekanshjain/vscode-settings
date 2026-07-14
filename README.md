# VS Code Settings

Ekansh Jain's version-controlled Visual Studio Code setup for a TypeScript-heavy full-stack workflow.

## Contents

- settings.json: editor, formatter, language, Copilot, terminal, theme, and workflow preferences
- extensions.txt: exportable list of installed or recommended extensions

## Use the settings

Review settings.json and copy the preferences you want into your VS Code user settings. Avoid replacing your existing file wholesale unless you have backed it up.

Install the exported extensions with a shell that supports command substitution:

    xargs -n 1 code --install-extension < extensions.txt

## Related repository

The curated, distributable extension collection lives in [EJ's VS Code Extension Pack](https://github.com/ejekanshjain/EJ-VSCode-Extension-Pack).

## Notes

These are personal defaults rather than universal recommendations. Paths, fonts, terminal profiles, experimental settings, and extension-specific options may need adjustment for another machine.
