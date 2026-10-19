# Repolex Knowledge Graph of construct/construct

RDF knowledge graph data for [construct/construct](https://github.com/construct/construct), parsed by [repolex](https://repolex.ai).

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
rlex download construct/construct
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28c6e5779f2b76d55474914607291a3821502000
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 28c6e5779f2b76d55474914607291a3821502000
│           └── chunk-001.nq.gz
├── blob
│   ├── 0148fbc890610900fd4eee75826767de74518eb6.nq.gz
│   ├── 052bdab691a893b621987af4c2b113f1efbbc024.nq.gz
│   ├── 05629f06db27e8e79509c5557a22c16d76e784bd.nq.gz
│   ├── 083f301560559c8a74fbaeda5a0dabbf9cafdba7.nq.gz
│   ├── 089116305870f54fceb1af0efd4d34d19242a1e7.nq.gz
│   ├── 09b07515f79af8f2642be4b418c3bcb69a96db99.nq.gz
│   ├── 0d3b156077f1116dbd47231edade8103210f5adc.nq.gz
│   ├── 0dd1562e3e4797be7967581b2e08d7143bd6f655.nq.gz
│   ├── 10c88aabcb15e597370db6548f5b3eb35da42f42.nq.gz
│   ├── 11272fbe0cf2300ec8aa8516056dbf78da714621.nq.gz
│   ├── 122beae5123ae300dcd358d05bd8dc4c252a81c4.nq.gz
│   ├── 1502aee9812b691455cf75f6bd801cc6acb8bd59.nq.gz
│   ├── 1598ef009e80b108c840240fd71f9250fc427b62.nq.gz
│   ├── 15b94a97a10f25e23430a854aa977d1b2932647a.nq.gz
│   ├── 2035c5fe1c4000fdc4b519752ea4727e43f76cf1.nq.gz
│   ├── 2250141024a59a1ff83b1370c985c6e1f911d487.nq.gz
│   ├── 229b6ee3b8b7c09c2a6d35fbb21fc4e88f5e8504.nq.gz
│   ├── 23bb3c114f90db90acee50ea7ccde037ec8de20c.nq.gz
│   ├── 2b913e311a614f1da4aef9915955ba23d99fd974.nq.gz
│   ├── 2dbd4ea4b64f3985bd75761a97f7aa85d76cc25b.nq.gz
│   ├── 31c068b31b9fd9c9ac3ba8a7f286192e1226003c.nq.gz
│   ├── 364f6c851b813062ad3860c3dff2e5f14399e1b6.nq.gz
│   ├── 39256aff89c44b7512165503b0d3c2102f8569a1.nq.gz
│   ├── 3c0ecfd04b3573935b837c26cf4264d1231ff059.nq.gz
│   ├── 3c36ad2667ecf61929615cc47bb0a980763a622c.nq.gz
│   ├── 3d0e753926190d86a1506fee33c6f6364317338f.nq.gz
│   ├── 41e9906aa35425b61f70fe9e7cad8ae02eb47165.nq.gz
│   ├── 421d97bdbbd45cd74129663e68a5f9b110b0c1ef.nq.gz
│   ├── 42d513a054da39fb94c02c2780281ca59aad2da6.nq.gz
│   ├── 435732b8f180f9c5a52459e5e5feb533ad419cc1.nq.gz
│   ├── 54d972e6501ed0d42b06175c4c8fcfb2229dca80.nq.gz
│   ├── 563aa2479d5b9f52db7565a6f88a9b8ec4cb168c.nq.gz
│   ├── 5894f5708459ed41cfb1fade925f7e23037967d2.nq.gz
│   ├── 5983a98c83e9093a179de78e785e04d96f4a2284.nq.gz
│   ├── 5a73e66d9e73947984b5d5a4aa17ee896acf58e4.nq.gz
│   ├── 5ce26a4fa8e6675628cde3f51521abea9e6b48c4.nq.gz
│   ├── 60d4a2c537978fe1105ce79e5d788efde9fc558f.nq.gz
│   ├── 667451fccd2b5343ae2a486b9df6c6914b486ece.nq.gz
│   ├── 66b6ef98b629dd38946a9c893100f9544bfa90ba.nq.gz
│   ├── 6c1435de00165a56cdb33cb5d17e3f82ed945cb6.nq.gz
│   ├── 6cf786aa8ac3137b29dbc43a442cefc45633cdd7.nq.gz
│   ├── 6f339f5df544610a4acc1bab017d12bfc0b7c393.nq.gz
│   ├── 77e91eab14ff05b46bf25c35696e4b27722ed7b1.nq.gz
│   ├── 7971128fd6527bbaf0dcc21af4626b0caf211e64.nq.gz
│   ├── 798f75c6d3f196972a9214ec7fcab8ce53e4fe8d.nq.gz
│   ├── 7a3e931d60bd58b0658e2c6c9f321ae226e3a9f8.nq.gz
│   ├── 7aefbffe4e0b67d46bef772a852cdaa717356cd3.nq.gz
│   ├── 7ccae0f626eb85018651e1d154b131da31d70dbd.nq.gz
│   ├── 81fdd16726b53475057ce0073d551bc3f89fcca2.nq.gz
│   ├── 82db841e13c043f1d16f7bf914c34c27db280863.nq.gz
│   ├── 87a02a79e52a806e5eb9900ffd1ad156f49dc230.nq.gz
│   ├── 8857958fd1c4d9b2eafb1b0b80c42c79e45d62bb.nq.gz
│   ├── 8abcff614cff1f90a49e8f8e3bda9da74eb4cc50.nq.gz
│   ├── 8b1aab7cb054743aed3291b6f3937ffc0fb02b42.nq.gz
│   ├── 8edac1ed07484cd577b6644ccd4d68b17224d822.nq.gz
│   ├── 92c44ef2997da797af28a4f42f91c6eca278ff19.nq.gz
│   ├── 9576354b1d9c5e136ebb5047caa8497c5e188f4f.nq.gz
│   ├── 9a863b2d34b94eb6c91b228d9a8375ea2383a66e.nq.gz
│   ├── 9cbf2a5823d2e4ccc028ff358ec9ada86f5a89c5.nq.gz
│   ├── 9d5c558c9abc159c8acf7f452972576a90c1a070.nq.gz
│   ├── 9f971cdbf8c453c0d3f18ec0feec8dc4694872bd.nq.gz
│   ├── a056afd2385bac8e5f7d74e2f7ab21cf38255e6f.nq.gz
│   ├── a2d164a51f238ac351830806b650219007646f24.nq.gz
│   ├── a307c0416a231fff5708192ababe3b40cefe60c3.nq.gz
│   ├── a5021c60e36ae085d1ef96c1fed9d88c2f65dd53.nq.gz
│   ├── a5122dd4389f569f724650a34213ac1f9a8f724a.nq.gz
│   ├── a53b856e80e129fffe276f7b2abcdb3f709c1414.nq.gz
│   ├── a71296310a6bac91d8d10fe55d041cfa75e2b6ab.nq.gz
│   ├── ad2b6788e56a863788c90e8686741cfa987aadda.nq.gz
│   ├── ad8b0525511f8826ec555ac49cbb48440b52d338.nq.gz
│   ├── ade98a624ee54a4cc896375010824d45c8e5c606.nq.gz
│   ├── aea2bc26408152b8ffd3773a9aed3717f8f70c29.nq.gz
│   ├── aff71ed3ed1f2324b064ff915bde3ff333cc72d9.nq.gz
│   ├── b39ad0059081a708b2aaf1a82d3d9c42d508316d.nq.gz
│   ├── b6a25adb0477c27796518465404205bb94c59b51.nq.gz
│   ├── b7ddf49b6e5358495c7b714257ab4c9b8bf06ff2.nq.gz
│   ├── b90feb62067be872f0eecf3eb8a552097a52ce29.nq.gz
│   ├── baa44d717a65a4a1051f3312d7ed76b62deae755.nq.gz
│   ├── bb7dfbff1ff8d580f7ef3671b01f3286cfe63787.nq.gz
│   ├── bc7e42f1f12da13e5dd28a10e13c44c8ab085f36.nq.gz
│   ├── bf63a8fd421703927dd706cc53ee99414d2d213d.nq.gz
│   ├── bf88e7d2f01dfa851d25a6c7fb71acfe778df8ad.nq.gz
│   ├── c1dd17957c951e0a0a9f69d0e4d8383030d21cfa.nq.gz
│   ├── c229b5aaaf17994d450d8b6e97c26e8254f31324.nq.gz
│   ├── c486cfb4bfbcd572d5370fff2b9c0dbd2c0c657e.nq.gz
│   ├── c5a0be9f198b720243222b14781c14cdc6170d9d.nq.gz
│   ├── c7ada5ba5433e03b2a757975e3d1dc23f1dde8ad.nq.gz
│   ├── c7ecc858a415804062b3f203120ffb5bb9908576.nq.gz
│   ├── c85dbcee146556c1b94d87dfd19d1e20d9db74f0.nq.gz
│   ├── c99ef993cf23c0be2bc244d6e8e373993f4e0c48.nq.gz
│   ├── c9c32df40ada4db6b0a286beeb70df7d6ed88ba5.nq.gz
│   ├── cac3501fd7863541ddff8d2aac39d67de53f768a.nq.gz
│   ├── cbf377fed044fe5564eded40d0e5b11d570bd4fb.nq.gz
│   ├── ce421251a9d118a5827c4cc9583abfdea97b5939.nq.gz
│   ├── cf62a8382b4fb9dae3cc1fb5c2b002042c1e13eb.nq.gz
│   ├── cffe69c9e9c7edc5f404e0fb43a224b95ed4c7e4.nq.gz
│   ├── d266a04d575d63d2e3681f39a75f527d58840fcf.nq.gz
│   ├── d49b903c08a15f2c1a46c5914709e54fc851dc5e.nq.gz
│   ├── d54e8cf6883ad760c62eb2d8a71e5baddee42550.nq.gz
│   ├── d7cde5acc03fd46e49ced09b5f4ea4b01f0556cf.nq.gz
│   ├── d9b03d0d1c72a469a92489455d05cd0fbb42e52b.nq.gz
│   ├── d9ff6080a5a860e419219d54ff4ab0f5fcf9bad3.nq.gz
│   ├── da44395951375cb4bdc56be0efa20fc65e72959e.nq.gz
│   ├── da70e3ac0216a8e8fbdcd6a7217f18c3044368f5.nq.gz
│   ├── e3c67104e376a010d9687cd5eaacf0512d9bbd98.nq.gz
│   ├── e68e54609f4994cf5e116828d04762fc63008ee0.nq.gz
│   ├── e692adf1b770bfc2148abc8e1e45d203dbcadd93.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ef7de77482246ca5993941b14d1b9b39a445dd.nq.gz
│   ├── eaf793fd25dbd99a0193212d8f5199ddd9d190d9.nq.gz
│   ├── ed97262f6f2112efe871eb11d043365cf4430027.nq.gz
│   ├── f028c09efa3a2e130ddd1f214764a93dacaa63fd.nq.gz
│   ├── f05364146e859664361370ae20b6eff55c8abfcd.nq.gz
│   ├── f22bfebdc1bebedaf15b4ac016232278071de261.nq.gz
│   ├── f28c77864f715ba3346932b49871550637547e6e.nq.gz
│   ├── f435f2f5d39aaa9be3ef30682c33c9463970f8ed.nq.gz
│   ├── f572a5e9717b1f7c5e9ced71fe1aff8f1bc6cf81.nq.gz
│   ├── f5a52af71c2e99c2dec366f82deccac9eb6f5dbb.nq.gz
│   ├── f5b5a8cabf8dfc0bbc06fe5efb413c169b5a76e6.nq.gz
│   ├── f5ccd76e3a64826b99f19bbbc71e3ff734280ec1.nq.gz
│   ├── f8622741d874105ed79c79767779dd4049c5f154.nq.gz
│   ├── f96e9b2bfe59f711054f34d39c64941ea8bf53a5.nq.gz
│   ├── fd38e6b5099b37d8f0063c9cbef58f941f1fcf1f.nq.gz
│   ├── fd82c4b07eb36a37f23220a75dc8d0320ff90c6b.nq.gz
│   ├── fe643ebc638dfc94f1149528d0e9a91ce52dc353.nq.gz
│   └── fe7a8920caf62355b70430280731ec7609e55ad8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 28c6e5779f2b76d55474914607291a3821502000.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 134 files
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

[construct/construct](https://github.com/construct/construct)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
