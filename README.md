# Repolex Knowledge Graph of ianvs/prettier-plugin-sort-imports

RDF knowledge graph data for [ianvs/prettier-plugin-sort-imports](https://github.com/ianvs/prettier-plugin-sort-imports), parsed by [repolex](https://repolex.ai).

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
lexq download ianvs/prettier-plugin-sort-imports
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 26bc50bd2f9846898fa3f8f4bac82cc1f55d7480
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 26bc50bd2f9846898fa3f8f4bac82cc1f55d7480.nq.gz
│   └── repolex
│       └── 26bc50bd2f9846898fa3f8f4bac82cc1f55d7480
│           └── chunk-001.nq.gz
└── blob
    ├── 00c17ac5b5ccf122d2239fe5d218d1872f8f038d.nq.gz
    ├── 00fd7f2458e61eb94c8528d1a415e517c53135c1.nq.gz
    ├── 0355cb84dfb7fdb164097c42db249cb3446344af.nq.gz
    ├── 049949c8449ba9a9e74f9b9928cd7f33d326595d.nq.gz
    ├── 09a94fde5f83a101763a58b9f71dd9ae20557df4.nq.gz
    ├── 0d5328eacd6c6fceaacf4409e8e7ec9137416369.nq.gz
    ├── 0e551093dd85c44486cf137e7f5a4ecebe9a1550.nq.gz
    ├── 0f6d7a76d794f0e7a28d27b0c0fda0b13a10fa14.nq.gz
    ├── 0f810925650a2b63237938fe207ebea975162dc8.nq.gz
    ├── 10a0eba76cc7949fdb7bdc6e1f1f516046dee8e5.nq.gz
    ├── 117ec4113d09726845600bd55a4de4ac64093c92.nq.gz
    ├── 15b15cd880ec4b96247350676d8a680f0ca7c012.nq.gz
    ├── 15bfbe950dffebb9f7b13480153af6c955336c5e.nq.gz
    ├── 16bc1d770cff1b0ebd180db362582945dcbd69b6.nq.gz
    ├── 19ff8aabd3c173d01b5477b049babdbf78016481.nq.gz
    ├── 1c18fb3e47c4106c4f60e27072a5f03395dacdec.nq.gz
    ├── 1dbafccbefa2332ed78f7362856a9c6ad78941db.nq.gz
    ├── 1ddf83e911e7157c0fae6046ee4edb295432e8e2.nq.gz
    ├── 1e1f13880f9cdc93f7a3fb9f6ffbe8955dcf7a4b.nq.gz
    ├── 1e49532837bbf59ad196571ac80aaffb919ac248.nq.gz
    ├── 1ebf5c16cd5b36462278dc124821d95985b7ebf0.nq.gz
    ├── 1f44fb62ef8cf74d41b6dc58d1756f525cbea197.nq.gz
    ├── 20501aa439f7b4fc8689b248c9eab30d49a11e13.nq.gz
    ├── 209a9d3f8bad2c788c112bde81bd80ce0bfdb2eb.nq.gz
    ├── 2117603047db28395effc40d22330c8eeffb6b56.nq.gz
    ├── 21c51534002db72476deaccd87232b65dfbabe13.nq.gz
    ├── 24ee86bee977c0148ed14780ad31266c0347d11e.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 27b38039c1e7731a10e630720124d8dd104899ba.nq.gz
    ├── 27d832b8881d5e9298c0e750067ce1c3e9b7cb65.nq.gz
    ├── 27f24a469132e3680c16504e4b9ee8e2bb9ac578.nq.gz
    ├── 280ff01e2f3e5af77ae628aab176baf999fca913.nq.gz
    ├── 281211a408af950ba2b95ee12c8504cb5538b418.nq.gz
    ├── 285a25c4566a2bede3b642049ad6df4e8208bc8f.nq.gz
    ├── 2ac7fb38a9f728455493be95c41582459114fd55.nq.gz
    ├── 2ac8b9c3e3f2520dbdd3443d7671cbaabf8ba048.nq.gz
    ├── 2acbd474b25900f0d42e7e1f3ad35f3eb36bc2d1.nq.gz
    ├── 2cc48f165ffde8b701a07dfbeb3e1e11cf9c531b.nq.gz
    ├── 2de7b9745a2084ac6a5bd32cf1f2b6555f9b0de5.nq.gz
    ├── 2f0c0247d74026e8f870836df6be71d230c7bf95.nq.gz
    ├── 3000a3de263b153e2a5fcf9fa0f764a367470256.nq.gz
    ├── 322a13abea3f949c58689d4a2fe18fff96999986.nq.gz
    ├── 330a2baad7622d323c3f895b7f7f8c0eb39531cb.nq.gz
    ├── 35d75ba66e1699e460b396290197606f7e566f2e.nq.gz
    ├── 377c86db9d5060754a89d8fb2626135d0140f8d5.nq.gz
    ├── 37e2c2d8d5756ce2c2ce5617a4accb8322502440.nq.gz
    ├── 395003be399745e3a10a1739f4bce2708ccd3b19.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3e0df3e62c05d6a9a3a79e810138c2baec15f2d9.nq.gz
    ├── 3e3573536ba4bee597fda087f6ac261b42336ab6.nq.gz
    ├── 4340d302ad0fb68429f850a8a5c7370578d275ea.nq.gz
    ├── 44f7eff49506c2955a5de4027f8a9248814537e1.nq.gz
    ├── 45598d4d66253cb69550ccd42b93701099d65692.nq.gz
    ├── 4614ceeea23ea74728f808ce9cea8180f03bec34.nq.gz
    ├── 4819d8bc53c28fca391190398432dd4af303fb90.nq.gz
    ├── 488b1ff56675fdfee17a27b2bc02e72f8d847aa5.nq.gz
    ├── 48e3b4d5498b4d5f01f23b8432ae6c0d0a481293.nq.gz
    ├── 55e6de202d8cd31c277955c456ea93989b39ccfe.nq.gz
    ├── 58cc8699261106f8bda5a91725a680b11fbf06a9.nq.gz
    ├── 596a0051a5b659690a88f7448669645f3f5466ad.nq.gz
    ├── 59cbdb0cae0feef111d9ed3cb6536cbb0def9200.nq.gz
    ├── 5a0d5e480b5f395024be26a530d1f72811b1ac99.nq.gz
    ├── 5c7b032581dc325aadddaf2909603fcf243b297f.nq.gz
    ├── 5d1af53cb5104b6bfd90d7b46854ca5264b50b26.nq.gz
    ├── 5e2428c66e7d43eacc8987cd9c3990beaf68ca48.nq.gz
    ├── 5fb546da4980b8813352ccd928b29635a37b4b77.nq.gz
    ├── 60e6f2c30406c4edf7f3c14e4eacb772e46c5cb4.nq.gz
    ├── 6279118046a9ed5a7c6f8224d64aac809168fed0.nq.gz
    ├── 63303544afeae13354ccb2b2e86f448d2ab0531a.nq.gz
    ├── 6780ebc7d0cdf314843cc29b506ce67cfc2a8109.nq.gz
    ├── 67912d9b3e5060a6efad06adb515590d85d11d6f.nq.gz
    ├── 67e9859911390c60b75b00b4b083dc6b9aa0264a.nq.gz
    ├── 699308a76fabddd78757d9e8ec4d70782e027b81.nq.gz
    ├── 6ae3495b4e5fe07d66b3bb624c35f4004087c33b.nq.gz
    ├── 6d69ce6881f6150e07d4948e8107d8f65904ba2c.nq.gz
    ├── 6dacb0cdfb94d924cd0d1078fb6e1801c07a9163.nq.gz
    ├── 6ddd35734802691e85daba762272ee9a5559f847.nq.gz
    ├── 6e7058dfe6454b681b5f932cad34cf9c855c9aef.nq.gz
    ├── 70538242277e3ff8e195f18726c7a96da859eced.nq.gz
    ├── 71a573b7095132bc235a8eb490179697fcc036c1.nq.gz
    ├── 71de7006a9faf4b6b87ccc34f221381ed9a20758.nq.gz
    ├── 744c7d79f9bb86cd8bd219ec2667c82b1192d1fc.nq.gz
    ├── 7571b983333cc67e4123a3f2b9b94c1a45a27624.nq.gz
    ├── 77d4aad7fd31dd70d08b12d3b00257e4b3a5ff7e.nq.gz
    ├── 7957fca1356a62f8e189b1d5826b1cff17ac1e0a.nq.gz
    ├── 7ac2db9e663be6a9d9f68a8d116dfddd94cd9a54.nq.gz
    ├── 7acdcc77006f3adb07b00a5a89864b58db9f268a.nq.gz
    ├── 7b0a094b0079ca41830ac28ba31f4c77790cce1a.nq.gz
    ├── 7b1f9aee04108113a62a0a6b42b9afa87de5d732.nq.gz
    ├── 7c7b208c33dd160da9f21c52d37a6d56b14f3eab.nq.gz
    ├── 7ce6b9077ca3bda00b4179b819ef80b0c35a8a47.nq.gz
    ├── 7d3dd69dcd429ec92d2eeb741a9391c695b13b19.nq.gz
    ├── 7efa359bdf93b8fe9569c76058690e3b184f691f.nq.gz
    ├── 81b9ff4300ad051c675f3148891f5930be860492.nq.gz
    ├── 8200b4970cee9d334c785c72151b275f8940ca24.nq.gz
    ├── 8496483981b0333ea46b7ab90c12c4c3b12f28c7.nq.gz
    ├── 84b70cf5ce7e0192250d7b57ab341cb82a04a9ad.nq.gz
    ├── 86103e8088c7aa945ded63f7a34505486882811e.nq.gz
    ├── 861f38bd70882eec68432dd4365adcc90200faf8.nq.gz
    ├── 86944311f0e207e4b8c197edc5e171b4436b3109.nq.gz
    ├── 87013e6f35a97ad6f1b57b8dd15b9a1c5f8ad704.nq.gz
    ├── 880853f5e00fd1709fe588842d32c8ed8a3f8b59.nq.gz
    ├── 88b21d2d3447140986af24aa6c6f560b3037859e.nq.gz
    ├── 8947e3c5cd1af56b95545d4846c4e612d3a8c50b.nq.gz
    ├── 8afc9b4414ab0967b9a192c3d174e3a39dd642ad.nq.gz
    ├── 8c64bbe78aa1000289e7fa98e3e9b2cfa668cbda.nq.gz
    ├── 8e03b6ab2ac2d5faecea57b9571cef6ecb5ea234.nq.gz
    ├── 8e7de5f64c3a792876eb0c23192c33f713db0fd2.nq.gz
    ├── 8e953a0fbd45b455fa06ee02d83b097a596c4e98.nq.gz
    ├── 8f49f0107135db4e6f55a45821440c897c6d0e7f.nq.gz
    ├── 90296790e18e663bf4e165e1973b9fa74f3a3e28.nq.gz
    ├── 90ba185bbe034f0847e29af13c5dbef8bd16a4f7.nq.gz
    ├── 9131b4ebf577fcda0c8f54da443f30913fa72975.nq.gz
    ├── 926ee72c175b4f0a96498bafdaf138f193f50cb2.nq.gz
    ├── 92888d97a03638dba5311c3ed04ff913c8f20a5b.nq.gz
    ├── 92fc034cafe1a5d08709b32e3d962ad5acb4d631.nq.gz
    ├── 93bb6376b475f6bec1bca931e7f76dbb2aceb6db.nq.gz
    ├── 9447635780c148b28ee4299202f428d2890e3fb8.nq.gz
    ├── 9491f0aad2f5fad21eb9bf64ab8fe6bd3b3cae9e.nq.gz
    ├── 972db9c4557d7190def7332dc5f4b2d1b699f7d5.nq.gz
    ├── 9825382c8b47acbfa63aed007ea4d07baeefc6cd.nq.gz
    ├── 9e6d2aeba120fc643c42cfb21fe7ec64ee7b5029.nq.gz
    ├── a28f9eb320ea2b5c94485a22ff74fa3bef1d5764.nq.gz
    ├── a4d851e115d7706433b2ebe2ba20ab90ee893984.nq.gz
    ├── a73492c78caf2db29f8fdb687059e2e1bf08a62e.nq.gz
    ├── a7c3f326d98a73ec44ddd8a6d5232c4f0dac66df.nq.gz
    ├── a93b151e40ebd54e8c832324ae21ba2d07a5ace9.nq.gz
    ├── aa511fb0ec704ce7b60a61a8aa693d5d5a077bf7.nq.gz
    ├── abcce9f0a93765ed6eb43cbbf726635cd3f76f69.nq.gz
    ├── abf690b77d4a0715840a4e82983819bd112ad348.nq.gz
    ├── ae6a3d086e54e40565abcd4da0181d8534e15a55.nq.gz
    ├── aea7c4b159e4f7d27f43cc4927c1da17ccb414d5.nq.gz
    ├── aef667be0df57af0f991ff880a4061cd9491590d.nq.gz
    ├── b013463a3223864359a5dff2f431d3190e4e38bb.nq.gz
    ├── b1afc0df4ecec509652dbd2b459ab23730c33898.nq.gz
    ├── b246749bba1b65c6374325d938f5d1351a055993.nq.gz
    ├── b28117e686946791b09d2dc42dc91b30068a176b.nq.gz
    ├── b3b0421a78709e6364bad84ae8f7bf1740f45967.nq.gz
    ├── b413472bb4f2ebfede15db4a628db29715e84142.nq.gz
    ├── b51b66b995fa188e5c60e5563d67dcf75f229231.nq.gz
    ├── b69746a6331e1c6f6e7e47e05ec2eb0aaf044348.nq.gz
    ├── bb9c74b0a60d2e0cc8ee224003c568bfb3a26c0c.nq.gz
    ├── bba4d805b8ecf77259b3453a772c18396a1cda50.nq.gz
    ├── be22cddd2c3882ca26149beb52a68a7b74202621.nq.gz
    ├── c055e2216109eea364ff31d3f5b2648f21b594bb.nq.gz
    ├── c062b9e744e1dec67a42c4f574cbbea0122d4c29.nq.gz
    ├── c2231e702919bb99427cb55f599b06d00cb8b2e8.nq.gz
    ├── c33479529aa914117413b476183c49f78faad23b.nq.gz
    ├── c3c37d2b6ae7f3541ad7b2bf8c8a151015935a12.nq.gz
    ├── c45395f1a31bebc0cfa91e54070e2495792bd9ce.nq.gz
    ├── c4eb1a6b9d5cc1f66bd67654523c3cd93bbeceb3.nq.gz
    ├── c66429db518ab8f02218e25555ae6b6e9633fdec.nq.gz
    ├── c918634cf768ec030a2b9856d56bb64abbbe48db.nq.gz
    ├── ca7af3facfea79230a95029fbcd6681fcca95714.nq.gz
    ├── cadb17c3981f47f9ce8d4b185e7cc49189fd3451.nq.gz
    ├── cb732dedc4822213d41b4be10fea9372216e1283.nq.gz
    ├── cc7919254a06329b9b797d1af266c8307b2dd8f5.nq.gz
    ├── cca1f2e7bf97d72b7f4e818c68b4f6b0e0f4bc91.nq.gz
    ├── ceef8254de277af7476a6f0d3a3aec7544873cbd.nq.gz
    ├── cef4dd0f729e122990ca3b50080e9b5be288d188.nq.gz
    ├── d02980ce3b3f544564b68b2d49b24009d0423e07.nq.gz
    ├── d18f4c893f0d2286b31f055dc2bf59d68abb4f57.nq.gz
    ├── d2f2fd3b73a9e80c0a2591bd3a7e049bfa5920bf.nq.gz
    ├── d30ab1f4a72321460c9d5fc055e3460627291326.nq.gz
    ├── d35129d3239578e1d998941f1f3af4fbb1bf42e4.nq.gz
    ├── d3561d036372208858be4ce7fdbc3866c83e549b.nq.gz
    ├── d37c82a12385b0b1c25f1b82ff5f205496f86770.nq.gz
    ├── d4140d6e8f5d4644c9c5b283eae9eaa603f56ff9.nq.gz
    ├── d4a91dcb73abd74b9409825dc84295378c8d4e71.nq.gz
    ├── d54440f3d8af0fa3867c06bb6a3cd336fd3f4dbf.nq.gz
    ├── d6c0c47e7708fc3ff08898b60898309416fad50f.nq.gz
    ├── d99633b09e07cf93577d9e230cb844d67943cbda.nq.gz
    ├── d9dfe5b583ae76ce280b99f2a687b630050ac619.nq.gz
    ├── db66601f990c8740b5b773a50e1ac1a22e2e41c1.nq.gz
    ├── dc864a052cd957b0074351835cf3dd8080a2b55f.nq.gz
    ├── de22bd1bd1c56ff6a4c7de650b62da537552027c.nq.gz
    ├── de3468d757c094a3195ea95b893528af711a3181.nq.gz
    ├── de7e1fade44db07dffeb7375d517b8617364d310.nq.gz
    ├── de86d17a72115bc77f8a728de3111f542f16e794.nq.gz
    ├── e03df516d7745dd19c28a5bb879f9294caee7cee.nq.gz
    ├── e0a77ea11b746872b73e5aae9ed7b700010a9806.nq.gz
    ├── e21cd09c7886fbc85a829cf769eedee4d4ddd801.nq.gz
    ├── e255d4a596b7068e9d3c33e37104559aafc9e989.nq.gz
    ├── e262af40f5f9c141a9d4c2d78a9e8e1f3faf533b.nq.gz
    ├── e4c793ee7158d2e3c2384a2e405b56cdeb515c40.nq.gz
    ├── e4c915c87aa15767cc8e313845213d46f5eeae0a.nq.gz
    ├── e4fbd43204a9793d73e8d9fcdf541df1b04fe721.nq.gz
    ├── e617df3c600e07a811c30c2f80e43b2927cd0662.nq.gz
    ├── e69df67a78a4700f14c7d35cbea60ceb866e39a0.nq.gz
    ├── e715e96ad278c53ee407104345904f2995659d1d.nq.gz
    ├── e8acbe5a6f947fdf76ad6050ef64f4bdf7bb56fb.nq.gz
    ├── e8f71db3680ae8d7873dc73015cc9574c0b23e00.nq.gz
    ├── e9cd8bb793665dfe29ab75e0b8d6204a25054ad4.nq.gz
    ├── eabee670711ffe15174787cf055a2c4b48b1def8.nq.gz
    ├── eb11fc4b267eeb22c19685311ee363c18b4a5f87.nq.gz
    ├── ec3e036d62ed8c7e8852108845f1238016525eda.nq.gz
    └── ed356e0ca5e7e54f64e0f206c1909aa54d348cd6.nq.gz

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

[ianvs/prettier-plugin-sort-imports](https://github.com/ianvs/prettier-plugin-sort-imports)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
