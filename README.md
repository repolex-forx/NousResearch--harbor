# Repolex Knowledge Graph of NousResearch/harbor

RDF knowledge graph data for [NousResearch/harbor](https://github.com/NousResearch/harbor), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/harbor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 783b9670dfe5573930c590a3b4971371a31af4b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 783b9670dfe5573930c590a3b4971371a31af4b4
│           └── chunk-001.nq.gz
└── blob
    ├── 00cb7c9f8c3e8c85f5868664d073fc2b5dc918f4.nq.gz
    ├── 0177844390c46fc50e12335d3aa8145236b43102.nq.gz
    ├── 021e040b15d0bb1874cde63e732c170bbceb30ae.nq.gz
    ├── 033789a92faafc34bb747b3d960176c426e750fa.nq.gz
    ├── 033986e360f337536c9e5f325356cb51c6ead32c.nq.gz
    ├── 05eb81b42dc46c5513c32746fee91ab3c39836f3.nq.gz
    ├── 06f3d8a9293f340fc7a081c5aa28b22b663b50cb.nq.gz
    ├── 07c927356f27b94033174f603d00a81d6d4aaa48.nq.gz
    ├── 08449146a1ac65566193b372a94a3503a86aca3f.nq.gz
    ├── 089cea0f7a729ef4721c5c6eb0eaca0e65205a0e.nq.gz
    ├── 09b25c4e0f4eb92ddb22a1f72a1edd4e1e38b4b0.nq.gz
    ├── 09c612613014f2a9b766ce411ad4f76669e9919e.nq.gz
    ├── 0b277dad8051bb8a71a847e7acdf0ae5ea0d27a4.nq.gz
    ├── 0b42c940c181a7e5aa0a96a3ae7be3cdf509457d.nq.gz
    ├── 0ba06f83c0c2e462e3a36dad46fc6084fc1a3983.nq.gz
    ├── 0baeffa8a88129db1f857d723e89567124390a1c.nq.gz
    ├── 0c41fa5e82099c0ca64e1f944f0b8a53d142dc00.nq.gz
    ├── 0c64e5662f01a08765cb2620801366eb5fa65587.nq.gz
    ├── 0c76a0596ed0be39b96a6b414d3c5040950e8bdb.nq.gz
    ├── 0c997c835ae882877dc8a4c2091634228df835a3.nq.gz
    ├── 0f85df5eb3d95803de4b97465ae29ac5a8446b30.nq.gz
    ├── 0fea1009b092fb0d9a640b17c6592207070343e5.nq.gz
    ├── 11b351881730063db3d47ac7448322ee97e75c45.nq.gz
    ├── 124955b3484b53106e274fe183982c47768146f2.nq.gz
    ├── 128bca31ae40ee3f75b8bea16aed2fe2eb674860.nq.gz
    ├── 135b319de34174bd26d0485a2808a7a6872d4310.nq.gz
    ├── 13a5bd2bb859093d684529d40a4be49b68df03dd.nq.gz
    ├── 13e36b73462b69ccaf9c2714bbd42c6ef3305d8f.nq.gz
    ├── 158f0bb73f9317439a903f4711039e3c08bef2a8.nq.gz
    ├── 15b91ea3162985daededa031b4a496159f457d34.nq.gz
    ├── 1668614cfa78e4d737f8f8ed9aca5f40c386f658.nq.gz
    ├── 17f904ca078678b50e32934b5d885001f2256511.nq.gz
    ├── 190ccfd8454a62d36a6fc58426d14aa743a9c639.nq.gz
    ├── 191f52b0963813b24396ab5d68a831706fcdc610.nq.gz
    ├── 19618b45b6d636ef2ed3bbb88c9a764725201736.nq.gz
    ├── 196aea73b5a06c9088d5bb60a7197b55a3471fd5.nq.gz
    ├── 19871bdd26766e59ea13df28797a92b6c40bcaf0.nq.gz
    ├── 1a5235eed5c548d2727b7788d87cdfa14e17bf31.nq.gz
    ├── 1b9e837321fb07caf1d9e4b0833b9d87c6e08337.nq.gz
    ├── 1bffdbda603725dce2bcc949197740dea372c43e.nq.gz
    ├── 1ca23d4df425e0bb61bb7740caf279ef9b1e3f31.nq.gz
    ├── 1ce9c51d4ca63118a1d50640214c6a75c2b26e34.nq.gz
    ├── 1d5b3a435ba6d2e83fc4608699c14018675e9bec.nq.gz
    ├── 1d6628da5d1d665f64591301a11ccd03b1fa1896.nq.gz
    ├── 1e28a6f842bb97064566b84d7df815d9c24bb3aa.nq.gz
    ├── 22b3e94496bb0199573f659e670ed9e463b098cc.nq.gz
    ├── 233cf8670e0e17b1c484a4d3fc72e34bac7a1455.nq.gz
    ├── 24681636c9cbabbc41cb43deb20839e8657d8f4f.nq.gz
    ├── 24a2186627d8920051bae83faffb36d16ede0aba.nq.gz
    ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
    ├── 255bc564640308135e62cdc775abcd550ea90578.nq.gz
    ├── 25943baa9ad536c068d5ba2c142e2804cf5fce89.nq.gz
    ├── 25dcec26e037ce4cf058320f0293db25fad6164d.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 27cc18f23491ce7cd6c09fdb483009b12e41222d.nq.gz
    ├── 28305c3ae310b6406c766b01a2679ed37b471868.nq.gz
    ├── 288297a175afae36012a4c23eca293d5af1862f0.nq.gz
    ├── 29a1b811a6caf29eb4fecb5a1650fa084c817197.nq.gz
    ├── 2a526c4e87324d655e2d0d33e980a077d9684c5e.nq.gz
    ├── 2db754bc65f62a9a2e45a1a1989521c3e4e3a090.nq.gz
    ├── 2ee4885a7978abb1eb6911ab726a11ef713d2ddd.nq.gz
    ├── 30633fb936e7788101223925dfe4bc06c537fb1c.nq.gz
    ├── 306b33d0bf12cef154d6fca464042ebcb5f1cac5.nq.gz
    ├── 30ca7ec3e2b50a0dcbe61ee7d7fcde841858083f.nq.gz
    ├── 31b59db40499369896cb44c9946e480760cd240d.nq.gz
    ├── 3219196be43bce22ac3b95869622f1a8358b1530.nq.gz
    ├── 3461679937e47568920b93b07890618924b37234.nq.gz
    ├── 37100efcd83a5f3659aa12fb6946cecd70167c47.nq.gz
    ├── 3757a44d50dd953776d32b9ec3b617cc439966d7.nq.gz
    ├── 39b738e101670e7c54f7af636ae953760ab9e480.nq.gz
    ├── 3a255adf5053d7c4bf6638c603a7fd65e8712cf9.nq.gz
    ├── 3e06120c8f5f573ee5da5347dda93acacc571072.nq.gz
    ├── 3ea5a1cbe708155021248f61020046c77a8d7f7f.nq.gz
    ├── 414ed500eeac6e52d50ee4f3e7180995e66dae31.nq.gz
    ├── 419be1214459bed6df852d026a9eea02594d52ac.nq.gz
    ├── 41edb904f39ec14ae84c84a7f1190631de11442d.nq.gz
    ├── 42c9924252f6dc8aeb579a39a5f0cf15512c0c31.nq.gz
    ├── 43d0b41e6c1e5111e21b655d21a5877594e2eff0.nq.gz
    ├── 43ee472c59defc2847a78ada1ff7053e1197b88f.nq.gz
    ├── 44e7296046348d4a19f0cbd4e2d34cb85d87c58f.nq.gz
    ├── 45472bce76ff13620208a60152b6653cf48dddc7.nq.gz
    ├── 46aaf479a9c51795c0ed06f2216c74d29fda88b5.nq.gz
    ├── 47332a29992cc46e5ce4e9ebb784098cffd9cd22.nq.gz
    ├── 48243f2421c3f837b2322bb5bd4324b9ca2eb91f.nq.gz
    ├── 4892adea9d94c85f773ffa321aab490c57e87117.nq.gz
    ├── 49dee3bd7a4d21478f2cdc099fe031e7bc6c9223.nq.gz
    ├── 4a35f1f236044f7b039a2ecdbefb85fedbe283d9.nq.gz
    ├── 4a5d3340a4b8c3c94bc5f02ab3d798a9fea813a6.nq.gz
    ├── 4af071a453e8beab083d37faa587ec8f6767bf6a.nq.gz
    ├── 4d883b748da3b9d517d848a3d028c6f83d0c0753.nq.gz
    ├── 4f16b96ab283e0a7716e996d99ea6d213222db3c.nq.gz
    ├── 4fd1985db26fa9d6df72bc144295a3b0fe2387a8.nq.gz
    ├── 5149b262e61dcc1fc1a278ba098c4a26df662c42.nq.gz
    ├── 51b19f39d4956ba7e93b23f5821da860da2a38de.nq.gz
    ├── 536a5fc973b33b2ce73d2d2a44882611bdadce92.nq.gz
    ├── 5518d0a23090ccb4bf0c206c5ab917735708cdb9.nq.gz
    ├── 5632a42e94b54ddf551f11501c634da9cca2810d.nq.gz
    ├── 57794848b6180c025e74b4254172fe2a1ff2777b.nq.gz
    ├── 57c80b318d07897e493917df55b3208d05064ad1.nq.gz
    ├── 57dd896a40c727cfed783a4b260b36dff3347891.nq.gz
    ├── 5810dd4e53df4ef0d20b34a4953123c8256c0738.nq.gz
    ├── 5812661ff3c4b192a7bab12e9eb6c6f92c6e511d.nq.gz
    ├── 58906cf38a6445484817377bb9914006589c3689.nq.gz
    ├── 59b6d903b1c6b8ca2ee24cd6cd83cb02d87bf642.nq.gz
    ├── 5a26540b3436734be9b85c11830b6f62ae5881ea.nq.gz
    ├── 5acc20acf55561635153c10d59c4147e355d8513.nq.gz
    ├── 5b2a52404e4f61d37f23a177d72c8592d974d93e.nq.gz
    ├── 5bc3c4bfc836cbfc9437e9e26169041cc53ac602.nq.gz
    ├── 5bf074752be2ebe109a81beff82eb430ac009b3e.nq.gz
    ├── 5ddce8667134640063da670a3f669141428fbd3b.nq.gz
    ├── 5f1d112308b05b67c05d59972398eb7a9bc4fffa.nq.gz
    ├── 5f4d9227952f7bb01030c523bcd45eb8ef9d934b.nq.gz
    ├── 5fa00abea26ffbe27535671f31c1f4e10328512d.nq.gz
    ├── 6021f79c5883070d4365549034101161a7c9a34e.nq.gz
    ├── 613a800e1c4cf1ab9bfd65cb757bd053ab7e5183.nq.gz
    ├── 616f5d354d89c1ac5429f7460a039f48e022bcf2.nq.gz
    ├── 61d2b12f7162afbf7ef4fe5019639d4010f5b54e.nq.gz
    ├── 62e10aff86a786f1232594fe13b91107a689d408.nq.gz
    ├── 66294a5867b0be1ea30601962214b34819fcabe7.nq.gz
    ├── 66caa9069d82fbae418518cd687c22f9f28febd0.nq.gz
    ├── 679ab77bd98e824ae12af5a95482b6af512321d3.nq.gz
    ├── 67c9aa4f2da48f60492183c8a1df59af3213706c.nq.gz
    ├── 67cbe0d54a3f9fa8fcf2ff22788d9fb2d9265721.nq.gz
    ├── 6836136b1a0e1400baf484088fb087aca0b838f4.nq.gz
    ├── 69be31abd65a267e3a15cc864a4c38c300a5cb99.nq.gz
    ├── 6a260d6ae884da735f0e2b9538a8d2af1f19ed47.nq.gz
    ├── 6a8df5bc54213090c586a0cb37573df9e7e0a31a.nq.gz
    ├── 6ccd6b992cf73971aee0e34ae1e01564aa7cb67d.nq.gz
    ├── 6d37de0898fabb39a1bf57f973e5e56f558c1fb1.nq.gz
    ├── 6e2bce3113d1c5eb32a317e3b2768d9d4e6d2845.nq.gz
    ├── 6e6267cdf04eccde13d021ade271651c7f4dc8fd.nq.gz
    ├── 6e6e708f77e33842ab4715bc1f09aaf60454696c.nq.gz
    ├── 6fbc154126b175d8b6b0b21d23cd3b1a20a40b89.nq.gz
    ├── 6fdf37479c10d8f7f1b48417294168e7e134ee98.nq.gz
    ├── 70c07081b83c2ddec679f763f352cbfbfc4dea12.nq.gz
    ├── 7146042d430fbe7b0544ac005a251de2bf2cb9ab.nq.gz
    ├── 7231cf4e2fabd4456425ca437801acc9bbd9033d.nq.gz
    ├── 72ea141ecfa1a7fbc9084512aae4fcb975cd2e53.nq.gz
    ├── 73f7f9c963ae261df144669550564457a327fae8.nq.gz
    ├── 76f7e973675c241cc39336da6505d553db67ce16.nq.gz
    ├── 773110d4a1cb1c0bae7be855f167bcf0b1829fa1.nq.gz
    ├── 790819cadb7c7388a365def4bde7e1127a56bae4.nq.gz
    ├── 79342767d1955e02eecc0353a8edaa024981533b.nq.gz
    ├── 7a48870b9f2bd21bd3dfef258e63d6579dedc5df.nq.gz
    ├── 7b168daeb9207e45791a32a092cecd65c054f558.nq.gz
    ├── 7bf1f273db16bad297d008d9c3eb7448e99eb274.nq.gz
    ├── 7c48dde99fb9897138700612ed547b3c87777c74.nq.gz
    ├── 7db8181f36b8e4b5a3249ae8032866d6ac334b15.nq.gz
    ├── 7e27e3893a899d1d4de95890a76a335af82c80de.nq.gz
    ├── 7e6a57446b75eee51ed83fbaa06f2e3050968fa2.nq.gz
    ├── 7eb94bd966ccfdc92443c82adaac31b98b46aac0.nq.gz
    ├── 8144459c73cdc9eae2f7ce4b1541f30472c546dd.nq.gz
    ├── 81d62f9005a64a686117857a0493f4228c5425b8.nq.gz
    ├── 81ea0ccb73b90f35dbcf59342079a771202a9171.nq.gz
    ├── 8293e0882f8eb86944bfcaa56b0c6a44234448ba.nq.gz
    ├── 82f7bdb5a908d95eeeff0462f87fb8538e0c2e71.nq.gz
    ├── 8394527ba342a1eae07b6e98c4ee48a8d7a671af.nq.gz
    ├── 83a8e09121c42b085dc57a06282d2c009538499d.nq.gz
    ├── 83fb710f9684706ffb5f67e8b22da82700e8676f.nq.gz
    ├── 8434e4de374e024c6850e3bbbcf7ffd95f317781.nq.gz
    ├── 864a113a9ec03d5ed8b258f911c91bf7dbdca9d3.nq.gz
    ├── 896efeec1e32c55c31d2123f5ef3f82c1b2f0995.nq.gz
    ├── 898eb9a724217e6c933785666c7a05c4541ef508.nq.gz
    ├── 89981543bb2292bdb01e38af670446b4d0d3fc8d.nq.gz
    ├── 89aac3e806bce8b6acd7bb08be0269829f679e4d.nq.gz
    ├── 89cd230f9ad6b3058657014a810917079ad9036e.nq.gz
    ├── 8a1b9dc0445e2f595ceab4177d779242f16c5d9f.nq.gz
    ├── 8abf4fec2b4fe964f041bed870b3c09539a58a4a.nq.gz
    ├── 8dcefbe70e897d66cad2e3f02a8c5faed21d5567.nq.gz
    ├── 8e0d94889b5928064ce286fdcbf4e889f4b919bf.nq.gz
    ├── 8e9d2b8ecae41b50c169de52effab64271617ade.nq.gz
    ├── 8fbfbad033a4f6e503fdce12b64984ef9f64e050.nq.gz
    ├── 912599c96eca3a91615a82c733fc85f864242f76.nq.gz
    ├── 978367b336c980d720577bc4a0349cc4cae0411d.nq.gz
    ├── 98596da9881ae0e02f5860e95c9a919f2dc90c32.nq.gz
    ├── 98bc4f332f017f376a614bf24621a2b3abbefe56.nq.gz
    ├── 9bafc73666fa5678de050f3030a820c086bcdd88.nq.gz
    ├── 9bcd853967eaae7341268a376a3477e453130173.nq.gz
    ├── 9c2027ba3dbd553891fd76f93012f421688db6f6.nq.gz
    ├── 9dc08f8d73cbbdab42c50b5b6db85ee37dee69d2.nq.gz
    ├── 9e4b7bacfc292e6a2f0ea00362297d729e13f2c3.nq.gz
    ├── a1be4fa78a423994a2656c30f7aa7b5231397461.nq.gz
    ├── a2c543d36f4e5d512d685f2a9e2ebc5ca0668859.nq.gz
    ├── a30c3fca27c697862f136ced6abc2d74c25fadfe.nq.gz
    ├── a38db8e242e25c9b1b8b7f702322166ca7c02ae4.nq.gz
    ├── a3c8342847b3e4598f5e2ba0fbe1d569de1a21fb.nq.gz
    ├── a52055c20fb75a9ffe1e593f3573cd9819113d90.nq.gz
    ├── a58c84c1409a989b1d923efd32b28392e7d91cc6.nq.gz
    ├── a5ae44761a9924327490ec93563b0c9e15f9c80b.nq.gz
    ├── a60710a5d097467d0e24539d57f86bccc740efba.nq.gz
    ├── a7968becf1eaff6d737c87af1b77f3dc7f50abb1.nq.gz
    ├── a7cce0cb03b84453c9956f2687471ed616053ce0.nq.gz
    ├── a85aa1fd310a94108abc8b968a79352cbafedf3f.nq.gz
    ├── a9252ac7da15d0104302916912eed75f103b776b.nq.gz
    ├── a9be66f2840e2694069e92b92c5782a28a2a2d60.nq.gz
    ├── abc9ce3e0e444c3304d6dc2063c32522b8afd245.nq.gz
    ├── ae9b29610c3b6dbec5cb872a5fa5de6f2883f367.nq.gz
    └── aecbfbdcec1ae7210edac6fc9b154e7bf431dc62.nq.gz

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

[NousResearch/harbor](https://github.com/NousResearch/harbor)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
