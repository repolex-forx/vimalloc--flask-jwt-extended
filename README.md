# Repolex Knowledge Graph of vimalloc/flask-jwt-extended

RDF knowledge graph data for [vimalloc/flask-jwt-extended](https://github.com/vimalloc/flask-jwt-extended), parsed by [repolex](https://repolex.ai).

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
rlex download vimalloc/flask-jwt-extended
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11785e00ea3e01b4eb57a8031843e215fe171c2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 11785e00ea3e01b4eb57a8031843e215fe171c2a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0501368ce347567b7206fa6d606a619d57b5d023.nq.gz
│   ├── 057101e5147653d9f0fc65143ddcede8a0054af7.nq.gz
│   ├── 0584e7a112dcc16c463abea7a49c081b5f622062.nq.gz
│   ├── 0ca78f6f1b65d343709a9a9ad0e74837c516aed9.nq.gz
│   ├── 0dc5b537f33380c44a49fa4d87c281fcf44af897.nq.gz
│   ├── 0fe03d538d5d81f4c1f3cb8c65d2e16572124c0a.nq.gz
│   ├── 178e081b2d8a59c1768a9765d4137d2ffeb11340.nq.gz
│   ├── 18ccd56f8ebd30f12aa38100da7b82231f634c7e.nq.gz
│   ├── 1aa736a0957f095b43e7c9d7b4a30b95a18a46a4.nq.gz
│   ├── 1b75f45aed310ef4801d612c7a902b12b77779da.nq.gz
│   ├── 1b91e8928d6a920d1bf86907f13cb1b817a0ae1e.nq.gz
│   ├── 1d01e30275bb5c65690d7eefbdb8ad96f8816b9d.nq.gz
│   ├── 1f98560ba61ebfed7f5fa32f230fe203eb2e75d7.nq.gz
│   ├── 1fedce0c22710d491290f3a48f55854b00e2ffb5.nq.gz
│   ├── 2b2353a66e3a85bd9eeda8635e84cb4596cfcf84.nq.gz
│   ├── 2b7d8c1695eaca3e32bd7f114e442058d0b9bf85.nq.gz
│   ├── 340f3e0c73ed5644226abbfe0a1242d44e267dd5.nq.gz
│   ├── 3dc09fae3cc6a766b0c1a3828a9cdfaf3943a14c.nq.gz
│   ├── 46c0ca576a0f560ea90aa3ab0e6122dbba91c1a1.nq.gz
│   ├── 474e25fc1d9189e74f2ef3449209938c8867972f.nq.gz
│   ├── 4bc3bc1e41cc72e20fcf6ebef24d7a437a366854.nq.gz
│   ├── 4ea2bebb89d7dd89713df0ec08099bc22b60b54a.nq.gz
│   ├── 51320a380a9283667e3a577f43c46ab5b4f119d8.nq.gz
│   ├── 51bf8b2246f99bb6ace6a1d522b85b9a1e0960bc.nq.gz
│   ├── 53090c15e354c1c200a868f3818b85efe7e6a861.nq.gz
│   ├── 5afc283f7967acfacddef51af8005c0604bccc1d.nq.gz
│   ├── 5bd067d9a64d8ec2c13f39aa5820ff2ac39e26e5.nq.gz
│   ├── 61973408503a649b8cedbd74a2f998d44df7cfbb.nq.gz
│   ├── 6295a053870b338cee7add086cf3cd83bd243c5e.nq.gz
│   ├── 656cb293a82063327352cfb7f30bf1fa24e68b3c.nq.gz
│   ├── 66716170385505a1366109448e59b857657b9aaa.nq.gz
│   ├── 6bb1491e8ba9f2a9f26a21d31cfee5df05e418ae.nq.gz
│   ├── 6f10e5da2352a506497776ec422c5f659ef17d3c.nq.gz
│   ├── 6fc9d8a83609bc17cf9527fb8e1aaa05fddd3660.nq.gz
│   ├── 72fe9356fbe2ad620ada78edcddab1d19da9ed64.nq.gz
│   ├── 785d065e52ff7bf58d6aea1d5d8403b9bd6d390d.nq.gz
│   ├── 7aca40d4306d740cf74556fd37ed79c8946bf7e1.nq.gz
│   ├── 7d2565165c2c991dbbc0fb44f5f38c032438699d.nq.gz
│   ├── 7e098da9668ef4edda3f73d8a0d1ff4b3cd2836c.nq.gz
│   ├── 88c251cf78b3d15e35756308720bffa1ab555824.nq.gz
│   ├── 8cb7a953ccd1d57987c73f82c97aa18b6060cbec.nq.gz
│   ├── 93476add12f72c20edb6460d1abf74c62efb8eab.nq.gz
│   ├── 97390f16cd3a652beb242f67b08d390f868e6175.nq.gz
│   ├── 98bdee38ab0fe8e51764642fee9a2c2b92804cf7.nq.gz
│   ├── 9a6726def99a5eeb31edb700b98de5849f320d8c.nq.gz
│   ├── 9af31e3cf7a559f160da0dd19f01c20834138674.nq.gz
│   ├── 9fb6d80635949e02b6de44081445e88b900c16c5.nq.gz
│   ├── a1d2d4834b536825de7fdd21975981382e1616ea.nq.gz
│   ├── a2b2269e5813d82d02a4d495ef92ddb678300066.nq.gz
│   ├── a7c9cbd7d63e9ecd8e29100902ec081963dc8a5a.nq.gz
│   ├── a8b28de0620299177b7b7d7c1f8b112a5b8a79bf.nq.gz
│   ├── a96c8ce6c4d00f0ff544a423e31dbd14fb8932ee.nq.gz
│   ├── b1b8e8398d6484582d395927409e445db5fd0a45.nq.gz
│   ├── b7b587b22d56a336c6ab0a93e12ebf26f5a68356.nq.gz
│   ├── b9599baea5534c76122b8a7cb5cb876fb4474d7a.nq.gz
│   ├── b9e77ff0a730acdf43cf652797478140577deb74.nq.gz
│   ├── b9f039111bbe2ce8b5d30cafbc41ad3a6845737f.nq.gz
│   ├── bae16a07ac88112ea2a160fb4e81e66406ac60fe.nq.gz
│   ├── bced449a7aced30c870e20aaa39db07055a0c704.nq.gz
│   ├── c60e1b6ca6110cf03a2ffd1efb24d4f0d2c3fd3d.nq.gz
│   ├── cc36d7bf8492d6375c9348274e443f7222a6886c.nq.gz
│   ├── ccc6713e35e1515ec1c085f1af0ca91c163ec280.nq.gz
│   ├── cf2ff7e25eb766001ed000a5dc61cf05c7fd0b7a.nq.gz
│   ├── d167160c5e51d7cfa75f0d91e06870111ead2be8.nq.gz
│   ├── d2d534216d511efae8f585709874fc518f4410fb.nq.gz
│   ├── d42f582a9d50adcd47754a45e4472091f0f4cd82.nq.gz
│   ├── d5030045febae5ec8716332acda1a4170ad8c447.nq.gz
│   ├── d98b8874ecc9c65df605965d2c73f536c4906fb4.nq.gz
│   ├── dceb50b589c9c56002a91f1a999138f7935625d0.nq.gz
│   ├── dfeaa9ed32e86893c2bcffdf278abd6db8cbfdd7.nq.gz
│   ├── e1aa1f0a19a51e541d03cab5ebb33453652430be.nq.gz
│   ├── e6002c949a625a0992e0fbaf61df978d32497419.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b434d448a8b47c1758e88bae4c541c54e1978b.nq.gz
│   ├── ea5eb025268c9e4e76be0ddb7515d2030d60a762.nq.gz
│   ├── f9a6a65c7095f6876333dee68563c2df229431a9.nq.gz
│   ├── fb3b825296af71806ae207c4a350252a68882dcb.nq.gz
│   └── fd71e06dcfbe9c232a394b876628b4948994c1b2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 11785e00ea3e01b4eb57a8031843e215fe171c2a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[vimalloc/flask-jwt-extended](https://github.com/vimalloc/flask-jwt-extended)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
