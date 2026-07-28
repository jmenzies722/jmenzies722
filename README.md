<div align="center">

<img src="./assets/header-v3.svg" alt="Josh Menzies — Platform Engineer building the infrastructure AI agents run on; agentic frameworks, developer productivity, production-grade AI" width="100%" />

</div>

<br>

Platform engineer in New York. I build the layer AI agents actually run on — the tooling,
guardrails, and infrastructure that make them safe to operate in production rather than
impressive in a demo.

Everything below is released, licensed, and something you can clone, run, or click.

<br>

---

### <img src="./assets/icons/react.svg" width="20" align="top" /> &nbsp;CubeCoach

[![Repo](https://img.shields.io/badge/repo-cubecoach-1a1a1a?style=flat-square&logo=github&logoColor=white)](https://github.com/jmenzies722/cubecoach)
[![Live demo](https://img.shields.io/badge/live_demo-cubecoach--three.vercel.app-2ea043?style=flat-square)](https://cubecoach-three.vercel.app)
[![License](https://img.shields.io/github/license/jmenzies722/cubecoach?style=flat-square&color=1a1a1a)](https://github.com/jmenzies722/cubecoach/blob/master/LICENSE)

Solve any Rubik's Cube and actually learn how. Interactive 3D cube, the full beginner
layer-by-layer method, step-by-step coaching at every stage. The solver is verified against
exhaustive search, so the method it teaches is provably complete — it will never walk you into
a dead end.

<sub>`React` &nbsp;·&nbsp; `Three.js` &nbsp;·&nbsp; `WebGL`</sub>

---

### <img src="./assets/icons/python.svg" width="20" align="top" /> &nbsp;mcp-sync

[![Repo](https://img.shields.io/badge/repo-mcp--sync-1a1a1a?style=flat-square&logo=github&logoColor=white)](https://github.com/jmenzies722/mcp-sync)
[![Release](https://img.shields.io/github/v/release/jmenzies722/mcp-sync?style=flat-square&color=2ea043)](https://github.com/jmenzies722/mcp-sync/releases)
[![License](https://img.shields.io/github/license/jmenzies722/mcp-sync?style=flat-square&color=1a1a1a)](https://github.com/jmenzies722/mcp-sync/blob/main/LICENSE)

One MCP server set across Claude Code, Cursor, Warp, and Claude Desktop — defined once,
generated everywhere. Four tools, four config files, none aware of the others, so they drift.
The drift is silent: a broken server reports only `Failed to connect`, never that the path went
stale or that the environment variable you referenced was never exported. `check` exits
non-zero, so it works as a CI gate.

Zero third-party dependencies, single file, 21 tests green on Linux, macOS, and Windows.

<sub>`Python` &nbsp;·&nbsp; `MCP`</sub>

---

### <img src="./assets/icons/modelcontextprotocol.svg" width="20" align="top" /> &nbsp;AWS Architect MCP

[![Repo](https://img.shields.io/badge/repo-aws--architect--mcp-1a1a1a?style=flat-square&logo=github&logoColor=white)](https://github.com/jmenzies722/aws-architect-mcp)
[![Release](https://img.shields.io/github/v/release/jmenzies722/aws-architect-mcp?style=flat-square&color=2ea043)](https://github.com/jmenzies722/aws-architect-mcp/releases)
[![License](https://img.shields.io/github/license/jmenzies722/aws-architect-mcp?style=flat-square&color=1a1a1a)](https://github.com/jmenzies722/aws-architect-mcp/blob/main/LICENSE)

Turns an AI agent into an AWS solutions architect. Ask an agent to design infrastructure and it
will invent an architecture from scratch, confidently. This gives it a library of reference
patterns to select from instead — then emits production-grade Terraform, a least-privilege IAM
policy, and a cost estimate before anything is applied.

<sub>`TypeScript` &nbsp;·&nbsp; `MCP` &nbsp;·&nbsp; `Terraform`</sub>

---

### <img src="./assets/icons/anthropic.svg" width="20" align="top" /> &nbsp;claude-max

[![Repo](https://img.shields.io/badge/repo-claude--max-1a1a1a?style=flat-square&logo=github&logoColor=white)](https://github.com/jmenzies722/claude-max)
[![Release](https://img.shields.io/github/v/release/jmenzies722/claude-max?style=flat-square&color=2ea043)](https://github.com/jmenzies722/claude-max/releases)
[![License](https://img.shields.io/github/license/jmenzies722/claude-max?style=flat-square&color=1a1a1a)](https://github.com/jmenzies722/claude-max/blob/master/LICENSE)

Scores an entire Claude Code setup 0–100 across nine dimensions — skills, subagents, hooks,
settings, MCP, portability, memory, output style, cross-tool unification — then applies the
fixes it finds. It scores what is on disk rather than what you assume is there, and refuses to
credit configuration that does not actually do anything.

<sub>`Shell` &nbsp;·&nbsp; `Claude Code`</sub>

---

### <img src="./assets/icons/nextjs.svg" width="20" align="top" /> &nbsp;Shua Labs

[![Repo](https://img.shields.io/badge/repo-shua--labs-1a1a1a?style=flat-square&logo=github&logoColor=white)](https://github.com/jmenzies722/shua-labs)
[![Site](https://img.shields.io/badge/site-shua--labs.vercel.app-2ea043?style=flat-square)](https://shua-labs.vercel.app)
[![License](https://img.shields.io/github/license/jmenzies722/shua-labs?style=flat-square&color=1a1a1a)](https://github.com/jmenzies722/shua-labs/blob/main/LICENSE)

Home for the tooling above. Tools for running AI agents in production — safe, observable, cheap
to operate.

<sub>`Next.js` &nbsp;·&nbsp; `TypeScript`</sub>

<br>

---

## Currently building

**A local Kubernetes platform** — k3d, Helm, and ArgoCD, split into how the cluster is built and
what runs on it, so the GitOps boundary is a real one rather than a convention.

**AWS DevOps Professional (DOP-C02)** — studied through a live multi-account lab instead of
practice exams.

**Agent infrastructure** — MCP servers, agent registries, and drift detection for multi-agent
setups that have outgrown a single config file.

<br>

---

## Stack

<div align="center">

<img src="./assets/icons/python.svg" height="42" alt="Python" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/typescript.svg" height="42" alt="TypeScript" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/go.svg" height="42" alt="Go" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/react.svg" height="42" alt="React" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/nextjs.svg" height="42" alt="Next.js" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/aws.svg" height="42" alt="AWS" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/terraform.svg" height="42" alt="Terraform" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/kubernetes.svg" height="42" alt="Kubernetes" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/docker.svg" height="42" alt="Docker" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/githubactions.svg" height="42" alt="GitHub Actions" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/anthropic.svg" height="42" alt="Claude API" />&nbsp;&nbsp;&nbsp;
<img src="./assets/icons/modelcontextprotocol.svg" height="42" alt="Model Context Protocol" />

</div>

<br>

<div align="center">

Build in the open &nbsp;·&nbsp; Own the layer

</div>
