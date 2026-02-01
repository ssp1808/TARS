# TARS
Ai chat agent experiment to help and assist with everything and anything.

┌──────────────────────────────┐
│ Messaging Adapters           │
│ WhatsApp | CLI | Web | API   │
└───────────────┬──────────────┘
                │ normalized events
┌───────────────▼──────────────┐
│ Event Router                 │
│ (who said what, where)       │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│ Agent Kernel                 │  ← THE CORE
│ - Intent detection           │
│ - Planning                   │
│ - Tool selection             │
│ - Safety checks              │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│ Tool Runtime                 │
│ - Skills / actions           │
│ - Permissions                │
│ - Sandboxing                 │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│ Memory System                │
│ - Short term (context)       │
│ - Long term (vector store)   │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│ LLM Runtime (Ollama)         │
│ - Reasoning                  │
│ - Planning                   │
└──────────────────────────────┘