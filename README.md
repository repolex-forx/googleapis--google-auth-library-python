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
│   │   └── 2ea24b03436765fa3cf279ce148482ff6332136b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ea24b03436765fa3cf279ce148482ff6332136b
│           └── chunk-001.nq.gz
└── blob
    ├── 0080152373d5d919b6d310d21d1be23bcf81a920.nq.gz
    ├── 022eaafda85c1923906343d6d83040e42489d34b.nq.gz
    ├── 027cb09c15a9ec92dea4a75c503d6b748a37d924.nq.gz
    ├── 0393b98b13f37b9fc9e12a76d3a192dc31f94437.nq.gz
    ├── 04ab45c19c9b9292805cb49a37a9dd4eb0c41528.nq.gz
    ├── 0574e0a3ab66ac718a378cc2cd2c7b7e9fe6d176.nq.gz
    ├── 05874eda7fb1019dc0d7ca80a688656cfe57c0e6.nq.gz
    ├── 0608223d8c20c97f56a65ea1140140bdaf070384.nq.gz
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
    ├── 18088284392e52c644ee1187b7c8baa3484b7eb1.nq.gz
    ├── 184329fed7e921cff1003a91ddd4c9819618a065.nq.gz
    ├── 18d1d8cdf2f6f385805a77829b21f833a0a92712.nq.gz
    ├── 1982f3d8e53dbc1a2b61cd78dd3e0f1f292c7154.nq.gz
    ├── 1a3e9ff52c66487d945d69e58d9004e009b991b8.nq.gz
    ├── 1b3fba7b0c806a80dd6254bc5af18897fadee19f.nq.gz
    ├── 1baa4995aff5d3a669e0937e6cc4b700bbce7391.nq.gz
    ├── 1bab21a69e40673704da51830f8a838de61989a3.nq.gz
    ├── 1c913377f2d806ce569b4e7bc9f177832dad343a.nq.gz
    ├── 1d5a4618cb61b1f410a9c9294e99a916445d180c.nq.gz
    ├── 1dd75d6e19eac712b553d9f103c8511519ccc990.nq.gz
    ├── 1e0eaf11db9f5467727f9fd6ed5a38a739c77223.nq.gz
    ├── 202276323c668e29ae9d9f00d104b6dfc49cf26b.nq.gz
    ├── 2142b6f50e8fe51b5f899e7eddda97cc8810b17c.nq.gz
    ├── 24e984f3d33636259b60819fd372207267fd6ce4.nq.gz
    ├── 250387d9d59c2448c6eb8b9684961289875a1eb7.nq.gz
    ├── 25be29326bc22020fc304628602541cc5aedde96.nq.gz
    ├── 25d2ea1deccc9034fcdfc7dc7dff2548381a8eb7.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2649c6c6eeed12ca70ce2af333a5e217d9cae4cb.nq.gz
    ├── 26a4c825a7b3521e1e384f9a38fc95ed443b0dfe.nq.gz
    ├── 26ed0e4edafe55b65ebee48e0ba261cc97ad7f1d.nq.gz
    ├── 2802c3e31e5cecb28269625e95d802a59ac45665.nq.gz
    ├── 28e47025fc4dfa7a1c99b3ebcc1ff8c9b29fb4d3.nq.gz
    ├── 29e06923f0f028b54d1b571dc218cdd92f751bd8.nq.gz
    ├── 2a8a7a5885d20de872d2ba707dbaf60a423bf530.nq.gz
    ├── 2c1a0414d39a9da28eed64c0ad998d8ab82782ff.nq.gz
    ├── 2c34091c588cf8dde2a8aec9655cc06ca6c7995d.nq.gz
    ├── 2ca735d9b34e74440521d954ecd24fae9c7a0587.nq.gz
    ├── 2d77e10c1fd16bd78d247bcc245ea3ef2ea8ce47.nq.gz
    ├── 2fb28446e3ab4c1acaf1ce9b6e8c2ce46d3d7963.nq.gz
    ├── 304f0606ed8549e9e667f20be2b8196a7af03e37.nq.gz
    ├── 3060d32b6c88156fad43e936498e609d168864ff.nq.gz
    ├── 31b11a6a2d7e666a6e5ce444a0cc3a7398e42aaa.nq.gz
    ├── 331708cba62c41e0cddc2e7c96f377200ee4bc1f.nq.gz
    ├── 3595fb43f5c0b44f434d4b803476faa881eb063b.nq.gz
    ├── 35b88c99ecd4621bf5891d341f0ff0461e0cb3cd.nq.gz
    ├── 380c2f0a3be39a0c98351ec638494692d46bdd20.nq.gz
    ├── 3a1abc5b85c91e4ff754fa79156fcb67217182e3.nq.gz
    ├── 3bc6a5a6762a5064b4c5767ad0ab049819515b2d.nq.gz
    ├── 3c8dcf85b418180aa4dc5c546f3f0fd736f9f286.nq.gz
    ├── 3cdf3cf3bdb73cdaa17a0098a4333969ce0d6925.nq.gz
    ├── 3d0319dd337c378cd3cb59b7aa54741fb234257d.nq.gz
    ├── 3ecb29a60516b14c7c31da9664529f0b44cb79ae.nq.gz
    ├── 3ff7281a672d8dd69926c7cb4f283ef262297d4e.nq.gz
    ├── 4192b8cf8d3cd5784165a942428fb457f4d39607.nq.gz
    ├── 43539900f7fc64a724ea52805c48e7b8e9ee78a7.nq.gz
    ├── 44bc6719f97a5c4adba4347931ddd9c7c51b2f90.nq.gz
    ├── 44fc4e5775142c7008f17eceed7041aa59d5deeb.nq.gz
    ├── 4575763500b216d7979e6b10e5f9c79116d28a7d.nq.gz
    ├── 4621dd8df7d7810f6ab4ee39d1cac59f4a9b1cec.nq.gz
    ├── 46b2a08ea6d1728faf0f111691adde837a0239a7.nq.gz
    ├── 4715a590a1eed05d665d0ac7032eeea5f5a6e409.nq.gz
    ├── 4787acee5764455d1bfb7ee7105f24369549a0fd.nq.gz
    ├── 4874a3728e2b9c8473989677d3bc6781b478dfd4.nq.gz
    ├── 48d9902236dd99afb4793ef213ef7b8e1c13fdb6.nq.gz
    ├── 48f79699706e1ea990af459b1f33cea134830589.nq.gz
    ├── 49d99dfe66f0464ae5438e0cf58ae0e08d9d416b.nq.gz
    ├── 49f6457f4af13fb6319d3bb5ccc4c3d8e0c0d463.nq.gz
    ├── 4b2fb39ffbda63f2ae4f86057baf0fb58de7b48e.nq.gz
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
    ├── 5ad9596cf85ccdbec19e079c8a8e683a91aefa16.nq.gz
    ├── 5b039eac825c6e036078bf46c99b7b727f7c69b8.nq.gz
    ├── 5be9713ef7a0c755aa463f4c90e01e916b1aa249.nq.gz
    ├── 5c950b514f3fdca9391ad1ca95157de2a21a8a71.nq.gz
    ├── 5d0f557e3c8435a1823f4e00362b0c8ce0e4033d.nq.gz
    ├── 5eba7b60e18331a0e396c2828465a90ba86bddae.nq.gz
    ├── 5f0c23c2db24d5b9ec0627882af9dec49ce5c57a.nq.gz
    ├── 60d6f83c4d9f2681ae111211918c543d853b5113.nq.gz
    ├── 62108f6be0ab5efcdd9c42337e6b2c9d1e06813e.nq.gz
    ├── 6365857f33c6c4c98eb292cf87dcfa000b301fb9.nq.gz
    ├── 642d15927d0ff553dc2d20f1984ce77c7f2ae32f.nq.gz
    ├── 64b161d42268f95702b7ba23f6c8f9a2402b0c1b.nq.gz
    ├── 64d5ce34b9a352984541ed7f78b42b94f4d01e26.nq.gz
    ├── 6525dd03e1bdb18f2473f57693754a27c0d32722.nq.gz
    ├── 666a6ca1fd9189817c58564ffd144f619734678e.nq.gz
    ├── 667bb0978c097e1777ca2b83efa1501d93f75567.nq.gz
    ├── 6689e8943b2a8d845f662ea9d0a99201bdb3931e.nq.gz
    ├── 67d04174db427187d6a5bb7b3edab545446765ba.nq.gz
    ├── 680fce628e2cc68d6b761ebd16d94fd09cea412b.nq.gz
    ├── 683139aa533e9c46407a60472eb86887b3242697.nq.gz
    ├── 6895d1e7bfaf110cbadaf8ed49a73104deba8a53.nq.gz
    ├── 68b74f11bc1d60217422f5e3c50241e9d83ca124.nq.gz
    ├── 6a01b1bacecbf35b253b80d0054ed88c09952194.nq.gz
    ├── 6b40b6682869c27fa92ad73c8056e0cc493a638e.nq.gz
    ├── 6f542498fc5ccec1434604842c9299faca4ddaef.nq.gz
    ├── 6f7aa2691330ddf2dbbfade097e37e1201a9bb79.nq.gz
    ├── 7060b03c82e324d084939125417cf36c26855794.nq.gz
    ├── 71cd1e597e385db30b49639bbcdf0a74e5c5efb8.nq.gz
    ├── 7410cfc2e05eaa84ab490ab4c5ca6c80b4d61891.nq.gz
    ├── 750631aa5fc89ee28bb23880ff47dc882dc5e12d.nq.gz
    ├── 760758d851b05d880db9e43b91910b177701e1aa.nq.gz
    ├── 774ca14843823ec0ade14c3bb8ce1ce85209a098.nq.gz
    ├── 782d95f203c60b66732c6445579f4d133b8d9160.nq.gz
    ├── 788f52263bce047573fb64115cf6a3fa01b0c227.nq.gz
    ├── 7933d820149a3ddbe8764fd15f4c2403f405b427.nq.gz
    ├── 79668f998cd5fcc3b142b0ddf83d317fc40d69d6.nq.gz
    ├── 7af6ca3f93143699d5809c9612c47f68aa3200ba.nq.gz
    ├── 7d82758c38b6942d572260e976b0a419d7478a2a.nq.gz
    ├── 7e1206fc1b28a0f9c527681995462302cd7ec0a6.nq.gz
    ├── 7e7f03bdca53a0dc1dcb29a9dfd623c8265de30c.nq.gz
    ├── 7e836861e4a732fc963254f064018711249f044b.nq.gz
    ├── 7ebd14758e5500d434ecfb8b46783b5a85213b26.nq.gz
    ├── 7ef75cc4b2a1abccd399cb5d672ea00fa6aed450.nq.gz
    ├── 7f5406b626a65a51d6763cbf221b20bd6e0fc405.nq.gz
    ├── 7f548ec0e9b353ba43f7d2c0871e0eef090f646a.nq.gz
    ├── 7ff2ff9437d8082aaae13d7352740a887ed5d349.nq.gz
    ├── 8032b26ad2edc9a6fee339a3f9556bc4fc52c4ba.nq.gz
    ├── 819248cb5fab9223c12de245f2fb4efc75535de6.nq.gz
    ├── 81f431a99733b5466a977ef4ca2d7c0d3e7feac2.nq.gz
    ├── 829dc97ff33cf7768b2951bafb1cc4c034d6ddbd.nq.gz
    ├── 8302344b1a7c9cd884284ae8c788cb517f421c9d.nq.gz
    ├── 83eace873ccba2c2c98711d77bac1ec1c5a0e937.nq.gz
    ├── 8472ed731acae6b06c9db211a1ade1fe266b82bf.nq.gz
    ├── 8483bd7ea3beb5bd8fa6fd58e7f29970be16e4c7.nq.gz
    ├── 85b3c4f99be379734d8d2aab328dc00d83ae7475.nq.gz
    ├── 879eff7e659084587569efe630ba53e1b4e8e731.nq.gz
    ├── 89853448f9fc71f47198d35607926361271d0dd1.nq.gz
    ├── 89db9617c467ebd1128d6704e296362a6c4dc328.nq.gz
    ├── 8a5f13a6daf4ebdd54088f55db36b619eca0fae2.nq.gz
    ├── 8ab2ff0293f65c7c3854c77443d00f0816451796.nq.gz
    ├── 8ab60939071236254d0bfacbc7875b0472015640.nq.gz
    ├── 8aba0d8516f19302e55ec6de57f22d6af5216b9e.nq.gz
    ├── 8b2c192dd08d537736a9b7d2abb07eba25e58245.nq.gz
    ├── 8b58ae9c01ae3b07eeba325544a99071e0713f31.nq.gz
    ├── 8d8fcd3f1af942f32d0709448e3f72098ca31f3f.nq.gz
    ├── 8e045cc3fc00d3907662250814ae4487946f3526.nq.gz
    ├── 8f43917d92fe947f29fccb20f0cf8aee25a87fd8.nq.gz
    ├── 908db3145c56a798756b7e04bee2222d4b91071e.nq.gz
    ├── 912035b0bf9d6ec5c1fd2ac0f4c543d7332a2f1d.nq.gz
    ├── 916211ac6786df59c0f82b4135a678daf2deefcb.nq.gz
    ├── 9279158d45c68a75b69ce9a0407ffda7deff5e1b.nq.gz
    ├── 939e5341e74dc2371c8b47f0e27b50581bed5f63.nq.gz
    ├── 9507e837fbff2332ca7b7f336370f04a711a374d.nq.gz
    ├── 9735762c4414964f3ccd22dce0b8669c7a76cfec.nq.gz
    ├── 976184f8c2490d10b550def4a7a5d7cc1999ba8f.nq.gz
    ├── 9780b8e2a1d2d60fb0d751673bbb5ba07fdb28f5.nq.gz
    ├── 995869032125fb2e0d6830a2898ea07e0c061499.nq.gz
    ├── 9b7adf8bc30df065e847eeb1caf0cab98ded64c0.nq.gz
    ├── 9ba7b1426b1ec006012c190fedbc2700201794d9.nq.gz
    ├── 9c3966bbad73f9aff0327d69c8ccb0489bbce6ee.nq.gz
    ├── 9d9eca4e28521a65ea8906fe167ec29548704efd.nq.gz
    ├── 9da0f37fedf9e884edd6e25c3d29ff767ce08bfe.nq.gz
    ├── 9e76f4d3558140bbe599745d179fde7cafcaee0f.nq.gz
    ├── 9fc2c8cf6cb532170ec4deacfb08a0a2fe6b9693.nq.gz
    └── 9fd177038eddf0fde8e77c9cdfb10a3e8e706632.nq.gz

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

[googleapis/google-auth-library-python](https://github.com/googleapis/google-auth-library-python)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
