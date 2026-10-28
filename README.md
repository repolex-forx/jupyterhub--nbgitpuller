# Repolex Knowledge Graph of jupyterhub/nbgitpuller

RDF knowledge graph data for [jupyterhub/nbgitpuller](https://github.com/jupyterhub/nbgitpuller), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/nbgitpuller
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7dce435044a769dfab00ed1214a7851f0b60797
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7dce435044a769dfab00ed1214a7851f0b60797
│           └── chunk-001.nq.gz
├── blob
│   ├── 036967c969a7aa8d7800c05425941d9a03b7c59b.nq.gz
│   ├── 0d736c6ccf860629ee5094bcf71dc7e6730b24eb.nq.gz
│   ├── 0e686bbbae4a268052abac77f44b24ea6865b969.nq.gz
│   ├── 10e8d1252ddbf4ad911706c22b4557cd9a82385b.nq.gz
│   ├── 11ac2acddd0c1841360574d45077d3d81fb8541d.nq.gz
│   ├── 13559e688157ace807d25939326a32e4b8018f77.nq.gz
│   ├── 2274048c3cd9d05bf14952674d4367ea75eba99a.nq.gz
│   ├── 2aebc6ea986eb7e1f29c2b3397369b805f36b1a1.nq.gz
│   ├── 2d61435c37e209e013b2230812c226a9f3407b85.nq.gz
│   ├── 371667be9124fcda8d92e2de484cebc9c08e3810.nq.gz
│   ├── 3b788daecb3008d01b624ade8800699be6f0d1b5.nq.gz
│   ├── 3fd434226d381b1eee584992f23e3d48b642dc8b.nq.gz
│   ├── 49bfef9e6192a59ac2cba5a7954cfc40ef1d5c08.nq.gz
│   ├── 55189ab109823e25dba059d8cfe0970a54a7e927.nq.gz
│   ├── 57093103d87665bbb4c3f54dd814866e4f7a18a7.nq.gz
│   ├── 57d5c17da3901e1934e5ef6bf5422154f3b88c55.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 6249df5322d87f39a858f8f6255dc7782549bcb8.nq.gz
│   ├── 70f1bd99ccc895ea447ea379d30480629247464e.nq.gz
│   ├── 7326b4fd2610f5e36acd411fa0bc5b23b5397af4.nq.gz
│   ├── 820cbabd34f6eb6c6341476a69f4b02aeacf690c.nq.gz
│   ├── 8b6decc68a3a1773c551d245281f483c4e6f948d.nq.gz
│   ├── 91764e9e444ca68b90fbdcf257b54cdf00da961d.nq.gz
│   ├── 9376e3b3b44781439e91e1f98426e16472655f97.nq.gz
│   ├── 94c8a866cb541b74e638bd336e4f4e30070a102b.nq.gz
│   ├── 9cc05fa64dc982f875e67a93829914f0dc691c7c.nq.gz
│   ├── 9e80110806f571346d42e62a76415b14040a7b4a.nq.gz
│   ├── a05006b7ba5bc6b90cc54700dbe70fc56ca4e7fe.nq.gz
│   ├── a2e0c180ab7b0a3ac59061ac10d544792e72fb66.nq.gz
│   ├── a51fe33b9ab0ab3053e00c70c1ce70326e57def7.nq.gz
│   ├── a5c9cb3a3e5b737d261ff393830cdc044c098157.nq.gz
│   ├── a5e268cb43139917f157720a986dfc03447942e7.nq.gz
│   ├── afb2ba0d4886fd62b49f0a2fa95efe587842dac7.nq.gz
│   ├── b165d7e52a751984d8fe853e29f828d19ff8d31c.nq.gz
│   ├── b64c63b229811dce0a25a923a129f0be77f5baf3.nq.gz
│   ├── b7a54c3fa37f256ac0f1160806bbe55bdfb801bf.nq.gz
│   ├── bb84e8e117777942568bfb0f71edbd2dbe2c4f4b.nq.gz
│   ├── bc3be83df93d7e6a80fc60b70914d45efda9dd3c.nq.gz
│   ├── bf505a2b091aac7857cbd2a185ad64243aad7217.nq.gz
│   ├── c21428a10a58d40ab448a5ca10d8125121600d8d.nq.gz
│   ├── c370278c60ad97c26572e00339316765cf3d4904.nq.gz
│   ├── c3ea9a001b6776add4487497db2a0c0dc279ed8f.nq.gz
│   ├── c680c87e348b2fc0d8af74c68b99f73d86bfe5b9.nq.gz
│   ├── c7c4ca7d4a41278d33bf19a3f0869cfb162630d0.nq.gz
│   ├── cfccad6042e746e885cc2fca0a8fd8ecd29dee9f.nq.gz
│   ├── d4401886ff9ff72311c6116acb42b7d25ad7a904.nq.gz
│   ├── d52c152156ed3a8d78bf990d7cce42273f740e1d.nq.gz
│   ├── df7be3fc4747f9cc9aa3a9525b4b8037a8450f3a.nq.gz
│   ├── e74b0547fdb9d0039c9c362756f65f068bc3c114.nq.gz
│   ├── f21246f9ae1a316d999421c12ec4db9accb4d6b4.nq.gz
│   ├── f636d3246d2a7fac2b9dca10558f67f4c2a30a8d.nq.gz
│   └── f980e760b6f0d3cceb7d08da4fdf373e6feeb9df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7dce435044a769dfab00ed1214a7851f0b60797.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[jupyterhub/nbgitpuller](https://github.com/jupyterhub/nbgitpuller)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
