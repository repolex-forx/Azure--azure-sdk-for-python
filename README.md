# Repolex Knowledge Graph of Azure/azure-sdk-for-python

RDF knowledge graph data for [Azure/azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python), parsed by [repolex](https://repolex.ai).

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
rlex download Azure/azure-sdk-for-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3dc2b386293e2fea95abd206f57b52cbf9e8be5c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3e80c20b0008ba6004753004be1462f0295c4b1b
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 4f0c4fd6f2385c0bc9a1082503a9d94ede08cfa8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5cbe34e9e0b8ea1faacc9f205633ccc0b885c0f3
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── c0e7da5389a96b2ce17ea7813b8504381c377c80
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── d5c477477dcdf0e85ddb62d2867385b1055c1cbd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3dc2b386293e2fea95abd206f57b52cbf9e8be5c.nq.gz
│   │   ├── 3e80c20b0008ba6004753004be1462f0295c4b1b.nq.gz
│   │   ├── 4f0c4fd6f2385c0bc9a1082503a9d94ede08cfa8.nq.gz
│   │   ├── 5cbe34e9e0b8ea1faacc9f205633ccc0b885c0f3.nq.gz
│   │   ├── c0e7da5389a96b2ce17ea7813b8504381c377c80.nq.gz
│   │   └── d5c477477dcdf0e85ddb62d2867385b1055c1cbd.nq.gz
│   └── repolex
│       └── 3dc2b386293e2fea95abd206f57b52cbf9e8be5c
│           └── chunk-001.nq.gz
└── blob
    ├── 0002e3202f29d8fa148d7b6854023ae1d7154b81.nq.gz
    ├── 0004aa3368530b0847a866ad653e2b0ded169cbd.nq.gz
    ├── 0012ac8459c948d24110c462f9ed5394a770f57b.nq.gz
    ├── 00151217e6a00c4d5a8f77ed432df2500664710b.nq.gz
    ├── 001ed99d07b1b4f75292a445c5d6871a9c36fae1.nq.gz
    ├── 00288640c7f6e7416bc528b76d2764f4928c9356.nq.gz
    ├── 002fe48dc371fcb10f2c040c326e6fe45aae0752.nq.gz
    ├── 0035918ed55df0a80e5adb72acb5b45170640772.nq.gz
    ├── 003cf52ebc386df806815d80a9f36021f2bd520f.nq.gz
    ├── 004c7f5cba775db52361dd90c047dabe97ee0511.nq.gz
    ├── 00546d69b9a5cf1a607f6f752f4ff538ad2f89f6.nq.gz
    ├── 0055ae2eef71f6fefd07e64f921537b146951154.nq.gz
    ├── 006152ba099e15b96f82117a90dc54bc66e8ab07.nq.gz
    ├── 0062f7dc188a2fa3221d52a75705f0dee40ccdbc.nq.gz
    ├── 006dce5ba90b4804533eda26731b64cf32458f37.nq.gz
    ├── 0070d19ea6dae73ec1ca960cc8ed8d86d8c53581.nq.gz
    ├── 007949fb3b70b869881bf83fd91655911183905f.nq.gz
    ├── 009ffd7be3ca4540c8eed6c0927ce0a4123f0076.nq.gz
    ├── 00b7d27f8322309b505d38c4edac9b86825f85de.nq.gz
    ├── 00c0a7939609fb7be12946cf34e9312e7f42ad54.nq.gz
    ├── 00df8630e517fae16b0f7b0a992d16248babbb8e.nq.gz
    ├── 00e3df39b759c667037d90d0cd2524d8a0fffb4a.nq.gz
    ├── 00f67da132368eeddc96c2eccfb47552009d51f4.nq.gz
    ├── 0107cbe781ce9afdfd08340d00707d8ce6ba3afd.nq.gz
    ├── 011ae3609d774edb082449d3c1e92a0dc8f60d63.nq.gz
    ├── 0125c5440ff8d446a261a6bc539beaec696d4a43.nq.gz
    ├── 0135af994117849cd1bf85b8f28ddccee928a518.nq.gz
    ├── 013720604e17d806fe43250b15220e81079b81b6.nq.gz
    ├── 013818194144853a789c8b5862dbbe4d62133bff.nq.gz
    ├── 014062e2f0b7cb82d94aee5002be4a7543c4ad28.nq.gz
    ├── 0144f341b177ae3cf1aed0aa717378b2b8c0f640.nq.gz
    ├── 01490053cb9fd905829b36cc4370a3f6de2a8949.nq.gz
    ├── 014c9b1eff7e79194e7b397e6c4158e60012a5e1.nq.gz
    ├── 014f71a1e612bf76c4831f5c0ac362cc038a87b3.nq.gz
    ├── 015af2ba8d67b5c4a645eb4b77d6efd862a8af43.nq.gz
    ├── 0169f7655e03c850ada6ca34dc55de641887a819.nq.gz
    ├── 016c2ae36a56e40d8157e8024e9798d5f1fb75e1.nq.gz
    ├── 0177eac87b609ffa249e85931c6963210ad29187.nq.gz
    ├── 0193886919d965790a89e4098027cb9998f26c3a.nq.gz
    ├── 019a8728408f315754488bdb8794210347609590.nq.gz
    ├── 01b94548257f407c4d5d8b43e31e4a19f56702d0.nq.gz
    ├── 01b9acd8f6df181a428bbb7698c0db27f371eb06.nq.gz
    ├── 01babf48f7c3b0a2837415a3ffba1839f74b9af3.nq.gz
    ├── 01cd62bbd75451dd4111d49c1f59231ab7ec0bbc.nq.gz
    ├── 01cf242762f986ad53c19dca97c59cb4422cdd55.nq.gz
    ├── 01d624a4c03c37521179d209df6901dc9f140804.nq.gz
    ├── 01f8cb5d5a9d66f6b9f956011fcf43821c1c49c1.nq.gz
    ├── 02001e84eb39fd4cf1b91c54d19f791a1c34eed1.nq.gz
    ├── 02078fbce133e73975fc3911ef17e18705a81f09.nq.gz
    ├── 0209ff696a1bebb93a438beb2a596a84d39ce794.nq.gz
    ├── 020a475f3441fb3a00e7343bf462f3829cd3f0d6.nq.gz
    ├── 0210372c94f86e90e9516245537abb24467f46b0.nq.gz
    ├── 021844bf7467fcb5e18c6aa27b49470bcef3893f.nq.gz
    ├── 021da914bbb7236e557db9815f67dafa484c29ab.nq.gz
    ├── 022214ea653a3ac5004483c6dce43152bb290bd1.nq.gz
    ├── 023e1c50c4037037bf2e8560edb5aa5f4c817231.nq.gz
    ├── 0242c17857645872ee6a80457fd8df8c854dfee1.nq.gz
    ├── 024365dce076bfd267883ba4d9bbf4cf02d2495c.nq.gz
    ├── 0257f762968c2bdf8872a3ec0d1379bad017aeca.nq.gz
    ├── 025ba98239a3d04249a9461073e4d8af23be6532.nq.gz
    ├── 026cf7fc072d87cbbc5c14d154357d8904207c09.nq.gz
    ├── 027c536333b59f9918592efd48cbd6e7dc3c5d45.nq.gz
    ├── 027cd8dc12958fac180abf1c113ab94c572cb23e.nq.gz
    ├── 027dec212fb93bf02b5a40b5546d98316c9a1b3f.nq.gz
    ├── 0284c4659f4fa49487f60ffa3c5d0a3ef586bd1b.nq.gz
    ├── 028756dc9ca02648e47029b7b8968a8f5075168f.nq.gz
    ├── 028b7f8c2e6be2976507f702eaee0657846a245b.nq.gz
    ├── 02a85965f2e2b6ae5b1ccfc86b0c8c3a54bb8718.nq.gz
    ├── 02aa9f857a596f7a5f7abdd691a6545d3991daa3.nq.gz
    ├── 02b7f51d6d7a74c4fd689efca55ac32d78b8ddba.nq.gz
    ├── 02ba5a16ae657c26f524cc6fd05eee161215db94.nq.gz
    ├── 02c2de8e4f44f1d091e3f2d4141e10ba27f06912.nq.gz
    ├── 02ccdc815655ead97c5a324684df0c35dc0676e2.nq.gz
    ├── 02d0705353f38dad80f162223b2dff67d6134aaa.nq.gz
    ├── 02d54c474887166c6470afe2006d9b46702fa0de.nq.gz
    ├── 02d88d0e43a8326c07cde0a07cf6615b4eee0136.nq.gz
    ├── 02e120b2ed3bf7c703e2535b824922cf38477be4.nq.gz
    ├── 02e711b86bc2e626a08d769982035470bf4207cc.nq.gz
    ├── 02fa808817f3bd00ccecdbc169dddb03629b2b07.nq.gz
    ├── 030d1dbde6cacfc89a8c1e5c673b80e34fcfd170.nq.gz
    ├── 030d369b1f4514df9084c26615b3dc58751244f0.nq.gz
    ├── 03142a6222609b3cb3c5b32c41b30f4b2feddb47.nq.gz
    ├── 03198f7f473494ef29478f4469d31e40362c3792.nq.gz
    ├── 0330d0d2c8192b8313f28be76708c24e17080b62.nq.gz
    ├── 03421bff8baab7bb1717a0b7174f7a3a760aaf85.nq.gz
    ├── 03424b267f8edcfc4b2ccae03a5cb3d5f09a2924.nq.gz
    ├── 0342a4906d7965a21c67cc2172c33e85e2aa16b5.nq.gz
    ├── 0346b3c4df4a68c600c1a147b410713a8901b36f.nq.gz
    ├── 034ea560665f7e2a2326805821827ee6ccff91e6.nq.gz
    ├── 034f7ff96ae55d2dca551a5e33d6ef76cb98f1b4.nq.gz
    ├── 0353967de1c1070cbe685e4ba211ea654119b0e6.nq.gz
    ├── 0355a7816e411b17bd37fc110657b4788c1895d7.nq.gz
    ├── 03632551daf5dfad919a361760a97c21557b1d3e.nq.gz
    ├── 0371d6e17fce66ad3a4d01ef3da80b870cbfb9a1.nq.gz
    ├── 0375040f469ebdf2e3eecd00f32f8764c56dba53.nq.gz
    ├── 037fc76e7a0f4a79a5c30474bf4f328b5b16b79c.nq.gz
    ├── 038addda9873592b7821a223ca8b8d74c9b8e46b.nq.gz
    ├── 03932306376000ff60f5313de8517ef9f73ee7f5.nq.gz
    ├── 03abc9f7de84d89d778e95c5eb287316dc51e321.nq.gz
    ├── 03b44b4e07da3a277f2d6129df36d4723ca5948e.nq.gz
    ├── 03c13d88e46c2070c89b6f550b202387bd1fe8a1.nq.gz
    ├── 03c1a63db71215f70c391dc2faf57724de0ac950.nq.gz
    ├── 03cfbeda603000c993d99689180136b42d39999a.nq.gz
    ├── 03d6ecf378ef16b92386e51738057ff03ebd5f41.nq.gz
    ├── 03db36206277ea895ab1cce22f91a2c4bbb5a27e.nq.gz
    ├── 03de06422df48e4f720712f7503da5f1b867ad53.nq.gz
    ├── 03e242500007936db97ba35c43127eb4e06db883.nq.gz
    ├── 03f01864e9dcd9c63ff8d90ba479c8e98cebccdd.nq.gz
    ├── 03f1b5c64bd1e493d56367f8b25d42b9210082fe.nq.gz
    ├── 03f7ef5c4fa60b6efcfb351f4922c4ae8a7c395d.nq.gz
    ├── 040cd683a29d38ab27960076198708b19810c3e8.nq.gz
    ├── 041190c2125c396ae172ceab3ad2c0b27e18f402.nq.gz
    ├── 041e2c2d6e84c82b4b75c9e6b96f687cf08b461e.nq.gz
    ├── 0432f337504de0c139a6b325be67a69aa6ab4dbd.nq.gz
    ├── 04396173e196c65e86c8fc1fbb4d3db2ffef9588.nq.gz
    ├── 044486eedd1de9a2f23bfc3c6b033572b03458a0.nq.gz
    ├── 04499dce2cf16523fe47e79a0daa058c0e73248c.nq.gz
    ├── 04524b22b4305b0d988fb648ed063abf23304b93.nq.gz
    ├── 0456e67bdaa83b3e94c0d88f8eb3f514b7d754d3.nq.gz
    ├── 045b11d3ebf1675268567318fa51b9198cfcb650.nq.gz
    ├── 045c68fe972cecb6db0065d213b6683906a6083e.nq.gz
    ├── 045ec0914026b5c3437030aaa23bc6aee32b9105.nq.gz
    ├── 0465ca1a2ba3e02cf7e17f8c128988c7006f0456.nq.gz
    ├── 0467abe80bcb30b79b5e9bc150eca76e55381c6c.nq.gz
    ├── 046d1ce6b07f35fbb00791de6b4c7a9e96468296.nq.gz
    ├── 0470fb65239409aa9eb817b003f3b7da422d91f1.nq.gz
    ├── 04754ab35f13aa822429d41574d664a237e1f940.nq.gz
    ├── 048848cc49226f470c7e4aeeca8dae9c7cda299a.nq.gz
    ├── 0498ba3787d34e459588cd5686f2c6d952fb3d8f.nq.gz
    ├── 049d2ccc5924fae80a28622398971c2a38a161bc.nq.gz
    ├── 04adffd8eb9114176169cc4b715a53a3cbdf5052.nq.gz
    ├── 04b32eb60613128510a44f64c3abf95b6819307e.nq.gz
    ├── 04bab89ce10c2d6fcd3dc0fd7056df33ae23e4ab.nq.gz
    ├── 04bfc89c66d61714025435aa3b6edd3c002b59bc.nq.gz
    ├── 04ca33c622a44d31fc07db577ec683353bad5d82.nq.gz
    ├── 04cfb9add92e9774ec892b3ceebe0c0bafef80ef.nq.gz
    ├── 04d99ac4f0acff0a0dfb297b4764b0ae4d96dbf2.nq.gz
    ├── 05145aebcb179e956dd897bb445d7eed3657f0a6.nq.gz
    ├── 051e8db28b43431dfcae32fda293f66e580fd607.nq.gz
    ├── 052d86ba9aec654446289391532346cfea61b537.nq.gz
    ├── 05379aee59a5799beb5badcd63b13f5d9928d373.nq.gz
    ├── 053a82d5e8ef804429a16b9e2841b427d20acc50.nq.gz
    ├── 053fa332d16914c31a236f726c4ec2549a5c3519.nq.gz
    ├── 054d216062da97c1e7659280010e69a07e94171f.nq.gz
    ├── 0551556f3a392a3a30c784161d8cc96120d6e968.nq.gz
    ├── 05521fb58da3b2913b2f30e701085c275d545b7e.nq.gz
    ├── 0556aaf55362180780fc355a78db65cb251750f6.nq.gz
    ├── 05597615e98408dae9df5e2bfa059955b5e9c1f5.nq.gz
    ├── 056380d33df438baccb2fd65f27390169500f58d.nq.gz
    ├── 05764451bdacb38bc45c030cd7fe75ca7174340e.nq.gz
    ├── 057817d18a0d7db0b26e5d5e603502fb384ddb37.nq.gz
    ├── 05878a211bac2341555d7d1b1ed8642f0051fd3d.nq.gz
    ├── 0594b4318dd01067bde84cffe4e7844a804d33f9.nq.gz
    ├── 059894cfb86b2db1c09d08dad0278e9b4e4e11dc.nq.gz
    ├── 059eb83d673a5d80f444db131dd04142ac9814ad.nq.gz
    ├── 05a64633d349d96fd047e4542e88e658afa0ecba.nq.gz
    ├── 05a67e8e3bade1c8ceb36b87eb8085abe4a25679.nq.gz
    ├── 05b065631a7235a8f69056c1be2fa4277f548d72.nq.gz
    ├── 05b362846a17d3822b6a60bf3f7fb7e98f614d20.nq.gz
    ├── 05beccbcf5e1198c3ed8ef83738ad5d4fd619d67.nq.gz
    ├── 05cc7fa48349b8d1584ace7b6013bdd4c6a78a21.nq.gz
    ├── 05cdefb9129f620686184a32428cbe5ef3333e41.nq.gz
    ├── 05d06e2e69eaaf16c8065e0266f1b3f544b67169.nq.gz
    ├── 05d567ab44371e27c7c20397335f6daf3223211e.nq.gz
    ├── 05e041d782b0fdaa24537c41891bf51459adeb54.nq.gz
    ├── 05fe35c34d2b54861136c300d9194ec9406f3adb.nq.gz
    ├── 05ff21290ce5e8ecbe02e58c4c27a22a45535935.nq.gz
    ├── 0600e296bfdfd7bc89b418999fe24d739ce6829a.nq.gz
    ├── 061505fcba2ee08992b62c8082d64dd159272139.nq.gz
    ├── 0618026e6f290bc6eb8471abbf00c6ba19fb4835.nq.gz
    ├── 0626a366288db1c4bfd60d5205f3c264b91a7626.nq.gz
    ├── 064ba9744e204420cc32baf2d953172d8ec53d4d.nq.gz
    ├── 065940389318004456e7e067e80a0f0af91c6e65.nq.gz
    ├── 065b1cf3589bef9a485122fe884d177acbb2fce7.nq.gz
    ├── 06623cf05ed4689bc6f78b99ac3080419861296d.nq.gz
    ├── 066530708b00c2e7164595b04c3b1bdf430b2e7a.nq.gz
    ├── 0675d9c0124f8bf0386628b99981bfe386b4b115.nq.gz
    ├── 0676ec865b6678e4fcba3f9577109a0f22aa15d7.nq.gz
    ├── 06790038306b2fc9a81d71525ecf955dcc9411ef.nq.gz
    ├── 0681a86f894930de78160e22bb53fa2e14fe7bbc.nq.gz
    ├── 06851b70cd3413840db0faa58fa6b590940aa421.nq.gz
    ├── 06a88f70bef9085ef95e6ce8af0fb9dbe528e543.nq.gz
    ├── 06b02c6a77aa210d87fad31815528d12e8e48551.nq.gz
    └── 06b40137b3f02ab0b8556d90c036cc70f23b1f2b.nq.gz

13 directories, 200 files
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

[Azure/azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python)

---
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
