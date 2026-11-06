# Repolex Knowledge Graph of zopefoundation/zope.traversing

RDF knowledge graph data for [zopefoundation/zope.traversing](https://github.com/zopefoundation/zope.traversing), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.traversing
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eea8b7a65166f2e3912185a00545683dc7e8fb13
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eea8b7a65166f2e3912185a00545683dc7e8fb13
│           └── chunk-001.nq.gz
├── blob
│   ├── 03962c34911e5f1daa0ade20ec3de3c447db3c1d.nq.gz
│   ├── 0e3d3b04a2fb0b5284475837aa437443d5d89dfe.nq.gz
│   ├── 0ebcb51aabd33bc803fdcca038878b02ebb1e6fd.nq.gz
│   ├── 104070094b8ea59cf0c27a882afd0fb1f4e9ce44.nq.gz
│   ├── 13039540f2bf99b0299b1eefd5f3c2ae2610d9b4.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 197d0fe57527819ac89e528a16b3a06c4dc94bbc.nq.gz
│   ├── 2deae8fe53bb04347e725f3568a3de61df6a64de.nq.gz
│   ├── 343db3f7bc51750fc043fdd29d0494e98ca21e44.nq.gz
│   ├── 3540b18b477c71946dfe15d0246b83484ebc59f3.nq.gz
│   ├── 419f7c5efb203121b598e9065012b14d1904a332.nq.gz
│   ├── 437e2de100f578db9f9b37a5685e017d37e90a2b.nq.gz
│   ├── 4ae5a08869c21499659efdef17824c70fa0714da.nq.gz
│   ├── 5c61f94bb10040d443eea96fa0e61ec16befcd1e.nq.gz
│   ├── 6069a68501e68e29c39097d6b0754923bdcab1a9.nq.gz
│   ├── 631fe162df53678aeacf39373571a735b5594f63.nq.gz
│   ├── 67fdd2bdf0740d0c1a4267aeb62bee919ecdbf03.nq.gz
│   ├── 6918f7ed2400093c5b3f27f2ea97a8aa6aa92f95.nq.gz
│   ├── 697de06caf1288a094da1f48bee999603180aa6a.nq.gz
│   ├── 6deec595258a73d473287855a5625117bcafd318.nq.gz
│   ├── 6e7d2481e2c3ada73135e87396488f8851f7b13e.nq.gz
│   ├── 7501c80f506cf6b3960362ecc6e61c2cf846fb7f.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 89ad7865c29e02830c68117348acf070c0b91300.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 91b8d7ba1aadc150bcc9aba6553fc59f01643aa5.nq.gz
│   ├── 9354cf40df3cb69920b4941a336e62ef01438371.nq.gz
│   ├── 966298d0566888066cd016f76b272997faab422b.nq.gz
│   ├── a32594a7c2946f82a9d7a7855012fffebff09296.nq.gz
│   ├── adbc0a7fc66346de81c4ee64e91700b9ff2fdfa4.nq.gz
│   ├── b4974a55681a3e7d8cc0c433cb25efca115191ce.nq.gz
│   ├── b631a4bfe931539531777affa6f1577e8918bd32.nq.gz
│   ├── b64f635bf6c95644d7fd31ee8a958b3ff8828f28.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── b8fa18964ed9c90cda361f45cbc4f9c7914ffd18.nq.gz
│   ├── bff22b8b98f61d34e0c1292510697640e00fb972.nq.gz
│   ├── c0492910d3dcdf685cf69df561a0b21c607f714b.nq.gz
│   ├── c7bfce8be470fb1f503aff3220c82e7a8f95594e.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── d2d502902f40dcf5281e2fdefbcd2548f95f1c06.nq.gz
│   ├── d4240a5945a8d009642fb36c66caaa36acb59270.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── d9e6edcb646504a0d885a92ca698c093c9caabe4.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── eef059c9f57f43ecdc947fb061f70625b1974b20.nq.gz
│   ├── f61a37f604e42a4daa42f741b6a5b22344089dda.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8e844d1a6e40888f31eb34d19d7f04df1521199.nq.gz
│   ├── fa11839a76510d1637a3765a4d29ea4abe15b088.nq.gz
│   ├── fc3bdaa3b6c2432102a1433829f9f8c4ec8b5156.nq.gz
│   └── fe8ec1c47415960276b5e445c4ba03050720349c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eea8b7a65166f2e3912185a00545683dc7e8fb13.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[zopefoundation/zope.traversing](https://github.com/zopefoundation/zope.traversing)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
