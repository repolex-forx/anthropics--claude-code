# Repolex Knowledge Graph of anthropics/claude-code

RDF knowledge graph data for [anthropics/claude-code](https://github.com/anthropics/claude-code), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/claude-code
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22fdf68049e8c24e5a36087bb742857d3d5e407d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 22fdf68049e8c24e5a36087bb742857d3d5e407d.nq.gz
│   └── repolex
│       └── 22fdf68049e8c24e5a36087bb742857d3d5e407d
│           └── chunk-001.nq.gz
├── blob
│   ├── 008168a4c9e17e7b958a206696a838dd5823cccd.nq.gz
│   ├── 00cd435c88bc23614422a12494488bd5b3bd255b.nq.gz
│   ├── 021234cf7ac8c49964552b50650428727ea891a7.nq.gz
│   ├── 02a556fdbd9483426d994419a81c936da7e28a6d.nq.gz
│   ├── 03e706c6fc833c1022674206b44c6934555e8949.nq.gz
│   ├── 0489074abad81a48abf1ce6b3fe96ee91137f246.nq.gz
│   ├── 05547bed410c358570ac6bfb8f4443f046468bad.nq.gz
│   ├── 06c15c847b2795e7a05fde75b7b1b846f026a39e.nq.gz
│   ├── 087e969717fd7f5e577c551efc9e11df3b4216f1.nq.gz
│   ├── 0a624d60abf93743961338886e4e7ed33834e305.nq.gz
│   ├── 0b27765f17635137853df05bb7c122d39f1af3d7.nq.gz
│   ├── 125857250d29c61e46e3d609af24f31d20a2ee95.nq.gz
│   ├── 16d492dd2635f48e8ac004d03223ac3689d37dc0.nq.gz
│   ├── 194b512ad67b76c9a58b80cf3f28acdfa6fb880f.nq.gz
│   ├── 1aca6cdfb71bbf67da11074f22b53c00d2ef4452.nq.gz
│   ├── 1c209e6d9ccab1143011e32b943a05d927357c9e.nq.gz
│   ├── 1d4ff3840f8086665838d5746f261d60c6966ace.nq.gz
│   ├── 2348239c4de79ede58b2cb14618f6857c467085c.nq.gz
│   ├── 27591dbcaff810375de507327d26911575029d62.nq.gz
│   ├── 28ee51fdf3a6d0ad4935c3505c6306e2cc034d1d.nq.gz
│   ├── 2ad3bd3112abe8fe70375c602e3d93afe0525f1d.nq.gz
│   ├── 2c37a2074672dcb97938dbc1d46c6809818bf9c3.nq.gz
│   ├── 2e5f697934f45ab2932db38205f3951d778df527.nq.gz
│   ├── 2fa6ca2409e973a1d002620c692cc0d282e58569.nq.gz
│   ├── 304b520c0d82dcfa3f1bdf2dddac6044877b4460.nq.gz
│   ├── 307289ddd099c38ec513530b826ce2ec50659a83.nq.gz
│   ├── 3076046052483b5638c1c5818d6a19d5a87f3305.nq.gz
│   ├── 31ef0790b704d5197843d54bdf3efcd112c54137.nq.gz
│   ├── 32933facfa790430576b9fafea85a27da0458dd6.nq.gz
│   ├── 36830932de4299c639d256b875e1163f3c8580ae.nq.gz
│   ├── 37a8b5789b42d3f6245f477d3162cd5e4c68785e.nq.gz
│   ├── 39d27ea057f3efb30d1be975b701316306225dbf.nq.gz
│   ├── 3b3533320e3f20a1e32cede2d030f16ec4721286.nq.gz
│   ├── 3b4dbcb62a021bbe213ea9a7394b92ea753574f6.nq.gz
│   ├── 3cf8b5b8f63ab784be687bb3cce7452164eb7759.nq.gz
│   ├── 3ea03ec83a2f88293ae34fd24ae7461ca6404d8c.nq.gz
│   ├── 3edbae7c5ef81da2eab91d6a8ccb5c13c7c112b9.nq.gz
│   ├── 3f798c518c3bdb74e2dc7a793b21015f42f23038.nq.gz
│   ├── 40699358f2f8098e860838cd68b0382a31c72262.nq.gz
│   ├── 40c9c2f3633d54fe1ec9a119f7a00f7eea0e171a.nq.gz
│   ├── 42cc8095cd2c54e043f9276224df408dca4f48cc.nq.gz
│   ├── 447538654d9439061799b6e08ccdabf80a4ff3a5.nq.gz
│   ├── 4528953397fd690282ff1c079f1c52a2a34ac3b0.nq.gz
│   ├── 462f2e01b89e6339994c071c765dcb4dd380c869.nq.gz
│   ├── 468750ed513d46c6e5af2120f996380f72c1f1f8.nq.gz
│   ├── 4709290be3f7076dd30d26875d2b6d0efbabcb4e.nq.gz
│   ├── 4842f83d2186e9688e0326f495ac303465375ec9.nq.gz
│   ├── 50d9723a8f6a79f69c652f0ce601cd7031254431.nq.gz
│   ├── 527b119c4465a99b1d4f81f880ab76f69e0329bc.nq.gz
│   ├── 53ab7a829eb159fe3f216faab8296f0ab306f329.nq.gz
│   ├── 57f0b6e3eaf82f0cafcc4692d135525bbb9a9f0d.nq.gz
│   ├── 584bc7ddb3a39e0cb1a83714caa91de1436c7d5f.nq.gz
│   ├── 587cae37e680a190b1f9c75232c639b33d36ea21.nq.gz
│   ├── 5ca0973f8fe283e3fbca710c2b5ac5233228abdb.nq.gz
│   ├── 5e0d7b1dc8329d9a9c0168e4e498b3d7a424886b.nq.gz
│   ├── 5ebdd02948511696aed8a317a7160d385e25db44.nq.gz
│   ├── 5fc681b28ad38baff444957f8ebb8afa17be5522.nq.gz
│   ├── 5fe5625f9a612f3a8fba4fcd1ab4a34f266164d6.nq.gz
│   ├── 600b6db41fac7e2081c7528ec6982960892c819d.nq.gz
│   ├── 60953920b40b007eaa364bfcd753299d402b1ac7.nq.gz
│   ├── 60af1c69dd539cebe1ea7daad34181a68de063ac.nq.gz
│   ├── 614c8dd32e27613a240cecdc66b9e34e22466d8c.nq.gz
│   ├── 645a5d67c6d1e16437bec850dad5bd3b6c81f77c.nq.gz
│   ├── 64f6041effc1c9ab182241b31814878952a3456e.nq.gz
│   ├── 65d66dcf8118d3feff6bac81b80f6287a0b3df1f.nq.gz
│   ├── 6d5f8af5db0888ee53137f37be6f170298daf497.nq.gz
│   ├── 6efa85468905d83f156d3d89d7ae5804dcb7eff4.nq.gz
│   ├── 6fb8a3baa1773bb78164438532f635bb2ab63bab.nq.gz
│   ├── 713683ccd803f04b4ebe87e84f91ad4f36639dc3.nq.gz
│   ├── 71de91d15d063cd3091768b832a4d0420588f94c.nq.gz
│   ├── 734cac27868f41fbce9bbe507b0cf938128fcd56.nq.gz
│   ├── 75b1a035fa66f2bbae3e5122b4a669609913eee6.nq.gz
│   ├── 78a5045c0e5eb6a05235c61f2ec82e08186753c6.nq.gz
│   ├── 7b482fbe621a999b3a985c6a846aaa358a3824f6.nq.gz
│   ├── 7b7006352b471382a4894fa90a4bba625ab2569a.nq.gz
│   ├── 7d6cfd81a8d2b70f4e6ab04029e546203be0db34.nq.gz
│   ├── 7e83ae867f8f6cef2e2ae11f40fe6d1ccde10eb5.nq.gz
│   ├── 7f6a172d1cbba26490b108420b7e68fa498b9918.nq.gz
│   ├── 7fb589cbd7140152fae41720e391290ba202e57e.nq.gz
│   ├── 80aa75edf74a5f9e1269811b4e8b5852be91e66e.nq.gz
│   ├── 819e86aa380009bc289ceeef5bd824048f28f9a3.nq.gz
│   ├── 8226eb197a7b498aeb1ef113ef38a155e683363a.nq.gz
│   ├── 8244c00591d3af06434cd881968b94e560cb0390.nq.gz
│   ├── 87039186caa4a0ebf27ddddc83881b5355001f50.nq.gz
│   ├── 8839281d88304ece7211abd74c669cd5d3f69a34.nq.gz
│   ├── 8a83ffdf60d3e312465a81f6fdaacf7d28b2e6f3.nq.gz
│   ├── 8a95a87a49defb1133a95906bb06884050a5575f.nq.gz
│   ├── 8b48f6ad72507d6a8741c613604eeeb98d03a270.nq.gz
│   ├── 8bdeda3430e43afddbee79830db0f6ea9dfbf36a.nq.gz
│   ├── 8c7bde5db16ac6674dccd5278e332b232482750a.nq.gz
│   ├── 8e293aba91b721773a007919e935af7ce9c3048d.nq.gz
│   ├── 8f84ed69eabebc632872316a42671a86ff0a64ce.nq.gz
│   ├── 8f9ba5e684d471fc75a18b00ea871f2ad3c358e3.nq.gz
│   ├── 912a06e184c8e77553264adf7dbc57c817c02335.nq.gz
│   ├── 96ba373ef38f2465de7838947dd794c871b85c67.nq.gz
│   ├── 9754f321a7d6f7a1e9f23a0e4f74a84c5f81a35c.nq.gz
│   ├── 986c2aadbc692f3fdfe0d28264da407d4aba2c9f.nq.gz
│   ├── 987e9a1948565e75e23f464fa70aa79015feec53.nq.gz
│   ├── 98df9bd2db78a926fde42c39b89c5ef16ddd83c0.nq.gz
│   ├── 9aa611c1041b329a4be20545c3c4d12b26ae5727.nq.gz
│   ├── 9b2de05b90e74f828e58a8874ed17f6eb9372db3.nq.gz
│   ├── 9bc4f38128b133e4413facc98bea20e39ebe77c1.nq.gz
│   ├── 9c89de4b6522f68ddb4421767505506e316cb31c.nq.gz
│   ├── a58a7b4b0a3301aa1330ea4db77636ea8df41bd4.nq.gz
│   ├── a5d303f20d80d201afd4c3a7257e2cebc6e6844f.nq.gz
│   ├── a65f0108899074d36839fcc3f2d7965104569d85.nq.gz
│   ├── a70cbf97c109667fcacbc43fb84a05b7a2888125.nq.gz
│   ├── a7c069691ee0ddcd655f88ffbd0253dbe7f4229a.nq.gz
│   ├── a84a38fbbf8c63c2f72a84c255a80016595ac22c.nq.gz
│   ├── a85c428fc1757903e3bf383f80104c5f3250e192.nq.gz
│   ├── a918ec3ab9e41a539c76fe1e2652b32537c6950e.nq.gz
│   ├── a9e12cc797e4fa987abadeaea1971a2ae94b4fe8.nq.gz
│   ├── aa85294745429c8f1cdfd90e1bd61653b875d1bb.nq.gz
│   ├── ac5491f4b8b0839b6df2779e27484c93e46e3953.nq.gz
│   ├── ac75eedde7ad999488211738e056aff9217f806a.nq.gz
│   ├── acce8f90882c815f8a9dca47bc460ccfb2712dd6.nq.gz
│   ├── ae6e94b1d714b05d728405fb5e496dd57f8bd6ba.nq.gz
│   ├── ae92971d8edd561096814b7f98ef181b8169a997.nq.gz
│   ├── b15adbef874f74734d7f0336b8d3364246aa2fad.nq.gz
│   ├── b348560c5302af9c93491c4f00410a77aefdf679.nq.gz
│   ├── b3ab7ce9b781ed39370b427b8c83ee78e5341c35.nq.gz
│   ├── b56e19935c94b3d40081a8d5853a6289fdda98b3.nq.gz
│   ├── b62a91035c84e76920242d363be1041288ba1b79.nq.gz
│   ├── b6ca0563fe9011fb5c3b512f3693b1d3f801498c.nq.gz
│   ├── b8a8dfa41e18ef6ac801ae64be38b2508aa04f44.nq.gz
│   ├── c0fcc79c31f864f6c108c086c1d9ed3a4e6de143.nq.gz
│   ├── c59e1aa645903acc75e40db19cd876deb09957f2.nq.gz
│   ├── c89e9060b42906dbb1e59300a7cc8d98051ad98f.nq.gz
│   ├── c9352e7530c11635a990df827185e07fac681b57.nq.gz
│   ├── ca4dfd4b92d9e40bd7218803b8e0930ff5ee17d5.nq.gz
│   ├── ca63dc29eef850b19f10dd6eec8347f52dcf33ba.nq.gz
│   ├── cb91a41ac960ca769e6059c794e37ac0aa04da70.nq.gz
│   ├── ccc7e472b39b4a84c06d86735bf86dec4f5aa340.nq.gz
│   ├── cf4a21ecc5b8da5394f0711aa513e566d1d7c0ea.nq.gz
│   ├── cf6b13f14a9a42f69dc4b438453d084e20e6941c.nq.gz
│   ├── cf977e4933f1bb7d1f0fff34c9abde0f918020eb.nq.gz
│   ├── d0601412c0e1ce9674d782b96001e7f8c40addf1.nq.gz
│   ├── d1a196991cf563fa36721365d33f33bf6817b115.nq.gz
│   ├── d1c0c199c70e8cef8fee8d3b792b0a27ff33046c.nq.gz
│   ├── d1fb8a5734ec666e225955fe1eb4f26dc67c581f.nq.gz
│   ├── d469b0e7b9123c2431534a5a97e9ffe912bcda74.nq.gz
│   ├── d4b70eadc30b84d4b0009091a68d02b343d7badb.nq.gz
│   ├── d4fcd96cf64d187e397dabe71a72d093abd50d7c.nq.gz
│   ├── d65daca71bcfde02702c8f9722c7f73199777750.nq.gz
│   ├── d6f810fb5368ee6623afd427314e13db50bb7841.nq.gz
│   ├── d83fa2793bb733d655ca380765ac0ed39e1b13f7.nq.gz
│   ├── d9031665564afc43ad19c07175f18bf7a84b1e1a.nq.gz
│   ├── d97b87b112fff723b27f448477410bf5f79f2b20.nq.gz
│   ├── dd45018d7f74b5a16b38ca0fae5c6614e5aeebb8.nq.gz
│   ├── e0f667ef65f7204399110214defd46ce062a1a51.nq.gz
│   ├── e14ef4ddbb5f3d3d99423e002453e8539b0fadcf.nq.gz
│   ├── e214620a3fa348c550bfca1f8d23ceaec39bfe57.nq.gz
│   ├── e34e4323119fbc3050dd83177a7ca5faae68f5dd.nq.gz
│   ├── e36432441f6d541ac3a76a3cffdffa1edfa671d0.nq.gz
│   ├── e39435e14d4fd45d11ba511b7d89f82a950dfc60.nq.gz
│   ├── e55bc38f4f09d8d65801582455e8c6eb1c710c3f.nq.gz
│   ├── e5fc645a80f97014645fd91c04772af21a238c58.nq.gz
│   ├── e6023cbbbc447a97e05bf2c8a72ce920dec3b39e.nq.gz
│   ├── e665193329add13afda0355a6603e2b40c3034df.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ec71c60172acd2e7ebe4b5d202af84e071171b.nq.gz
│   ├── e91cb7bed28ced8b6a48952abe430fba6deeae6d.nq.gz
│   ├── e96448fe9b8ba79e13ebb40be6914f62bb930d15.nq.gz
│   ├── ea09aa194db8899f8760018650dd1486c65bdc19.nq.gz
│   ├── ead68fe39d0063179b5303ae3954ec51f9683690.nq.gz
│   ├── eb1b6e7eeaec45f030303026dae07efd0ca0a05b.nq.gz
│   ├── ec19b4012acbb9770c07e8e2710066a812977dda.nq.gz
│   ├── ec75fba62c543292093b83b5cfb82e6867172d9a.nq.gz
│   ├── ef6cd0493b27a02aa5a23bb3605193c6faaf2dd4.nq.gz
│   ├── f23d4fbe9883c19174141c32e1ce85774253fd04.nq.gz
│   ├── f247571baeabe6ec0e6899dd953ea98e13d78d2d.nq.gz
│   ├── f265c277e3b565e6efe29c564cadc8505b14f430.nq.gz
│   ├── f720f0fcec856560cdddb6b030ac7e64af159438.nq.gz
│   ├── f79ab431604adea8c230da32608c3e5c6ca39c51.nq.gz
│   ├── f7de63267245f6ea392a5484087082cfbafc89db.nq.gz
│   ├── fa2fc3e36fee0d886902d118a55ab12b08a0a876.nq.gz
│   ├── fab66510a84a486718a67b95c3891d99e07f6420.nq.gz
│   ├── fc299bc6960425edce15a6cb5215e4558a456c36.nq.gz
│   ├── fcb78bfd11004048fa287ac52c55eb5c17855549.nq.gz
│   ├── fce2b87e5dc2a42e0d3ff477ab86f528ec9dd290.nq.gz
│   └── fed0a1f1d47b8efe9dff01796cc661b1582c1e85.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22fdf68049e8c24e5a36087bb742857d3d5e407d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 189 files
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

[anthropics/claude-code](https://github.com/anthropics/claude-code)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
