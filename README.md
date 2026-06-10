# Abhay Trivedi

### AI/ML Engineer — LLM tooling & agents

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-trivedi1)
[![Email](https://img.shields.io/badge/Email-555555?style=flat&logo=gmail&logoColor=white)](mailto:abhaytrivedi22@gmail.com)

Python engineer working upstream on the open-source LLM stack — merged fixes into [litellm](https://github.com/BerriAI/litellm) and [Haystack](https://github.com/deepset-ai/haystack-core-integrations) covering provider parameter handling, tool calling, and async streaming.

## Open-Source Contributions

| Repository | What I changed | Status |
| --- | --- | --- |
| [BerriAI/litellm #29779](https://github.com/BerriAI/litellm/pull/29779) | Fixed Cohere v2 chat silently dropping `max_completion_tokens`, so token limits now apply on the default route | Merged |
| [BerriAI/litellm #29812](https://github.com/BerriAI/litellm/pull/29812) | Preserved the forced-function `tool_choice` name through the Responses-to-Chat transform, so forced tool calls are no longer lost | Merged |
| [deepset-ai/haystack-core-integrations #3410](https://github.com/deepset-ai/haystack-core-integrations/pull/3410) | Fixed async streaming chunk indices in `GoogleGenAIChatGenerator` to start at 0, correcting off-by-one chunk ordering | Merged |

## Tech Stack

**Languages** — Python
**LLM frameworks** — LiteLLM, Haystack
**Provider SDKs** — OpenAI (incl. Responses API), Cohere, Google GenAI

## GitHub

[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abhay23-AI&layout=compact&hide_border=true&theme=default)](https://github.com/abhay23-AI)

---

Based in India · Open to LLM / AI engineering roles · Reach me on [LinkedIn][linkedin] or [email][email].

[linkedin]: https://www.linkedin.com/in/abhay-trivedi1
[email]: mailto:abhaytrivedi22@gmail.com
