# Repolex Knowledge Graph of magic-wormhole/magic-wormhole

RDF knowledge graph data for [magic-wormhole/magic-wormhole](https://github.com/magic-wormhole/magic-wormhole), parsed by [repolex](https://repolex.ai).

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
rlex download magic-wormhole/magic-wormhole
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfa275f575ddc009ce42fcb3bac5382df2698f1e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cfa275f575ddc009ce42fcb3bac5382df2698f1e
│           └── chunk-001.nq.gz
└── blob
    ├── 00aab08049b2fdbcad8c26e34d0ae420b4f19e1c.nq.gz
    ├── 00ca43a764a06d8b051d3b5d23d10a1684b939ff.nq.gz
    ├── 01f11e090195484c9b38898a940d671603b6d53a.nq.gz
    ├── 02746b1e1d6880c5ac6705b9b1557b443e90654a.nq.gz
    ├── 03ddd32106ad6503d654db13937ae37e02088457.nq.gz
    ├── 04adbf33b444e5a778b4551ea591ee9e654fe1ca.nq.gz
    ├── 052356f88a934f46210b4635394d0b3d707a4f1c.nq.gz
    ├── 078950c565e774a2886cd70a113b8ce909ebc8ec.nq.gz
    ├── 07a960b417bc6683a61061321a0063a029e40246.nq.gz
    ├── 09383387004503a705f6b5b4e39c472c19620061.nq.gz
    ├── 094fa6d71e4b6dcf32ec8aa193495ec7bf090a6a.nq.gz
    ├── 09cc02cc56766270bfe7d54aa47c18c9a639faff.nq.gz
    ├── 0b4c2eea63fe14f28a867445446b6c9adeb9c07a.nq.gz
    ├── 127594ef50052ae07ea2334587d3d2869b7a93bf.nq.gz
    ├── 12fe9c6be2bf2d3f73c73fafcc6e6c17d9be6e4a.nq.gz
    ├── 13035db4e76c8a6aaaa6f9a5cadf76d897cbcf1c.nq.gz
    ├── 1465802ef9e8d8ef34053411ecd1cfa5eefe99ed.nq.gz
    ├── 150e771ebceb7a9066cd3c83ccae20f18c72a48a.nq.gz
    ├── 158ed2626a9dc739a5b665b753462dc19740c325.nq.gz
    ├── 159d5eab0ffd19ee8c703957b22fee934d8d9dcf.nq.gz
    ├── 1737ddc256a74468e3efc77f490cd579cf5ffd07.nq.gz
    ├── 1808a4e8ac21d8445d8e3caf3e25f9becd9767f7.nq.gz
    ├── 1814e466d325063f38a9bc3373d968388a79ff85.nq.gz
    ├── 18c9679247949f50b9bd7497ef291e413d07e2d4.nq.gz
    ├── 1a70051f975c53140747ee2a8a0686e77cf07d1e.nq.gz
    ├── 1cc165c37510c81080c172a1b95b4103cf9b6abe.nq.gz
    ├── 1e886da6b540a527eab899b16b3eae63a87061af.nq.gz
    ├── 1fcd4022a4e3712f0899bb6d69a0d434a31a42eb.nq.gz
    ├── 204878b5597258f8523605e33adbf979c0ca20e6.nq.gz
    ├── 21366b4cc83f7187e0df1d5fa483db1cf3bc9c7d.nq.gz
    ├── 2209d9f980d8f53a7ec27016669bf8d6b010796e.nq.gz
    ├── 2260517c90309c3c1b9f81bfc31e7ed9c1b7e1c0.nq.gz
    ├── 243dc9a1f0f5b62491bef40455528e60f48bc9e4.nq.gz
    ├── 263a4df6c06d4aee1842592de82d1920a17cfc86.nq.gz
    ├── 275e8cd3b122f71ba090bef890ddd69ac46db06c.nq.gz
    ├── 2773793d8f555262e1f10561319985845e2f7fe0.nq.gz
    ├── 2950a252441b01a5cbed65e13b0835870d867f99.nq.gz
    ├── 2b4dcf414a8c46cc419c0dc4fd4c2f56f60d9098.nq.gz
    ├── 2dd3668619ac417dc303b042c56c31002ea665ef.nq.gz
    ├── 2de0cfbaaaa57843efd414106e60a0e916cd5e0f.nq.gz
    ├── 2eaa86e2434a03b32b0d840c6a6244de84adf593.nq.gz
    ├── 2f2f0df78f8fa19b32405a377162b137928b7bc3.nq.gz
    ├── 2f7361d60607b9dfd8d53220aaea0e5cf57e2809.nq.gz
    ├── 2f9e88f48524697e56321a6dbe53110caf9135f4.nq.gz
    ├── 3070a7c5063d262fbc3f0f5bbe2e76c0fa2a0a59.nq.gz
    ├── 30a260f041003c91e2b103effe3bdf4c792846bf.nq.gz
    ├── 3101f18986ef14cd3acac5d38042438feb9fd91b.nq.gz
    ├── 334a7d24cb5334ac9e71f01bc50239f76c6c2d5b.nq.gz
    ├── 33f81ff23b7b7f3a85113b5e4b1494ff14c72611.nq.gz
    ├── 353cc89e42b7b29b91ff264304d6af4d722b0c0c.nq.gz
    ├── 38b7df1b262f359de3b01c6f281ef42f50a50d64.nq.gz
    ├── 3924be929491dfca47c90529c5d559eb202c5ec1.nq.gz
    ├── 3c6608022006a639c27c10ed970e48289f912adf.nq.gz
    ├── 3c693261084fa9b4e30369a56e4cc83fbbeeb79e.nq.gz
    ├── 3c760f8d524d7eacdb8799346507ec06fa7a199e.nq.gz
    ├── 3e4ff5ac8482887eca062ec7c2e594c2f5c87e58.nq.gz
    ├── 402e5a3c189558b3afcc4cb651659791090f2c76.nq.gz
    ├── 41a9573c2f6a2a0038219d0c95fb83005edb10d5.nq.gz
    ├── 4366eea4a9904338e15eba468fa9be9a4e7af3f7.nq.gz
    ├── 44bae1084d9afa10a28c3903de869264a10b3af7.nq.gz
    ├── 44c0af66668bf6951f0e30457280b3de74fd8ee6.nq.gz
    ├── 49e45bf425a7bcc3195cc362f4e3f9349a13590e.nq.gz
    ├── 49f6b62a0734e26e14ef44e095c6985c8a2559ee.nq.gz
    ├── 4b2f6ec3c2f8fc6af7858b03eaef9f9d5fb572aa.nq.gz
    ├── 4cce2e67d6532a23347dea4d3d30125437c1d276.nq.gz
    ├── 4f1bfddafc424d0d9004f514ad9f20958568de21.nq.gz
    ├── 503c2c448dccb5c054b61bebf8890123b329f2e9.nq.gz
    ├── 5055e232541d4827a65e0a3198887110fa37268f.nq.gz
    ├── 50d4b82e8ff5fe893cf61fd3d0633f28bf5aed0a.nq.gz
    ├── 515d2a1725deebef920e0f0bba458f32129594eb.nq.gz
    ├── 5253c4cee5ae375c6ebda14838c788ea6da7b7ee.nq.gz
    ├── 533712420be0a7cd6a19b728149ef860ef29f7f8.nq.gz
    ├── 54d6125dcbe9208ed08692e7a64a18271e7b84f2.nq.gz
    ├── 571f3ac981c930ed6245c4adb374116205fe3767.nq.gz
    ├── 57b4f8558456ea88e36df87359b446c28cda4ced.nq.gz
    ├── 580d2b987b5321bf9ec4eeed70ece169bf1a9551.nq.gz
    ├── 5822be692fd4f5c94c0449b062a09fed854a85a6.nq.gz
    ├── 5867f870ab7faf6d7d82db3050cdb0b9f65f355d.nq.gz
    ├── 5981e114073c431f145d1cac132c9143d68641cb.nq.gz
    ├── 5a9c248a35828e0a245e8a131c5db61751b001cd.nq.gz
    ├── 5aa9b0120eff56b23ced9d8704a81879ffb4e5b8.nq.gz
    ├── 5bbcd5888f9cc1ce843ecbb5e3003ebcfa498445.nq.gz
    ├── 5e1aa9aea5c2fc81cc664f74f2c369cb46f42dc2.nq.gz
    ├── 5e25278a6afaf2353d0f6dffcc5d5b8fb7a2405c.nq.gz
    ├── 5e5ec8d4c306111a9d3a2574ecdad33f4b7fffac.nq.gz
    ├── 5e78c22d17466275b3b3fb7cceabf92648390448.nq.gz
    ├── 62d8cf3a3e952eec23cec8a0ec7a8abfad80d954.nq.gz
    ├── 651821e50e60044b90136c93de9777bd7677d27f.nq.gz
    ├── 657ee3544dc538abe93858ae3b3d82d9b990e656.nq.gz
    ├── 6750ffe5698bf23a328046a4d2aa06e232e2d7b7.nq.gz
    ├── 67b116f29e51f8ce7d8935ce492c3c970056c46d.nq.gz
    ├── 67beaa6d8c8073fb4b8a5ebd7974831b6b11a1c8.nq.gz
    ├── 68ab48763600cb1fbe83f04c54acc3fb29b26013.nq.gz
    ├── 69b89018091b3da1e9bb0b571b8cfcfcc9dcea41.nq.gz
    ├── 6c08c8798d6cbf060e8dd8b25193cbe504968b96.nq.gz
    ├── 6d4501fae356d2475cc1bfba1891d0fb381abbc4.nq.gz
    ├── 6f2dbfaccb57de77838deed140de51d71b276592.nq.gz
    ├── 706dc64a92f59b1cf136053fc77ce4282e4c1ff5.nq.gz
    ├── 72f7d74f469b057fc6d3869a55fa963f43a453ea.nq.gz
    ├── 741dbcab8119621d289c6fc3c53d3c3fc0ed3aee.nq.gz
    ├── 74b6b2dad8fe6dbde11da411378add9e24aa1d65.nq.gz
    ├── 74ead1060cb2a0a6cbaf18a996a4b874a2c05deb.nq.gz
    ├── 75b7b9de48af9d7da8e14fa75d68fa3ca794d944.nq.gz
    ├── 76daf5c87948ecd0bdf584473357492696e457db.nq.gz
    ├── 77036480151a7a87cf6bd6bc52004a77ccc84678.nq.gz
    ├── 78d7fb90a5ed8ebe49294aa8e51c245c1342d42d.nq.gz
    ├── 7903466b09097d9be6f5d7622f8df9ce28c49979.nq.gz
    ├── 79c49ff0417ab35c255bf88dcd309bc3b33b1f77.nq.gz
    ├── 7a71bb96e07fe7c772f02a8d1ae3a63a28c850d9.nq.gz
    ├── 7a849c069bfdc56487587085384c32567aee2b16.nq.gz
    ├── 7b233456c4cd71d0f8dc6669a287917ffaa6ef1a.nq.gz
    ├── 7b5a62ef5883a60be82c51f9d4da07212e9dcaf3.nq.gz
    ├── 7baaa4582a96f5bb38fb7f8e0ad68ee834e0adb4.nq.gz
    ├── 7bbf9694c0a3650ea3a5685c6be0e4df710c525d.nq.gz
    ├── 7c022a2e1b7c608b39bbac44a35d948348431d79.nq.gz
    ├── 7ce005c5445ab891c4cd12661d74af90c7d39cdc.nq.gz
    ├── 7dabe55e76aa127bc03ffc97195001a351b5893c.nq.gz
    ├── 7e36aed62cab9e34c38ca30290cbce310ebd7f64.nq.gz
    ├── 80bec647b9fc1b26483c3215c29694a5021e1e3a.nq.gz
    ├── 829207db4723b081ea5b996ecf0e91dc892d3e22.nq.gz
    ├── 83126f76f070335c3d1e8a045be4f0dbae322330.nq.gz
    ├── 8443914538ca809680d4476766ad0fcc50338a0d.nq.gz
    ├── 84f08b997cc26b7d71cde65c7f231c7205de940e.nq.gz
    ├── 8720adc9968097ae1d468c49a9b0ce1cbce52148.nq.gz
    ├── 87c726fa3db2e05d5a72d78ba33187d73018a4e4.nq.gz
    ├── 8893e982f791da9e65cace99f1a2938e9eeface8.nq.gz
    ├── 88c51f47cc3a7b648bce59d9a4eb4209ee81d8ab.nq.gz
    ├── 8a4257542fc80a0e45849d98fddc16f562836641.nq.gz
    ├── 8aa9ac3f797806c469b78819f7381fc607617a2a.nq.gz
    ├── 8d31863cbff10a1cbd2d8ae4ecec8448403f602b.nq.gz
    ├── 8eacf2655bc20717bf043b79a9b7eb8f0cb143c5.nq.gz
    ├── 8fa4024eb4735527ebc9af47ff595f5ff2a163cd.nq.gz
    ├── 8fea3e54515636139a4ddde0e4fe7ac0d03e7962.nq.gz
    ├── 90441896df365c3d5a62b31d92ff20803d17ec57.nq.gz
    ├── 90c26a020dd34166ebf3757311ce5eaae43f70b0.nq.gz
    ├── 9125f5c5405c67104e8c7bc32beff00302128f45.nq.gz
    ├── 93b4124741ae89c2d72236fea57d5445693bef0d.nq.gz
    ├── 94a5edf6bbd124a4abdebc0e9d6735cfefda4596.nq.gz
    ├── 94f05d85107b012e30f92d80cd2cb1dbc26cc280.nq.gz
    ├── 95216b0fbcca7597a6bdc53d503aa879e889b1ac.nq.gz
    ├── 95f42f0386db0409f8635bfe89cf65d15807ea18.nq.gz
    ├── 96428e562f9eb8ed37893e9c5b3cd9e51ef80863.nq.gz
    ├── 9652135088613950410980679d8785741c0092c0.nq.gz
    ├── 965c556a1da6a6d19c18fdb71b00c2cb03c3bf1e.nq.gz
    ├── 981ca65a8eac5b7cf662a8ac3889d191006c987d.nq.gz
    ├── 9a1bcef8e8e3507502d0fbb68ed1de8ebc569848.nq.gz
    ├── 9a1c2556961147adfc153fe14fac9e9fb24352ae.nq.gz
    ├── 9a2ff409c8870158d1e4e926e7d93cec8aecce89.nq.gz
    ├── 9e51a031ebfbc721ea3806a2192562c33a4a18a8.nq.gz
    ├── 9f8034af8fe3cd8449753e731cbb64ed65dec98b.nq.gz
    ├── 9fb6a9fd7d71857e3d3033b5c0027c9d829f600a.nq.gz
    ├── a1c0b989759a3b92b98e3b742a11b8a352549e45.nq.gz
    ├── a3bd9c86cc7a532ae2cceccdedc1fe4ffecd2d01.nq.gz
    ├── a4cbfe7debed2e56f2eaeba17b6ab849086759f1.nq.gz
    ├── a521e1a38cb22c8f929e51ef09c14c723d707516.nq.gz
    ├── a69b79a90f8a978c912cffb40bb37f45247acf3d.nq.gz
    ├── a74c76378405e499b310fa95f019f4cdc478379b.nq.gz
    ├── ad6cbef18945d1963fe7cb33fcfb1bc769a4f7fc.nq.gz
    ├── affdbe271719797af29424471068b804d1d57a43.nq.gz
    ├── b0d9da7df240914972e831990eb04ccdb636d384.nq.gz
    ├── b1951ffb8c3de50bd6124cd5fd07e7451894744e.nq.gz
    ├── b37e6ea03d3730c8daf17f8f39f595dd4a12e482.nq.gz
    ├── b4a3e66e90e3b5c9df26606a03141907c2b9ab7a.nq.gz
    ├── b4b4f4ec24d2d0b9c55a4c19b3024d90340b4914.nq.gz
    ├── b62a8605f7b94bbc34b7715ee369d1fdb59f5877.nq.gz
    ├── ba757e1329355738aba75d4661ba4bf8e6a41c14.nq.gz
    ├── bb36b2ec7e3e4bd2b4c1c52ba8b6dd68a7792132.nq.gz
    ├── bc4c02e41be529fd528df35c2ebea5789c93f6b8.nq.gz
    ├── bde7d8ed8e47a6248e5ee094a186a02d23bc44a7.nq.gz
    ├── be0cc98cc1002c25222bb271b4e739075fbd7a9b.nq.gz
    ├── be75890ed611717e9e5a06ce8313e5c8e2cd31d1.nq.gz
    ├── c028b9a668278ea38510856f35c4e2718636f0d3.nq.gz
    ├── c10a297b3e0464ec6020403f252f9b222b2ffb97.nq.gz
    ├── c1b98b8d65c9e0d01c2528e8134fc94842835c69.nq.gz
    ├── c2ad90ae0508bc77db7c1ae44882cdc7c50de18f.nq.gz
    ├── c4981b5b4813b451264f2795ac8eba96be23adf5.nq.gz
    ├── c72e4e315015c3cd7ae2ecf41413baa4569b4148.nq.gz
    ├── c75054f0da89978896ab7d0c5d340dce83ba3499.nq.gz
    ├── c82b184ffd98ecc43151028920a022d4af7824bf.nq.gz
    ├── c95d01506f2b7cfb099d07ceabdc697156f55d97.nq.gz
    ├── c9cbc2bb9da1af92bd408686bbbbaf358ebb9c92.nq.gz
    ├── ca19b98aa3212ee48b492bc2a557cab9cd45d329.nq.gz
    ├── ca25fb2f7c92a8b249a971d84bf06800e13c5e15.nq.gz
    ├── ca61708674881105c7bb4a03abfad3341d9dd299.nq.gz
    ├── caea7ee3308861159c4d42e43d530e78e1c81a4e.nq.gz
    ├── caeb364b126b423af02c794e433034639f6c5664.nq.gz
    ├── cba80ddb60465061fa26b799833f3284d3fd5a15.nq.gz
    ├── cbdb6931b344271a2c45352a232ffb7447aaedb3.nq.gz
    ├── cc77f9a310a7e71964b87be0525948b6abd2c74d.nq.gz
    ├── ce5588d822e541dd57898bba1195a6ab4130912d.nq.gz
    ├── d0314919e245d90a1ebb02ad0ea2df6dd49939c7.nq.gz
    ├── d0d6978dca2bdf9e67eb3ed9fad327091044f42b.nq.gz
    ├── d19bdbc6c70ddbf01eb8ca668cc4effafa03bb4f.nq.gz
    ├── d1cc8863e6b75fcc723a71a5330b16fcfa99ff32.nq.gz
    ├── d1d5d9386f138681da481bfb33b5877ba6db3518.nq.gz
    ├── d2a8bfda36950f608331b4be4e2ac9e6c1d755d9.nq.gz
    ├── d2c31da09f701ba16de617343909999eb22e591a.nq.gz
    └── d5a6c6017272f2c1413a9ffea1eb41a9131e3788.nq.gz

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

[magic-wormhole/magic-wormhole](https://github.com/magic-wormhole/magic-wormhole)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
