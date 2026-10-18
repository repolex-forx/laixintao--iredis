# Repolex Knowledge Graph of laixintao/iredis

RDF knowledge graph data for [laixintao/iredis](https://github.com/laixintao/iredis), parsed by [repolex](https://repolex.ai).

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
rlex download laixintao/iredis
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 554bff6bfaa499e8fce488fb9dbd21900cd3d0ba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 554bff6bfaa499e8fce488fb9dbd21900cd3d0ba
│           └── chunk-001.nq.gz
└── blob
    ├── 005b47b91243ff3e2d74abc9a06b9e33b7d1cb27.nq.gz
    ├── 0217a297e7a06c6e0e89af1c420636b6761974ed.nq.gz
    ├── 02496acf31c6d21b9fa2260fb27d9d6a40ac43c2.nq.gz
    ├── 029f80d6f405000ea9f151dc0dfb1ec545665a69.nq.gz
    ├── 02b716326f0fa0f3c0c48305c7da3b96787fb352.nq.gz
    ├── 02e8b1d3b6a719c308b475fcaabd8fa0f3945b55.nq.gz
    ├── 02ffe9eb957e19a6ef88d27ca6781420662436f7.nq.gz
    ├── 03fc3d4158fbdaaa649027ecc936095198198e26.nq.gz
    ├── 0446386cc15fdcf83de697579ccdd807d00efd06.nq.gz
    ├── 0572b01cf590feb625232f5ea6ed3008374db081.nq.gz
    ├── 077cb3776da471684c8e18c5ed061fa55cd4d336.nq.gz
    ├── 079edeb00101909e29ef39d9de1d86fa21ef89b9.nq.gz
    ├── 07b17b2071d56ee7b98e8be459562ef1f70e1680.nq.gz
    ├── 0808404f25dcc5c8365f0768094d8409e811035b.nq.gz
    ├── 08af1c9ae1cf3dc466d6e7236b49716839f61f0b.nq.gz
    ├── 08d55d5a9eca6f1af9833107362f9c9ce27cd963.nq.gz
    ├── 08f823ff7f2ed8b11d40d8b5e3eedf4e9eed0d71.nq.gz
    ├── 0b00d0140bc8677e36648fcdb029803475039207.nq.gz
    ├── 0b8ccf09857f781eb03dff0b4791f4915589ad46.nq.gz
    ├── 0bffec84b5dc8b96e4e046866c691f39da9d26bd.nq.gz
    ├── 0e7f212724537efc5cbddf0006616ec94bf1630e.nq.gz
    ├── 0ea28bd41be6a7362c2af9ca06d0c422556cece1.nq.gz
    ├── 0eb256fab8e95eaa6bdfc314ae7863bf0d17ef73.nq.gz
    ├── 0ecda0ddd7b3d114cb5ff78b6869a192a2e6c1e0.nq.gz
    ├── 0edec9b45e3a4bd2a12bdf79109c60cac02fe559.nq.gz
    ├── 0fecb133e015d238f7d1b51d039fc9850090a492.nq.gz
    ├── 101694141879910040949dd94e1dc0e32333eb73.nq.gz
    ├── 107b7b662a68da49d41e4c020a2243bac26f849e.nq.gz
    ├── 11aad62bbe7eb89f602d8999a289bea03ec7b8b4.nq.gz
    ├── 11dff98ce7620ee9a64512b01688243db7540620.nq.gz
    ├── 120bf4412d5c6645d1e0957d8101050056f71a18.nq.gz
    ├── 1506af304a2d4526823d44739910d7845a654ee8.nq.gz
    ├── 15484f79739508eac0fcee4131216cbd3cf4e938.nq.gz
    ├── 15821e1140577fcf31ad07daf927f5fd40454b85.nq.gz
    ├── 15a478026f0435ed128395df4e1bcdc9222e6338.nq.gz
    ├── 15e872c124179a95ff52aa4d18184f05db3d2f2d.nq.gz
    ├── 16488054ec3203b6fbaa872ce4abae20d099a034.nq.gz
    ├── 1667e1eab5210d10e1dc6cf142fee16d96ba2bc0.nq.gz
    ├── 16848a0e08e60c4f4c241e6537522e12e7124bd7.nq.gz
    ├── 16f125baff89099e0817ca866d04f5d2de4c045c.nq.gz
    ├── 16f7c97ac1e8f102009623cd64c9d7a1e08f2a68.nq.gz
    ├── 17c3af3c3cf37c5bfef3bc8fbb95e1988d8b3c66.nq.gz
    ├── 17dd0bf0b4cad425fb95a9d76fe196ab580fc5ab.nq.gz
    ├── 186caca66c184920db3c90f869f0bcbac761f1fa.nq.gz
    ├── 19dd377f1ccf4c5fe172fc66ca0f51731a91bdad.nq.gz
    ├── 1a82ee4f691df180043a8f2e0b6a261a2df39102.nq.gz
    ├── 1bfa3e232b940302719483e1700f236a19b69462.nq.gz
    ├── 1c34405bfef11b3b7f14de34a2cca7e99bf3a991.nq.gz
    ├── 1c3ec93dce42d06ed03cd8489694bd8f8194731f.nq.gz
    ├── 1cc0865ec5e33b1140d7f6d1afc78c6415c51e5c.nq.gz
    ├── 1cdc52010bd985af0b9594d5e8b75ede6f84f36e.nq.gz
    ├── 1d73fff19d4de1f9c852d58757898ed372020eec.nq.gz
    ├── 1eb1a7bb34dd77334d90cb1c480c1757d742f355.nq.gz
    ├── 1ec6c45d2b803133e4baa8a6a266d8ae8958cdb5.nq.gz
    ├── 1f4b8b8a3ee88e65b92cfbec301d77524c26b4e1.nq.gz
    ├── 1f7309c5265b09e04e21f7bb5aa625a1f66a936a.nq.gz
    ├── 205646893a77ea041b28fa7f422be788aa8c025b.nq.gz
    ├── 219cd6e3e0d931961c82ced2f0de29e55e9f76e1.nq.gz
    ├── 21a99d32da1a6ad16574294e069da028c1246c99.nq.gz
    ├── 21e2853e3929738fa0a7fce42edc5c9b0a456c16.nq.gz
    ├── 227285935251284f22c496409d202f64adaf2673.nq.gz
    ├── 229c63deab0694ba8c1eeeb5db49f62108174d0e.nq.gz
    ├── 229cfca7d667fa3bfd7587cc420bbdfe2085177e.nq.gz
    ├── 24473e50b5dd6a40926e2e99f28b60c495e47f4d.nq.gz
    ├── 2622cdd53af298f6f3c2490dd9cb012bae190e92.nq.gz
    ├── 262713ef31016cba40acc76e0e05678e0fe26d87.nq.gz
    ├── 26e5bb700d756d72e92b88c681f70a3f952c64f8.nq.gz
    ├── 27fe4c36c42f328015d3f6070f0f0515f4129f0f.nq.gz
    ├── 2868d160b6a63d3bc2c9a50d9a0196e975efeba4.nq.gz
    ├── 293892fd8f30ee91b0f8709832977d9d203a867f.nq.gz
    ├── 2a091db48cb2aca55109a868760330cd33b3f4dc.nq.gz
    ├── 2a896417469b161cdf1c9f067931614598d52772.nq.gz
    ├── 2afbaecf5eb38a598008118aa8f9386279eb942c.nq.gz
    ├── 2b6d436aaff4ec3cf9a3d00f919122529db8e4a3.nq.gz
    ├── 2bde9e05ba919e6f385f7655e39dfc3ecb32a5af.nq.gz
    ├── 2be45c0bf587a6d0facfba662722a2d88f5cb54d.nq.gz
    ├── 2c1819343535381a301657e3885e9531e74d7eb6.nq.gz
    ├── 2c8bd7432f371af60463ee06960506f730e78767.nq.gz
    ├── 2c9a973b43982995b0a315a7c3e1fd117fd64076.nq.gz
    ├── 2cc326957f1b65886fc382401a6daa9a96cdc054.nq.gz
    ├── 2cf1af682813babd2141f329ca3419c6dc79df9d.nq.gz
    ├── 2d8f626eedccd98b02079638b961610438fe06e0.nq.gz
    ├── 2db5ea58bc0baeefa7a5e2c018a738850b69f08a.nq.gz
    ├── 2e1517afb7d67e31e7a08aa4d6d5129be3351f45.nq.gz
    ├── 2e20d415f2a80c28f9d38db136cd64ce2837133c.nq.gz
    ├── 30e17518ad353d5e3869ed082b1ff6d85c01ad95.nq.gz
    ├── 310adab0c6e307b21d28c5740691ecbfbfa8cb10.nq.gz
    ├── 31308c20281a44e62ee6b2ad6b3c91d9c5553a54.nq.gz
    ├── 318e0e253f57721c6e756865f4d5bce56e6bb5a9.nq.gz
    ├── 328d56bde64b4c4f609ef006e8a3200c3f487804.nq.gz
    ├── 34b95741ed8f40e30866d9d927ffe7f61d1f3698.nq.gz
    ├── 35ea017f2ac8bc9466f6bc2f1b72f19507279b83.nq.gz
    ├── 368a34cd97f88035055f7e113fbfcbdcc3e3ca22.nq.gz
    ├── 36c0c7df00522124817443e660a5a4568df8ac34.nq.gz
    ├── 36ccd9b61eea7f06e08caa1df493dd2f156b663f.nq.gz
    ├── 36dc8d9a403bde80897c38a639694cc4deee1a57.nq.gz
    ├── 36e69dec77c0b6539450f80780b288d2c2689c9d.nq.gz
    ├── 3717f001db6355c3c8acbef08a8488ee153a7538.nq.gz
    ├── 372cc739060612e36dc5693c73726099a2571cd2.nq.gz
    ├── 37545f9bd950a24da88e30d6d260b6544c336648.nq.gz
    ├── 3773cfbcd339801e0fab6d7446dd76af9aa1feff.nq.gz
    ├── 3779ed5e472dc804b5b500fedbed75b7574a2d2e.nq.gz
    ├── 389a1095ff5d70450b84dc1ab93e3ee6c9828a87.nq.gz
    ├── 38c300d590f44bd5c577bf20fcb13fed459f96cc.nq.gz
    ├── 38c412a19a256c1c3193752c76372072910d684c.nq.gz
    ├── 3926307fbeaa08b3f94b0f822782adb651696241.nq.gz
    ├── 39b593cbe3e22eecccd8573dfba5f6f325ca5263.nq.gz
    ├── 3a19810c946d17d2582c2d5fe5c5ce4d9d699869.nq.gz
    ├── 3a9583d0d91d94cb9e9e36924cad9be5d72911b5.nq.gz
    ├── 3b1e159006097eb432271822d0c193fe841a9484.nq.gz
    ├── 3b27b1d1230ff9eb0abaaf24d9ad7ed5391aafbc.nq.gz
    ├── 3d0bba46889fb32dad3749e80508e3bccaacc13e.nq.gz
    ├── 3d24c254d887501b6cb4056e1e5809280b55be11.nq.gz
    ├── 3e0cc43100b54b2157c654fc67316df0a0255a6e.nq.gz
    ├── 3e9988eff9104afe8e41496881c754a84c5aa4e3.nq.gz
    ├── 3ee4a3d067f52bc7ad72af965c797544e187bd7b.nq.gz
    ├── 3fa479d02dddf679da03592e16d4b1f87e5ee2e4.nq.gz
    ├── 402c51b8a7d0a9ab5fce4e6855372821daf1fa8b.nq.gz
    ├── 41c2010e7f9045b3f125830a600afe84d359ba61.nq.gz
    ├── 4264f1b072da74f8f8dd02a5cb314a24245488d3.nq.gz
    ├── 42d78c9ef38b98857fdac3d8f667983ff6549699.nq.gz
    ├── 4334b150a0b249e8bd7462acce39f52e50b09864.nq.gz
    ├── 448468ba14adbfe290dfb352a81ee6f4781a3180.nq.gz
    ├── 4532d6059850cb2c57521e3e8cab56632e47096f.nq.gz
    ├── 463a2dca28d5ac8546fd271c20662b415e844303.nq.gz
    ├── 465b3d73f770de440bb6cdffb16d847a658385bf.nq.gz
    ├── 46bde8da69098a427f92e5a59acfe483004a88ab.nq.gz
    ├── 471ecf4187776e9d126033d2030b7db434ea3d1a.nq.gz
    ├── 48840aaa38e2a4c79e91748d7e380b9fb6437393.nq.gz
    ├── 49e2d506e9b338f7f34bba349dfcdcb323e34982.nq.gz
    ├── 4a507b7c27cd2003852a1db34064eb6ee9ab432b.nq.gz
    ├── 4afb3cd1ded95e1e63684ae531647afc7d8850e9.nq.gz
    ├── 4b0841e049d634dab24d269350ce4860b9288905.nq.gz
    ├── 4e0807971b22c29e078019a46baea593a4b011dd.nq.gz
    ├── 4e21b9c96d7002c2766bfb0eb5ae81a3050c8a88.nq.gz
    ├── 4e6192e11709e96e9f8248a04f25688b97c69915.nq.gz
    ├── 4eefffc05a861aa1e7cadfd2d5f04534693bb66a.nq.gz
    ├── 4fdc149f61f0e945dca8ee10177b8b0938c57ce9.nq.gz
    ├── 5062718f692666ffed3212f787d06a285c2e7cea.nq.gz
    ├── 51a2276bafbf81ec0a31c97f504fabf943e82565.nq.gz
    ├── 521c1a6594e0d042cf93162df1744536bf184e16.nq.gz
    ├── 53e5ebe603921ca6e6d34ba43d725db2e4aabee4.nq.gz
    ├── 545bc92c3ab73b2bbc72bdf600a191e8daa7a8d3.nq.gz
    ├── 54ced9781da39709ab0ff07ae02b1a30714ae8f4.nq.gz
    ├── 55269592766ab10fc44de5ae98217637c5ae9c2c.nq.gz
    ├── 576b14067467c11d6a36f2e5e5148a13fe75a582.nq.gz
    ├── 57badc8b78fea55f73fb008c5a478a086ba30035.nq.gz
    ├── 58b4c7abab9c7c804a2759554bfb5f3c56db2e43.nq.gz
    ├── 58d4e7529d9b059328ea8c527f8eae66e1f0043e.nq.gz
    ├── 5a10ec6e8b4b91f7f1c0e684e7dcd16ed84518a8.nq.gz
    ├── 5a562d0cf4b949e664dc5426ad18a55ba3f149b3.nq.gz
    ├── 5a6e509d6062a3408b174af24a93a6dfe4a9aefb.nq.gz
    ├── 5a7adccd79a15bc06b9b1573e1e366b3579a5891.nq.gz
    ├── 5ad504335d71174ce25487136213bcb6cbf5af8c.nq.gz
    ├── 5b2288c16b180874ac5fb6d10ccac3a13f5eaac0.nq.gz
    ├── 5b22fe5ed3600eec5b3675773a2922286b4a8e60.nq.gz
    ├── 5b403aaa8b7db5543240abb0790dbf52eac92d9f.nq.gz
    ├── 5b4c646edbb993e9e53369501fc7bf22d8d1d4fe.nq.gz
    ├── 5b90f817336f2d903d80737d5aff6dd4be3fefd3.nq.gz
    ├── 5d0128b1a096abae37656e47b86cae99ceae619c.nq.gz
    ├── 5d458eca346249054326ca25e5d1144aea21ed2c.nq.gz
    ├── 5dca6dec25d2e90a249be02f1727b16f70274a06.nq.gz
    ├── 5e10af6015eef590935a83030d380031c8feccd2.nq.gz
    ├── 5eab55d83150d3111a7f481d80a450f3551f42fe.nq.gz
    ├── 5ebe43356def9ea903b4045b7ff7f20ad12e0c7f.nq.gz
    ├── 5ec7b8485b2f71deb4d5cfeaa95ea8fb48fca14c.nq.gz
    ├── 5f283bd044941302e4890fcc21ef27ff1528997c.nq.gz
    ├── 5f8bc482488d75400ebd48cd348a8a07774e294a.nq.gz
    ├── 5ff44f2fd26f9b434feeecdfa5f9e5871d46a961.nq.gz
    ├── 613849fc2d7fcd73e9fb3f5e59de661fc4fa73e9.nq.gz
    ├── 61423c6186e70612aa979ae5615acf3476a8c366.nq.gz
    ├── 617e3d5dc3d5ce36b995359c66ad40eacf5fc514.nq.gz
    ├── 6213d56d073ee3ae9da363cba8ece4749b3d5ccf.nq.gz
    ├── 62283f8dc13fd4dc9e32a12d9c9290e2debd85c6.nq.gz
    ├── 62b04fc651fe509923dca8201911b65173c9f56c.nq.gz
    ├── 63637edabddf55a8aa7aa4f60e21a1ae26ef7a42.nq.gz
    ├── 639c899dbdad78df4b32be716410546f80707eda.nq.gz
    ├── 642d0f3a1d5cd6afcfa892f79be0e792b9b03574.nq.gz
    ├── 65045f60e2fe75cf949f90f3518fd2dfb8726cc3.nq.gz
    ├── 6609c85b13ad441d3400370faadf8bf586fafb1c.nq.gz
    ├── 66223a32e530c9efb1ae45d54855ddb99604ebd4.nq.gz
    ├── 67a00147daf866b09ce46b2954b153584ff8c954.nq.gz
    ├── 685cb036412535a83726a8d2c9c2fa509c9f6b48.nq.gz
    ├── 689bfdd0ad586a81f4f4d770da15ae34079add23.nq.gz
    ├── 68b23aec1b22fb4ffa82bbe0de9244ede05e1b3e.nq.gz
    ├── 6aa45a1e2812c18978107e034a26137451a0eb60.nq.gz
    ├── 6abee168b44e4ce20fd705d34845c587cf6100e1.nq.gz
    ├── 6b2400b6b0c27c2c1d559f2779f3d3c7266a5eb1.nq.gz
    ├── 6b8f300253a3c83e636f16005fbf6987c2890ebd.nq.gz
    ├── 6bff5061fe4fd5a12b599bb818a967c2a6f2286b.nq.gz
    ├── 6c2eeedb0799666c242682cdd0914156902a9b19.nq.gz
    ├── 6cc062f2a17e557b66a69b9f020c0367adc92f38.nq.gz
    ├── 6dd877f24cb537064134cd12272c10de50397809.nq.gz
    ├── 6e7c545fc1d2314ea2bd00cb212e8cdc22a376e2.nq.gz
    ├── 6f3a7c9e14b21258077cd614e6fe1a4fb606b83d.nq.gz
    ├── 6f778da1e778b2290816d9bda43a2996fcf6e02d.nq.gz
    ├── 70070a6abbcf7fefb401ebebc635295407afc395.nq.gz
    └── 705d0142d4b13ae6c8d9f8b0d3c2f820becfa19d.nq.gz

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

[laixintao/iredis](https://github.com/laixintao/iredis)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
