# Repolex Knowledge Graph of openai/evals

RDF knowledge graph data for [openai/evals](https://github.com/openai/evals), parsed by [repolex](https://repolex.ai).

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
rlex download openai/evals
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8eac7a7de5215c907fbddc30efdaf316913eccdd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8eac7a7de5215c907fbddc30efdaf316913eccdd
│           └── chunk-001.nq.gz
└── blob
    ├── 0004a06374a2d6c02bda45a6295478bd80ebd45b.nq.gz
    ├── 002ba72e0b41a8e9c2e8a392bf67352df4ce1f24.nq.gz
    ├── 00872ba551c9e5c0f6bb1f335ee8fae6959dce79.nq.gz
    ├── 00d6e934b65c040a1c004fc5cfcd3a61520c247e.nq.gz
    ├── 02519815c2f381a57fcd170962b89580fb4dae25.nq.gz
    ├── 025f4644311e7921e0f1e5021b1e0581cdbdc1c9.nq.gz
    ├── 026e3ea22487d35f5f8e2e1ff21bd95d5202cede.nq.gz
    ├── 03c88ece889ac1d652fff5df6da99bb7ec456e90.nq.gz
    ├── 04777dc22510cb97e6f7d87ffdd50f96e84477b4.nq.gz
    ├── 047b236209441cb0c73ee1806679dd0e0c54324c.nq.gz
    ├── 057af9142ecd1970e08dffc0d01d8efba89014cd.nq.gz
    ├── 07d442d0f97bc5a79f16eca1265a227b6837637b.nq.gz
    ├── 087c3f4b65d6b7da663c5e54335da84e20bfb46e.nq.gz
    ├── 0929d043e72200a197ea1c91cfc23a95f12837a4.nq.gz
    ├── 096dd8f52596550271d4e5917c9a37fc82f768c7.nq.gz
    ├── 0bbfe17f15204cac756f3d8a567aef641757d7d6.nq.gz
    ├── 0c412dedc4a9a0775c4ffa240fe997f2c2907fc0.nq.gz
    ├── 0d163f289c152d930cc892acfda4dbec945ca187.nq.gz
    ├── 0d1e8dd15a4dc67ea6d7dff5bc06d40b78e687ff.nq.gz
    ├── 0d2dcfaa4340dee2413ab5041cb7372a2dd59488.nq.gz
    ├── 0de8b83846c950ce456967542e303bd2f9b890cb.nq.gz
    ├── 0ec50c9acaf2ba45c442fe1e1979750ba3d63a61.nq.gz
    ├── 0fb399abf3899c7791b0280f1cf512bd32077b92.nq.gz
    ├── 10ab2c93c1803d390a570c824c4bc852bd199d72.nq.gz
    ├── 110af6c8cf02b3231c7a8f68786c2d3ec0d13fd0.nq.gz
    ├── 113fb14fa1b1990c089317f4e3fefdcb02f6fcd8.nq.gz
    ├── 117c4d910451d193d265f23ab7cf9101c0166137.nq.gz
    ├── 120a2492d71f033ae7ccd4a572dd0ae2b8d23548.nq.gz
    ├── 121457df8c1b27e797e4a45848869ddecd44228c.nq.gz
    ├── 1288d0e3c0c929da47664424bce3b20fff942cb5.nq.gz
    ├── 139d956a19178d4266974d2284d2e6fcbba4a89f.nq.gz
    ├── 14b725cf37c412d541cf0d9da1ffd21e55f13ecd.nq.gz
    ├── 157451b96f21b3cdbd4241f34df2e15ae209ba17.nq.gz
    ├── 1618f9e4750a70f77048a9fc84a73bbb23811c2b.nq.gz
    ├── 1742cfb8bd455a38cb7023076d44792e23df802c.nq.gz
    ├── 175cf54b9c700079d552d273c87abfee544a1afa.nq.gz
    ├── 175deb97aa13672d72eb80e027d7dccf6ec501de.nq.gz
    ├── 176bd5246e56894cef93ddbf34692f2ed38db1b4.nq.gz
    ├── 176df9a983cd4ad28345f1d03ec2b5fc88b990ce.nq.gz
    ├── 17f688d0b981c9d3081eafffbd26ec3b83eee7ee.nq.gz
    ├── 1804855f51113217289dab04ebf6313a90db82cf.nq.gz
    ├── 18c47cc6932b3d2e1fd2611ea526ebfbe6c08e0c.nq.gz
    ├── 196a082455d8b6f65c585fa7b805766ac20fbaf4.nq.gz
    ├── 1a150a763b971d8fc70a77d6ebc327380e7b631d.nq.gz
    ├── 1a473001729337347272ed63adfc645e8509060c.nq.gz
    ├── 1a4b68e0a3ca1629d5e7ab9265fb2fbdde334bae.nq.gz
    ├── 1aa806bab5f0395c4d9560532b052ca944fa6da9.nq.gz
    ├── 1c80aab0422f8e2be3ed77e387afa0e52b61ae23.nq.gz
    ├── 1cb872403c0b6951af786e2da9e42da79d0cb4d2.nq.gz
    ├── 1cbd1de338eaed7a03de01e2f743c9c308073823.nq.gz
    ├── 1cf8df0b1befa8f97181480571236c51e990e645.nq.gz
    ├── 1e1b45a3db3c0dc55089d59ec68a492733f3a17f.nq.gz
    ├── 1ea6974f46e04d1d901f63962f3ae67dd19f8342.nq.gz
    ├── 1ffe93bba0ff4e64672507f060c97823a46c8a82.nq.gz
    ├── 20c1580b2f6e707e3e7e64f0869a0c4d5673f8e3.nq.gz
    ├── 20e96b74fcec9a43ef7b24d32f2a0a5d7e28b26d.nq.gz
    ├── 20f7ef6aeb7715ea0fd78ce3d09afdf24a2af381.nq.gz
    ├── 2246843674cd93bb9669312593ffef97d7e0204a.nq.gz
    ├── 225d9252e2eef97e5748d117b8147548d40b1404.nq.gz
    ├── 236fe7a07f544dee627239fb94f886ae8fc45312.nq.gz
    ├── 2414afffa3a63896b65c634a27c6d06bb156e6fd.nq.gz
    ├── 26745469a0abf0f661bb43115ae41cc02660f51c.nq.gz
    ├── 27aefb7ac9ebedffaba65200d5bff204468c32e0.nq.gz
    ├── 2830d2a22f712330e328c3ba8f12a84ab351a9ac.nq.gz
    ├── 292383d0e827d1702d5e28f2f6890ecdc3fe318d.nq.gz
    ├── 298c10b6ba08b0428281bddbf2c9fb8f690be39d.nq.gz
    ├── 29dc157323c1bd3ea0acf778d397c0513e89cc44.nq.gz
    ├── 2a89d779d3b766ea016cd111c631d4a77ba247ad.nq.gz
    ├── 2b9c2bb039320e30c2eb0011722282dfffeb3628.nq.gz
    ├── 2c3ce9d213c10b08ee1c8274df2a10fd69a02971.nq.gz
    ├── 2ca94f39613564908596fa11dc9a6464eaaefdf5.nq.gz
    ├── 2cc48941690ebeed9531cf4a9fe7e6535d24a3d8.nq.gz
    ├── 2d76352f84a9faf0e492ff1cba02792500451859.nq.gz
    ├── 2e4adab2f9c650f71c3084f2f202f4dcaaa4f05c.nq.gz
    ├── 2e979592ab72c3276e7438e8c8a10e4cc7530874.nq.gz
    ├── 2fa495c7022c46bfd3875fac14f40ab01219c80f.nq.gz
    ├── 302c08fc405c9d594f98ec57523a28e7a176a45a.nq.gz
    ├── 302e8e5db38eb1c0cfe4f349d16e577b403d3ee2.nq.gz
    ├── 30b622ddba708a89964b3ec3f9bd41fc1a36e423.nq.gz
    ├── 30c0eeed97956dca03920bc68080b7925b8a7e9f.nq.gz
    ├── 315276e00f9395e3d411c3439cb71c44510b319d.nq.gz
    ├── 31b3b743e06b5c7eb162284738a2a4c5e496e438.nq.gz
    ├── 322540998fa1926f6fbb5154bd9ce11e04cb5a8b.nq.gz
    ├── 325f4c1cc2d90c2d304c381b4a590bb3e8a28f6e.nq.gz
    ├── 3296d7d19e660d7a4e00dcc5c9b99be47dc0d958.nq.gz
    ├── 32f4ecbafa3dd1eb1587ca4c0912c73070fe3fbd.nq.gz
    ├── 32f64614f651162ac541ae0e295cb2c0241f34c6.nq.gz
    ├── 337856cd72053b2012df32f6dbfdbbceb4ada1fa.nq.gz
    ├── 33ddbe8e6c41bc836fcce1c59d009075de2df7a5.nq.gz
    ├── 352824501d2e43765c063986583b9de942461cd2.nq.gz
    ├── 357686a95b72a5ddfe77fa47013c4a04107ecd6c.nq.gz
    ├── 35b8c99ff92f33ad0b874786eeed7f5eba83e64d.nq.gz
    ├── 36c9c34a0ee05ab1adc1940cac21435427c4686e.nq.gz
    ├── 36cb8dad11b40d8a6467f252f30a77fbf6b70b7f.nq.gz
    ├── 36f51faad400d5c59159ba96aaaefad62fcac86d.nq.gz
    ├── 376e95a032a44c18e3ca99eb97d06899a509f3f5.nq.gz
    ├── 3816836b5aa0d87772d23dfee5c4d596de8af467.nq.gz
    ├── 38cbccd59479fc7d450dd2adf62dfe3f9a7f1cee.nq.gz
    ├── 38d17a752840f1135cc3744f82f765e3f9000a03.nq.gz
    ├── 38f069ff657f0d689d547097a18120df97a6e0b6.nq.gz
    ├── 3903e24d6aaee4392144d7ce68a053fe57f43f16.nq.gz
    ├── 390aadfc94673154277a96b23f229ec40a5c298c.nq.gz
    ├── 3a7d841d341c1aa144c8bac0888c8a9f274fb9e5.nq.gz
    ├── 3cb16e1d7949405907e7d3c3190b32e42f7582d1.nq.gz
    ├── 3cd9e59bbddfafc8e85d26f3cf91708710113024.nq.gz
    ├── 3d1e008f6111934fb3fc46deff3bf4a4b40c4f6a.nq.gz
    ├── 3d7b113b51e2f120cbcb45861d8787e1cef984ba.nq.gz
    ├── 3d862bd29a631f6ad8d5899e099dcea72972a7d7.nq.gz
    ├── 3e2692217be87298e8177451216be53fb30ae0a1.nq.gz
    ├── 3e3d763587751e7c3f73a180b0c0fd2c5bbc3d61.nq.gz
    ├── 3e4cfcfd6dc704c5d289a5627742ecc4eadf4003.nq.gz
    ├── 3e650a6a25beda694958eaca0624a49c59260444.nq.gz
    ├── 3e6e0b5558660c7d85f9879af7528cf7b0fb11d3.nq.gz
    ├── 3ee424e0e4493dd793261aefc44e97c0e35b1a9f.nq.gz
    ├── 3f75fefc0b5cd82537adbe23c6d8711c9bdd4559.nq.gz
    ├── 407b3cc0331e9f8b93d4ed56f537cd148580a18c.nq.gz
    ├── 425c4fc1f715bcfe12c21b71750f821a2d1d0692.nq.gz
    ├── 42882a1098bec859e60caa66155bdd04ae09b3be.nq.gz
    ├── 434e082e88703154d66d57f016ed81918b2e6a83.nq.gz
    ├── 434e70deca06d96f5399f25b811d38f37dc41ea5.nq.gz
    ├── 45717c34b87f8cc001c0d621a33ebce4d9360bbf.nq.gz
    ├── 45b2da50868faf881af9960060ec73152301a67b.nq.gz
    ├── 46d5371af1e796149bf6e358b5e42754f89f3d3d.nq.gz
    ├── 46e2d34dff307ba202b9a108daa66567a2eab730.nq.gz
    ├── 47aece73cc21327fc678a3e31f31d20dc1962141.nq.gz
    ├── 482992710700e36aa7e1c63fb1542de68025f4f7.nq.gz
    ├── 484faaea36370f3391b2605e7b81dcbe84fa860d.nq.gz
    ├── 495acadb1844f04fe16cb5cbe6b54aeb86ee125d.nq.gz
    ├── 4b8718d60782d28ab4f54463f642d286b91c3c05.nq.gz
    ├── 4b8a4330acb1f55d9bae689ee9cf74c7a75c6fc8.nq.gz
    ├── 4c1ddcb443dea35da874a85a57c6c8b3d0895c0a.nq.gz
    ├── 4c8f5f5e782b1e35a1e1358c3af914e46440f6c5.nq.gz
    ├── 4c92bb53ded50bca3a82dce25f6328565c8b06c5.nq.gz
    ├── 4d72c0e5cf6508f88c77c913ba1fb42452575ed9.nq.gz
    ├── 4db98ece85788e9451c161fbf531d02736d3cce2.nq.gz
    ├── 4dde641e37e432a81715344453db5cb8d46fae20.nq.gz
    ├── 4e64018484c2f11f1f644692feba6ad56d59d606.nq.gz
    ├── 4f46f04e6e3c5e1fa968962e6e6301c5d08b34bc.nq.gz
    ├── 4f93689309493071a2109afbbb4243c14b3bb9e7.nq.gz
    ├── 501ec3b1a9ed3cbcc14ae73f64ba2edaa9253cf4.nq.gz
    ├── 50b70719f323362f00cc1e929c3e3e785ddee3da.nq.gz
    ├── 50b94adc18530f60d7c4fee1bdabae02c8822088.nq.gz
    ├── 5114dde5d23b8767c96862b13d3e75b602bd4658.nq.gz
    ├── 5240f85f94268c552f56e51ce2f744eb57732ed9.nq.gz
    ├── 531d3a08c90570761432c01f24baa0da4bbc5449.nq.gz
    ├── 536d49a83200a4d36945becff11d8cc3a5a344b9.nq.gz
    ├── 5390eb04375e0affc1df20657e0fbb6a764a9dba.nq.gz
    ├── 53bd0fc8f61be11f1e5a790b136a740abb789c75.nq.gz
    ├── 53e2844890bfc9a1ca9f1e27f1134c0f0befeb25.nq.gz
    ├── 54130346b34782828760eacd17741967906ee3a5.nq.gz
    ├── 5414766b8b1c6118e7777bf3ffa4ffc2528406af.nq.gz
    ├── 542e61dc96bcb27b562b171c9b6953b409cb3e91.nq.gz
    ├── 54fefb498ce944a142b03255c77440e09d1ea615.nq.gz
    ├── 550016ecd55e02637828ca16f24a202e3548961c.nq.gz
    ├── 55d07eb4d815e53cf4285c50e771137808077b8c.nq.gz
    ├── 55faf8e20fb80106e9ecdfc212aebe2bdb28797f.nq.gz
    ├── 569bc4ab7da5e36c9b7540e1fbe4f3b01bfcd610.nq.gz
    ├── 56b46b48f3e38fdd3e4c677acd7a87a8e54d4f5b.nq.gz
    ├── 56f76a1b419d426178d739171e7752e1c7307abb.nq.gz
    ├── 57d819a5b9564632c264194ba33d4625c424ef17.nq.gz
    ├── 583df30cbf162ec4acb5c210ca5ea049ad841c5d.nq.gz
    ├── 598aaf5c5c531e458ef3a0ee8d27cf1d267e92f6.nq.gz
    ├── 5a1658bea6f980f00a6479b494da6cbcec3eafb1.nq.gz
    ├── 5a24d083a57264d214d4f73138ef2ce79e82ddcb.nq.gz
    ├── 5a356179d00f328b5347de82f48c598363c5e326.nq.gz
    ├── 5a5dd975c8991e3da86572af86604c0e2e6f1787.nq.gz
    ├── 5a67f06b15782ba7e375d46f8b7e3743cb4e3e0b.nq.gz
    ├── 5a75804cef3df56a0bbe57fd0b8fcbd98954d763.nq.gz
    ├── 5af5a12af9fbf5b9465e94cfa6053611d3a4f192.nq.gz
    ├── 5b7f7e75aa912b6d73584cfe2b293db5db7d3037.nq.gz
    ├── 5cf5f5f3fe3b4ebb8993bb3a45aa2e4e351fd868.nq.gz
    ├── 5d0c589b30fa99771b40c188b7262180c036f67b.nq.gz
    ├── 5f2d97ed28672a6f92ed127ca17e5ef7711dec94.nq.gz
    ├── 5f422ed3b045a582b792988ea2ca2c9439c41481.nq.gz
    ├── 6095449000a9a743d9c66e7c6d6a216020184029.nq.gz
    ├── 60d3d323682051d00feeb235ce72afe52b9ac014.nq.gz
    ├── 6254f07b467a83aacd4dca8a7435210ab6f27c9d.nq.gz
    ├── 627f3cc5e92ed9fad7010cf8e3f147eaebecd040.nq.gz
    ├── 62917e86a845ebeab4888610b63b73a2c14b89e5.nq.gz
    ├── 62d015833d8139d791f33f7a7c2e694dcfc9a360.nq.gz
    ├── 62fbbb1ee235d5c7b716e357baed435627d21bbf.nq.gz
    ├── 639915dbfea53217ede71309d888626de075468f.nq.gz
    ├── 63d27e5741b7a99925dd16c4386a3a6b14c8eef7.nq.gz
    ├── 6496941bfed486e91e97e5485cab01517aa1299d.nq.gz
    ├── 64bc2aa72595e5987f7d691f39ed7272b6a084e9.nq.gz
    ├── 651da13e6de921b653bc9f91f9099e7b02753a60.nq.gz
    ├── 6540875334b534b64dfc998be55312b3790ff4e5.nq.gz
    ├── 658dab41ec54342d708e28ab4408c3bca7d86502.nq.gz
    ├── 66615d4907fa6579d25c8a1f8bbf919c8c5c5d58.nq.gz
    ├── 67a5eab98a88be7259bf6eba18ae6219d6f2e50f.nq.gz
    ├── 67c39bb3e1334478e9b489c6f1fee25b28b5c0c4.nq.gz
    ├── 6802a11aff57010e006348301abde76947e14e7e.nq.gz
    ├── 6837b776c656e768f27f6c79b01ed44643e22c1e.nq.gz
    ├── 687138a99ce4d2009d514a6c598f4cf4c903065f.nq.gz
    ├── 68d4a4391d0103ea931254f605620945f80f970b.nq.gz
    ├── 695729bbb97f62f998da8ff5b42f530e71cd1c38.nq.gz
    ├── 69c5052784fe04c241d287cdabb652eb78e2c62c.nq.gz
    └── 69dad1e04cc0fc0e641b904145e46fe7530e63bb.nq.gz

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

[openai/evals](https://github.com/openai/evals)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
