# Repolex Knowledge Graph of simonw/llm-anthropic

RDF knowledge graph data for [simonw/llm-anthropic](https://github.com/simonw/llm-anthropic), parsed by [repolex](https://repolex.ai).

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
rlex download simonw/llm-anthropic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b66cdf112c7d9da30edff581c37de64d796e617e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b66cdf112c7d9da30edff581c37de64d796e617e
│           └── chunk-001.nq.gz
├── blob
│   ├── 13b0cf0ba1cc14df2e0649f636ae4282da1f5b4e.nq.gz
│   ├── 1af699141baa0d7ba25c03856e0d0e07ddc943e6.nq.gz
│   ├── 22a73c2bf9505cbca1fa481b605d17b2280e7a18.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 298ada2dc7da3fa7b855c8dd8103c70e0a6737e7.nq.gz
│   ├── 33e8692b8b2f99b37b7e9e517b18fdff3650a556.nq.gz
│   ├── 3ac55b002212e49a4088ded3b0b62f242a531950.nq.gz
│   ├── 3c56e3fac431cdc0ed36f0ea44a7d2fed3749e16.nq.gz
│   ├── 3debec16d33e0bee2a7bb0803780aa630394cf24.nq.gz
│   ├── 408bf8d0df8552cb6d40aed2877302a8e806a563.nq.gz
│   ├── 492d76143e78534c61a2f72a9bb92f9fb6fc8445.nq.gz
│   ├── 4d4b63eedf2fa94d4eb336b1ce20202da4180db6.nq.gz
│   ├── 4fe19d0bcc008c9bf9ff566ce67722fafdf0c59e.nq.gz
│   ├── 5417c7ee1e58e8dfc4192fcd2ab49ba21331b685.nq.gz
│   ├── 6006279c60fcb0ead3234bde68fb286e84ac49ca.nq.gz
│   ├── 67da6ad463055ab5ed7cc999c692e064a291f73c.nq.gz
│   ├── 69761b7f665d4018f5bd332b437da3a631714b0e.nq.gz
│   ├── 74afc5b48e3420bb2f060a974b4dfacaa0648d23.nq.gz
│   ├── 780642ce7de60d23e9bc6a8443cac7a2657bee95.nq.gz
│   ├── 7d5538cad5f6a19b3e2d34ea06f94a3e5ea4bdae.nq.gz
│   ├── 83132029b1c3dc8996273c81cd04a752d90a2dc2.nq.gz
│   ├── 8ae843516cc1afbd25af71f95d1dbe547b073807.nq.gz
│   ├── 9166bbebbc22dcec0bceb2c3f59fade0a880fdb4.nq.gz
│   ├── 99311c73841cfdc4f94fb3e04d94e84471cbf697.nq.gz
│   ├── 9b3a8fc76dafa3d1831fa35cb3a4eeca192cb553.nq.gz
│   ├── a43602bea848494d01ef8c5b9faa337621956c25.nq.gz
│   ├── ac57d3c970863bac5e3e3d11c94e79a770624e5f.nq.gz
│   ├── b01726b734977ffde342810c342eefb2e0123cce.nq.gz
│   ├── bc37f38a5a85b7b232440bd9e0a4fa7642e2d7f2.nq.gz
│   ├── bd4edd67feacc64a89d5d32067e6824cd775dd29.nq.gz
│   ├── bf2221b7c043749c85fca46d19e6b2a236562927.nq.gz
│   ├── bfe71d21d767cf834aab0a1418945b370d7b23f4.nq.gz
│   ├── c1d8fc69fe4d7b8a35dfdab2d14250a1d1a7e53d.nq.gz
│   ├── d0d5ce3ee8fa6494d61b4f902ee7d8de943e1b36.nq.gz
│   ├── d2468ef2d5829ee84d3dc82e510d40020111dc9e.nq.gz
│   ├── de8b12ca07a2bd52c7b9d0840be55cf39f3a5b60.nq.gz
│   ├── e2e4b53d2ee1626c24474e4c93b8d6b41e18340d.nq.gz
│   ├── eb6d19af01791c8c63f7eafb5eb27d42d2d4de92.nq.gz
│   ├── f3872bfb296631f740bc891aa8952eb51ce28c97.nq.gz
│   ├── f40d655dd459b688ec29d6602702fcc7ad6ec50d.nq.gz
│   └── fa946d06a5b8ffb24a24dd35cd5c4c4180ded243.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b66cdf112c7d9da30edff581c37de64d796e617e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[simonw/llm-anthropic](https://github.com/simonw/llm-anthropic)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
