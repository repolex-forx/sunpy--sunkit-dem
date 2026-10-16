# Repolex Knowledge Graph of sunpy/sunkit-dem

RDF knowledge graph data for [sunpy/sunkit-dem](https://github.com/sunpy/sunkit-dem), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunkit-dem
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e5dacc21c84c071aabf6e563e52044ac007726b5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e5dacc21c84c071aabf6e563e52044ac007726b5
│           └── chunk-001.nq.gz
├── blob
│   ├── 042a14edc8b181b004853f273371c3576c37ff22.nq.gz
│   ├── 09d9cf6b81550854f33e3edf1768fe3127f21090.nq.gz
│   ├── 0d2dde9cbe18335c82a3b7fb8b14e6b323871205.nq.gz
│   ├── 153c51c166827119295a2a1515c814cca1457ca4.nq.gz
│   ├── 1727d632d77e75dd60ad4c192388834c01665673.nq.gz
│   ├── 18d666e9133d8abd398a675e0f8fe515374ad7d5.nq.gz
│   ├── 1a2c804449029f5ff197f79984577c34b40d7c87.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 2c76e6127fafa17411013fb3b9df316910e3df44.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 38634284f2d4e8015dddb8aebb2012b01232fd9e.nq.gz
│   ├── 3c9d82e2466db4a027612954c8fec41b1cbb5ff3.nq.gz
│   ├── 3ff6dba6161133bd788585836ab9dcf977923d67.nq.gz
│   ├── 4d4ed0fbae99c908d3902a39fa8b7a5785e4259b.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6890bc29b654e742c8ef0455cc88b9b0fc379c00.nq.gz
│   ├── 6b53520aa4d54ee783c6b5c79378a4a035be5eaa.nq.gz
│   ├── 6cc801ce99d306ca4ee651259d2d7fb4c451dc0d.nq.gz
│   ├── 6ece151a3e9b434dee07712f0fe35eaa0e4ce95f.nq.gz
│   ├── 773f36d24a0a0417718e6cac925a45a6436135eb.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7a543d5164232a2b1c42517e48229319d5f247b6.nq.gz
│   ├── 7c3539b745322d7f2458e1375643890f8b54a815.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 89d4dd8a3ba6313e95500048da00594ac66f05c2.nq.gz
│   ├── 8dfe3a3fa32f29f9bd7ecbe69db6e2ce56eaaddb.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 988debf51060eb223212788187f60b37891ac768.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c91fab521cc5a5644e1595c74dc61477f882bdce.nq.gz
│   ├── cfc0c29cae8f0467149a43285d6291690dcb40df.nq.gz
│   ├── cfdb6f8cf087446873d5d0482ae23ed81ccb7e95.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── dd1c80d3894bd3570abe348531b7b55903a14a5a.nq.gz
│   ├── e0ca8d75189eb2ec852ea0b1b8d1ca8163dc5e3b.nq.gz
│   ├── e1814ab0f4cfc0dcedf36e3d0481a6c68dc96652.nq.gz
│   ├── e1caafaf520aca5a178837426fc829c68b39dd84.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e396791f235b784b9e66282ce866dbc65d439080.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7399bda1bb64cb5e5648c7b921fc9080c2e687f.nq.gz
│   ├── f29177b0b7bcc2c96b3a54858969f0edbd5032fe.nq.gz
│   ├── f475a3832b0808d663840c5b3bc8d54c70506f9a.nq.gz
│   └── ff217a8a5f477c7078cf1978ba2bbf987484ce68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e5dacc21c84c071aabf6e563e52044ac007726b5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[sunpy/sunkit-dem](https://github.com/sunpy/sunkit-dem)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
