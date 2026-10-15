# Repolex Knowledge Graph of sphinx-contrib/sphinxcontrib-towncrier

RDF knowledge graph data for [sphinx-contrib/sphinxcontrib-towncrier](https://github.com/sphinx-contrib/sphinxcontrib-towncrier), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/sphinxcontrib-towncrier
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7b6ebdf880c41be8bb0ff0a23c4fca2a7f4b8926
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7b6ebdf880c41be8bb0ff0a23c4fca2a7f4b8926
│           └── chunk-001.nq.gz
├── blob
│   ├── 02eecca09dab1f9c03a8071a9f09b09f50eba807.nq.gz
│   ├── 038156ec0d9e07d120184979fa4927fc72f6a927.nq.gz
│   ├── 04390f45163c4d0524feb2b2cfb69f37532e7827.nq.gz
│   ├── 053148f848642cb6c79ecb61968f0a9d3fea8bb4.nq.gz
│   ├── 0e249fc1472b0c00b937833518f77a855e69ac39.nq.gz
│   ├── 180ca775c74c79f6228aeceeb0bbb3563d42cbc7.nq.gz
│   ├── 1a68fb84e7a778f499c81b0d9c5071d6698bd263.nq.gz
│   ├── 1f1821b24f9e3117661682b830e540f5eb74c2ae.nq.gz
│   ├── 273f9061a2339e07fe4934db3a756aaed6fd7789.nq.gz
│   ├── 298d8411ef928701a057fa3fc5d781de2fbfb04a.nq.gz
│   ├── 2a250ba489345935cd780af99784ab116bc43d7d.nq.gz
│   ├── 2b62571b0ccd4aae0613d721b8913134cd67b148.nq.gz
│   ├── 2f58646f553896b09fa818683974953829683816.nq.gz
│   ├── 309e8bf3f458438b51d0ab03ade12b8e2198b4b3.nq.gz
│   ├── 32e88ac95b5746802028eed3e0e3de3fb4e91149.nq.gz
│   ├── 34094b039d032eb836f74700e8e3d19aae0223e1.nq.gz
│   ├── 35b726a444945be2ea7f824a7ab36a53e617bee1.nq.gz
│   ├── 36a13f8a2653f74ce8441145b5529852a6aa8313.nq.gz
│   ├── 38cc2638672e1f6ca56e4d5ceaf16451dd702b67.nq.gz
│   ├── 3a9efc0a3becf98d2abf837d20de309c6da66b63.nq.gz
│   ├── 3e1e5f01a09520c798a40e09ba74db0f5379786b.nq.gz
│   ├── 3ff5fd3723b144507f69b35e457efc87c5603653.nq.gz
│   ├── 46b574de0a9d25555dc0cd15b562d450b6595b5f.nq.gz
│   ├── 47de6a3432d7e8e8f4a5aa6c053e03d9479545b0.nq.gz
│   ├── 50bae8ca850f2cb7adc56c23be4e5291a7634ceb.nq.gz
│   ├── 54f69b69bf816c7244a567376c6ad024d60155b0.nq.gz
│   ├── 5b6f57cf621ccb0c9a972c4fafc25b5bd500de93.nq.gz
│   ├── 5b91122b473278b51cd9532d4c1cfcbc0a2d81fb.nq.gz
│   ├── 60f1867e6a2e59f883d46df0c8d49a6a862b03dc.nq.gz
│   ├── 6364b131697b6f38565745e15fc370b7efd5b4ea.nq.gz
│   ├── 65d6f3110f2def9f06bf3b22b23e32256f59407c.nq.gz
│   ├── 6628ba645ebcb95fa7ac19d95e7ab217d6292dd7.nq.gz
│   ├── 674d7b907efe86dafcd2b8ddc5655fc55ddf5395.nq.gz
│   ├── 6acb3b415aa0ee5568c3c30ff1e447d21c53b6a5.nq.gz
│   ├── 6f7a4f76e63fff5847b71ef2107bd273531838d8.nq.gz
│   ├── 80c79fdef414f24abb6f67bb245170b3507b1fe4.nq.gz
│   ├── 82cb77f057c170d7ad1dabad8f112596859f0198.nq.gz
│   ├── 83cae4515c3bfb7f7b706e027ddba67f9479f17f.nq.gz
│   ├── 86721b5dbd89569a40eeb6969aab3bc5aadc5f54.nq.gz
│   ├── 8ad35b0c65509180f1f9b5bb6d0862e958bc59b7.nq.gz
│   ├── 92fd32f8f31b0c8b37203dd9097cea8891dec1b3.nq.gz
│   ├── 961de829c1e9622adbf93cfdb5a092b5a021a14a.nq.gz
│   ├── 9d8403cf2b5b21c7892156b5352fc3700cfa1380.nq.gz
│   ├── 9e8fe43e9a08b9414bdf4193d904e4aaae9afdd8.nq.gz
│   ├── a3490e91f94d19aeb05943fc395ed67c4351441a.nq.gz
│   ├── a538bc300f4478a6e7c4d471abeeb86fc2728232.nq.gz
│   ├── a91bae5cc25f57f88ab0b8c18792f71fc26846a5.nq.gz
│   ├── b482403b64589ab4d9befc66ab1b6edd2d5c2947.nq.gz
│   ├── b6e140e083b3ceb39aeb92eca5aef91872f83df5.nq.gz
│   ├── c197c23f6fae96465763eed3b235a5874e3c43fd.nq.gz
│   ├── ca20fdf82516df7a64f7052738ee67ecb5455b43.nq.gz
│   ├── cec9082b6d68f3fdd70f2fef2818bf74ec6ef362.nq.gz
│   ├── cf719ce94253886678cc9d46360a9580452a56b8.nq.gz
│   ├── dc2baeb26fb68061863cbdb5c053dafebda7d8cf.nq.gz
│   ├── deb2e36a3079a3e90aeca22987589fdd493ed288.nq.gz
│   ├── e0ed8e46801b3bed806dc8f1666f4b60e44cd2e8.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── f073a8db31f9f9ee2c34559b164a364cb6de3704.nq.gz
│   └── f570c25ad07aabce4011f1768b6fd82f122a175c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7b6ebdf880c41be8bb0ff0a23c4fca2a7f4b8926.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[sphinx-contrib/sphinxcontrib-towncrier](https://github.com/sphinx-contrib/sphinxcontrib-towncrier)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
