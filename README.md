# Repolex Knowledge Graph of tiangolo/fastapi-cli

RDF knowledge graph data for [tiangolo/fastapi-cli](https://github.com/tiangolo/fastapi-cli), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/fastapi-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 093be9ca19f2ef44ba523aae0a98d6c9ea2e0888
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 093be9ca19f2ef44ba523aae0a98d6c9ea2e0888
│           └── chunk-001.nq.gz
├── blob
│   ├── 02080ec284abcbc28f90cc3d88b61ce732c96586.nq.gz
│   ├── 03ff41b36fb07425af74d23fe5a63afa079edb85.nq.gz
│   ├── 0702b65d0db8c2e3ebb7414b413c07183faa59fe.nq.gz
│   ├── 07991ed6ee5d64a354db278d639405b4d0c70266.nq.gz
│   ├── 0aa38c512c7964cd21abf351448504498126fb9d.nq.gz
│   ├── 0ad27aee0e22f37eb2cdd2f780032f753fdc87a0.nq.gz
│   ├── 0af7d37c47ac1155606c6d86c66705eb6c1a2cb2.nq.gz
│   ├── 109425d7cc395432df4a6e942094e74176647527.nq.gz
│   ├── 1190754e06742087b3b4cefe52dce45bd9089c0f.nq.gz
│   ├── 11bbf09b5e073869363186a468b38af280ebce91.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 173208d0fcdc12b93e573ebaa52081663140c2b5.nq.gz
│   ├── 1a8b84d8c92a9f8b3e7cf52aeffd80aaede28402.nq.gz
│   ├── 1ba31b578da735fd3d9a504faf4a06033571d321.nq.gz
│   ├── 20ae8e98b49fbfd717b2bfd5cc1e471160f6debf.nq.gz
│   ├── 22f3c9cce338c67c7066b0cbeb481af3556d36d2.nq.gz
│   ├── 2d5a2eb883b6ceabd87881559f979e06c80da916.nq.gz
│   ├── 2e0061f5e5dfaeeda49d050646d0a8c35a129f0d.nq.gz
│   ├── 2e5e42001c7155d68abbc5e5428c20e87839b211.nq.gz
│   ├── 3403d5ca143539b149f8a5e82ef55eac5b6ade4e.nq.gz
│   ├── 34527857d26b0764eaa56442e6c73d37adff0edc.nq.gz
│   ├── 35d089860c07306cb8c912c67f60c5679b5d3094.nq.gz
│   ├── 38b262dea091214ee619ccb247afdd515ea92ae9.nq.gz
│   ├── 3a8816c9ee242c60a463acead1b8a881a7adda08.nq.gz
│   ├── 407561da261915727fc7d23e33fa8a4ac7d77fd2.nq.gz
│   ├── 41e4150d193796f4e457931dba6c10552d559974.nq.gz
│   ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
│   ├── 4f2294a5b04fd500843cc605543fcbb1eb2c1a83.nq.gz
│   ├── 4fdb1c91b5a066fc781030efb6b1c2f11518c955.nq.gz
│   ├── 510b8f9515fa39fdd779d694498cfae689b395e8.nq.gz
│   ├── 517ac6422e2fe836060c86a5eae360d6afed3339.nq.gz
│   ├── 58bb20b090879360085ae7da8764d458648c54cb.nq.gz
│   ├── 597f25c6aa7250738c58258562e9a2349d6b79fc.nq.gz
│   ├── 71c0c8492bce23a05a5fa096af5c9a2a6ca52082.nq.gz
│   ├── 818155de3f47b571b83f740ab2ccecdecef379aa.nq.gz
│   ├── 84a1a152c626b344195ad536cf98e082c06fcb6f.nq.gz
│   ├── 851594dabaf62af9a28e0b5be3244437b101c0fb.nq.gz
│   ├── 8ab049ee73022b7903c1564c3ea164104bc25562.nq.gz
│   ├── 959cefd33305178dce72630375f97e3dab5f88e9.nq.gz
│   ├── 98d2517445b926bdcd1d05af16c8567d417afe01.nq.gz
│   ├── a3d9a05615d99183e246eae126a0a0b456e5c30c.nq.gz
│   ├── a58dda52d02117a5c03b5c81b0fc2b696df721e9.nq.gz
│   ├── a6fc3c2d99334dd6924d1268aa0ad7ad46401cde.nq.gz
│   ├── a8d4274f3b96598257576ee4bb9bd280f3b9ab99.nq.gz
│   ├── abca706f1d87f0b9f3e9f29e2f605036e676ad51.nq.gz
│   ├── bc3d8f100b688f44495a8e31a1c00d048ec6c2e6.nq.gz
│   ├── c197b73f8b847675f4edfe0b3f9ca28ccc5527ef.nq.gz
│   ├── c1f1a2786bcb6512756841de643f0e76f22ff2ee.nq.gz
│   ├── c2d0388bb13a586d6aabe044cea68b18264068c2.nq.gz
│   ├── c3dccbaeaefd25c4c82576a22cc58cf3f09b5a3a.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c9aa5241927d47da74b344d6457b0f8f474324ac.nq.gz
│   ├── d1ee96b3aea00fb06b8d367aba9c9b033f17c479.nq.gz
│   ├── d4e4fe07b48a59f6087242d73c807964457e0af7.nq.gz
│   ├── d609ee4a34e70f43d583db9b1483b3c69016568a.nq.gz
│   ├── d6c1816cc7975b0c1f03cdb51bf97e3821ac4ebf.nq.gz
│   ├── d722d960243b8204b0e4dbbdc03771ae3cbcc68c.nq.gz
│   ├── d850c65fea74ae9e00e21ff3092748ba6d9a9de1.nq.gz
│   ├── d8f504446e74eeb3245e7e2e64efac493761a19a.nq.gz
│   ├── da8eba1cd3b1bc4abb5a7ba88495615cae1de834.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecd288ba19b3d374f4353076bb36be677c180b89.nq.gz
│   ├── ef706eaeccc818c83d2921d7d1199f6ff9210a65.nq.gz
│   ├── ef9572e2d3830cb0a500298c3f646497903025a4.nq.gz
│   ├── f0f04afe94146cabf57cf3e63758294082cc8ff7.nq.gz
│   ├── f6b368906f6a7716261ed84909c5e057464ee139.nq.gz
│   ├── f79b147acc522bebcbc38cb606909d0dbc56fabd.nq.gz
│   └── f8fed7027f9106b3515d9c6ac2d572266e342b4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 093be9ca19f2ef44ba523aae0a98d6c9ea2e0888.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[tiangolo/fastapi-cli](https://github.com/tiangolo/fastapi-cli)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
