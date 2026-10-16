# Repolex Knowledge Graph of pysal/mapclassify

RDF knowledge graph data for [pysal/mapclassify](https://github.com/pysal/mapclassify), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/mapclassify
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8df1564808e475f2a48db7f9ab8275400dcc627a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8df1564808e475f2a48db7f9ab8275400dcc627a
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a194690f5605bdb61ce127a0131e9ea1eceef4.nq.gz
│   ├── 05e9fb75cb8ebed512265dd565eb5cc79607e12b.nq.gz
│   ├── 06e10206c323c165d7b1a5df851a57cf2d68c553.nq.gz
│   ├── 0c09717690f466c24f124d1b3244633531007942.nq.gz
│   ├── 0f23047715ea8d27d47cebefb7a5b9f3bcb8bff0.nq.gz
│   ├── 12cfeb7855bec685490824c669bdfc25586f2738.nq.gz
│   ├── 17bdf630daad5f3f49deeac00a5633792efe1a94.nq.gz
│   ├── 18b9b96d1ed5132b95f7667fc0544b0ddbe0ec35.nq.gz
│   ├── 1a3930d2f8f639841a24501a3cfa9ea1834d150c.nq.gz
│   ├── 2000dd43857ce6530ec261008f3b6d06e3889e8c.nq.gz
│   ├── 218e23d19a1c548fcbc7c3226b40883506e0a23b.nq.gz
│   ├── 2b033c4c9412be8e5e0eb3615a6ca994f16a987c.nq.gz
│   ├── 2c2239cec45497285b2689a19789bb5baba98278.nq.gz
│   ├── 2c7c39fe384726b1d7fa3b3c2a13ded8958bd183.nq.gz
│   ├── 2e29a540519d9c8323e38d0972cfbc13e4ae551f.nq.gz
│   ├── 2f195f784ea5da1ca90ad01c29e47000c8e447cf.nq.gz
│   ├── 2f1b5306018476930d601cac0fbb54091c2411e6.nq.gz
│   ├── 30dc03b3e3fc30b626c830c0a6aef39f390ce410.nq.gz
│   ├── 36ac447044eb265d15afdd565cb02d96642ec044.nq.gz
│   ├── 3c0328537557758b9d5cb110cd0b81ef051392fd.nq.gz
│   ├── 5011e3b0e6a4ef4de4953e0d087199edc60d6671.nq.gz
│   ├── 516c646ad25f087e63035dcb334f89fe59c95c7b.nq.gz
│   ├── 5303d9f06ef8bf4422fcf85b6eb4335eb6015077.nq.gz
│   ├── 5350819754538f69ed7baac8c558af55786e7ece.nq.gz
│   ├── 574ee2df58ee70d76cb496e5adeef8c1bf92cc79.nq.gz
│   ├── 57fa59b44b47c23808ffaca4ac3d3bd78312eaf4.nq.gz
│   ├── 5891a16a14cf208cfe5d49339dccc9663cb27317.nq.gz
│   ├── 58a16c228d9b61d1de39770ad2549fddf0497d55.nq.gz
│   ├── 5d86a23740099176093b15c9d2a5b7d16dfa7e45.nq.gz
│   ├── 65c9ca3ffcb080c4f88dd5120ff4b8ca6bf4b562.nq.gz
│   ├── 67ace4669c7956d1d9c830e9cca418ca5a232f88.nq.gz
│   ├── 6989df98004c431909fcf92c1cfda0662b64178e.nq.gz
│   ├── 69d758e22072e39a2e0fea9e835858199f1d97a2.nq.gz
│   ├── 6e4b8d49c0dbd1dd21aaabc8f93288b1e680f59c.nq.gz
│   ├── 7233d83fe184e1326fb5c483abc903298659b3f0.nq.gz
│   ├── 76c0e9c694ab3e73bbd6311abe0fac31cb717ec2.nq.gz
│   ├── 786bc27a82bcdd4da6a17ec241dfaaa0af39f229.nq.gz
│   ├── 7c2d8609ab8da35a22190151659e5bdc809639e3.nq.gz
│   ├── 7edca1563601549d6614801250bcd68b6afcfd20.nq.gz
│   ├── 87909ad9f17dfa16724350fb34530c9ecd165176.nq.gz
│   ├── 8895e556c0d5c83447b0cd1d553b8082cebecac1.nq.gz
│   ├── 89d32b53d30f26e174d9d733b85c96b2c650f7cb.nq.gz
│   ├── 8b29d6fff367b80fb8afa3a6ac2d0d242c7e099d.nq.gz
│   ├── 8f7caca718bbd4752ce4e5bc524a202bb25e7499.nq.gz
│   ├── 92311dd1f01d6146c4967c1d1a7be55115cfb27d.nq.gz
│   ├── 935c52108e0aa2847bd2a6304a58e210b0bf6784.nq.gz
│   ├── 946a22acb318920c0a68545d85b13c3d09d384db.nq.gz
│   ├── 979d0c6438963bd36d0cbfb421acc338c5f40cd2.nq.gz
│   ├── 9c7ba9db6a02266110c037c9ef37905a6c382515.nq.gz
│   ├── 9d193aa6145b1a480fc769521e7f16a4dbb09af0.nq.gz
│   ├── 9e00c72d27d189fc504219219d700b231225343d.nq.gz
│   ├── 9f73473df69bd38ce7ab1c56bc1440d87bad7fde.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a1b70eff059e9ccc786f19cf99f25087c01b219a.nq.gz
│   ├── a218a62e2d2c19f8e5db7f63686517e4a3808cd9.nq.gz
│   ├── a9d6c63d5995f24c51f453867ea3701b86e0db23.nq.gz
│   ├── abcfbfb272fc0ee0dabf47ca1e3e8939081be32c.nq.gz
│   ├── af2a982d78e32b951d31229942b8107af06c7b23.nq.gz
│   ├── af2ef608cbee665acfb234ce8dc9328fc364fd6e.nq.gz
│   ├── b1dc60d1df693a358375da38ecee15bbe118adbd.nq.gz
│   ├── b24e530d3a1772f9dcb9d50e3fb8306bf5dcc8b5.nq.gz
│   ├── b28385a4513ed5cb34fe21aaa477ae45d71c3492.nq.gz
│   ├── b2c3ba314b6489f69f9f6311a0a54b4146d0193a.nq.gz
│   ├── bb46a70a2a2aab2f3373b01e8866bd105b6189b7.nq.gz
│   ├── bbfd44febb7c4ece59ef3936794994d83153e665.nq.gz
│   ├── bc1c24c72364b44e4ef840cf96ea0acb752f225f.nq.gz
│   ├── bccc1e2a8af14a07ac48762daf2157bcfebd3d76.nq.gz
│   ├── bce049ca3d3834592e57bd2d7f60563382c1c431.nq.gz
│   ├── c1c77b0f0cccb34e2dcab5f1e603cc14f3f71307.nq.gz
│   ├── c6b11441804f46663ff6d4832039a6b5073e6320.nq.gz
│   ├── ccce72ab05824067ed334375100035805863f8ec.nq.gz
│   ├── cebc006c097ff41d18f60fe3c52357a24d72e5b2.nq.gz
│   ├── d0e50b4aab4631d453a2b30d767d77f652f9b8d5.nq.gz
│   ├── d1bcf9578c0a615cad2755e798b5f5c527bb303d.nq.gz
│   ├── d55231a0ced94088bc5b32eeac4e8695c84530eb.nq.gz
│   ├── d976551f796103df135e73479a1d8beef1806f94.nq.gz
│   ├── dd107396b070b63768173d80b2c01a241c7fe116.nq.gz
│   ├── de828d78a398ddd67bafe21b4e066f2d2e5ec4d6.nq.gz
│   ├── ded1666393ecafbe3564f1d44080617c9d58ebd0.nq.gz
│   ├── df22d8bbb449db1bdd1d71514400815f868a315c.nq.gz
│   ├── e046b1b6c4ae97d42746828e5c4c19cf719296d9.nq.gz
│   ├── e21225f88f2e2e1aa488c32aff8b10a715ad4858.nq.gz
│   ├── e24af8c774e12a97143ccbc97fcb5061eead44cf.nq.gz
│   ├── e4c056e4b589bed4404145e15a28993456e3dbbb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea69e7c9b5e6e58862ae39a3d1e208f8f3aebb7c.nq.gz
│   ├── ecccd7c8c3ab9600a8783a0af2ecf676b01dd035.nq.gz
│   ├── f1e906e1ca677148fe3338ca4c08d43cc12845df.nq.gz
│   ├── f62f4c75315f7a24c5bc8e39878b3f2aa4c9449c.nq.gz
│   └── f870ef9aab8b30c5862558c8aaa73fd215931db2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8df1564808e475f2a48db7f9ab8275400dcc627a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[pysal/mapclassify](https://github.com/pysal/mapclassify)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
