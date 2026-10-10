# Repolex Knowledge Graph of jazzband/icalevents

RDF knowledge graph data for [jazzband/icalevents](https://github.com/jazzband/icalevents), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/icalevents
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9794b29e9d59d534a571361f9dd92018a5dc01c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9794b29e9d59d534a571361f9dd92018a5dc01c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 03cf293e900c74b455d5fa0d70017fd21ea11589.nq.gz
│   ├── 05066186299acdaa6f5e6aa601a8d1397fbc2151.nq.gz
│   ├── 0b028fd9f0553a6a729b2c09b0f60fdd64a24576.nq.gz
│   ├── 0d5087971eb6ee5221b6a57bbe3c205e114e6b1e.nq.gz
│   ├── 228f2b4a3ac35976ec11efed8cc7091b307e781b.nq.gz
│   ├── 2e0fc7fcb5dbac9d6e7176d3f7c1becbd0f6e64d.nq.gz
│   ├── 34be33ba8a588b4ea982307a456a1f7ec97ec20b.nq.gz
│   ├── 3731b0dc192b658605f65ac50ea8ffded78c3e9b.nq.gz
│   ├── 3a8c073a52d212bf3b1cb57ff432c02b3ff7fddc.nq.gz
│   ├── 3b018fd74591dc958e7bbf83c88340706c1c4d0c.nq.gz
│   ├── 3ba76f679f7e4cbf40d47eaa01b2ad814aa3cec0.nq.gz
│   ├── 3bcd697f02a755b88dbff261f030d659bbc76836.nq.gz
│   ├── 3d74aab901b3a6242e20b906be370510420fcd22.nq.gz
│   ├── 3e65d6d6640bb64c16563560c859458d60c2b76f.nq.gz
│   ├── 405f842c7ded901a156f587456789386bfaa5121.nq.gz
│   ├── 41d0722973d2fbbaacfade2538d3345cd2cf0bdb.nq.gz
│   ├── 425a4ead6ab93b0ce96d07ccbc40ed8d8d021e77.nq.gz
│   ├── 50099d7282aeb80aa339c7b44ec6909481b7a53a.nq.gz
│   ├── 5075ce34781c63c965514ba12514808d800acb9c.nq.gz
│   ├── 51243ada2ed9281c5be1f421fb398c6b6082fbf7.nq.gz
│   ├── 59557865445a777116589f67b4d87ba87a4f0c24.nq.gz
│   ├── 5a6e65ff2cf03f8adf198914b254ce854b13c883.nq.gz
│   ├── 65e9e4e8ba79685b7730965d659e2b74c36f6519.nq.gz
│   ├── 6b599c42c560e85a6ec2baf62b39f26f3c2e4036.nq.gz
│   ├── 6bb938c80dde89a94e60b0b5b0121eac47895d0b.nq.gz
│   ├── 6c440502206787e4a64a117848ed91893058530d.nq.gz
│   ├── 6c72fd93e2cdc59dc90973312a8d784174071526.nq.gz
│   ├── 6f29bd074ec8022f12c1833d0bddf5517ed35f8c.nq.gz
│   ├── 77ad2f2713b3df1b444205b25617839bb6a50f40.nq.gz
│   ├── 7a6441b622147f81d0c2ca014a3e48a99e53b1eb.nq.gz
│   ├── 8675cf2031a4d25a21f9a190e31bc65e89adde09.nq.gz
│   ├── 87ae1f82dab2a67b7eba4e1e030c60971cc37aba.nq.gz
│   ├── 89896da1192ec6bf5d0797d2a96def86c9c30b63.nq.gz
│   ├── 8c07e394779733c43d7d6aa4a4b5e960f119baba.nq.gz
│   ├── 93e498810a4f25ac1f2239ad840fc72f6f792c79.nq.gz
│   ├── 9ce3845717175ba4f3f638c16ac04397f64ba0a5.nq.gz
│   ├── a069ad862d49485f6fd1ff61dae873802c3e38be.nq.gz
│   ├── a7a831c0d7de4c538719378810940f4a085c69e3.nq.gz
│   ├── aa1adb91a6ea268c6bfc90dba0499838a8256f63.nq.gz
│   ├── ab5f8615ccf5fbbefdaba314168b908f957683a6.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── adac9a3558e0a88e1b2d964c383f9d6b90958c5b.nq.gz
│   ├── b68640669483b5415ee4e9cf13a680dda059be49.nq.gz
│   ├── b88034e414bc7b80d686e3c94d516305348053ea.nq.gz
│   ├── b9b66d0defb4492ec62cc4da88f082a5bf9515aa.nq.gz
│   ├── bb42e1a5ca81ed0923e46caa04feb5079019e216.nq.gz
│   ├── be26adeb020b330a0c21400a91a237343d674c32.nq.gz
│   ├── becea354aab3f785c33f4cf23ea1c9eaca537ac9.nq.gz
│   ├── bed4f1bbaee1bdecd66523548b13640602f2c16e.nq.gz
│   ├── c1e2e762d9c43ac47d596f5d12f8168cc49d30fa.nq.gz
│   ├── c281211530a329059116eee7bb8bf1c2ebbbcdf4.nq.gz
│   ├── c2fdddce7e707f2af769b9255fbdeb619a316eeb.nq.gz
│   ├── c442f2d63987cf0943a74fc6c8438acd893d917e.nq.gz
│   ├── c98067e64fb29d602543d6f5980316ae9d903c49.nq.gz
│   ├── d0c8e199819992ea4558199b641b90325d88669f.nq.gz
│   ├── d1e1e61a61663107c6b3e01dbaf5220e6cb85e1c.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d91228ce1298ac36d1a8b07dc841da1e25fcb102.nq.gz
│   ├── d9a103ec09fa04c0f7fde2c644fe9306f138709b.nq.gz
│   ├── db05dbd88b203209bdb6e4c919e394feffc4a324.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e126df8a77dc5af3a22f8a6d813eaa4543a87fd4.nq.gz
│   ├── e69d87e8897d9d749982ae46ae8e1c5bd230ac9a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73c8f451a23faf28c087eca0801374f0a086fc9.nq.gz
│   ├── e8d89e8bc8d98ba9840d1baeef3343cb0e145249.nq.gz
│   ├── e9ad1ef8cded0a007f815984fa176af65bff1ad0.nq.gz
│   ├── f270f3c8ad59af7f8eee4dd8e1c4504c4d9f3d06.nq.gz
│   ├── f3808e6c1943165ca59f02fa9b85223e6abb48b5.nq.gz
│   ├── f441fda722e62e10c9c22276bf76a9af03d72e2e.nq.gz
│   ├── f66cbf73367e6943fbe1d4301c91ff234c81f432.nq.gz
│   └── f6e3eeec68dad8a31ae6910c7dd7102bdd2ca2a3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9794b29e9d59d534a571361f9dd92018a5dc01c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[jazzband/icalevents](https://github.com/jazzband/icalevents)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
