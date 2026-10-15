# Repolex Knowledge Graph of pydata/numexpr

RDF knowledge graph data for [pydata/numexpr](https://github.com/pydata/numexpr), parsed by [repolex](https://repolex.ai).

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
rlex download pydata/numexpr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d7c975073be01045010a71206f6c85fff3416a35
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d7c975073be01045010a71206f6c85fff3416a35
│           └── chunk-001.nq.gz
├── blob
│   ├── 00864217ab915d1c808901fe2000756502c8113c.nq.gz
│   ├── 01c982668d6dfe5772a72028cb0a51bc64bc6c65.nq.gz
│   ├── 02a02a1f5fb4e20b3e255016f0bbceb7fcf83f0f.nq.gz
│   ├── 079a17f051f2f25782c41c7757d6dfca94e39b69.nq.gz
│   ├── 0be0bf763f5ce1772241d3608b9be91d90062ddc.nq.gz
│   ├── 1b7d730276fe93dcb4e0d6fabc0293decd5bbc96.nq.gz
│   ├── 1c0de0b9955ca51c37255bc4811821acba2eadd4.nq.gz
│   ├── 1e81a02599f443664287237ba54ddd4d00f20810.nq.gz
│   ├── 26f784ef82613d5a52dde656f500c3b1034aa230.nq.gz
│   ├── 28d978cdb294c9f0259d0610ab506fba2ba602c4.nq.gz
│   ├── 31ca2fc7035df20efa92a0726474da4fea1e651e.nq.gz
│   ├── 3334d599404e853346b0fe5f5d57878fb0cc7494.nq.gz
│   ├── 3803a410de621405860343d20bf36f02c2d8e0ee.nq.gz
│   ├── 3aceea6e3f25cd3c7a38bd8897158007c68f09b3.nq.gz
│   ├── 3eb12b1daeed02e1284f9397c77b15f06cf5d4c3.nq.gz
│   ├── 3ec09bb701631b6a23803b0f613ea1e0e62f2a97.nq.gz
│   ├── 4491162db01be7ffa09080f66821b7694f28f5f9.nq.gz
│   ├── 497c6fecbc7edae9de0f849da69e7416b984397d.nq.gz
│   ├── 4b5075247aac697a1cd67f1139a6899e0ecd0f5d.nq.gz
│   ├── 4ec8d9fcf6002bd38939c8e89cfd728c660514e5.nq.gz
│   ├── 4fec1708cf911c8015ba4aca61ab83daf12e7893.nq.gz
│   ├── 51d32125e9f2f3ffa4e3ee815df473535b74ff1d.nq.gz
│   ├── 57dd4d2ea7a1df0a629c00df7467674fb73b70a0.nq.gz
│   ├── 5b1c46f59bf6860a6e201a15435101d117ebd56b.nq.gz
│   ├── 5d1bb0f454fcb73cf9e4641adcdf459dd783d6b0.nq.gz
│   ├── 5df0c358d6533930de2bd9ce321be4d2707e735c.nq.gz
│   ├── 5fdeebb948d59f106f2f3da2585fe3315e866a46.nq.gz
│   ├── 60cf6c50724b7ab2a78c18279bcebc7467e78f0f.nq.gz
│   ├── 611bddbcfcfe3fb32b317cc49aa8304da85a5396.nq.gz
│   ├── 63bb9e98cd47f6174897853fff3bb16262b4c75a.nq.gz
│   ├── 64d9f2003d3cd11e3d03e37813befd267d71bf98.nq.gz
│   ├── 6631f8dd5e454be2391547ab316611d4e65a9bae.nq.gz
│   ├── 67629bd3b18b94aa3603d0eda4ed2d18a40f5dc1.nq.gz
│   ├── 6d38d999116e39b0541f23f3fff057485d2982c3.nq.gz
│   ├── 797e64765fd224f363eb21feb3a152602c533432.nq.gz
│   ├── 7ae0f54d70f3e5fd7967bd892863c25d91e56e60.nq.gz
│   ├── 7b9b53cab4853ccce0fb7d75e22269919138fda5.nq.gz
│   ├── 7bf6f989a60dc7c98d0be349271a62932eb866b0.nq.gz
│   ├── 83a66b98dc72ea96ed5ce7c4f0b8677db329731f.nq.gz
│   ├── 85a2b3846574a37fd34c4c1ae40b8be5afa0374c.nq.gz
│   ├── 896aba018885f5180c85fa18ae0da324dbb30618.nq.gz
│   ├── 897a4ca460c42deb198a803f1517116c876280fd.nq.gz
│   ├── 8e4d722fc7b711f9877032a2acb4a782856004a8.nq.gz
│   ├── 9c706107736ac59b57dd1dea65a88c92365ecb37.nq.gz
│   ├── 9e45fbe79189f69dfc32b8372204ce4f7497c850.nq.gz
│   ├── a48fbe24ae01b4c9eac09ae982f4d41dc7eb856e.nq.gz
│   ├── a4c58ebff7a8a3bb4214d2963f27c220f5127f07.nq.gz
│   ├── af04286dc9f0e5ddc4c45d8b2b04dabd933006e0.nq.gz
│   ├── b599642caaaa8214dc7a87901c0aa262e7e3d14a.nq.gz
│   ├── b653c7a4d8daf6957b5e7a32bd904a6b5da922d7.nq.gz
│   ├── b6e2f9c1911810eba5f9582807f24336bae2661e.nq.gz
│   ├── bb4d7dd9dbf70968683caa44747ce17079d94e86.nq.gz
│   ├── bcbcb877fdb4bff9b3f100c4330d0f56c31fc5e7.nq.gz
│   ├── c015bbf98588aa8b6a6c0313f99eeff72aa3c6d6.nq.gz
│   ├── c12569de9fc84334d32b68043fc434aa7a0dec45.nq.gz
│   ├── c66267ab484b8db6841bf436655448edf260c354.nq.gz
│   ├── cab0247c4a85b2df6979816dac2af58d373740f9.nq.gz
│   ├── cd00e783015f14e4adea2a459000aedcab0a4ccb.nq.gz
│   ├── cd5bb440d7956ce6dc8fd0f19a5bf54f133d4900.nq.gz
│   ├── d47f1fdd7244ff8fb3601c53da3026967bfd0529.nq.gz
│   ├── d517391a8b0e834b0ba95090bed6fea0457318e6.nq.gz
│   ├── de9a582603ca6aa895136e2b118443e9397897da.nq.gz
│   ├── df7419cbc16d78a9b17c3778a85318146851fa5d.nq.gz
│   ├── e0ff8a284f5b9580afa87eed3126fe6138036d79.nq.gz
│   ├── e8bca81a88ab0d7d166fbd16eda8ef162404f045.nq.gz
│   ├── ea8b30f6cedbf153dfcb49794c969183722109c1.nq.gz
│   ├── eb4819b198ef7cde1765d94ca333c5ec753077d6.nq.gz
│   ├── ed7f410a14e4fe163d687c31251db7a78d1b0081.nq.gz
│   ├── ee49c2a2ba53e4180caa0f15997709dd84330d94.nq.gz
│   ├── eeccd0bc1b99d896a593adb6e38970145f452be3.nq.gz
│   ├── f37772147afb5c3b5f2a5099e5105e58d60116e8.nq.gz
│   ├── f47c8cc2ffe59097ea336e25692c25680c1c9004.nq.gz
│   ├── fc38fb87cb5bcf51e5fcd28392f4fe36b37d0182.nq.gz
│   └── fff41047f44842bfaeb8840490c740b83fe6ce5d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d7c975073be01045010a71206f6c85fff3416a35.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[pydata/numexpr](https://github.com/pydata/numexpr)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
