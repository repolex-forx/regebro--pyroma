# Repolex Knowledge Graph of regebro/pyroma

RDF knowledge graph data for [regebro/pyroma](https://github.com/regebro/pyroma), parsed by [repolex](https://repolex.ai).

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
rlex download regebro/pyroma
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3062c977fab17aeb5fbf1af7251d97578be536af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3062c977fab17aeb5fbf1af7251d97578be536af
│           └── chunk-001.nq.gz
├── blob
│   ├── 062d70cf6203d9b4487a7d1ad060a0ca8899be7f.nq.gz
│   ├── 0b2120781ccbad141d41c5f14aeea4c0b92e39c9.nq.gz
│   ├── 13a4d59aa7072c9e496bbae76a0af6821d869068.nq.gz
│   ├── 174223f94e33f35958c631911a3fbd3edd3a651e.nq.gz
│   ├── 1fbf5cb235961479df29b2df3d824295956109db.nq.gz
│   ├── 213aebbdfd11945ce93a7be5891997a31127bf57.nq.gz
│   ├── 226c9e80b794e56c8a9ffb2bef288a2b02a52a1b.nq.gz
│   ├── 228996361b603ca840828f8bdb1957f902b210c0.nq.gz
│   ├── 258e908bd99cc7b8115d7446cc8a569120d2da09.nq.gz
│   ├── 29c2e0a6f4492fa9862da1abecdc7544b9080398.nq.gz
│   ├── 31e08bdab355cebdafe9a53f599f4b53ff61e49d.nq.gz
│   ├── 3326e731105b19e7078f4679f7ad44a440ec08e3.nq.gz
│   ├── 3826e896499469673592de6b61eae85d98552eb6.nq.gz
│   ├── 3cff04d745a7b5114d41b262770045d4b541714e.nq.gz
│   ├── 4d3d9242bd4fd451b9fb9a04ff907e131f5a382e.nq.gz
│   ├── 53009ccce8020d4db318d462751210e0d8c28c0a.nq.gz
│   ├── 55ec8d784c3cfc688c31cb32a4225e5f551937b8.nq.gz
│   ├── 576b33a120e4356e76e2ec02a8a0c138234e61af.nq.gz
│   ├── 5b7d60eb84b009f66a55564cee7d16c9e3f1e911.nq.gz
│   ├── 5ccc0ea36b545a93108ee0fed380bcefc5ec921e.nq.gz
│   ├── 5d4dfc59ec399cbe14ac8967935a879d1f8e95ec.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 62fb90a9a1af823763acc6f7cb3ec0797eb8b5b6.nq.gz
│   ├── 65650845e37c13270dc362ce0d351bfce006cf64.nq.gz
│   ├── 6ab09b61b075cff5e50f2c35b4c52aba711821b9.nq.gz
│   ├── 785a02dafb95823e9e84fbf7bbbb425cfa43266e.nq.gz
│   ├── 7ba48e5be4e97bbc6bb82841549d38721714c890.nq.gz
│   ├── 7d847776f969b93e8e25baaba0b59b27f705ac4d.nq.gz
│   ├── 7edd7aea3b2d7df0e83fb71a968b148e606b49bd.nq.gz
│   ├── 81954b68867556fa091e014d6ead64fb73c0029e.nq.gz
│   ├── 8f58b0e37946afee3da68e98a2629886d16ba936.nq.gz
│   ├── 976199186c2bb1a17b44f534b39c22cb1d54a702.nq.gz
│   ├── 9a023acf480b3134012e863edb0da054c2f1f846.nq.gz
│   ├── 9e70e61931da9e491e3659340252e1a676a01dd8.nq.gz
│   ├── a2cd79ff7ad3439b4474153399819f034cc7fbed.nq.gz
│   ├── a7e9a2a1454f88b94891c5ecc1b484393bafd7bb.nq.gz
│   ├── ab2ff5c54efbedc22374d60bc40c48c668442b94.nq.gz
│   ├── aec2b5c07f2b8e664051fea069d2f92f0d2aa51f.nq.gz
│   ├── af1469809dc0bd616b9e10a3a21a019c3f3d2cdb.nq.gz
│   ├── b024da80e9c1c8c800cc1b46e90c1e783cb446cc.nq.gz
│   ├── b0f076532a06d9d7b19e62dd4310fbf33a853ecf.nq.gz
│   ├── b54bcabbf4740d4970ee2537df4d2d02b423cd63.nq.gz
│   ├── b908cbe55cb344569d32de1dfc10ca7323828dc5.nq.gz
│   ├── ba098ae3944fdf1f1aaf43cbed1aa7bfbcfa9b51.nq.gz
│   ├── bf22d78e1eb2240a51c9107384b3c7ac828a8bbb.nq.gz
│   ├── c6a0d8a92822cf72c3c36a5abc20639165ef3387.nq.gz
│   ├── ca2be1020c4b5d179a046154b5b6d8781933fada.nq.gz
│   ├── d78eb42fcf89343abc20fc5c59e736a513c93a19.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── fa15823dd069c4beaecd31fec8b70ff4300a980f.nq.gz
│   └── fd4b83210420009fe6f891a09e778c9769219c00.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3062c977fab17aeb5fbf1af7251d97578be536af.nq.gz
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

[regebro/pyroma](https://github.com/regebro/pyroma)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
