# Repolex Knowledge Graph of google/brotli

RDF knowledge graph data for [google/brotli](https://github.com/google/brotli), parsed by [repolex](https://repolex.ai).

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
lexq download google/brotli
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e61745a6b7add50d380cfd7d3883dd6c62fc2c71
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e61745a6b7add50d380cfd7d3883dd6c62fc2c71.nq.gz
│   └── repolex
│       └── e61745a6b7add50d380cfd7d3883dd6c62fc2c71
│           └── chunk-001.nq.gz
└── blob
    ├── 01b2998e25d787ab4e7400b82f11ddfbc3c7a2f3.nq.gz
    ├── 037118364250cbd2a53e267440000d2179c7875f.nq.gz
    ├── 040f179e2bce8f5f7a2f407b2d61ab86824bbe8e.nq.gz
    ├── 043572f396ab51a81231e1adee93f83ab1352701.nq.gz
    ├── 047c3562ecf1020a2d3164050489247ab9e39526.nq.gz
    ├── 05918ada841504e845247dba308763f0a38987b9.nq.gz
    ├── 068e6802cfd28ff10e7c5dbd1ae7951744f9bc7b.nq.gz
    ├── 07152197db668cd60dcc8141fc9d81e8d34c350e.nq.gz
    ├── 092754589e7f7578dbc7dce8bf19de55c5cab94c.nq.gz
    ├── 0941d53684a142062238e6ca1e2b781ad15a62f3.nq.gz
    ├── 0a0b910d0194afdb2515bb586f1727554f1937ef.nq.gz
    ├── 0c18f44fdf9b8dbc68e1426299d618e5a90e7966.nq.gz
    ├── 0cab81668158d240fe063060617cec9e3899c607.nq.gz
    ├── 0d758c9c7bc06c1e307f05d92d896aaf0a8a6d2c.nq.gz
    ├── 0eab7bcb18cd0b553a2b5e128443aabe08786334.nq.gz
    ├── 0f5c8f9d111701c66b483f844b310d74af11c20c.nq.gz
    ├── 0f6845fde037ffb7af39958060d6ad1b80b7c575.nq.gz
    ├── 104e6548ec4df4ab36ef48bde10995effb20455c.nq.gz
    ├── 1072b69b4fa079b36330958f87f0bc15c343db65.nq.gz
    ├── 10ca969ec1b21ac672ce6d3ec63e0ba91bdaae93.nq.gz
    ├── 1257b924066fe20b5676ef2086ef71b7dd3d0ae0.nq.gz
    ├── 14f65cc42975b64a7c9b30945c44bae6a0279ff5.nq.gz
    ├── 152f9ed5aa2d840c4a115d34ac0271262ca416ef.nq.gz
    ├── 15ed86207ec2432b5e044480a6ba6da6d6dbe146.nq.gz
    ├── 16d853fe5aad11d189d5d09ab716003f3168f853.nq.gz
    ├── 171cc9b8cf5ef281198281a9d659119f1a43a951.nq.gz
    ├── 1750fa5c7b2a8d30fa094b793f1b6c419eced367.nq.gz
    ├── 17bb347215fa2296e66e5509cdf088198192dfc1.nq.gz
    ├── 17ed3c197a72458bc6393bb6d9564c35608a7e59.nq.gz
    ├── 17f99ed7cc853512646dfccfe0a74eb16ff164e9.nq.gz
    ├── 1844907220d30ee356a39e576fc29e8f3688e73b.nq.gz
    ├── 18ed6470a3de780e4ff52dca47b26f678af2661c.nq.gz
    ├── 19a6d005fd1e604f1e9b318d9dd2d87fdc8f7339.nq.gz
    ├── 1a52869609e0aa47afdf7953d6ea85064b6d0dbe.nq.gz
    ├── 1c8a0e7976207fb9f03ed7e260950b62b8b9d396.nq.gz
    ├── 1e0aef083b62658d2bfbaa8784223ddb26e9f1e5.nq.gz
    ├── 1e269cbf05ee8dbd28a894b906dbdd8848d6d99c.nq.gz
    ├── 1f3f7ad5c90486797e235bb7279b8b6ffb159511.nq.gz
    ├── 1fde8d64f3d6f68b55c5693d5b9592022538b948.nq.gz
    ├── 208642e8301f75daa5d5deda3aaccbe630800cc1.nq.gz
    ├── 2094f13e5569f6748aced864bb342546e3f99955.nq.gz
    ├── 22154d2741cbf38bfbdc2f15b00c98b94b3ef3d4.nq.gz
    ├── 22bc060cad1ec0151d34c6e413c2ab6bdcc256a0.nq.gz
    ├── 2319b1eae908926ea8cf01bbc1b1ea4911698477.nq.gz
    ├── 2319baeb74093d50cf2ac1bb2a986a531eb670c7.nq.gz
    ├── 25626ec7f6b31b98df4e4bb0e121c17e0e725f5a.nq.gz
    ├── 25dda6b3f1bf96b34f94531fd845d4e1a248cdfb.nq.gz
    ├── 26183aba65353135666a31bac9d75683905d12a0.nq.gz
    ├── 268a10b601423d1638145a6e30afaa8ed9afe91c.nq.gz
    ├── 27737c5838e6518bf0ce5c55aa96bb18ed00d446.nq.gz
    ├── 27f4463d7f3a1c3e12d51a487306ec8e53a6c2c9.nq.gz
    ├── 2858a12ece8755a58b94ef8fdf537bd3466d968e.nq.gz
    ├── 28da198f06e8b89f464d630b6c2b6942bec942f4.nq.gz
    ├── 2a44b5def2201712a8261bdb95a5528341e0570b.nq.gz
    ├── 2c2dceba9b62295cf39770792da7b7132f649413.nq.gz
    ├── 2d47919968b6938230400fcacd0e7d58cc69f115.nq.gz
    ├── 2ed134ebc9b194b4da63f8891888cf7929b200e4.nq.gz
    ├── 2ed703bf7994b01f57bb300582b95811d3a07059.nq.gz
    ├── 2fbf41b58a80474f5141a677bfdebc3f7f9d37e4.nq.gz
    ├── 30c40d33f20fe6a41a2896421d063fd72ab43f71.nq.gz
    ├── 3279ee739911b1ef028ee300fe6e4fdcc853703e.nq.gz
    ├── 334a79a443c57dda25ba00c2f42619f1545173cc.nq.gz
    ├── 33b7cdd2dbaeddce1e35aa1a13f63d71154dc42f.nq.gz
    ├── 33e3a98e06889f59227f3444fa4cd905169f7f14.nq.gz
    ├── 34088b82cd029bcd3b6b0d1adc956f95734699a9.nq.gz
    ├── 3445f80f6719000a9a64e63f3f5df756ab713b4d.nq.gz
    ├── 366a82c3f0260a4e2a6ffeb50aefec015ce49651.nq.gz
    ├── 36ad2ba6bce1be0f450d0dabb69f4499ccc22f7e.nq.gz
    ├── 36b75f250d7989d9c6242957413ce697b13a2b46.nq.gz
    ├── 36f8128eaf7bba74d55b0380623bdcebf1fb3ab6.nq.gz
    ├── 3769516d943745d67d3873caf4e9149e95d4b73d.nq.gz
    ├── 378d3b5213aad5e05dd126d973d8baecb748356b.nq.gz
    ├── 37d86e253e9d812e7749cab674b9ee55f23083c0.nq.gz
    ├── 38f7f293d1d1f024a3dbf9d63f6dbe320474004b.nq.gz
    ├── 39303d33f8f080dd3707883d4cfa0560326808f9.nq.gz
    ├── 3a5890db755a997b460335fbc5fb2f4118cbe900.nq.gz
    ├── 3a7621100f1e18d80cd82d1f86589dbeeca6c655.nq.gz
    ├── 3bacbbc3413b22f12f3c1ce3912e3e288fb90155.nq.gz
    ├── 3d4f40e601202fbf39fb0b4f5c6fb763d1e4a893.nq.gz
    ├── 3ec8760a5581bd3222eaa8e1ab602946d448506b.nq.gz
    ├── 3f9cf8651c95f006109c6d04e15fe3e26e477fe1.nq.gz
    ├── 3fb2bfa29cedbebd0c226caec73b379f7e223f52.nq.gz
    ├── 3fefb8432b07a661c487ea2ade458ffabd2ca85c.nq.gz
    ├── 40efb3c113eed183d35b0db57fea058d52a94bae.nq.gz
    ├── 42af3c3f9d10f568c2ce5129a07114fe2d67192c.nq.gz
    ├── 4363e0d308df5aa467570d2e3ac8f311244f2aec.nq.gz
    ├── 43c655d44563cbd6819fde769845a4ec79cf2e9e.nq.gz
    ├── 453c22604209327a8691e995a12b74a81d603754.nq.gz
    ├── 46144e07ebea213d725b7cc7cef1c7676f064df5.nq.gz
    ├── 46ff68f50b90e996ba9f327b0d73c07230f7ae15.nq.gz
    ├── 47408cd685dc7256fa95f1abdb47a072138a041d.nq.gz
    ├── 481a2c791706b8112e1aaf6e76feae4366527956.nq.gz
    ├── 48909409079abbab5e8ef53423d278a663aaeca2.nq.gz
    ├── 49c17287c386a7685a7a77625058df655d75a507.nq.gz
    ├── 4b0bc4ad3d6c11b7132f5a15b6560ef7d7fb1929.nq.gz
    ├── 4c545dce5aa4b107dc9fc8acc375f6816e2928ab.nq.gz
    ├── 4c9b57ac9844618ba2f8edf6c29f18a11fda9438.nq.gz
    ├── 4d147e11279c3fa5f67a09d3c9b4e4883730c6e2.nq.gz
    ├── 4d699d5cfbb98089896c3020ab40a5b6de2735cb.nq.gz
    ├── 4dd0811bd61666f1e93b84014e2859e393dfe1a4.nq.gz
    ├── 4f10c7152ac34b94e6c29f45334e44b5046783f7.nq.gz
    ├── 4fd51d079bd4ec0c3c499d347c5a4e1ea1250f20.nq.gz
    ├── 4ff340123b6cf17f224cb08364bd702626661a32.nq.gz
    ├── 500c0709ca24338426091ca19777e13a1920ebdf.nq.gz
    ├── 5013629573a3923f92eaf5a92d0f708f7e5a4569.nq.gz
    ├── 50eaf7468dab47f264eee6ccd5016066c14bb84b.nq.gz
    ├── 51978015cf879f88f71fa846a715afa9e59181a5.nq.gz
    ├── 524e34198448e64a47cfb1ec9c5a2f2e5aac73c3.nq.gz
    ├── 54a7f007363f8a52801db92da0cca10cd583e310.nq.gz
    ├── 54dab698ba445428f52099f4cf308da671c9e8c4.nq.gz
    ├── 555263e008d2d3594e7a68cc03539bc28d76d550.nq.gz
    ├── 5651caeb7aca8acbf06f5a88187291cf9ab55fea.nq.gz
    ├── 572032bf7e07c99e87c8a31f767f4a651bef6dcd.nq.gz
    ├── 581509726a6a1756e36113b990bb10f971bf2c70.nq.gz
    ├── 586ae738591da005802e261996ba9b8825f62cb9.nq.gz
    ├── 5aa4d4f17c84231cc976302942fe239c62e3ccc8.nq.gz
    ├── 5b773251af400a79f39db76efde721c6907f37af.nq.gz
    ├── 5bd3957779cc39d2480123947c3af8faf152d30d.nq.gz
    ├── 5cde6dfb95ddbe34f572a7cf5327fdcfaabcbce5.nq.gz
    ├── 5da7115b60a7cfe39695db069a0430fea659a0b5.nq.gz
    ├── 5df6748e826c91977e4fffd1d57e97c844024193.nq.gz
    ├── 5e6c249196280cb65b837a84fb6d8d3ccb5961ba.nq.gz
    ├── 5eca238d8ce54ec575239dcc81f24b9879e70451.nq.gz
    ├── 5f4d0345037d2b31b60e2b036be7f539da7ed58f.nq.gz
    ├── 5ffbaa049ade136051cf0cf3fa05571a74c6734d.nq.gz
    ├── 62b99a954c590cf67ddfe190e880520a9294b867.nq.gz
    ├── 6362f69b9f5b599c6be8cd872df0a69bde2c3baf.nq.gz
    ├── 63d3b97ff92623ca1985b416b5b3aa06991c3626.nq.gz
    ├── 64f129b0e1bd5ba26303ea4c3056fd4d8197729e.nq.gz
    ├── 6586469e62ff9df422a50ce9e4c9005c10bf680d.nq.gz
    ├── 66905b991e21f4a242f75dc57b9769c5fd6c11e0.nq.gz
    ├── 669939c9f6adb3a6aa6092a3798171fda96ab594.nq.gz
    ├── 685a279dc06993aade6fedec6a6fd7105fd29724.nq.gz
    ├── 699b4b203d833afdb4a1d8ee8d72d0a6d067d17d.nq.gz
    ├── 6a55d420a8186fd40b050a2226ef870a73783a55.nq.gz
    ├── 6a9068aa40b136090922b4136769383158c6e350.nq.gz
    ├── 6b5d4eb0c989067ed8995f9523311792b0a3a551.nq.gz
    ├── 6bad9f613ca5d47125d77bf6daca4aff6824b97d.nq.gz
    ├── 6c65dc8e006a223135b8beb005d2e46428e6d207.nq.gz
    ├── 6d23118f0d0084657a974875123ddc1b9a0738dd.nq.gz
    ├── 6da2ff6bb432729630e68377199009f853305713.nq.gz
    ├── 6dfb92c4e4616690538278f34597e10b6cee2cb7.nq.gz
    ├── 6dfe8f21af2c90c4e5c498f4d897f30610277f8d.nq.gz
    ├── 6dfeedca8d43cf7aaf63c63885227bcd31a5ae7e.nq.gz
    ├── 6e04f0dc6fdb73e2c7b9d9f6df50f6c37b2a1fbb.nq.gz
    ├── 6e2e6e5fa2f7b20f9849c6b3ce98376a67bd822b.nq.gz
    ├── 6e390c36b579746ca588feb8d0a2c14b5adc9930.nq.gz
    ├── 6ea4069cddc91c310624b6d2f8bcdb8ebe55e81b.nq.gz
    ├── 6f9902aef2a72f57ff5fcadfdb08f427a7e2ab82.nq.gz
    ├── 7018934564274bda848e54da2be795aef7e3ba2a.nq.gz
    ├── 703365523b944b721362a0fdf7a8255b313e9dd6.nq.gz
    ├── 707a89a6e1b2d3e953f1b1d30e70bbd9258c70bd.nq.gz
    ├── 71d8f68adf7f36720e096c97fc338d63aea037cb.nq.gz
    ├── 7242a325509bd6955c6433e4582b3834fdfb0177.nq.gz
    ├── 7299ab7203b340afde0bb276afac01fb8de1b657.nq.gz
    ├── 72a5317f1616b770e51a0d6f749284ea11408cfd.nq.gz
    ├── 74b77d30ad417e77655b31602acbd40d165b0dec.nq.gz
    ├── 74d0be10a7ded87c29f81b65a8637ce52e2d0c88.nq.gz
    ├── 751b3162c49a6b1181a4bd539fd844456dda25bf.nq.gz
    ├── 75f376828fb41dfa45ec6bd5e30da0bf48806d16.nq.gz
    ├── 766bf91ffd26436e5a561b36a16943dd297be70e.nq.gz
    ├── 771b1e3d25ea26396fa8f746366fbf8a89c95de0.nq.gz
    ├── 777a5f5a55893838dbe19a7825d2aec06170e60f.nq.gz
    ├── 77bfa4717e6606fd110481504d495319769c7589.nq.gz
    ├── 7813681f5b41c028345ca62a2be376bae70b7f61.nq.gz
    ├── 7896a50247d15ca886d156c6927ceceba2a8b006.nq.gz
    ├── 7a094b4c166cca145a4473f3f9c14f42cf9bf436.nq.gz
    ├── 7a7eedaa098d8b92f8c397e8707769f468d4af3f.nq.gz
    ├── 7a9b21198dfeb81be098559b4da078fc38aa0691.nq.gz
    ├── 7b7d81b83c86d6293f00a3a4077b8720c6973926.nq.gz
    ├── 7b8581cc2cb1384800dd4ad1f31fe6273c73eb6d.nq.gz
    ├── 7bcf0705d33f28bccba87f53a66208fae197e681.nq.gz
    ├── 7c678d3d8fa55b99649d7aad95f6039d184dfc99.nq.gz
    ├── 7f7b256a40cebccaa21315455241e03d8af2aa83.nq.gz
    ├── 80007f5dcad6cc9767299d24cb37674b460cf035.nq.gz
    ├── 814e56332c47a5dd142caee7580b84a2e5c4f07c.nq.gz
    ├── 81a374354c0de051af9b0b779f6282ce9f76f36f.nq.gz
    ├── 81f0388bf825cf858828b03ba404b8202f303e18.nq.gz
    ├── 825237a3357931389a6d5a4a1937f7381234bbaa.nq.gz
    ├── 832e7b2b6e3701157cf47edf0a2c084af0a2572d.nq.gz
    ├── 8395f04f72809970046b2ff08995269fcb850e18.nq.gz
    ├── 842e7995c39db5cb06e968ab2ad958cbaee150ca.nq.gz
    ├── 8450112d921e0289af3855a187161de01041af0a.nq.gz
    ├── 84c35ab77d58f5b50a72f27a93499a3b7e49c4ad.nq.gz
    ├── 84f606f03773fcfdd2d2d115cce07a9b854c698b.nq.gz
    ├── 851c75cc5e74cf97d145360755d116d2409881f2.nq.gz
    ├── 87d579d45f814c5d931cb86862686a00b7990c49.nq.gz
    ├── 8834f3275a80e77f03dd99010f43b5024255b515.nq.gz
    ├── 88dc7b60fe2afeeedd1ba1bb5d4229b17b29b041.nq.gz
    ├── 8915918cfc71f59b268e3230c6149cccc87ef68c.nq.gz
    ├── 8cbd5eac67b2a23579358464b74dab9c6e7e5363.nq.gz
    ├── 8d90937b43689b6de63b0421e843afa835ff52b3.nq.gz
    ├── 8dce1480399c0c6bdf95265ce3bee4f63e7ca712.nq.gz
    ├── 8e079c04225d58ed61406dc9430bef2c5746c022.nq.gz
    ├── 8f53f39d3f2e8edb944f80c2b1cb841564efe498.nq.gz
    ├── 8fac0345cf82c2639ad62d7c6e7293aeb9d8c2e9.nq.gz
    └── 8fda80c220395806cf5768165b40f42b34279a9d.nq.gz

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

[google/brotli](https://github.com/google/brotli)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
