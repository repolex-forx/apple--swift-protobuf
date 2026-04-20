# Repolex Knowledge Graph of apple/swift-protobuf

RDF knowledge graph data for [apple/swift-protobuf](https://github.com/apple/swift-protobuf), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-protobuf
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c036968472334e42e06e4133a4ca846eabebafca
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       ├── chunk-003.nq.gz
│   │       ├── chunk-004.nq.gz
│   │       └── chunk-005.nq.gz
│   ├── lsp
│   │   └── c036968472334e42e06e4133a4ca846eabebafca.nq.gz
│   └── repolex
│       └── c036968472334e42e06e4133a4ca846eabebafca
│           ├── chunk-001.nq.gz
│           └── chunk-002.nq.gz
└── blob
    ├── 00d975c6d3573cfadb92f49aa5e37ec62bd49843.nq.gz
    ├── 0119d8f61a7d059e5f0ec6a94bc960d89c2bc686.nq.gz
    ├── 012490b93362515f3767b441b9c1d5fe1e289cf0.nq.gz
    ├── 023b628b918acc7069b24e4a283cdc6544aa721b.nq.gz
    ├── 027bc06e4e84b098befdc1fc441515e7201e7951.nq.gz
    ├── 02b84f00f09e1ce9b8f0f8b639593aa10012f463.nq.gz
    ├── 02c57fd5d78df96a656ca97f425fbc90f509f099.nq.gz
    ├── 05a52437c830903beb7b58cb851208ac80cdaf63.nq.gz
    ├── 05b0c8bcd667877617f43f62bd47a796ba056708.nq.gz
    ├── 05f2c62b98e3e0a9ae3558fcb8194f36da3a5733.nq.gz
    ├── 0619c0d4d930e1eea1ed6e36d2fdf167a0cdcb0f.nq.gz
    ├── 063989166c1af1c111a1849972a26c0e9902390e.nq.gz
    ├── 064746ff3f27a4799040740e5dfb447769f3b9b8.nq.gz
    ├── 071b3759d371802e85bcb68dac720fc6755e386c.nq.gz
    ├── 0861ac9edcfd87b8faea41de877c071c9ad92197.nq.gz
    ├── 0899dab708d683ccb495bb8a8cf14515e75ea392.nq.gz
    ├── 08a643ba98591993237b9ba3531dec0960009f1f.nq.gz
    ├── 09a7ece7d73d4be58c9344197fc71a4c7f7ec8bc.nq.gz
    ├── 0acfc18001faca472c52b2e94d54f4c0aeb02d9c.nq.gz
    ├── 0b08c0108f4640b5bc38313bdcc1db6a8f863256.nq.gz
    ├── 0b30255bc244e15b9823ff2e54a6e6e60759f140.nq.gz
    ├── 0b34fc68d472445e4bfe5c2b2b352cce86f107c6.nq.gz
    ├── 0b5d4f5a1f226ff6d84e775bb60fc7dfa2cf2c52.nq.gz
    ├── 0c454c345362586c47bf3f748f5bdcf076ce9771.nq.gz
    ├── 0c8e41b0d1bb815ba559f89afe617a904f6e1a22.nq.gz
    ├── 0ce02293f5f180363567bec528f6f267d613ab5b.nq.gz
    ├── 0d3d43f45e5eb67fb44e136178dda89cba3e800f.nq.gz
    ├── 0d953467e65f755f463700f8a42fd3c8a69fd8ae.nq.gz
    ├── 0e0d4e9d79fad7b113fdd91179e2d836c7406fbb.nq.gz
    ├── 0f6ea0cd9bc9bb8f6d70a8af25d041b804f949f9.nq.gz
    ├── 0f94f6c9d303398c2348e537cbfe1bb2c4c6a389.nq.gz
    ├── 0fb9121f199269284d692f5e2e587c93328b4e82.nq.gz
    ├── 0fe74d58b303918111dcf4dee18c8504ad3c1674.nq.gz
    ├── 0ff738c98367f69e179effa4ad9490f3dc22c6a5.nq.gz
    ├── 10d285f8a540f93c8d46e59a98514fedf24a7aa6.nq.gz
    ├── 10e35be39b686f580a196edbf767d426f22820d7.nq.gz
    ├── 1185d60181463366808498b9cb5a4012945d989f.nq.gz
    ├── 11bb943cb8245bc1f28e33c085a9c3c59e65874f.nq.gz
    ├── 11de1028ad7571522c685fe383a813c21e74a379.nq.gz
    ├── 12a810b6beab4f571d26dd82a3378e3ffe496af8.nq.gz
    ├── 132d0bc248de0786366a44704db61dfa9f996cc0.nq.gz
    ├── 1354212b13ef3c9ca6cde538c57d8fa242929067.nq.gz
    ├── 135f50fea51c72f977f48d06a7584aba0f61e260.nq.gz
    ├── 143d499db187dfa9a2b93102dd00a0af48044ec6.nq.gz
    ├── 147fa4eb8e63f4f33d68227d4536f23d0469bcb1.nq.gz
    ├── 14f3b8ad9ab78cbd7f45a4e21053f6ea71c6e179.nq.gz
    ├── 14fbcde2595fd345e576e38b6852decd12862493.nq.gz
    ├── 151e4d44aadfa19e05fa7f8bf8652941a238a8e6.nq.gz
    ├── 1537be24d67aef58524b36eaaf9a5301e2312b78.nq.gz
    ├── 15d010f2a925a6fe447d8b3fe19b7ad6a40b9d61.nq.gz
    ├── 15efc954de7808b813f03d52824b42e7e909b4e2.nq.gz
    ├── 162b6bd68850968522b81084e538fbff4a5010af.nq.gz
    ├── 16b6adb9ed59a29bf11ad95f2ebb0fac445c9f31.nq.gz
    ├── 16cf6a41bc31e2199bfc8112d94045d78fa0061b.nq.gz
    ├── 16f42141299c14288bf72ed20ae69e4ceda61c30.nq.gz
    ├── 17952ef3e3338d5c562d6746758a2c7e9c126fa4.nq.gz
    ├── 17b09de1d53fed9eeaac9500abb4d44a53926a7a.nq.gz
    ├── 17c7ff0f2f127bae86e73baafbd8217d0e0995f0.nq.gz
    ├── 183ffaca9f7d8b926f9bba7e696e9d2fbc5b9991.nq.gz
    ├── 18f6d2eced9402c6f505f3794ca3a8dc63da6df0.nq.gz
    ├── 1a491e2720059e37c432607b387a93c30096fa7a.nq.gz
    ├── 1a5936d0b95cfeaec2d3d7ad1c7dede1eb081b4a.nq.gz
    ├── 1bc61b681d0985e8e0647a525b0d1df8f2380b33.nq.gz
    ├── 1bd2d535498dfa243905aad0f4574445368bad1c.nq.gz
    ├── 1bf0c1ad9586578e8332d061f7648dcb041ec063.nq.gz
    ├── 1c334393bdb2df46c17d2cccfce4ff26707f7484.nq.gz
    ├── 1c339ed30e9a852d37027507a9f17837f86f6a2c.nq.gz
    ├── 1c8a092e9847b96c32bf5d38153fad2887116074.nq.gz
    ├── 1ca846032480cb1465d2034f8daf9e4605f91f67.nq.gz
    ├── 1cd45dc298d700983d41e9ea5288baf74833f643.nq.gz
    ├── 1d8a59e3883ea35ed2c1c6e5cbdd1ae1be39f1ec.nq.gz
    ├── 1d9f8d36fbc66c7e55f7cf5b887ca16f6e09a674.nq.gz
    ├── 1dd1ebd6177b5e82026ad0c5fa11e1363a4c763b.nq.gz
    ├── 1e8473fe041f817acf011646e4b952890e673e15.nq.gz
    ├── 1ea260cec4b65f1a1de3bae1abab69107ee4c668.nq.gz
    ├── 1effadac43876ff503d9ad9f6f0eb6e7c2fdfd73.nq.gz
    ├── 1f39fb37aa0b1a5a2a2030f270c365be8f7a832f.nq.gz
    ├── 1f67b5ba82a73186ecfb81efb8eb4a429db452cb.nq.gz
    ├── 1f98cf9c8a94f802b7fa2c427268dac9b22f57ca.nq.gz
    ├── 1fd05966de66123825d73b5cce508fab4f77f8f0.nq.gz
    ├── 1ffb3f17183531a5c74404c198b764419d9e6697.nq.gz
    ├── 2078a523dd64511a706c6e8bc718b7b4dc0dbb3b.nq.gz
    ├── 213655aae49bb0e2a6e6f23e1376f3eace63c62e.nq.gz
    ├── 21934e3b4fa65378f82944e5ad799c1131e06066.nq.gz
    ├── 21a36c1a26cc9622ef532763f89cd3da8c16de17.nq.gz
    ├── 2255aa4bdc3143f0091d7bb5fb61049aecab476b.nq.gz
    ├── 22a42b4598abbba14665e345089cd1e1f94b4ac4.nq.gz
    ├── 245e25c16a531e74c4ea29c847369640f059af6f.nq.gz
    ├── 24685858b7eb3ed846a42440f3728d15d4239831.nq.gz
    ├── 24e561a7a7beb24ea120073c152af0c4265983e5.nq.gz
    ├── 255ef0d35258280b5425053d344fc6f5cbedb671.nq.gz
    ├── 257189d29d334eb1d23bffd237ab05f31e6fde47.nq.gz
    ├── 26834d11ce5c48ffd7e2025eca11503fabba4a5d.nq.gz
    ├── 271771eeeb9ced1dc4d1fb8f2da05581d220ad47.nq.gz
    ├── 272151d82f662dcaaeb62caf904ba667aa5b2626.nq.gz
    ├── 27ccb1a4f54006ee3abd7ab2951aed8ffd2819e0.nq.gz
    ├── 28d65750b7787b4ac6e96c64d685fb223c25b5e4.nq.gz
    ├── 28f25e322e302f2b5433be24fee64eff4ebe2c19.nq.gz
    ├── 2a4a24b9f0d0efb5600415fd4d202ac074d0f144.nq.gz
    ├── 2a799275baf5e55c7dcc6345fa3cf900fc8ce972.nq.gz
    ├── 2ac3222da362f689f75029dd7b09bb0f0d913fbf.nq.gz
    ├── 2aed5dd37d1b602a358bd5d37a60b6a531340ef3.nq.gz
    ├── 2b3e159c8107558ab0c70ddc9ebbddbef6918de0.nq.gz
    ├── 2b46c40cb9020991eacd6c02bc7984739f90e754.nq.gz
    ├── 2b8f0aac2d7a3e16272723ba78a53bcdcbdb9277.nq.gz
    ├── 2bc37f019d51bf97444dcb093dd82526f8558cde.nq.gz
    ├── 2c7615ed6d3d0533d5f2c6fa879748b6df5610f6.nq.gz
    ├── 2cba42900e2ebf25d60587e49d057db63b0da179.nq.gz
    ├── 2cd4ccac25f95a879ce6e0eda89f4b703575c163.nq.gz
    ├── 2e2afc9fd460d305f87b84a8ca926d7e3d242d40.nq.gz
    ├── 2e42c302a544190d65320eb2ef4aca4d82c5c119.nq.gz
    ├── 2e6ed7f5498ce78c2faed15551b0e460138000c9.nq.gz
    ├── 2ec9fda40cfd312dc26a81329aab7646b5d955fc.nq.gz
    ├── 2f54bda481035501ba8c3e32839919345fa1d5c4.nq.gz
    ├── 2f8d26f942e41d8c430ffd713854f4248a1f1163.nq.gz
    ├── 2f97e61dd325418a92f703e30f6228dd2a800b3d.nq.gz
    ├── 2fc0073b826e7aa2c330a7d761f504f118fea39c.nq.gz
    ├── 2fdba052e423109ef86e2e873951d513d9cf07a4.nq.gz
    ├── 3024157ce492c4509b805e4512cc7002ab871d58.nq.gz
    ├── 30b40cdd2f95b8f97ddd44e64492ff80dac614a5.nq.gz
    ├── 30fa79097bb28ba7092ccdafe9c90847e41e0b4f.nq.gz
    ├── 316c5ed0dfbd225ed5d5d346998a2657e1892938.nq.gz
    ├── 31d06223922bf548b82308220853d99d79b887e1.nq.gz
    ├── 32a96c5be4c8e039e5c98b1bb6a98ebbec0b4482.nq.gz
    ├── 32be7f5687761c4484161a18c2ae1414e9516d35.nq.gz
    ├── 33264b4fdcc1290e957fc372637038aef8e10955.nq.gz
    ├── 333b7e99882e53e642cc46f20d8cf9d0ea8c51c6.nq.gz
    ├── 33d1183d5cf08a2c6248521f7ee8c4d829b5119c.nq.gz
    ├── 3407f73abcb9454e2192600bec09e4a765e1f311.nq.gz
    ├── 346826ada30d6ffba0c193f36ee24fe900f84e26.nq.gz
    ├── 34701fe3108d5226a2a33bfa2cee19a87e80a5e7.nq.gz
    ├── 348f860ec4b2de23ae02293ed6443a7b97652dfb.nq.gz
    ├── 34aff05ca1f4e6b66af2cf2dfed425059c35fd0f.nq.gz
    ├── 3595641b287a6fb56d4e51a762912df0583fa7d4.nq.gz
    ├── 35a407c5d66990c8eac26165319dba5918c8f1ff.nq.gz
    ├── 36068d185af29ff027c576d14baf0b1131b32106.nq.gz
    ├── 36b5067cb39f7703825feb4a12399286cdcacb7e.nq.gz
    ├── 36ed3eef80ad03ca00b9f487462a6d6cc04341a9.nq.gz
    ├── 36eff35a14d1c5e604348781ed6f5aa6710c141d.nq.gz
    ├── 380a592d70e17aed729d7e8d7cb3c937029b6f6c.nq.gz
    ├── 381a38912422cd7ff94766a836360f71b317c9b5.nq.gz
    ├── 3868b5ac437eb01f9b2498957009f0980dff9215.nq.gz
    ├── 387b8ea712ca1d2f9a3810c254861ebceec38cdb.nq.gz
    ├── 38d24d27b916b19751b2c759f0e6343e0ece5c9f.nq.gz
    ├── 38e0fc82caae82a4d9193266b3e165e1eec80623.nq.gz
    ├── 3993e4d938c199d8bd40a52298449e6814766fbc.nq.gz
    ├── 39a9ba90ddbdbe6abaaed72e3b9169f19619257d.nq.gz
    ├── 39e71214be5af52265d8eb97a0d5da52bbf73184.nq.gz
    ├── 3a3aee80286d845d085eb9aadfb058e79e4b153e.nq.gz
    ├── 3ac8ac92f32a25edc8593688b63018ff9f777128.nq.gz
    ├── 3aeb0975018716944397c82f4817a94e6ee6b093.nq.gz
    ├── 3b19f83033169b96f86c7a6a40cc8ce9803cf120.nq.gz
    ├── 3b1ab626c4fd72a999badcad4f2bf3534b1b4fb3.nq.gz
    ├── 3bf3e2c23ddbd5f1e3c0f8cf26ae02239ee8ec97.nq.gz
    ├── 3c1c01a3a28022c5d7b4a7da392552d31a09bd0a.nq.gz
    ├── 3c3f31fbe32ce3f55439c4ab644d8b4c70ef2ed1.nq.gz
    ├── 3c8adef80b1e73f1138adbd5557a33c024389907.nq.gz
    ├── 3df1872037d59d2a79e620b11cbd6b8faf242853.nq.gz
    ├── 3e1950f1df0f6f0df3ed1699cedf01bc3c95dcea.nq.gz
    ├── 3e47bbeae933dfec4ce6a49fe289df3e54d30560.nq.gz
    ├── 3eb7732f2ae195e9e27e58ad2676b4f9c8ecce65.nq.gz
    ├── 3ebb8e36a4b222abf9213cbf6e423f5a26273e1d.nq.gz
    ├── 3f1382fbd161bda98af4b3e4751dc5f28090f560.nq.gz
    ├── 3fdee5a6ad453dc0c1102f13e207c3e04d198df5.nq.gz
    ├── 4003f60df2348bd0c44bab643197308f960c16db.nq.gz
    ├── 409b8a4999b92e8e9c7471ffc01b0858e9b3f93d.nq.gz
    ├── 40c0703da5475e520a3631838a4a022608088b0a.nq.gz
    ├── 40e96eb2320084f8409ad5ca106d68a655c96670.nq.gz
    ├── 40f93d468e2595f61d6207823456a3103bea66ed.nq.gz
    ├── 41abd761d94e9e1359fe1b9575fd192cb9743660.nq.gz
    ├── 41f40c22247de377be99e30784229f3f128508a2.nq.gz
    ├── 41fd8d934f18e001541455a9524a2de72a59bfcd.nq.gz
    ├── 425aaa752757cd506738bed6f118e039239ce995.nq.gz
    ├── 42e1ce3b2742d596f6db94a5b683e4e6585ea7b5.nq.gz
    ├── 436039cdbaf4ae0df173d698fe7561012a8390bd.nq.gz
    ├── 437a843e5a6333cac4d56ff4d8ad5c88fe7418ef.nq.gz
    ├── 43d373f54418d3d6a4abf3823746ab07e68c27da.nq.gz
    ├── 441fd5e555c0d897e015a16f2f8240b24f4022e8.nq.gz
    ├── 442a1e1f693972383648919140fca5eb1063aa73.nq.gz
    ├── 457de4a099fd7ad0485aee484c02cd517483a74e.nq.gz
    ├── 463be35217c10ca348c671fccc57223f07d445de.nq.gz
    ├── 46b98ad978080308a1cd4c72fdee53fe640385ef.nq.gz
    ├── 46fd2d81b3522191d864b3f38b635df86735dc79.nq.gz
    ├── 475822b8f3384114c1f5c58404638ce4689d5bbd.nq.gz
    ├── 475d3d86992f42e90cbbae81ac4c4d717192a5ed.nq.gz
    ├── 47a10387f4db14871a4ce3419ebb2ce5c1b6edf0.nq.gz
    ├── 47f2a0acd48f04eb0362c448611ce68ac2c1825d.nq.gz
    ├── 48674bd4cd8adbd2072cf9413d1cbed410b9ff08.nq.gz
    ├── 4870604c4cd7c688532518c447431df4111cf251.nq.gz
    ├── 48a4acc2c5aeffcd70c94a311720c45b77da63f8.nq.gz
    ├── 48fb6b596947219bd045b1d3c71893aedbf68880.nq.gz
    └── 4926c9f0156f671977c5e7a1f214f2f84027a559.nq.gz

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

[apple/swift-protobuf](https://github.com/apple/swift-protobuf)

---
*Parsed on 2026-04-20 by [repolex](https://repolex.ai)*
