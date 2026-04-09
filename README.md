# Repolex Knowledge Graph of tqdm/tqdm

RDF knowledge graph data for [tqdm/tqdm](https://github.com/tqdm/tqdm), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download tqdm/tqdm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 75bdb6c379bcfc6c592b6342dc791a092b5d6ae0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 75bdb6c379bcfc6c592b6342dc791a092b5d6ae0.nq.gz
│   └── repolex
│       └── 75bdb6c379bcfc6c592b6342dc791a092b5d6ae0
│           └── chunk-001.nq.gz
├── blob
│   ├── 004d7e57b2f378e4979a8b8e47b969c81114956f.nq.gz
│   ├── 019151800bc0c4c4fc543314b6398aa602b0692a.nq.gz
│   ├── 039ce338068a141e234fb1ecf880ab98d1a9bae1.nq.gz
│   ├── 04fdeeff17b5cc84b210f445b54b87d5b99e3748.nq.gz
│   ├── 09ea66673fb8f869874a259cc93fb443fe834108.nq.gz
│   ├── 09fe48f2e58b4b232e1a3109c94f3714006e3aa5.nq.gz
│   ├── 0d1f379d98d160a0e94bee70d87fc4e8f2af913a.nq.gz
│   ├── 0e3e61471065a29ca71039c07a38f7128d3e2742.nq.gz
│   ├── 101ae624d17d5a9e934fe094c5c33d5dee2459ea.nq.gz
│   ├── 13da5bdc35654166547fffb907543678dd98e824.nq.gz
│   ├── 14b0c1963156d9aea344889d8c72603ae0265e59.nq.gz
│   ├── 16992bf3e22e8b200b10de0ee20ca3a2eda17170.nq.gz
│   ├── 172fa701874cdda3021d050e2a4f66b59da99373.nq.gz
│   ├── 17bcb6292870ed7979df7e0f1d144017fb6af103.nq.gz
│   ├── 194caf554f8f10ba4cac8a81b631a61d0d81f60d.nq.gz
│   ├── 1dd08f6053b992274dc8242a4e81ec7e66ddd937.nq.gz
│   ├── 1eec5cae61ff25d112cea73fa1c5318461285573.nq.gz
│   ├── 1fc397123dd6801018e83ffc4902f68747bd1fe8.nq.gz
│   ├── 206c4409d5269594bdbab3a092ef6e09e7c01947.nq.gz
│   ├── 235cb319737293b3fe3c1c3dfbc9f75c4ea542c5.nq.gz
│   ├── 250e6585d73a7d778f431335c6becd418490a621.nq.gz
│   ├── 273c79304a899e68472bef94423efb08438529fa.nq.gz
│   ├── 2d00a0a2e755f36068d079ccc12ca84d86ff42be.nq.gz
│   ├── 2fa5a68a98acea72bf0f3ec16f9660b2c0aa16e0.nq.gz
│   ├── 2fff78cc44fc24f4e2886299b8b3e5e40c535301.nq.gz
│   ├── 307dac423c018c30b4ad2b20ae039ff0d512552a.nq.gz
│   ├── 3235dbf4f9e80fbca4b399c07cd87309ac519b1a.nq.gz
│   ├── 341dead146d50c2ba65c6ceb5b2c342367bb2b51.nq.gz
│   ├── 385e849e106d1319fe21045f14eb0aa6552fb153.nq.gz
│   ├── 38e6b4f82b07933683fdbdb0a9d61d940d0d1331.nq.gz
│   ├── 3d392edaf115a93f7c145de52cbe8978dcf1ede8.nq.gz
│   ├── 3e31905088bf61426b2a356611ffa64a4673afdd.nq.gz
│   ├── 3fa96d8d41a326e626cf58af12ce49afb8a538c0.nq.gz
│   ├── 495c797f27a0f2dad1a4057375a4a905f459a81a.nq.gz
│   ├── 4a91d2339ba0afa14759b23ff7a2f44d18147526.nq.gz
│   ├── 4d6d0cb75827c3f2f77fccb50a14ec91825b23d0.nq.gz
│   ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
│   ├── 4fc8f6b1640d0921633b40b79d239cd443d635c1.nq.gz
│   ├── 537a0578cf75c42a5c2baedba08fe92da065af9c.nq.gz
│   ├── 574baa84bbbeb5afce4a49f23edac894d680ca82.nq.gz
│   ├── 57f1b668f59dc5991019eee34c7df3232a2c2cd7.nq.gz
│   ├── 5a8d09137fb05b43ec637164034ee828621d2e46.nq.gz
│   ├── 5b7db2873738df677c82a371b0029a597262dc1f.nq.gz
│   ├── 5b8f4b9ecd894f1edfaa08d9fe730b8d7c8b93e0.nq.gz
│   ├── 5cd439c945c0ef41807a0ad7da9092685004ae1d.nq.gz
│   ├── 5d03594cc2a7ce3834a34c069be55e8179b47ebd.nq.gz
│   ├── 5d8a6efaebc6d30f14fcbb31d579cd0180718aa9.nq.gz
│   ├── 65c85bfd83021cd5bff1d2326bbfeb3bc90e23c1.nq.gz
│   ├── 65c8cd5588a76cfae5a1e8f0ab502840953e140a.nq.gz
│   ├── 672664d9b7ebeb7bc45dd65a09d44a6f4fa217c8.nq.gz
│   ├── 6cf1e6cf98551fa513098304b126049919ef8a3f.nq.gz
│   ├── 73489bdff7337cd622c2b7005b26a03df338da37.nq.gz
│   ├── 75df2107f065c7a311b51a04f51d733df31da870.nq.gz
│   ├── 788303c8687e007338ce816bf9afeec8581f0188.nq.gz
│   ├── 79cc7ce3fd7044d345bee28b88824a4fe6a50ed0.nq.gz
│   ├── 7b051c8a4d909e020d21ec883e7edad954de09fb.nq.gz
│   ├── 7eeed0b0491f684e5e9b26f05816334d819c2cbf.nq.gz
│   ├── 7fc4962774a4651db7a739a3f143633b6215a9bd.nq.gz
│   ├── 8081f77b8812f3b42d7949daa4195d2c35dc70ac.nq.gz
│   ├── 822b33b24f6a4700c1d8fdfb17fd9e66918a9599.nq.gz
│   ├── 83178e981f46c0784a36bee1f9e347022c7678a4.nq.gz
│   ├── 87ec4601fcff138e0882808237375aed93f5ef35.nq.gz
│   ├── 88a2255596f8f02f7ded4232ace5c5ab0cbc03bd.nq.gz
│   ├── 89e0406c2f4baf2d9f69505ef03c30ecd8760af6.nq.gz
│   ├── 89fafc8c92f8ed085077b37eb58329f2588bd5d7.nq.gz
│   ├── 9264a2ab1a2bf31d051a3fc8925a90fbfda62bd7.nq.gz
│   ├── 9338fb19799fd1d094357bacb91fc7d8aa350ad7.nq.gz
│   ├── 9955d5fb8cdecca499084b52f1fa6696e42038ba.nq.gz
│   ├── 9aa645cef7ae7e042a64e41daca2eb01d2b97237.nq.gz
│   ├── 9bca8ee98904ce869a4f8d6417bbdc4f00b38751.nq.gz
│   ├── 9f61c7f14bb8c1f6099b9eb75dce28ece6a7ae96.nq.gz
│   ├── a09f2ec4b8c95f12b8c7b7774f84d5ec55826334.nq.gz
│   ├── a30d1368668b9aa563ef001a5bc13f63e05c0804.nq.gz
│   ├── a6c48238bd5ee395db5610657531b35aace31df8.nq.gz
│   ├── ab3eb8f7bab312dfb239b4c89c8c913fb00e0054.nq.gz
│   ├── ab454de7c2a7f6c8e47dd9f61e5d288351bd143b.nq.gz
│   ├── b7e149413f638a9b32bffffd16b75903dcb01a2f.nq.gz
│   ├── b8d60b65a7c81b58bb25bf685fc837e52622e821.nq.gz
│   ├── bd8ec609428bfe0a67cb80b4bcc263a5d2ef7ab1.nq.gz
│   ├── bff1c9e02e2bee6b689ac57b52101773ce3a5d8e.nq.gz
│   ├── c351bbc450672b092cf4102464d8c4ce7d558755.nq.gz
│   ├── c4fe6efdc603579e7f8acfa27ac10dccdf3e94ce.nq.gz
│   ├── c51a85cb94ef41ec05e3138606e5a1d3cbb99525.nq.gz
│   ├── cb52fb91a8661f4c73edd352bbc6f21b877dcfee.nq.gz
│   ├── cce9467c51a95388aaa502d1da9a42f3ebf0af24.nq.gz
│   ├── cd81d622a1309df179042159a56cef4f8c309224.nq.gz
│   ├── cf560e7ea76be757c591be3f2dc3a96a65d1cfa6.nq.gz
│   ├── d07f67643899e47d7ce55480496ae3f569f5270a.nq.gz
│   ├── d62a29897949f32594195143cd84246e52e6932f.nq.gz
│   ├── d892cd22186f3163f3fbcb963d4f9a2a1c993cf2.nq.gz
│   ├── d903bb53b4e2fada3e34238d02759d2c25eb8c34.nq.gz
│   ├── db07c7ddaad06042f92b46174d6966724d5059e9.nq.gz
│   ├── dddd918e3619b976be2cc820fdbc4dca7a857beb.nq.gz
│   ├── deb498ad90c509332581198737aee305c687b77d.nq.gz
│   ├── e06b28d3dd370ba645f8b79f119babc1ad37d914.nq.gz
│   ├── e06febe37b5d70b5296804c55dca48a397c250e3.nq.gz
│   ├── e1a921ab6d83e98928c0ee05e5d6088c1584d583.nq.gz
│   ├── e67651a41a6b8760d9b928ea48239e4611d70315.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea3cb31034314d694962fdb74c5855265b0af8e2.nq.gz
│   ├── ee8b9f374f163264cada3da685ad619532cd5e40.nq.gz
│   ├── f225fbf5b52d04987ccf68f4d5ee4b735e3158b0.nq.gz
│   ├── f32aa894f54b3a5b47a0fbf4263c2fd20df56c9d.nq.gz
│   ├── f45fb977a19cc671eb781793296de3a10ac41d01.nq.gz
│   ├── f71aa56817ca77eba5df4a2dd11cb0c4a9a7ea1c.nq.gz
│   ├── f813c5e482539d69f262758fe7def86392f4ad89.nq.gz
│   └── fe29b8a7d503aaada0305707c934086997da2d29.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 75bdb6c379bcfc6c592b6342dc791a092b5d6ae0.nq.gz
├── filetree
│   └── 75bdb6c379bcfc6c592b6342dc791a092b5d6ae0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 117 files
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

## Source repository

[tqdm/tqdm](https://github.com/tqdm/tqdm)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
