# Repolex Knowledge Graph of TimDettmers/bitsandbytes

RDF knowledge graph data for [TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes), parsed by [repolex](https://repolex.ai).

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
rlex download TimDettmers/bitsandbytes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 833649043474794b8fe7a4136e0c40faf077b2e0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 833649043474794b8fe7a4136e0c40faf077b2e0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0066d086f1cf20c2783f9009482bafa2663bd89d.nq.gz
│   ├── 00bdaa21494e3fe1d08a8e611c00e433ff4d2a72.nq.gz
│   ├── 0108dcaa44a8c4f2282e6605b6d515d16a5babf0.nq.gz
│   ├── 0112727da460813440147fd2e70f68c39a2e0dd3.nq.gz
│   ├── 0186d41c403e70acdabdabd3315810526f4acdea.nq.gz
│   ├── 01ff4441c75bc7ffc217c7742cc7d9c3e953e7c6.nq.gz
│   ├── 03490db5080557c2a308b5d7e278affaa19ffaa6.nq.gz
│   ├── 038eda8417e98ed6cb416a3b5ca9e73f8f9f3341.nq.gz
│   ├── 044d946621ec8f25bca518eb259baafa9c1686b2.nq.gz
│   ├── 046f18ab3bacdbc4f7755fee07beddc116c0c240.nq.gz
│   ├── 04c3d4fda9d070014b0dccde9f001cebfac178f7.nq.gz
│   ├── 055abed2e31812e1fbf2a39fe245be9d7a25516f.nq.gz
│   ├── 07174c38dfec8cbb6a3e93f8177af965026e168e.nq.gz
│   ├── 08b500a221857ec3f451338e80b4a9ab1173a1af.nq.gz
│   ├── 0b4f789eafdb4d55d527c1e27a882fdf7010d956.nq.gz
│   ├── 0c33bdd36cf1963a83c39e2a167e99f9a3eb44f5.nq.gz
│   ├── 0cf535364cfdcc8e47a7428951fb7bbd975d63a8.nq.gz
│   ├── 0d2e162f3ebb1d9fedd43983c9dd7262cd5bb1f4.nq.gz
│   ├── 0e2e2552eedd1454fbef3aa40234edf2c305b529.nq.gz
│   ├── 0f46fe6b0d36db64cca453327b7be3ca2a1a07a4.nq.gz
│   ├── 1496c0bc3c04d95cc8a7e5fb98a41765fa25cb7d.nq.gz
│   ├── 15af97d6d0825dbdb8b9d84a0675725deb5549c1.nq.gz
│   ├── 15dc553da40a70293b2fb31148aef7b24a4766cb.nq.gz
│   ├── 16eed4e819aa9a74e46c377142a4924094bc20fa.nq.gz
│   ├── 1d65a949f139321214884935fd2d2a7bac3a1562.nq.gz
│   ├── 1dc2a298dbde5f603aef56488e352929edb9e076.nq.gz
│   ├── 1feaaced592e93575dc55451e68c383891c2a147.nq.gz
│   ├── 2003bae927556cbfc5ce17189fa5f38f327ce265.nq.gz
│   ├── 221c754448a1db38d007ced18f4d4ce2c861f26a.nq.gz
│   ├── 2399cfaf6c22dbc582fd4d1b5955746e1bdcff32.nq.gz
│   ├── 24431603b21d46e6483b04cb860c72f01cff0298.nq.gz
│   ├── 2566d1e47ef37a55966bb66b5931cca1c41d85f0.nq.gz
│   ├── 25ce3cd1efacf417cc20e57a528777f864a48e52.nq.gz
│   ├── 27c6e2b3c8fab7013d998a90eb4f2ae385e3b393.nq.gz
│   ├── 27dae7ae0ef0b3872a3ccb086d080d1673c5d432.nq.gz
│   ├── 28cf7142a93345fcd56a9786a41b28a2c71a62d2.nq.gz
│   ├── 28e508e48b528b0bd00e3040b2ad5a2e7f56e4dd.nq.gz
│   ├── 28ea804d06473344e1dae2aa3960a2fa7eab77c5.nq.gz
│   ├── 29736311dd1e8a8e8dcadcf4dc97472d031bdefd.nq.gz
│   ├── 2dfe7e758f1a118e7a2d80251e373306bffb107f.nq.gz
│   ├── 3097a1a60fe91d14821ee0eb1966d8cb01a80ffa.nq.gz
│   ├── 3119bb5dac5d18045c48c174faf820387387447c.nq.gz
│   ├── 311d49985ed522851e23350abc52fe9465d73253.nq.gz
│   ├── 327938e5465f0d279abd326425cd808f790b38f1.nq.gz
│   ├── 33b2cd9ac674f338429fc972669596dbedc88143.nq.gz
│   ├── 33d839f6b41aae5b8450fe99b65932602a0a2367.nq.gz
│   ├── 3464587926ddc1db4611b1fdf949dfedfbe17e10.nq.gz
│   ├── 34af1e9e138dd2cd36cef8161aafe45718701400.nq.gz
│   ├── 36e151dfc66caea5c178c87c7fc2a246be40d126.nq.gz
│   ├── 3a1ec40a84e765399a96189c4e58cf56c698a950.nq.gz
│   ├── 3ab1cc5bdcb0a77e1a5a697a2b5e082f156c7204.nq.gz
│   ├── 3c21a9a29b0702db951366927ebc0c0c1dff94fc.nq.gz
│   ├── 3c62ef6f72127dab1231dab51472a8edf87ac623.nq.gz
│   ├── 3e5f6a2aab0dd34a7e909b355c9282e6f128df2c.nq.gz
│   ├── 3f206a169fa2d2db0c7b107d4b3e9c48ccb8d5bf.nq.gz
│   ├── 410282f3976d5f57e2ea157ae8fb4cc573f6a12c.nq.gz
│   ├── 42b8edf0354da61179d9361d685b615e1ddaaf82.nq.gz
│   ├── 43efd860999f38d8d0b20a0398dd73ad41e5ad2e.nq.gz
│   ├── 44fb5dcebc794d7cd8e5a509f5144016d775fbee.nq.gz
│   ├── 45fe0949b3834ce33ae0b2c37578ab63d26d954e.nq.gz
│   ├── 464f921648459b71c61153faa11bf5eb77821f51.nq.gz
│   ├── 48e12b5447fd811d7218ed8aed825f25040680e0.nq.gz
│   ├── 4a2e08c2bdf1c555a6d3e17360c5950df4ea6ac9.nq.gz
│   ├── 4a39e9155f4ec6c2d256ee121979b160d4954f19.nq.gz
│   ├── 4ca60f845b91ea7e3f3ccc73d844bfb176949440.nq.gz
│   ├── 4dc01412b7ace66a1bfd5b8ca46f4c3947303add.nq.gz
│   ├── 513baceab4ad3233909818864dd4fdf2df527f01.nq.gz
│   ├── 521802922810fd6f6432564ef1f71233936d2508.nq.gz
│   ├── 54c1fbda0935f42be13fe743e080977938278417.nq.gz
│   ├── 54c2614bdd981e57165cd267015e38081c46ffe6.nq.gz
│   ├── 55f679cae7e504b6a16bcbdcaea03700255757c8.nq.gz
│   ├── 56a52736ec6b07ff408904013ee0d05c512f1607.nq.gz
│   ├── 56c7c201be1873d3df8e5f76a0e7b9d427b6fca9.nq.gz
│   ├── 6100491f660d1a2fcf8be9a3f5a2468a511d77ed.nq.gz
│   ├── 63210bdc30e7db78642a8208d35395507b5f773a.nq.gz
│   ├── 645687598c23523319450b0613cea42a319156d1.nq.gz
│   ├── 655da84a05fbf4288398f9d0c3ff3cfb9b38d3d7.nq.gz
│   ├── 69b47b5ade88fab2dd055b3cfa0858766fb17a47.nq.gz
│   ├── 6ae3c7c0af0d74945f3f0aee48c29b997079f17b.nq.gz
│   ├── 6c8f4b705e688d6b4d555df1a3e7afa4b10e91c3.nq.gz
│   ├── 6f3f6fc45eac45ac79c2d529b4c12343e38abd33.nq.gz
│   ├── 7077052979e8a737f552dcc31a8f1ec7717646a3.nq.gz
│   ├── 72ee8cfaef7f1ea1697ad13eb23a90e62a0609fb.nq.gz
│   ├── 731200c534ab1950072daed3d2dd70026a2a64b1.nq.gz
│   ├── 75fc714744403f7776c5c11c096ebffe8acdbbf4.nq.gz
│   ├── 7630236c90b8134880abdb2cd66309d6ee63e9e4.nq.gz
│   ├── 76d7327a8e002bf8c61434eff2616b8052ea7548.nq.gz
│   ├── 76fb739a30d9f56a8d0dc999003c55fb5fbca7d8.nq.gz
│   ├── 79ede45b21252a69b267d7f4cfc647115b5ca2cd.nq.gz
│   ├── 7a8f1064fe579fba527661720ae393abd0350b31.nq.gz
│   ├── 7a9dc93fc63bd68d26836a6f22cea63fc156995b.nq.gz
│   ├── 7aed74fa20824e5ad54c6cbcafcd77f96dcc5c35.nq.gz
│   ├── 7b72c349cff1b9f77800a5eedad4b8892dec94e0.nq.gz
│   ├── 7b79c8e88ad9aef5991e065bcf9fe3920923c6f2.nq.gz
│   ├── 7d273c853f386fe0160f624301be0d97c042b05e.nq.gz
│   ├── 8183c27e77bd51bb61c267de7663d3b077576bc9.nq.gz
│   ├── 8242d104e0084179af9ac564af574f63e7403a30.nq.gz
│   ├── 8419f14856f0b1cedac4f453d4be9d170b01b5ea.nq.gz
│   ├── 895d7c31642912406b02587bd617f634cb10c387.nq.gz
│   ├── 8a069bd101a089afc59b7d4d3d48e5dd399bc967.nq.gz
│   ├── 8a38bb8aa563e55d936ccc25fbaedd28b4a3ae67.nq.gz
│   ├── 8b2645de2c4e6041582ea2d312e1d2fe1cd2319c.nq.gz
│   ├── 8dddba04cd75478ecd403e3589bba52ef28c4f92.nq.gz
│   ├── 8e59036550286ebe985dc3aefd58136d4aeb1882.nq.gz
│   ├── 8f69bb58f0936fff27984faebc7a539d7ef278b6.nq.gz
│   ├── 906f2858866556bb5a4bc23fae4f77de24aed3bb.nq.gz
│   ├── 92bbdf947ede7433dbd37e8a2cf460b1b272ee44.nq.gz
│   ├── 92ccfadafe0198f5b1827a19a0b30e5ddda079e1.nq.gz
│   ├── 939843f43c758e713320b707421e67c3fa915f0e.nq.gz
│   ├── 93b5c55c36ae689ab97a667e82f65028df3d9c9e.nq.gz
│   ├── 959a7a285771b104fe4348150e423df71a7f1721.nq.gz
│   ├── 95f78b6d396b3ef3f3fb634123c22cf65b3f2861.nq.gz
│   ├── 960201e2e544ea33d71e007b008a80cec7aaae7e.nq.gz
│   ├── 987488770f4594652e06197798cf9d8de9dbd846.nq.gz
│   ├── a0d09d1e86fdba8a051dc9031fddb166b4e674f8.nq.gz
│   ├── a0d9ffe8311a649b9d77f93af4f70a909b24a811.nq.gz
│   ├── a40156a2616f2cf0b1dac0fea6fea8aa824a456d.nq.gz
│   ├── a4f4b4b0aff0a5319630dd243e36c2a150928fb1.nq.gz
│   ├── a5ea80f970718c2f9db5744eb3e4d12af8fb01d6.nq.gz
│   ├── a63e59a99609e1ee42a982590cc1e9e67023d33c.nq.gz
│   ├── a64925c062cf19571f18cd8a5179874dcb8d2894.nq.gz
│   ├── a65652aeb6ae4675961d559ef986f08346aa6b03.nq.gz
│   ├── a6e567859a5fd1343223691867ed67cb8aff68ee.nq.gz
│   ├── a9a57165d9ab396cba8b5eb4005d71d67d2eca72.nq.gz
│   ├── ad70be9114de3301bafed78e459070940a11381f.nq.gz
│   ├── b078e82b7f8360cbc8332cf774bcd3efa6734d58.nq.gz
│   ├── b5591965d6eb6a20fc35546ee34851e8f321242e.nq.gz
│   ├── b96dcb0480a0b0be0727976e5202a1e7b23edc3f.nq.gz
│   ├── ba3d0ea2c11b20ef09e414637c8797ffdc279b25.nq.gz
│   ├── c05d344b37e0fe1d8c12704d6109c6e50eacf915.nq.gz
│   ├── c0a5a21efff7507e1409fc2d021c9814bed22c1e.nq.gz
│   ├── c2f5aa7847ae77a394a96056cf5f68a52f92040f.nq.gz
│   ├── c38fa15308f5ba9d68d2850feb4c2a77031ff1a2.nq.gz
│   ├── c5fd042e86e9207341bb8f68530da0440c10731b.nq.gz
│   ├── c693bb26117f341788401537146591186cb920d5.nq.gz
│   ├── c7114bcaa9d30d9fad42656480f2feeff879ac22.nq.gz
│   ├── c8125745190dd0e4e8912bc6adda4ab6867b4618.nq.gz
│   ├── cc46675c6986c68212483bbbfde83c385114fe0e.nq.gz
│   ├── cfd37832b4469328c76fcfc9e8ef0dc68a8de23f.nq.gz
│   ├── d0f5354fba6ec8f466f7a390f80c56616042c4e6.nq.gz
│   ├── d1cfd67d5e91150d94d28bafcb23ac965d383165.nq.gz
│   ├── d2d0991418eb9e324989e17dafc731eb04517802.nq.gz
│   ├── d3a7474b604da25123cfa4c75529229914848003.nq.gz
│   ├── d3dac55b2f695d0f1f3e0bde929d704c418e8f15.nq.gz
│   ├── d581380ed12cc11746c6b329de62b66519a31a48.nq.gz
│   ├── dc511661bc7099026451aebdb89bdc44a444387c.nq.gz
│   ├── dda8091baf7030894ed68e546c551e5a6946ebc2.nq.gz
│   ├── df0f093df449c6c50cebcfbbeb2c78d8378962b4.nq.gz
│   ├── dfb9046ac561f79f06114d9faaaf89a2efcf13d7.nq.gz
│   ├── dfc6e5d65ef791b26b4b92d89aba1265019d5556.nq.gz
│   ├── e234f20d3346c5effcdc15ae426b9e54c16a6412.nq.gz
│   ├── e24f6a2617b4290bef2297545ed2fa476563bcb1.nq.gz
│   ├── e2501a99a5c07e0f97a7b4366bdada809da33703.nq.gz
│   ├── e3dd410de33bc0b7d2ae460ad20def98f49968dc.nq.gz
│   ├── e4cd6a128422b7f2a42e078b5e20b448f1be09cd.nq.gz
│   ├── e55b4603ba8e3ce923ec15ced40d4b656587eb22.nq.gz
│   ├── e62562bf8cd86ffb800e84425ddf6c00ae000c4f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e716b6f3ff54cb847682d68fd4cb0e6893dba3fe.nq.gz
│   ├── e725ecb17c500f14efcec9c7e151844e1a432fa8.nq.gz
│   ├── e9641235fa0f91b40ab7e75b43bb54a387d43a92.nq.gz
│   ├── e9d4c0ccb1d565132acd60cf942c7f4630cc5385.nq.gz
│   ├── ebc0b09439c4620ef015b18b242328aa65f14c18.nq.gz
│   ├── ebd2bcf56c47911fe4341ea161b99cf9775c164a.nq.gz
│   ├── ed0c22b173e424ee7e1a8ff6253e85f5d5b0edec.nq.gz
│   ├── f1900a4fb2bb57729b1249743f3a1ab13ed26779.nq.gz
│   ├── f1fa7eb62c47aefda51062afdfade3611e66e801.nq.gz
│   ├── f367bc415a963c76ebd9bb8f4b5163c2e25222fd.nq.gz
│   ├── f67885266feabb2c357f4665f80f426420a22cc7.nq.gz
│   ├── f7eb2e213be9f4a5a5ace6393b11ad616dc33d57.nq.gz
│   ├── f8c307c2afa28309e2bec33dbbbe1faa5e5864eb.nq.gz
│   ├── facc58b30af8f3eb3a7895e712588dcf092721ee.nq.gz
│   ├── fc0b196af498f0f4fd8d1541653af4db69448ca5.nq.gz
│   └── ff2f011a260d1dc011b9ede46261fb2fa6d72720.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 833649043474794b8fe7a4136e0c40faf077b2e0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 182 files
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

[TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
