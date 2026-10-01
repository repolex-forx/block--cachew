# Repolex Knowledge Graph of block/cachew

RDF knowledge graph data for [block/cachew](https://github.com/block/cachew), parsed by [repolex](https://repolex.ai).

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
rlex download block/cachew
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57af02da05f1031d726168914ac6a9ed22cdd9fc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 57af02da05f1031d726168914ac6a9ed22cdd9fc.nq.gz
│   └── repolex
│       └── 57af02da05f1031d726168914ac6a9ed22cdd9fc
│           └── chunk-001.nq.gz
└── blob
    ├── 01147bcf697c986790b3e8295e79b7afb1d71ef1.nq.gz
    ├── 011d12d86559392c67ad665da100642f608dac3f.nq.gz
    ├── 026d6fd543b9533760aaae630f3dc0629e1932ae.nq.gz
    ├── 02b5f4d059bf83bf698ca000b4c08e7110abe4ec.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 050483e8b055b7c7f5a72015f61f7d43a42991b0.nq.gz
    ├── 0568c3adf6819f28eea728d811cfaa61c5075b20.nq.gz
    ├── 065b2e49eefd122d7cc75eed3c53f4fe10a37bdf.nq.gz
    ├── 07619000e68a9cc4af0e159dd3c7ed9c778f2163.nq.gz
    ├── 07ec4d7732d1df23a604a5f499f9315bbea269fc.nq.gz
    ├── 09e12ebfb1e311d3625a2541ee64147d5d7902e0.nq.gz
    ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
    ├── 0bc043fca470f77a65940b5e74d71461a7622730.nq.gz
    ├── 0fb0b8a491499861c3231b66bf8eae058f404e8d.nq.gz
    ├── 112fc14886908dd7fa7c345038c752af9f104cd7.nq.gz
    ├── 143b0f12d2086a3b02b84eed9bf89e07f625dc26.nq.gz
    ├── 14715e8a637bcf606b375f061ee59e63a68993ef.nq.gz
    ├── 15a35845d1e4ad535fb14f795a0130c01cba9fc6.nq.gz
    ├── 15f3d5e52d691d16e63374ca469237f96390ac97.nq.gz
    ├── 17cae74759495fdc28e55fdfe7e6a43379c4c4b0.nq.gz
    ├── 1a06b0a8f88edd096f97c4310c5cc4fe5a75009a.nq.gz
    ├── 1baa3bb8ddd084a98c0451fb38250b876477fbdd.nq.gz
    ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
    ├── 1f3a3d7f56261f1eba6eda1857e30f89b85c1e91.nq.gz
    ├── 1f94e5582d1d1f38ac6fa469c8e880f7520ea68a.nq.gz
    ├── 1fdd575391d3b3d5deae9b159297a5bde28717f2.nq.gz
    ├── 2193a429da9c2f1b51ec1c124f5aff007a13757c.nq.gz
    ├── 235d3c181c8415760fdd948762f30a6409b31866.nq.gz
    ├── 2398b6c71ac656940692885e5494d1065759a492.nq.gz
    ├── 23bd794b22f6c99592fa371e98e31726b2d8238f.nq.gz
    ├── 24a71b508ced09b9571e96a34f00b5f916643a09.nq.gz
    ├── 24c224b3a64b85b6b48d7b4e3371b84f0cfbd4f0.nq.gz
    ├── 257840ddf0b4a9497cb49d27f6a5077226286c60.nq.gz
    ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
    ├── 26ed89b46edb9ea0aca9859ba2d08aea6326f8d5.nq.gz
    ├── 27a870c1637de0cfbb3f7f116aac46d8c7f45030.nq.gz
    ├── 2bd08497bb0e6686b4eac9d86ec13abe6df3f668.nq.gz
    ├── 2c4ececa103d7dc0938b8aa7e41b8231ab6d8a97.nq.gz
    ├── 2dab2aebae802f153923074cb3ca6b42335bf5b6.nq.gz
    ├── 2dccdcb6a0923cfc1858ec79e010ee012ee54ca9.nq.gz
    ├── 2f3f6cbdd84988ebd9e10fcef6acd0214e6f6994.nq.gz
    ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
    ├── 332c394720c4b3b38bb59b1ae8e4ea31d8170b21.nq.gz
    ├── 341d5145bab60d8c0b57ff9af706300b6ce8d320.nq.gz
    ├── 344b09eb3bc714a6e9c97288ca3971b4546bf8af.nq.gz
    ├── 34a233b1dcc0490c882273fffc3697cd18b7d85b.nq.gz
    ├── 363c9415508d7e9145d4dfd59572eefd035abe85.nq.gz
    ├── 36a7e892ae2bc8a2ad9df7e161682299cceba36b.nq.gz
    ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
    ├── 38ce2e4a7fd3cb2878235c85f376ca3b3bd4392b.nq.gz
    ├── 39f3d0fa757ee35ee317ee6058ee2ab9e5cff38f.nq.gz
    ├── 3b7467bbcc9a5e5b490707fa400eefb3f8c11eb3.nq.gz
    ├── 3bb5ee0676acabfb85c74c58aa6ca6cc968eaa83.nq.gz
    ├── 3c3628646e8a518d1bc45a2a308f4b0118969204.nq.gz
    ├── 3c557afe2d3d1b2d4588d1048374bcbe4c7752a1.nq.gz
    ├── 3c57e1cc3207d5d0da035c2db777f2c3126d434c.nq.gz
    ├── 3e36a837a437e501f602d9b04903d6a11a946664.nq.gz
    ├── 3f795a205d25972a0a1a77551fd66d97a5b45512.nq.gz
    ├── 3fbb1ab62835167463a04c90340c688801980d3f.nq.gz
    ├── 3fc1f1c7db187cd33651fa313e3f8017cb7844be.nq.gz
    ├── 401ce2ba451dc4a501e5cb29a622bad2f72854c7.nq.gz
    ├── 40241592a1dd7325f8e7e910ee59602ad3c9392d.nq.gz
    ├── 40c81b89159bb5b05459dac4adc6145b48af5b24.nq.gz
    ├── 44e5c0e4578a75d9eb76d315b1c7f3ccfbd1f048.nq.gz
    ├── 467c8e84f0eedb144a6c572594ee22a59901eb82.nq.gz
    ├── 46ecf0a43ed302cbd258fdacc6a1a9258a2b8492.nq.gz
    ├── 46f36efc358e8c5ee6c240b12540d5b8fbf159e1.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 487a0fc10d32830636c711e92ecb0921a2168fbb.nq.gz
    ├── 4ab711189248568c88bb10b1f79ab99031a693db.nq.gz
    ├── 4c70d17929a73be888fced465cae9c0dd72e5ac8.nq.gz
    ├── 4e714e8dda2e0937b4b574a3db8e966068a5070a.nq.gz
    ├── 5033cf37b8252568773314e67c063078f6d76b6d.nq.gz
    ├── 528bee2e0776f181630fdf502fc574af7134a4a0.nq.gz
    ├── 52a03f2c057844b0b2309e30dbe61669283272bf.nq.gz
    ├── 53a343affa89bdc1e8ea6cc48a71bd71a90c7813.nq.gz
    ├── 53b7d772e6459ce66de09c4fe38ddf61f20d821d.nq.gz
    ├── 5482adf3ca5d8c41e33289f5ddeb13e875b61562.nq.gz
    ├── 55458d07beff0ea4a1ad4ef2613a02245fb65662.nq.gz
    ├── 58735c5b5009b948788c92a5f4654e208dd5d6d3.nq.gz
    ├── 58b6055b69e99c3a66ab0ab66f1f96f4ba92046d.nq.gz
    ├── 59020d72fbb0ae0a77b338188599ebd3fae68332.nq.gz
    ├── 59e5c7a454e7014d90f3913e8f412c0823fc383a.nq.gz
    ├── 5a463163ae0a6c6656d48dfed4eeb65e4713bdea.nq.gz
    ├── 5a6409d9e5a6ffa088c41fdb600df304df3be5f0.nq.gz
    ├── 5a8ca58fd593bcf8eb2a7d74614f9dda349f4db8.nq.gz
    ├── 5ed93692851082d95ee2c00e2d7b33ee18510a61.nq.gz
    ├── 5f8f26e0427f4ffd8cb80456fa88ad58b0367658.nq.gz
    ├── 5fc5b6ea8b7f17d7822fa6a9b75ea5d18cc2ace8.nq.gz
    ├── 60786da4815e4354a038893f431afd94d6a4afc6.nq.gz
    ├── 61d5bc3a071095d8758ca5bced322d0491f99e7e.nq.gz
    ├── 6210916e46237cf2eae2266b66791a712c84740e.nq.gz
    ├── 644b6228277bc350d3003b6b7ab85f17d1997daa.nq.gz
    ├── 67aae0ebdf591a1d2a16b3c04f67771d36133cc0.nq.gz
    ├── 67f9209cd8be9dd566e87fa8442b0e038a56bd82.nq.gz
    ├── 68973f5243d1eae4daa21a50e65f0d2a1bc3fd54.nq.gz
    ├── 6a4f21b6b70fc1d1ed0383e142a7399b6f991e6d.nq.gz
    ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
    ├── 6da71d39738296e2773f064aac1d2548db975b61.nq.gz
    ├── 6e6dff205e3faec7deba8f9dd4068a48bdd6af46.nq.gz
    ├── 71ddbf9c34a3e7ca06f0e45116fa04217c4eecd7.nq.gz
    ├── 73ab4d51a54cee542c265e7617d58f188e15b86d.nq.gz
    ├── 75ce825bd0484c5ca6443c1fbdd4ef18767e012d.nq.gz
    ├── 789ba195e1f11ada0b3ba88e2398d37af42593d8.nq.gz
    ├── 7b017b4334637ebca37edd562785e1be5ff9b50e.nq.gz
    ├── 7cdc931a330dbc5221f4c36cb75198ab7ec79013.nq.gz
    ├── 7dc844a7f832a7e6f471e031a369023993d2daf2.nq.gz
    ├── 7f365cb05f2c7fb6d23e0891a69c797f48a9add3.nq.gz
    ├── 7f89d1beaba547bc01c6ab21a3f585add10774fd.nq.gz
    ├── 83d6faa71136390fbbc0d5d2c956b74aac91334d.nq.gz
    ├── 8557483d1b9cb3f630ef9fd294e492806da6a640.nq.gz
    ├── 861434d3ce6392caf7fcb346020d05c7d08db02e.nq.gz
    ├── 891b2314fe0671516a898b7b0ebc0ec744ab24ed.nq.gz
    ├── 8c2b551824d9cdcdb6b34acac1faaf990534c9ab.nq.gz
    ├── 8d5364a9a5560997f800e47cac6b911d66563045.nq.gz
    ├── 8dadccc2e68c296e2044aad271ae104132732dda.nq.gz
    ├── 8ec0be9b7ae45512f6d5c9e8da3f720cf36b4d65.nq.gz
    ├── 953fa4101a596725fbef6d929623ffb349c6a88c.nq.gz
    ├── 95854d2d0b78231abdef7bbc9bf31e9fdaa9842b.nq.gz
    ├── 9809925a7fb56bf66ac4d50d96366dbc0a72f9c7.nq.gz
    ├── 98637674cdeb9d896bcd3ca33df01cf522fc8e35.nq.gz
    ├── 99e87832b412bdb7f5d50d4c3dad2349ac038761.nq.gz
    ├── 9ce6ebcbb77fc7d020a32cbcbdb8fd6145d86cfb.nq.gz
    ├── a014e0d1538c6227d66f925c6903ed870a95a248.nq.gz
    ├── a1863ea16ff5464a5ee17001a33d416644819b49.nq.gz
    ├── a2b5edbaa6d05ba353661a187e3a095f386663d5.nq.gz
    ├── a3bb9127527c263a44b2104531f0fe0244e652ae.nq.gz
    ├── a5386452f5f7122e45c00387de963027a7e15e66.nq.gz
    ├── a75ee270a89fd2cbc3f6d7ba92645aac6c1d102f.nq.gz
    ├── a83a1ea733d64071de0e66ff72f0991fcfaaa391.nq.gz
    ├── a854b1f0b40ceab1007fb7e8563101f88f7cde74.nq.gz
    ├── a91e026d69ded7a4e35a91f610f211756c3cc2dd.nq.gz
    ├── a9b43a2c41a16b7522cc6372f53ad7d629aef5de.nq.gz
    ├── a9cf3db8566175e1507f276c7e6dc81b0a3ed670.nq.gz
    ├── aabfd4ab5e49ed4237cc1ca6ff9213775c076f49.nq.gz
    ├── ace4460747023b093ca3306e3f694b27d57638db.nq.gz
    ├── ad384bfc711841bafd0ae6dd053888c30cd6362e.nq.gz
    ├── ade5036504f91e86e31243da46903091b7796ced.nq.gz
    ├── afd3c9196a0dcac54e3871c1ca6f7b313134b470.nq.gz
    ├── affc491277c08cc9cbdb4e48628da6f8f14f1790.nq.gz
    ├── b0651e1f472d6e16aff9cd2cbc2c2f335a92318a.nq.gz
    ├── b07488b82557862188bdd05a84b22dc95fb66558.nq.gz
    ├── b179a3ee25c9f45839d5e57d65742b43ac600d7f.nq.gz
    ├── b19463b6a53ef9c248108524fa3c5d619b65e957.nq.gz
    ├── b2fead31c0f41f45316d0822429c8ff5dff0aef4.nq.gz
    ├── b596887ca26ffb7f25ba2164fff1b5a21199f10a.nq.gz
    ├── ba5f734bbf75d97b7ea7fcc202da2d7ee6145b7f.nq.gz
    ├── bad875a188a00e60410081b37e8f010b96409151.nq.gz
    ├── bcac34fdf02da92ac0805e5c13e650609dd522a3.nq.gz
    ├── bcb5909d13f27a103ed141905119815d535ea0ae.nq.gz
    ├── bf9168efe5dc9c35938489ae63dbab8458d8ea53.nq.gz
    ├── c03f520e31d555ece6d7afcf70dbbeaf8d31802a.nq.gz
    ├── c14c7fad3b1317b87041961b80972f1d3375b84f.nq.gz
    ├── c1ec912d04db626bf069f036861f717e97b45154.nq.gz
    ├── c3d98c8f2f0e6f3a813e25feff96a513d0888615.nq.gz
    ├── c3ed72b59dc974fb63438ed7fe74e775139ded79.nq.gz
    ├── c400b3b0728e494fce7c1bc62ffcd190601c7232.nq.gz
    ├── c49ca5d3041ef5285ab9d4623f1ac7d621fdf666.nq.gz
    ├── c546882f9b9854ea20387457ce756453db6395ef.nq.gz
    ├── c5ac8851ed1e8a7e657378ccdba4c1e2c2e3d9dd.nq.gz
    ├── c7a85ea234a4f356c02fdb613281aa2e54cb96a1.nq.gz
    ├── cb6b87e59f44b5f087c9c5745e4f85f45984e67b.nq.gz
    ├── cc3a3d978f2428d911a7235edb401cd9a07ad24e.nq.gz
    ├── cc48934efe7a1e284c20f579deeba03718851b0c.nq.gz
    ├── cf59ae7e1708f88e3c0efe371d224221aa46dacb.nq.gz
    ├── d140c050c4b6355b854a7efeb9ced0b366c51610.nq.gz
    ├── d2d4b511bcc45c840e5fcb541e81cb0f65303800.nq.gz
    ├── d43cbe33b68db89ff567b6134cb883b9c9dec77c.nq.gz
    ├── d59980ff354e37bf2cd04ad8cda98bfa2ff68f8f.nq.gz
    ├── d5c0d8d081829dbd84742d4468d482c1003e4ffd.nq.gz
    ├── d6b868acf5bcc13cc7afc60347be7348cb0efaf9.nq.gz
    ├── d72ba69b58636ac831ca2edde94e110ec713f040.nq.gz
    ├── d81dbdb710dc9ad8e762e20c04be17ae804b7894.nq.gz
    ├── dbb2c93e46d41c4fef6997842c11b9584a04e38b.nq.gz
    ├── dd0fb24447ddf31a6def33873b43736765018ee9.nq.gz
    ├── de03f3f6a57e5f697bcba1f21e136dd91caccd3d.nq.gz
    ├── de35831f3bb37c97ef4b12f710154c3ef14c84e6.nq.gz
    ├── e01b6447bcbfb2a02ea4298e57c7d8e4b28ca302.nq.gz
    ├── e05561ea14c6b2ff5c50f714c91a687152ecd1f5.nq.gz
    ├── e0d1bbb1896bd37dd8973a0b7d035463f321daff.nq.gz
    ├── e1f13a12673692c71ebb407b7ac5c6c82dc8e64d.nq.gz
    ├── e25451a4942c4600136c9cc0ce1e641b51ca8b59.nq.gz
    ├── e5568ea936728808ef12e6ebcc87ed6d03abe11e.nq.gz
    ├── e648bd829d37b4b7ab88c9c974258a8a3d17bcad.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
    ├── ed588d91eea25b9c688b5b23b6ce00edcaf0ac6e.nq.gz
    ├── ef94912dc9c336ef33703649fea0deeff2019951.nq.gz
    ├── ef9d247e456a5337b7cd1de8403658ba24e8775e.nq.gz
    ├── f033e7a03f207fbf0ee88660a840c4d1d6ca7582.nq.gz
    ├── f0e42af466b703cc22812c5a3ed7caeaaef22b47.nq.gz
    ├── f19ede37c0de6a3de2466f4039d5fa2931bc32d1.nq.gz
    ├── f21c01c0f2d404976cb07a60b0b66dece16a7ecc.nq.gz
    ├── f47ffc63a69a83d83ef79ee569e89eeafc932aab.nq.gz
    ├── f7716cb22dbd3c84aba9e89b0c187dabb8272bc2.nq.gz
    ├── f7d11edcda0124fefb4d5b67791ff4556c2fd0a7.nq.gz
    └── f7df530f1cf1715f10f5a26aa81f00d935427125.nq.gz

8 directories, 200 files
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

[block/cachew](https://github.com/block/cachew)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
