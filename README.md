# Repolex Knowledge Graph of graphql-python/graphql-core

RDF knowledge graph data for [graphql-python/graphql-core](https://github.com/graphql-python/graphql-core), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphql-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d913a6106ffe2e459b91dce97f225d15723aa81d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d913a6106ffe2e459b91dce97f225d15723aa81d
│           └── chunk-001.nq.gz
└── blob
    ├── 008836040e67498bc65f41ca02274e31b775bfd1.nq.gz
    ├── 014a2e96060e8064f6821829f7789d09eb4a759e.nq.gz
    ├── 01f30fbeade09b1d8d8c169c2d0338b6fe6b4168.nq.gz
    ├── 02093eb2ccb6eb24402cd83de07a9d0b3b8ab834.nq.gz
    ├── 02141bc3883a40336df33c40caae8a6e1ceee740.nq.gz
    ├── 0246434f98b60114b2e65504345bf88f7cc85118.nq.gz
    ├── 03f1ddc8acd661c66b69237835e3238e0817268e.nq.gz
    ├── 0442ef384b4c35bbe799ef2986c1e2e55e35116f.nq.gz
    ├── 04a3be08065cd0073c7feac26d7df24670d3ecc7.nq.gz
    ├── 05299053f815b80911ea52e3424de53b8ea6cc4e.nq.gz
    ├── 056a78d18e2d548ed3ecbb411e6549df3985115a.nq.gz
    ├── 0689dbd4aa05c820d5c25321f9976771bb45adfb.nq.gz
    ├── 06b674ede41cb3789e83a90380837a2c76dc3d8f.nq.gz
    ├── 06bfac6f604ffaa37c14a651919ecc2110a24ac9.nq.gz
    ├── 0792ffbc69f100dc28e90133dfac9e58e4f964ee.nq.gz
    ├── 07c673876d52d378876f906d3a813316b6bd9374.nq.gz
    ├── 087888257fbe3de02d9dca48d0a21c3593bda1b3.nq.gz
    ├── 089f8eeb91426c333b2b38de9eb3a6178b9b704d.nq.gz
    ├── 09567645460f4b193a48a9f22502796cb2b1a18b.nq.gz
    ├── 0b0a67a23e0a748bf09c0c70a8b2cc35314ef18b.nq.gz
    ├── 0b2cd0952bf772a99bb2296f4709399cc81a627e.nq.gz
    ├── 0bf5f7f4fa99dd6a2d5bbb043cf4f640bdf43852.nq.gz
    ├── 0bfa1f5e7c2aac9c59d674d2e878f163c29691a4.nq.gz
    ├── 0c215da19d51c773886b571e5b4b108f32b89d78.nq.gz
    ├── 0c47ff67c2bef73f48b129c60daea3cd24b82cc6.nq.gz
    ├── 0c6ca97ce2893653c50fcb5516811d55b8c47d0a.nq.gz
    ├── 0c71e80ca3054b90983feaf0c18d6a6287567e79.nq.gz
    ├── 0cadce37c32dd4a735b627bebd5f1b94300fa908.nq.gz
    ├── 0e17b4d4d1fe4ea1444b1664b8c4610f21bab2a8.nq.gz
    ├── 0e910bbd4c913c69c8e5f513b8a0620a754794ec.nq.gz
    ├── 0ebfe1100ce8a0fd5cdb94c445ba96cc66690adc.nq.gz
    ├── 100239ba345f6ab0089ac4813d61f52e98199ba5.nq.gz
    ├── 10fc411d6b76053649b0eb11152656aa108d0d15.nq.gz
    ├── 11ae4b15905aa1a028046da4f70cd087298670e4.nq.gz
    ├── 11af8aff9593dd10e8db57761ede332583fdf9b0.nq.gz
    ├── 1210795ad5164434f3be714bf9fabb8565223c47.nq.gz
    ├── 125be39d127f0bf7abeb0decfecca3ee0bb1fe22.nq.gz
    ├── 12d185358eb8e9536f1f2cfadecf7dcdbf01d530.nq.gz
    ├── 133ab58d447e6bc6f821cf2ccdf25b6450bd5083.nq.gz
    ├── 13dcc7ac716465127eb0061f2ad2376da0e406b3.nq.gz
    ├── 140de9e12603c20bc81c81ff847d7c7d26b146cf.nq.gz
    ├── 1479b2cf291ce1dc1a4a66e37a424488ae398bb7.nq.gz
    ├── 147ccca9fbb933d69f8665c0543fa38070af895c.nq.gz
    ├── 16d66bbccfc09869566f5f8ebdcf77af1d92d9f5.nq.gz
    ├── 191b604f0555b2667013da916497021140b1cb30.nq.gz
    ├── 1a13936b64ecd6a4eb7688a5aa448c711feccbef.nq.gz
    ├── 1ac8bc5df30d28b3988f676db22573209a8db7eb.nq.gz
    ├── 1c8ad24c6be0871fe064cb4b1c796d1e9a5baf34.nq.gz
    ├── 1cb594b880a9665e4c48a0cebab7353600df58b5.nq.gz
    ├── 1cb9dc58749097aa93549add9180218eaa349782.nq.gz
    ├── 1e82b4e27fe13e9a01ec8301e89d246915c30069.nq.gz
    ├── 1fcdd59f3d4b9fe07876b8944b12d7dc0c23f8ef.nq.gz
    ├── 1ff03b8f2996b92c2966f8f3657d8abf67993a2f.nq.gz
    ├── 2161c5e40e81f0e0767ba623cabe16ee15a9c918.nq.gz
    ├── 216ba3c5aaaf37937aff0030c23143afa9b2a336.nq.gz
    ├── 218c0d6deaf5fac82fc19c5913c194f3ca0138a6.nq.gz
    ├── 219729acf9a2b55e9397c39dcf6976a0f76d15ef.nq.gz
    ├── 2256b8d4a215b0d61421f73dca6dc175c66f1bea.nq.gz
    ├── 2274e750245bfd4227cfd24b1967c2ee58077e71.nq.gz
    ├── 22cae2cd6e4d7dbad3511822261dcfabea22111a.nq.gz
    ├── 23690a1570d38f228b705be3a48d26402d4bdd62.nq.gz
    ├── 251f75fe1c82c900ef922e4ffd364b417c5bd029.nq.gz
    ├── 2547fd7048b258e1dbbda67974971ad8e6a73ed3.nq.gz
    ├── 27afabdfb40389e4c188171fac5dd6c6b22727fb.nq.gz
    ├── 27b4e74d7204515c3da227e11a9a3de0cbbc1f6e.nq.gz
    ├── 28a21cd1aab1d97db1e4dbb22394d87f3798c49d.nq.gz
    ├── 29394adfaec84e436d26112dfa339a35ce6d94d4.nq.gz
    ├── 29878a63cadff57bc3ee365baa41f90bd732c2c8.nq.gz
    ├── 29c5e0c047830e7d52dea6a2918102cae7e36b9a.nq.gz
    ├── 2ad9325874c03ecc5439f24cbaa091a63f9125e3.nq.gz
    ├── 2d6c87668803ca3576b93314dbaad4372c95c2a8.nq.gz
    ├── 2edc2068b209af0211f6f9865cb52bab83135399.nq.gz
    ├── 2f276099afba72ca00e7e2621b8d467dd226f1b1.nq.gz
    ├── 2f68b2ee29b70df47af96a106cb5f594210b826d.nq.gz
    ├── 2fac158cc4d08532929ac4f3e694a44cd5e7e294.nq.gz
    ├── 308df393ae9b75cf0116463999826681d406940b.nq.gz
    ├── 325380a3cc5788df84892328340d9f399c335081.nq.gz
    ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
    ├── 3336ef05738e16ccb75c7f01d67bfeab0b7641be.nq.gz
    ├── 340a667558d8805dbc2695d2456c6d533e394f31.nq.gz
    ├── 349a8db97353e8a9dbedaa2792d927fbed895f26.nq.gz
    ├── 349f84f71cd14dd0fc6c9c02341421c73bf5bddd.nq.gz
    ├── 354cfe74bbaa2c0bc10bdaacedeb1b9fbfc4e458.nq.gz
    ├── 35771879f47acb5deb633490700b2d74080b1c95.nq.gz
    ├── 35e42852ead556738d0a9ddede45a0e772997341.nq.gz
    ├── 361c5e2cdb9f49eaf07f3925936075969f6841ef.nq.gz
    ├── 36ac493baebabec315cb1e98853369dd524eac3f.nq.gz
    ├── 37149dc0a6211d6d1cad62eec2f2081acd7fc5de.nq.gz
    ├── 37254d735a59416427a9bf2d4d48677298b9c55f.nq.gz
    ├── 37370c9d3390254204a79af55b0c76b1c070a3b0.nq.gz
    ├── 377775ced38ea5f9a3998d71bb282a23d12fe35e.nq.gz
    ├── 37b95f9be322224dd30811d13b29fd2ea50b6c1c.nq.gz
    ├── 388c2533aa32f7057c02814a7b0b4099356ecbe8.nq.gz
    ├── 39aad3ed967db0e25ef869ae679fd1f1e291d696.nq.gz
    ├── 3ab09e053c7138c4cbc50f5e60e7be52f8646867.nq.gz
    ├── 3ae9d19df2f933a70c309255b5954e8a046adf57.nq.gz
    ├── 3b0e1dd1aaa11e73a783c42f76ed51f287b8e01e.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bc60a0ab54eb891a48439d26aa330d0058d84b3.nq.gz
    ├── 3cf46ec58f94c0849b675778e4f6531e4188f54e.nq.gz
    ├── 3d2fe46ff4d01af0f0aa0663400d09db1eb6616b.nq.gz
    ├── 3ecfd9b271976fc8c9887d6a8bcb6e8339dacfa8.nq.gz
    ├── 3f130f0bedbd8618652da09d54d164dd48ddbeee.nq.gz
    ├── 4044d3081f851309203e397ff7895050c27919d2.nq.gz
    ├── 40c0821d5cd34e48454116c4017c7e98fc49c482.nq.gz
    ├── 40e5166f52bf429ef66fd66985042e39fe3aec9b.nq.gz
    ├── 40fbb3ce6ad36a7273e49d017ab1414b450ea5a3.nq.gz
    ├── 4133bc6b9aa58175f71b57d7eebead921c170c9c.nq.gz
    ├── 41e37f05bea3d18b9d5fdb637d1e8f4b066f44dd.nq.gz
    ├── 421a22ff77bf115f4da269ba9f12efc900018366.nq.gz
    ├── 42b1ec34c7607b99659ac10d30329688711c0abf.nq.gz
    ├── 42b2af11d1c036ff57fe5cb83aebd1067be8b8a0.nq.gz
    ├── 4371979b7b4b0ef0ce4a8d793c4393bfcba2ae17.nq.gz
    ├── 43e6341cecaf062343e4f5b3a2c020b926042e6e.nq.gz
    ├── 4416d64acc478c1dd9e5845b6135420443037e83.nq.gz
    ├── 44693f216d9abfae029b68b3cd346b266cc9e34c.nq.gz
    ├── 456c89d266d9e9224199dc702268199dbbf7aea9.nq.gz
    ├── 46b33433f5902e2da2940756aad1814462a623c4.nq.gz
    ├── 46b3497dc250917a7e8feaf609aa800793a2f26b.nq.gz
    ├── 4704daba3d2b02aaf4fa155f3d2922923a9e088a.nq.gz
    ├── 473e0c881cd3ea67cf86f9a12017952b52600baa.nq.gz
    ├── 47433cc215c27eff69e1729acd7173335fae9a4d.nq.gz
    ├── 49dad199be0ceabda18c75d3d111d0651a5f02b7.nq.gz
    ├── 4a21c63b65e4397cb38e995fa01b69400852109f.nq.gz
    ├── 4b0dc1c9404744ff384bfb72e7894bd17c3bff3e.nq.gz
    ├── 4b211e27e5efe2d020954eca5521a1dcab7165ab.nq.gz
    ├── 4ba77acb6e5ae2cce2028caace4bc09e2847c708.nq.gz
    ├── 4c276e07fc9285388c654e779a5bd83976b570d4.nq.gz
    ├── 4c30d96596b4f7557e4a86de0095f55a0d01251a.nq.gz
    ├── 4d1835101e49c4ddc6f6697e786fffdcbb07e5ef.nq.gz
    ├── 4d3af98374196172dff3573defeea23ea1f91b57.nq.gz
    ├── 4d7645626c177c2e495712f6e54b77d312095b19.nq.gz
    ├── 4e7a85a2d5e9230ac9f1fa2062624076ca6ad3de.nq.gz
    ├── 4e9199f33c1ff2fa43174c6846a0c04ecdf89466.nq.gz
    ├── 4e9326784cbc6f61545add136214d870c2c67bf7.nq.gz
    ├── 4fbddb8ceca95429c056befc33853c5686669a6b.nq.gz
    ├── 4fe3f9985956157830a51ab5b25bdd36c00c32df.nq.gz
    ├── 5012202625ed555651c74d5676ed0c0171928baf.nq.gz
    ├── 50250e710781d2a57e23d099d3fb8ea3edbadf15.nq.gz
    ├── 503705eeadc1e5f55fd9aa7fc8a1712d6c37632d.nq.gz
    ├── 50df3a08bb2fc046ac8d24f995f4333887f25be9.nq.gz
    ├── 51a899e7a2c371f83efa66325155ce1ef4bf249f.nq.gz
    ├── 520fa2f85e3b82b3d8a00400a661c17f5c97ec02.nq.gz
    ├── 53cfde0ff92d52a4ed94f968627417e4226d625a.nq.gz
    ├── 5445ccb7761166d96bb302eca5c8d3bf30cb2262.nq.gz
    ├── 554bff028803d2d26e0483a6c51928c8a3dd2d3f.nq.gz
    ├── 5611b45c1375a6fd67fcd4dc780e0fb96e164faa.nq.gz
    ├── 567b5948e3f9d906168c3434628254d9b30acfef.nq.gz
    ├── 56aace03e73f27ad51c7df2a8de419c212329d44.nq.gz
    ├── 57ebf703aa9fd3fe42a195b89ada4e45b8320be9.nq.gz
    ├── 5a027846264bf5c7d74caf6c4d5e0e7a7edfb6eb.nq.gz
    ├── 5aab56eae1ecc55b34fc6ebea19f7d703ef01abf.nq.gz
    ├── 5b7197173abdf07440a7f7fd083138047a82af0c.nq.gz
    ├── 5b9b5b8ca5aecec13a5b5ac3c00bda58cd367c7a.nq.gz
    ├── 5bae1b0baad51ba91f1f64a02690171f31479ed8.nq.gz
    ├── 5c7b21b0365cf7a402015c006815defe36f491bf.nq.gz
    ├── 5cb20c5a9b4c27f504723944c8feec92f9f463be.nq.gz
    ├── 5d87057680ebf1f371ba7686451f5b24f117f37c.nq.gz
    ├── 5e9b1c216b0d434141ffcac293354321e6a68d37.nq.gz
    ├── 5ec97db1af5961d396315c6bf4fc0a350ba64135.nq.gz
    ├── 5fbe1f064c413e08ec394d382eed79bcfa643f9c.nq.gz
    ├── 5fd8fdd1207912f7c4de37f8fb7e8991e5917b6b.nq.gz
    ├── 60756f2747ed49d7adbd2e4a300bb727cf10e99c.nq.gz
    ├── 62fe89e3b7f9a6fa1dbe77ee56f7731b2449c4cd.nq.gz
    ├── 631d47e713e416d3e7b083f7c2bd12e9b71c4cea.nq.gz
    ├── 64aa2b952dad40f871eaf62fe845e612d73887c9.nq.gz
    ├── 66805874a0dd98283a50469b3c54d300adc6e156.nq.gz
    ├── 6bdf0e757d3e4db7fcceb0df95499bd02056077f.nq.gz
    ├── 6c4c33db8b9fd748110fb6563bab7ff5a427d5d8.nq.gz
    ├── 6c7966bc99b3316e83d598649aac0ebe5225992e.nq.gz
    ├── 6f0326b9d46803f3c8e05a1447e527867622dbb9.nq.gz
    ├── 70849608fcac6450a8346e9d2a33d58cf468cccb.nq.gz
    ├── 70de87293b565945817e51b468691218247f3c08.nq.gz
    ├── 716c649ff472d68f6088535ecf48cda8ed60af39.nq.gz
    ├── 7278dc73ec314e660cbac9b925fadec161c9181f.nq.gz
    ├── 7352a87fa38804531b2cddba2e8bde1e9b3766b8.nq.gz
    ├── 73d58ff54c2b976a45468ad05f84574030910bf4.nq.gz
    ├── 74910714964a7238827313f0ab9d067ec89c0c94.nq.gz
    ├── 74a51d1d8d44d9b5075a99e8cea0507af7c3a20a.nq.gz
    ├── 7646a7da6a748418575c8dafc4709367ac7e8ef1.nq.gz
    ├── 7675a71570a32810963d628c6fe40b29f2888718.nq.gz
    ├── 76b359a9bcb29ca4d94b9167467f85e842b2c64d.nq.gz
    ├── 77ae052f7f6df3af574f5c0ed03fca50b6b1f25b.nq.gz
    ├── 7874768302816b390769261b1b072b6cbd007a3c.nq.gz
    ├── 78a746e3604279eb6363bda741fb26d0dbbb9f30.nq.gz
    ├── 791edfc157068ba3d6a33d0d7578a4985d903dc0.nq.gz
    ├── 79a4f4ffb70a93b4e7598bad9b6a0b7b05ff649f.nq.gz
    ├── 79bd3ef86a7f4dcfc4ae8ac29bd8277c74a21f74.nq.gz
    ├── 7ae55bdf874941c50e8eed325acff35b7723ed3d.nq.gz
    ├── 7ae78ea9c9da6635adf58ad3acd8cdd70f161c8b.nq.gz
    ├── 7b33c7457f2bf7e419a9d8b2eba5aa6df91b08f0.nq.gz
    ├── 7ce4f0815d83043f2e2bd3639193b4e9dd29b877.nq.gz
    ├── 7d48fc4298664b0a00f90117540f525ecf577665.nq.gz
    ├── 7e0c69ad408bb176904b24e37a1964ea7dd142ff.nq.gz
    ├── 7f05d10da21e6a43c445069dbed2652394967c87.nq.gz
    ├── 801ea9d1355d92962eec8219f524886254d5b107.nq.gz
    ├── 81102c2d2d4c9835ce178b8710261804207126e7.nq.gz
    └── 8158013c69e28ab66bc50f341529b3afd412a7bf.nq.gz

7 directories, 200 files
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

[graphql-python/graphql-core](https://github.com/graphql-python/graphql-core)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
