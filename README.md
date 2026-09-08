# Repolex Knowledge Graph of rust-lang/regex

RDF knowledge graph data for [rust-lang/regex](https://github.com/rust-lang/regex), parsed by [repolex](https://repolex.ai).

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
lexq download rust-lang/regex
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 25a15e272b3ae5aee76b525902c2ab91b0d9e12e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2aaa18dfaeda7a07202f1c8a0d7a7a10116d5153
│   │   │   └── chunk-001.nq.gz
│   │   ├── b028e4f40eac8959d05e82abf8404906b1c565c0
│   │   │   └── chunk-001.nq.gz
│   │   └── ee6aa55e01786e4d2c11eb1be805835bbb3bfa99
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 25a15e272b3ae5aee76b525902c2ab91b0d9e12e.nq.gz
│   │   └── 2aaa18dfaeda7a07202f1c8a0d7a7a10116d5153.nq.gz
│   └── repolex
│       └── 25a15e272b3ae5aee76b525902c2ab91b0d9e12e
│           └── chunk-001.nq.gz
└── blob
    ├── 01b41a1d406008fcbeceff215acc027e32ea595d.nq.gz
    ├── 01e6f440d25a6aa13a735fdb0c8976ce801e62ac.nq.gz
    ├── 01f430fcb799492936184280405d3fadd19a8604.nq.gz
    ├── 045c1fb18f512cc64a0b3f739ade43306f8c5a82.nq.gz
    ├── 049e8a89d1bcb843390ba0d37baf4de5f933beee.nq.gz
    ├── 04f2ba3c3ed2ee7cfc101b771c141f7ec7bf9192.nq.gz
    ├── 056213b28df87f412e262b66b3d99fafd1ce1aaa.nq.gz
    ├── 0570f328c37c45361599d42e6430209535a349d5.nq.gz
    ├── 0586935c03591ab25a5eb53c26625db5d7e72622.nq.gz
    ├── 05991a67189a6fc95c08a48f17296cafe2d5d0e3.nq.gz
    ├── 072ccbe7e251c2b8fa2dbcab4f2a1eafd749a236.nq.gz
    ├── 07c2847313162e56d4ee0d50c643c82760044826.nq.gz
    ├── 07f6ff2f5af7f8b2f4ccd77c7994496534a34913.nq.gz
    ├── 07f78194b21eaf0b9508d45bc7ac74c037f21f7a.nq.gz
    ├── 08793cd6dc760a1b8a15e8e958c9d3f741da2c97.nq.gz
    ├── 097d67177c5c79f8ed41125400db78e8d14dca1b.nq.gz
    ├── 09caffabcb1f16983aeb4ed4b0b6b71027666392.nq.gz
    ├── 0af313dea4676f2cbbe2075480f579ecf262b0bb.nq.gz
    ├── 0bafd8b2b463ceadf89ec2971d5222b25a78fe96.nq.gz
    ├── 0bd15f74d9a41e0b55861fb94c734d41e241be15.nq.gz
    ├── 0c2a352655459bd063351e2dc56e31ccf29e332e.nq.gz
    ├── 0d8f539db639381352c1daa5a13089090b0443a5.nq.gz
    ├── 0ddac4c96d116fab377624bcfe636dbed36f1615.nq.gz
    ├── 0f222c537ec8fe90c3631bc3db6948712c9af6e4.nq.gz
    ├── 0f2248d098716e8acd623a679786f1601f25d1d0.nq.gz
    ├── 0f809f33f44d17fb4e2d04c100226208e407d109.nq.gz
    ├── 0faefe97daa1e321e898b3de2a41dd4e69e33aff.nq.gz
    ├── 11b285515603a0de41f28cd77326d8c8f3eeea4f.nq.gz
    ├── 122e39c75e908b090df9129e6e3e8fe9625a35f7.nq.gz
    ├── 12356ced288eebad5e78dbd5858685ed55fd0633.nq.gz
    ├── 123efdde3104f5005e0f41365210bdd5b924afbf.nq.gz
    ├── 1257235a920a448af9c8f19786ceac9bc885f65f.nq.gz
    ├── 12ca5191b215781b9e07f293b1eb90992720d2df.nq.gz
    ├── 1316e6d695e47b6c71baeea2216c8f25437a5ef3.nq.gz
    ├── 13cdf24da72499c07a53a0106302c891dee3f808.nq.gz
    ├── 14a0c30bea70ecdab0c018dbe7df71cea61c1b66.nq.gz
    ├── 152769d2da2ec10d9f6145cd5da285ce172c17c4.nq.gz
    ├── 155fa6d8dc17565a6c6da9477182ae537ceb65df.nq.gz
    ├── 15b43e47f2f97d2825362dfc846f3ee74a98295d.nq.gz
    ├── 15c8b7362700c7fbf434ba9cd036ceee725fe48d.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 1769d803d4e07c25f41ae267c4b77deb586f15f4.nq.gz
    ├── 180e431db4e6602b991669c1e91807c4670f6eb6.nq.gz
    ├── 182bc7fa136d8e1c8caf68b89c8914b9e8f072fc.nq.gz
    ├── 184b6ed7019033ef791366a8dfd3287d7d347965.nq.gz
    ├── 189700d83f05b97857d156e2c65d7ea9eb75f374.nq.gz
    ├── 18996c2bfcb0f42a105d29fdc6ddcc618135b4e0.nq.gz
    ├── 1956e9846678ba00d45e608ae360c4a3d58f8af3.nq.gz
    ├── 197323116fb695ce36b17129ea3e3fe8f398d569.nq.gz
    ├── 1983a9b89ed7f7bfca570d7f587b728e372be1b3.nq.gz
    ├── 199561dfef4dab5c6e9f68d8a9fde5565b786f32.nq.gz
    ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
    ├── 1afd992f1ed4c0322ea50a42d6ef2570f9af2d82.nq.gz
    ├── 1c2ac9f764f7ae7596b65529d0921ad027d046ab.nq.gz
    ├── 1c44da5e6a1f155a4aeb1f4e26ef097835ef23b6.nq.gz
    ├── 1ceb3c7faa1dd4eccda1f2c63dfdf230b01a61f0.nq.gz
    ├── 1d86fc9bb3b235d11970ed058cf1e5db23025910.nq.gz
    ├── 1d8c0d632d41afd4ccdd62802fa4256d536e4026.nq.gz
    ├── 1f4a505db41784b36be5f081252c542b33fd0aa7.nq.gz
    ├── 1fb3fec9f24464029b0ecb413b4fedaccad33c42.nq.gz
    ├── 20736c7ac813e4f40f726260232570c1216c2767.nq.gz
    ├── 20bb8cc37149e565a8d186da3c4f94f5b4c05a09.nq.gz
    ├── 20bd6965c80d7618ef8e3aefca4831ca1322b197.nq.gz
    ├── 20f97b4bb9a69d0c0a705e66732a4524939c4afd.nq.gz
    ├── 210ab6f4b24e17a6cab6287ffcd3da7ec6c16ffc.nq.gz
    ├── 2118d1f59dea8897305fb1360c6222b11b95c97e.nq.gz
    ├── 213891b3e8b56385d9ea607a87da12832c5a087f.nq.gz
    ├── 21c1a3a31253c9d215fd1fb1f54c72fcdc6a7561.nq.gz
    ├── 21c8c0f9c839c83eab4ec38fa0fe62b06b4336f2.nq.gz
    ├── 21e484df96dcd904f1fd5a987d2a73151d5c63c1.nq.gz
    ├── 2270d66383735d6b82649975b7cbe32d4f5cd4e8.nq.gz
    ├── 22848ccf54f76cc8a96eb82188f22c1c7908d23e.nq.gz
    ├── 22893d7a328d1b501d7bd4cb364a8fed421b4334.nq.gz
    ├── 22a66e6a8b27eb8197cf03143c049da08d9cbed5.nq.gz
    ├── 22b114144984fd4e17fd6d3739e7866e2d27fdf2.nq.gz
    ├── 22e38c94ca4b0a629b591a48c29b7338f059455e.nq.gz
    ├── 233fcbc950a61bc614dc0e0a7418724fa0c36c56.nq.gz
    ├── 236613ae0ff8736a8c2fd64fa43a5a3b15c03ebf.nq.gz
    ├── 238f978b39c67a03a83aa378242247bdb8e95bf9.nq.gz
    ├── 242a0e6c3a9914e60ded8f1f515378b8ef4ae27d.nq.gz
    ├── 267808ffb7572d9918b40a6fc3cabeec65873e9f.nq.gz
    ├── 2730b602d2e9aa430e249c296cbe47b090e78133.nq.gz
    ├── 282893e55e95f25710d90dda5ecc6e1179b910db.nq.gz
    ├── 283e103a2e589865d910b6910f9d33b094a8de58.nq.gz
    ├── 2926fd316a91d7aa959730392c5796100c01af2d.nq.gz
    ├── 2965949f7fc3ddb9d904f928246946861857d2ed.nq.gz
    ├── 29f5595c76114006a671582b479a87104c956470.nq.gz
    ├── 2a6350e64663ce978d8d0aa2210e3e2810d02b58.nq.gz
    ├── 2a6d7709be75216bed090524d92389101b0070e0.nq.gz
    ├── 2af91cbce6f2c7caf49eb07caad0c29088cf30b8.nq.gz
    ├── 2b5a2a0acf93784592c31005df7d7ce545f637bc.nq.gz
    ├── 2b62567f12c6e60e84d75074972339bb1d2f3fe7.nq.gz
    ├── 2b851aa8f9caf97bc4da28f10b0d7187d1c89110.nq.gz
    ├── 2c3de64fb95663cbcb4d87fd5b36884153d4ef06.nq.gz
    ├── 2f1f0183edf4da111197e32a9bcd789bbc7af723.nq.gz
    ├── 2feb839d16a69acfbb8b1ea8979cf5ba175cafbc.nq.gz
    ├── 303e0cbc4a351928fc76db86aa64fc0eee64a423.nq.gz
    ├── 3056bca2f335559837ff22c307040e7d200693b5.nq.gz
    ├── 30924d4bd5b21a0d94f05bf14a92d9eba81679aa.nq.gz
    ├── 30a3a3ba0ef9fbdaff1b01233c44da7977d4bb7a.nq.gz
    ├── 30b412ca65079d449ec007f52e216adafbed5ae6.nq.gz
    ├── 310d775d7c28680504849a22f8624e3da9b31ba9.nq.gz
    ├── 312767e97b7e1cff042e7a32d26ea481adeaf6c6.nq.gz
    ├── 31a6e6d48890d314bd50e009093bee36c98a1515.nq.gz
    ├── 31b4ca3816ace287913339ed02eb65ca41b1aa85.nq.gz
    ├── 31d5572f8662f9d64aaffdf5dc6c0f4299022008.nq.gz
    ├── 32686214737f4dde5565049a798693cf6e229fdd.nq.gz
    ├── 3296d4376b4bfafc33a5fab81ec0693ee8ae0894.nq.gz
    ├── 329b9f031b21849e5c311e13c0477885ef700669.nq.gz
    ├── 3442137eb99a1a580851d0cf9f23d7ccd1ad1e40.nq.gz
    ├── 346e36971d4335f768783ac7f1023044231a76ae.nq.gz
    ├── 358bafc207bdbcdf3579ba4522a460fe161a8054.nq.gz
    ├── 35ed6d1eb26bac26eef3ceaa954512f5e2fa83d6.nq.gz
    ├── 36667d09ccc37b4655811efe3de369b365ce3465.nq.gz
    ├── 36cd713c0f3dc60d062adbf1709a3fe0120baba5.nq.gz
    ├── 373b14951ed1691624b4e8ca95eb2489266a578c.nq.gz
    ├── 37b741a71919f6d72feee3e54dc5c08fdaee2011.nq.gz
    ├── 383ac4a5b59b7a02dbacb65e32e982b74feeddae.nq.gz
    ├── 38e27059a2e3f35177f88f41007b4c7c747a3732.nq.gz
    ├── 39d4bdb5acd313c1a92dbeaa1c379aaf0596a315.nq.gz
    ├── 39e284b38280392f511a045d58ce2e03f2a228d7.nq.gz
    ├── 3a2faac403c450deba94c779d57d966a2372cbac.nq.gz
    ├── 3acc901d50af2075a742529dd39f27d212ae6164.nq.gz
    ├── 3ae75bd567b347a256b23c9c7c9e56d98206b93d.nq.gz
    ├── 3af46bfcffe22c4d99c78e808b9820ad1cc67898.nq.gz
    ├── 3bb08de8bfe5e57586f98717867667196a35d2de.nq.gz
    ├── 3be07bc807581b9f3c29f769836d1b0fa48a97e6.nq.gz
    ├── 3c4f980da3f36e3aee0bc406084b27d64da3ee0a.nq.gz
    ├── 3cc6a1a7afa60e4e9352ac85fb845e5d2e867ee1.nq.gz
    ├── 3d44b837219060fef6669f629ae1603bd26cb0ff.nq.gz
    ├── 3d62edc42317baa4a7ca60fbb0c06dca14a8734c.nq.gz
    ├── 3d78779f6f73ee4e6ab9c74587af1393e579c18b.nq.gz
    ├── 3d8196f7d094f65686c07391819095711549e310.nq.gz
    ├── 3d89e19b32fb497cf4ac83f994de0b7547bb05a8.nq.gz
    ├── 3e1585a6464928cf0f8768ead3fd4485972949e1.nq.gz
    ├── 3e1778b7191ebc17fd5bfeed7b10723a185f4af4.nq.gz
    ├── 3e437ca9ca73e5982e27a28181d28905732eff50.nq.gz
    ├── 3ebbac3c0070a52499709efe83c76c2d0e03d647.nq.gz
    ├── 3ece11d155411eef8382ac46e04856ad5be8af20.nq.gz
    ├── 3ff7d60e7d8f1f2b968e3a3c1a8a65bf70d90a19.nq.gz
    ├── 404c47721506237a58aa4913c76fc80f6bea2846.nq.gz
    ├── 405aa7533d49369570b5cc132cbfd9ebf0d618e4.nq.gz
    ├── 426fa6ce2a2542262d6ccd5afe57efbae68aaf06.nq.gz
    ├── 432b06ab9a64a0340687c16c88ee0a19c855fd8e.nq.gz
    ├── 43d5b5ba01c5733dbc95c7a5508e01b20ddb0bea.nq.gz
    ├── 4403ccce41caa91687fe4fb9c7dc03c35510354d.nq.gz
    ├── 4416a76f897f368cab37a81278346316ff4ea513.nq.gz
    ├── 44af3b3f34d1ea11803b9f721fb7419afad10611.nq.gz
    ├── 4625e8fe897d51c6f0c3316310057c93691400f5.nq.gz
    ├── 466510c9e6131eedccf9c29fff4d633b0ef4786e.nq.gz
    ├── 470e09b9c88b919861f1721d141f51329191d107.nq.gz
    ├── 475f9515963751873d4fff36c79d47ac2eeb2954.nq.gz
    ├── 47c83e806f8bcc99a57b719123a831a29ae4df40.nq.gz
    ├── 47c8460480891353aa8889b5ecb4f1a859b4cf81.nq.gz
    ├── 48224c6d114eaa197650b4ff57ecb1282cf6a53c.nq.gz
    ├── 48469f9e1615d0edf457469ac9a2fabdbbefce80.nq.gz
    ├── 49b87ec453dbdd6be96341b8fbe442371e151992.nq.gz
    ├── 4aaca66984f1e8d05cc7b37a9ae1e29b1dbcbbbe.nq.gz
    ├── 4b04c4f8fd2337ed2a6fb101ed743ed7aacb6b15.nq.gz
    ├── 4b7ac1bc90f164ec88f4f440fabbcd9aad906f7b.nq.gz
    ├── 4dba085f2fe8ddd3611788cb3195df8ee10ee6f1.nq.gz
    ├── 4dd33bd3d5138ca6456dc6a6a29e063105397c64.nq.gz
    ├── 4e783872e837d7abb7b8dedc8aa6b9648145f4ee.nq.gz
    ├── 4eb47c85cdd6b5535530e462cc0afe7a8313b9f2.nq.gz
    ├── 4fa13fbed47013e22bd6e9c9209ca0e8a61937fb.nq.gz
    ├── 50d3a136c3c827f7cf86bf449f732feee58771f7.nq.gz
    ├── 5126a4661ebca02b553de47988a8f3336f9649dc.nq.gz
    ├── 518530113f204a2d590846ed833fb4043c51f85a.nq.gz
    ├── 51ac16eeaa50df6cd601d56d411122266150aa22.nq.gz
    ├── 51af3613f51636e708ff76a44acc64188cf66dff.nq.gz
    ├── 521e935f43bc28b9ac2863ba8bb78146a363d17f.nq.gz
    ├── 525c4d13835f5b36eaae470b1ca988f9fe303920.nq.gz
    ├── 529513b0c8e97929b182e395489bb10274304609.nq.gz
    ├── 537035ed1d99b3f50c01078b885c25cacfb61ae7.nq.gz
    ├── 5376f348d10ebc6208c6250d29ac4bb4571ee572.nq.gz
    ├── 53ab22287e66bfbef0f7e8288709e37a07578ba7.nq.gz
    ├── 53b0701a3ceeb29c905462f23572fe1920ee5557.nq.gz
    ├── 53e082d8962935c63222000d9ab99e002f5ca498.nq.gz
    ├── 5415e7a45195f6734a9752dfc771c79d8092952c.nq.gz
    ├── 55477fdceffde5607987d1356be2688918704808.nq.gz
    ├── 556d91f4a0087a05860fbc4b84b7de92980b631c.nq.gz
    ├── 5653adc9aaaf41d63ac055520ef47e599ed59ad5.nq.gz
    ├── 567ebfb2ea95828ae60e55c0a38cb2ea3666bd0b.nq.gz
    ├── 569f60acda7f5cc9bd65b9a2fe977ac31500b016.nq.gz
    ├── 57ae322d50af21795d5750e34ff7e9b99ecf4624.nq.gz
    ├── 57c25ae602d4d8773818d6f9986e543542c47f0a.nq.gz
    ├── 583860839accee39e902f338fe5e6cf06ba6dbd6.nq.gz
    ├── 595365d50a895a0c5048cb7a28c8b89b79c55715.nq.gz
    ├── 59a62f4ed9717c04172fcd48a4cc20ed2fefedd4.nq.gz
    ├── 5a13a1047a2f4e622440f5e37e5fdb9ec1317738.nq.gz
    ├── 5a2ec09d50d787b1699e188215707cea1ce0d9f5.nq.gz
    ├── 5a71144e65cf802bbd1a16fea35d1906fa636190.nq.gz
    └── 5a721f142a7c0dde122fa33aed713bc56f844728.nq.gz

11 directories, 200 files
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

[rust-lang/regex](https://github.com/rust-lang/regex)

---
*Parsed on 2026-09-08 by [repolex](https://repolex.ai)*
