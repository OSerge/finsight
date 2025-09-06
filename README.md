# Finsight

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Product Features
- Chat-based Document Q&A against a pool of documents
- Citation of source data that LLM response was based on
- PDF Viewer with highlighting of citations
- Use of API-based tools ([polygon.io](https://polygon.io/)) for answering quantitative questions
- Token-level streaming of LLM responses via [Server-Sent Events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)
- Streaming of Reasoning Steps (Sub-Questions) within Chat

## Development Features
- Infrastructure-as-code for deploying directly to [Vercel](https://vercel.com/) & [Render](https://render.com/)
- Continuous deployments provided by Vercel & Render.com. Shipping changes is as easy as merging into your `main` branch.
- Production & Preview environments for both Frontend & Backend deployments! Easily try your changes before release.
- Robust local environment setup making use of [LocalStack](https://localstack.cloud/) & [Docker](https://www.docker.com/) compose
- Monitoring & Profiling provided by [Sentry](https://sentry.io/welcome/)
- Load Testing provided by [Loader.io](https://loader.io/)
- LLM Observability by [Arize Phoenix](https://phoenix.arize.com/)
- Variety of python scripts for REPL-based chat & data management

## Tech Stack
- Frontend
    - [React](https://react.dev/) / [Next.js](https://nextjs.org/)
    - [Tailwind CSS](https://tailwindcss.com/)
- Backend
    - [FastAPI](https://fastapi.tiangolo.com/)
    - [Docker](https://www.docker.com/)
    - [SQLAlchemy](https://www.sqlalchemy.org/)
    - [OpenAI](https://openai.com/)
    - [PGVector](https://github.com/pgvector/pgvector)
    - [LlamaIndex 🦙](https://www.llamaindex.ai/)

### System Architecture
[![System Architecture](https://www.plantuml.com/plantuml/png/jLJ1RjD04BtxAuPmo2bLsgGIaH0YYMqe0XhL4HoggjhOKsVRzMoqEsuR4F_EncxTDEjGX8GFbdRUcpTldZVfGeXNaX2KMEkI8PC6KvQQRF0ggv7FKJo_d9zUdfry-3WFWgR3wiAzUAtS6vabvJQmDv9MmeW2LYAz4Jd2pm3SCt6dtEYIigbMsi3hy70wZ4O0NKYGOT70a5OuQoW4fqlW9O8mHj_LG2scJORcGMXGFLKzriI9_85mE6pEFYjXDAXvlS8jFAuU3s_qsf1gyubMsGuuLZ8dI95S9VWLR6MIAbrc_psHez6R_cJKdi1pFvbWiH1sxqUAmsWIzlq9uU1usE__pOJQQ2t_R4-lUJWS7KTLTRwKwGsXjN3qN8nqji_gt0YoZeN4EtPzx0NB1bCMbAkzgKJZA8p2bjodW-Zu3way2NVEa5pVGQgB3WWBzV5XtdaiB8zd9zLW1rpKrQdH19_qeZusNswcBUS6xMP0VRqwu-y998FEezoiN2YPmYoCOL8wHNuGd1bvAnWXOMr4ZbDDZFVSS9xqedj6Gq91WkPMfcWRwIIQTYr4MIuCECSNyBQNwJlgxRXrixHQvveEf8POag1KEhbGiDXfQryzGMAptZH_qIHP6qdvfadX5UzjEbqXZKyUFRyumwTxcxX47l_KEj_GfAYQ8Bwwv0wkBSIEp4wq8dSXSNpd5KHsNLekaDX2QJULfSmofFhdOGE_7thdDUMYpR5NsQOtDwAnlWstteTsvaitfDLskUgzynstKXsnpOpNN36RhThXFLxz3Vsv7kMV51j_mNjdgYnKy1i0)](https://www.plantuml.com/plantuml/uml/jLJ1RjD04BtxAuPmo2bLsgGIaH0YYMqe0XhL4HoggjhOKsVRzMoqEsuR4F_EncxTDEjGX8GFbdRUcpTldZVfGeXNaX2KMEkI8PC6KvQQRF0ggv7FKJo_d9zUdfry-3WFWgR3wiAzUAtS6vabvJQmDv9MmeW2LYAz4Jd2pm3SCt6dtEYIigbMsi3hy70wZ4O0NKYGOT70a5OuQoW4fqlW9O8mHj_LG2scJORcGMXGFLKzriI9_85mE6pEFYjXDAXvlS8jFAuU3s_qsf1gyubMsGuuLZ8dI95S9VWLR6MIAbrc_psHez6R_cJKdi1pFvbWiH1sxqUAmsWIzlq9uU1usE__pOJQQ2t_R4-lUJWS7KTLTRwKwGsXjN3qN8nqji_gt0YoZeN4EtPzx0NB1bCMbAkzgKJZA8p2bjodW-Zu3way2NVEa5pVGQgB3WWBzV5XtdaiB8zd9zLW1rpKrQdH19_qeZusNswcBUS6xMP0VRqwu-y998FEezoiN2YPmYoCOL8wHNuGd1bvAnWXOMr4ZbDDZFVSS9xqedj6Gq91WkPMfcWRwIIQTYr4MIuCECSNyBQNwJlgxRXrixHQvveEf8POag1KEhbGiDXfQryzGMAptZH_qIHP6qdvfadX5UzjEbqXZKyUFRyumwTxcxX47l_KEj_GfAYQ8Bwwv0wkBSIEp4wq8dSXSNpd5KHsNLekaDX2QJULfSmofFhdOGE_7thdDUMYpR5NsQOtDwAnlWstteTsvaitfDLskUgzynstKXsnpOpNN36RhThXFLxz3Vsv7kMV51j_mNjdgYnKy1i0)

## Usage
See `README.md` files in `frontend/` & `backend/` folders for individual setup instructions for each. 

## Caveats
- The frontend currently doesn't support Mobile
- Our main goal with this project is to provide a solid foundation for full-stack RAG apps. There is still room for improvement in terms of RAG performance!

