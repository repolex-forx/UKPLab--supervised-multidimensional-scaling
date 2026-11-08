# Repolex Knowledge Graph of UKPLab/supervised-multidimensional-scaling

RDF knowledge graph data for [UKPLab/supervised-multidimensional-scaling](https://github.com/UKPLab/supervised-multidimensional-scaling), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/supervised-multidimensional-scaling
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 272f3acc45a0170cf2930f17a63bf9b7c4535688
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 272f3acc45a0170cf2930f17a63bf9b7c4535688
│           └── chunk-001.nq.gz
├── blob
│   ├── 0028ca2f30d2166e3511d8318f75afd7e95110d2.nq.gz
│   ├── 0715cc24b3031cc74db130efe37f8c82227e784b.nq.gz
│   ├── 0717e0d370ebf2219afc7e993dbe205047e933ae.nq.gz
│   ├── 071e842b50fcdef79446b83d8d24834a938ddd7b.nq.gz
│   ├── 0a8920b6473d40afc012503f43a4e52b3722e405.nq.gz
│   ├── 0a90a83b6e71ae4066aaf7b8cea30206dee73e68.nq.gz
│   ├── 0c13fc051c63ba600df8c65653d328d9fd2832f5.nq.gz
│   ├── 0ca578351be014429db2e84e3c40f73ffcdb1e4c.nq.gz
│   ├── 0cefe3e4c01837479f385e4c548fe9f8760e418a.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 142f8b959d219eaa9a85ac86c01be326c2c6fdb4.nq.gz
│   ├── 1637c17a5bfb92dba4cef9434ce4bef2efff5a98.nq.gz
│   ├── 16432c76880852c3be1e98e2ffc164e2f0367a71.nq.gz
│   ├── 18dcea401e74c39b00ab779f7a6998cc9f05a211.nq.gz
│   ├── 18ea1318368ebbfb92dbfec37496bb0ac560158c.nq.gz
│   ├── 1b2b4c64340d5d0d2db6540f22c84ce0e6ffa30a.nq.gz
│   ├── 1cea476166c6a1e5e5ad4e1c12e009973a03a4ce.nq.gz
│   ├── 1e1c6b7ea04d7e9a2830a18d536db7f1357614f0.nq.gz
│   ├── 258750bae11ceee4b26edaccd07cbc3b0dfa50c9.nq.gz
│   ├── 26c81a70e39759c5d09b39a3c7a4865b1fbc9d44.nq.gz
│   ├── 27245b7abed2a381c48fe92153c8f8766ffcf941.nq.gz
│   ├── 2b132c2abe5b193269489603c445753ad215bda5.nq.gz
│   ├── 2e9b4efd5f9367974c74be82bc53af6abfbf7fc4.nq.gz
│   ├── 390056bf3a7a93537941b43be81d7ee89c897ff1.nq.gz
│   ├── 3a65b5a2fc9401e778a880682851b440b74a9129.nq.gz
│   ├── 3c9167af12b579c364269863b25f7029c67d39f5.nq.gz
│   ├── 3d57efafbab4cc8da04074a1e127e1ffc513bb9a.nq.gz
│   ├── 3e595a089076a8aa34fee24f1e002adb79627a86.nq.gz
│   ├── 42103d9d4cdde5ce0a7d3cac88b9bb68a4c5ff0f.nq.gz
│   ├── 437470ff6c3f51009fedca89c8a3b0212611d099.nq.gz
│   ├── 43974b8522cda8aabdc8d6ac5dfe5ec219d4d849.nq.gz
│   ├── 441fe57ebd78cfde28b1c05230708bef55c1a06c.nq.gz
│   ├── 44f58973edf9465571ca5b8454b467ef1387242e.nq.gz
│   ├── 4561bff01276f7ae7c0608569369e401f0f1b530.nq.gz
│   ├── 45ccae1c70bf505868083c60d6372ab343f3bbb6.nq.gz
│   ├── 4a1cb988656abd3547b43f2f583f63dbcf49b406.nq.gz
│   ├── 4acc41a3a51d279809a5faae810fd6e34faa155c.nq.gz
│   ├── 4c3cdcf67a0a4aedca1e0aaa9e325995722cfb1d.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4db82ee77597e262675c709efe1a8266615bfadd.nq.gz
│   ├── 504972b9eb5ece89b7f85e815fbde9448f208d70.nq.gz
│   ├── 53b9e64b03666a1e062fea4f33eee689f84dfbd4.nq.gz
│   ├── 5467ed03e3026638b91a2a5837b179bf3dad5092.nq.gz
│   ├── 586d3e504d836121de542923b6ce3f9a54393360.nq.gz
│   ├── 58ab47d60622870013d549f53f5bc2c383eafdd3.nq.gz
│   ├── 59d0af19ffc27e3d97406b308ebe943a486692ae.nq.gz
│   ├── 5bc9bae522ee81dae8f4abcf20a7166a4fc8c8ac.nq.gz
│   ├── 5e28fdb5d12004b2e37cd32e77f143d43083d560.nq.gz
│   ├── 5ed43ea25a8bbb29dc9218109697ccd1946e7c81.nq.gz
│   ├── 5f1f0e72d4b33662d7fc9be52407503959efcf4d.nq.gz
│   ├── 618a42535a5f1d9c07677eba3a2b80ad09962038.nq.gz
│   ├── 63bda2b4b406fba60a1c91963508f6f8a7958eaf.nq.gz
│   ├── 67af7819054305df83a963d6a45220b6cd4849d6.nq.gz
│   ├── 687a075951c507c247c7cabd2578606fe654318b.nq.gz
│   ├── 6b5e2d93b8d413550ad4208b6597f351dc9d14ef.nq.gz
│   ├── 6e3efdb43a372bfbe8f5a0c6e62e60aa7de8c5f5.nq.gz
│   ├── 6f0ff1186ed85f33620bf593f41bf875f4c282e5.nq.gz
│   ├── 78debfa84541621b6c5372443108de391206bc08.nq.gz
│   ├── 7bdcf0f501ca5f948ccc8f7f31d7c2b35913a1eb.nq.gz
│   ├── 817aa3803585aeb65435be6b35d1907b9bf98073.nq.gz
│   ├── 82d80d0f1941440da627e4585f7f6f8a4e0f7870.nq.gz
│   ├── 8762a8defdeb6f60374bda7e38de3a6d475468b3.nq.gz
│   ├── 892e400af001b46df9c5edea310fea4e7cebc402.nq.gz
│   ├── 89de120323ef4a302265d42dd4616baa4ac0d226.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8bfabd8a573579596c7b91d1b9252d8f1d452260.nq.gz
│   ├── 8c1164b2df90e7f36bb415c9853b41fae418da0f.nq.gz
│   ├── 91d1e448c585744e7c99ff477de139825c717d21.nq.gz
│   ├── 9543621dae87d8ca910adf4d40f78528738dedf5.nq.gz
│   ├── 994f7ce17310cb8534490ee66d7aa398496587a4.nq.gz
│   ├── 9c1c32e307da0e244adcfc0ab2476ea16a212846.nq.gz
│   ├── 9f50c6f35239e56b97d1c2898a2cf92db052fd09.nq.gz
│   ├── a05135781ef9185ef8830fad2e5afb514a102bc3.nq.gz
│   ├── a2c0a6e851eb0750934a7041f4579727e235888b.nq.gz
│   ├── a64fc981c85de38df3237f55e88538134da5767d.nq.gz
│   ├── a709bca465bc4980afa9a9510dc3e20a381a4dce.nq.gz
│   ├── a72b0e50d3a70203f56706ea72f8596c77d60a78.nq.gz
│   ├── aa6c9a21de101b67c88f7c97d8ecf9523f9b0b98.nq.gz
│   ├── aafe10e81194bb1c80b99772dafb39ae707409c9.nq.gz
│   ├── abeb56d0c88465d253d733b35a5b9b462d0b0810.nq.gz
│   ├── b1531c54a6cd44436b598caeec8980fc76c9487e.nq.gz
│   ├── b448b721aff1a9c770fbe3e0efd9eeff327e876f.nq.gz
│   ├── b61863b96739f33712ff1836c409414a18d359a8.nq.gz
│   ├── b636855723ec9648002390031ea7deececa7b6f9.nq.gz
│   ├── b657432857162632c5d39505eff91c4d415c5537.nq.gz
│   ├── bb47f5153b442f14e86511381bce684fc905116c.nq.gz
│   ├── bd677b913bef9ea9ecbdeeaa209eab08c102cde3.nq.gz
│   ├── bdbbec682e559366437fb48fb0035c0c2ae46c11.nq.gz
│   ├── be89f8b993fefb52e80bde86f9929c0cae9fd0b4.nq.gz
│   ├── bfd78956cc63ccae068ff434d35d3d823303b40d.nq.gz
│   ├── c37076ac8f0e50ede43bc74ee81fe7e79c73504f.nq.gz
│   ├── c53a90180b5a28cae0d12e3c813366671f827c41.nq.gz
│   ├── c700747d3eeb748df446ca6c9f6b9a6d9167d531.nq.gz
│   ├── c8340dc241c9a598d654442efdc569d843abad8e.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── d1e4c5752edb00f9ecf884f6db9d8b51a05c4164.nq.gz
│   ├── d506226dc5200a1770e7ddb51e14b3d359190dc0.nq.gz
│   ├── d705ec276ea5ddea5943c79549c76202e253296b.nq.gz
│   ├── d819f4a928a6dee05bf4427703bd1b36f45a1779.nq.gz
│   ├── dc8d38bf99bf6968c26d3b182bb31258514c2a29.nq.gz
│   ├── e028b521ed88ca8712391bdb986505b076fc2626.nq.gz
│   ├── e13058c656beebbcdf6217d929d4d927f8895d1e.nq.gz
│   ├── e43945bf4da5fa245aeecf722ff68a5290e11320.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── f1906b4c912554da6a03c600a191dd01ae7c52e8.nq.gz
│   ├── f2f3f3960276a619503a950917d5e26b74354687.nq.gz
│   ├── f4c5c10c70dddaf6ee9a5d949a381514a2c5eec0.nq.gz
│   ├── f4e5b961dfc4e5053ee33c16d721a1e21a265e6e.nq.gz
│   ├── f6dbef56653a2275afcfea5c3df8af1990d4cb1c.nq.gz
│   ├── f907a945e41efb62b304f115f67ca88bd9e54ef5.nq.gz
│   ├── fbeda5500ad291870c1904ed49f72a990da1c824.nq.gz
│   ├── fe19224f58ccc88d019df45a207497368dff36fc.nq.gz
│   ├── fe2d1b933321380576089ee4152e55276bb6d21b.nq.gz
│   └── fe9a5d4adfe942a6a8048db1fc75c677a1c5b6be.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 272f3acc45a0170cf2930f17a63bf9b7c4535688.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[UKPLab/supervised-multidimensional-scaling](https://github.com/UKPLab/supervised-multidimensional-scaling)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
