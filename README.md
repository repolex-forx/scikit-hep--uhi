# Repolex Knowledge Graph of scikit-hep/uhi

RDF knowledge graph data for [scikit-hep/uhi](https://github.com/scikit-hep/uhi), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/uhi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2925a6d0ff4a3ea8525d9f6bd1477d71bc667c33
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2925a6d0ff4a3ea8525d9f6bd1477d71bc667c33
│           └── chunk-001.nq.gz
├── blob
│   ├── 004c5ff058761fc8b5e353b1320eaae94c49ec84.nq.gz
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 00d7fabb11d15fdbc50bfdb6aa3b84c26e9def48.nq.gz
│   ├── 0157f6b7eef9cdd0c51f3bb92a84a6e5eefa5eb0.nq.gz
│   ├── 02a883973dfeb367340ee7f5314458f3ac7b8f13.nq.gz
│   ├── 034ff9cabcf1177e214ac148852c38328cf3b9f4.nq.gz
│   ├── 039d4f8450710a03c181837fb3f97c9e685d85ac.nq.gz
│   ├── 0718c2aed9eed9160ff8f66c75f4455bde5cf24e.nq.gz
│   ├── 076926437e02735281c4b8c58ac7a3198094552c.nq.gz
│   ├── 0b2440b6767cd26db9001be34df2cfd537d52559.nq.gz
│   ├── 1188982242ec4d32104c14171c17aa29494be872.nq.gz
│   ├── 11e5e48d6c9f06e9768ca41cc361f39b17d48613.nq.gz
│   ├── 12c34ae24fc95dcedd93adf90d460b8310f36650.nq.gz
│   ├── 15a9fa33965cbd0603315f1c0d5949593fcaa9c8.nq.gz
│   ├── 15b6b6d959b833b96bba3154d41830aa911b9d7f.nq.gz
│   ├── 160a2e7f1c94f461677da81cc2a08146e170568c.nq.gz
│   ├── 1652cdfc367ab48e46240e9c29a82bc798bd8a09.nq.gz
│   ├── 18d98da824431c15cd3129e7cb20f41ce9d55777.nq.gz
│   ├── 1a8ae4a9c9ec5a589dc76d15f1902e3d71141e78.nq.gz
│   ├── 1ab4935c06ac53423a1dcc379f16ef29d59ae307.nq.gz
│   ├── 1b393c0707e87dc10169a5f436a0d9c095d3ef94.nq.gz
│   ├── 1fa25ecdeb4b4dbe4e5ff73c2bd3f45ff42a99c8.nq.gz
│   ├── 1faa16aa765bb7ffaa6011047f637786f0c1612b.nq.gz
│   ├── 20a0555fdd019ff86d66595df31bdf6ed3638890.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2941b6e42bddd508f4c4a87d0fa39f2e4f384891.nq.gz
│   ├── 2af976de4bccfd5ffac417a322f5a54c4a320d87.nq.gz
│   ├── 2ff55c9bae624540856ee82c78b775b90752d84d.nq.gz
│   ├── 30f1126586ae5ca685cbd28abbc9550600491fed.nq.gz
│   ├── 31e01855b150ff2f69514409d1f1ed5a28c04bc0.nq.gz
│   ├── 361c0041a889d83cf8c3bfbe16a9078610ca543a.nq.gz
│   ├── 366f73c9ca124d557454158ee2d26dba772be0a2.nq.gz
│   ├── 36a634b008876b1e1cfd899f31c3999df15572db.nq.gz
│   ├── 373025958e2d1b679d473b314b7dfd883fdcf9b7.nq.gz
│   ├── 3c11d1e1be4c8ce32d1a12bd4c130d64e994057f.nq.gz
│   ├── 3c3cb05ec0dddcc3839a8d930ed52f6b03426e44.nq.gz
│   ├── 3d3226343cdd45fec4fc899ce2a641a29cdc40c5.nq.gz
│   ├── 3f5088c46e76a45885cca604b055c0dbc23e4542.nq.gz
│   ├── 40589999f5e4a139f7fb264856770a05aa962b15.nq.gz
│   ├── 411bbe5e216b00258f72d373b7a476af17f750de.nq.gz
│   ├── 43dc7a716bbe39ac0a79adec969c85e7daaa2b04.nq.gz
│   ├── 4487b5ffefb3f49af60e60483477b5bd161a8906.nq.gz
│   ├── 4782e9078a10529205d89291d0c87662333b631f.nq.gz
│   ├── 4a6847e7a6da26e0d50389f7ca2470ed89eedaf8.nq.gz
│   ├── 4f33229718c9e77fc21ee238e81a80d4590f9c14.nq.gz
│   ├── 5431563a7510a4e0350a8527b6368861b386e45b.nq.gz
│   ├── 5a53e0a87f2ad5e14ac2a2086bd9a314da71ba66.nq.gz
│   ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
│   ├── 5c97d37c0e59b5f514e011b598ae23a1bc5b2199.nq.gz
│   ├── 5c990b4ed4351afa35ac1e31151c738c0b6895cf.nq.gz
│   ├── 5cf0ed9044d32ab278235fa4e480ecc804c35015.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 66296a0d2abe1e5fb5c52712261f1bfefb571ca9.nq.gz
│   ├── 71e7b13e4f732423f125da717df0ca1febb91981.nq.gz
│   ├── 771221a9ad04e6081991c2c8268382e56038d8e9.nq.gz
│   ├── 7831800deedd5318514ac795384f6801c112ed45.nq.gz
│   ├── 78f4551c3dec1062cc316560e748095538b239e9.nq.gz
│   ├── 7a046dbaee56659ffbd4e08737961c500fc81241.nq.gz
│   ├── 7ebe456fc4ef9664fb38f62abe38b777c13f1814.nq.gz
│   ├── 7fe11df767d5dadfb9681772819beb6034f59bb7.nq.gz
│   ├── 80e11c06a61b3698e98bab905062e699707c3f34.nq.gz
│   ├── 842f002183a77cdc8b27df2e2cdbf79a36e0fc29.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 90b24096774b4c4d95d40bb901833bf28d7151e1.nq.gz
│   ├── 93164f1ef24838bd5002f5b653d6eeb9dd6ebf65.nq.gz
│   ├── 96b1391eb78f29e315b184aa76cac4b5534e5c2d.nq.gz
│   ├── 98f80eb577643250a3db93bc9dba14659040917e.nq.gz
│   ├── 9c9cfa34dbf95121b15b77d44af40a6281c8e574.nq.gz
│   ├── a493b9ab4041ad5d53bae61e5cd5a94ae4b4ad2f.nq.gz
│   ├── a737bd09327687bec34a7331a15b81425ce436fb.nq.gz
│   ├── ae0a1257f12a5c90bc96b328b8b5f93cef0036d5.nq.gz
│   ├── af56b054d0e2a4b458cc48afa7ed802edb09952c.nq.gz
│   ├── b033a26a26531686e838c54406587ba4cc8a2f62.nq.gz
│   ├── b432ba2c14ab2410d05e06fdef07ccab54b17f45.nq.gz
│   ├── b93dc7c5817bd05491118aee1ca91452a75ef7f1.nq.gz
│   ├── c2cbb04c2e125536d7c1a9a9126cfb253426c6b5.nq.gz
│   ├── c2f7449f237cd9443142374d17dfc0a31bf56177.nq.gz
│   ├── c7de260b92a81875630fe6e273157871eb3d8825.nq.gz
│   ├── cbb47c3a02395bb419b84a0ce13f77d8ec52d7ec.nq.gz
│   ├── d314ee857fec7f6f727f4d575bf8e9ba92cbccaa.nq.gz
│   ├── d3f6d57a588dd647231c1dc04a58a452f9d2cfe9.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d62b381baf6e95ed8478059824b81b8ebedaf2b4.nq.gz
│   ├── da1e245391f5a13590d63dafa15154b01a02151f.nq.gz
│   ├── da6ad60ade91f9c3c97ed1f266a3bf88a2ef0bc8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea58ef7f460fdabf93e651128b16c0cbddb0568b.nq.gz
│   ├── ed7a3aa3e6d2f63d4d72ad4628aa783d9091011b.nq.gz
│   ├── f3a6d3f1357075588e3c3882e8a607c83fd82a14.nq.gz
│   └── faf2a8bc9ea31aaba61741011479fc0e4991a551.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2925a6d0ff4a3ea8525d9f6bd1477d71bc667c33.nq.gz
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

[scikit-hep/uhi](https://github.com/scikit-hep/uhi)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
