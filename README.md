# Repolex Knowledge Graph of python-poetry/poetry

RDF knowledge graph data for [python-poetry/poetry](https://github.com/python-poetry/poetry), parsed by [repolex](https://repolex.ai).

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
rlex download python-poetry/poetry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 38a86661d2ae58694c76d0bb4e628e1400d6dc6f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 38a86661d2ae58694c76d0bb4e628e1400d6dc6f
│           └── chunk-001.nq.gz
└── blob
    ├── 000a806eb9f0b3babee9a03db1605f0a65c0c04b.nq.gz
    ├── 014a94a69a888195942899c07bffa08007e312f3.nq.gz
    ├── 025032a16560f85acf328f909319ef6c8405a722.nq.gz
    ├── 02891e025fdc49ba4b40377657f1c976a2b2cdef.nq.gz
    ├── 03fb6ee077c34cae75d3c28f257dcebe97c7833a.nq.gz
    ├── 03fe010d4d7957e0f56f5a080b7a8b5114bcdb5c.nq.gz
    ├── 047b0cd3be0afbbd56980888b473372a48ca1f24.nq.gz
    ├── 04a1dca1b920be99fcafe2994bedb270b3d85d85.nq.gz
    ├── 04d839f235c4cd57537ad117b5b25ea02ca9e7d5.nq.gz
    ├── 04ea890c943c3af2754df4bc7976cd7fbb570c1f.nq.gz
    ├── 053f9cbdc25929945a0c7ca83b86d772184f2034.nq.gz
    ├── 05c2797d30d6ca29b4ff49b92eaa2590442ae43f.nq.gz
    ├── 05c6162ebc2c13f6f48d21bbd745b305d0a1ea9b.nq.gz
    ├── 05fc0c25a3be626871e1b4205e33340c2114327c.nq.gz
    ├── 06880366cc988fa31f41b8d02dcd066b718da5b0.nq.gz
    ├── 06c2827ed277e911e2a8b263880fdd5f0bc75c11.nq.gz
    ├── 077ce46a64734d99b1175a23fe4d361b51a7c4e2.nq.gz
    ├── 0840377a8fc64e0c7fbdf246dc711f99f701e298.nq.gz
    ├── 093cf3adf17215d727c77e7ddb868b38f435ce12.nq.gz
    ├── 099b9eb696fb9219561da5ff8c940514480f2611.nq.gz
    ├── 09fef493e789cbd68e16407e1c59b1d62b71ecb6.nq.gz
    ├── 0a9d872f93a07b8797b27d05965b8939518334c1.nq.gz
    ├── 0be6ee6f03d3f2f086d5fcff6a66be0a3d77af1f.nq.gz
    ├── 0c6018291a572e36dc359c2af985cfe329aacf95.nq.gz
    ├── 0cbd289d9ae69e03a77337ea63d2e33c4019cfb6.nq.gz
    ├── 0e4a71763fe63d7ffbe15b2a8d8e963a919276b2.nq.gz
    ├── 0eb14528baec01ea0e4173efe4d434a5ec08363d.nq.gz
    ├── 0eedc7be1ab721ac23f560023333ae53af413314.nq.gz
    ├── 0f09fb96fc429146526860e8e4d2ba31a23a2d11.nq.gz
    ├── 0fa207acf7a97978a0998404a26ef32e79eefe8c.nq.gz
    ├── 0feb2bcaf001fe10987b8ccbc562906902137780.nq.gz
    ├── 106b44d1d706fdc8b7278ac049ba77432ea8ee77.nq.gz
    ├── 10d8f3f3f3da7ccdaea098fe27bdc7590c091464.nq.gz
    ├── 1110753e3fe5becde6996e9624b84ff9cd9a7b9a.nq.gz
    ├── 112649d593b29b881287f741b4f9e7403390a5b4.nq.gz
    ├── 11b7a3d226863f02db62043d2cc66639c190adaf.nq.gz
    ├── 11bef9cfb1331737065f6317eaed285061609984.nq.gz
    ├── 12538fe8bb309619a22d71c90392f86565ac3f3a.nq.gz
    ├── 129f6c2ff799eacd3f85d536f1dcecb072bf5610.nq.gz
    ├── 12b32e5c3d43568e261f1ce696644dc84e1c4f2b.nq.gz
    ├── 149aa9527c577a1828a5a3114377960fd1e41a88.nq.gz
    ├── 1548c3a33a1a887aa66e637dbb76cbc696ba1092.nq.gz
    ├── 155f93446c12070e85699470291c808307a895c3.nq.gz
    ├── 1568e31dcb0d44b79ae6bf1c872df81ac1f7123b.nq.gz
    ├── 15b72917b0ffe915d9e6a773bae580e570211a45.nq.gz
    ├── 1615b002392a7504f4f03b4dfd11ef9cabcc9e4a.nq.gz
    ├── 162c7a30ee15ddfbb081d1084e5e77f237868878.nq.gz
    ├── 176dbb952634cf5ae6de8cb3e3d448e823edbf75.nq.gz
    ├── 189d19ef69e16fbda812241b3359f644b3c745fc.nq.gz
    ├── 18f5472d337b3ee2b524aec7446c46b3f91ee6eb.nq.gz
    ├── 19279f2da23449eda90b344f2a6cdb30eff7d47f.nq.gz
    ├── 1aba06effe1f17237e127d593ce92f0095044d1a.nq.gz
    ├── 1b30429c78cec0905c7691e8c082b0e310a86132.nq.gz
    ├── 1b7696895ccdf3950f50d22e392edfa3fc0be8ed.nq.gz
    ├── 1b9c1817ca2dd76c1651781b09ddee69180d0bc2.nq.gz
    ├── 1b9e242ddff09b2d0884f1875c026327868d9bf6.nq.gz
    ├── 1c7074117eb414659513ac0704e8e857b1825b40.nq.gz
    ├── 1cb00f344d5ac842f965f14f0d6e3fd20a64f0dc.nq.gz
    ├── 1ccefce3b218c5926ba57c1d2ee4f820d4a123d7.nq.gz
    ├── 1cdbf5377270c1674a4d8240767c41ba9d3e9110.nq.gz
    ├── 1e2ea7540596a37d14c02d73d55d695f87c7b69c.nq.gz
    ├── 1e866d8dc8f12e07e9899b69d2e84d514aade500.nq.gz
    ├── 20721382dd0a5aa4ffc7d173aca85874d7483e7d.nq.gz
    ├── 213d264674938580fcf548a8c60df84cebd7b57d.nq.gz
    ├── 2142f1dc77b5a04ec5979a5b5a5c3ce1e02c768f.nq.gz
    ├── 21b405d8c2dac873e9063b1dff87e46c3876aa58.nq.gz
    ├── 220a8ef8975055aee13eabd9ce5562f3c6cad736.nq.gz
    ├── 223bcfaea68b81fb96ae2e201b6febd2c8877ccb.nq.gz
    ├── 2264b167cfac84bc241568de6dcd982d63ead5ae.nq.gz
    ├── 2278b5aa5840799a81d6f2307b36732a6e69cd07.nq.gz
    ├── 245121d496d2808ec3ad2dccfe6f0113eeab0bdc.nq.gz
    ├── 248141d4b6ac3b14043a6f6b5d05f6d8b3495ffe.nq.gz
    ├── 25ec2764d77976c64408453d6c3f6e0a234b5379.nq.gz
    ├── 26c229f73e0b42ba7718fe60ebfb7ad58e001a2d.nq.gz
    ├── 29233434af87518e12df8471912ec27a6c3c3500.nq.gz
    ├── 2a25518780c9b61aed6c26bb38622f180e384cd1.nq.gz
    ├── 2a5809cb573967400388f484db17ae0250c24584.nq.gz
    ├── 2a7e8d1ce18b3885102a671c6e501711ea578cf9.nq.gz
    ├── 2ac98bcc428174dadea0b059d02259c85775531f.nq.gz
    ├── 2da6c360c00a862909e855cbc2ec23e7fa093091.nq.gz
    ├── 2dfbe7274d80b6204149922c44e8e29ea081e7d9.nq.gz
    ├── 2e80aee347f85ee2e23c868ccd66b308b9724c8a.nq.gz
    ├── 31237bbf72c98a57d9382b0b53eeb404d85efb2d.nq.gz
    ├── 31859db816f6b579ac0ca98f81bb257608bae815.nq.gz
    ├── 3229630afad63235fc7c2d0bf31d292f85b4801f.nq.gz
    ├── 3254f4262db1d6ad186270e10918bfcd36f3a36d.nq.gz
    ├── 329e3582ff11c903536813dd7631e945ef1ba556.nq.gz
    ├── 32b52549dad77394989172daa1ce960ead9be42f.nq.gz
    ├── 32bc5acee2c9ce7eb3ac45b25533c8c2514df1b0.nq.gz
    ├── 32ceec3786318df251402220c5ea8dd99b86495f.nq.gz
    ├── 330f2b9dc14f20032c28d83ba9aa322253d84df2.nq.gz
    ├── 337c6fc4301f39085a4e30c82fd7b08b3ed528fe.nq.gz
    ├── 339de55c5e0a4744f2e925991d50d1b0098c58d0.nq.gz
    ├── 34302031d7807b26e768deb325d7fbdf96e1fbce.nq.gz
    ├── 34859d5bd52f33e65eaaabf09b94d24a3bebdd9f.nq.gz
    ├── 352f15e5cf00768e02cc596c0a92750c9fce3113.nq.gz
    ├── 35bb6c5c05b7497c8512fae72aeb8dab001d65ec.nq.gz
    ├── 365ce8b3374ed77006ff08f5aeb78647629e28bf.nq.gz
    ├── 3693aa87881cec257d982834f4c293888ddd47f9.nq.gz
    ├── 36c1b3b19f78bd0939fe34306e26e4b4a6ecdb17.nq.gz
    ├── 370241fa47683426d09671d225a5d4365e30e06e.nq.gz
    ├── 371caa6419070bd00f162d77ec85d305d538b9af.nq.gz
    ├── 37615c8ce575256eb4e45c620e572cdcb7b13e85.nq.gz
    ├── 3803c815aeec32130dd842a271cb971bcd735d69.nq.gz
    ├── 391fe8391ef463c6c9871028e1d046d98a6b7040.nq.gz
    ├── 39ed699a35dace2af0255f9b9c4ffb0934e9c7be.nq.gz
    ├── 3abb0fd5b1927cc12fa0205c06a699a3bffb6bd4.nq.gz
    ├── 3ae42b5e92e9277c1740bed6887975ff93c96816.nq.gz
    ├── 3bd3edf14b1cb8294043c244abc82429ab877a56.nq.gz
    ├── 3c2e1b9b7c679e9f6ebb198b15a69e2fce92105e.nq.gz
    ├── 3cec1de9a56be93a7213ece9a916b847f4d904b4.nq.gz
    ├── 3d1a31bc5765d6eb5a9bca03cfe9c7635e0e8c93.nq.gz
    ├── 3d70d8720bf738cb5853986500b9c2396a86e8fe.nq.gz
    ├── 3dd226e99c49602d00053439cc2aa5fb85f9c92c.nq.gz
    ├── 3ed7054f88b09a70c609dd650555049f821b538f.nq.gz
    ├── 3f564cb6ff720c25025a6207fd1d4a923a175906.nq.gz
    ├── 3f5b804d7cba2ef54de79969e706fa7f2a3c2a1a.nq.gz
    ├── 41295ea5ac91be1fdb229d2ece0f16e65ec3207d.nq.gz
    ├── 41ce3a6be9c0075c80f901759f59d15f99acfce0.nq.gz
    ├── 425861568aa2242d00d0d46b20db1bdd63ed87c0.nq.gz
    ├── 429e08333da8b0febf4c2aad088f4393828dfa62.nq.gz
    ├── 42b329869a219ec10cae3c76478cfb118a8a9ddf.nq.gz
    ├── 42ff15e3a35da61aa179c3a67c81c6f78ed7fa1e.nq.gz
    ├── 434721368c77f0f2d0857ba307b588a18a36543d.nq.gz
    ├── 43582ddef46baedcff3fd2955d5d159e69338dd1.nq.gz
    ├── 43c0716994b9e18d8661e7b1d0b4d1a7d458f358.nq.gz
    ├── 43d40d61d8ff967d3042d32fb01fc92ab5f81033.nq.gz
    ├── 43f0c7ada86c5a31400d7546c2b948fa0087569d.nq.gz
    ├── 4457b50616944f1d40a994b821f310dc96669fa0.nq.gz
    ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
    ├── 44e93caa6239cbebd279031f7d7e9c61a104fbbb.nq.gz
    ├── 4523dbecd99f70d94856a18c6114b159f7574539.nq.gz
    ├── 455d7eb0e0ae9cae19d8dce144b8cf258f9bb316.nq.gz
    ├── 45a61d43cadcc283c44c7641cdfb8301b240eb67.nq.gz
    ├── 46e2fc497f1fb183ba56a46977cda319976b6cac.nq.gz
    ├── 4723483f725e8c91557ee21bd42386bbe493840f.nq.gz
    ├── 4774f141175bd6b9ed01704ebc4b46c8ae984208.nq.gz
    ├── 49fa2f62d71d88b8894ba351b2daaf5e3ab730a7.nq.gz
    ├── 4b7ffd2e49e15596fc20cdc693164b30dd978f1c.nq.gz
    ├── 4c8cf2f72b3b7effa7b0513aa5d694ed7165e165.nq.gz
    ├── 4d0f1302baba573ede481d136b5c54afe695e550.nq.gz
    ├── 4d69ef0bcb2849ee85c29e138f8e720b4e6226b7.nq.gz
    ├── 4d7fede62401f07c843dfd0a8441fcf6428d2042.nq.gz
    ├── 4df1c9846211f3a6293fa3d9eefb578a3a100be4.nq.gz
    ├── 4dfa7c4f17e280346daa141f6851ae8bdf80abd6.nq.gz
    ├── 4e562f4641371346c7da1d72db248aa45afe3f54.nq.gz
    ├── 4ea986aba736273029fc8394b7d1ffc727390acb.nq.gz
    ├── 4f5bc496d337e635885beebb5fc44ad43c93ebaf.nq.gz
    ├── 4f85d91c18f32746b7d707ef61e65bc4246b3646.nq.gz
    ├── 4fd63de9f6646215ad75fd3b84818c6e8101547e.nq.gz
    ├── 4fdd86e5235c8a6ed6f1faead177251519ea690f.nq.gz
    ├── 503a122b5161930380a5443f7161ada17260ab39.nq.gz
    ├── 519f3ed71b5522afca137ad8af1d087c92610569.nq.gz
    ├── 52353e783cb99873ed3bd1be97641b50739a7d18.nq.gz
    ├── 5248e96d2068809abe36aa2f2cd1d7eac693c23f.nq.gz
    ├── 5270af1260e5cce4acad95f885e4055a264d3f85.nq.gz
    ├── 540b486e48d5896423afe8701bbdbb403bf6f834.nq.gz
    ├── 54887185a484610c3e1212e32156f379cf90aeef.nq.gz
    ├── 55439bf4ae19b12cfc5bdaa6a6481a561b4a1d9c.nq.gz
    ├── 564d9d03d94d060b2a2a1a2e242b58dc78bc2191.nq.gz
    ├── 5741cf3d9f575c9e117a1359bf2a4bf8626640ef.nq.gz
    ├── 5896ba0791126fb29eb46c06b2a14989881a7e9c.nq.gz
    ├── 58fd430d372b07d2ef4b49985761e465826c9af5.nq.gz
    ├── 5964dd8c18dd1cf094c68161240df19ad696482b.nq.gz
    ├── 59f4e044a6c708e59e93a4f800436ba978e6b650.nq.gz
    ├── 5a774db24683f0f9fe67d39c3895fccc84d46111.nq.gz
    ├── 5ae15783302643fef2dc98415c2a8193921d19f5.nq.gz
    ├── 5bb499a5faeb734fab7414d25b9c16ae070b00c9.nq.gz
    ├── 5bf1f37c867be41c3a53ce84230e1877d5078125.nq.gz
    ├── 5c00c6abd23d0638428279ca1f42acdf6368072e.nq.gz
    ├── 5c0b6537d3ac781a291bd1f75eb5e55e9cb88b4b.nq.gz
    ├── 5fa09dd65702fca4695371c9f30ea7995bb87a7e.nq.gz
    ├── 5fd7b6aeb5939cb21c6476d638dcd2f1ee56b2a9.nq.gz
    ├── 5ffdfbe578386d60499869eed619893b8db50b60.nq.gz
    ├── 6017e98aae65ca9bfd9871b24116ed2f6d7b767d.nq.gz
    ├── 60da31e88e441275130ceef4974010bb7327fc65.nq.gz
    ├── 61446e74d26d69720ecaf852860ee06180bec3bf.nq.gz
    ├── 6158e2bc13fcbc52419ffd0296b2a236f5160e1b.nq.gz
    ├── 62a8894c0f330db68c5a3d70a5f09cb16d13692c.nq.gz
    ├── 63a90eec4edb01727103834ae72e2ff6d5f3a850.nq.gz
    ├── 6452ccb168a6d67da5248ac8d6028c46c092640f.nq.gz
    ├── 6496da91ee6eee318958fc68391cae7a1c34e6a7.nq.gz
    ├── 656e919fb860af91be86e8de85bafa8ecad71cb1.nq.gz
    ├── 65e4341fcddc3a0cd2145c5f7cdf2aed2f6e872a.nq.gz
    ├── 66568032a9186ef669933f67401fcec9454d58d1.nq.gz
    ├── 6760fde544920d5c9da3d5e77d7a2adaac44a8ac.nq.gz
    ├── 6881182b7b86c69d4b29da004b18d8628e7d7c80.nq.gz
    ├── 69bc86f48c8b3939ddca4567c4d8b2b263914ad5.nq.gz
    ├── 69bf7ad04e63d1b74f9f9f117b114e97b35950a7.nq.gz
    ├── 6a54d8938ff7b5884c8c3dabd1525e7ab6446557.nq.gz
    ├── 6a96d65915f51248f0a5874a97a7c69b7bb9b23a.nq.gz
    ├── 6ae9145252d7ac88634249317c7ea7b1e738ce1d.nq.gz
    ├── 6af46c971f50c14aa953a2861164470c4890cd23.nq.gz
    ├── 6b6c93ab2651935d1ac1e64b55024f35ac418ee7.nq.gz
    ├── 6b9d864e4b9bb553f0f79d54f254b7c992e4ac3b.nq.gz
    ├── 6c2ae38b1496e8741651b13812af026f7dd1d914.nq.gz
    ├── 6c3dd468b9fcdd8c19850912d91d3e25e5866c11.nq.gz
    └── 6d05c6596e9032916b8b09cbdd25aa020933c1ee.nq.gz

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

[python-poetry/poetry](https://github.com/python-poetry/poetry)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
