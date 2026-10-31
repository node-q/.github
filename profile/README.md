```text
███╗   ██╗ ██████╗ ██████╗ ███████╗       ██████╗
████╗  ██║██╔═══██╗██╔══██╗██╔════╝      ██╔═══██╗
██╔██╗ ██║██║   ██║██║  ██║█████╗  █████╗██║   ██║
██║╚██╗██║██║   ██║██║  ██║██╔══╝  ╚════╝██║▄▄ ██║
██║ ╚████║╚██████╔╝██████╔╝███████╗      ╚██████╔╝
╚═╝  ╚═══╝ ╚═════╝ ╚═════╝ ╚══════╝       ╚══▀▀═╝

╔════════════════════════════════════════════════╗
║  self-evolving AI, benchmarked  ·  nodeq.tech  ║
╚════════════════════════════════════════════════╝
```

# node-q

**Self-Evolving AI, Benchmarked for Trust.**

As AI agents learn to improve themselves, progress needs proof. We build [Harness Playground](https://nodeq.tech), where every result is pinned to three
things: the harness and its version, the model, and the tests.

- **Prove it got better.** Run each version of your harness on the same model and tasks,
  in the open, so anyone can check whether it improved.
- **Follow your harness over time.** Upload your benchmark jobs. Each version gets its own
  row on a board, with a 95% interval, next to other harnesses.
  [See the benchmarks](https://nodeq.tech/benchmarks).
- **Evaluate harnesses for your domain.** Not everything is coding. If you don't know how
  to build a harness for your field, or don't want to hand your work to a third party, we
  can set up a private site on your own tasks, with its own database and domain, and none
  of it public. [Talk to us](https://nodeq.tech/contact).

hbench, our open source engine, runs Claude Code, Codex, Gemini CLI and 40+ more.

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

Then upload the job folder to Your bench on [nodeq.tech](https://nodeq.tech). It stays
private until you publish it.

## Links

- [nodeq.tech](https://nodeq.tech): Harness Playground
- [Benchmarks](https://nodeq.tech/benchmarks)
- [Methodology](https://nodeq.tech/methodology)
- [Docs](https://nodeq.tech/docs)
- [Enterprise and contact](https://nodeq.tech/contact)
- [Report a bug or request a feature](https://github.com/node-q/hbench/issues)
