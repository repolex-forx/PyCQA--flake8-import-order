# Repolex Knowledge Graph of PyCQA/flake8-import-order

RDF knowledge graph data for [PyCQA/flake8-import-order](https://github.com/PyCQA/flake8-import-order), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/flake8-import-order
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1cf24157c650562c17da8e4ff4f7585db7cf7edd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1cf24157c650562c17da8e4ff4f7585db7cf7edd
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ff7fea63c3f52b816998d2b1653c2c49504a09.nq.gz
│   ├── 064dff0eef6f6b6803f1e85189d8d9eeedf0121f.nq.gz
│   ├── 07c6f03b1a9e505f8e10b011e304f764e71fd730.nq.gz
│   ├── 08d4eb731a39860739cde7d048c8a0163e13e280.nq.gz
│   ├── 0c6bbca7b7bf096e21870f03a0944dc4d5b417ac.nq.gz
│   ├── 0f6a0159467b8a8e99b6a09335fa10006c69648f.nq.gz
│   ├── 18174bb75b7f6e27e5ea021252bf3d4a6e6547e1.nq.gz
│   ├── 1b915bb9d346253a7f7401455ae79f2b83f428a7.nq.gz
│   ├── 1f5005f2fab936791dab61415f3de77b0effb28c.nq.gz
│   ├── 253bcb76bad2d73c891ec0fa49aed4c2b24181f9.nq.gz
│   ├── 2add7e5542e84b4ddab3963e2be42c4177e02a3b.nq.gz
│   ├── 2cb3417f30c455335f85877ecb65bcbbf1b0a839.nq.gz
│   ├── 3844136b9db4b5e63349cc34763fcd10c2794d66.nq.gz
│   ├── 3ef94c8c08c657df681afaaef6c6f5d5e55e21d5.nq.gz
│   ├── 48897453c2c8c50484d110544bea099e2a791400.nq.gz
│   ├── 4891cae587bc9cd12250252673bafa2e07afe0e8.nq.gz
│   ├── 4bcb8da771728b00435ff034f0e8eb340d0f0153.nq.gz
│   ├── 4e204a706a56fdadfd84955f64cd20b4d6e86079.nq.gz
│   ├── 50c37e25e8f207890665d03aee6943f994d225d7.nq.gz
│   ├── 5240477658bf8d224533f4dfeda6978e59817af0.nq.gz
│   ├── 541ac92e2d53a13fc8a170203a3c6aa8b844e57e.nq.gz
│   ├── 59fd913716fd693da0d88a89a5d8204ff185a5e5.nq.gz
│   ├── 5b27e2fe3ec23ae427bdf2b2d7b3631c5b496b6c.nq.gz
│   ├── 5b5040472bdbc2618cac0776c81b01c4a69e3cef.nq.gz
│   ├── 65c5ca88a67c30becee01c5a8816d964b03862f9.nq.gz
│   ├── 700594c52df8f1d783ad5b02db70b323b3f2ab39.nq.gz
│   ├── 74be7a0f677248dfd6c524b4ab71885700985ede.nq.gz
│   ├── 77aafd8ca5c7d67eb5852d872251b10a5c44f386.nq.gz
│   ├── 7abe74e6e0531bd2ac4daebccb03b17ccb0b5efb.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 7f7ab37eac05c53ef75d8c32777eadb3bb491328.nq.gz
│   ├── 806eeda9c469030643ae518972627d81038a282a.nq.gz
│   ├── 8185f7115d2963e778ef0fbf1038a82439255073.nq.gz
│   ├── 824704fc7fe97bfcc9a36972dcdfb48c79c391d1.nq.gz
│   ├── 887201fe7af8e0abb93a2918e41962ef9173db79.nq.gz
│   ├── 8c46bbc7301098ccf6bc8b440ff64ce4523c3456.nq.gz
│   ├── 8efcc31189eb5ba056e8f087c0498c2b0c4ac221.nq.gz
│   ├── 9436816245d248f26c823672c554c8e20a6007e6.nq.gz
│   ├── 94dbf1e6270e623292203b37b384fc8c216cda58.nq.gz
│   ├── 9e35892b1e575ee601244b7f9b602df6acad722f.nq.gz
│   ├── 9ecb0ff878f727ff037c980d88235ccc01438a77.nq.gz
│   ├── a650bb08c73aeb9b36af79a8c8a6e8a40814e0dd.nq.gz
│   ├── c0a96271a17c26af013e9d34a06b16b1a3d725fc.nq.gz
│   ├── c47a8d7893f1ca285b6fd91252c7303212e1b5e7.nq.gz
│   ├── cee23b50599dfc181c508a78260d2045f758629f.nq.gz
│   ├── d1bd0be02963d1d7562bc1b4ed0340f17dfa3cac.nq.gz
│   ├── d471a8cc41a661c68cc43e2ca6c811218d49df7b.nq.gz
│   ├── da714537477e0ad89bf6032cc99eac0df5dd5c98.nq.gz
│   ├── dc96c665ab667e4c60a220eb2e3b0d7559341068.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a7d3b3b2b47fd9c1123d974f9f93cd698f45aa.nq.gz
│   ├── f1e651f8fa4be1c5b416716dc213dd55cfef6ae0.nq.gz
│   ├── f5f29a9bc9233d6427579ef69cbb9e582e036676.nq.gz
│   ├── fcc75e228410811d54a457a413f04964c29c72ef.nq.gz
│   └── fe0fe6cc384ab630c5918396cccf3f0b8e9711f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1cf24157c650562c17da8e4ff4f7585db7cf7edd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[PyCQA/flake8-import-order](https://github.com/PyCQA/flake8-import-order)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
