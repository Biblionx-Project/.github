# Biblionx Project

**Multimodal Translator to Dominican Sign Language (LSRD).**

Biblionx is a university thesis project (Trabajo de Grado, UNICDA) building an accessibility pipeline that translates written Spanish into **Lengua de Señas Dominicana (LSRD)** — Dominican Sign Language. It covers natural language processing, a structured sign dictionary, a REST API, and a browser extension so the translation can be consumed as a real product, not just a research prototype.

## 📂 Repositories

| Repository | Role |
| :--- | :--- |
| [**biblionx-lsrd-translator**](https://github.com/Biblionx-Project/biblionx-lsrd-translator) | 🟢 **Active, working repository.** The actual Spanish → LSRD translation engine: NLP module, SQLite sign dictionary (2,458 entries), REST API, and browser extension. |
| [biblionx-libraske-processor](https://github.com/Biblionx-Project/biblionx-libraske-processor) | 📚 Architecture reference — adapted from [VLibras](https://www.vlibras.gov.br/) Libraskê Processor. |
| [biblionx-player-webjs](https://github.com/Biblionx-Project/biblionx-player-webjs) | 📚 Architecture reference — adapted from VLibras Player WebJS. |
| [biblionx-translator-api](https://github.com/Biblionx-Project/biblionx-translator-api) | 📚 Architecture reference — adapted from VLibras Translator API. |
| [biblionx-translator-text-core](https://github.com/Biblionx-Project/biblionx-translator-text-core) | 📚 Architecture reference — adapted from VLibras Translator Text Core. |
| [biblionx-web-browsers](https://github.com/Biblionx-Project/biblionx-web-browsers) | 📚 Architecture reference — adapted from VLibras Web (browser plugins and widget). |

The repositories marked as architecture references are forks of the open-source [VLibras](https://www.vlibras.gov.br/) project (Brazilian Sign Language translator), kept in this organization as historical/architectural reference for the design of the LSRD pipeline — they are not active dependencies of the final product.

## 🎓 About

This organization hosts the code produced for a thesis project (Trabajo de Grado) at UNICDA, focused on accessibility technology for the Dominican Deaf community.

## ⚖️ License

The VLibras-derived reference repositories are licensed under LGPLv3 — see each repository's `LICENSE` file for details.

## 📬 Contact

Maintained by [@MiraP7](https://github.com/MiraP7).
