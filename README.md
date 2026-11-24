<h1 align="center">
   <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=600&height=70&duration=4000&lines=Hi+there!+I'm+Bernardo+Kunz+👋;Senior+Software+Engineer;Backend+%26+AI+Engineering" />
</h1>

<div align="center">

[![Linkedin](https://img.shields.io/badge/-LinkedIn-00AEFF?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/bernardokunz)
[![Website](https://img.shields.io/badge/-Portfolio-00AEFF?style=for-the-badge&logo=Google-Chrome&logoColor=white)](https://github.com/javabetatester?tab=repositories)
[![Email](https://img.shields.io/badge/-Email-00AEFF?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:bernardokunz@gmail.com)

</div>

Senior Software Engineer from Brazil, building [**Versatile**](https://versatile.sh).
I focus on **Developer Experience**, **Performance Engineering**, **Compilers & Static Analysis** and **AI Engineering**, with statistical proof behind every speed claim.

### ⚡ vxc

[**vxc**](https://vxc.versatile.sh) (*versatile experience compiler*) is a suite of high-performance Go tools in the spirit of oxc, each tool its own binary. [Repository](https://github.com/versatile-sh/vxc) *(open source soon)*

| Tool | What it does |
| --- | --- |
| **vxlint** | Go linter with the same findings as golangci-lint on the same rules, **14–28x faster warm** and **up to ~1,960x faster cold** (95% CIs). Syntax rules run per file as soon as it is parsed; typed `go/analysis` passes (go vet, staticcheck SA/S/ST/QF) run per package against a persistent cache. |
| **vxfmt** | gofmt, gofumpt, goimports and gci in one pass, byte-identical to each. |
| **vxtest** | Runs `go test` only on the packages your change can affect, with the reason for each. |
| **vxbench** | Benchmarks, probes, mutation recall and conformance against the tools vxc replaces. |

### 🔨 Versatile

| Project | What it does |
| --- | --- |
| **bench-engine** | Language-agnostic benchmarking with statistics built in: confidence intervals, Mann–Whitney with Holm correction, change-point detection and bisect. *(open source soon)* |
| [**go-lint**](https://github.com/versatile-sh/go-lint) | One lint kit for Go repositories: generated golangci-lint config, drift check and custom `go/analysis` analyzers. |
| [**semgrep-rules**](https://github.com/versatile-sh/semgrep-rules) | Shared Semgrep rules for Versatile repositories, pinned by tag. |
| [**connector-engine**](https://github.com/versatile-sh/connector-engine) | Connector store and MCP gateway for agents: per-agent, per-function grants, approval on use, pinned definitions. |
| [**agents-vault**](https://github.com/versatile-sh/agents-vault) | Account ledger for coding-agent harnesses: isolated Claude Code, Codex and Grok accounts, API keys and live limits. |
| [**live-platform**](https://github.com/versatile-sh/live-platform) | Screen sharing rooms behind [live.versatile.sh](https://live.versatile.sh): Go server, React client. |
| [**homebrew-tap**](https://github.com/versatile-sh/homebrew-tap) | Homebrew formulae for Versatile tools. |

Also building [**adaptable.chat**](https://adaptable.chat) and the agent engines behind it.

### 🧠 AI engineering

At **MeuControle.AI** I build a conversational AI orchestrator in Go on Claude: 30+ domain adapters as tools, multi-provider routing with fallback and per-attempt metering, output-edge guardrails, and an evals harness (paired baselines, McNemar, Wilson intervals, LLM-as-judge) running on every push.

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/bernardokunz) · [bkunz.dev](https://bkunz.dev) · [Email](mailto:bernardokunz@gmail.com)
