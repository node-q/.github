```text
███╗   ██╗ ██████╗ ██████╗ ███████╗       ██████╗
████╗  ██║██╔═══██╗██╔══██╗██╔════╝      ██╔═══██╗
██╔██╗ ██║██║   ██║██║  ██║█████╗  █████╗██║   ██║
██║╚██╗██║██║   ██║██║  ██║██╔══╝  ╚════╝██║▄▄ ██║
██║ ╚████║╚██████╔╝██████╔╝███████╗      ╚██████╔╝
╚═╝  ╚═══╝ ╚═════╝ ╚═════╝ ╚══════╝       ╚══▀▀═╝

╔════════════════════════════════════════════════╗
║   coding agents, benchmarked  ·  nodeq.tech    ║
╚════════════════════════════════════════════════╝
```

# node-q

We build [Harness Playground](https://nodeq.tech): run coding agents (Claude Code, Codex, Gemini CLI and 40+ more)
on the same tasks, and see which one solves the most.

## Open source

```text
██╗  ██╗██████╗ ███████╗███╗   ██╗ ██████╗██╗  ██╗
██║  ██║██╔══██╗██╔════╝████╗  ██║██╔════╝██║  ██║
███████║██████╔╝█████╗  ██╔██╗ ██║██║     ███████║
██╔══██║██╔══██╗██╔══╝  ██║╚██╗██║██║     ██╔══██║
██║  ██║██████╔╝███████╗██║ ╚████║╚██████╗██║  ██║
╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═══╝ ╚═════╝╚═╝  ╚═╝
```

| Repository | What it is |
|---|---|
| [hbench](https://github.com/node-q/hbench) | The benchmark engine behind Harness Playground. Run coding agents on benchmark tasks from your terminal. |
| [hbench-action](https://github.com/node-q/hbench-action) | A GitHub Action for hbench. Find out which coding agent is best for your code, in CI. |
| [hbench-action-example](https://github.com/node-q/hbench-action-example) | An example repository: three tasks and the workflows that run coding agents on them. |
| [hbench-datasets](https://github.com/node-q/hbench-datasets) | Benchmark datasets for hbench, published as signed OCI artifacts. |
| [hbench-releases](https://github.com/node-q/hbench-releases) | Release binaries of hbench. |

## Quick start

You need Docker, on Linux or macOS.

```bash
curl -fsSL https://nodeq.tech/install.sh | sh
export ANTHROPIC_API_KEY=sk-ant-...
hbench run
```

## Links

- [nodeq.tech](https://nodeq.tech): Harness Playground
- [Docs](https://nodeq.tech/docs)
- [Report a bug or request a feature](https://github.com/node-q/hbench/issues)
