# Repolex Knowledge Graph of facebookresearch/segment-anything

RDF knowledge graph data for [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/segment-anything
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dca509fe793f601edb92606367a655c15ac00fdf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dca509fe793f601edb92606367a655c15ac00fdf
│           └── chunk-001.nq.gz
├── blob
│   ├── 064a2ba5ff820c6b2328f51f0ae6b147ec698881.nq.gz
│   ├── 08b500a221857ec3f451338e80b4a9ab1173a1af.nq.gz
│   ├── 098f6686f063bf6c631df4f5f3b5921d48ed2d2a.nq.gz
│   ├── 0c1d6dac9ef9fce429d99317055e0b24fdde2072.nq.gz
│   ├── 0eee130ba71d14ec260d33a8ebd96a6491079a54.nq.gz
│   ├── 25b59894f509e315610f675d050b62945570daf6.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 263991c9496cf29ed4b99e03a9fb9a38e6bfaf86.nq.gz
│   ├── 26d6454d626bfd71b386ca1ba032836ea12f8a35.nq.gz
│   ├── 28fafea52288603fea275f3a100790471825c34a.nq.gz
│   ├── 29360eb40414747e5e6c6cb1e72f9bd3f6098863.nq.gz
│   ├── 2bf15236a3eb24d8526073bc4fa2b274cccb3f96.nq.gz
│   ├── 2c0986317eb576a14ec774205c88fdee3cc6c0b3.nq.gz
│   ├── 2e006c95b407ff4a7c0c071badf6a9cf2fe34ef0.nq.gz
│   ├── 2e58656beedd2d48ea7df680e27646d906f408de.nq.gz
│   ├── 3196bdf4b782e6eeb3da4ad66ef3c7b1741535fe.nq.gz
│   ├── 31afbe5c63f8269e10c1ae56a17e9b0c085713ec.nq.gz
│   ├── 34383d83f5e76bc801f31b20e5651e383be348b6.nq.gz
│   ├── 37cd245124079e7cdd0d047ef9dde077db99efcc.nq.gz
│   ├── 38e906243d898d7fc071c0fe218338c5cace3ea1.nq.gz
│   ├── 41f1ddd8073590bce6db3b0f2d2b2b803b09d3f5.nq.gz
│   ├── 503c0f2ec12dd5f911838eb7e8ad7dd241ad1c7c.nq.gz
│   ├── 5277f46157403e47fd830fc519144b97ef69d4ae.nq.gz
│   ├── 53250487668abfd94308bf4c6152455ba46877fd.nq.gz
│   ├── 56755a325e704b56fc376accd4c1d103bf96e411.nq.gz
│   ├── 59b80d06d6779c4681b9a89fec14d22c0c53872b.nq.gz
│   ├── 5c6f8389ea96fc871e4a0ff36a30fa7b9fcf4c90.nq.gz
│   ├── 5d2fdb03d535a91fa725d1ec4e92a7a1f217dfe0.nq.gz
│   ├── 5f365d826723ab12df839d89aec6f0170242aa72.nq.gz
│   ├── 66351d9d7c589be693f4b3485901d3bdfed54d4a.nq.gz
│   ├── 6b0759587aa5756e66a13ef034c6bcdd76a885f5.nq.gz
│   ├── 6b98688c3c84981200c06259b8d54820ebf85660.nq.gz
│   ├── 709c77e28d2f3fbe457742dcfd2dccf28923e4a5.nq.gz
│   ├── 714dfc91cb980e00a48b658bd4f1a173c803a26b.nq.gz
│   ├── 7e9f6494a6deffa67bea5e6d01bdba07d8553116.nq.gz
│   ├── 8074cff6b40addc6b66f7ab4962218eef20da13c.nq.gz
│   ├── 815ceaac472a18915b33e78c70231b88e5dd2eee.nq.gz
│   ├── 85f791c45610e5a3c230fddb1e712dbc602f79d0.nq.gz
│   ├── 8a6e6d816955b4c6097e1de6ce6e4ed3bafe327c.nq.gz
│   ├── 8fb19cb8a1a68d2b53948ca4d27658d06a5e977c.nq.gz
│   ├── 9ceef18bf750efe3cb68cedf55cfadc4c0b389ee.nq.gz
│   ├── a26069fca517023805beddf94968dfd55a9ced3d.nq.gz
│   ├── a426553564b0652ba26ef39484ec67121809e939.nq.gz
│   ├── b598f486b642bda9df05d0fa51b0ba7eaf3a8974.nq.gz
│   ├── b5c61c956711f981a41e95f7fcf0038436cfbb22.nq.gz
│   ├── ba24e42d793346047f258bf5c3cfe9d1653c6d9b.nq.gz
│   ├── be064071ef399fea96c673ad173689656c23534a.nq.gz
│   ├── c08ba1e3db751f3a5483a003be38c69c2cf2df85.nq.gz
│   ├── c1de897c0b245acdfeb4bd89caa50e9bff569567.nq.gz
│   ├── c3143f4f8e02ddd7ca8587b40ff5d47c3a6b7ef3.nq.gz
│   ├── c363be6afed0ea17e0f9fabf6ec67b3cf168be7a.nq.gz
│   ├── ca49c35711cd391d9d539007fafc9efbf94cacad.nq.gz
│   ├── d5a8c969207f119feff7087f94e044403acdff00.nq.gz
│   ├── deeafdbc1d4ac40426f75ee7395ecd82025d6e95.nq.gz
│   ├── df2e17436d30e89ff1728109301599f425f1ad6b.nq.gz
│   ├── e92b38b8fe466d9592f9eaff10de94803b320154.nq.gz
│   ├── f2dbf676ae6db3d4aa4a6f0ff5185fd60b6505f5.nq.gz
│   └── f2f521623ed824abeaf3877bd23951bbcf9475bb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dca509fe793f601edb92606367a655c15ac00fdf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
