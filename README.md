# Repolex Knowledge Graph of HypothesisWorks/hypothesis

RDF knowledge graph data for [HypothesisWorks/hypothesis](https://github.com/HypothesisWorks/hypothesis), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download HypothesisWorks/hypothesis
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a92fe8cab6a3011e30436aa49e8c9bb815c5df5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6a92fe8cab6a3011e30436aa49e8c9bb815c5df5.nq.gz
│   └── repolex
│       └── 6a92fe8cab6a3011e30436aa49e8c9bb815c5df5
│           └── chunk-001.nq.gz
└── blob
    ├── 013813b707fb2f915a41a562c995e391bfc4707d.nq.gz
    ├── 0458e6494fcd49716c43e26698f6b33e67b57b02.nq.gz
    ├── 054bbfe88dd765258ce8d7f717c3d4fecc0f09a4.nq.gz
    ├── 06565553e67b883e387dd9e5dd42e03a720c8f30.nq.gz
    ├── 0737b91dea172408c3484522ad0793e79892fe56.nq.gz
    ├── 07a2c12bee135b915198484a7d5d5d58c96b41c4.nq.gz
    ├── 08597211a597b9fd7c57f73e58c1364ff25a3478.nq.gz
    ├── 08bb71353b774bd2d2c5a726c0a439448e2f95ff.nq.gz
    ├── 0931e7a6f3d186ac46d9023f53e51d79799d2012.nq.gz
    ├── 09fd7941421e7e0d3944d55ebf4f526b305f52db.nq.gz
    ├── 0a7309874c48c39527f6c3615d0b3b94ca6fb7b6.nq.gz
    ├── 0b6dd472c7b76659bb35564ec7e291973604bd9b.nq.gz
    ├── 0b75bbb3e4c104a624b159e575c6b04c17581e5a.nq.gz
    ├── 0c7eb8f1a177d9cd8d4732d571df380c7fc7511d.nq.gz
    ├── 0cab7c7e40f0cdae874eb6e0962de62d1332e283.nq.gz
    ├── 0f165d8bda6ddfe58b3bc511c8d0e46a1a8c419b.nq.gz
    ├── 1024d6bca14d82b43aae97558b1257beaef0a2e5.nq.gz
    ├── 105040f3423c5b3a5bb9aabc69ce416a74b140e3.nq.gz
    ├── 106c0d12c44161760a099e73fa169848cdaa99eb.nq.gz
    ├── 10a852b1c876c3a7b8e050da58b6341de42018af.nq.gz
    ├── 129143b56fab0f9df8bd52045e94bcbf1b8fc733.nq.gz
    ├── 13b487832ca622364fe76d9c412addb8ab64abed.nq.gz
    ├── 13b54f6168e6f85108e390f8e29f84bec033e823.nq.gz
    ├── 15587f41fde574befcb6aec700eae06359ee5f7a.nq.gz
    ├── 1826086100b1205b01013051c4cd8bb9d191c7f0.nq.gz
    ├── 184573584eabc17a056526d90d3fee3e0a71f5dc.nq.gz
    ├── 1a299801b18679665d98557160e73b337042c71f.nq.gz
    ├── 1d45d671662b5bb3293d3d82a4473fc683278e65.nq.gz
    ├── 1e26aa536b7a8f3b02db4e3e27a6544cbc5e24c0.nq.gz
    ├── 1f1ff6cd7cc67f6101a0ce28bf5f3c14c9005050.nq.gz
    ├── 221bda7a4a94007ef8e2e720ba5145e58f584e4a.nq.gz
    ├── 2323b3189f13721142f38acf6801fbc217d29773.nq.gz
    ├── 253db9df6ea13c29c4aad16b1ccd5dbe4451aaed.nq.gz
    ├── 26ffb983a273cc97356de217cd6b1e121d5ebc17.nq.gz
    ├── 2778a19ff3597e1e1e7fc786a1a25f2b88ac335a.nq.gz
    ├── 28989d5650485579f04bcc0471fdbff281e1768c.nq.gz
    ├── 29a8583248311b96e2e29c5b9c7ac6513fb75c35.nq.gz
    ├── 2a7578a76c89d22cd5f19769e2cde55981438437.nq.gz
    ├── 2db24206385fb58ebdcd0045d69cdf1a68844560.nq.gz
    ├── 2eb5f7cb32e7c0c50d83d0ea55bc4b2567bb88a2.nq.gz
    ├── 31f04ffe85d2fc50c43c4238f793c1e91f0c327d.nq.gz
    ├── 3266473c15b88525a1bd10da105e3cea6e58b6a1.nq.gz
    ├── 3307fed7021b4eb1ec3473acde9af2996e26dcc8.nq.gz
    ├── 330f059b90a46e355ee6c8659e2037b22f221910.nq.gz
    ├── 33e61281d90877c2f7ddc060c7fbddfa79f27374.nq.gz
    ├── 352ad4cef9a3d3607d0f9f03bc5f7027c54a7bc6.nq.gz
    ├── 36433c7246f421c483afa3491854e41ae5db84f1.nq.gz
    ├── 37f09007b7401c1d3a22029830dd4725402fd44f.nq.gz
    ├── 3a472bc836c30415445def35bc58338a1cbe38c5.nq.gz
    ├── 3e05740f5dfbaf0cd96d94d9d7010f6b5729e6e4.nq.gz
    ├── 3edb148d5b9abae47a0bb94a4baa94702bddc401.nq.gz
    ├── 40043d2e57bae6e728c56f88983192d89102f7e9.nq.gz
    ├── 400cbbe04ca6a65f0fe98102ff69c9fbccd7fe5e.nq.gz
    ├── 4312822a7629c0abf1549c39a08932d8a5c51610.nq.gz
    ├── 44d438c8e378b5f27ebbb6ac0833bbf585e8de04.nq.gz
    ├── 453053968494dd9bfe85fd832d257338978b2d7a.nq.gz
    ├── 45bc185fa9e9365f68ce19f94203b67b396f42d1.nq.gz
    ├── 46d2d2057f9f6b97a1256923144af55938582623.nq.gz
    ├── 47207e996dc2b804364685fe72728ded20601ab2.nq.gz
    ├── 490fd0311e61d19a9843c609cfe23282851e581d.nq.gz
    ├── 496323df01688cfa4542ba876a3a9525a511f0c7.nq.gz
    ├── 4aee62e2fb02e6f5bbbd433d0a41d1c57b18bba8.nq.gz
    ├── 4afbde3556f2f6764fe01ce33061eaea8d13d637.nq.gz
    ├── 4ceca61bdd8fcb7ae987f21aff7af6e96bffc09c.nq.gz
    ├── 4cfce07bf3fa2dba9ed2dd7838ad6946b1533b01.nq.gz
    ├── 4d0ecdf0bbd6f34878b891e92704a2229fd86f29.nq.gz
    ├── 4e04a5301fa8a2c70161365addfb88a7348edb7c.nq.gz
    ├── 504fb982c074cb64de7cb9a10f4583b4a24e69cb.nq.gz
    ├── 50c0f8afb403c3b19b76b00cebc61275861097ab.nq.gz
    ├── 51b90d7c212a65319ee1fe3f424db519dc17582a.nq.gz
    ├── 52042897e082f1bc3b9346827265a0c6d2c423d4.nq.gz
    ├── 526a59238e49a1c9a4c926a3e07ada0c7cf56b89.nq.gz
    ├── 534102aac150a01e4d33ee71a4bbfc56d3755586.nq.gz
    ├── 547e4b6ed6e78e1a9e5aa5dadaf92dbeac29b941.nq.gz
    ├── 561228ed3d7a927aacd57701db73db8eb242180f.nq.gz
    ├── 5643a1b4a30255e9f48af24c855ece4fe28b3306.nq.gz
    ├── 58dad57b067ef48d0989eab1489e6aa36cd51f32.nq.gz
    ├── 5b26b87b65a3155bb9163548def8057785e91930.nq.gz
    ├── 5bfe4440c79c84cce95a21b47095273f4f1fd3ec.nq.gz
    ├── 5c1d6d0cb543135e9b0138ea465051178fb5a7cf.nq.gz
    ├── 5da3aadada41f3020c2eb52ccca9f8ed3498708c.nq.gz
    ├── 5e82313aabfd163e2cd8cf9d9ad404f36bc256df.nq.gz
    ├── 5fddd5d2c33c23662a2cf49dba4d58829ec2ef05.nq.gz
    ├── 605349dc8ec374ffc7ccc94c1b1b20753245f527.nq.gz
    ├── 62684c63af9e5998ff31bedcb27c4615074ee02a.nq.gz
    ├── 630e7f0fbd8d7d7b6dc7aaac47b3ca3e50fb7f35.nq.gz
    ├── 638452bdc4b4bce0c343df047117585866cc05a1.nq.gz
    ├── 6645a5299ccd328a267c517ba9e0d3cc592c7a57.nq.gz
    ├── 6652622419227cfb2b7994a230d17732ae983c30.nq.gz
    ├── 678ccaa1279f55e412a245c0b6b2d541ee289023.nq.gz
    ├── 68c5ac456baa533dd7c4ae6f62c592b91204cd63.nq.gz
    ├── 691318f949b341a3dc36a668119ac9d60137d995.nq.gz
    ├── 6957db95f57b9f0e19840cfd8048a46e1bb2647e.nq.gz
    ├── 6b56b4ee1d12b68fe468bf010490819d0ba7022f.nq.gz
    ├── 6ccd3cc6eb0497c4b3dbea297f38e527116633fa.nq.gz
    ├── 6cf5517122919e85afe2c943a83c913739c1ff72.nq.gz
    ├── 6daf88b4d9733e41f042facf860aca3f4c38b780.nq.gz
    ├── 6e2bd4e2afb56fb81487c5f25b0f2faea32b4ed9.nq.gz
    ├── 6e811b07d99a5606cdb170e1741adc453e96d72b.nq.gz
    ├── 700578c7372bff2945cc483f81b59bd927897d58.nq.gz
    ├── 70197f190a8f1421a9b17c19b05d18b3a9c3c03f.nq.gz
    ├── 7293f9c86986ba55f63f564222a859d75f0fa570.nq.gz
    ├── 72ef75bb051e2e8f5b7384ea326f556c7da67189.nq.gz
    ├── 750319e5f50a0b2430eac02117b97fb9adc4316e.nq.gz
    ├── 75acf19d7af2db03de36f980e5dde633d22e5f76.nq.gz
    ├── 75f5ed4e3c24460e82bc3a258a08a044f6cfa8c0.nq.gz
    ├── 78c18e35c496c8b6f47a20122ea2b3bf69db7f76.nq.gz
    ├── 7a0488199da54f8f8f0bc359a1b853bd8d950548.nq.gz
    ├── 7a43822ee9c7494bb2aef892ae04f9e1f7cd4afe.nq.gz
    ├── 7b98313d179bd81a680aa48419c362c24f2af3a8.nq.gz
    ├── 7ffaa6cf5aaaaff30b487b1f6b36a5e55b1134de.nq.gz
    ├── 81927ab510ae6db92550c544f7d03c575eee558d.nq.gz
    ├── 827c4d35709c3b43669bbff381e013ef191c96c1.nq.gz
    ├── 82b63405d6e508acdec9684994d4463d0f5846cb.nq.gz
    ├── 82dedf15febd059386c6bf718ef6eb15665992ec.nq.gz
    ├── 83c340130eaa11329a31389905688eeef147c8cc.nq.gz
    ├── 84a9a1857244ec014e5bec9aa16992f673ed22b5.nq.gz
    ├── 8575c5a482946a1928f718918fcc2dd8f710a912.nq.gz
    ├── 895db212c077fb10e0e71bb1dacf580eaab07d58.nq.gz
    ├── 8a9d2f6ef3f117f9f845684153da35ad13650969.nq.gz
    ├── 8f9b25ab462ae78c562c5a77f2ff4cfd324e648b.nq.gz
    ├── 91cfa4d327bf0213999c2244ddad2ef9823de513.nq.gz
    ├── 92f29168d368655b09606834a0d788cf21b20b76.nq.gz
    ├── 9570ec776ae3a6b094d955d2c7f9c7231298ea24.nq.gz
    ├── 96fa45a58c997cb4424fd27e4a14ea6eeed25a7a.nq.gz
    ├── 978d23dc1273fc164267cbaed49ecace9a14ea89.nq.gz
    ├── 99ef4fc725f495296f67dfa19baef47e69d5c7f7.nq.gz
    ├── 9a5505d42d25f036db2db1c87df8b2b1989e9ccb.nq.gz
    ├── 9ae900aaefc01f78c09e2b5e8a93976b6453d1c3.nq.gz
    ├── 9ba61d5eb002cb336979da95a82cafc5379ffba9.nq.gz
    ├── 9c699683ed7876a2e28a1204e306594186d672d8.nq.gz
    ├── 9c6bfccfd7dc16dd4766f1a7129fb207b16638f0.nq.gz
    ├── 9cc2ffe96f2151630bac64ec2250d3171046c175.nq.gz
    ├── a0d2ed3b0a1908e2284b43fa431c23a9f716e24c.nq.gz
    ├── a1a210cca4196ba6af853263b55b4d66e233a12a.nq.gz
    ├── a2d3b988e796bc85ecffa1b0568a3e5326ca6c5c.nq.gz
    ├── adef593d019fa513f449119362deb23380528d8b.nq.gz
    ├── ae7034749a65742dadc3b431d99614042b6a795d.nq.gz
    ├── af45a95a8e3c1f5e726c4b6dabb1eac714b71f75.nq.gz
    ├── af908fe8e4359642b75a44f91f9052c1e7f92d2e.nq.gz
    ├── b1f9df667b101a9b64f72390a00413b70a3ccf18.nq.gz
    ├── b238c106da34e19484cfa078d464adc74164c80b.nq.gz
    ├── b23a8366f0c6489a07091778577b722e9caa32c0.nq.gz
    ├── b490a2af582b5c3bb7f6b78ae3f9ffcc87d87f32.nq.gz
    ├── b80230036b550b4beb3b78b13c53744be34e6045.nq.gz
    ├── b9831bf9a20c85c82068336b0d34e782de28d870.nq.gz
    ├── ba64a0ae6440e6d71952504c04767abb762c41cc.nq.gz
    ├── be78af7e128e1993501d11ee3bc432e452fa2e57.nq.gz
    ├── bf20cf734b7603db550f69db0f0a51df70c7ec38.nq.gz
    ├── bfda2c9faaacf24f2a75f3e514440d8190b06c2b.nq.gz
    ├── c03f9bdacdcf6608284e553f6dc2a4d490a9ec42.nq.gz
    ├── c0e1cabb7d4197de13d78f7bbbef379dcbe188bd.nq.gz
    ├── c1e4bbe84ec59e2518217578a66c1ab0b69cdc61.nq.gz
    ├── c23128f79d42ee4a335ed764fc73b7043c34bb5b.nq.gz
    ├── c55976fb20e4b393c52622bff7439674c254e188.nq.gz
    ├── c5f8611ef44300db811fb9197c748b71e95b3abb.nq.gz
    ├── c66c5328295fa24ac8654f3dc0b06aed762da776.nq.gz
    ├── c725a774b0986c696bd720cdd0641781d58d61f8.nq.gz
    ├── c8b3296e1d2d41c3838b19615520ad29784df369.nq.gz
    ├── ca98de1011f95895ddb71921addd272ac5efbf9e.nq.gz
    ├── cf521b1bae8521aa55efa0f4fa9e80f9a7272b2b.nq.gz
    ├── d26906bd3769fa1e49d379d75eb4bec5db0c11d3.nq.gz
    ├── d3850a57bd8fec47a6450a1c556244e77e0f60a8.nq.gz
    ├── d557c502fc6964297ec8ec991076c226e3f5544c.nq.gz
    ├── d5fc348fd3a29535bddb7e02a6cdb34497311574.nq.gz
    ├── d613b082a3109c3143d4d9e32a096ec6ed52ed20.nq.gz
    ├── d69a496d8706a45666c30372c69363f7a77407c0.nq.gz
    ├── d6bf776289262fedd43024e54a50beeff873d100.nq.gz
    ├── d83fd0bd7cbe525191524e02546b67013d49d0a6.nq.gz
    ├── da77d510d319ad3af0aac28d17515c61db5754aa.nq.gz
    ├── db38ae563b5bcfd95f3dc7fac823878bdb65b165.nq.gz
    ├── db8fb8c5dead2fcef6c665f889c9681963c6ca64.nq.gz
    ├── dbbc5e7df624abc68703c6c1ee5d4269c7ea36fe.nq.gz
    ├── dc72f5d275debcf003c607fc855e11ee551fbde5.nq.gz
    ├── dd9b92f1e1ec5310f6f2fe3d307cf8c4a38cfb4f.nq.gz
    ├── de1b3edd1ba73a956aa032c2894c3827d3fd1c5f.nq.gz
    ├── e0253023c5f4559e12e7af35b88599588325c9f5.nq.gz
    ├── e0cdff346553389470663cca545d5d49c63b7cde.nq.gz
    ├── e3722cdadae684259e665c5783e6c2c8bf3196df.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e72c52b8f3e787e21d81ec0e97b3b4f85c34beb9.nq.gz
    ├── e85ad1e0309521db0b143be85ea77e03eaac655a.nq.gz
    ├── e922a6364d75b5f9b4933c4cee7128b984a18f9a.nq.gz
    ├── ea57e8a0067cad30be225369dd01aab14fdbee62.nq.gz
    ├── ebc071eb077051cce187d599673f46f455251dc8.nq.gz
    ├── ed4f2340945c36f08fbba71a6629636f3c2669ab.nq.gz
    ├── ef8e2075099acd998c70e00c8ebd4c94d808bb97.nq.gz
    ├── f154be3c447f49d8f31f3ade309253b299bb8b8f.nq.gz
    ├── f249d4e059fb449d586a9b81028c2adc299114b9.nq.gz
    ├── f287adbdf5a5f315b6fa34c908637e2379d68d06.nq.gz
    ├── f4e01ec4adfbbc6675c6f9c9f933f94609d387f1.nq.gz
    ├── f612810b721a53514ee52437b926033b93894f9d.nq.gz
    ├── f6eb09640f2a4b4b6590584946521a188198c2b0.nq.gz
    ├── f87ec74199a67c14b515a7a60e6552f99db92002.nq.gz
    ├── f94bd0ef8d5d725514fa88d55e628c92c5136a74.nq.gz
    ├── f9ae5727e1e397869137d171afca33b08663903d.nq.gz
    └── f9bf19dbea59fc768e6fe26f3a8055f469692515.nq.gz

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

## Source repository

[HypothesisWorks/hypothesis](https://github.com/HypothesisWorks/hypothesis)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
