# Hi, I'm yotta 👋

📍 **Tokyo** | 🛡️ **Guardrails for AI coding agents** | 🗂️ **Ops strategist by day**

I design operations for a living and write Rust and Zig after hours.
I build tools that check what AI coding agents do before I trust it:
the commands they run and the software they change.

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Zig](https://img.shields.io/badge/-Zig-F7A41D?style=flat-square&logo=zig&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)

## Start Here

- 🧿 **[omamori](https://github.com/yottayoshida/omamori)** - Stop `rm -rf` before your agent finds it. Blocks dangerous commands that AI CLI tools try to run.\
  Install from crates.io or Homebrew.
- 🤨 **[sideeye](https://github.com/yottayoshida/sideeye)** - Kills your program mid-write and brings back the smallest reproducible counterexample. It doesn't believe you.\
  Install from Homebrew or GitHub Releases.

## Also

- 🗜️ **[lossless-compaction](https://github.com/yottayoshida/lossless-compaction)** - Compacts a Claude Code conversation without throwing anything away: old tool output moves to local files, and the agent gets it back with `recall` or `find`
- 🧪 **[jevfuzz](https://github.com/yottayoshida/jevfuzz)** - Change the order, check the decision: does [Jev](https://docs.typesafe.ai/introduction) (a small model for fixed questions) give the same answer when nothing meaningful changed?
- 🎰 **[randomware](https://github.com/yottayoshida/randomware)** - A slot machine for software: real public APIs go in, generated apps come out

<details>
<summary>Resting — no longer maintained, but they still work</summary>

- 🔎 **[jev-intent-review](https://github.com/yottayoshida/jev-intent-review)** - Checks a PR against its stated intent, beyond the diff. Stopped: in its own evaluation, a frontier model given the same PR found more
- 🔑 **[llm-key-ring](https://github.com/yottayoshida/llm-key-ring)** - LLM API keys in macOS Keychain, not in plaintext `.env`
- 🐍 **[modern-python-guidance](https://github.com/yottayoshida/modern-python-guidance)** - Stop LLMs from writing 2019 Python
- 📐 **[intent-diff](https://github.com/yottayoshida/intent-diff)** - Intent-vs-behavior diff for pull requests
- 🗾 **[hyakkei](https://github.com/yottayoshida/hyakkei)** - Dashboards on the Japan Digital Agency Design System, in your browser
- 🐣 **[clawd-cardputer](https://github.com/yottayoshida/clawd-cardputer)** - A tamagotchi on M5Stack Cardputer that reacts to Claude Code
- ⌨️ **[cardputer-launcher-sdk](https://github.com/yottayoshida/cardputer-launcher-sdk)** - Keyboard-first app launcher for M5Stack Cardputer ADV

</details>

## Writing

Articles in Japanese on [Zenn](https://zenn.dev/yottayoshida). Short posts on [X](https://x.com/yottayoshida).

- [rm -rf を Trash に変えるだけのツールを作ったら、AIが無効化してきた](https://zenn.dev/yottayoshida/articles/omamori-ai-cli-safety-guard) - I made `rm -rf` go to the Trash, and the AI turned it off
- [上書き保存の途中で死ぬと0バイトになるCLIを12件見つけた](https://zenn.dev/yottayoshida/articles/sideeye-one-month-upstream-reports) - 12 CLIs that leave a 0-byte file when killed mid-save
- [RAGを作るのではなく、検索される知識を運用する](https://zenn.dev/yottayoshida/articles/rag-knowledge-ops-agent-search) - Don't build a RAG; run the knowledge it searches
