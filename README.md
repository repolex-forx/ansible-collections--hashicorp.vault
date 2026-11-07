# Repolex Knowledge Graph of ansible-collections/hashicorp.vault

RDF knowledge graph data for [ansible-collections/hashicorp.vault](https://github.com/ansible-collections/hashicorp.vault), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/hashicorp.vault
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5f9deee0d7fb46c77cf77e6da4026f817c7e605
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5f9deee0d7fb46c77cf77e6da4026f817c7e605
│           └── chunk-001.nq.gz
├── blob
│   ├── 011784b8637219884e17ea3b47a3772811be3939.nq.gz
│   ├── 0396808d36856695d275d84569d33e148c6a3a20.nq.gz
│   ├── 0785bb57fb6a5709a03c7fc599639c7702080a25.nq.gz
│   ├── 0a8f85efed31ccf352ca7bcdfa4a130abf04b312.nq.gz
│   ├── 0aee3a9dbab1cfaf22c03a29695f5211818b1543.nq.gz
│   ├── 0d78333ebe9e343ac9f6b1324d45f93b50ae732a.nq.gz
│   ├── 0f87198fa349ccb2fcea186929210127fec4fb24.nq.gz
│   ├── 107733978aa6d19914797f13800ae66bd7e8e778.nq.gz
│   ├── 113fc5294c530ec429bef14781ffb5d182302969.nq.gz
│   ├── 1527556a8273eedeef096eea20a2c33c86ed730b.nq.gz
│   ├── 15fb479a6ef881b35ad85c475d5cdcbeaa5a40a0.nq.gz
│   ├── 16aef90f7f1a4098facd19b54b7cabe6129157f4.nq.gz
│   ├── 190326f384d395c99c8c7b41252584e8be34c5ed.nq.gz
│   ├── 1ba20110d448c7b6adf0030a3f3d5d5cc04e4022.nq.gz
│   ├── 1e204b18153deb48c838debbaf14cde3b65acb84.nq.gz
│   ├── 1f0850843b36b06179e9dfd0c109e039c794cd1d.nq.gz
│   ├── 1f5d8eff5925a9edaf19c0411aa54b8eaa5540dc.nq.gz
│   ├── 1fa8048a593b6e5b9c811504aeeaf64e8b70df5c.nq.gz
│   ├── 21dbe1f22e2a46ae734349d67a8d0c704072aa8c.nq.gz
│   ├── 220dd827d77cff669ef3bb96bae87e53e2238806.nq.gz
│   ├── 22b486449eea2504bc46c71e3d4f8ad9a3e141a9.nq.gz
│   ├── 2359527e355383a16c50222c1ee86e14629f565f.nq.gz
│   ├── 2495a1c9031f710952830dc4f99fab187100f31b.nq.gz
│   ├── 291d51fba7851bbb34e0869cd271560d7967d089.nq.gz
│   ├── 297ac1fbab81528c0a45bd90916745534cb2e9c4.nq.gz
│   ├── 2a41f197098d8e8b6cd2106f84a014efa750fbcb.nq.gz
│   ├── 2a5c9f443198c37858f426ff942040e2e03ed5de.nq.gz
│   ├── 2c7d6f67d01b1fad758cfc05c1d9eb93e8b1b60c.nq.gz
│   ├── 2e2ddb747ac9eabd9887fd7e316a97260ae04ad5.nq.gz
│   ├── 30ce4d4d4ff8d4d99380976576fcb4587125c3ec.nq.gz
│   ├── 33a16c77f2ae02a370ea1e88550ee46bb30653e6.nq.gz
│   ├── 35936c1e578d82beec821da2839f1137dffa4e5f.nq.gz
│   ├── 38914ef39ff1cd447902aa75f7b375692284faff.nq.gz
│   ├── 3b5e9288e0b6181ce2c4cbbc6a37f7122560d8b6.nq.gz
│   ├── 3eb468b3c178b035f49ea468174244f008eb1a4a.nq.gz
│   ├── 3fbbd4852789168f626155c0fc8837c52cf74ca9.nq.gz
│   ├── 40928aabe2806307e74e33b39766bfb32a2b3d61.nq.gz
│   ├── 4332039407b7d2a71f6b3176c3502ea3594f5cf8.nq.gz
│   ├── 4334866156c8dc9220661a245db093d3b08509db.nq.gz
│   ├── 435f8c2386f8361f9b73bf26a33cfd4e3e548df4.nq.gz
│   ├── 4368f43fb18f0ca90747da2a1d2a8b0513af4a2c.nq.gz
│   ├── 4800de8ecabe8f92d0ef9b9351cc9c7592fcfa76.nq.gz
│   ├── 480edc92d011b7fbc8b65696f6919c8c41d4cc17.nq.gz
│   ├── 48bf7460add4ef62d508827d2fae8ffb0a476810.nq.gz
│   ├── 48dd0e925b531fb0e496932901ecf6b1865a0d29.nq.gz
│   ├── 4a7280ae274312a77e22dcdc2c964f39c95c8c5e.nq.gz
│   ├── 4bfe76d68eb7a7d1a2834f936153fb15294551f4.nq.gz
│   ├── 4dcb809a72adbe54fb7912c0d40a74bcade4bb85.nq.gz
│   ├── 4e3990121e520313ae65df347014f00e0931418b.nq.gz
│   ├── 4e6ca491301bb76a9f773eeccabb547fff5adccd.nq.gz
│   ├── 50f740eeec954809d90d431586c2699cce1f389e.nq.gz
│   ├── 513d869af6e4d9f4c1abc97907cc7c2c96891b69.nq.gz
│   ├── 5157aac15fd2ab5e4d82a1eadd4e35a58ac0cd03.nq.gz
│   ├── 5227e9579bc9bba13fdff5198b28557099eedb17.nq.gz
│   ├── 539dceb3bc67e78fff5d2d9d635ac13c92e3f396.nq.gz
│   ├── 5633ac66caa876c526caf79de7fc8ad80b6a109a.nq.gz
│   ├── 5684cc0c136a66c9b8243c2c48cc18ce96855c2a.nq.gz
│   ├── 5746a49185ec7ab4fddf580cf8470ba08a6bceef.nq.gz
│   ├── 576eb9944ab776baef82e3b522fe7029c62cc881.nq.gz
│   ├── 58fe606611b3deee5dba011315a37831508a217d.nq.gz
│   ├── 5a77b3f6f6c84655b42e4de0262ac876eb08b4cc.nq.gz
│   ├── 5c196dfd8e0b5014d568208e8af81b726ded0aec.nq.gz
│   ├── 5cd12c4de393040e1c77a9e7c294d84656451ffd.nq.gz
│   ├── 5dc6a6075cdc0b9a7ac12794a40f69e6ef02ac41.nq.gz
│   ├── 607b90b52a1b1fce6295580bfc9ce9eb6f7359e2.nq.gz
│   ├── 60b4be8440e57b2ba35c1e698b966a0eb278c407.nq.gz
│   ├── 649c6d289b59056350650adbfa0b9d48ed69fe97.nq.gz
│   ├── 67a2fc2a7fd56f37a2c9e9986b37f22c3473fbd8.nq.gz
│   ├── 6cc46840cacbca57792133d9f433e5498d8dbc19.nq.gz
│   ├── 6ddea586d4b27bf962874583db426d007aab3fa4.nq.gz
│   ├── 6deda3287fe081a261ef7273d6d84bf591478e37.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 70041dbf034fdeb41af31ddaa236345940395c7e.nq.gz
│   ├── 722d9e3977b28a5de42e68b9d6d8e611b029bf2a.nq.gz
│   ├── 74aba221a54d47151426695915ae29eb5aebd48d.nq.gz
│   ├── 7594fa596a08410c7efea185bdcb91f71f49641f.nq.gz
│   ├── 7949bd8a3636c55f3f638aa4ed5d0ba5a688d988.nq.gz
│   ├── 79c92743a0ab1f072fff67ab44ee37944e619f6b.nq.gz
│   ├── 7bbefa14e296b110564aa280a29ba6ac497e9f9b.nq.gz
│   ├── 7bf9ef4edd26ed70074598b0a25083fce0bd3108.nq.gz
│   ├── 7c8ca11e09971f5868723a1211c395d94077241c.nq.gz
│   ├── 7cd6de6d70ba914e1cd9525c924e009d25714653.nq.gz
│   ├── 7d01233a95f27429cb66c83712c3ccee3802e186.nq.gz
│   ├── 7eb24376744ec7be84c90f2dec9e8412507c41ea.nq.gz
│   ├── 80b274f817780d549ab91f242c97a1e7e021083c.nq.gz
│   ├── 812e4a77aad3dd8abf801261dfe17f2747c6df7f.nq.gz
│   ├── 81399f608f6a1b7ac796fc1387d8d580497b7711.nq.gz
│   ├── 82c0d4a616de874f4e1a39e2a0a90c97e4afa874.nq.gz
│   ├── 83c1208c70c62dc0eb2c8020cb8b81f63b3261e7.nq.gz
│   ├── 848148de02fbc102f2a001608a7c03cb5f79031a.nq.gz
│   ├── 875dd454c30c0eb35341e90d266310e11ce9c54d.nq.gz
│   ├── 87c8308106d5a4e5207be8087c31cd207db17552.nq.gz
│   ├── 89fcb4c0e6f38e9656d0d49b3cfa92c05b436ec6.nq.gz
│   ├── 8ba036117a7f9d0575cbe46d93816a037e800ad2.nq.gz
│   ├── 8dd631a09f25d5319956d659c7aa7c7812e18b8f.nq.gz
│   ├── 902ac0ef87420ff1ff9638ee379217cc1c74a836.nq.gz
│   ├── 90765c7ad1cbd24b731fe881ef336cbf7b04d9e1.nq.gz
│   ├── 92cbe8c3f44aaa4782d3c386e5f607eb9e2de882.nq.gz
│   ├── 92d91fd878027cb4239671a7d540c5f6edc57390.nq.gz
│   ├── 97078ca536248e034745b5cc082f823535185b24.nq.gz
│   ├── 9719b7e902166e99c8eeaf5ec438dad4a33346e2.nq.gz
│   ├── 97e0ca04c93472b5b4dba7e51d5903a49f2f06f3.nq.gz
│   ├── 99c84fec6abf52bf94e662c4db755a1daed5c723.nq.gz
│   ├── 9aba46cb4ca540a3037c1dee98a5f0d844897974.nq.gz
│   ├── 9d594f588c97a56593cbe758421c3b26e045c21f.nq.gz
│   ├── a2ec752b7f7c35b04684f04741e6e286b5fd2fe5.nq.gz
│   ├── a4cbf0caab4d3f621f7aef7b5053280005d8e36d.nq.gz
│   ├── a688ae984e07e03510b1a8709930672fded6765b.nq.gz
│   ├── a8aa553bd8b163f20eda3554c9386f0895668651.nq.gz
│   ├── aa4e6e51f52ffa1b13b53c20f77e2287dfdc91e4.nq.gz
│   ├── aa9c5e2c1dae87d44cb412a9f7e8ff6cabefccae.nq.gz
│   ├── aaf0d230d970d7dfc5405763891d36e88d4d1f61.nq.gz
│   ├── ab95224b7f91568d683f7a2709d93e4f8374be72.nq.gz
│   ├── adf1dc2dfe17dfb3f1d787bd08b911a5b0f728c9.nq.gz
│   ├── b24ebcbf4f67f9827f5bb18d6095e5946a428beb.nq.gz
│   ├── b9e891fa0e12126bd38e97b4ba8b30a3c7bcb5ce.nq.gz
│   ├── ba6aa688ca65aa16b07dace821cd47a44ce80034.nq.gz
│   ├── bae3f2630e931e7c719839a811138337a4ef41d3.nq.gz
│   ├── bcf34bcd7646c8c8c7317001432ea20b190c6207.nq.gz
│   ├── bd0c6386bffb60206934fb0f5ee5386315377992.nq.gz
│   ├── bd97536d20884cdd71c8ab7f359a2cecf9f8a7a6.nq.gz
│   ├── bea59ade7125e02aa7b88e2c166165553a398331.nq.gz
│   ├── bf829d82bab7a9d578922492a450dbc8d7d75f1b.nq.gz
│   ├── c2045b88448c0640f34c981e1b1ec03411ee704d.nq.gz
│   ├── c288b8ea5413947cf946a0f24ecebf64dcd06150.nq.gz
│   ├── c376a358c3e434a8e345b23e3e5cc10cc0312968.nq.gz
│   ├── c605f121fe4c8474bd0d47860c678466482e82e9.nq.gz
│   ├── c656bdc37ed02c92c7fb1d1c3e8e18195ddb5085.nq.gz
│   ├── c7f2380a22f408539028c80c8b6719a1fd07733b.nq.gz
│   ├── c96922aa11a63b7bd6718731548ca23640e891a1.nq.gz
│   ├── cbb7a61a6add42c901b342e1fc4830db18496eb6.nq.gz
│   ├── cc63c39acf8687ae4dbd76f9126897f733235bba.nq.gz
│   ├── ccf9db7b4f7e2894345257c2e5bc2b5835dd0ab0.nq.gz
│   ├── d0bd7e58cef8dcb9d000725d0e648041e71df90b.nq.gz
│   ├── d2b72d8389caec0a5191828a8aede21943d73d2f.nq.gz
│   ├── d506d619c0737733dcf26166380859af444808e0.nq.gz
│   ├── d71ee24a38f0e86432064e89191d8ee606db51d8.nq.gz
│   ├── e03b4d340c3e2958625c80e1fd99667a4375248b.nq.gz
│   ├── e0ebb504449974eb1fbff912cd93704b151388f1.nq.gz
│   ├── e0f2fe2f50206605eac8108f20966a0bae7bc8b3.nq.gz
│   ├── e2062384714b349fa0aff762d34b2b586bd3588d.nq.gz
│   ├── e340fe0936945aec89f4f9cc554d43e67b86f8fc.nq.gz
│   ├── e39e20cab50b5d72bf415a5a46ef2f8a8da90881.nq.gz
│   ├── e42b66aa9f19775279d5f70870a39a07c5e0861b.nq.gz
│   ├── e4ba441414319aeeda9045118ee2aa335d1a7ef7.nq.gz
│   ├── e5910bcf65cc5ebc65c6c225ca334d6ea2dccd34.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9703051095e670bceec1a7445922eb1fcb64374.nq.gz
│   ├── eac612fa730df6091b6280d58c326b3637c03caf.nq.gz
│   ├── ec987714cc2f441742559c7590f30276b651959e.nq.gz
│   ├── ecc25bb3434fc413e26d647498603d8ed7810e3a.nq.gz
│   ├── edb5eb03fb1e6795bde31e55c607aef38c02e18b.nq.gz
│   ├── ef88e7835ebde0274c1e4028d70f56060d0dfd0c.nq.gz
│   ├── efa54370d935e843bb8a2f5b856331313a0008a5.nq.gz
│   ├── f0f6323e49d51b53f182d0c9e4a9337d655558cb.nq.gz
│   ├── f12dfb872f18dbcabb6f333857fe44a1071222b9.nq.gz
│   ├── f1df10fc1117d9f8a578794a2bb466dd676d303a.nq.gz
│   ├── f2293605cf1b01dca72aad0a15c45b72ed5429a2.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f3fc82e5df5ce680cb89d9f3c3f3d9910853a36a.nq.gz
│   ├── f42fc67ba244be44d8e6b7cb945aea9003906c79.nq.gz
│   ├── f7f63a405f2e7c37ba430a7cd82f0bc35bd2561d.nq.gz
│   ├── fcc865429e3bb38fb017ad43cc69fb0075a35bb2.nq.gz
│   └── ff8d312c336486f5f6f79aea6a4bb429a0614c58.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5f9deee0d7fb46c77cf77e6da4026f817c7e605.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 172 files
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

[ansible-collections/hashicorp.vault](https://github.com/ansible-collections/hashicorp.vault)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
