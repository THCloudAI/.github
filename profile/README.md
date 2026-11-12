<div align="center">

<img src="https://raw.githubusercontent.com/THCloudAI/thcloud-landing-page/main/logo.png" alt="THCloud.AI" height="72">

# THCloud.AI

**AI solutions for real business outcomes.**

We design, build and operate AI systems for real businesses — together with the self-hosted platform that runs them.

[thcloud.ai](https://thcloud.ai/en) · [hi@thcloud.ai](mailto:hi@thcloud.ai) · [@thcloudai](https://x.com/thcloudai)

</div>

---

## What we do

- **Applied GenAI** — assistants, document understanding and agent workflows that reach production. Our LINE customer-service agent answers end users with a human in the loop for approvals.
- **Platform engineering** — we run our own stack end to end: a model gateway, media portal, headless CMS, client data services, email and time tracking. Every service below is something we operate, not something we resell.
- **Agent interoperability** — MCP servers so coding agents can drive our platform directly ([thcloud-mcp](https://github.com/THCloudAI/thcloud-mcp), [genai-toolbox-demo](https://github.com/THCloudAI/genai-toolbox-demo)).
- **Data collection** — pipelines that gather and structure social and web data, delivered to client apps through an API gateway rather than direct database access.

## Stack

<p>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white" alt="NGINX" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" alt="MinIO" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

| Layer | What we run |
|---|---|
| **Edge & identity** | Cloudflare for DNS, WAF and Workers · Authentik SSO across internal apps |
| **Compute** | Docker and Docker Compose on Linux hosts · NetBird mesh VPN between sites |
| **Data** | PostgreSQL · self-hosted Supabase · MinIO (S3-compatible object storage) · Prefect for per-client ETL |
| **AI platform** | LiteLLM model gateway (OpenAI-compatible chat, transcription and speech) · MCP servers · ComfyUI diffusion workflows · MindsDB for knowledge-base search |
| **Business apps** | Directus (headless CMS) · MediaCMS (media portal) · Kimai (time tracking) · Listmonk (newsletter) · Postiz (social scheduling) |
| **Integrations** | LINE Messaging API · Google Workspace · webhooks and agent-driven automation |
| **Languages** | Python · TypeScript · Go · Node.js · React · SQL · Shell |

## Open source

| Repository | What it is |
|---|---|
| [thctl](https://github.com/THCloudAI/thctl) | Command-line interface to manage THCloud data storage and compute resources from the terminal — Go |
| [thcloud-mcp](https://github.com/THCloudAI/thcloud-mcp) | Custom MCP server Docker images, exposed through a Docker MCP Gateway |
| [markitdown-api](https://github.com/THCloudAI/markitdown-api) | API wrapper around Microsoft MarkItDown, with a Streamlit UI — Python |
| [genai-toolbox-demo](https://github.com/THCloudAI/genai-toolbox-demo) | MCP Toolbox for Databases demo against PostgreSQL |
| [thcloud-landing-page](https://github.com/THCloudAI/thcloud-landing-page) | Our landing page |

The LINE customer-service agent, the client data services (Prefect ETL: sync, embeddings, campaign sync, matching) and the social scraping pipeline are private — ask us about them.

## Work with us

Mail **hi@thcloud.ai** — or open an issue on the repository you came here from.
