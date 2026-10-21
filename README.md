# Repolex Knowledge Graph of scverse/formulaic-contrasts

RDF knowledge graph data for [scverse/formulaic-contrasts](https://github.com/scverse/formulaic-contrasts), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/formulaic-contrasts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 180d601657c84734778dd69caaa06573fea9c63b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 180d601657c84734778dd69caaa06573fea9c63b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 0a01db01fe20a938979eae28a282772f84e0e341.nq.gz
│   ├── 0fbffefe3ab9d6fda9b0584a38e74c7ce0c0c279.nq.gz
│   ├── 1b17c57c562dacb004732a4aaef8bd05e14be0a0.nq.gz
│   ├── 2d3556679d802bbe6a8e22242210a7dace11f42a.nq.gz
│   ├── 31e10b3ea0930e8a0a9f6cbab9a2bc94459b578d.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 45643db182160f04b3ab01339901a825e46b8204.nq.gz
│   ├── 4c4a8608e9b58c9c001dd2e4489e821bcb56475d.nq.gz
│   ├── 4e004d010cf7bf578592addf874fe2071fb4241f.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 617de4288a3336d77a87b81cf9b4bc77a0fb9b43.nq.gz
│   ├── 62a7db0259d9bcaef870bc941a2926638af84d18.nq.gz
│   ├── 660e02ef8ff7d776e5730eaede43ff7205cbd530.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 69897c3b379c4b6c25f7b7a4e62f653a37399557.nq.gz
│   ├── 7b4a0cf87d73bbe25166dd0330e358876a2f0756.nq.gz
│   ├── 841bd7c207030e263bef011117c231dfc7a7cb65.nq.gz
│   ├── 903c5a722d4a83e9d984446350000d93cee695dd.nq.gz
│   ├── 9704d50ab5d9d1dffb34e440bb4bb770cf44dedf.nq.gz
│   ├── 9aaffcbbfeb9ad74c2af8cfef1101872828b7b61.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── a01d990f87dfd957b3800067ca7fe6b4b73cee48.nq.gz
│   ├── a5a20e68c8a77dd7eacbadf8336638dfbe0be957.nq.gz
│   ├── a6fa580344bebc29d0cacb0711046e4ab8ebbfdb.nq.gz
│   ├── b5f7c83917f5c315d02a3a0b7b262d4f804f7ea3.nq.gz
│   ├── b6715d6f286006e6463342c40d25835976eee843.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── bf5bdf969d40eee14b2a6e026bfd4f731bd88b26.nq.gz
│   ├── bfa2cf000e7714b0f0a9ff485808bd3c93a99e58.nq.gz
│   ├── c31893ac04fb775ae5a123685ca79c9a02b6721f.nq.gz
│   ├── c31a275101243663f6673a0098a41e0457a5a4a6.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d3ace1dda9392bbdc35866a2b877403ff0d73388.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── da4a605a84b063f8ad1f5b5d576498e8c2f0a6c9.nq.gz
│   ├── e0ea8015810bc0b12fd49637d17b2b4af72af55a.nq.gz
│   ├── e400b056c0b49e89591f230bd28470ce61a982fe.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86647dc4c7cfc18a7b4cb10b414592dd6d84345.nq.gz
│   ├── ea05ca3b7c2a86e0a1707a8e43748fc164dd58e8.nq.gz
│   ├── f80801ad70a30329a47fca3e6b98ab3cc5b6ed14.nq.gz
│   └── fe56436da7603768c96f95350a88a386f7b01d91.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 180d601657c84734778dd69caaa06573fea9c63b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[scverse/formulaic-contrasts](https://github.com/scverse/formulaic-contrasts)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
