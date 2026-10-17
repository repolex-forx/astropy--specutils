# Repolex Knowledge Graph of astropy/specutils

RDF knowledge graph data for [astropy/specutils](https://github.com/astropy/specutils), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/specutils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22ba8446b620cb7d9ab076b1c1204feb481d5da5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22ba8446b620cb7d9ab076b1c1204feb481d5da5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0141f9a34f24264a8a305d5b645a68fafa99bf42.nq.gz
│   ├── 040e3b82f414fe2ba1f2621fe7eae76d9ed49bf5.nq.gz
│   ├── 0593fb1f3f64c8e33880574b3549c702d96164b4.nq.gz
│   ├── 0c120c83477b10c7088759a9051b431e6a1c153c.nq.gz
│   ├── 0c3df92b10feb4b495fce23712ef1d59e8287748.nq.gz
│   ├── 106aa94cc27ac89c30fa172dd4f3cd9ce5fda989.nq.gz
│   ├── 11078a74bdae1de89078d2adcb8ed9d63b9fb0a9.nq.gz
│   ├── 1260adfb7e2debaf1aa0dd3b3420b917a4fd48ba.nq.gz
│   ├── 1495360268a2184c78d88f3d90b8be9f950146dc.nq.gz
│   ├── 14ef8f02a344f9ce62de1a13ae1868eeaa499a73.nq.gz
│   ├── 14efaf0b537c7abbca9f3cad65454c84f679bf7f.nq.gz
│   ├── 1578e1e9de9ef51365b639268b8560df9f4ff3da.nq.gz
│   ├── 15f66d4edc845cafc93a59fe6e4b7e27e74323f8.nq.gz
│   ├── 17c43f8f6c2f48daa907f177ac4ba4f122ce3299.nq.gz
│   ├── 18f9afef81301ea8ed7188dbdceeb8fae2b1e4ad.nq.gz
│   ├── 1913e14a390787a646e803f2cfa32725092c632a.nq.gz
│   ├── 1c4587b7b8a3db55a603cfaf5c654f3263486874.nq.gz
│   ├── 1d0c360425d1a87101c533c1e0de3e8c59286e37.nq.gz
│   ├── 1de1f681c948cbe4b44b30b06ddb3d9f201fd205.nq.gz
│   ├── 20e5a1a21cfb9559463edc8f59bbd0592d537815.nq.gz
│   ├── 229d8787895815d3266f3348dc22c8676ebe9ce1.nq.gz
│   ├── 237ea0a69e7c9dd01fb53cee82ce4fec4b9d0df4.nq.gz
│   ├── 248e62a3e08f0ad5d6c714413f71a79f7583ae33.nq.gz
│   ├── 24af69a6f8e97178100d74f99a16756c0ab675f8.nq.gz
│   ├── 292d5e41d95a24a95c074257dfd3c71b6babc969.nq.gz
│   ├── 2b650a3caebf4d553853009b93377e716783f35c.nq.gz
│   ├── 2e6fd3f2143a09161e6b7b45ab285065f35d558e.nq.gz
│   ├── 2ff7e2a6b3f5fd926a79e1a55871d18657ecc96a.nq.gz
│   ├── 33c7859dfbb0cb3c35c4f863428542645f9befff.nq.gz
│   ├── 36f372db5a9ae4c6b9fcc6828433375a901663ae.nq.gz
│   ├── 374fa259ae47a6f9fa2e65eeb9161edd7789efd6.nq.gz
│   ├── 37c23776b73219c5497a21e01f5e0a053846587e.nq.gz
│   ├── 3b164b25b30bcfe038e62cac58920a47c87545dc.nq.gz
│   ├── 3be1361ab0b65ce5eeebfe835ae317377ee6af6e.nq.gz
│   ├── 3cb1369f5099b9b5d0e03c957e6335639900c5ad.nq.gz
│   ├── 3e3e17b05ebee7f1809c26d2430a906d13d3c7df.nq.gz
│   ├── 3ecb2eaf95dd34aa904f383b3d560b834642801e.nq.gz
│   ├── 412f4be0a12b23846347a5d82179dd9b6c44cc46.nq.gz
│   ├── 436cd004d1fe74bc2ca7f611eb086bc08e650d4f.nq.gz
│   ├── 44b492ace5232573b9705b97da01b5f616a49198.nq.gz
│   ├── 468670e7f96d34c4d3b28c1e352eb8fce97f545c.nq.gz
│   ├── 47aa26033eaaf219038ce887fee6827dc92ad9f4.nq.gz
│   ├── 47ad605269c509cf4a689779c96a5055ade6220a.nq.gz
│   ├── 48685b05481ebf26f453f56d29323a171df36a60.nq.gz
│   ├── 49621fad4b3fbfbdccbdca39111fba6ecf6b6a8e.nq.gz
│   ├── 49debf67426f19475cc7a51bb2cd1a5a6b08bf18.nq.gz
│   ├── 4f8c4b1dc5b74246fbb326cca6bef19ab6e71941.nq.gz
│   ├── 4ffc094df3b11eef907c048386dd8d838eee36dc.nq.gz
│   ├── 501cc86f31cc57490c710946b9df425ccae84540.nq.gz
│   ├── 56e06fe8d72e7c61d3b571f345477d8b36a6ca05.nq.gz
│   ├── 57ab639981334cdb8e3b697ae3e59b970ab8e072.nq.gz
│   ├── 583ab80df4e0fc029fb5fcab9cd194420d9a1af6.nq.gz
│   ├── 585b0b8a140ccb4d0ea3ddba7ddddb21570008ca.nq.gz
│   ├── 58f7b7df530b947cf785cb912d73f0380dbe063a.nq.gz
│   ├── 59ce6d4c4c6943282ae20bf4798b961fe8007805.nq.gz
│   ├── 5abf084ce801b819bca1668670715616e970bd36.nq.gz
│   ├── 5d245d37cba69d4dbf7763f89c2b222a17a841bf.nq.gz
│   ├── 5e65d5d79b7835d09218f8005f25d42ed353e51f.nq.gz
│   ├── 5e70cf78c3e8d0e65deaf1ce1b8a592bf194425d.nq.gz
│   ├── 5ee8d4c9e7f1d6d91f0549c50702321b8b580f38.nq.gz
│   ├── 6237c2be80d29ae4d4f70b4ca1a3a8753707c8bd.nq.gz
│   ├── 624804e60d39f65dbd86927dc11836d34401078a.nq.gz
│   ├── 62504c9e8aaa536d2532e5b454cb887707e01860.nq.gz
│   ├── 62adaff6f1840bfd0cce0d012a2809451c8f7947.nq.gz
│   ├── 630c0b8d6c80d8dc704123b2f129eec5ddb21882.nq.gz
│   ├── 66db6cf8827a7d6a1f3e9023a30546c3c4d307e5.nq.gz
│   ├── 671822db54f67c68be9ddefa435127d55a15d341.nq.gz
│   ├── 6a80ac1d3443c8f6cde9f5da453307ea222db54a.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 6bc6dbd6e30ad5457b4b1daf4f92e73983f9dc3a.nq.gz
│   ├── 6cb4cc5d01376f3f3bc519e630282aee0062dbfc.nq.gz
│   ├── 6d35028a7a4ac186deb865f73edb90ed06263847.nq.gz
│   ├── 6e10b9a410f383904ce40dfc277140226468b168.nq.gz
│   ├── 6fb4b9d205c8ea8ff138dac447b364a9c8e937f9.nq.gz
│   ├── 7031f07966fbe773412c1a111a610231e95677c7.nq.gz
│   ├── 729ae92955290dde259a26b03d95cddb080936ed.nq.gz
│   ├── 75f0b9f2245f66117cf068e57f89708cf3ce06b2.nq.gz
│   ├── 77bc959464bcc839cb495c129e2721a240819eb0.nq.gz
│   ├── 78431eb5c9881d149e66803fdf25b1718da19905.nq.gz
│   ├── 7cf449c827eadf81f646e3e76ad713fb42553aa2.nq.gz
│   ├── 7d577cca043afb20bba72d9a5fe54d00e2421b2e.nq.gz
│   ├── 7e17d4017bda25613742b7c2ed1d6e9591fd18bb.nq.gz
│   ├── 7e897baaa2ba7aa889e0d9148836df0ae3529876.nq.gz
│   ├── 7ea90d6ed24a52a62bf89067ca4f9e1d7858881f.nq.gz
│   ├── 80e1a0d0956f2fc9397f04993705f77645aecf54.nq.gz
│   ├── 84842f7542c3ccc22de8cead2178265b026b3a6e.nq.gz
│   ├── 89709ae12457e11d9dd24729109b0706c34e946a.nq.gz
│   ├── 8dee947835e3b00d7f4e1bd793fae1f4699aa00c.nq.gz
│   ├── 8fd0b168f8cacf84d5e69f96f432a4825c1bd46d.nq.gz
│   ├── 9031bc91a90ea321415ab69a128bcae716de2016.nq.gz
│   ├── 909363e284b35f7849afd01a8fe06f83ecff8982.nq.gz
│   ├── 9103c433eacaed3cff5a39d93ef5f8e69654d45d.nq.gz
│   ├── 913e6846a3c555017386d2512cb57e728cd945f8.nq.gz
│   ├── 95caa3bba6b5cff2c63b8e68e4660a5bfa501e6f.nq.gz
│   ├── 97c966b05cc0136e6b3ac04d321c4b9b00c64869.nq.gz
│   ├── 9acf40589f62a24ddc750540030553a27e500112.nq.gz
│   ├── 9bbbc06886b08454198ea8e6da9e3c4c064b05f7.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9f1e55da7f66f2b91bc7f0be7d38e4300394f896.nq.gz
│   ├── a02dfa7a26ccaa0db7876fe557c196b13c0996d5.nq.gz
│   ├── a1c18eafd5c3b45013de6337cb0658f4ce659343.nq.gz
│   ├── a353a088c592401c7a7423f8d4a4f8b2a182d841.nq.gz
│   ├── a38c27fa4863f93f699517c4778b1b832c89c7cd.nq.gz
│   ├── a460a728f4143bdf5fbba0d5fb979a9e853c9d53.nq.gz
│   ├── a50b3062fac34780b3fb5b79860e6569e3ede2aa.nq.gz
│   ├── a6ba5eb257364d6eb7e4d0bd9f227052d37f93ce.nq.gz
│   ├── a7e4020465290977d33692ad44f94c6465f60410.nq.gz
│   ├── a81c976506d4b8cb5e99e553fd48c1b97f962427.nq.gz
│   ├── a8bfa4a60e89f6f58c1a10511183c1d78bcfc0ad.nq.gz
│   ├── aa930134b5de891e548ce582fcd8670951cd6035.nq.gz
│   ├── ac7c35b9d3aee87ea645a6d2b1424f6105184697.nq.gz
│   ├── ae7952bfaf08c861e99a0664b51ab105e2c35e0c.nq.gz
│   ├── b1d3eaa2b9c4d6654e187b9e504085df88a814f1.nq.gz
│   ├── b1db0199365da71e4bcfb056aa688468097e0e4f.nq.gz
│   ├── b1f62d16d89410ff95f86365af4d50256777bbb1.nq.gz
│   ├── b2b5e5dcc437af1744b0dc71b8144ea3ce807a6c.nq.gz
│   ├── b2c5e18c168d7089c1763676a976c62b9988d1e7.nq.gz
│   ├── b6eb74a45b71d5d80692d8aea1376a5a5cab90c8.nq.gz
│   ├── b8a3a8c686f7d9c5ab21cf009224471c5434bd37.nq.gz
│   ├── b9d201d94541f8de038cf68aaaf9ae5a2b551dcd.nq.gz
│   ├── b9f7601cd1257fb27498e86e959e0208b5a2ce22.nq.gz
│   ├── bad7a41d3bd1b1281f01e13b4a412d6e7ec51483.nq.gz
│   ├── bbdd33c758f25a1c3697846a2fa6d5bcd9743413.nq.gz
│   ├── bd0217b53ae21688051b4e9b6cad000010670f2f.nq.gz
│   ├── c0c687b2694e02fb48a8253f5099d1d3513d093d.nq.gz
│   ├── c0e998161b0cbcc58a02715983bf1e32e1288b37.nq.gz
│   ├── c16c8bca281b677de05c4ed514b38d59f90fc388.nq.gz
│   ├── c3aa6783369257ce358fd4355aaacd6202d19da7.nq.gz
│   ├── c8e83f4c82fdb1112981ab7b0b6b48f4985097e5.nq.gz
│   ├── c9c9312c93c295a08a07788c4e69fed13860820f.nq.gz
│   ├── c9df8d12bac841a99a562cd455d6fc1973db7896.nq.gz
│   ├── cc4af90dec62a6208b39fa87faeb319a851f24ca.nq.gz
│   ├── cca79fd48623f39b161e5b2a6ad168727edbf4d9.nq.gz
│   ├── cd52c645f37c695b58535e15f1ebb81221fcb23d.nq.gz
│   ├── cd6a37670c24150a44c4a954f8a0ff1b1460a79c.nq.gz
│   ├── ce153bdc3b7499fc97d5a827400236082379f7d1.nq.gz
│   ├── d004e0943ecff2f5a341af75bbfd3b61c976b440.nq.gz
│   ├── d0ddf160f258ebd0c5b05c81dc18ff15454c5a3f.nq.gz
│   ├── d210da0b7f307598bacdc9385f31f0fa6fa7c651.nq.gz
│   ├── d62241d84aea1b0dcc967f3d339caad74f9b8d67.nq.gz
│   ├── d6ae04915bf20bc7eee2c4af68bd2f139ec5dece.nq.gz
│   ├── dd696bece935e666387b0f872f5e294e6031fb8e.nq.gz
│   ├── de6d20d3ddb6bc0af3d76aab04620734f1281760.nq.gz
│   ├── df0443886349cb3db0734c76bd4a0b4a506bf454.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d20f458d611fbbb2bcbba62c72a70661e8706c.nq.gz
│   ├── e89fda519cb9876d9595536340d26c9936702019.nq.gz
│   ├── e8db0c600171c86e07e2371f17eea79ab5ed3e49.nq.gz
│   ├── e9dced2ad9f8518426b93b6cb6358258f9f3d111.nq.gz
│   ├── f0de5bf6a9689c8dd770d2bc7620c8ac009c578e.nq.gz
│   ├── f1e962434213479eaf45e398c6e8b4378b7b0b91.nq.gz
│   ├── f2aa78456e600fb044528563fef7611a9d67520b.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   ├── f447d655b2111f2f26271ddeb704a9d3ff5c5e38.nq.gz
│   ├── f53712fe4398b46b1fd9f5fa7610797b5ee0a101.nq.gz
│   ├── f543cb2b02cec09a888eae37706724deca4011dd.nq.gz
│   ├── f5f7a11daf9a8d81c3272023da5dd5dc37d60a79.nq.gz
│   ├── f8e169f02dac911defb1924dcb7952f2afd73bfc.nq.gz
│   ├── f93b9cd015ad273708899a19ea8c89dba3e0f316.nq.gz
│   ├── f9e1c20693eb2aa72ea281741b2fdfe91ca67a6a.nq.gz
│   ├── fa84ca8e1943282dce239bb55120a6a2673ebbf0.nq.gz
│   ├── fb03f26e6be82581a39a45b00c82f59717bd983d.nq.gz
│   ├── fb82f988d9a9bcc8dd0cbc14be055da90276b409.nq.gz
│   └── fcabc5dd0aecd038827910e2f6966fab1a4c05d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22ba8446b620cb7d9ab076b1c1204feb481d5da5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 172 files
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

[astropy/specutils](https://github.com/astropy/specutils)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
