# Workspai (by RapidKit)

**Workspace Intelligence for Software Systems** — the VS Code experience on top of the open-source RapidKit platform.

> One workspace. One truth. Humans and AI aligned.

<table>
	<tr>
		<td width="50%" valign="top">
			<h3>🌐 Main Website</h3>
			<p>Product pages, docs, supported stacks, and VS Code install.</p>
			<p><a href="https://www.workspai.com/">workspai.com</a></p>
		</td>
		<td width="50%" valign="top">
			<h3>🧩 VS Code Extension</h3>
			<p>Workspai — Dashboard, Repair flow, Incident Studio, and Advisor backed by RapidKit CLI contracts.</p>
			<p><a href="https://marketplace.visualstudio.com/items?itemName=rapidkit.rapidkit-vscode">VS Code Marketplace</a></p>
		</td>
	</tr>
	<tr>
		<td width="50%" valign="top">
			<h3>📦 RapidKit CLI (npm)</h3>
			<p>Canonical command surface: create planner, workspace model, agent-sync, impact, verify, and release gates.</p>
			<p>
				<a href="https://www.npmjs.com/package/rapidkit">npm — rapidkit</a><br />
				<a href="https://www.getrapidkit.com/docs">Documentation</a>
			</p>
		</td>
		<td width="50%" valign="top">
			<h3>🐙 GitHub — rapidkitlabs</h3>
			<p>Open-source organization for CLI, VS Code extension, Core engine, and examples.</p>
			<p><a href="https://github.com/rapidkitlabs">github.com/rapidkitlabs</a></p>
		</td>
	</tr>
	<tr>
		<td width="50%" valign="top">
			<h3>📣 Social</h3>
			<p>Announcements, releases, and product direction.</p>
			<p>
				<a href="https://x.com/workspai_com">X (Twitter)</a><br />
				<a href="https://www.linkedin.com/company/workspai">LinkedIn</a>
			</p>
		</td>
		<td width="50%" valign="top">
			<h3>🔗 Related hubs</h3>
			<p>Marketing site and portfolio.</p>
			<p>
				<a href="https://www.getrapidkit.com">getrapidkit.com</a><br />
				<a href="https://baziar.dev">baziar.dev</a>
			</p>
		</td>
	</tr>
</table>

## Platform

RapidKit and Workspai form a single **workspace intelligence** platform:

| Layer | Role |
| ----- | ---- |
| **RapidKit CLI** (npm) | Commands, create planner, governance, adoption, CI evidence, `workspace agent-sync` |
| **Workspai** (VS Code) | Dashboard, sidebar, Incident Studio, AI workflows, developer-facing operations |
| **RapidKit Core** (PyPI) | Python engine, modules, doctor inside adopted projects |

**Create planner** chooses the safest path per stack: `native-create`, `external-create-adopt`, or `adopt-only` — you do not have to change frameworks to benefit from workspace intelligence.

## Features

<table>
	<tr>
		<td width="33%" valign="top">
			<h4>🧭 Workspace Intelligence</h4>
			<p>Model, context, impact, verify, and sync — one evidence-backed truth for humans, CI, IDEs, and AI agents.</p>
		</td>
		<td width="33%" valign="top">
			<h4>🚀 Create & Adopt</h4>
			<p>Next.js, FastAPI, NestJS, Go, Spring Boot, .NET, and frontend kits — or adopt existing repos in place.</p>
		</td>
		<td width="33%" valign="top">
			<h4>🤖 Agent Customization Pack</h4>
			<p><code>workspace agent-sync</code> writes AGENTS.md, Copilot/Cursor/Claude surfaces, and skills from the same evidence CI uses.</p>
		</td>
	</tr>
	<tr>
		<td width="33%" valign="top">
			<h4>🛡️ Release Gates</h4>
			<p><code>pipeline --strict</code> and structured reports under <code>.rapidkit/reports/</code>.</p>
		</td>
		<td width="33%" valign="top">
			<h4>🧩 VS Code Command Center</h4>
			<p>Repair flow, evidence cards, and Incident Studio for governed fixes with verify loops.</p>
		</td>
		<td width="33%" valign="top">
			<h4>📚 Examples</h4>
			<p>Starter workspaces and adoption patterns on GitHub.</p>
		</td>
	</tr>
</table>

## Core repositories

| Component | Repository |
| --------- | ---------- |
| CLI | [rapidkit-npm](https://github.com/rapidkitlabs/rapidkit-npm) |
| VS Code | [rapidkit-vscode](https://github.com/rapidkitlabs/rapidkit-vscode) |
| Core | [rapidkit-core](https://github.com/rapidkitlabs/rapidkit-core) |
| Examples | [rapidkit-examples](https://github.com/rapidkitlabs/rapidkit-examples) |

## Quick start

### 1. Install the CLI

```bash
npm install -g rapidkit
# or browse commands without install:
npx rapidkit --help
```

### 2. Create or adopt a workspace

```bash
npx rapidkit my-workspace --yes --profile polyglot
cd ~/rapidkit/workspaces/my-workspace
npx rapidkit bootstrap --profile polyglot
npx rapidkit create project nextjs my-web --yes
npx rapidkit workspace model --json
npx rapidkit workspace context --for-agent --json --write
npx rapidkit workspace agent-sync --write --refresh-context --preset enterprise
npx rapidkit pipeline --json --strict
```

### 3. Open in Workspai (VS Code)

Install [Workspai from the Marketplace](https://marketplace.visualstudio.com/items?itemName=rapidkit.rapidkit-vscode), open your workspace folder, and use the Dashboard for evidence-backed flows.

### 4. Learn more

- [npm README](https://github.com/rapidkitlabs/rapidkit-npm/blob/main/README.md)
- [getrapidkit.com/docs](https://www.getrapidkit.com/docs)
- [workspai.com/stacks](https://www.workspai.com/stacks)
