# pandas_skill

个人skill（版本管理）

This repository is designed to store and manage custom skills for Trae IDE.

## Structure

- `.trae/skills/` - The directory where all custom skills are stored.
  - `<skill-name>/` - Each skill should have its own directory.
    - `SKILL.md` - The main skill file containing instructions and triggers.

## Creating a new skill

1. Create a new directory under `.trae/skills/`.
2. Add a `SKILL.md` file inside the new directory.
3. Define the frontmatter with `name` and `description` (the description should explain *what* the skill does and *when* to invoke it).
4. Add the actual instructions in markdown below the frontmatter.

## Version Control

This repository is linked to your GitHub remote at `https://github.com/Panda9995/pandas_skill`. 
Use standard Git commands to track your changes, commit, and push.
