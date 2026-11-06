# Repolex Knowledge Graph of youtype/mypy_boto3_builder

RDF knowledge graph data for [youtype/mypy_boto3_builder](https://github.com/youtype/mypy_boto3_builder), parsed by [repolex](https://repolex.ai).

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
rlex download youtype/mypy_boto3_builder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6226a0121fa2e887ce6a19bbf1341c03d69d280
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6226a0121fa2e887ce6a19bbf1341c03d69d280
│           └── chunk-001.nq.gz
└── blob
    ├── 0040e14a288f2186faba36505aef88457b077865.nq.gz
    ├── 00d45a17c45e1774809143a98f5c13a49cdf5a01.nq.gz
    ├── 015da19be663dadc8fd77ec4c36e7afb215b355f.nq.gz
    ├── 01f8a0ef71ca507aca90ff6a99afc167d9ddaa3c.nq.gz
    ├── 022b48630ad2b788b4d10a5534a1d1af5479257c.nq.gz
    ├── 025959eff94e4e89cc836f304bf4624c339cf8d4.nq.gz
    ├── 02b4c7e12e784b7971e886680175909b12162b1b.nq.gz
    ├── 045b231051aabed17b3de59e08adfb2ab44417d3.nq.gz
    ├── 04b2a0724e0922e0d9bfc24eeede2cc890289e81.nq.gz
    ├── 04d7290a594abe90577fff0d64a3913fb06c79d5.nq.gz
    ├── 05421ca85bd9defb24636f59cb3d9eb3a66bced0.nq.gz
    ├── 0580d880be2a9630e239f2b79ed4ce3ef16eae95.nq.gz
    ├── 05910868c8f2710928a9e7293207a82036f0584f.nq.gz
    ├── 05cf4b570b2d93e7fb9daca6de12e97179adeeca.nq.gz
    ├── 05f3fa4f49c6d982fdaa000228e486f3fcbc6df2.nq.gz
    ├── 0804402f98e7e6c9c2d28147cac7507c908601a5.nq.gz
    ├── 08089458fbc6344ef192c47a6fe4fc4a725652aa.nq.gz
    ├── 081987466a7cec04fa8a4b0b2a76cfe55544f966.nq.gz
    ├── 08433fb2ab0eabee82ff5c294cab9b0e8cd5994a.nq.gz
    ├── 0a80f58c1b9012eed12769fb94cb5fa49a09bff0.nq.gz
    ├── 0b1984182c0ac1de133dbd06eda22f95d9f62c23.nq.gz
    ├── 0b4847fb4702551dd0bad6495364f05b0291c740.nq.gz
    ├── 0ba79f79abfaa795da7a0abd0753c8bcf3fa205e.nq.gz
    ├── 0c42fbae2fadd0db12fcaf5dd63fa38c81f2958d.nq.gz
    ├── 0d2ae18063225162e596185b705b8ef2a79bef90.nq.gz
    ├── 0d5fada19f0184c3f2dcdc828f9c46b3b6ad2031.nq.gz
    ├── 0d70baf1f06c6a9ab79ede0fa5fd9b0a730926a8.nq.gz
    ├── 0d9829ed37e7c71e0fa4f3f9fce8bc7370513053.nq.gz
    ├── 0f50797d0eb643ce16c1714cc590c26912b95fda.nq.gz
    ├── 10bb0194c1ef9de1452bd4d2332f1a78fda4ff72.nq.gz
    ├── 11ad677b307217b4850027ed77a1019b06d1399d.nq.gz
    ├── 131c7b91e531f938ac469fd41a595cdaa3409525.nq.gz
    ├── 137c27dfad88e988ef625ad96efd8c99d55005e5.nq.gz
    ├── 13c1eadef5e2d91575a77d82b71be42f10d6583d.nq.gz
    ├── 14d497f8e42b787f959f786e35fa88f948617b5b.nq.gz
    ├── 161248986d945a548d413dc2050dd465217612b9.nq.gz
    ├── 173c742615e6ce1f1f5e930f631d82390037fdbb.nq.gz
    ├── 174ca7d2df27ac6d6e0b4f57cfa6bcc35b7dd2b0.nq.gz
    ├── 176a252d8f903dd3eaa1ec98ac16e9b060cab8bf.nq.gz
    ├── 179ab56cb90a33b22e290ca1bc937aefed0eadd9.nq.gz
    ├── 17d7bf7f727ba0148ca08adf827c837a6af7cefa.nq.gz
    ├── 17e74cdb48ac201b87456545b6db7bbc5b6f40a0.nq.gz
    ├── 185bf3adda350079a1bb24d39493c7251e9b5c13.nq.gz
    ├── 18b4d0605e0470afcc36707699fae0233a858625.nq.gz
    ├── 1984f7f82e8822c7026b260c6f54e082b840e706.nq.gz
    ├── 19ccb060ce28aa71603d49671c22838c4b63ffff.nq.gz
    ├── 19fdb16aaaaa7196ead741b0039bd1054490073e.nq.gz
    ├── 1a23fba60e13f24306c60d8a38e38e7c3b883adf.nq.gz
    ├── 1b9ba1d1fc3e106116676704b23e7c6a06a9bc63.nq.gz
    ├── 1cb921486fb9e919a1aa93cd9bae9d55f5027708.nq.gz
    ├── 1cff93171ca1db7dbae4308942d240d15d33512c.nq.gz
    ├── 1d41d294fa46b65cd34442d8ca8b1d9b6a2f2a79.nq.gz
    ├── 1dd29051f414677769e1a074f2df14501f967a4d.nq.gz
    ├── 1ed86185245b8e13cc6e0360159bf556290f9d5e.nq.gz
    ├── 1f648b2f454de9ab511abca562b80fdcbdb13e02.nq.gz
    ├── 2024d49d2839e60f73ae87a4e6e82a1e50256e9d.nq.gz
    ├── 20daccd206a2e10587741b60f2aa182f0a754c2f.nq.gz
    ├── 217a7cabf5c903fb9ae31227387cb92bf382ab2b.nq.gz
    ├── 22255803ee913683695f56658c3a884237258930.nq.gz
    ├── 22a6c4e4fd1455ed6e97ef89dc4360f952ddb54e.nq.gz
    ├── 23525121c33cc17947220d04b7e0d523e0db8701.nq.gz
    ├── 23614624e80a242a90abb359909b07b1fbb4a9f3.nq.gz
    ├── 241dbaf733cd87a07187161bb5a0039c2bee09cf.nq.gz
    ├── 2482f4a66df455c9b8e16d6a79f48963c78f3ddb.nq.gz
    ├── 24a7f91ea4a771bad888a744da62eca1ca13e636.nq.gz
    ├── 264501223617c391a61934f3939a57fe74e8920e.nq.gz
    ├── 26545a5f5631ec126ed0ce4ef307b35aeae02e72.nq.gz
    ├── 266cc1afe27a622feef83f006be3563cf7a7b6ae.nq.gz
    ├── 26c462bd261fc35ef5d4809cadbcfb46c2af325c.nq.gz
    ├── 26f2d6b3d17ed6fd7afb1eed401ea9d6c65943f3.nq.gz
    ├── 270508dea9e10bc121213c0ee3c78d6d4e4ad73f.nq.gz
    ├── 27196338b6928eb43039d855667ace5b33f299cf.nq.gz
    ├── 289b870c0bd72d472d791b0cdce7186fb415a610.nq.gz
    ├── 294f3417714b9479fdb1085f130c06cc4e096868.nq.gz
    ├── 296093d7171b9433489a07d428581bdb0ca1aeb2.nq.gz
    ├── 29bbdf4e08bd1d3290ff50cfab502863bfd177df.nq.gz
    ├── 2a5e3dca27580ff38d4f4207737a18735ca2d788.nq.gz
    ├── 2a8b14535e895772a146945983db9ed770ee5865.nq.gz
    ├── 2c4c9e779c1fea4ac6aba247134134fb87a74d5e.nq.gz
    ├── 2cae1f2c71e6dcb5d458a9059beec97dd4bebf32.nq.gz
    ├── 2d58e5187510d63718926f9251316f474f9c8902.nq.gz
    ├── 2d6fc9cba321f73092c8aa2d12b33c19cb028689.nq.gz
    ├── 2e1e0a8918f4507eb9df942f1383c4f1572c6788.nq.gz
    ├── 2e62dd5ba8e7bf0bb3476b6d56988d1449757bbe.nq.gz
    ├── 2f1a26019d3b8d8277237f0d74192b68e18b8843.nq.gz
    ├── 32fdfcd18f9b16ff0fc85d1992b3c68290e5f0e9.nq.gz
    ├── 332e897df9d7386bd28c1cef2354b905532a4665.nq.gz
    ├── 33a6baeebd1e3567ba575ab7b5eb9f40b70b0fb6.nq.gz
    ├── 33ab9bdec83d61107c2fed6139ad6f029cade82e.nq.gz
    ├── 34254e51d966751328da5ee3932811700a1faf08.nq.gz
    ├── 34e97a8f4627e76c36bf8ea409d9c7e4f177ea83.nq.gz
    ├── 35367945ba61e43ba21f2446d8fea01bf7723ca3.nq.gz
    ├── 35e5763c18ba4dd91c653d3db83f317a52fb6682.nq.gz
    ├── 363e2073e8409ff44a93640a8ffdb4cefd159420.nq.gz
    ├── 364325a372c09cdbb3035868b54f9389aeafe5c5.nq.gz
    ├── 3675462fac16e4cd58dc8ca4a49e6cc566420596.nq.gz
    ├── 373487c37e4328193f0b3691de41325b776dcdfc.nq.gz
    ├── 393cc5026c26ec8a99a4c9bf8ebeaae1c853b148.nq.gz
    ├── 397e914942599d551836721ec02725f92d6a533b.nq.gz
    ├── 3a56b4cbdd8e98eedb11b0ba265ab56f69a9ab07.nq.gz
    ├── 3a5f1833ad09f59a8be1627cd4cf778b80219544.nq.gz
    ├── 3b3604f5dbd3bd720e1f4ca3ff9466ed9437090f.nq.gz
    ├── 3b393fa574545afa6367da39de21dace1b007e9a.nq.gz
    ├── 3b88d8afbd9eafcd8bc0d7857555d39a22f3465d.nq.gz
    ├── 3c17c60fe7638e04652806d9a248c1a90e0dae1f.nq.gz
    ├── 3daeef6c47183356417411502820dc5546e4335e.nq.gz
    ├── 3dc9c8d18de8445037c75a347ef699548f583ebf.nq.gz
    ├── 3e42ea09e8772ca541432a83a273f7f3e0570d38.nq.gz
    ├── 3e8452983e9dde1547913751a21f87075e72296b.nq.gz
    ├── 3fbd1aad2ef4758ca48d945f24ad7899e509758d.nq.gz
    ├── 3fdb4dc0a2ff43d169a2eee4b0e2b375fba6031c.nq.gz
    ├── 3fe453a1832864336242a92fe0fc264df8ceb7d4.nq.gz
    ├── 4016929d48f966bf6cb9ad0f7b4d6eb51bb4665b.nq.gz
    ├── 41568d04c66697a8fbefe8fb2b775f6c368171fb.nq.gz
    ├── 41915353d83ab23803d883093488c10e92d7fa88.nq.gz
    ├── 41e96806a60caa535d4fbb02dbf51d6f3c911be5.nq.gz
    ├── 4207dd6ea6be8e13f0b9c5cf539b69dd39bc1a34.nq.gz
    ├── 422a0cb52488390eb8d9c6e27aba595959edfd15.nq.gz
    ├── 422bb4414ba25d1b797a8c2166c92395553ad25d.nq.gz
    ├── 42c8144d990fee6cf6a0d821e85be6af869dfb00.nq.gz
    ├── 433943e66f3ae65a8565db289dee2276c0a4527e.nq.gz
    ├── 43eec0a1a6b1006b8bcbe5e599f3b76cbd93bfd0.nq.gz
    ├── 441a668671c1a728d22244bc23f4d73552f761f2.nq.gz
    ├── 44a5d2cb49068d353df0f3d5e32cbb8d3ab7143d.nq.gz
    ├── 4508f4b5382a15b75fe72dbcf9b2518406943cab.nq.gz
    ├── 4592a8cd8389cab779b6c1995d06be8446bae79c.nq.gz
    ├── 4595a61e597496983c87e11167845236046154fb.nq.gz
    ├── 45ee86bf6c4a2d694e1cd9bc614a315f2f9d6a14.nq.gz
    ├── 46231e157d7dc7268ecf977471b3c69b2e8c21d9.nq.gz
    ├── 46f2e10e5bfdbfa90c85e40bc29abb4decad0a8e.nq.gz
    ├── 47d25af727f23cb05583ddd8e4462119baf2db1f.nq.gz
    ├── 4838b80c8ec9573bef418e32cf18a17b5628c3ae.nq.gz
    ├── 486e8621e03317c7c789c182379ce7da10f08918.nq.gz
    ├── 48aa4770c9ed37dd8c4da11bf7932dae056f5384.nq.gz
    ├── 48aaf7496d5a55e683794d36679ef76fab199e4d.nq.gz
    ├── 49a9a2a8085c3fb41a2af755d0e80f7fcdf340bf.nq.gz
    ├── 49b48321316384dce3314ad0b84b4aab468e84c9.nq.gz
    ├── 49b83f2450a0a8b766f2f28094036eb522fd6f63.nq.gz
    ├── 4a2f694ec41c456d7ed04eeb02adfabd3950804f.nq.gz
    ├── 4a8b0c276f85bf136e0316a5934b4f6355e80c84.nq.gz
    ├── 4b9b715757d88a7ee9a96d3061d84ad5377ca11a.nq.gz
    ├── 4be04f3123c13848c183b30a1ffbfff3b19c1d82.nq.gz
    ├── 4c156ca8b3b5bc448cfcb7e817d5cd8b3569777c.nq.gz
    ├── 4c49835b19948260e6d878fb3376036c7ed6b031.nq.gz
    ├── 4c77278c750ea4887ca06908196eab2f1e53c45f.nq.gz
    ├── 4c8c96656719382ff232feef50192d7c6e4cc1a8.nq.gz
    ├── 4d0bca1e9f7858f1151d7d869e53833d4725b616.nq.gz
    ├── 4d795126b59a5f61b1bcbed974bc1d3afbdee182.nq.gz
    ├── 4e0a8932198fc93512ca031ed7e271910eb6a281.nq.gz
    ├── 5060aa7332055d5a2305e5102cd6dc2d8ce59039.nq.gz
    ├── 50b44ea9db4e178c78aec26963ab76e6ed564ac0.nq.gz
    ├── 50e21757b8decc1609eabe6b76154039f51a06ca.nq.gz
    ├── 51652adea2b37e70d56624f853959cf317136e26.nq.gz
    ├── 521061a15ea9118cf274d8efb22aa78cb60f2fc8.nq.gz
    ├── 5229daade81d2feece4f26ae6b10c877094ee2ac.nq.gz
    ├── 5254e31fdbfb350676f148040e8058cc98fb6ade.nq.gz
    ├── 528f53e961427d8f1545d7d035ad37aceea75800.nq.gz
    ├── 53fc71bfb1af369156b0b95737659b5a2775e993.nq.gz
    ├── 5422842c551a82ca23d951101aa933801901b20e.nq.gz
    ├── 543be0130c8d4e5a6b5bb9c5a766d31f35e6e190.nq.gz
    ├── 54cb89e673728d3fe8a26f81c67f08e73bfd3608.nq.gz
    ├── 555bdc802837c70a1bc8ed2802af936b40aa7543.nq.gz
    ├── 559fd88812221732f67ea7e877222855d67a55ad.nq.gz
    ├── 55b2fce48cca8401a759292a64fccbf539e2a333.nq.gz
    ├── 5633ce348fb04bfc8e6580e175f2c049c367b37a.nq.gz
    ├── 567fddc5b6c7839e469fad23f96ab7021aba4cfc.nq.gz
    ├── 572eb995f5025e6582cd7632e0add2c29dfd18b8.nq.gz
    ├── 5793b4fd18004c7c39cfdad7639f61d638d72024.nq.gz
    ├── 581ece51d6719ed275d1744ad7b34c48eb632755.nq.gz
    ├── 5847818309500dee8142ae9be3c6b75e6ddcea2b.nq.gz
    ├── 5905502b7716bc5c0704e09f179a3f3a43703cb2.nq.gz
    ├── 5941ba35bbfd51ce102d2b966542d7615db017b9.nq.gz
    ├── 5943f2cf290d7f0c7aeb023688710f388e6f9187.nq.gz
    ├── 59ecd5732b42597340dd93fa57f475a4a61b00e1.nq.gz
    ├── 5a1210824748bc758407779b902637587c5c91eb.nq.gz
    ├── 5a3ae23d7c7f159592f4bf0e81c4a1725317547c.nq.gz
    ├── 5b536e1865de6f14b6dd6e475dd9bf8356530546.nq.gz
    ├── 5b67c8736147ace7d0861fc99da21bc9a9ae9a0a.nq.gz
    ├── 5b77ecaba503a81483cfd0f786898ce36f9caabd.nq.gz
    ├── 5b7ee7748839e4f2c75cea03c469dc2adac1a29a.nq.gz
    ├── 5bf78f6a1c2ac2058944c84b95d0c7e732e2f6aa.nq.gz
    ├── 5c06c2038137730d9dfc081a8531df9df1b5df98.nq.gz
    ├── 5c5db5579f561ef8b61925e53c00b191ce29e06d.nq.gz
    ├── 5d0e96b2964c5188d7b38daf5db747abae90a024.nq.gz
    ├── 5dfd8a76194909130fb39b6194c43777df521462.nq.gz
    ├── 5e3c00c3de4e5392860a63dbc133f05fb65380dc.nq.gz
    ├── 5e512edceec636b9079f5fb1a3526ce8e7916fa1.nq.gz
    ├── 5e8545ae107c60598e1d7b5786281bee90de44fb.nq.gz
    ├── 607f450bf4296bf6b541c98fb907193f97977eea.nq.gz
    ├── 6155726a6e41535b7dea7f8db5fbde0aa35b9050.nq.gz
    ├── 6173cd0b46b2da77d97c1e397a7260b41fc3adee.nq.gz
    ├── 62492daa82aceaeb2beba79548ad14027a0a486e.nq.gz
    ├── 624e47b6e54d1b200bcfb2fa3bd836f83cc88710.nq.gz
    ├── 63725c7fd5a7159651036f13e2e1540b0d81ea23.nq.gz
    ├── 63965e6309a20879e588aace7c1b1f40a4a1601a.nq.gz
    ├── 639d7bb533dfac4d1e141cba155c0c28af78b10f.nq.gz
    ├── 63db46452d9138e0ca24c87662046da86f301b82.nq.gz
    └── 640cdeb8615af5ef8ad5a75f7c495a567a81cfae.nq.gz

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

[youtype/mypy_boto3_builder](https://github.com/youtype/mypy_boto3_builder)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
