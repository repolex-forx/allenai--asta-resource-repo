# Repolex Knowledge Graph of allenai/asta-resource-repo

RDF knowledge graph data for [allenai/asta-resource-repo](https://github.com/allenai/asta-resource-repo), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/asta-resource-repo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ab06f1ee12b9cf6dfad7f7e116e10df3047f2d8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ab06f1ee12b9cf6dfad7f7e116e10df3047f2d8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a08921963d8d3852dd3da4cb9dfbfd33d83b62f.nq.gz
│   ├── 0f083e69d71f12ba2e4d8e79c6fee0784edb9996.nq.gz
│   ├── 166dcbf09dbc853e9329b9cc2d0b60522d98289a.nq.gz
│   ├── 16cd242fedad71aaf07a2cde162cab2363ecbd3b.nq.gz
│   ├── 1b1c7f1c4ae52d32af92fbf724bd6a6928eaab4d.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2628d1f2672d145d2744ec824050661d1099e023.nq.gz
│   ├── 2c13e0cee02ab0ef7901c7f312b14dc3afdba213.nq.gz
│   ├── 2d2bfb44b3c227e9f89cca14fcc6f983435d9b11.nq.gz
│   ├── 33157cb2878d86aaec22a2dcc01ee67e2fe8de13.nq.gz
│   ├── 348927e2346825b67e1f81b1ad9022c7d5adb9c3.nq.gz
│   ├── 38a070d212cedfb532d840a824bf7061e19f49fc.nq.gz
│   ├── 4717012d8b10532a85597147eb98f8d85e9a1f8a.nq.gz
│   ├── 485f47bc87547016dc4947405568deebde79bfbf.nq.gz
│   ├── 50f281f032bb69c9e5eff0ef7ecbfdbc34448ad5.nq.gz
│   ├── 51504a9bd03e0db10802a4510a8eecbc24119bde.nq.gz
│   ├── 53530662f320e46bb9ff14afb74475117560e6af.nq.gz
│   ├── 57aa378e4b78ccc65cc5a5785d98dfa9b2a05f8a.nq.gz
│   ├── 57e8260d1a2f5b2ffd2b6fd813955f7bc2301f46.nq.gz
│   ├── 5de0a548728fa9eb00228753665c81302710fe11.nq.gz
│   ├── 66173aec46f4872ef3626ad8b9abd0a177334f34.nq.gz
│   ├── 72bc5fd3b3e6d56fc218c52cc9d556a11e7ab444.nq.gz
│   ├── 752caaa21bf98435583504f749fe4897eb0dc740.nq.gz
│   ├── 807d5983db8974da81873898c775358439450353.nq.gz
│   ├── 85151e9d12d0800284a6b3e66b780f083caaa456.nq.gz
│   ├── 8d005af170e20695d085f9386fa8e59f0525550e.nq.gz
│   ├── 8d5a7c1addb02d7d4ca11804262de588f4b87241.nq.gz
│   ├── 8da612586774fe4337a8cc865ac4f6d0027b498c.nq.gz
│   ├── 8dc40c230415cb596c08ebea5c60b42dbb1ed103.nq.gz
│   ├── 91607d79b111d0a4ed6df2d900cd5a7e0e191369.nq.gz
│   ├── 97a7f5078a5acc0dd4437818e1047522120209f9.nq.gz
│   ├── 9dba22f6340677a652d7996428af27a756ce1901.nq.gz
│   ├── 9e4aa6725232e2cf16258061b7b6b2358cb485bd.nq.gz
│   ├── a3e1ab70d47820ee4e9b0601270132ed6723664b.nq.gz
│   ├── b00bd34b0a2481586bcc899d4e8325b436eb0941.nq.gz
│   ├── bb20cca476fe3fabddb9028a07ce52c413c9801f.nq.gz
│   ├── c64314e550178ce77d8daa6861bfad6067069391.nq.gz
│   ├── ce2d5d34b37b2b4721985fa7240daacd9205702b.nq.gz
│   ├── cf2b50fa769f6ea588c858f5bd2baa096915b663.nq.gz
│   ├── d27a1db571d8f5ac7c319577295fac47e6dcfbb3.nq.gz
│   ├── df7a4af984b329ed7a5eec9482dd415f60fbcd43.nq.gz
│   ├── e4c083d1ff5af3cedeb0f6acc3a0d352352b9eac.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec8edb231a0d94bc4f55a74e5768521418da8fb8.nq.gz
│   ├── ee27a472cc9de974cb6183c085bc5a0622b4e77f.nq.gz
│   ├── f2427856e2cc2108d903a48af3772b975b6324fe.nq.gz
│   ├── fba84f04d1741beea0e6cf6f8b6d40170d2aa01e.nq.gz
│   └── fc849faccb3c1372eaded945d1156b6d78d1db22.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8ab06f1ee12b9cf6dfad7f7e116e10df3047f2d8.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 55 files
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

[allenai/asta-resource-repo](https://github.com/allenai/asta-resource-repo)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
