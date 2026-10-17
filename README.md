# Repolex Knowledge Graph of mongodb/motor

RDF knowledge graph data for [mongodb/motor](https://github.com/mongodb/motor), parsed by [repolex](https://repolex.ai).

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
rlex download mongodb/motor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 60f645614eb35d99e6934ce2a8fe7356a8c4deac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 60f645614eb35d99e6934ce2a8fe7356a8c4deac
│           └── chunk-001.nq.gz
├── blob
│   ├── 0477541cc4eb1bfa59b140956fb6a930aa0853d4.nq.gz
│   ├── 06550316f58474d5304d52f883cdfb238c5c0c64.nq.gz
│   ├── 066e77a447dd6c3ed2ba9facc1230ffc3ad9e310.nq.gz
│   ├── 08cc794309403c98c46e88612d541784efe2861e.nq.gz
│   ├── 0e10ac2cd110be1a83adba4942fd9cf9b75b7137.nq.gz
│   ├── 0f1517f92024e1210cec12961fa9ba5983612194.nq.gz
│   ├── 0f4057061a763b445a4300825a450069a96f5719.nq.gz
│   ├── 113bcb2f4dab53f7d1f1cec14d1928958dce0c3d.nq.gz
│   ├── 11d0100e48caa81d3cf389a8724ed1522adc2364.nq.gz
│   ├── 125ff9ba171b016a6438755da0fd40b0e79982bc.nq.gz
│   ├── 1881e76d79812b4c333df882a4ce393dc81e6362.nq.gz
│   ├── 1d79573d4b88e5f13cc54f9dbaaeae19f558c83f.nq.gz
│   ├── 1ea4f7ab8e5a2e24e160a9768a14f896db3ffaee.nq.gz
│   ├── 2061f59f01e80a1917e0865aaac9421cdbe06268.nq.gz
│   ├── 206e9730074c1ec5205000254a30025ee1239403.nq.gz
│   ├── 225d07b70bfb38122245e1c85e4ed2eed6e5fde2.nq.gz
│   ├── 24beea2d48a94ad3aa4057ed2bd83dfbfbcef12d.nq.gz
│   ├── 25e104bfca6e6278dd420e64b6eca5c68c9c811c.nq.gz
│   ├── 25f0fd9e227e7c69766b985c712fdfc574018777.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 280d0d7ca7f1d8e703f5dba6347e4c8d8205167f.nq.gz
│   ├── 28bd3d422572b5309df4e4ba2042c3355b7e5d92.nq.gz
│   ├── 29451eb2a7b8a4162b7c609a4efcff47e87cdc8e.nq.gz
│   ├── 2987f3e826f622b2e39f237ed689a3437bb64f36.nq.gz
│   ├── 2e8bb32358aac14212c8d42fffc1868bdf9e1aa3.nq.gz
│   ├── 2f719c21774b727f41ea24346412f5735b5a1541.nq.gz
│   ├── 321e4a761fa4e5ec22d7be065ce0e436f1139daa.nq.gz
│   ├── 32dca63b07cbb09a9437e4a5d16f2ba6beabc657.nq.gz
│   ├── 3868e0da619ac93d1e650ab8ee85c4a5b84b1a98.nq.gz
│   ├── 38e5e3d474dc7f0b0bb37cc524af80da2faf491b.nq.gz
│   ├── 3c961aa59aa6aa76a324ccef5a7ecb4fb33432c4.nq.gz
│   ├── 3ce8de373c6b0b08a5d7facb07e771b517a9b748.nq.gz
│   ├── 3d612d7081971defe1ff49be69b943a65e0e9500.nq.gz
│   ├── 3ec3075034a235c79b473a0ebe664b47438c9359.nq.gz
│   ├── 3f4960e9c75cee29401f2e2c5a216679359e03c2.nq.gz
│   ├── 3f4a92b4bc6f2eb489f91d6655a2ce06a512b1b2.nq.gz
│   ├── 420a40d437339b5c73c0664008d7f03db7e8b381.nq.gz
│   ├── 4242b01c70e5c85cc5d1a48a9327d2298f9fa445.nq.gz
│   ├── 449dceba695b79f1c2ff3389172438351652c3aa.nq.gz
│   ├── 48574aead9ae405f825dd997ffae3d842fda914e.nq.gz
│   ├── 48a3862db5e0817f317ef1afb5b9f66189391a23.nq.gz
│   ├── 49dec304fd81e05707bbc0b6ed91f185635ab348.nq.gz
│   ├── 4a6c09b921c16b7bab24b66f2feb9fba06033ef3.nq.gz
│   ├── 4abea09353363a0e9c2510b29a150971a0244e4d.nq.gz
│   ├── 4dec588be673ea26c0d5fd79450b41543a508ba9.nq.gz
│   ├── 4e5d441b14a3aeb98efd7c18e9069ffe3f27b372.nq.gz
│   ├── 4f6c3142f3d8f96ebd5c2504089522491d11abcb.nq.gz
│   ├── 5041422465297e865f3f99e2a2ee15e8e3e32d9c.nq.gz
│   ├── 5328847b36fcfbc3355a8d36403f43f087453cf1.nq.gz
│   ├── 539a914d5a388107a4e1ecc8dce2b2cf9c30700e.nq.gz
│   ├── 564330ef5117588907cd70782689231e27e69035.nq.gz
│   ├── 59a62f27a133feab36cf7d4828d7f917dbd1ce5f.nq.gz
│   ├── 5b070010920d3159a2b4eb1bed834508fb799fde.nq.gz
│   ├── 5bf500ba12f47aa20bb160286e8a07c5e8586342.nq.gz
│   ├── 5d0d8759d4fd62172c38a8205c172f6097f166be.nq.gz
│   ├── 5d75850e448c3af130d5f7c792f2de2dd7cfb7ea.nq.gz
│   ├── 61396a25b221c5332e3942c174fa152b7252146f.nq.gz
│   ├── 61825fd6698fffa3e39f9dda8d9d70975f6a0e14.nq.gz
│   ├── 62d220b97c36222348c1471037a570cbc838e120.nq.gz
│   ├── 64bffad83a03f31d193043beff47c9a71313970f.nq.gz
│   ├── 64cdebc22ba7ee6a1f69049a4ec15ff0a5eee5f1.nq.gz
│   ├── 673469b846e7dd866cfc82700807df549d44432c.nq.gz
│   ├── 692107a6c053ccc59e80214ce36782606ee360d6.nq.gz
│   ├── 6bd2533284b353a9f101c8d4f08dce0c6de57612.nq.gz
│   ├── 6d220f3164991ecf5a10673f9afe5c8681d82668.nq.gz
│   ├── 7003c9e047c6910822336367fb9668ce9c9b1f28.nq.gz
│   ├── 705f329f3a2a2dfde1f9e6567c38c935b77b338d.nq.gz
│   ├── 70b15da5eaa77093f7804551fe5bb25b4f67e8e1.nq.gz
│   ├── 72deed7513382a365f9dfc83ed9fe7085d16ddcd.nq.gz
│   ├── 72f4a440dcdc851c0879af18ff800addef2f4be7.nq.gz
│   ├── 7447cca84e95c3253d44e8d1ff457dcc4373b886.nq.gz
│   ├── 7458b67d018a170e40843226f644416a7ab7ba2a.nq.gz
│   ├── 7480f9644763eff444e0490bf78bdc342213c7b8.nq.gz
│   ├── 75270c707cf825c4ab24d013c6830ce3d9488ce2.nq.gz
│   ├── 75347492ff36861e19c3bfc4663a74862524f68b.nq.gz
│   ├── 75d5b34ab34eacd5708814668a5a45079db4f155.nq.gz
│   ├── 77204e239da7260dae5d5ac1752ddb0cdd3ae7e1.nq.gz
│   ├── 77a72c2a7c4a482eaba9f41a5be815c5db557385.nq.gz
│   ├── 77dd7f3c05b90a940973edf44acca7b4910836e2.nq.gz
│   ├── 77f864c3b39bab265f86d393e6b44a3aa6308aa9.nq.gz
│   ├── 785f5b60f9a77e7c4d47b73715999598a2aba01e.nq.gz
│   ├── 7a37c52eb443dbb14650fca379f6427135bf3f78.nq.gz
│   ├── 7a978316b9656a4151232fad799890ff8019572c.nq.gz
│   ├── 7b842f4e1d84216f0f1001ff5b972bcfc9ae7bbd.nq.gz
│   ├── 7d1d696e719bf30aedeafbb646d4f96b1a73b632.nq.gz
│   ├── 7d96d83757dc0f1656dc4926d2f5f9572affd990.nq.gz
│   ├── 7fe552a928e1d0de6ec0e5a1559e6d0ebaa2b93c.nq.gz
│   ├── 81950b1fc80d360f5396d6dde92403584745e4da.nq.gz
│   ├── 854032f05454c02a3e58793ef85cbe6453ffcae9.nq.gz
│   ├── 867d7ffc924cf78df6c78ac005ca2098ad9791a8.nq.gz
│   ├── 87985a0fe0b94ed1ff1c53e1966f6f33f8ff5161.nq.gz
│   ├── 89c0aeef50364d05a82ac9a1abf28ce9ef5b5f0f.nq.gz
│   ├── 8b1b7b83ed8be2fd7eddfe8bf771caf0ea70f2ee.nq.gz
│   ├── 8b3657eba3c06b7e2da2d5116cc546dc0d313bef.nq.gz
│   ├── 8d8df1c659471e0de7849d32d0a125601adff7b0.nq.gz
│   ├── 8dd6abd4a7c836bc811178877982e1c4b7639462.nq.gz
│   ├── 8ea4aeb9e4789853c114e218643d5a6b3dc0d89b.nq.gz
│   ├── 9162926524b4d25d8f9a7f543fc7e67752fb66de.nq.gz
│   ├── 9177d1c16a8aaba8fdf22757abd1e7eda008e3f5.nq.gz
│   ├── 94fa9c2cd8f973a6570f005f4be828ba92d62c51.nq.gz
│   ├── 99caf60b09d522db66d9f9d26bc561a31284eca9.nq.gz
│   ├── 9bdbd1c7851628a86584088b0126204eae20398c.nq.gz
│   ├── 9e1afefbe9ace8596663672b9e12ffd203ff2729.nq.gz
│   ├── 9e38ee71b518b244af0c5870fa74c81107a15af3.nq.gz
│   ├── a0f80b830803e44a889ec82447fe850d8a59cf42.nq.gz
│   ├── a1143ed15f0005dc7f50f32baefaaac957ea65d4.nq.gz
│   ├── a484847e29c898a406ec5ac98d96156b8dc5d863.nq.gz
│   ├── a574d6753c2be87ce65d33313277ca8869624c62.nq.gz
│   ├── a6a655c1646b59641b9dc6059a8779ba71d55d05.nq.gz
│   ├── a8665766104b9bab22cc9714d59f7362acf498d5.nq.gz
│   ├── aa42445c8013e90dd98eebbe14dac8a8a987904f.nq.gz
│   ├── ad3a87226080b82b37dca36cf5aa7468dcb09cf2.nq.gz
│   ├── b0dddc6557d5dcc9ccd076d8f284cdf2cd352e1b.nq.gz
│   ├── b216739e368f28a3762d9a2783af9868af173d1d.nq.gz
│   ├── b26049d47083942e0111a37207337aacbc015376.nq.gz
│   ├── b3b4fc123f9ded388b2c9aecd92ad3d33ed3bfc7.nq.gz
│   ├── b472608071feb2a7782abc647cb814ebd045d06f.nq.gz
│   ├── b5474d1deb4999a038d7de068ef1ce774f585383.nq.gz
│   ├── b5f2f65c715db56d31fea501c2c6f9357fdfe373.nq.gz
│   ├── b8f8e88d655a7840acf3fedf5db07dacdea4b102.nq.gz
│   ├── c014897cb8b2119f7f221b266f512b36948a0927.nq.gz
│   ├── c1560326b12507943d128910a761eefe9a5c6f79.nq.gz
│   ├── c2fd9cc67c89ca4c6977c82efe5691900e4de119.nq.gz
│   ├── c6f532351d4ef00dcff8571dabd931cc43de161d.nq.gz
│   ├── c978d85b76016e74155d813b7cc66d8c14e28795.nq.gz
│   ├── cb09dc94e561b6d2e0418b7a03e419f805e6cabd.nq.gz
│   ├── cdda9558abadcdf2798a61b102d9a72109cd3b9e.nq.gz
│   ├── cf435a91c6886f61ce7921f6513c1a7c3ed03344.nq.gz
│   ├── d18293f9fe362e09ed232d14911ae01a4f3fe25f.nq.gz
│   ├── d18b89917713d3f03945c522f0f0332fd14ace2a.nq.gz
│   ├── d1ac539b75431d927cf494dfb35c3e4ab15bdade.nq.gz
│   ├── d43d1ec9e797644ddf778c84bced7de3d5daac1d.nq.gz
│   ├── d9cb1c0b39cff2913c517c40c8c973d1138d30db.nq.gz
│   ├── da787e388b14de711e2784818d0fb90475293ded.nq.gz
│   ├── db6c17679f3c0740160cc2813ac1c9a444625ab9.nq.gz
│   ├── dbf84794dcbd2b2218b9cc17726d83ff29708fa9.nq.gz
│   ├── dc708944db80639783f0e9683a1b4834a1fe08d3.nq.gz
│   ├── ddc1b37b75cdf9972a2820fd24939bd781024277.nq.gz
│   ├── ddc76a3dd0049a3dca14bfe9c53d4b486f4e0361.nq.gz
│   ├── df8779057ee1acfcd050cff3a2ff230b55abf53b.nq.gz
│   ├── e01e85facd1a25a1975e3fb8067f8575c108b720.nq.gz
│   ├── e1cf8b0ac15f6ed8492f853c54f7fc2bfb4064ec.nq.gz
│   ├── e21b87ddd3ce7f72b93b6a099b444f5186252f72.nq.gz
│   ├── e244d540698fb98c7f1e5cef84b9a882d123832d.nq.gz
│   ├── e47e553145a7567e6bc7bbe1bf6f77256c012355.nq.gz
│   ├── e66043107bfe1769605af5039f724eae35529847.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78d0663f67c4d32c2210d44920e57ef1583ad02.nq.gz
│   ├── e804770ffdd9b0aaca8b3fcfd34722a044efc9cc.nq.gz
│   ├── e8d58f4bfaac49d928fb10605e507f2d9e3cbd7b.nq.gz
│   ├── e938ee54489496df748e34817000e3887b6724f3.nq.gz
│   ├── e941ff8d8d113ae1f712d6aa7be3b61867863a64.nq.gz
│   ├── ec8a5e682a0fb79da191436d556e32c26a3cc44f.nq.gz
│   ├── ed2a04c4c49e02016f4e214474c044a13cf862f0.nq.gz
│   ├── f14045fed8f41825efdd98320a25ff92c8f145a4.nq.gz
│   ├── f223721b31ff02911f6073c74fd4bc2ebb9e8d56.nq.gz
│   ├── f3e380f6adfc5e86441cd95548ceac59b78c3284.nq.gz
│   ├── f618778fd683cd13c8cf9d544e23300058bc42b1.nq.gz
│   ├── f660ec94bc93296ace88cb10b31d5f7cae29a06d.nq.gz
│   ├── f6b48fe5744b13c83da864e67ef80c2510165ee5.nq.gz
│   ├── f76d4f70b1615bd3d5d35ccd763c38f6e27ac4cd.nq.gz
│   ├── fa89caa8c9a44947cadc6dc4312a48eeb1bdf890.nq.gz
│   ├── faca0ed9864165b7ab575ab90ac5ba60100b1456.nq.gz
│   ├── fbe4d45a87fb9a87d03804012312a76d661e6393.nq.gz
│   ├── fd34318058f532d3fce583134080fde65336a9ba.nq.gz
│   ├── fd371b552c42962a581142322fd8bafd0450264f.nq.gz
│   └── fedb841a05b75ce50cd1c087107d6f927c8c579a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 60f645614eb35d99e6934ce2a8fe7356a8c4deac.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 174 files
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

[mongodb/motor](https://github.com/mongodb/motor)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
