# Repolex Knowledge Graph of jaraco/librarypaste

RDF knowledge graph data for [jaraco/librarypaste](https://github.com/jaraco/librarypaste), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/librarypaste
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c08f6b9bb5d40940d5d51c9f8723c8a3ffc95d02
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c08f6b9bb5d40940d5d51c9f8723c8a3ffc95d02
│           └── chunk-001.nq.gz
├── blob
│   ├── 004b33cbc5a3a333ec7a15c1989c3437c07c7c4c.nq.gz
│   ├── 00db792e0f14e0341e26a576b4e7b766ddd0c118.nq.gz
│   ├── 0bb19a4af855aec1d45df1b6e92ca9b9922b756a.nq.gz
│   ├── 0ceb843402dd1e7b1c2dde18291b59874df4daf8.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 1fc76cf0fa362e708fb9382f3ca60ebdadee20bc.nq.gz
│   ├── 2210dd84a44327ba2390c16c24c759cffeba6d29.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 27b3c587d327c3b1c80e6466d58644e35b6dc154.nq.gz
│   ├── 2d101469b6b3706c82a946d2eb1788613c5a2b34.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 3367089466cbad18401561074b3e1df485ad28a3.nq.gz
│   ├── 3389ce41f9b292ba0b31151e81a5198eea06cc58.nq.gz
│   ├── 3517565baa38665a3ac7e9049f45adbde626c088.nq.gz
│   ├── 4118394e27884b13a3412c655514252bc9bd3e81.nq.gz
│   ├── 4737a07ab895130cf58027beb0842baf1e6c9743.nq.gz
│   ├── 4fb3be7b28e30dd3e3e7d53e636b86ecc40099e1.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 59522db15a1ae9cf1e136447e8af2c7dd567fb1c.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 65ab270fd839f722d2118c3d90d89c80bbe3bee1.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7cc94d01bf4873a233c23d2f8a4b027399c9559c.nq.gz
│   ├── 89e04a6fff4c1fab89fb48822ef18c6a44bcbd0e.nq.gz
│   ├── 8bb80af35a3af5a7ffd0a052bd990ed2eb574fa4.nq.gz
│   ├── 8e8cb8f13da016c7000969f4676dfa5b050e9f0d.nq.gz
│   ├── 8f5200bb596fe2e44a4aa7a172be2ffe5dd87b86.nq.gz
│   ├── 94a7cb39b32e03aaae9ca20266ce51154c0f13fa.nq.gz
│   ├── 9a8699fa77454ed3de2ae83915e60786d35e1c86.nq.gz
│   ├── a602bd3555307f5ae865bd54a9a13d5246844cb7.nq.gz
│   ├── abd509a972264874839f30ed641067cc3b2138f9.nq.gz
│   ├── aeec21cdb80d977e2380bf41fddba6dd4da07c17.nq.gz
│   ├── cb307cb4a33c66db785ad9d8aab242237c050367.nq.gz
│   ├── cb8c7f0d2272135e91f743b785113860980284e4.nq.gz
│   ├── d6b6df33283654f6566aea9a8fa1b10dacdf750f.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── ececf2d5541cd4c272b7f94a76172ba3aa5f6a80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c08f6b9bb5d40940d5d51c9f8723c8a3ffc95d02.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 49 files
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

[jaraco/librarypaste](https://github.com/jaraco/librarypaste)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
