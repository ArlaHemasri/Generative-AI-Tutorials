# Tutorial Task 5: AI Tool Comparison

## Problem Statement
Compare major Generative AI tools based on features, strengths, and limitations.

## Horizontal Comparison Table

| Tool | Main Use Case | Key Strength | Biggest Limitation | Live Internet | Context Window | Best For |
| --- | --- | --- | --- | --- | --- | --- |
| **ChatGPT**<br/>OpenAI | Learning, coding, creative writing | Detailed explanations, best coding | No live data in free tier | Yes, GPT-4o | 128k tokens | Students, developers |
| **Gemini**<br/>Google | Search + AI, Google integration | Live Google data, 2M context, free | Less creative writing | Yes | 2M tokens | Latest news, research |
| **Claude**<br/>Anthropic | Safe AI, long doc analysis | 200k context, safest, clear answers | No internet access | No | 200k tokens | PDFs, books, docs |
| **Perplexity**<br/>AI | Research with citations | Every answer has source links | Shorter, less creative | Yes | ~25k tokens | Assignments, fact-check |

## When to Use Which Tool
```mermaid
flowchart LR
    A[Task] --> B[Creative/Coding<br/>→ ChatGPT]
    A --> C[Latest News<br/>→ Gemini]
    A --> D[Big PDF/Book<br/>→ Claude]
    A --> E[Research + Sources<br/>→ Perplexity]