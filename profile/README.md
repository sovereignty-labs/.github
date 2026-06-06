Sovereignty Labs
Local-first AI infrastructure for people who want to own their intelligence.

Sovereignty Labs builds open-source tools for running models, memory, and agents on hardware you control.

No cloud dependency. No hidden model stores. No vendor lock-in. No permission needed.

Projects
Anvil
Run models on your own iron.

Anvil is a transparent local inference layer built around llama.cpp / llama-server.

Plain GGUF files
Visible runtime flags
OpenAI-compatible endpoint
Hugging Face model pulls
Multi-GPU and fleet-aware workflows
MCP tools for agents and operators
Repo: https://github.com/sovereignty-labs/anvil Website: https://sovereignty-labs.com/blog/introducing-anvil/

HEAT
Sovereign memory for local AI systems.

HEAT is a cognitive memory system built around the A2M protocol, hybrid retrieval, PostgreSQL, and user-owned infrastructure.

Repo: https://github.com/sovereignty-labs/heat

Hirdforge
Human-sovereign agent infrastructure.

Hirdforge is the larger orchestration vision: Kubernetes-native agents, GitOps workflows, infrastructure-enforced authority, and human-controlled automation.

Status: in development

Philosophy
AI infrastructure should answer to the person running it.

That means:

Models should be files you can inspect and move.
Memory should live in databases you control.
Agents should operate inside boundaries you define.
Infrastructure should be understandable, reproducible, and yours.
Start here
Try Anvil:

curl -fsSL https://raw.githubusercontent.com/sovereignty-labs/anvil/main/install.sh | sh
anvil runtime install
anvil pull unsloth/Qwen3-8B-GGUF:Q4_K_M
anvil serve &
anvil load Qwen3-8B-Q4_K_M.gguf
Then point Open WebUI, Continue, Cursor, or any OpenAI-compatible client at:

http://localhost:11434/v1
Links
Website: https://sovereignty-labs.com GitHub: https://github.com/sovereignty-labs X: https://x.com/the_arkitectai
