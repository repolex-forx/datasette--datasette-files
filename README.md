# Repolex Knowledge Graph of datasette/datasette-files

RDF knowledge graph data for [datasette/datasette-files](https://github.com/datasette/datasette-files), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-files
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 011d2106dcd014341c469f09a61f5965610bd82c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 011d2106dcd014341c469f09a61f5965610bd82c
│           └── chunk-001.nq.gz
├── blob
│   ├── 05438cdc42e3e8302c31697ab32aea996766b047.nq.gz
│   ├── 08e7631d318c1e44455646db56d49d2bdd30a4e8.nq.gz
│   ├── 097dd39a5d8c6489a5da9248d926008593ace94c.nq.gz
│   ├── 12e9048cc08e6dd1da7e4285a03dd67a006434b1.nq.gz
│   ├── 163f4965b30524c7644270fb6c542d168f833be1.nq.gz
│   ├── 20005d2b926a898c0be72ade540e456bc6a5f10d.nq.gz
│   ├── 200b36fe162207d446bba4f8b9a6cb1288014dbd.nq.gz
│   ├── 238bf139313fceb7ff61b3f747131732d6269c48.nq.gz
│   ├── 25a87cf48166f2c392f005679c6b417d885f1cb2.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26b96292e9ba81bf8de1269802187a5928ed8659.nq.gz
│   ├── 30fe7e9bbf26cf2ec125c0bddedae18ab9b08117.nq.gz
│   ├── 36b9c462a904a05e460d68110ed3bebc6d10897f.nq.gz
│   ├── 3eb5082b6b06efba5841ef17c0baf73457615963.nq.gz
│   ├── 4412e32aa541bfd8c5af29bfa690080c74b9dff3.nq.gz
│   ├── 4707cd59659b1c10b060cdbceeda3b9555f568fd.nq.gz
│   ├── 4b10b342df6554f2dfa5f2411a2a2db93a03b17c.nq.gz
│   ├── 4cba8f8a80deb7205ec4057ff6c122a04ea11cec.nq.gz
│   ├── 505d262ea90e512056895b8877923635a07625d3.nq.gz
│   ├── 51b95746a18348c0645c4ee7cbe6a259b53c332e.nq.gz
│   ├── 604d48c253bb089fee5d900411a59be38ca12e36.nq.gz
│   ├── 6198923cf98d5c8e28e4dc124eb03208f45be4e1.nq.gz
│   ├── 63f3107adec1b37524d5d74f2eb40c3e067eaf71.nq.gz
│   ├── 667ec7a552c088073bd95faddfdbf365a1fca032.nq.gz
│   ├── 6776e7bc17f88bbdc22913f70197c114802b5b28.nq.gz
│   ├── 6b52f6b20acce259041078ac7a2c809aa604a259.nq.gz
│   ├── 6c7f950ee6c0fb22f53bc426c06d3c4bfb4625c5.nq.gz
│   ├── 78836837d4fe46852f0eedaebab613ef4b2cbb09.nq.gz
│   ├── 87a59c1e075a04360009ac6f9096de9a36e189db.nq.gz
│   ├── 9272ef91f767976e27f37399dd42d7531ae5f64b.nq.gz
│   ├── 98dc048201d43a9c1ab401365dc9fcb4fd4f6ee9.nq.gz
│   ├── 9b179f7c68123bf50dce6b8f11d4862b84a914fc.nq.gz
│   ├── 9e46463ec5a80b0b5873c1c57a2e3f5aa6e6f33f.nq.gz
│   ├── a271eee341406fca448390b511ba8fe079e234a3.nq.gz
│   ├── a4a0f5cf8614fcfba95636caf29a375c4badf780.nq.gz
│   ├── a70158fd2b5a66d09b85a80b559f5bd3ee71de8e.nq.gz
│   ├── bb972e41bb5029d98e7a6e1f5c659fc361d8bb7d.nq.gz
│   ├── be26ce8c553305c20827ce2c2d4520a8bbe276ea.nq.gz
│   ├── c19b0fa8a0b35c32d91a1862a6a4d81de0728b85.nq.gz
│   ├── c6045c63fc034c91a859fbd8bdc435be72a51b45.nq.gz
│   ├── c9dddc39b6addba11e3052b58421bd810f766eb4.nq.gz
│   ├── d4f41977bae4f9ec8acc8ed7e9725344bacd95e2.nq.gz
│   ├── d594c720e8c0fcc6528fec49bca86ff12ba51ae1.nq.gz
│   ├── d81b05cae2ab69e8b297ba45c31dd334181dac90.nq.gz
│   ├── da2d17ab0f39d0306a31850d5a69ffbc9007171d.nq.gz
│   ├── ddd2d5546ddf072add13f71ffd4469f2d3706b4c.nq.gz
│   ├── ded70cc2bdfc7d35a1513e8c4cde7aab3db70fd9.nq.gz
│   ├── f691681850cda2292b7f915eaa16a81d9fd01886.nq.gz
│   ├── f71537f9fcbe8456ea6d15c63bd70916c720f136.nq.gz
│   ├── f76778cc0a0ff4f87bf7c7b278673ccdae0d7ce9.nq.gz
│   └── fe497b391574688ece4ee308620a868a270f8626.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 011d2106dcd014341c469f09a61f5965610bd82c.nq.gz
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

[datasette/datasette-files](https://github.com/datasette/datasette-files)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
