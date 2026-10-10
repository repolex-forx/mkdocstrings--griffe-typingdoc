# Repolex Knowledge Graph of mkdocstrings/griffe-typingdoc

RDF knowledge graph data for [mkdocstrings/griffe-typingdoc](https://github.com/mkdocstrings/griffe-typingdoc), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-typingdoc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 685beab57f93219b1229f5bf9bb1a7165fff23f5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 685beab57f93219b1229f5bf9bb1a7165fff23f5
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0547e162fb248d8d12e04b10b5ff6d22463f7b41.nq.gz
│   ├── 0b9c7d942389dff3c925f720002ee1afd20b4640.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 0ea2cca50666c1dde509049579a66f7c67c8f439.nq.gz
│   ├── 18ff971dcc9b1b88c879af7f7ff960af2b681244.nq.gz
│   ├── 1d1878183207eaf8c52b81f93716fbcbb664cd90.nq.gz
│   ├── 2069eda4ea5937f3681630832bcecf5a37cba75f.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2de19f5dc3a04fb4d023ef8ed7909f16de3e4ab8.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4e83ed65c6e4ac0a7a800623cf440d69d7790b52.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 576a5af1d369882fc0cdd6cde77c8817358d5d56.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 5bac654ad8dd95df88adaef6f5f493635281ee39.nq.gz
│   ├── 5cc731ee918a3b3d7ef7123fb48a99753a043460.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 62df57374d0b48a75265058b46018a3be854592b.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8be98ba0b593e768acaa9f76cf4d5c357b866d0f.nq.gz
│   ├── 8f1ee72ee2d566da96d4497119183b6e8d362a32.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9cacd16199474a0b419a9d661b06164824ba61eb.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a2e013bc773a74c8bc9870d9e24ea6fcbd3e6099.nq.gz
│   ├── aacbe59290f38cae9a3b0f007ee63a5a9942c3fa.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b2914f0f3467680324749fb949da159cdbaf470e.nq.gz
│   ├── b2cfa4237699300f22eec18821c9f2b59ebb38d3.nq.gz
│   ├── b4ee6bd928710599b517e51345516bea47853ab4.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── ba654a65e68f7a60d48074e5482b74e4af574ea1.nq.gz
│   ├── c11d60a95ff316fc2dceac36fddffce44a50bf4c.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c5690efc2eea79c27a997dc98c220e8779a94ee5.nq.gz
│   ├── d49f14dbddf131a0b8d8a44a785116f8193936c1.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── dcb185285c33a40b9aeb0eeaad87c101834e0f93.nq.gz
│   ├── e1985e866e360b1ada872b873ed17b469ccc1495.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e48f6cb8b3829c0dde1d760e0443a6e246bc7f63.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── e91e3cb831f3551b495bd88c9ddf1bda27d94064.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   └── fcf4e32538f077e38fc34562ba307ea9f82edd1c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 685beab57f93219b1229f5bf9bb1a7165fff23f5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[mkdocstrings/griffe-typingdoc](https://github.com/mkdocstrings/griffe-typingdoc)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
