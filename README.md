# Repolex Knowledge Graph of ansible-collections/ansible.proxmox

RDF knowledge graph data for [ansible-collections/ansible.proxmox](https://github.com/ansible-collections/ansible.proxmox), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.proxmox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── efa0d5bd4e7149e7d7aa6c2e5ad99e9315d338b8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── efa0d5bd4e7149e7d7aa6c2e5ad99e9315d338b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 003e00d51d5a988f8c412633c49ae3eb75cf7360.nq.gz
│   ├── 034c3e5e4041f30eb50cae43b57bd974dcd9d917.nq.gz
│   ├── 0479e4c3497d1457ed528bb4e2b3a3c300f88742.nq.gz
│   ├── 07fc71c30a63679760d4201b5ad8eae0dbd90367.nq.gz
│   ├── 0a2e3705b95ef0a8296d352e1fd6b6607f03aa03.nq.gz
│   ├── 0d9d1707ad8d0066cc1acaa043f4cc04192c43be.nq.gz
│   ├── 19591235a24c2addcab784021af4e96519f3c04b.nq.gz
│   ├── 1b32819a73884dc3f70d00150cc4554762e0272b.nq.gz
│   ├── 1f797535ed8cffded5ad03a17ec8682cc593d279.nq.gz
│   ├── 22298d06abc721e8d457ccf930aa429a3109383d.nq.gz
│   ├── 25c3a573652d38a0323bb60c7ea7e3967c0efebe.nq.gz
│   ├── 2c22622f4211e8037bb8fbde75219ff8219976e0.nq.gz
│   ├── 2cadbb0811fd30fc93002943407b2016d137c548.nq.gz
│   ├── 31368dcb706b75bcac97144613cf8c5b6bfe7002.nq.gz
│   ├── 36b93d23ecc50c2db5b69da4ffda861a7efdaf48.nq.gz
│   ├── 38b598af30c60f77313617dc03282eef19c2346f.nq.gz
│   ├── 391d95106793c26b4e580c3d68714054a5af5df7.nq.gz
│   ├── 3f3861258f97fa8a971cf151573830940cd43c40.nq.gz
│   ├── 3f3d73dc10af6e61de9e0a80ca099acdfdc8b9b6.nq.gz
│   ├── 416b0ec37ca750c644408706370d90590865cd95.nq.gz
│   ├── 421d8bf2fdf391d0fa9f78182b2c7f4a4319d2b6.nq.gz
│   ├── 42aaf6a646801a573478b5b1996e1b62d48a1986.nq.gz
│   ├── 43cbc9d47e003e8b6bbc848d6cfa9197c0bde2f3.nq.gz
│   ├── 4646f4a390164c5538c36e8b98c75a51cf823549.nq.gz
│   ├── 4953f366238a34a60b14047bdf2359641c7b5bc3.nq.gz
│   ├── 4d042f0bc29ba11add87e47b2b12264c44d7dbe1.nq.gz
│   ├── 4d9a1d540ee17bdfeba3cfcc1a202cbfd6f6ee91.nq.gz
│   ├── 4fc78c2bb6fbcf844398b6175aba8d44bc40b692.nq.gz
│   ├── 52b761f0318ebab7985b2861cb0587e61c312460.nq.gz
│   ├── 5489aa7b5c54a6978b6b55f246f5bc54c66c669b.nq.gz
│   ├── 5a3f5dfa0bb3986e022f04b3aa700744eac66882.nq.gz
│   ├── 5cae24f9438285bb0cd854d9e42b61299f333dad.nq.gz
│   ├── 5d315bee0758d76c38a7e8e83b189447db968a47.nq.gz
│   ├── 5e49649998a543f6241fcb8ee0f57708c9e9a068.nq.gz
│   ├── 6163ba7769698748a86b4ce39de77a658935018f.nq.gz
│   ├── 6ef92f4afe7fc53afea523b4da6d0424dc809d13.nq.gz
│   ├── 70c71a359952217d43a615d63b482d76e86f180e.nq.gz
│   ├── 7111aea1eca9b4c5f7ea4f16a304d01f21f443c9.nq.gz
│   ├── 728d9c7d3b86c909a9e1170021415766c5808483.nq.gz
│   ├── 802d6e7cc01006da8ee612f00014e3e1269c2f49.nq.gz
│   ├── 81bc8be3454bba10455383a33bb2b491e9412302.nq.gz
│   ├── 86578f26ef21986d5d82e8fd4f7b64294b7f2249.nq.gz
│   ├── 89325be16f1ce63cd560b1b57f883cdf7927dff1.nq.gz
│   ├── 8c2ef4105e0f489b4677172ad561dae24ceb7862.nq.gz
│   ├── 8fbfbea9313304b0674fc49449d057378fedf993.nq.gz
│   ├── 900df3257fa3d465ab9382b3bfbf2f2e5829dedc.nq.gz
│   ├── 919a88663734b9c4dfece3fc3fb01ddc429ce6b9.nq.gz
│   ├── 959b5b7ee5a8f433ce4eb44dcbfe88fabd98a91b.nq.gz
│   ├── 97c5c0e825dc21bede4dee9f1ad19311763253fd.nq.gz
│   ├── 9ab929331828d79963b53e5489b5d94d748da34e.nq.gz
│   ├── 9b0b30557f54f7188f111e300461a07365b00df0.nq.gz
│   ├── 9cdb7908ead24e8a1758c516bfe6f612429e4b65.nq.gz
│   ├── a1890ef675205c16d223d5d7f60eef67cfb9b443.nq.gz
│   ├── a240261c02b0d3f36fe2ec56f4f5fe560369cd2f.nq.gz
│   ├── ad287c399cdca9fb4bfeae029aa23d7e5d4be6fa.nq.gz
│   ├── ae66aff413b2528c3b18ae3ca945280dafcb94e4.nq.gz
│   ├── afdcf758bf2e2b40c01f53b10847ea756f747f12.nq.gz
│   ├── b4d90790223b95552556ea895ac541a489a7379d.nq.gz
│   ├── b5f56f101ec4fc56852f0b4cc3120371b85c3bcc.nq.gz
│   ├── c1b8af2d016923a265b4b01ff2b5f700cb5c2545.nq.gz
│   ├── c4e8fa8e066d659b5b64007fd4dac9c2bb2d8d58.nq.gz
│   ├── cf5ed529cdb6e003d1e9592a22b827cf935f3e7c.nq.gz
│   ├── d365cc03488f8eeb99beb23e790bec25d4e16f78.nq.gz
│   ├── d794ab30be703208b804dc546711bce798f60c4a.nq.gz
│   ├── d89a0b7c9c839f6e54b4f590bb86415b63ffd4ae.nq.gz
│   ├── d8e72b0c2ebddc0012c637e69930612303d4cfdb.nq.gz
│   ├── d8fed0353014eef3ab8a5fef31266ad0b91c409d.nq.gz
│   ├── da45d2e7c1e9f71440e23fdd78c6d25b060bd207.nq.gz
│   ├── e0a9e00867d1e9c1586a028789a5d258d1190a8f.nq.gz
│   ├── e4f0a016c06141f1decccfaa7e4809ea5b1ec8c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ead651546f2a569835df8c219efd29239c5b413c.nq.gz
│   ├── f0a6f0e56bc0818096dbd0b1f93d036cafe96035.nq.gz
│   ├── f0fe63e207d9abb5f1f670f8202321fd5b2da3db.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f35a9e00dfdd63fee2c936828d4f3bedeb59d75d.nq.gz
│   ├── f45c10f05c53e9cd072ccbf6f62ed4583a3c0f94.nq.gz
│   ├── f7af525f561cbfc7bf67628a0d717e6c5dc87b1c.nq.gz
│   ├── f921c516aa77b2f6a25325fc7b94ba916fbe4e7b.nq.gz
│   ├── f976ed6f0c6a9eae14a7fd7e28b179cc4f2fff77.nq.gz
│   ├── fb56a0d1318dbf2d2a839affdc3848f62ca65bc8.nq.gz
│   └── fbaee755543716b5e00ca70dc811770b79864dd2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── efa0d5bd4e7149e7d7aa6c2e5ad99e9315d338b8.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 89 files
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

[ansible-collections/ansible.proxmox](https://github.com/ansible-collections/ansible.proxmox)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
