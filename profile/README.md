# Biblionx Project

**Multimodal Translator to Dominican Sign Language (LSRD).**

Biblionx is a university thesis project (Trabajo de Grado, UNICDA) building an accessibility pipeline that translates written Spanish into **Lengua de Señas Dominicana (LSRD)** — Dominican Sign Language. It covers natural language processing, a structured sign dictionary, a REST API, and a browser extension so the translation can be consumed as a real product, not just a research prototype.

## 📂 Repositories

| Repository | Role |
| :--- | :--- |
| [**biblionx-lsrd-translator**](https://github.com/Biblionx-Project/biblionx-lsrd-translator) | 🟢 **Active, working repository.** The actual Spanish → LSRD translation engine: NLP module, SQLite sign dictionary (2,458 entries), REST API, and browser extension. |
| [biblionx-libraske-processor](https://github.com/Biblionx-Project/biblionx-libraske-processor) | 📚 Architecture reference — historically adapted from [VLibras](https://www.vlibras.gov.br/) Libraskê Processor; now independent LSRD equivalent. |
| [biblionx-player-webjs](https://github.com/Biblionx-Project/biblionx-player-webjs) | 📚 Architecture reference — historically adapted from VLibras Player; now independent LSRD player. |
| [biblionx-translator-api](https://github.com/Biblionx-Project/biblionx-translator-api) | 📚 Architecture reference — historically adapted from VLibras API; now independent LSRD API. |
| [biblionx-translator-text-core](https://github.com/Biblionx-Project/biblionx-translator-text-core) | 📚 Architecture reference — historically adapted from VLibras; now independent LSRD NLP. |
| [biblionx-web-browsers](https://github.com/Biblionx-Project/biblionx-web-browsers) | 📚 Architecture reference — historically adapted from VLibras; now independent LSRD extensions. |

The reference repositories were initially inspired by the open-source [VLibras](https://www.vlibras.gov.br/) project (Brazilian Sign Language translator). They have evolved into independent LSRD implementations and are maintained in this organization as architectural reference for the design of the Dominican Sign Language pipeline — they are not active dependencies of the final product.

## 🎓 About

This organization hosts the code produced for a thesis project (Trabajo de Grado) at UNICDA, focused on accessibility technology for the Dominican Deaf community.

## ⚖️ License

The VLibras-derived reference repositories are licensed under LGPLv3 — see each repository's `LICENSE` file for details.

## 👥 Team

- [@MiraP7](https://github.com/MiraP7)
- [@Jose-hub-design](https://github.com/Jose-hub-design)
- [@wilkinvasquez](https://github.com/wilkinvasquez)

## 📬 Contact

Open an issue in the relevant repository for questions or contributions.
