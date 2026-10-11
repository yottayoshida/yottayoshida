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

## Products

- 🤨 **[sideeye](https://github.com/yottayoshida/sideeye)** - Kills your program mid-write and shows what it left on disk, as a crash you can replay. It has caught real CLIs losing data. It doesn't believe you.\
  Install from Homebrew or GitHub Releases.
- 🧿 **[omamori](https://github.com/yottayoshida/omamori)** - Stop `rm -rf` before your agent finds it. Blocks destructive commands, and attempts to switch omamori off, in Claude Code, Codex CLI and Cursor.\
  Install from crates.io or Homebrew.
- 🗜️ **[lossless-compaction](https://github.com/yottayoshida/lossless-compaction)** - Claude Code compaction that forgets nothing. Old tool output moves to files on your machine, and the agent gets it back word for word. No summary, no model call.\
  Install as a Claude Code plugin.
- 🎰 **[randomware](https://github.com/yottayoshida/randomware)** - A slot machine for software: spin real public APIs, get a working app built by GPT-5.6, or an honest death certificate. [Try it live](https://randomware.randomware.workers.dev/)

<details>
<summary>Resting — no longer maintained, but they still work</summary>

- 🧪 **[jevfuzz](https://github.com/yottayoshida/jevfuzz)** - Find the input that flips the decision. Rewords inputs to a [Jev](https://docs.typesafe.ai/introduction) decision function in ways that shouldn't matter, and keeps the smallest one that changes the answer as a test
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
