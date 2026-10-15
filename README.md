# Repolex Knowledge Graph of django-guardian/django-guardian

RDF knowledge graph data for [django-guardian/django-guardian](https://github.com/django-guardian/django-guardian), parsed by [repolex](https://repolex.ai).

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
rlex download django-guardian/django-guardian
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02465ce96c187912208f75e28d3a0b17cb1aa81b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02465ce96c187912208f75e28d3a0b17cb1aa81b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00702656e744e19004dd500d07506f36ad074b06.nq.gz
│   ├── 0083138f70a26586b7a9fe4711b7edf0e3be95ed.nq.gz
│   ├── 04a7a5f63638e364be746ea7377624e360ba55f5.nq.gz
│   ├── 05559acb38d527ce28600e5a7a4f838887c0d3db.nq.gz
│   ├── 05d01cbb4eee44e9f355ced897547b32ed222d93.nq.gz
│   ├── 094eaf5e946113ff0fd6f9a94f113c45b7eba9e6.nq.gz
│   ├── 0d2964b13f61a7763dabfe44b2391ef48caec1fe.nq.gz
│   ├── 105219ece0f5d96a2fbbd722e519ba31c06c1b92.nq.gz
│   ├── 121e3456e9d03fa1eca88ad76a2e3caefc53ae36.nq.gz
│   ├── 134494ea81ba3a532d6b1f91e17ecbbfebb61032.nq.gz
│   ├── 15fca7cd934279d9629978ad352c4d2a35e9a99e.nq.gz
│   ├── 19303b68640c2d14c1cd208b5b499ea36f58d67c.nq.gz
│   ├── 193de62a730debb54d7d8b958e585d6992961aa2.nq.gz
│   ├── 194503abc5b02bbe7ee4fa1c0c7a9f60e61e2833.nq.gz
│   ├── 19bb952d7d0c5f79633621234c12a4e28b627b63.nq.gz
│   ├── 1b6da49135ef97d6cc875de3e0059e3cb994ac53.nq.gz
│   ├── 1bcb2cba8d54fe3e541e6cfea4eb458cd898bf33.nq.gz
│   ├── 1dca99e3bad4c50af2f6f3502be4b3450efdd720.nq.gz
│   ├── 1f07b3747d56f73246ecd05c07c83eb01b282652.nq.gz
│   ├── 1fb5454b942e1e018469a497434245c865946927.nq.gz
│   ├── 20bbe926f36a2a500e2d75192519fadec918f460.nq.gz
│   ├── 20d7062f5325e5a39f35c12e9855f516e1a61464.nq.gz
│   ├── 2193877a6053b6bff6009c33a12af7dbaceb5d52.nq.gz
│   ├── 2718c0ed876146ff37700d076a47a4253dd832ae.nq.gz
│   ├── 282579e0981c4febf7e27fe2f31d019ce8816e4e.nq.gz
│   ├── 28f4f8c870c12fb8e1ee1de6fe5aa26117e36e4a.nq.gz
│   ├── 2aff97f187972cf8f08987915846a27721587821.nq.gz
│   ├── 2b57895efb6a1b524b13f2ac8574cafcff2bf1c6.nq.gz
│   ├── 2d7e857ae5d72764b5dd4ff237596e9e61b407d2.nq.gz
│   ├── 2e176fac7a1f6db0bfdef2ad9910e87e923766bd.nq.gz
│   ├── 3194d30974126627efb855e1f90708c2813d7fd2.nq.gz
│   ├── 3324fc15afd4782b94d598de962f3a6dda91e161.nq.gz
│   ├── 341f7393dd028cc478af0bff90f31b6249fa34a3.nq.gz
│   ├── 347d424fffecebb8f5399d47fcbb04bb1e21e7cc.nq.gz
│   ├── 356a6548a82d261a53cdc3e3744da3208eecf101.nq.gz
│   ├── 3615ee8c320cdd98a32afaa1acc5ea2d0b19bb38.nq.gz
│   ├── 3654f1c0f61bb355c546080b354f1cdfcc6fc4df.nq.gz
│   ├── 3a08f5d3564e1e1a2a56de632f08e3babaa00ed3.nq.gz
│   ├── 3bf6484a29d8da269f9bc874b25493a45fae3bae.nq.gz
│   ├── 3c74d2efc675b015f431c316719085c6337b8727.nq.gz
│   ├── 3dbe0a0a03f6f45fcc6244063ead4968f6a3c644.nq.gz
│   ├── 3decd7955b3b3dc33c22fe0f09c7826dd453e90e.nq.gz
│   ├── 3e9094231b74925c64ed02cf3e84e09df6b6e5cb.nq.gz
│   ├── 3f0cb6789c392c4309371134428f8a632d4315c4.nq.gz
│   ├── 3f1283010555a6d5333093f5254c4b01891cafde.nq.gz
│   ├── 3ffa42cd5f348561d54959377b89fc213c29cad2.nq.gz
│   ├── 45894ea854cf1890aa9905515220b2e101642fa9.nq.gz
│   ├── 46d05a8ae225da74a393dd45734d1c8c97559f81.nq.gz
│   ├── 4766093fbf1ad2b12be9d0648105aca68198786e.nq.gz
│   ├── 499c23f0409bab26f95e31ca018f4179ff44ea1a.nq.gz
│   ├── 4ad184f991a5e322487c32e379cfab2c66671cc6.nq.gz
│   ├── 4afcb39d0013b454df31fea4fe2a087244e3162d.nq.gz
│   ├── 4b3b816cc1f3a5ee6b97e3603541c0cb69eb3bd2.nq.gz
│   ├── 4c0b679fb7c366c089f1648ea77f35c74ec0de54.nq.gz
│   ├── 4e6208fbccb8969f64112891ea92d5d23ded9c6f.nq.gz
│   ├── 4ffb91e4950e3004eb35609d0822073a42ac1b69.nq.gz
│   ├── 51d4562c1d360549c7d851a9ab0ce8edac76aebf.nq.gz
│   ├── 5473ef5c2f7eae0a1ce54480d410b9d5e959043e.nq.gz
│   ├── 558db4994f272817733e4905ea21857eaa6c6a16.nq.gz
│   ├── 56922f158ca0ffe49357729e8cff450cee66227a.nq.gz
│   ├── 598cf3e6688ccf5b7ab7d860d628fe36b46eddfa.nq.gz
│   ├── 5a1e7fed2db24dd1d0fec235e5d686e00fbe375a.nq.gz
│   ├── 5a9ca398a6ad3d216ecd339344fd42aeb84112b4.nq.gz
│   ├── 5d0903171a657cdfb9cb9458086e2cc2ad5d2a68.nq.gz
│   ├── 5e348bcb11f742d2f55312ff89b3c48b4788d822.nq.gz
│   ├── 6448bb84547b92b81030d6f4e88941548b0882f1.nq.gz
│   ├── 667eeaac47a6f89f49b570c02f8add41dbb3d5fb.nq.gz
│   ├── 67506eaca3903d741308bc282eb887098c6c8a14.nq.gz
│   ├── 6a69bc88d5b1822cbaeaa9b138072274f4a9d0d8.nq.gz
│   ├── 6b44973082ddbf83354cdd31568595339d87630e.nq.gz
│   ├── 6c74495c1d2b7bc21e7057e20d27903aea96b5f6.nq.gz
│   ├── 6d1a7526d08ef9310091a46583ce11f52a823666.nq.gz
│   ├── 6def24efee9da41d12349ac8fac239a8ef6878d2.nq.gz
│   ├── 6fa0b867cb1c60e462b65bf1c5e8c21b02c699a5.nq.gz
│   ├── 6fdb82ac0e45c6c363a89fbd1d37279bc61aa706.nq.gz
│   ├── 709de3d88453226f03eed371c7c9820b7268844c.nq.gz
│   ├── 7506bbf79b9bbe96aa4921edc88a8e3edec3b8ae.nq.gz
│   ├── 752a4586f06784f53acd9f4c0291e4ca7990010b.nq.gz
│   ├── 77a67fb53fc49e4514c886cb04c79c6edbfd403a.nq.gz
│   ├── 79a98cd1160595cff9ccb386a66623b2ca972672.nq.gz
│   ├── 7a0aa0d320171f7484303ef5b518441e2e70706c.nq.gz
│   ├── 7ae7517689498c63f32e3909763009f7ee565740.nq.gz
│   ├── 7b53edd9ba79619431026428eacff4f7bde1bd19.nq.gz
│   ├── 7f9ca6ecdd151481b56cf5414389fa138d1ea438.nq.gz
│   ├── 7fee0eb6c3280f90512d01b5b1b3095293e9be7a.nq.gz
│   ├── 810373b6ea217e4df3627344cb4f1e1c4adb4f4d.nq.gz
│   ├── 82e5f80f87caa89ed6da4663d2db1685827d3705.nq.gz
│   ├── 83ad2c168d502f7755df563243e1f53409042c63.nq.gz
│   ├── 8582231c9348e2c6ef02d855dc904ea6004a065d.nq.gz
│   ├── 8648f56d3be7a154ff5385541495d890d47b123d.nq.gz
│   ├── 87e6b1df5789df5bccfe9132287fa01490dd7fe9.nq.gz
│   ├── 88c18c4ae526d24a9b1e418cba76fe808799e5cb.nq.gz
│   ├── 897da2dc250779bfa4005f7328c5840ab7dbd84d.nq.gz
│   ├── 8bb047cb1cfe0baa891b15577a8b5b4c98c0317f.nq.gz
│   ├── 8c60bca841eef853c9df8dfd98bc9c261a045988.nq.gz
│   ├── 8d7795f36a068993069ddffc68834d3264d6cac8.nq.gz
│   ├── 8dd111d3643d41c4bd1c8ccbf52650aaacd801bf.nq.gz
│   ├── 90899b60b4d519b6de7602cfc1fb69474b99ff1c.nq.gz
│   ├── 909bac1b999518b4d79630f5517a8d83c3b02640.nq.gz
│   ├── 9112ee072603aa0336a3e46bf8776dc8c585e0b6.nq.gz
│   ├── 91711282efa551d1bcdf158b7f7483df1527f29c.nq.gz
│   ├── 94214f33603901c678c4acd59bf6d1eafcaa3bc3.nq.gz
│   ├── 963819790ff17e7bf57357acc18b790eab65fbda.nq.gz
│   ├── 9757411211381501cfe4f0d80e784cef2067aaf3.nq.gz
│   ├── 9c95d5658caf63dac1836694e198855e880ea5b6.nq.gz
│   ├── 9d571d0620544582423d41673e242f640e511c17.nq.gz
│   ├── 9d907c075a0f1918f651e5f196d89ab16bed9b55.nq.gz
│   ├── 9f1c8b0353b4f1e7789123ec964421d9f6d9266c.nq.gz
│   ├── a03beb334c9a2211e9ae9bb3a5168fe51da196ac.nq.gz
│   ├── a1e33a57aa0526de32f0f07d3409799efd5d49f4.nq.gz
│   ├── a258e68ec05f019cc4f1a98a3d2b23779284c97d.nq.gz
│   ├── a507945dc94c012ebbfeaec1569f19f94c12121a.nq.gz
│   ├── a6f9b3537d69a73f1d8e947e37977e0d8946cd7f.nq.gz
│   ├── a7a1de362aad11bff07c1c4586261d9e1cac008c.nq.gz
│   ├── a8178bb3451428df64e5a8c90d16b33829002c94.nq.gz
│   ├── a9969993201f9cee63cf9f49217646347297b643.nq.gz
│   ├── ac95615a98e30b4305ab4475f91312f2f7ede51d.nq.gz
│   ├── ad5c373fd6ab527947ebd8327592855ec07a0eb5.nq.gz
│   ├── adc3ba947b3d622bf8db0f821d37f00826e38121.nq.gz
│   ├── ae5c13b98d5123fbac5354bcff19b50c0f35c581.nq.gz
│   ├── ae8d22b3bd52b708a5877e4a2ac7ec5933e6c8ee.nq.gz
│   ├── af8ac9dedfa33bec3078dc0a5fd952009730138c.nq.gz
│   ├── b016556db9542c4b8878a1b303f95ba40baa79fc.nq.gz
│   ├── b08949e1e1bf85a192c2524d0a2c4c8e98778c1f.nq.gz
│   ├── b131551d7cbb7b3048c586c09fc9a384dbdbd696.nq.gz
│   ├── b7217d722bd96fac36fd4214a1f058cfe6642a3e.nq.gz
│   ├── b737789a101f92ef7d45c9c300135041af708f54.nq.gz
│   ├── b75c8692ff7b5219fd782445520c55b2db33b42e.nq.gz
│   ├── b7b8653697c0368589c0745c75ed2af82715b05f.nq.gz
│   ├── b7bd05261bd6ef39dd1ae85ee40092c129022cbf.nq.gz
│   ├── b9245e5087f5b296a48375f4ef5d8f7cc8db006c.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bc4208a9ae3760321e6751c3670c193dd7e3c1ae.nq.gz
│   ├── bd1d34dfff0882f6b46c03012621a84f55fb62f8.nq.gz
│   ├── c0950383d884128b04b22587bba6ff6f23f8cd00.nq.gz
│   ├── c19af3a5c6823255c996b4ee4a3fabde0988b1b3.nq.gz
│   ├── c4c958f4190616910501039c05299b434e491a8a.nq.gz
│   ├── c8ae4107218fa27f8368681d657913d98d3f313d.nq.gz
│   ├── c8e3101610c4dd0e7362333f62920c185abc97e7.nq.gz
│   ├── ca2e201f63d4f4fccbee5f9383e70fc9f652d991.nq.gz
│   ├── caf36da4eeaf17ec7f1d11e9cd49286948f275da.nq.gz
│   ├── cea32105f7aeafd4a62e4fccc8d63e8ede897869.nq.gz
│   ├── d0f2daedf89a8030ee44ee217362f5d1a02cb872.nq.gz
│   ├── d13130f6e82cac1f9529d17e4b6024049afbd33b.nq.gz
│   ├── d21a8261039dae3cb38f0e3ded3f751e6cb1f24d.nq.gz
│   ├── d4127a8fdfa15626ffa1fc8cea504c9c1660da2d.nq.gz
│   ├── d7b1a51c3927eb4f407c3e6ba1f32df2e2ec11f1.nq.gz
│   ├── d84a4709c9b024734a42ecfaa87d95d59415469a.nq.gz
│   ├── da000b9349bae36e123663754b81f0582eb4bedb.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── df51be8a39ef157367dfc42c90879d280e5571bf.nq.gz
│   ├── df63b40c261225f119f0086cd13489bebb4717e1.nq.gz
│   ├── e07013f9d5c81f773573a62a5b30eba81b178ad6.nq.gz
│   ├── e2a7d113761e66f8008d5c9047ecfb3db9186b8f.nq.gz
│   ├── e56c9c81fa5aeb9542128fee48c1a04eb7401596.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ef6c9776035f39717e0647d9e115df528d5288.nq.gz
│   ├── e75cb3eb275dee5d04e1e4aab9d5d43485fb4168.nq.gz
│   ├── ea2e75936af39e222db1faae78b8e8604f35cf51.nq.gz
│   ├── ebc6180f91f8681f2ba07edddb7f4d98a851d05b.nq.gz
│   ├── ed404b8daa8e4c514ad24979c566c4cbd10b0e2e.nq.gz
│   ├── ede065a2f79e1478b948ecae17596fd277ab92d1.nq.gz
│   ├── efa660d41d9859456b23be54acacfbc28302b1dd.nq.gz
│   ├── efd18427c34265f3363e8a3e140e81450a32c6bb.nq.gz
│   ├── f30d3f0a9c165ddc99e64a0530a22b110beb6935.nq.gz
│   ├── f316f1fd8cb1a6c698dcb8f799e971dae08f72af.nq.gz
│   ├── f3670b5ed07f68d59ba9ab36e4bbe1b4232d2cf1.nq.gz
│   ├── f39b2d7abdf14a5bbe1b8469848875d390ff443e.nq.gz
│   ├── f9726f9e67d10a596ac6efaeb114a6c479fa24ca.nq.gz
│   ├── fb3ad98d120040fb305c919ff5562873a057552a.nq.gz
│   ├── fc7057fd6c9dee1a9eed18761c561f6c1928cd92.nq.gz
│   ├── fcc7d940c84bd54d34b08f7f7725466bfbfc909c.nq.gz
│   ├── fd1213b8393b01d079477429166c78b085fbc2c2.nq.gz
│   ├── ff07ac5ddcc986a5883972082b56f7230fbd11ef.nq.gz
│   └── ff7ca25f403de33885b0764b6f824c0d95534fc2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 02465ce96c187912208f75e28d3a0b17cb1aa81b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 183 files
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

[django-guardian/django-guardian](https://github.com/django-guardian/django-guardian)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
