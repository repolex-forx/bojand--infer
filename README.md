# Repolex Knowledge Graph of bojand/infer

RDF knowledge graph data for [bojand/infer](https://github.com/bojand/infer), parsed by [repolex](https://repolex.ai).

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
lexq download bojand/infer
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4256ea07165a9393186b6c190541fac4b5e6f9f5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4256ea07165a9393186b6c190541fac4b5e6f9f5.nq.gz
│   └── repolex
│       └── 4256ea07165a9393186b6c190541fac4b5e6f9f5
│           └── chunk-001.nq.gz
├── blob
│   ├── 084a7d1f8d13f74530095ab463c4b0b3bd809d97.nq.gz
│   ├── 088ba6ba7d345b76aa2b8dc021dd25e1323189b3.nq.gz
│   ├── 08e5982500e4eea12e22110d5132494aa98be94a.nq.gz
│   ├── 0db50fdc51dffbbbd03d57ab74100e3c9da962e6.nq.gz
│   ├── 11f731308a8cdefc4ddea6cc914289211087be89.nq.gz
│   ├── 1248ec7972a7d3601a0d0ffa173e2b3c1d437483.nq.gz
│   ├── 150715f51f753c17b9da78f95d9b59b1efef9ae9.nq.gz
│   ├── 17d0f12b8b8dc58ed48627f7ff17a81b770cffe4.nq.gz
│   ├── 1a0e6e93833c9014da11f0f76cf834c74dc9a56d.nq.gz
│   ├── 1c14cbc3afd19047167b2eb7bf8e5fec18b5e7fd.nq.gz
│   ├── 1cf68668eb18dc6243dadd588556a3e06c1cb0b3.nq.gz
│   ├── 260f1a89af973c4e517153e574b309a8be4d217a.nq.gz
│   ├── 2b21dc49441acf9832e49e083c0259b25b940aae.nq.gz
│   ├── 30ed410dd58a8881b712975288d10d3fbcc4b199.nq.gz
│   ├── 32b43bfc6a64bc46ebe0e58b23ec3aeec80878d1.nq.gz
│   ├── 353da1cbf057e94315beb8a1c55b32055fbf3e8e.nq.gz
│   ├── 360d8833784e724a4af60e406606a9e37f9a1b0a.nq.gz
│   ├── 38f47e6e1d8f82a999c85a0fcad45c9b5774e359.nq.gz
│   ├── 3e85bb83d1ed39496762f8a0c6157c1d4a5dfe2c.nq.gz
│   ├── 3f71b3b16c01614fd475977c31e36946d76c92e6.nq.gz
│   ├── 3fa72285a41fd43c0bfdc14e3b2fe94731facf78.nq.gz
│   ├── 4724d8fae5af1ffac000018d2cdafd4c5589c85a.nq.gz
│   ├── 48fd604675b89868d958c51b8fa06206859edfee.nq.gz
│   ├── 49100b268ce301f8f5cf6ad42c4c259b977632e9.nq.gz
│   ├── 4ff0f8d46c666b757a4bd5c6403813382b75092f.nq.gz
│   ├── 512f98bd72f1d1b0430f51fd3fa1412d9ad6260a.nq.gz
│   ├── 536cd5da3d2a36fb3e51c30f1a5b1715d0bd3fdc.nq.gz
│   ├── 57a04c7b6890ec510e8d77178167cce7616fc518.nq.gz
│   ├── 588aa079e90b16ff98e0e5804cfac789e04f6f75.nq.gz
│   ├── 59e55bb9322a453215efa4f28a8d4d15b1c91d3e.nq.gz
│   ├── 60297f747c51f69723b0e2f2cc66ee430c847204.nq.gz
│   ├── 635bcfdd83ca6b9f80a59db163b4bec51ddfd831.nq.gz
│   ├── 6399cf6ffbb27a3923cd70c071db48b1c2cacd38.nq.gz
│   ├── 67565757fddc8e9e6e672c7e6ce15b614813faaa.nq.gz
│   ├── 69957eb044d31772cf721260fce2b06a7ce0961e.nq.gz
│   ├── 69f71c7525ba7d0d02010b3cc5b258df0313e7c8.nq.gz
│   ├── 6a9eaa88ff654dabe53864d0ee8f53e138819348.nq.gz
│   ├── 6fa417a941ec167b4e3e08c4cb1d29e1d8f118ad.nq.gz
│   ├── 73cfed42fc85dfe55710ff588f55c3478a85f187.nq.gz
│   ├── 7473f5170e2457d617395e02494051d6f9811b14.nq.gz
│   ├── 77576226aabec8cede72a836b7d25a3a20624c34.nq.gz
│   ├── 7789533af1ed849a8982345f72dc103ec926ca4d.nq.gz
│   ├── 77cff72f873ec209961c72f3b0f55c12536eb706.nq.gz
│   ├── 7848269b9abb0c5a6980b3f48468f22cd20b407e.nq.gz
│   ├── 79667cdbbed2993589eebadd3b929143dea8c80a.nq.gz
│   ├── 7d8808fa3374ee6bd06a2f1f6afb5bc6beb9264b.nq.gz
│   ├── 7f3983a39ddd578eb08d311deefd69d8ebfbb1c4.nq.gz
│   ├── 811cd9b9d47931770e2e39974dfb2656a5111d63.nq.gz
│   ├── 84af1b95f81be8ddb3112354fefb295ba50edda2.nq.gz
│   ├── 8af2b17fb89116898cf0b927bc7b22d5cfdab2ca.nq.gz
│   ├── 8c0369018e4cb5d2177d8df8f1c78e48565f1195.nq.gz
│   ├── 8dded037998bba953dad0c41a20aa0f885962da2.nq.gz
│   ├── 8fd8eb7c51823bb9569ab43fdeb783d8b3576df1.nq.gz
│   ├── 90bd36918b4771959e628fa1beb5563566b54cf3.nq.gz
│   ├── a24483c6bd9db789836ea8e8656b1078ff54b23f.nq.gz
│   ├── a52a6f3df012a24001f9d3d66d0cabc7a4ac8946.nq.gz
│   ├── a78c5f606bc6e1e73496b614f4063355dbb72764.nq.gz
│   ├── a87a20eb27c2f9aa5777e279f4c6f72c2deaa628.nq.gz
│   ├── a87decceb4706ef3d8b3d05ab454afe724b769f1.nq.gz
│   ├── a9bf588e2f88457fdf73ac7361ef1d596fb81453.nq.gz
│   ├── aca5e1c6b29bee3cb844648427d697c04a6af0de.nq.gz
│   ├── acd86df69abe66162e87ee95a981dd544c83d565.nq.gz
│   ├── add645bb77d45cdfa47505daad0c81c75e289d5b.nq.gz
│   ├── b0348d5e4c70e5bf8247f63a7f48194b2f1d1aaa.nq.gz
│   ├── b07c7c4a5d27ff4b5b5fe9f3f1ea03345c75340d.nq.gz
│   ├── b4d4906190c0e4525435edd49d5cd38ffa3f08dc.nq.gz
│   ├── b67d8acb159bd686d304d85a224dbd0541b19fdf.nq.gz
│   ├── bc0a1de9888c62492fd601497b7c83ed35140bb6.nq.gz
│   ├── bd32231a3462be05e01cf1f11abb491232fecaf4.nq.gz
│   ├── c0e475142402cae1ad8e78ed6545057ec6db12f7.nq.gz
│   ├── c60071ae2b7d9bcac59daab35e8d6fbba4caead6.nq.gz
│   ├── c8d63de4bc3819a721cb07d08510d33bacd4b588.nq.gz
│   ├── c8f7d95a8461c9074a319454da4a2be509c4c120.nq.gz
│   ├── c994a851d891ea3c2965ccf99228ad193c216761.nq.gz
│   ├── cfd6de3587672bcb3fd388d64cf6aa940d6a84d4.nq.gz
│   ├── d13f908cc073a24465d293562d8bc6427d7d62e2.nq.gz
│   ├── d1b81012098d0a334f3a2dc48272a5b89f18ebc8.nq.gz
│   ├── d3ab91e3088b8260e83434af0661239c73f383ce.nq.gz
│   ├── d80548dd6a9f42d894b0ea0a6acebabd59104aed.nq.gz
│   ├── da946da5290ec1ed99392c1a56ad5b4e95baa2e9.nq.gz
│   ├── dbf0f677fc0389034c53d75194ab52410ce2f835.nq.gz
│   ├── ddd256ac1920c36f51fcdc62ec661795741d942d.nq.gz
│   ├── dea98937ddecbe5374445753339f44286c8c62ce.nq.gz
│   ├── e25b4fd735b642b85d06798aab6e4d9026d3a14e.nq.gz
│   ├── e33a51efb6e534f3a97a74ea02a82775aff4c0e6.nq.gz
│   ├── e5955bf3df171f91649ae0815e96efa171f72f0d.nq.gz
│   ├── e62a4afd461e52421f481120d08dc73702a2d5f2.nq.gz
│   ├── ea1b8bd6925d3d5ace1f0441557b80d0ac43d4e4.nq.gz
│   ├── ecb84531109e2155d78b91b8a2e7adc10b134e71.nq.gz
│   ├── ed07fdb1f0b2c42888ce98149069fe1e88b955ba.nq.gz
│   ├── eef17acd19aecc8e58422de9a52138fe0ba29945.nq.gz
│   ├── f161727f2ba2a37771761750f516f21169641b8c.nq.gz
│   ├── f7edc4241548dca7282059feb541b3f19f3cfddc.nq.gz
│   ├── f8e5fd1c8706a8adc6e6ff9934e4494671d14f0b.nq.gz
│   └── fee238c94dacc58b49a9ab09458d7692dffebbff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4256ea07165a9393186b6c190541fac4b5e6f9f5.nq.gz
├── filetree
│   └── 4256ea07165a9393186b6c190541fac4b5e6f9f5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 105 files
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

[bojand/infer](https://github.com/bojand/infer)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
