# talumi · तलुमि · タルミ · 塔鲁米

**A translator answers for every word.**

Talumi is an open source project built for professional translators. Any AI can translate a document in seconds. Talumi gives the translator a method to check that translation, find the passages where an error would change the meaning, and deliver a certified document they can sign.

> Status: **beta, in preparation.** This repository publishes the method, the rules and the roadmap. The engine code will be published here as soon as the first checking path is implemented. The service opens at the same time.

Website: https://xi-app.pro/book/talumi/

---

## Why

```
Harry Potter and the Philosopher's Stone
↓ translation · 231,000 tokens · 25 min · $0.10   (the whole novel)
Harry Potter i Kamień Filozoficzny

"...make sure the infusion set is disconnected..."
↓ one wrong word · 3 tokens · 0.6 s
"...make sure the infusion set is connected..."
```

A translation can read perfectly and say the opposite of the original. In 2010, the German manual of an insulin pump printed a warning correctly on page 73 and reversed it on page 71. Fluency is no proof of fidelity. See [docs/cases.md](docs/cases.md).

## How it works

1. **The translator translates.** Their version is recorded first, before any machine output is shown.
2. **Independent paths check the text, blind.** The source is translated through several languages with different roots (for example Italian → Korean → French, Italian → Swedish → French). No path sees the others.
3. **The paths are compared.** Talumi brings out the passages at risk and the passages that need validation: conditions, exceptions, negations, obligations, numbers.
4. **The translator decides.** Each flagged passage is reviewed by hand, with the reason recorded.
5. **Every check is traceable.** Talumi records which models actually ran, when, and on what. A check that did not run is shown as not run.

The full method: [docs/method.md](docs/method.md).

## Certified translations

The engine is open. Anyone can run it, study it, improve it and use it in their work.

The **Talumi certificate** is different. It is issued only by the Talumi service, for translators listed in the Talumi registry of verified professionals. Each certificate carries a code that the client can verify on the Talumi website. See [docs/certification.md](docs/certification.md).

## What this repository contains

| Path | Content |
|---|---|
| `docs/method.md` | The checking method |
| `docs/cases.md` | Documented translation errors, with sources |
| `docs/certification.md` | How certification and the registry work |
| `ROADMAP.md` | What comes next |
| `CONTRIBUTING.md` | How to contribute, including difficult cases without code |
| `TRADEMARK.md` | Rules for the Talumi name and logo |
| `LICENSE` | GNU AGPL v3 |

## License

The code and documentation are released under the **GNU Affero General Public License v3.0** ([LICENSE](LICENSE)). You may use, modify and redistribute Talumi, including commercially. If you offer a modified version as an online service, you must publish your modifications under the same license.

The license does not grant any right to the Talumi name, logo or certificate. See [TRADEMARK.md](TRADEMARK.md).

## Contributing

Translators are welcome before the code is. The most useful contribution today is a **documented difficult case**: an original, a plausible wrong translation, its consequence, and the right solution. See [CONTRIBUTING.md](CONTRIBUTING.md).
