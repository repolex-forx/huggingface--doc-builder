# Repolex Knowledge Graph of huggingface/doc-builder

RDF knowledge graph data for [huggingface/doc-builder](https://github.com/huggingface/doc-builder), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/doc-builder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 90ddd199e07144a13408c523680c76987343c95f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 90ddd199e07144a13408c523680c76987343c95f
│           └── chunk-001.nq.gz
└── blob
    ├── 034e164576c42ab5faa7d8e49ad0bc159bdd1e29.nq.gz
    ├── 0365732340a3c138259c1e187b5dc6d31ecc4363.nq.gz
    ├── 04fcb0203c63b35dfb805226e992341ccb4bfc1d.nq.gz
    ├── 062b4d1181631fdbfee3c67f7bd1950991f7e40b.nq.gz
    ├── 074d2ae3aa7f93c784947f3290d03524fdd60217.nq.gz
    ├── 092fcd2cf55ff52d26738b9413c4da536ab2aaf9.nq.gz
    ├── 09a0554972736cf37d753486053866b7f7142749.nq.gz
    ├── 0a354571278bf21608d8b6d99d7cd62d538774af.nq.gz
    ├── 0a6b65c247a68f312581885cc16b435d1d63c1be.nq.gz
    ├── 0a8f82e3aec44c4fd2895bb5a1dad49015c7cfa0.nq.gz
    ├── 0c5c66e2c157730cc4c4a2d6d1dfb588d0e5d6d9.nq.gz
    ├── 0de921405295e24ecad024d59ac7cc40a08445b8.nq.gz
    ├── 0ff08795b4c38b4f8163e70d1f5d03fe68e68799.nq.gz
    ├── 108f580dfd17465c8e9a4f8f960a544031a24e24.nq.gz
    ├── 11d00eb3036296c02bf0fdfc39f9f875e34dd6ea.nq.gz
    ├── 12f7213d4c987e1bf9f077af350a7cc0206e9d47.nq.gz
    ├── 141f8e4b52b0c6af5c07483b7615a38989cf45ec.nq.gz
    ├── 14a36c3eaa9c2d9cbbc6c289966a777eae4e8b51.nq.gz
    ├── 14f21e9e67bc672ccae31c4e72099ad0def20375.nq.gz
    ├── 151355346b9593365274391eb6fac4ef8787d959.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 1676b170402de387a944dc409c71fc614a178931.nq.gz
    ├── 172006ef27d2a17bc97105867883d61f1b871058.nq.gz
    ├── 188b73f568a92f23bd6b8d73d923b7576e5e3d18.nq.gz
    ├── 1894de40be547e715d7df6ef32e6be8024485297.nq.gz
    ├── 1ae05ea94f8d9f4223e4e85a1604abdbfa25f5a0.nq.gz
    ├── 1b1023d89f6f1c578e9b7ffe2b25a9fc683afc77.nq.gz
    ├── 1b439cf626ca56d651fdcf4c4e3a806598b352d6.nq.gz
    ├── 1ba5929f1675b919302c6b2e305c4ebc3cd1e94c.nq.gz
    ├── 1d85221e448037bf0ddc8246a87d4c8cfdc774ac.nq.gz
    ├── 1da9ffedde44749819e07f7f9cb6317a8f68afd9.nq.gz
    ├── 1dc39bda046511de169f2dd3fbbfb33041f223e5.nq.gz
    ├── 1e6baee69db48fcbd951c7190a6059670eb8c753.nq.gz
    ├── 1f1e467744e788a40b2c3b75c70f8d8b798cf9fa.nq.gz
    ├── 1fab62a44d9c2940b644bee8e8f25175bcb2cd67.nq.gz
    ├── 203fd25be5070ee304da5756f2b7dd0fee10595e.nq.gz
    ├── 2106ecf0d44baa3072e0473e9da513a2cfffd353.nq.gz
    ├── 21168a0a4fc3296373aa6edf0d22e523cd642ca7.nq.gz
    ├── 249c02c4cfb7588a2c6737a30e201e74e73ddeba.nq.gz
    ├── 25f22d7abc29071b1ef53be24576c3a71ccb7848.nq.gz
    ├── 2614806547da3a3f472ef755c3b800f2eaac487f.nq.gz
    ├── 279e43d36deea6acd850a9c3a5f40f21b2766260.nq.gz
    ├── 2805dbcac54c1fd90eccf24816ded7aa59ca66dd.nq.gz
    ├── 2aaad1cf0522a99d94d5c2513b7c7f7593de763d.nq.gz
    ├── 2d5da55ab63bb49b8168ea3807841db3da289bf9.nq.gz
    ├── 2f64c1ce6dd669c412b7df205313e9b8745d0cf7.nq.gz
    ├── 2fab673170fb0a937a95931aea86d317b44aeaf3.nq.gz
    ├── 309402a7579fb30c49b9586f4163f1f4b1969160.nq.gz
    ├── 31907d413244cd8ddcd393651f4218f9fd996f71.nq.gz
    ├── 31b6af172e18fd5a6cb16c1257f9be5d6a178209.nq.gz
    ├── 323b1b321cfff5886ef2e5aa14dc9612133e0024.nq.gz
    ├── 324ed5a2b118453347a12dd8ce93bffb3f867138.nq.gz
    ├── 32eea71c12534ddcfc297ae72722843b531f4211.nq.gz
    ├── 362961d3989aa1e7f8ac4175700f52405fd1c349.nq.gz
    ├── 37bdbfebfea5fcbc5e3b28f5f3d2a507e8e9d32d.nq.gz
    ├── 38972655faff07d2cc0383044bbf9f43b22c2248.nq.gz
    ├── 3b04f8ca0c8777483abe372b849b867ec0a93337.nq.gz
    ├── 3b0648194106dbd47e4017741087e4e183ccb99e.nq.gz
    ├── 3de8f9327bb2b9c8574f93abbd3814f84fcd0e85.nq.gz
    ├── 404625ccfe3acc2ecb0dc731cfdd1ec5c12582b3.nq.gz
    ├── 40a3ecf6a95bfa7dd4dfcc192942f833607bfe89.nq.gz
    ├── 4261117d6fdff7f287030062dbe3b4315b7fc12e.nq.gz
    ├── 43a0959b8bb936c87963edc51ffeaece6ea8c590.nq.gz
    ├── 444890120fbe9c460c5be721c6a77dc2e5a3d996.nq.gz
    ├── 44b404f6c78415c499d67f3c4bf1ce403cce60e0.nq.gz
    ├── 44bb6fe2898e5b13b2c93e9050a77083c4b2c110.nq.gz
    ├── 44c63d8c86630502efc4306308a6aeb196087510.nq.gz
    ├── 464d5b5daabc6be6480a54373fbe15e0b9155a9e.nq.gz
    ├── 46818b1c2b035550c33f22736dd02e81877c2d6f.nq.gz
    ├── 48c26c7804dcbc4623a641676a6f358ef427215d.nq.gz
    ├── 48c874db6799bae101e64fc671082e5949026bfc.nq.gz
    ├── 4e0444b288adeee48210762eb79147d51c866f64.nq.gz
    ├── 4e7819e1b90a7e59868d6dfbf15d64f12c26c9d2.nq.gz
    ├── 5068705be76852d5ffc87bb95b671aa5f4e0f712.nq.gz
    ├── 524fe9fca8f4cde8497c760c06ff039f972e340b.nq.gz
    ├── 5260b1d366ebd1afe23817f82164c1f5a2748d17.nq.gz
    ├── 52b6a1e82c9dd66df6f41cfb3c4fd1731983b776.nq.gz
    ├── 53bb403efd2c7c449eef16c20652078a0f5addd4.nq.gz
    ├── 53cb47ab65d3e2ef7291b34ca8a15acdc6b92ffa.nq.gz
    ├── 5618040044542ea99801c80d7df807a65ebcac6d.nq.gz
    ├── 58fb672589ecd79c6eca6b75f3808ec2d1292e39.nq.gz
    ├── 59887275fe8a9a3b11e426696fc971adafc02e9d.nq.gz
    ├── 5a4fdadca72a7ea95ca3e94f93004826a62d4a3a.nq.gz
    ├── 5c067941aded042e68b033299a906712b334c5c6.nq.gz
    ├── 5db0f58b94b7beeb2ecb1bb7038b63832cd38abb.nq.gz
    ├── 5e605706e003b01a152c2156ee6a83e76f32b2a5.nq.gz
    ├── 5eda301821d1490eb00b1fc151b7c09ee19d902e.nq.gz
    ├── 5f41ea21b0988edba888295baa3a7c2e46ed04f3.nq.gz
    ├── 60a67def50ef24357b6ee77e0be8552cf2761d35.nq.gz
    ├── 61148d70fa6ba47e6859bfe7aa1229c8efd79ac5.nq.gz
    ├── 61cf9af52e9dd74075879b1adc1d26924443e9d4.nq.gz
    ├── 62fe492b2e7ddfd8e647ad54356644b6cfcbd9f2.nq.gz
    ├── 632df75ea2a88acef75791f9eafeaeec6c3ee831.nq.gz
    ├── 679b6fddbbf3eef607b7c20acb21a63b5c219645.nq.gz
    ├── 68b7d66c97d66c58de883ed0c451af2b3183e6f3.nq.gz
    ├── 6a2b25b3f17af20670c2b5f75a16a1d0251cb573.nq.gz
    ├── 6aac8e087be8c1cf8d940395dc9fa371236ca2e3.nq.gz
    ├── 6ae0c8c44d08a78140c9c62c1b0f745edd05e804.nq.gz
    ├── 6af7d48fc36f87f93fd8df90617f60caaf64010a.nq.gz
    ├── 6b30aff408072bb1818d9e0aa38feb3bad5c22f2.nq.gz
    ├── 6b894058b4751c8c400a0470d26fa164ebb9a43b.nq.gz
    ├── 6c51b98b6a22cf50589bf5d349c93a0ba62e0e79.nq.gz
    ├── 6ceb9d04992fc6b7ca3bd9cab7d26af7e8ec2bca.nq.gz
    ├── 6d87a42ca1f6fefaf5f6f3cefc4a27dcaf8dcc68.nq.gz
    ├── 6e2bc1a467cadb4a419aed055cd778a9b1ee13e4.nq.gz
    ├── 6e7fc870fed526e6769df034fec226f9d935c7df.nq.gz
    ├── 6ef59a83e9785f496ee271fe42781827728bc4c7.nq.gz
    ├── 70593611a61c183bae3ecf1475852dfefc09440a.nq.gz
    ├── 719e9f8cf0f4ce2b5f1d13c7a7cac718ca5d1189.nq.gz
    ├── 721aa82767e08664fc1ab5de30b154df881dc79c.nq.gz
    ├── 738449b05831813b1bfe63f82c3628789bcb66e8.nq.gz
    ├── 771d86cbdb870c37a8f5a660b4ce9ee196626c27.nq.gz
    ├── 77eb9f1d39bb1db2ff2638016ff22652697dbc7e.nq.gz
    ├── 799406ca82b1ac2b1855c8d7bbc0c3309b4a7e75.nq.gz
    ├── 79e70c60955c80709494da9c8d7402f81d0a408b.nq.gz
    ├── 7b5591a6dc0bc2fe00f8a97ea7832a37c975dcba.nq.gz
    ├── 7b7a2871f96233258197c4eab3d2cb4778721b7b.nq.gz
    ├── 7d4e9dc478c4905fddc95d080eec8ad3258e6862.nq.gz
    ├── 7f74300268a8d7fcd9d5edafbe0fdd897a53df08.nq.gz
    ├── 7fb75c3f662850a77e933ff6d3b6cc42a78596b2.nq.gz
    ├── 7fe8bbf43fb09d9bd7cd2aacf5308bbbcd1ea46b.nq.gz
    ├── 808b13b565d4abb8f4f8aac3a7ac0b7b1a83f436.nq.gz
    ├── 8187e247ee694b7da768b15619d8e82c87601f61.nq.gz
    ├── 825b9e65af7c104cfb07089bb28659393b4f2097.nq.gz
    ├── 8350b5675081f2d3a1e1317b079c73d28283a3d2.nq.gz
    ├── 840a3e84b56f521ce1feec4730a4e4bd4c224ab0.nq.gz
    ├── 84550fbba4482ed272e86bff99bc860c12066d06.nq.gz
    ├── 854f83b1111ae7d0d93cff9aea9498f7ecb23c7e.nq.gz
    ├── 86988c40bfd5470ef54de7752e81400545bb82d6.nq.gz
    ├── 8776ec7921daddaaada7408d2b8491f2df3e7534.nq.gz
    ├── 887b93a204bbcb307261cd3bb9319cbbef4e4138.nq.gz
    ├── 894d75c99c252effbd729b99e44852504f64c9ed.nq.gz
    ├── 8a3b7afe2fd8aa4e84b64cc7c1df23e18cc912f9.nq.gz
    ├── 8a57dc65d8ac850e6e624267ec92a09e06d85827.nq.gz
    ├── 8b74c26bca7f809738e66a221153e18f34b6a25f.nq.gz
    ├── 8cccbd07965816eee9071fdaf7b1d7afc9b99b1d.nq.gz
    ├── 8e1009c4ec0ee2c3d0d4a33c9a0c0654a1490e8e.nq.gz
    ├── 8ead5bab89a1d5d0625938cf8618b079e0c082a6.nq.gz
    ├── 8f2dcbc601b7d8b6303bbdfe86be9eafa604db84.nq.gz
    ├── 909e745631d84bc54ff20fb21d7152eb38287dea.nq.gz
    ├── 9142f463cfad45246e86f45ee57f41a69f5771d1.nq.gz
    ├── 91c9043a1af1888b630429609eadd630ec35b952.nq.gz
    ├── 91d2b94762d857f1f7e6db5ae653003ba03207c0.nq.gz
    ├── 92c667d1fb2fc9ea79ab5f71db68a197dfc2c7e2.nq.gz
    ├── 969ec08fd1b696f2de1bba9e2a03005220b839c0.nq.gz
    ├── 9990a562d223f33b753e03a1d4094948ba0dce94.nq.gz
    ├── 99a2bb3117875485bb69dfdc19bb9caf4efed8ed.nq.gz
    ├── 9dcd2af08e3ee75e9697cdfcc76227d89c42059a.nq.gz
    ├── 9f37045cd0e1534e139342306d3d27575a551c2c.nq.gz
    ├── a13e39cb1fc7241ac90d0d532f831f5e411a964f.nq.gz
    ├── a279fbda25dee88a4de006b6fd3bab68baca4565.nq.gz
    ├── a2c98855cb4f4fa898f8f78dc260355586a6c680.nq.gz
    ├── a4dcf12047a147434295574bc9c19f7e2eb3c3db.nq.gz
    ├── a67109c1639db0abdbe351ce62f4081f87a782ff.nq.gz
    ├── a8016fcc8140a2048d0fc6e4c13d3d64dced0b95.nq.gz
    ├── a88b7739f5ad92154404ec2087082ef26fe39d76.nq.gz
    ├── a9b56dbbbecfae16cc2d178c53663e6d1897c5e4.nq.gz
    ├── a9f79857a4f4dea1f993fcc6371d3610211b557c.nq.gz
    ├── abbfbdc537a5e81ecc02ec50e0c4501081f4ce7a.nq.gz
    ├── abde625b573e0d0538b1ea92f3df8988faa42e54.nq.gz
    ├── ac90daeb790299f27dc0aac7fc46dba999090b75.nq.gz
    ├── ad6c2b182077de7ae51f87ac53fb67515fa05f43.nq.gz
    ├── ad7bdc2e32bc6d5d47105a8f35b2aa414aa9d050.nq.gz
    ├── ae0dd30aed3f4f3b617eed99ffafcc31a00339ba.nq.gz
    ├── b04b2b303dc1a336b7c84c5e0ff0dce03832ae8a.nq.gz
    ├── b419837e54e1d1a689dcd5b49ded461da08c15ae.nq.gz
    ├── b4f539af71cbd6ce7d873f06103a26a2da18fe1c.nq.gz
    ├── b60ea0286d17cdad084724119b7916cfc17c5d5b.nq.gz
    ├── b62b346fb7a3bcd9db21dc46e6070b9ee53c5753.nq.gz
    ├── b6d67eeae50f312286e99e72a836a4bf2f857231.nq.gz
    ├── b6f27f135954640c8cc5bfd7b8c9922ca6eb2aad.nq.gz
    ├── b73016bb653f7a51fc3dde68c4fc0a4bceb7a31a.nq.gz
    ├── b786a5ae4a31c118241e68cb9aa3edbd4aebed1d.nq.gz
    ├── b7b104ac26e528eb38cf2ab4ccd257edafa8a273.nq.gz
    ├── b7b28d9188f14fd3dea2e77584704ead4984936c.nq.gz
    ├── b9d480b51a373c2c1df3604e70568f47403f57f6.nq.gz
    ├── b9e8c381941c0f04ebbccd71d3bb23e45d38dc78.nq.gz
    ├── bab7d90bfd107f871047fca5006c24621c33be0f.nq.gz
    ├── bacebf61d10e140faaa9dd44974d3e27a6206517.nq.gz
    ├── bb928ebac9dc304016a96f908ad87757e5568271.nq.gz
    ├── bbc4420a0da94f9addc674c7f32e0b173514cfb9.nq.gz
    ├── bc1835109f8a5edd0d5b62745b7f2184da3cc1dd.nq.gz
    ├── bdf7f85de532f74c5466b8ac70b89a08c7c901ff.nq.gz
    ├── bfbd0b5c6cdbf80efc2da16d83bd6b29a9141475.nq.gz
    ├── c0460f810a63016504f91726ddab62b170b0439b.nq.gz
    ├── c15de9a058fecb86cb3cf13e8f5ea7f75cb64758.nq.gz
    ├── c190b88eee62c27d39191ef8d4751d897a1c45fa.nq.gz
    ├── c3d08fdac9afb64411bc9f7558d0aa4640644390.nq.gz
    ├── c624007e3cbb682304997a611f7ecc91986caffd.nq.gz
    ├── c692513254a8234c908a86976128198f3d72686d.nq.gz
    ├── c7624c8579575ba7dadf14d820347435db9dc210.nq.gz
    ├── c77174c287df614c3e98473b1baebda770ab4ef7.nq.gz
    ├── c82057d3b9e636d1b80f445816745683a47b1b5d.nq.gz
    ├── cb22115b2c8ac7fb2918e2c7c31ed64d5f34f2cd.nq.gz
    ├── cc198a88f92f818a942ae68a295495c057787350.nq.gz
    ├── cd55b0d037cd0b91202ee8542c12c232a30bd081.nq.gz
    ├── ce0e8d5dd361e6d094e44166b6c762a0eb3ca7ac.nq.gz
    └── ce4e60decbb3cabffd9878107bbb3d6585c6125e.nq.gz

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

[huggingface/doc-builder](https://github.com/huggingface/doc-builder)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
