# Repolex Knowledge Graph of eslint/typescript-eslint-parser

RDF knowledge graph data for [eslint/typescript-eslint-parser](https://github.com/eslint/typescript-eslint-parser), parsed by [repolex](https://repolex.ai).

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
rlex download eslint/typescript-eslint-parser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76b4d42e6ac0b2392d5c523c8e84dfab14599de3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76b4d42e6ac0b2392d5c523c8e84dfab14599de3
│           └── chunk-001.nq.gz
└── blob
    ├── 00d04632efb98a1fb1ac60a1af0e334613fc9893.nq.gz
    ├── 00fcd7be15ef21bbcf38e21f006b093aa4a389c1.nq.gz
    ├── 01c67fc786c0787bcdc17e89e4e6f0833bbaa4ff.nq.gz
    ├── 023291c4e9952c3c4246ef1fddbca873010081a8.nq.gz
    ├── 02458f045eb3ab155e4d56921cd0f51c8eb1f662.nq.gz
    ├── 02c0c9131844c286ee1bf88d72b1865cedd6a499.nq.gz
    ├── 032a56b3d7e188b8fa852e17368f1ae183d2de36.nq.gz
    ├── 03508aea0a725d01ac5efae755c5598f280d4114.nq.gz
    ├── 059be0b3c2a01829268a841de9fd0712fadada63.nq.gz
    ├── 066334bf8743c1a9945f935e9c45b47e64dbbb74.nq.gz
    ├── 07db7a79d553cae4e46154f281a46042a4587619.nq.gz
    ├── 07dfa60925894e7b06d4dd5e5c2e9dcf349a9603.nq.gz
    ├── 0821397f396cdbc5cbde4cd070ee620c27d7b0bf.nq.gz
    ├── 084fa0cdd14a37300e5cdd470751095cf0f9def0.nq.gz
    ├── 08c6203a9da6da33e16149e3196235f419915a6e.nq.gz
    ├── 090dccf02df695d154e5a168627ba1b073e6674c.nq.gz
    ├── 09d0d344e633f64bbab44ca4c57d33461ef1b7c9.nq.gz
    ├── 0a02bc2081f483b38daf5b261d4659efcd64c475.nq.gz
    ├── 0a4caa7f0b758b2bf37baaa06bbae238ca77cda9.nq.gz
    ├── 0a69310519e114cdab0797f8a8f43236025fe437.nq.gz
    ├── 0c55147878a5a483d43844cc41ea85e09042b91b.nq.gz
    ├── 0c5e89163a40481266b91853bde8a18f98b20dd9.nq.gz
    ├── 0c6986fd88c69ecc0e4f6f7a0e4d936bb9051fd3.nq.gz
    ├── 0c8bde149a88e971313aabd666c286107e95e4a9.nq.gz
    ├── 0caa3fab4a96db1859e3316ab78eca9d993191c7.nq.gz
    ├── 0ce82a509cb3570011e2fe2a19bc778c6a0ba051.nq.gz
    ├── 0d7e62648fe2ed21b163e11fc1c339459ae56eb5.nq.gz
    ├── 0e6918d7d43c994e5f4a6da5f1081ec1c345b1c9.nq.gz
    ├── 0ebc974917b46d9803e62f73e3060662c3236474.nq.gz
    ├── 11d8c39bfa8b5b461935a6559ce3ee9416d976e1.nq.gz
    ├── 126d595430f0b606866af5d3f21c30abb2de6d11.nq.gz
    ├── 12898791abbd08bacc87992d68cf81fb58ab77d0.nq.gz
    ├── 14b2f8e3875051e42613aa2022c1e958f713a560.nq.gz
    ├── 14e5e1dcb0b8b84f3c05aa76c8925d03d1b01232.nq.gz
    ├── 15617f88e041ab3660d0273c9b1e84472384158d.nq.gz
    ├── 15897e0cefa5becf6e3d856c596788dc699c6a28.nq.gz
    ├── 15f6b7c33f2e37835da683bac1d529909595f1e2.nq.gz
    ├── 16e3ea2897857e1dc3b6760432b1f739fdada9d5.nq.gz
    ├── 16eb9c5687400fa80068bbe294c4765ae59ed216.nq.gz
    ├── 1740302f82917b89b32504300655487b79fe110f.nq.gz
    ├── 177cd72468dd9a9690966a783548e5e479a1cb3d.nq.gz
    ├── 18dff34f73a574a5dc49607d46e747854ba00e27.nq.gz
    ├── 18e73855fd2e4caf64bf5f2881321e763fe26fe8.nq.gz
    ├── 1925b1e2da93aa0c4f6d46b8bc975f97b75f00e9.nq.gz
    ├── 19351f45e7101e3ec3efe6dab49200138f363854.nq.gz
    ├── 1948b43ead29f31848f3a7d20d7cc49f1a23f7d6.nq.gz
    ├── 1abd3446ff0dd6d7ff6315c5fc6a8e70e6abe5a5.nq.gz
    ├── 1b212bc385afb169086e454f32fe0613f1853ae8.nq.gz
    ├── 1b881004b3c1c9095588ff9e7b36d9ee36ddc587.nq.gz
    ├── 1c94b625bd2ef31475a83e4950e06394fe306a89.nq.gz
    ├── 1cc0e41709ea51ede0f89739addbd27977287591.nq.gz
    ├── 1cf79a3aa7521db6db85115df180b4d7480ae154.nq.gz
    ├── 1d23c00eb09534ff5744c29db37cabb51c36f38a.nq.gz
    ├── 1e6428494f658f19fb26a1367794a3437433f838.nq.gz
    ├── 1e9f54230af36674ce12101f14cf5d6894fd833c.nq.gz
    ├── 1ef4ef44c8a662de48218a83ffda02bd82c9d8f3.nq.gz
    ├── 203ca0836b8f9a71789dad0103c5a7e55902f517.nq.gz
    ├── 204f239e3696cc300ad1994890a3e5ec9cd6efca.nq.gz
    ├── 20899cb988ae9c8097b311065ffc5e650c10156a.nq.gz
    ├── 210a5ac4d9a6c44515439f9e614085a1df8e59f7.nq.gz
    ├── 2134f68be4fe811b3406c0fc6e3a3ea47bb6326f.nq.gz
    ├── 216c093e580f9cff52f4fdd18d870d4c041a74e4.nq.gz
    ├── 22213ad116bc89ece19cc50fb38d676aaa557b7a.nq.gz
    ├── 23cb06466d6673b0b0a06a72616dacc3767eeab1.nq.gz
    ├── 2421c8b7a8c2437d1cc5dc22fdccc83927696daf.nq.gz
    ├── 24f2b53691d1e847bd92728b363c3f01a86d6353.nq.gz
    ├── 2525c6720f2192e55ffb2e17e653a31c64595d0c.nq.gz
    ├── 2537287de022ab20b489d14fd426088f32987712.nq.gz
    ├── 2590bf7a9136947a6a8dc178c760ddd43e61b814.nq.gz
    ├── 25993b363d55f3610f6c2f45eb1ee92077a7f4eb.nq.gz
    ├── 26013fa26279ff0c9f95ccbcac73ba6e31e192e5.nq.gz
    ├── 26ac16e44cfa306f1f382fd7c9867c43ca45b4c8.nq.gz
    ├── 28bec5ed0b4ecbf4093884f2830b0cebdb8468f2.nq.gz
    ├── 29298a12b52fa6a307239780354f87d18586291f.nq.gz
    ├── 29fda8e4a120fba6ea51033b5bec8f58a4d4dbfe.nq.gz
    ├── 2a6819ff0b13c77a973bf26b342da8cb2a8655d0.nq.gz
    ├── 2b138015de5eb7ee6381075c14a8a937041380a1.nq.gz
    ├── 2bf99cbfb588d9bf88429d2f6bde89d91b7efa86.nq.gz
    ├── 2c7930d925cb59d9ad9ef20cf0a9e6e689868fef.nq.gz
    ├── 2c8acc12d369dadeb65973fe46232899828a6764.nq.gz
    ├── 2c9dd12d0481ca1ebcc7b653fc20fed4c0c21b44.nq.gz
    ├── 2d2d277b17a6cd8dd72fd074eb004944f5977c01.nq.gz
    ├── 2d96e2fa71cb68bf08223f7f4c1b7b2de7443f08.nq.gz
    ├── 2eb0d18f575b9ba80409c1c726210fd03b56bb3e.nq.gz
    ├── 2fb83c2349ccc5ab5788af5ff446a1e5456d307d.nq.gz
    ├── 2fe152d3d419cecd223368cd32439174fd402eff.nq.gz
    ├── 304405d389ef020b6000fc8ac95086023e7331fe.nq.gz
    ├── 309cc757326039ce93a6fe68bca9bafcc5c41274.nq.gz
    ├── 30b7cd791f31b2c3dc077550692bd99daa3457ef.nq.gz
    ├── 30f2b72c83b610edb0a648340310f8dd991df6bb.nq.gz
    ├── 31f184e8e67a5d043711e8db7e54d2e50679031f.nq.gz
    ├── 320bf39a58a764a63f54aa6465f28f281c9c6669.nq.gz
    ├── 321a2ea746ae4487c992977a44afb3107e433821.nq.gz
    ├── 32683cf927736146ab0c8b26be509710b930dc8d.nq.gz
    ├── 32cb28ea92ba53690a5fcb6cd62f3f180d1182a0.nq.gz
    ├── 338ebc128b7eba87bbabf703f9370e22f0873075.nq.gz
    ├── 33ce0e95c298da43d90bafcf1450fb546485f601.nq.gz
    ├── 34119d84c9adfa21e2ec44333e491b2ecc99c62c.nq.gz
    ├── 345b888444219a08054f5f5d6defbdfcb60b5d0d.nq.gz
    ├── 34da4b5676698508cd1127082ee8d1d0c4e37115.nq.gz
    ├── 3509c96a752f3118c32b92a878392b14e1128ae5.nq.gz
    ├── 35c2762a2954c2d2d9ddb440022e9de16bea5e1b.nq.gz
    ├── 360727b872ef9421f00edb6401e2aa12ce855636.nq.gz
    ├── 3690a57479ab4af5b3110d2b45143442d6e0a626.nq.gz
    ├── 37142ae38ab63def8c2b061f66eeaa4dcbb4efa4.nq.gz
    ├── 37a088a0f158c1adcba630eaa98f7f03c2326688.nq.gz
    ├── 38395bd1c5d037adaaa49554efa5f73c398bad6e.nq.gz
    ├── 386baca17315fa781213b366c40be40d113f1142.nq.gz
    ├── 3942db82641a5067e3dfd8f61a9a65259ce62107.nq.gz
    ├── 398775778522c54596488fa311bce6cefca6c29b.nq.gz
    ├── 39ef542fe289a2636b38a5c51db9db707a886dd9.nq.gz
    ├── 3b55650bc8947ea195bb2cb41e767b1dd025e2ac.nq.gz
    ├── 3b8bb8eed40d73c88d1037c8f7d0e61b630d327d.nq.gz
    ├── 3b8d21ba958c932a6d6552c929861cba3df6c29e.nq.gz
    ├── 3bfab96a2698f3ca213ba72cd6aa6f184a892779.nq.gz
    ├── 3c186ea51cd92cfb9b410662ffe0097615d012c8.nq.gz
    ├── 3cf9d1fdc452a6c2bfa758bca2c79a64baf54f7c.nq.gz
    ├── 3dddc35360313554a2f35de6ffd1441764621f91.nq.gz
    ├── 3e1360594e06f4226d2e5cb97f5e9b1e81b0ce37.nq.gz
    ├── 3f2483ce9a81835008a68ae6ab5af7a12bb1b852.nq.gz
    ├── 3f576881e6c5d0be1d72bf8dfcf78b9be4e80dde.nq.gz
    ├── 3f6c5d2ec27812ec040259196fb95ba332694ffa.nq.gz
    ├── 403557868e70133680037a749be1d13588efce0e.nq.gz
    ├── 4077e9b1ad797dab0611ea73b017766ce90845fe.nq.gz
    ├── 409abfa0c48b74045582256f7209ce41ef26201c.nq.gz
    ├── 40bb7fe8ade678c925e34cba86abcaeaf56d7901.nq.gz
    ├── 40c40bf9436ffaa65c7f37de10086d97423f060a.nq.gz
    ├── 410eed8cc78f1b808e5dc58f61e8e467a94986a9.nq.gz
    ├── 4163a542c54e1af9faf86ff2d7888a674d33f3f4.nq.gz
    ├── 42128953cb7d1c9925873e3e1d17b396e1bce5d5.nq.gz
    ├── 42b4c0565f4b0837b665b9fafdffd465785c6506.nq.gz
    ├── 430a8bad251d35b4f947e5b9ee536ce260ee103d.nq.gz
    ├── 4461d79e3bf3449c1c1926c525ae3a5ff457b4c6.nq.gz
    ├── 448d419a81cd6855200eb79cfd30df868e64c136.nq.gz
    ├── 44b5da534b6697cad87f2a362a22f038bb8b02fe.nq.gz
    ├── 44b77c7aacb662d8882ebadc8979741d3a4e2055.nq.gz
    ├── 45ab5c0f905c31a0b7a64c37a547e29fd2ba8fc0.nq.gz
    ├── 45cabe3919de5bd10ccc2adae2ed471b8bcc9913.nq.gz
    ├── 461e8955c72ac5f942361259bdd207e6eefa13aa.nq.gz
    ├── 46b13d0e56be5dc7c8e96d0b411584cc062e06f1.nq.gz
    ├── 46f729479dcdf654959b017d5e42aadb22f0e56b.nq.gz
    ├── 475794bf0c0b6e217f9723651a951a2ff1de1b7d.nq.gz
    ├── 48319379e161366aa0258869ed74d0cb7ebbe0cc.nq.gz
    ├── 48796e029fb41b207363fec3aeed237639e294b8.nq.gz
    ├── 49237c1f1480d2c6f6e78b8fa06d9c82a4293285.nq.gz
    ├── 4925bd4778cca11a0f799577c0a5caf784f62e58.nq.gz
    ├── 49837b4a1505b314734a1b1d0706972ca14bde53.nq.gz
    ├── 49a04ad0bcf9f093cd68c197b8a5d740534209f3.nq.gz
    ├── 49f73ed38546cf633140799a867528e9f68f5925.nq.gz
    ├── 4a5809fdd554fdb729f2f3cb339b6835279efa8b.nq.gz
    ├── 4b8882f7305cad5ae7ac61fc73f516138477e1b1.nq.gz
    ├── 4c9e774a3c74aaee71e8c31bf7acf4cc62334b0d.nq.gz
    ├── 4cea72889f61b47b600d5213b0fd8a1dbb6b0dc8.nq.gz
    ├── 4d4d65d91ce5318b65f0aa6d4f9dd6685d9d1b9a.nq.gz
    ├── 4d733791c65d33e65faa7b99d79d9f90cfe18038.nq.gz
    ├── 4dc0eeb08a3465bc665c99bad5f30c6f90aaf48a.nq.gz
    ├── 4e618d12dc37ec3bf7630f70ffc871fe995cb923.nq.gz
    ├── 4f4d10709f5680f2c0ed1556dda0bbffe3efaab4.nq.gz
    ├── 4f8c006ac0149bc64cbf57541fd1536d422eb48b.nq.gz
    ├── 5198ead3cde7b4e81c519c3d9eef9f5a8d9e284f.nq.gz
    ├── 51c02f8b6ed11d4b4c836013fe9148c280278615.nq.gz
    ├── 526137f30906f94e3cadadf8fce43bcc1b3182ad.nq.gz
    ├── 535922a77760aa1325eeb33c50cf9189519be4d9.nq.gz
    ├── 536aab8062dc8ef6d412b657cd5da4414795dc79.nq.gz
    ├── 537036b92f84e1f3c9682faf7a17ce6d1c6bf86b.nq.gz
    ├── 5387a76cc7448a0570dd14160a9e97ef71fb0931.nq.gz
    ├── 53b1654cb828d48e386ca242f0fbc48cb6c15c19.nq.gz
    ├── 53c8e72ec952db3910aaa96b42074eba7c1b8e4e.nq.gz
    ├── 547ca4bd91805346300415c61842e57519ec322b.nq.gz
    ├── 548267aeb2e4185f55994bf514f7c177c689737d.nq.gz
    ├── 5549093124c0fed01b9cefc9ba2eb5efd86e616e.nq.gz
    ├── 55faaf141dc2e31d10b5e95c105e267e03e6d9d8.nq.gz
    ├── 56d367c193d464546b8857fad844b20b0f21e838.nq.gz
    ├── 570124e64f76c0af30d173ccac1c91bd88027a8f.nq.gz
    ├── 5788395aaa33aa1097189276d8e0b50cdf49346e.nq.gz
    ├── 57eb3a476d1530014e4380985b94891871faf4d0.nq.gz
    ├── 5903f34f08bdeb1b5091ce8ef4b51127861842f7.nq.gz
    ├── 59fbab7761a6eaa2b658ff8e3930e44e2dbe9f32.nq.gz
    ├── 59fc47fe082559b3a699add129fc93f6a2b2491e.nq.gz
    ├── 5a51236aa6f81887c608a00b8ce663c8b367a5d7.nq.gz
    ├── 5a71f3507199d63c06393bdbcfaa2bd85e78fed3.nq.gz
    ├── 5abfb88e92f2aa0bd0795d7bf2cc608deace2f8b.nq.gz
    ├── 5be12dab64a607caee21bbef85a47067ca880c4b.nq.gz
    ├── 5be9a685aabd5d80cde1544bc9def1d28ccaac82.nq.gz
    ├── 5bf66b1e20726f8bfabf6f249a0a74c6efb2c8ec.nq.gz
    ├── 5c09849b2e7956d7fe666f33fb626c1a4dd0fbb8.nq.gz
    ├── 5c542c940acef6817ca3b452b807e504db5dde1f.nq.gz
    ├── 5d038fc71d95f58991a7e4e895fb71726b61f97d.nq.gz
    ├── 5d32a24de0a99f6e1b941e4cceaaa7c98b5543af.nq.gz
    ├── 5d58cb32306b4d21d347ade8c1921f4057c14616.nq.gz
    ├── 5de9359ff3617f2410eaf7a9c536ac7fb403a397.nq.gz
    ├── 5df03fa0b7261baa0b624a9e8fae571d90317c7c.nq.gz
    ├── 5ee5169b312be1175f61101c5a14476d8330a802.nq.gz
    ├── 5efab6d986b6e8199607df0bbc0be361ebfdbbb5.nq.gz
    ├── 5f3ddae50e295d0f8e687aeb91a86a6f0ebc56cc.nq.gz
    ├── 5f8f86aeebe0100af1b00b28638b263eef7d849e.nq.gz
    ├── 5faab37ebb443e4ddc2adf353d5fdbfe43708a53.nq.gz
    └── 5fe5821757f418307d487fad4ed17aa5e98f4338.nq.gz

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

[eslint/typescript-eslint-parser](https://github.com/eslint/typescript-eslint-parser)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
