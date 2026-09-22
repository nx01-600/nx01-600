### Hi, I'm Nicolás Carreño

Full-stack developer and Systems Engineering student at Pontificia Universidad Javeriana Cali, based in Cali, Colombia.

I work across the whole stack: backends in Rails, FastAPI, Node and PHP, frontends in React, Next.js and Astro, relational and NoSQL databases, Docker, automations and integrations with third-party APIs. I pick the tool the project needs instead of forcing one.

My strongest area is AI:

- **Agentic development:** multi-agent systems, orchestrators with tool calling, LangGraph, MCP servers, and agents that close real business flows (sales, quotes, scheduling, follow-up).
- **Generative AI:** RAG with hybrid retrieval, embeddings and rerankers, answers with traceable citations, voice (speech-to-text and text-to-speech), and running models locally with Ollama and LiteLLM.
- **Machine learning:** encoder and decoder transformer models, small language models (SLMs), semantic search evaluated with NDCG and F1, and data analysis in Jupyter.

I'm Claude Code's #1 fan. I use it every day, and I like it so much that I build my own tools for it:

- [**claudeTalk**](https://github.com/nx01-600/claudeTalk): a plugin that gives Claude Code a voice. It reads its answers aloud and lets me dictate with local Whisper on GPU, through a live liquid-glass overlay.
- [**claudeseek-code**](https://github.com/nx01-600/claudeseek-code): a local gateway that runs the full Claude Code CLI on DeepSeek models, escalating to Claude only for Anthropic-only tools like WebSearch.
- **Custom status line:** a Node status line that reads session usage straight from the transcripts, plus a git addon that points it at the right repo when the session runs outside the project folder.
- **Custom skills:** audio transcription with local Whisper or the Groq API, a web design skill with anti-slop heuristics, and delegation of heavy writing tasks to cheaper models.
- **Local agents:** an agent running fully offline on Ollama through a LiteLLM bridge, executing tools end to end.

I love hackathons: short deadlines, a real problem and a team that ships something working by the end.

---

### Hackathons

| Event | Result | Project |
| --- | --- | --- |
| **CODEFEST AD ASTRA 2026** (Colombian Air Force, Universidad de los Andes, Aval Digital Labs) | **1st place** | [AeroCode](https://github.com/JuanMCanchala/codefest-adastra): multi-agent analysis with traceable evidence |
| **Funnelchat Hackathon 2026** (Universidad de San Buenaventura) | **2nd place** | [End2End](https://github.com/nx01-600/End2End): AI agents that handle WhatsApp and Telegram customers from first message to booked meeting |
| **Platanus Hack 26 Bogotá** (AI Security track) | Participant | [Aegis](https://github.com/JuanMCanchala/aegis): conversational DLP for safe AI use at work |

---

### Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**AeroCode**](https://github.com/JuanMCanchala/codefest-adastra) | Multi-agent strategic-analysis assistant and visual dashboard over 1,825 multilingual documents. Every number traces back to its source fragment. **1st place, CODEFEST AD ASTRA 2026.** | Python, LangGraph, FastAPI, FAISS, BGE-M3, React |
| [**aerocode-demo**](https://github.com/nx01-600/aerocode-demo) | Post-hackathon consolidation of AeroCode, running on any OpenAI-compatible LLM with a lighter retrieval setup. | Python, FastAPI, React |
| [**Aegis**](https://github.com/JuanMCanchala/aegis) | Conversational DLP that stops sensitive data before it reaches an AI tool, and teaches the user why in the moment. Platanus Hack 26. | Python, local proxy, ML detection |
| [**ad-astra-retrieval**](https://github.com/JuanMCanchala/ad-astra-retrieval) | Multilingual dense semantic search over an aerospace corpus, evaluated with NDCG@10 and F1@3. | Python, FAISS, BGE-M3 |
| [**End2End**](https://github.com/nx01-600/End2End) | Team of AI agents that serves customers on WhatsApp and Telegram end to end: qualifies leads, sends PDF quotes, books meetings and follows up, with human takeover. **2nd place, Funnelchat Hackathon.** | TypeScript, Supabase, Twilio |
| [**claudeTalk**](https://github.com/nx01-600/claudeTalk) | Claude Code plugin for Windows: Claude reads its answers aloud and you dictate with local Whisper on GPU, through a live overlay. | Python, edge-tts, Whisper |
| [**claudeseek-code**](https://github.com/nx01-600/claudeseek-code) | Runs the full Claude Code CLI on DeepSeek models through a local gateway, escalating to Claude only for Anthropic-only tools. | JavaScript, Node |
| [**turing-machine**](https://github.com/JuanMCanchala/turing-machine) | In-browser Turing machine simulator: define it in YAML, see the state diagram, run it step by step. | JavaScript |
| [**Juan Esteban López portfolio**](https://github.com/nx01-600/juan-esteban-lopez-portafolio) | Architecture portfolio website with smooth scroll and WebGL effects. | Astro, TypeScript, GSAP, OGL |

---

### Tech I work with

**Languages**<br>
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img alt="C" src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img alt="Ruby" src="https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white" />
<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
<img alt="SQL" src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
<img alt="Bash" src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />

**Backend**<br>
<img alt="Ruby on Rails" src="https://img.shields.io/badge/Ruby%20on%20Rails-D30001?style=flat-square&logo=rubyonrails&logoColor=white" />
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img alt="REST APIs" src="https://img.shields.io/badge/REST%20APIs-555555?style=flat-square" />

**Frontend**<br>
<img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img alt="Astro" src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" />
<img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-663399?style=flat-square&logo=css&logoColor=white" />
<img alt="GSAP" src="https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black" />
<img alt="WebGL" src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white" />
<img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
<img alt="WordPress" src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" />
<img alt="Elementor" src="https://img.shields.io/badge/Elementor-92003B?style=flat-square&logo=elementor&logoColor=white" />

**Data**<br>
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" />
<img alt="Firebase" src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" />
<img alt="FAISS" src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" />
<img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />

**AI and ML**<br>
<img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white" />
<img alt="Anthropic API" src="https://img.shields.io/badge/Anthropic%20API-191919?style=flat-square&logo=anthropic&logoColor=white" />
<img alt="OpenAI API" src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white" />
<img alt="DeepSeek" src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square" />
<img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img alt="MCP" src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" />
<img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<img alt="Transformers" src="https://img.shields.io/badge/Transformers-FF9D00?style=flat-square&logo=huggingface&logoColor=black" />
<img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
<img alt="LiteLLM" src="https://img.shields.io/badge/LiteLLM-555555?style=flat-square" />
<img alt="Whisper" src="https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white" />
<img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />

**DevOps and tools**<br>
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img alt="Linux / WSL" src="https://img.shields.io/badge/Linux%20/%20WSL-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
<img alt="Twilio" src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" />
<img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
<img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" />

---

### Contact

- Email: [nicolasct0627@gmail.com](mailto:nicolasct0627@gmail.com)
- Location: Cali, Colombia
