<p align="center"><strong>Mantis CLI</strong> is an authorized vulnerability-discovery agent that runs locally on your computer — a security-research-focused fork of <a href="https://github.com/openai/codex">OpenAI's Codex CLI</a>.</p>

---

## Quickstart

### Installing and running Mantis CLI

Install via npm:

```shell
npm install -g mantishack
```

Then simply run `mantis` to get started.

<details>
<summary>Building from source</summary>

No prebuilt GitHub Releases have been published for this fork yet. In the meantime, build from source:

```shell
cd codex-rs
cargo build --release -p codex-cli --bin mantis
```

The resulting binary is at `codex-rs/target/release/mantis`.

</details>

### Using Mantis with your ChatGPT / OpenAI account

Run `mantis` and select **Sign in with ChatGPT**. Mantis authenticates through the same OpenAI backend as upstream Codex CLI, so you can sign in with an existing ChatGPT Plus, Pro, Business, Edu, or Enterprise plan, or use an API key instead.

## Docs

- [**Codex MCP interface**](./docs/codex_mcp_interface.md)
- [**Bazel build**](./docs/bazel.md)
- [**Protocol v1**](./docs/protocol_v1.md)

This repository is a fork of [OpenAI's Codex CLI](https://github.com/openai/codex), licensed under the [Apache-2.0 License](LICENSE).
