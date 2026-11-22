# Repolex Knowledge Graph of googleapis/google-auth-library-python

RDF knowledge graph data for [googleapis/google-auth-library-python](https://github.com/googleapis/google-auth-library-python), parsed by [repolex](https://repolex.ai).

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
rlex download googleapis/google-auth-library-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 2ea24b03436765fa3cf279ce148482ff6332136b
│   │   │   └── chunk-001.nq.gz
│   │   └── b662fc45829d5892bfc7ee4fdbf9c91e1940d873
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b662fc45829d5892bfc7ee4fdbf9c91e1940d873.nq.gz
│   └── repolex
│       ├── 2ea24b03436765fa3cf279ce148482ff6332136b
│       │   └── chunk-001.nq.gz
│       └── b662fc45829d5892bfc7ee4fdbf9c91e1940d873
│           └── chunk-001.nq.gz
└── blob
    ├── 0080152373d5d919b6d310d21d1be23bcf81a920.nq.gz
    ├── 01c2fa085aadfb94d3aec029972b75397806764c.nq.gz
    ├── 022eaafda85c1923906343d6d83040e42489d34b.nq.gz
    ├── 027cb09c15a9ec92dea4a75c503d6b748a37d924.nq.gz
    ├── 0393b98b13f37b9fc9e12a76d3a192dc31f94437.nq.gz
    ├── 04ab45c19c9b9292805cb49a37a9dd4eb0c41528.nq.gz
    ├── 0574e0a3ab66ac718a378cc2cd2c7b7e9fe6d176.nq.gz
    ├── 05874eda7fb1019dc0d7ca80a688656cfe57c0e6.nq.gz
    ├── 0608223d8c20c97f56a65ea1140140bdaf070384.nq.gz
    ├── 0639be1026750bde6636244ec37bfec5bf5720c2.nq.gz
    ├── 0681eaa277a271632406d5fd04af762c26c2db88.nq.gz
    ├── 06cc2676bee70b45bca824b025bf3a70074895d6.nq.gz
    ├── 0729ffd9eb415ed3841747120ae215bde89eba85.nq.gz
    ├── 0955a15bf2b136122f504fa3427e722a6e5e95b1.nq.gz
    ├── 09aeeca1c1bc7053e8737839178ad30e2f6747e4.nq.gz
    ├── 0a4a2af4613f6b8b124c6d5aa328782bcb4fa2b3.nq.gz
    ├── 0a5d8ab1aaf959491f80115c6cfc680806124400.nq.gz
    ├── 0bc44c13a28b4c5590a09fdc5aa0e685f5eb8423.nq.gz
    ├── 0d64f0e0ad2b7dcb54d570c510046f31fac9939a.nq.gz
    ├── 0e545392ccff2a8df3c9baaa47e7858b95688395.nq.gz
    ├── 1034ed6c1d3afd282bca9793ea01ee3ac201d5bf.nq.gz
    ├── 10910e3575588e285f576d2f21c233d37f752c5b.nq.gz
    ├── 10b7bf37189b2c3b978a60adadd2e8e1e54efbb2.nq.gz
    ├── 11a9a8d986058b24f3d3a527d2ab20eb0f259975.nq.gz
    ├── 11b50e23cb7878020ff6ecd893b1cf45757f8396.nq.gz
    ├── 11fdaa42f02a2d53ff21e5abf1ecdf6e531c6256.nq.gz
    ├── 123c3e1223241b3933a43562c1d3ec62828e9b31.nq.gz
    ├── 12f83dcfaca07eb27dfa521edcba4589aae8bb57.nq.gz
    ├── 12ff96291b891babcff10728f523d2235560fb72.nq.gz
    ├── 1323de9096f9fdb8d7ee994b09e0631ea29cdb1a.nq.gz
    ├── 166a3be50914885deff2f3295a862808982b5161.nq.gz
    ├── 16caa659ee6122cf8337bc82fb3fcb4bfaa12f7e.nq.gz
    ├── 172164e9fa1774b9f92b9f3fe5e4b27fd1ecf4ce.nq.gz
    ├── 176992f7714f4f93fc1e5e4c840286d142aa6d3f.nq.gz
    ├── 18088284392e52c644ee1187b7c8baa3484b7eb1.nq.gz
    ├── 184329fed7e921cff1003a91ddd4c9819618a065.nq.gz
    ├── 18d1d8cdf2f6f385805a77829b21f833a0a92712.nq.gz
    ├── 1982f3d8e53dbc1a2b61cd78dd3e0f1f292c7154.nq.gz
    ├── 1a3e9ff52c66487d945d69e58d9004e009b991b8.nq.gz
    ├── 1b3fba7b0c806a80dd6254bc5af18897fadee19f.nq.gz
    ├── 1baa4995aff5d3a669e0937e6cc4b700bbce7391.nq.gz
    ├── 1bab21a69e40673704da51830f8a838de61989a3.nq.gz
    ├── 1c825aaa64ba041f5c43ebad723519a508345e4f.nq.gz
    ├── 1c913377f2d806ce569b4e7bc9f177832dad343a.nq.gz
    ├── 1d5a4618cb61b1f410a9c9294e99a916445d180c.nq.gz
    ├── 1dd75d6e19eac712b553d9f103c8511519ccc990.nq.gz
    ├── 1e0eaf11db9f5467727f9fd6ed5a38a739c77223.nq.gz
    ├── 1e4cdffec188b74eeaa729e54ff4f2bdd806a5d6.nq.gz
    ├── 1e6557272122c08590c01f80e3180ecfa66db951.nq.gz
    ├── 1fb880096916b74676d7062e9861d986c1efdef7.nq.gz
    ├── 202276323c668e29ae9d9f00d104b6dfc49cf26b.nq.gz
    ├── 204375f8d3b0dfcbaacbf9dd5b4ffbd27774f04d.nq.gz
    ├── 2142b6f50e8fe51b5f899e7eddda97cc8810b17c.nq.gz
    ├── 22d4f585ff43d57e99334a33200aeb0c3cd91655.nq.gz
    ├── 2465b6a9703a1ba3b9e8e4caff68d872911c1999.nq.gz
    ├── 24e984f3d33636259b60819fd372207267fd6ce4.nq.gz
    ├── 250387d9d59c2448c6eb8b9684961289875a1eb7.nq.gz
    ├── 25be29326bc22020fc304628602541cc5aedde96.nq.gz
    ├── 25d2ea1deccc9034fcdfc7dc7dff2548381a8eb7.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2649c6c6eeed12ca70ce2af333a5e217d9cae4cb.nq.gz
    ├── 26a4c825a7b3521e1e384f9a38fc95ed443b0dfe.nq.gz
    ├── 26ed0e4edafe55b65ebee48e0ba261cc97ad7f1d.nq.gz
    ├── 274bafc5fa76a5c6f579902ccb33baa584e18fd4.nq.gz
    ├── 2802c3e31e5cecb28269625e95d802a59ac45665.nq.gz
    ├── 28e47025fc4dfa7a1c99b3ebcc1ff8c9b29fb4d3.nq.gz
    ├── 29e06923f0f028b54d1b571dc218cdd92f751bd8.nq.gz
    ├── 2a8a7a5885d20de872d2ba707dbaf60a423bf530.nq.gz
    ├── 2aecc0b7edabb4958881b8a9a2355157acd25752.nq.gz
    ├── 2c1a0414d39a9da28eed64c0ad998d8ab82782ff.nq.gz
    ├── 2c34091c588cf8dde2a8aec9655cc06ca6c7995d.nq.gz
    ├── 2ca735d9b34e74440521d954ecd24fae9c7a0587.nq.gz
    ├── 2d77e10c1fd16bd78d247bcc245ea3ef2ea8ce47.nq.gz
    ├── 2fb28446e3ab4c1acaf1ce9b6e8c2ce46d3d7963.nq.gz
    ├── 2fbfb980d5884a6d5b02c4776149da8ffb26528e.nq.gz
    ├── 304f0606ed8549e9e667f20be2b8196a7af03e37.nq.gz
    ├── 3060d32b6c88156fad43e936498e609d168864ff.nq.gz
    ├── 31b11a6a2d7e666a6e5ce444a0cc3a7398e42aaa.nq.gz
    ├── 322c57b62561af61ea91641fa3d0698af39e4e9a.nq.gz
    ├── 331708cba62c41e0cddc2e7c96f377200ee4bc1f.nq.gz
    ├── 358083edad05d25a0a6ff41075ff78e19b06cd3d.nq.gz
    ├── 3595fb43f5c0b44f434d4b803476faa881eb063b.nq.gz
    ├── 35b6c4495436c3ffa0d696f3c015550f3586943c.nq.gz
    ├── 35b88c99ecd4621bf5891d341f0ff0461e0cb3cd.nq.gz
    ├── 35fa529231dc6df2cd4b4f92ee34fdfe1ca3e470.nq.gz
    ├── 380c2f0a3be39a0c98351ec638494692d46bdd20.nq.gz
    ├── 3975a3d2a85bbb97282cdfc151267c4a4be4c6cd.nq.gz
    ├── 3a1abc5b85c91e4ff754fa79156fcb67217182e3.nq.gz
    ├── 3a33c2c02154eadd29807bc2e4d578e91104bb8c.nq.gz
    ├── 3b28bb5184ddb261aedaa7f6419e4932065e572d.nq.gz
    ├── 3bc6a5a6762a5064b4c5767ad0ab049819515b2d.nq.gz
    ├── 3c8dcf85b418180aa4dc5c546f3f0fd736f9f286.nq.gz
    ├── 3cdf3cf3bdb73cdaa17a0098a4333969ce0d6925.nq.gz
    ├── 3d0319dd337c378cd3cb59b7aa54741fb234257d.nq.gz
    ├── 3ecb29a60516b14c7c31da9664529f0b44cb79ae.nq.gz
    ├── 3ff7281a672d8dd69926c7cb4f283ef262297d4e.nq.gz
    ├── 40ca927178564c8f0df3290f5109d769ef605902.nq.gz
    ├── 4192b8cf8d3cd5784165a942428fb457f4d39607.nq.gz
    ├── 43539900f7fc64a724ea52805c48e7b8e9ee78a7.nq.gz
    ├── 44bc6719f97a5c4adba4347931ddd9c7c51b2f90.nq.gz
    ├── 44fc4e5775142c7008f17eceed7041aa59d5deeb.nq.gz
    ├── 4575763500b216d7979e6b10e5f9c79116d28a7d.nq.gz
    ├── 4621dd8df7d7810f6ab4ee39d1cac59f4a9b1cec.nq.gz
    ├── 46b2a08ea6d1728faf0f111691adde837a0239a7.nq.gz
    ├── 4715a590a1eed05d665d0ac7032eeea5f5a6e409.nq.gz
    ├── 4787acee5764455d1bfb7ee7105f24369549a0fd.nq.gz
    ├── 47890ce4b46c646d80eeaf9f4b0b30f13ea57d6b.nq.gz
    ├── 4874a3728e2b9c8473989677d3bc6781b478dfd4.nq.gz
    ├── 48d9902236dd99afb4793ef213ef7b8e1c13fdb6.nq.gz
    ├── 48f79699706e1ea990af459b1f33cea134830589.nq.gz
    ├── 4930a70a7591295458472b96a99b49545d87d077.nq.gz
    ├── 498b75b2233c80e661364c199341487d67ca3d5c.nq.gz
    ├── 49d99dfe66f0464ae5438e0cf58ae0e08d9d416b.nq.gz
    ├── 49f6457f4af13fb6319d3bb5ccc4c3d8e0c0d463.nq.gz
    ├── 4a69d4c61f9dfd5c7d50d573a430975a53642d5e.nq.gz
    ├── 4b2fb39ffbda63f2ae4f86057baf0fb58de7b48e.nq.gz
    ├── 4bf21b4224eaf3920ee71ee585bd04fb3169c322.nq.gz
    ├── 4c5988469494fd8700d7060566bd3a77f83ea8c0.nq.gz
    ├── 4d12abd86c6708582ac718fc67b8ba0d82b20678.nq.gz
    ├── 4fdf7f2769ca8d66f94e27d384c72018c5018e71.nq.gz
    ├── 501db63289586537acb9069b8457b5e7347ec60a.nq.gz
    ├── 50465d1b766c3f8a8b81b28a622ec51d48002fc9.nq.gz
    ├── 50b2a83e4356a975c4e5caab72585fb654c8f8cd.nq.gz
    ├── 50fec964973212c5b45fe3dd407b44f8b1f707ad.nq.gz
    ├── 51d85daf2285dd104d9f7aee2a8be43478a4fd75.nq.gz
    ├── 51e4f0611c886c315b2aeb32d757d99958b5efba.nq.gz
    ├── 51f2a03fa4a7f8a6ecd7c3e577fcb7215a8b2725.nq.gz
    ├── 53a8ff88aa28c2636e340cf3d8c8c5c4523497a7.nq.gz
    ├── 53e365bc4e7948b5dd72afacaadff7cb4c515a44.nq.gz
    ├── 543a693a98bfe331052701fa094547705cb62926.nq.gz
    ├── 548cd726d0bcf2584372f69cb6f675aa4dda6b49.nq.gz
    ├── 54fcc60fd039da8f67536ebfcf22b2ebc9877093.nq.gz
    ├── 5511f581f658552ded82ed544ab507a99f847123.nq.gz
    ├── 553f35775facc7c6ca621542a8ca110a40d784ab.nq.gz
    ├── 55cb918dbc01205399db1f0e358b48c784c6b475.nq.gz
    ├── 55fd264632c4641da3f057462c7acffb57bde188.nq.gz
    ├── 56c2e629a1918988653bd15133888ac7525e01f9.nq.gz
    ├── 57443540ad3983f9786921581486b6ed9c352cd2.nq.gz
    ├── 5996e993596c54a94c28e1d7da33a01212dc7fa0.nq.gz
    ├── 59a2f9be4f43b1db5685f49bea265361c72cb532.nq.gz
    ├── 5a6318482998663f265e099b9cb448542d24609f.nq.gz
    ├── 5a9a89fcaac2008e193062cecc256c3603cd3f9e.nq.gz
    ├── 5aa979c859e1aa6f92e1c295a0ea68ebf9da0ca2.nq.gz
    ├── 5ad9596cf85ccdbec19e079c8a8e683a91aefa16.nq.gz
    ├── 5b039eac825c6e036078bf46c99b7b727f7c69b8.nq.gz
    ├── 5b56b60b1e0bc06125bcc7fe49b2cce4616b8ee2.nq.gz
    ├── 5bb85c264e1b93305b400848468219a9ea493101.nq.gz
    ├── 5be9713ef7a0c755aa463f4c90e01e916b1aa249.nq.gz
    ├── 5c1b4e6600bcf83be9f34666485bbf8566fc9f2f.nq.gz
    ├── 5c950b514f3fdca9391ad1ca95157de2a21a8a71.nq.gz
    ├── 5d0f557e3c8435a1823f4e00362b0c8ce0e4033d.nq.gz
    ├── 5eba7b60e18331a0e396c2828465a90ba86bddae.nq.gz
    ├── 5f0c23c2db24d5b9ec0627882af9dec49ce5c57a.nq.gz
    ├── 5f0ef916b620ba80426bbe151a7a5f11c9f10c15.nq.gz
    ├── 60d6f83c4d9f2681ae111211918c543d853b5113.nq.gz
    ├── 62108f6be0ab5efcdd9c42337e6b2c9d1e06813e.nq.gz
    ├── 63075aba03eb9da83b01bba052267cc81db7f78f.nq.gz
    ├── 632abff25a488dfd6a3e5355b43457ad77f2c9a7.nq.gz
    ├── 6365857f33c6c4c98eb292cf87dcfa000b301fb9.nq.gz
    ├── 642d15927d0ff553dc2d20f1984ce77c7f2ae32f.nq.gz
    ├── 6468498bcb6d027ef02e2af4ad8d89106c525ea8.nq.gz
    ├── 64b161d42268f95702b7ba23f6c8f9a2402b0c1b.nq.gz
    ├── 64d5ce34b9a352984541ed7f78b42b94f4d01e26.nq.gz
    ├── 6525dd03e1bdb18f2473f57693754a27c0d32722.nq.gz
    ├── 666a6ca1fd9189817c58564ffd144f619734678e.nq.gz
    ├── 667bb0978c097e1777ca2b83efa1501d93f75567.nq.gz
    ├── 6689e8943b2a8d845f662ea9d0a99201bdb3931e.nq.gz
    ├── 67a19f952d242462c881b81ee4840270e05547ea.nq.gz
    ├── 67d04174db427187d6a5bb7b3edab545446765ba.nq.gz
    ├── 680fce628e2cc68d6b761ebd16d94fd09cea412b.nq.gz
    ├── 683139aa533e9c46407a60472eb86887b3242697.nq.gz
    ├── 6895d1e7bfaf110cbadaf8ed49a73104deba8a53.nq.gz
    ├── 68b74f11bc1d60217422f5e3c50241e9d83ca124.nq.gz
    ├── 6a01b1bacecbf35b253b80d0054ed88c09952194.nq.gz
    ├── 6b40b6682869c27fa92ad73c8056e0cc493a638e.nq.gz
    ├── 6ca89628f11c524d2583c935a2dfc6489d4d3afb.nq.gz
    ├── 6e158089f31d22eab0c6f5e17055c4f7dff3570f.nq.gz
    ├── 6f542498fc5ccec1434604842c9299faca4ddaef.nq.gz
    ├── 6f7aa2691330ddf2dbbfade097e37e1201a9bb79.nq.gz
    ├── 7060b03c82e324d084939125417cf36c26855794.nq.gz
    ├── 7083ee61436bc1da91f16c8ee5241c52a5bd04ad.nq.gz
    ├── 71856a6232bc666a07be17c9826bce8fa6164c6d.nq.gz
    ├── 719f7d9b6c39e251ec29d3fa9d110accb08d246f.nq.gz
    ├── 71bfaa39c9c8ffa38e13a2499bab6c9c817853fa.nq.gz
    ├── 71cd1e597e385db30b49639bbcdf0a74e5c5efb8.nq.gz
    ├── 7410cfc2e05eaa84ab490ab4c5ca6c80b4d61891.nq.gz
    ├── 742f863d0f97cd2b2b414e22e1364848c0ba1995.nq.gz
    ├── 750631aa5fc89ee28bb23880ff47dc882dc5e12d.nq.gz
    ├── 75e43687fc2f8b328217704c67a96a9eb507791a.nq.gz
    ├── 760758d851b05d880db9e43b91910b177701e1aa.nq.gz
    ├── 765bbd70581a2a74eaabee8b856a86ef102b1103.nq.gz
    ├── 768f8eac2a059bc263e5128ce885a66ba847a6f9.nq.gz
    ├── 774ca14843823ec0ade14c3bb8ce1ce85209a098.nq.gz
    ├── 782d95f203c60b66732c6445579f4d133b8d9160.nq.gz
    └── 7872a71872a8ec629d1e79ab5ef366e569776add.nq.gz

10 directories, 200 files
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

[googleapis/google-auth-library-python](https://github.com/googleapis/google-auth-library-python)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
