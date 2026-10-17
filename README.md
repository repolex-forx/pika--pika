# Repolex Knowledge Graph of pika/pika

RDF knowledge graph data for [pika/pika](https://github.com/pika/pika), parsed by [repolex](https://repolex.ai).

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
rlex download pika/pika
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e31246e2038fc8cd140d873b654999ef0bec09e1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e31246e2038fc8cd140d873b654999ef0bec09e1
│           └── chunk-001.nq.gz
└── blob
    ├── 00af9284166824243b034e619d08d5889ac7043f.nq.gz
    ├── 025f6582cde870774780423e6cbe4550f5c5b473.nq.gz
    ├── 040542d3fe3d7726b9427c46a67a169462a1c8c6.nq.gz
    ├── 04675565389c00a30d4c0a7dccd7ba2418d61c4c.nq.gz
    ├── 04ff9fd9b8abf3fff190382af051b1c45a8fba01.nq.gz
    ├── 0508aa2d200a630f2b810a1a4408c86d7fceccc9.nq.gz
    ├── 05e5d35589b47876a91d069854629a29060a5492.nq.gz
    ├── 06ab774bd7bf8f41f39be8c256e312791212fab1.nq.gz
    ├── 06c3a3ae1f5b2707cfbb71df88bef34b0b4f36a7.nq.gz
    ├── 06f9e33bb85c35fe71af4eb644a67f63a7c20ac0.nq.gz
    ├── 075fffb0913ffa64fc9d10fb61b71bafcce4e88b.nq.gz
    ├── 07ec7b8ff5a7a6f5cda181b4618a7e7b3e65a84c.nq.gz
    ├── 09fb3c28104dfec90c62bc88a20451420fadccff.nq.gz
    ├── 0bc4cb4dd2e6332d47009ec265e984eca6b17693.nq.gz
    ├── 0c3f54b56d9edfa6f0d374a568edb286fcdf5bb4.nq.gz
    ├── 0eb6531eeb627385009cf0eaf3709813634f9249.nq.gz
    ├── 11ad29a0056235bb097cbd6d6eb9a576ef0b1bae.nq.gz
    ├── 11cf00600d4364c0283d36f368b3c46bf597ed63.nq.gz
    ├── 12291f8035457efa65d0db9ad06771e6950775aa.nq.gz
    ├── 124747515504515234c3e79dcba07aad9d4b61f1.nq.gz
    ├── 14612e44429490d5703c692c4d5d4e44c9680d62.nq.gz
    ├── 16033fe484117ef436d08bdebbcfed5f072497b0.nq.gz
    ├── 162ba73b57ae2158f99165f4c5d34e51cc1fa455.nq.gz
    ├── 16b0aa24c6b76f89fad6199437d1bd637b1a2766.nq.gz
    ├── 185151fd18c20128c4011e8fcd474457647532d4.nq.gz
    ├── 187a634b1bf1b95a13aa8272dd2e0918bd0b6576.nq.gz
    ├── 191ab2dea3c76c87bada6ec21ad68527d6ec53b5.nq.gz
    ├── 1be5d5c8b998a5059db412518ac06671abce7726.nq.gz
    ├── 1bf44e8b89794052e2c19409f86bb433727816c4.nq.gz
    ├── 1bffc6dc51adaa4b6bab5963c4607cb0db0566a7.nq.gz
    ├── 1c27fd1a3e44f4a803b3714cae0b50fed4ad735c.nq.gz
    ├── 1d62fbbf68ce35a625edf9c2a7184b06ce585455.nq.gz
    ├── 1f3ef998c29be66dd7b76b7782df56a8dd6ffe4b.nq.gz
    ├── 1f7a494e5dbe23c8ce7c66e543edf03e27b191d9.nq.gz
    ├── 203249bb8bb507a4b013eefd7b30211870e5b47e.nq.gz
    ├── 20c52a15a01f8355ae954240306cd64c204bcc70.nq.gz
    ├── 23619dbbe460782837a2f2db5dc5d2b6cbb397fb.nq.gz
    ├── 23944c4096c69a70d648a9f806d84f20d3119954.nq.gz
    ├── 24565b4b0e292200d40883b2e80491ef0c98ecd5.nq.gz
    ├── 253aade7586d7f06fe9806eb05125890f14affbc.nq.gz
    ├── 25630afb8365f10b5428a57ce08f61444c2fb05d.nq.gz
    ├── 27216b8eed028d721d49869eb6dbf8892bdff078.nq.gz
    ├── 27f98e1220a5383d3898a83ddbb95b9149566569.nq.gz
    ├── 286c1b8dd6955794fff8c939f777848bb61dc150.nq.gz
    ├── 287803eb51298a1b39dfb1adbf963b7fc180d3e6.nq.gz
    ├── 297b40c400e829d054b89fdf5cffe0c4b2b57988.nq.gz
    ├── 2b0fa0823cba873b53a13fdd8c395dd13e298c82.nq.gz
    ├── 2e713098abd89992cd1c39ebda822ca9f0b5575f.nq.gz
    ├── 30c99bc5516b7429c7feadf28cdcdea4f3f838b4.nq.gz
    ├── 312e92f00771947383fc5c6d8bcfb5db8b9a243a.nq.gz
    ├── 3271d53c1c592662aa54197907f6adcad4f9abcc.nq.gz
    ├── 34b7ccf5d1c2b3ad6063d9b7773dc8290bc0ba76.nq.gz
    ├── 351f057bd2dc4d3e8004b84a4c2a64f71a42462c.nq.gz
    ├── 354d12cb63a28291b31ff567cfa7d2df94591581.nq.gz
    ├── 35a98380831c4181a55c24bb28e8e61912963034.nq.gz
    ├── 35f27eeef928bd817cba3ddd822206dd2b75a648.nq.gz
    ├── 390721f2f23784ed077f645fe437af8ca645d7e8.nq.gz
    ├── 39a1e6beeb411887f2611cc2d8012f83c662ce63.nq.gz
    ├── 3aed84baf5272774bde103988b8b6a5e4bb584d1.nq.gz
    ├── 3bc91b418396d4ef752ef900d22a93fd077a3e26.nq.gz
    ├── 3d59b2ac11c0c6e4d8b60049be5b5260cdfc70b2.nq.gz
    ├── 3f15c93f3c425bc0d51c3b7ccc23de931320d49e.nq.gz
    ├── 3fcbdfe2f4fada221291c1609980292f3759cef4.nq.gz
    ├── 40c119502770f31ba22d4f9ddfd8a31e7dd214fc.nq.gz
    ├── 4223669a46e65029d8b6acec8fad2d5881a610f2.nq.gz
    ├── 445868014baef6972aafbdcd2c5be31fc7637d69.nq.gz
    ├── 453809e53bfd9bf1c177e9f13f373f91de96095a.nq.gz
    ├── 46a433fc97d7a105b029690ffdafdd421c9967ee.nq.gz
    ├── 46b1062166e666a6556925184511ec3046d0d150.nq.gz
    ├── 475dc287662a0487cb2a6a75701ec743a487cb9a.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4807966701e4c962d7cf14d21fea56ef982429dd.nq.gz
    ├── 4a5d1fef56183ddccc69dd9bfe5bb82f9581c0e9.nq.gz
    ├── 4aa7ab53b1639cfa15e45de30d372285cd99acb0.nq.gz
    ├── 4b106486c5ad20d2817696e68fe97d724083e17f.nq.gz
    ├── 4c72b1ade6adcf05b295a407b7a092a41379ccd0.nq.gz
    ├── 4cb605e9e6898384b2fbb777ffc08ca2fd567b18.nq.gz
    ├── 4cf7331ffb00668884c8f02ea2ab7a506d14f5f2.nq.gz
    ├── 4dbeb95d504f5bd6ebf9c16ec912971b035963dc.nq.gz
    ├── 4e774d376b7b4cdcbc0911907d1d74e9e1f6a99c.nq.gz
    ├── 4e9803a1951651072f31e49e124878b53d714a4b.nq.gz
    ├── 4efb7015b7305bfe95f3a5ba7793f6e05a9cc6be.nq.gz
    ├── 501a566a8615f5120c0ccad85ba5a33ae333a62b.nq.gz
    ├── 513ce1cab4ea1f2fc1d2c2f4aef8dee3ff137016.nq.gz
    ├── 5409661f4203867e8fff07c346ecf129d13114cc.nq.gz
    ├── 54a2e4e46bcce61540f2d80a3b461c02d0766ce2.nq.gz
    ├── 54a399cc453c28945fd8f858f6bb101af383de52.nq.gz
    ├── 59e9450ac6b01be8ffe208ac5acc7f10d92e4575.nq.gz
    ├── 5b4247ad0d13433e81a8c2398940dc04c56f32c9.nq.gz
    ├── 5bbd7bf7699ef7937144e6cb4bffea4bdf769cc2.nq.gz
    ├── 5d203553f5be155a82417ae9a3bd6e3ea92445a8.nq.gz
    ├── 5d69903815905c6b672a5b98e16784882c11c664.nq.gz
    ├── 5d950230e21d8897b54353cb559f2c3521793bb6.nq.gz
    ├── 5e403e3a0ebf07573fa85f39c3cb8125811ce7b6.nq.gz
    ├── 5f610463973e68b10682afc11a4c2df5550bf5a4.nq.gz
    ├── 5f968e7e2e5fa368a8c370b498217f1a2d08e837.nq.gz
    ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
    ├── 61e379f649a65fa3720527c7e9a4b293164002b0.nq.gz
    ├── 62219855b039c21352e2e089b46d31cae664530f.nq.gz
    ├── 6386b457e0f2d65e0e7d4ab1b996a94cc6b2f5ab.nq.gz
    ├── 663d04fb2a5909bf49b33d5b53f24569c861b25e.nq.gz
    ├── 66d549641ec7d089e9bdeb1a7819a8fa927e3d0d.nq.gz
    ├── 67293b9459e03ebc448c6853d2a74d4ed2422521.nq.gz
    ├── 6b86208f64535a0caf73070f56abf173abc90514.nq.gz
    ├── 6d598f9eae188b71836276dbdc896e8dc48ead29.nq.gz
    ├── 6d76538e3c6ebbb94b87c31c59149062169e215b.nq.gz
    ├── 6dcb2b4084665ad2a60a15ee8907f88698ec756d.nq.gz
    ├── 6dd12ed18c7809fca819b2311e86878b16054014.nq.gz
    ├── 72ecca6ad5a1819c1909a4a9eb01a80d0acc17a5.nq.gz
    ├── 759281f4577b058fb4a680e210b4141860eed14d.nq.gz
    ├── 79571f61a88100d3adc1bee3982eff5372d62fc6.nq.gz
    ├── 7ae8a79a30a72765fe519223a2dcd02630de3e07.nq.gz
    ├── 7b9881bc3259e687a8a17953422888f8724b840f.nq.gz
    ├── 7ea48cb325981f23417182fd266f0a4e9e2cb520.nq.gz
    ├── 7ee54f95a755b706dd5dd53fff1d7c9ee5bcef28.nq.gz
    ├── 7f6ba9c0a61e9070dfb07946f4f06b340324e3c4.nq.gz
    ├── 8188be87481505edd2f7d3548010eb4e3fb26f9e.nq.gz
    ├── 82a272a0deae27233d9b7ec426f0d88a62511b27.nq.gz
    ├── 8966c250484e89b0227b3612bebc2c39ae5efed3.nq.gz
    ├── 8a5e68b29d4a5e5a743faa089d1cf79a0d926a45.nq.gz
    ├── 8a95872b806b5cd40038d12b844a943926ddbf75.nq.gz
    ├── 8e6f0beed2ae6165b6039fa7d62feec031c2c1e6.nq.gz
    ├── 9095797d2ea77a50de674239464d0f166368a767.nq.gz
    ├── 9200af26a113c4faf74a8799701f56b9f4e3cd77.nq.gz
    ├── 9297c9e86d19fd0e8f1fb1d83594d8546c061d09.nq.gz
    ├── 931fecb215248682d572e918f88e54f993ce42da.nq.gz
    ├── 94845376af4582a1ddd7f34cddfc88859e2acf97.nq.gz
    ├── 94c6fd664c6c691f34eadf6547e481d1c01b973c.nq.gz
    ├── 961249f1c6f592cca7aacb99fa4c72b165b3c098.nq.gz
    ├── 97f2fe5cbdec7aa9b78a74bb97052f53b941dbd9.nq.gz
    ├── 98f56b44c42bc648a8db8271be5b7b26aafc3605.nq.gz
    ├── 98fe8fdb99b05602af20ecb6701d3e557a284350.nq.gz
    ├── 9a2409f3be3bd27ebca51d3935c65c69911508e7.nq.gz
    ├── 9b8eb49e132681509076537bf36a076e131342a7.nq.gz
    ├── 9bb2c5572313768f23fe37c713e5eb84aa9ada11.nq.gz
    ├── 9c638d8c6a7f47f714bd1e63ac4a50653d44cbbf.nq.gz
    ├── 9c848e469b20d2d3b960b6268611ca9be53e8f83.nq.gz
    ├── 9db0ef1e329b9bb689d34f07a017569eb23f6d08.nq.gz
    ├── 9e13fef3d11072baa8013614cac07c7e2c56e154.nq.gz
    ├── 9e517c47d8a43b7bea767fa87d0c8cda5889d7b9.nq.gz
    ├── 9e7f2385a33db9177867fb3d32e5b64d93323812.nq.gz
    ├── a053bce049924b5f76907df52ce3fd07252ea82f.nq.gz
    ├── a154e98ceac1c107ca45af831dbeb60e4c8fc88e.nq.gz
    ├── a29f827dc11283c8f5a3352a769e239f0baed3eb.nq.gz
    ├── a53a2863e0cdf2862ff8718f83b5d196267105d9.nq.gz
    ├── a540a53a1dcf62de90d5215c3aa260581bdd6fbb.nq.gz
    ├── a57b1dcb4831cfd59c422fd2b9aad0d735e2d2c0.nq.gz
    ├── a5b2ce97cb7089127aebfbabfcbfea8870b2aa67.nq.gz
    ├── aabc15803ce23308dc427e2003a9fbe759860463.nq.gz
    ├── ac2e8627a4ad0a5470138c729dd8d676035dbd91.nq.gz
    ├── ad92811ef86875303f243c1fbbb88e755aa17021.nq.gz
    ├── af57cb957680844a9e86348c88da89637a6b920b.nq.gz
    ├── af6e38b7b1b6ae47578e370df48e5b3ac83f3df0.nq.gz
    ├── b04312685a8c482e7237f67238ce50ac73afe1d9.nq.gz
    ├── b0784c9644f559dc5d0ebcc72084a9f1eec2d169.nq.gz
    ├── b3863d35657a7c43d12b0f2343764165b5785b1c.nq.gz
    ├── bb2d68e795f485142bcb37a2e27cdda1429e4be6.nq.gz
    ├── bbbd103cbde6edc1e3a097411314a9d8139f750a.nq.gz
    ├── bc734dde61cd88691c85a7073e5dab985213fdfd.nq.gz
    ├── bd5b5b73c7a28f78f6abba92c378a83cf6fd053a.nq.gz
    ├── bd63320870c38a149362bbd36966a343f25ae57c.nq.gz
    ├── be3c44a3a96c84b54246599c8db660394de555b7.nq.gz
    ├── beb12e38b275af21b61737888ea773e9b6046629.nq.gz
    ├── bed602c0b2f3123c34987bfe5077e5e5fc921d98.nq.gz
    ├── bfcc80e6fb553dd22d472739148fe3faea2f49b5.nq.gz
    ├── bfd9f5b155fd056824753a1510253387f72b5a3e.nq.gz
    ├── c1a7121c1bd6c9648bc686c95b1c7a94dd69cdd3.nq.gz
    ├── c37f99ab6d29454cb2de0ae2d13a5b4b3c0f90d3.nq.gz
    ├── c4d27b72efe046ff34949a130004cef3db1389d2.nq.gz
    ├── c581e756a0c228a180059502b26989f74509896e.nq.gz
    ├── c61a52e5332f48c284ae6fde2d10d8c8c46daf5f.nq.gz
    ├── c8da16ccedfe5310860d524ec7f10237858dc187.nq.gz
    ├── cbfb8f1e3bc9ce9b4663be9d84e63e475e6a9584.nq.gz
    ├── cf3022d10551026e9a26910a08d543acc1fe454d.nq.gz
    ├── d21cb78db4e90f274dc48a920518984df9eb5111.nq.gz
    ├── d245c8b42122f5864955658835e3cceb0d79fc41.nq.gz
    ├── d2f0d42e4e8d31539e7dd622036a719cd7170cfd.nq.gz
    ├── d5bbe4192a982312cc0d267f5a653175fd2a74a8.nq.gz
    ├── d6f91d9ac5e34c2fc6cde3d298dfe827e980ad59.nq.gz
    ├── d915bf4399a1555294eaec22d278ce591e658f3e.nq.gz
    ├── d9ca4108e263dec91ddf4d344105b5a32d4b8339.nq.gz
    ├── da714ca316bbb0b4c8a013c35b4871c3329eca3f.nq.gz
    ├── daa9b0097884403f31a45e9cf26e9d87fe8c7f37.nq.gz
    ├── dae624e870cb0f3d2bce87a6b59770fc4afbb0a5.nq.gz
    ├── db9a46879ced43238fabecabb56707f4aad91057.nq.gz
    ├── dc116a274aaa4b08d32be5fbceb0f3e0738c0fb4.nq.gz
    ├── dca5f25f9539e4937b2e4f727b3c7c80355ee857.nq.gz
    ├── dd2fbcb5566907c4a9dbc49eb67bbf1db3c6d2e4.nq.gz
    ├── dd379ee43f66d41041731a9c1ccd7563a8fb5343.nq.gz
    ├── de7760fad35c377eda951a6fca6da1f877537f60.nq.gz
    ├── de7ee6afb4310c4e19f965d5cc74822f01bf60df.nq.gz
    ├── dec995d0b9488178b9fd14d8821bd9831357a942.nq.gz
    ├── df05d5dbb5626b589751f9c27420f7d6ed31b2de.nq.gz
    ├── e143863ca09ba71e34e0d6bba7475b9cc37a8c76.nq.gz
    ├── e17a5a537925488e4b5a16b81c4af49122c3ecb7.nq.gz
    ├── e5bc5c85cbae3784b4ff742f000c8adcce846ffc.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    └── e6cd095f009dc1125ba893b876114fa05a66276c.nq.gz

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

[pika/pika](https://github.com/pika/pika)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
