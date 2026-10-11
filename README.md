# Repolex Knowledge Graph of celery/vine

RDF knowledge graph data for [celery/vine](https://github.com/celery/vine), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download celery/vine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ef33151cbb2787ad9a1ab64fb93c8fe2e54b0a09
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ef33151cbb2787ad9a1ab64fb93c8fe2e54b0a09
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f0434b85512ba88bc299565f7e3219ab90426e.nq.gz
│   ├── 08c14df60a1fe1f7e3b64c2c4efb79aff932a327.nq.gz
│   ├── 0a1cbfcd3036e816246e94f34534e879c1958d0b.nq.gz
│   ├── 0a949125133e07cd611351babb202a3a72b4249f.nq.gz
│   ├── 0f7ed41247d39c56ad15ce4625fe0018b4227222.nq.gz
│   ├── 110ac2c1f09914cc3c5147a538ed85dec77cadf1.nq.gz
│   ├── 123b65a497d5f316ed086bf683142c7efc075b5f.nq.gz
│   ├── 1a4fd77823a5329092d7f2a1e0070e3d17db1d11.nq.gz
│   ├── 1af4a31ac6337e473669a29f0231839a541e14d8.nq.gz
│   ├── 1d8c2f23c53a5e11a87e9efeb1a637965eb46c73.nq.gz
│   ├── 1e8760a45d98ab133f3be28cf3ec0c9adf813f95.nq.gz
│   ├── 201d119d778a998c688d7e301090aaf53a724ad3.nq.gz
│   ├── 21655fbf840de118bd765620649e4c30ade92973.nq.gz
│   ├── 2294bfe4bcb559a8ddb95fb4f4c49c8c8f22b34a.nq.gz
│   ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
│   ├── 3133f5f21564d10f87a71b3e1297318da8d6a5fb.nq.gz
│   ├── 3cb8d56d44e2a4496689aa60b841305c162c944b.nq.gz
│   ├── 41c3debc6895e07fbfbf753ea8fe07b87ac9f4dc.nq.gz
│   ├── 457f4aa6d4a5d621347584fd61d1aaffe2a12f9a.nq.gz
│   ├── 45fc2bf322d48d7897d857e6cbb38ed74ce2aa33.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 47b7a10fa8e3ef916c9c038a3612b62e8485bcb8.nq.gz
│   ├── 4fcc4d47c71388e04e7d31076d6987d2cae39307.nq.gz
│   ├── 52ca79685a33d5c99b434b3e713a054e601e4312.nq.gz
│   ├── 539a5fcb35bcaf83108623732688b1d3427f2f38.nq.gz
│   ├── 5a15de5c7e5219d652b9ae08b78d4e87dfab0a26.nq.gz
│   ├── 5a80ae78cdb293782bab633db06d9945946935dc.nq.gz
│   ├── 5b20da335b1980be7deed652749d4959d650f59b.nq.gz
│   ├── 623a2284f1f3643cc312592562d3d1e76ce4a9fd.nq.gz
│   ├── 68fef6a81c6cf591e99789a0e4384512114e4035.nq.gz
│   ├── 7349954b56a0a0d04c510c2b0e8ea80a56dfd376.nq.gz
│   ├── 7b8a9aeff5648039f60c7c9f32216e4d25d5d853.nq.gz
│   ├── 7e33b262ddd0dfb361ebefaf6fd51a64d764e2d4.nq.gz
│   ├── 8b960f380492fd80aa9f0221fa4351f62ed500a6.nq.gz
│   ├── 8ce7e455fe8aba3513d57202d4f55fe1463ebba6.nq.gz
│   ├── 8d9722791d911cd8ae45d57402d627165da14783.nq.gz
│   ├── 95343ab800a71846691c8fd310a441dcb99d775d.nq.gz
│   ├── 9680c58fd70bbc67da217b322f4e60215083c59b.nq.gz
│   ├── 97c4d14bcbfa0ead7ef826073e225e774c482f9e.nq.gz
│   ├── 9d33e345ba911862c6308bcfa318d45edb761ea2.nq.gz
│   ├── a75aa4e2866fbb962847b820983d264b108d9a7c.nq.gz
│   ├── c5e593767252ed15e68e9cb56c5024c5f08e23a3.nq.gz
│   ├── c703e7fda09f9b65a06e32798103a083b0272e9c.nq.gz
│   ├── cde7c44dfb76864319345e4af8e283406657a06f.nq.gz
│   ├── d4462ca294fe482f755354333a4f523862121e49.nq.gz
│   ├── d5c986ac4661b1b2239eb264f35f9771123e6af2.nq.gz
│   ├── da7087f682c9cf0adca6177b873ecc00ef8bcf14.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed4b886ea3fee8377dad7345ab215a26313b5b91.nq.gz
│   ├── f19a81127f00d26b4fd7be358c8e2751752fb04c.nq.gz
│   └── f7f6216accc553d4c5f21f910fe05b96308730fb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ef33151cbb2787ad9a1ab64fb93c8fe2e54b0a09.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[celery/vine](https://github.com/celery/vine)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
