# General Assistant

The second built-in DesireCore Agent, named **通用助手** in the client. It handles questions, research, writing, analysis, coding, file work and other general tasks with the capabilities available in the current environment.

## Defaults

- Stable client directory: `general-assistant`.
- A transparent portrait is bundled at `assets/avatar.webp`; `avatar.image.path` references it, with the character and color retained as the fallback.
- Manual multi-session mode is enabled (`session_mode.manual: true`); users can change it in the existing session settings.
- Smart routing uses the flagship tier without pinning a Provider or model.
- This Agent has its own identity and can collaborate or join teams. DesireCore retains the central system role.

## Content and updates

`agent.json` declares this repository and its `main` branch as the upstream. `persona.md` and `principles.md` use L0/L1/L2 headings; `instructions.md` is loaded as plain Markdown.

The client ships an offline Git seed and merges upstream updates through the existing Agent update flow, preserving local evolution. The market lists this as a system-managed Agent with repository updates; it does not install a second copy. Runtime permissions, tools and approvals remain owned by the platform.

See [中文说明](README.zh-CN.md).
