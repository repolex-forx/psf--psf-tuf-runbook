# Repolex Knowledge Graph of psf/psf-tuf-runbook

RDF knowledge graph data for [psf/psf-tuf-runbook](https://github.com/psf/psf-tuf-runbook), parsed by [repolex](https://repolex.ai).

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
rlex download psf/psf-tuf-runbook
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 01ff5b2b82dbe51695ed898153b63d7a0cfc1921
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 01ff5b2b82dbe51695ed898153b63d7a0cfc1921
│           └── chunk-001.nq.gz
├── blob
│   ├── 00885cc43987f166fbc82d90b186add585f67aac.nq.gz
│   ├── 030ad0eb3946161b037ff270a9d12a57efdd97bc.nq.gz
│   ├── 0c3196c7b3dc19f7e0b74a84674dbba974fbc7ad.nq.gz
│   ├── 0fa7f4731beb54eb4e8ee3d51ea4e04a1bcedae7.nq.gz
│   ├── 152d9698da86b95ea0d980bf6720fb3d1fee337d.nq.gz
│   ├── 157f46619d1dc4c4d26f9c862569ccc3badb5f7f.nq.gz
│   ├── 18b94eeb91310bc511ec8974dc3873c87d16e0ac.nq.gz
│   ├── 19bbe3b8b4cebee7a991f4bca37edefe050fae6f.nq.gz
│   ├── 1e507a0ed7098590f6a846047e333286a999ba62.nq.gz
│   ├── 2565ae1b34e66896c1c9a1d3efbae8245e65b1c8.nq.gz
│   ├── 27fb8250f22f3001331e1179968ed73e81f691ff.nq.gz
│   ├── 2814222eb13aab9a89751cda61dc1f8baee07533.nq.gz
│   ├── 2925f235201aa657a0e8bdfd521aa0aeaa8f0593.nq.gz
│   ├── 2cad35d78ded82f86be46c70d09ee5911737bcfe.nq.gz
│   ├── 36ac44a242e88e2cedf2ead66c7a73f107dd4b56.nq.gz
│   ├── 3881c2e9dc661f75e6207429f4af0d95de47dd96.nq.gz
│   ├── 3d48056a45fe3375f05be438a75ee9401abda704.nq.gz
│   ├── 3f8b615fcb2f6f6dc58130d8d699deb6c3373fc1.nq.gz
│   ├── 42d86a8e8a8a1b0b102a9a4dcfa481dcadc40525.nq.gz
│   ├── 45e73e624e611cd833952fd7be6bad1296f24c8f.nq.gz
│   ├── 464b158256ab49592a549718dc86a7b98ea85a57.nq.gz
│   ├── 50ae725a326169b03f6be889e1423dcddaa5d280.nq.gz
│   ├── 536fd6907b2e44638daf2c650aa22803334f9b61.nq.gz
│   ├── 5598f1bf841a78b84905fbe29fe5a33e8d41234d.nq.gz
│   ├── 5769f47fbb2fb9489369946b5927a545345cf508.nq.gz
│   ├── 5813d9fd32db98eec4ccf57f0d7ca08cc3538026.nq.gz
│   ├── 5a0d371e5e08fb19d7c7093fb330afb7589752ee.nq.gz
│   ├── 5ab8c52cdb7545c99db61a48f091c02da10746aa.nq.gz
│   ├── 6197f49b3c209008e7f25f0c4d96d6c701ddc1d5.nq.gz
│   ├── 697b8a12d296a78a90657a21022e4eec53ae5419.nq.gz
│   ├── 71a33e7f64b24a04fc3723b39ce0ba9c51825a68.nq.gz
│   ├── 7975e6aa98b475d55cecfbe5297162b57e23a568.nq.gz
│   ├── 7d870273705396d4156998087f8764ab2f05adcf.nq.gz
│   ├── 7e7c8f58fda214055db4da71e8f093ec6aae6b38.nq.gz
│   ├── 833eea4efee60a33414706f9712f556e1a327a12.nq.gz
│   ├── 85de90ab6f0be9acef4aefd80c927bdb31a7ef6d.nq.gz
│   ├── 879119a045134f8e1305a8435af0f032fab7a435.nq.gz
│   ├── 88d9394a60abe56287db55524a8316b0363f400f.nq.gz
│   ├── 9014206275198c8fa446308b11826e9f3d907e4f.nq.gz
│   ├── 903bd1eb1380c507b85e77a6f40e0626c7e5a385.nq.gz
│   ├── 95f27a41f4a461edc53726c89c251dea137f3c45.nq.gz
│   ├── 965827cc8944db6ab35ccfb306a30b2062d5246a.nq.gz
│   ├── 967d778c5b2b608c494f7e04cc5b834aea1effa8.nq.gz
│   ├── 9a03d8458c70f3b6e9991360da16ebbb1db1d15c.nq.gz
│   ├── 9a0cc350a4bf0d200eedc13ba87c10114793a88b.nq.gz
│   ├── 9bc5c479b1277ac64eeb98dc3c85283096697d07.nq.gz
│   ├── 9c54b18fff73dc33a34ad9b4c8a7a386a94212d4.nq.gz
│   ├── 9cbb57ca18658635f43432ef9c6ecc2fe3a027ab.nq.gz
│   ├── 9e017080321cfbf6707ef0c77d4938c24d23d8f2.nq.gz
│   ├── a9b15ad3d3b83a4f062a698b573c3996103fda69.nq.gz
│   ├── abeec7d07cd4529cfb99e4f94e5aaa730e7b7035.nq.gz
│   ├── acdbc6854c9b8ab7d660d962267e1ed4334f8284.nq.gz
│   ├── af6dc46e5d1d57d15462f787de30ab2b55622d50.nq.gz
│   ├── b1300e08a582804b32d91f80ce25494af1e5bfca.nq.gz
│   ├── b15a3d38a105063059e197ef67220f8ac32845b0.nq.gz
│   ├── b2c05eee1d5dd9d1ccf1ea41a52c306c2c3ff205.nq.gz
│   ├── b2c33f6353bef15d5da3fe6d002a26a1160d3ad1.nq.gz
│   ├── b4982cb2b9a1fb6e136230bfa6ff02760aafad2d.nq.gz
│   ├── b7641c21acd53a290008507e5bca02d995b3f951.nq.gz
│   ├── be98f6d23a9dbe004eaf122bdc69d93f348667d4.nq.gz
│   ├── c04c86bb8522985a05335a82ae9c3c573396eb0a.nq.gz
│   ├── c4bb90286ed0348fa75f108eb86799193b122ab0.nq.gz
│   ├── c7479713161da4e92723d25395f7c5e65b51ffe6.nq.gz
│   ├── cc69bc2e469d5589fcfaba4c04b3b64306e66f1f.nq.gz
│   ├── cc825c976ef9ce1dc5639e3698f8e44eb0c4cedb.nq.gz
│   ├── cffb437d840c2946e0b36c9e67925c7213a0821d.nq.gz
│   ├── daa922aafee4d5acda32c63bde98ed71bc4a0435.nq.gz
│   ├── db7d9e8dff2535d570ff5d596ccada2470abc406.nq.gz
│   ├── dbdd4d20ef6f7dc759d86217391441110de089d5.nq.gz
│   ├── dea6527b3119d7f313380d51845efe17cb1c0bb5.nq.gz
│   ├── e1dfc43c53b9217e1d274856b017add5aa2355e3.nq.gz
│   ├── e281025dbd55118775dad8a227f9060cb5c14515.nq.gz
│   ├── e3e0029993c843c3544e5811573170813fa395fb.nq.gz
│   ├── e561b846f7a5fb399923b467aa7a2251c199782e.nq.gz
│   ├── e937f9544195aabe4ff217bc48b3079e4d93836b.nq.gz
│   ├── eba95817d900c71386ca698fc7ece211bf9f46ae.nq.gz
│   ├── f5c1224c63e63e9e156235727167bd89c0ccb22f.nq.gz
│   ├── f640ade7cd7f4653d952cb2635b6a90f64b09e11.nq.gz
│   ├── f8d466892aa6980306ea664d4e07276b6dfd5cf1.nq.gz
│   └── fed2da7f316c44f44f2f6b8a741afa22f5aa6934.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 01ff5b2b82dbe51695ed898153b63d7a0cfc1921.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[psf/psf-tuf-runbook](https://github.com/psf/psf-tuf-runbook)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
