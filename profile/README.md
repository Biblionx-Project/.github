# Biblionx Project

**Multimodal Translator to Dominican Sign Language (LSRD).**

Biblionx is a university thesis project (Trabajo de Grado, UNICDA) building an accessibility pipeline that translates written Spanish (Dominican Republic) into **Lengua de Señas Dominicana (LSRD)**, Dominican Sign Language. It covers natural language processing, a structured sign dictionary, a REST API, a 3D sign player and browser integrations so the translation can be used as a real product, not just a research prototype.

## 📂 Repositories

| Repository | Role |
| :--- | :--- |
| [**biblionx-lsrd-translator**](https://github.com/Biblionx-Project/biblionx-lsrd-translator) | 🟢 **Active, working repository (v2.2).** The Spanish → LSRD translation engine: Dominican Spanish normalization, ML matching, optional AI fallback, NLP module, SQLite sign dictionary, REST API, web playground and browser extension. |
| [biblionx-libraske-processor](https://github.com/Biblionx-Project/biblionx-libraske-processor) | 📚 Architecture reference: processing worker for pose extraction and gesture evaluation of LSRD signs. |
| [biblionx-player-webjs](https://github.com/Biblionx-Project/biblionx-player-webjs) | 📚 Architecture reference: WebGL 3D avatar player that renders LSRD signs in the browser. |
| [biblionx-translator-api](https://github.com/Biblionx-Project/biblionx-translator-api) | 📚 Architecture reference: translation REST API service that exposes Spanish → LSRD translation. |
| [biblionx-translator-text-core](https://github.com/Biblionx-Project/biblionx-translator-text-core) | 📚 Architecture reference: text translation core (NLP) that converts Spanish text into LSRD gloss. |
| [biblionx-web-browsers](https://github.com/Biblionx-Project/biblionx-web-browsers) | 📚 Architecture reference: browser plugins and embeddable widget for translating web pages into LSRD. |

The architecture reference repositories document the design of the Dominican Sign Language pipeline. They are not active dependencies of the final product; `biblionx-lsrd-translator` is.

## 🎓 About

This organization hosts the code produced for a thesis project (Trabajo de Grado) at UNICDA, focused on accessibility technology for the Dominican Deaf community.

## ⚖️ License

The architecture reference repositories are licensed under LGPLv3. See each repository's `LICENSE` file for details.

## 👥 Team

- [@MiraP7](https://github.com/MiraP7)
- [@Jose-hub-design](https://github.com/Jose-hub-design)
- [@wilkinvasquez](https://github.com/wilkinvasquez)

## 📬 Contact

Open an issue in the relevant repository for questions or contributions. Read [CONTRIBUTING](https://github.com/Biblionx-Project/.github/blob/main/CONTRIBUTING.md) before opening a pull request, and report vulnerabilities privately as described in [SECURITY](https://github.com/Biblionx-Project/.github/blob/main/SECURITY.md).

## Origins

The architecture reference components were initially forked from the open-source VLibras project. They have since evolved into independent projects of their own.
