# Claude Praxis

The practice of effective AI-assisted development.

## What Is This?

**Praxis** (Greek: πρᾶξις) means "practice, as distinguished from theory" — the practical application of principles.

This repository contains a **comprehensive methodology** for Claude Code that transforms how AI assists with software development. It's not just configuration — it's a complete system of principles, workflows, and practices.

When you bootstrap with Claude Praxis, you get:

- **Semantic Code Understanding** - Serena MCP for intelligent code navigation
- **Up-to-Date Documentation** - Context7 MCP for current library docs
- **Structured Reasoning** - Sequential Thinking MCP for complex problems
- **Hypothesis-Driven Development** - Test-first thinking as a core methodology
- **Progressive Knowledge System** - CLAUDE.md → guides → ADRs → memories
- **Project-Aware Instructions** - Customized to your actual tech stack and conventions

## Two Bootstrap Modes

Claude Praxis has two distinct modes that can run separately or together:

### 1. Environment Setup (once per machine)

Installs global tools that enhance Claude Code for **all** your projects:

- **Serena MCP** - Semantic code understanding and navigation
- **Context7 MCP** - Up-to-date library documentation in prompts
- **Sequential Thinking MCP** - Structured reasoning for complex problems
- **Specialized Agents** - Domain experts (architecture, TDD, debugging, etc.)

### 2. Project Bootstrap (once per project)

Sets up praxis methodology files for a **specific** project:

- Customized `CLAUDE.md` with your conventions
- Methodology guides (TDD, research, problem-solving)
- Architecture Decision Records structure
- Serena project configuration

## How To Use

1. Open your project in Claude Code
2. Tell Claude:

```
Look at https://github.com/rosudrag/claude-praxis
and use it to bootstrap my project
```

3. Claude will automatically detect what's needed:
   - **First time?** → Runs both modes (environment + project)
   - **Environment done?** → Runs project bootstrap only
   - **Everything done?** → Offers to verify or update

You can also request specific modes:
- "Run environment setup only"
- "Bootstrap this project only"
- "Verify my praxis installation"

## What Gets Created

### Global (Environment Setup)

```
~/.claude/
└── settings.local.json    # MCP server configuration
```

### Per-Project (Project Bootstrap)

```
your-project/
├── CLAUDE.md              # AI instructions customized for your project
├── claude-docs/           # Methodology guides
│   ├── tdd-enforcement.md
│   ├── code-quality.md
│   ├── security.md
│   ├── research-workflow.md
│   ├── iterative-problem-solving.md
│   └── multi-approach-validation.md
├── docs/
│   └── adrs/              # Architecture Decision Records
│       ├── README.md
│       └── 000-template.md
├── .serena/               # Semantic code understanding
│   ├── project.yml
│   └── memories/
└── .claude-bootstrap/     # Bootstrap state (for resumption)
    └── manifest.json
```

## Philosophy

1. **Methodology over configuration** - A complete way of working, not just settings
2. **Hypothesis-driven** - Tests are hypotheses; state expectations, then prove them
3. **Research before assuming** - Investigate systematically, don't guess
4. **Progressive disclosure** - Layer information: quick reference → detailed guides → historical context
5. **Project-aware** - Adapt to the actual codebase, not generic best practices
6. **Graceful degradation** - Works without optional tools, better with them

## Customization

After bootstrapping:

- Edit `CLAUDE.md` to add project-specific instructions
- Add custom guides to `claude-docs/`
- Create ADRs for architectural decisions
- Add Serena memories for persistent knowledge

## Requirements

- Claude Code CLI or VS Code extension
- Node.js 18+ (for MCP server installation)
- Git

## Contributing

See [CLAUDE.md](CLAUDE.md) for development instructions.

## License

MIT
