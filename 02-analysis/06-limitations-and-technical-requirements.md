# Limitations and Technical Requirements

## 1) Stating limitations properly

A limitation is a deliberate scope boundary, not an excuse.

Good limitation statements explain:

- what is out of scope
- why this is sensible for this project
- impact on users or future versions

### Example (strong)

> This version will run on school Windows PCs only. Cross-platform support is out of scope to keep testing controlled in one environment and to meet available development time.

### Example (weak)

> I am not doing mobile support because it is too hard.

## 2) Scope control guidance

Good NEA scope usually means:

- one domain/problem area
- clear user roles
- meaningful logic and data
- realistic feature set

If a feature is removed, record it as a conscious decision with reason.

## 3) Hardware and software requirements

Include these when they affect development, deployment, or user access.

Keep this practical and proportionate.

### Template

| Category | Requirement | Why it matters |
|---|---|---|
| Operating system | Windows 11 (school devices) | Matches target deployment environment |
| Runtime | Python 3.12 | Required to execute the project |
| Database | SQLite | Needed for local persistent storage |
| Hardware | Standard school desktop keyboard/mouse | Required for normal use |

Only list relevant items. Avoid generic full-PC specs unless your project depends on them.
