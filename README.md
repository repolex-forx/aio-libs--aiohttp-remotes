# Repolex Knowledge Graph of aio-libs/aiohttp-remotes

RDF knowledge graph data for [aio-libs/aiohttp-remotes](https://github.com/aio-libs/aiohttp-remotes), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-remotes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7aa3efd7ae1c9d92ce6ec9ad074c551c9568e7d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7aa3efd7ae1c9d92ce6ec9ad074c551c9568e7d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 00940ae393dd96b4fb6f3056daa12fc58007f0c9.nq.gz
│   ├── 0358eaaee8c97f65964d9627f587dff2378f513c.nq.gz
│   ├── 05e0832cc811d9c427a7c3c5de466e0d081f2b9e.nq.gz
│   ├── 0b83237ce65c772ac14a31b13a0f1933274c5fa8.nq.gz
│   ├── 0e7f18457383bd72e37137cd1029341205648564.nq.gz
│   ├── 1378ebab7d4a004bf627b33bcdb45681642c79b9.nq.gz
│   ├── 15e27edb12ac25701ac0ac21b97b52bb4e45415e.nq.gz
│   ├── 1b3bdad2ceffae91cee61b32f3295f9bbe646e48.nq.gz
│   ├── 1b955fb2921808563d5e840c0686e0ea7e1df7fc.nq.gz
│   ├── 208c0a5c468683f207b54b0113508dbe5f1b4c7f.nq.gz
│   ├── 208d4cd890c3183d946092ebe982738ade565061.nq.gz
│   ├── 2109507900ab7cc7e6174d531a21eb7277834540.nq.gz
│   ├── 2a924f1d6a8bc930c5296bdb2d5c2d3e39b04a1c.nq.gz
│   ├── 2a940a7da7c14e6a36901e83306849ba7efad4d4.nq.gz
│   ├── 2b83142b28b097f641d780d3dca75f0e94be1b5d.nq.gz
│   ├── 3496121bb64116e7938a9100840044cf9a251ad2.nq.gz
│   ├── 3589a1c9760f8b655f73542d76441f0352c239f4.nq.gz
│   ├── 35ae114ea66705ce57574d07db75215718da489c.nq.gz
│   ├── 3c0a4db0c41d5852bb18fc235541d3ed3d53c4ea.nq.gz
│   ├── 3ce00869b9df240433cd657db2ee64b85875ad81.nq.gz
│   ├── 45da79ec8443bd15a7f5a8a5401581cee031684e.nq.gz
│   ├── 4d91bcf57de866a901a89a2a68c0f36af1114841.nq.gz
│   ├── 5348e2c2d5f169a6b8754b0d7956d38698ca5b62.nq.gz
│   ├── 53f6a4525cd3db79b5076e557b0d4c89d810fcae.nq.gz
│   ├── 548e6cc50f3f9e41c3a2452d940fbf87816598b4.nq.gz
│   ├── 5756c8cad8854722893dc70b9eb4bb0400343a39.nq.gz
│   ├── 5b55f32beaca186f84cca115514f02cddbd1bbd5.nq.gz
│   ├── 5b9277b853494809c379ffdf12e0939a96b5bd33.nq.gz
│   ├── 60ba9785b8aa513be5e880293b0975bd700e6e3e.nq.gz
│   ├── 60fc9b877d27a55da64eba8ad640097041714123.nq.gz
│   ├── 61faf8cab23993bd3e1560bff0668bd628642330.nq.gz
│   ├── 6baf3aad8f862ef6d1e881a9f4289d2cba40d57d.nq.gz
│   ├── 6f0c4941eee6f887782893fe7b91734ce6df9d46.nq.gz
│   ├── 6fd535bc3ddb6b5c5126b20d6ef7079b0614e90a.nq.gz
│   ├── 7107cec93a979b9a5f64843235a16651d563ce2d.nq.gz
│   ├── 773bfdf151662e602c47799ebfe864f604ead626.nq.gz
│   ├── 82f2cc1a1cf846473b34fe6365a59f8a53428940.nq.gz
│   ├── 83467ce221dec2a502c52f15ed30d5327267f078.nq.gz
│   ├── 886511f6e10000ac9ae5ed5ac3dfb87b899414bd.nq.gz
│   ├── 8b3bd50b51b6fef4d6046ac677c691ecb85a5383.nq.gz
│   ├── 91752161bb6da7f2de5c1e3c97ba0e123be6fd62.nq.gz
│   ├── 99eb1e34bc43f6c1f876d98ada9bf1c7294da90c.nq.gz
│   ├── 9b7363c771492e88d0d5b1336985d045fbb06cdf.nq.gz
│   ├── 9cd7a219da33f8ab90061615cebff21f633d50af.nq.gz
│   ├── a858a410e4faa62ce324d814e4b816fff83a6fb3.nq.gz
│   ├── a875e7be8b2012218cae0d636ac57c1823be9c8c.nq.gz
│   ├── aa1b7c6890ce12f157c74a9114afc87e6cdae9ef.nq.gz
│   ├── acda6d0ec59aeff19827caa7c46d6ca6e8a8861d.nq.gz
│   ├── acee3b68efbbfb9de3bfa73fce2531380f4bd820.nq.gz
│   ├── b31f66465a67db8790f50573beeb3591f2154266.nq.gz
│   ├── b3ad7620cd87ccdee54331d648982bd3e7ac4d07.nq.gz
│   ├── b461e80845ef77bc693e7563be3e8b129f3a51cd.nq.gz
│   ├── b48e55304027102de13911ab2590d9f3758ab1be.nq.gz
│   ├── ba04dcf2827c10867916622ba83669d56fca4cff.nq.gz
│   ├── bf007341bca308779b9a1bc8cd0a0732ccfdcf93.nq.gz
│   ├── bf1a175b4162c512bcd7a834e24e39ed3251a635.nq.gz
│   ├── c6ed1856c0ac39f767380a7f0f8dfbe5ccbbcb1b.nq.gz
│   ├── ce8357599843c4f4b0605484479ed406c79476fc.nq.gz
│   ├── cfdf3bd683be1ee8d9270cee6533976fc72e6e40.nq.gz
│   ├── d1afcabc1524c81e83034f6a0ceac8f9e25135de.nq.gz
│   ├── d7440b065085e3179a564d27d0021577dfeb6137.nq.gz
│   ├── d96755fdaf8bb2214971e0db9c1fd3077d7c419d.nq.gz
│   ├── d9be53c373e9c596b96dd26235671ec3a2ee40c9.nq.gz
│   ├── dfbc0cbd512bdeefcb1984c99d8e577efb77f006.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea91134a41b712c5b38b9afec2505b9c9b376093.nq.gz
│   ├── f14d68c809d5bc485a3e074de0fc2e1005b5051c.nq.gz
│   ├── f2fc2747874e38d72f12812ed38418bc21935608.nq.gz
│   ├── f400db9b142dc47cbf218c56aa7d7cf11d164fe0.nq.gz
│   ├── f6a6a99e60ee9a5ce4d0922a3a82c6d81c1db7f2.nq.gz
│   ├── fa7b176ae3b9a8376f70f5cf3e88fd1492e159b7.nq.gz
│   └── fa9ed5dd884b875698843942a484e99bb00ddd30.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7aa3efd7ae1c9d92ce6ec9ad074c551c9568e7d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[aio-libs/aiohttp-remotes](https://github.com/aio-libs/aiohttp-remotes)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
