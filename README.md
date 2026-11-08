# Repolex Knowledge Graph of canonical/openfga-operator

RDF knowledge graph data for [canonical/openfga-operator](https://github.com/canonical/openfga-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/openfga-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1426008dd3c4fa4a7b9199f9e5198cd0b8fb7725
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1426008dd3c4fa4a7b9199f9e5198cd0b8fb7725
│           └── chunk-001.nq.gz
├── blob
│   ├── 004f3e2586105f5fd402aa7dbc826c7544583b9e.nq.gz
│   ├── 04dc0ed32aa2f03443f01185e239ab85556410de.nq.gz
│   ├── 07b41fe4e9d7ce24f07b5886cb85f3a2c9fc10f9.nq.gz
│   ├── 08fa8aa15f5e39a06283c2c6104cba6ba2e42801.nq.gz
│   ├── 0e514e7272e1167a5c34d51cd4cf04a17dc926b7.nq.gz
│   ├── 0f0af05f53576552be239ee1d6119d2ff35c358b.nq.gz
│   ├── 166bb70f891efe5f46673da9763dc00f1866d8bd.nq.gz
│   ├── 17d1f431ff2788d753dbb7b9aa19e6769c74cb59.nq.gz
│   ├── 1c21e6742ea0df85d46378e2fa55a8d3684b8b35.nq.gz
│   ├── 22327531ca24f7d7904b9507ed280d8bfadaa4a5.nq.gz
│   ├── 25c2d37082113aa54ad23de757b0da185417b88a.nq.gz
│   ├── 270968a99b348122d2ae58472350de6a32bc6752.nq.gz
│   ├── 2b5bcff9e842953ff98a0733b4f6acfcde5d7f09.nq.gz
│   ├── 32344bd49baaa52a2fd653abfb084a511e164f84.nq.gz
│   ├── 328eb51ecf6ca089ab523f23558758aa6615b6fe.nq.gz
│   ├── 32cf880e73848c3723241741fa69e0bc8acd50ad.nq.gz
│   ├── 342f782c9dba6a4412f21901be216a17a79ff261.nq.gz
│   ├── 34dd026407a968c94b3eb7c22bebae0d6d16ca58.nq.gz
│   ├── 361e20773b201dff1cded3ebb993457948c85f87.nq.gz
│   ├── 3e49673abc1af4451656bbc630a4b31f4b38ccfb.nq.gz
│   ├── 4199ca40d4a8f50827a42d5dfa80993c52e5bed1.nq.gz
│   ├── 524d8ae96d80b582acaf9541b4983f09ffe7064a.nq.gz
│   ├── 5390de1bb9b56670c86aaecbe4840e3e0afec642.nq.gz
│   ├── 53c460efe1eceaddb08b6490f6324de9a446bf8d.nq.gz
│   ├── 5baa983a6c37c7c1f04424229cadcec44510410a.nq.gz
│   ├── 5cbaef207b2948da44fda58f8c316c203c010b64.nq.gz
│   ├── 5d7aafe6ffe6be4860181f1f00218be7e192c79a.nq.gz
│   ├── 5e7d2734cfc60289debf74293817c0a8f572ff32.nq.gz
│   ├── 61470520c1560e63fe52b603711dfccfeb4aa5bb.nq.gz
│   ├── 651ef36e445cc0293b2a1149ebb80ee8a633d09c.nq.gz
│   ├── 67a6c09dae83f7838357592086eafdc0f31f4191.nq.gz
│   ├── 6b5d157fce5aceb9c8083587c4462eae0a909b5b.nq.gz
│   ├── 6c5443bc7a4f32e3749fdad2486516a172fc4fb2.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6f8afdadab1da22097d68463a403190b3b6290fd.nq.gz
│   ├── 70037073b3726a1abe07c1ef565ddf5caf22ae8d.nq.gz
│   ├── 7141a3683d5579eaf53d3c494a6548e051c89328.nq.gz
│   ├── 74d2ea6440b41276a79f19f5349051a956582023.nq.gz
│   ├── 7924675ea427b51e6904ec481ef40b35d8d08e17.nq.gz
│   ├── 7abd5c55735ee785d54efaae4ace5edd2308d3d6.nq.gz
│   ├── 7bbdc13c1e8825645b2e9f07ed8afdd6fbf0d98a.nq.gz
│   ├── 8081313721ea4b171d655cba6c51ea6caa71d323.nq.gz
│   ├── 80f35e6619d34c08cf3bde0eb3f2da4653d690e1.nq.gz
│   ├── 815a71213317b7577fbd9edfc98e5a93510acdf4.nq.gz
│   ├── 82b99394f00ca7ecde9d51449117fa9c75b4b124.nq.gz
│   ├── 8a5f4aab7b4817cfc40748bc55fca58ec1ca0764.nq.gz
│   ├── 8d9bcda3c9e30b07440aad71f7bbbf603c28bbe0.nq.gz
│   ├── 914006185469ab9ce3b2b569e03fb3191893a9ca.nq.gz
│   ├── 95b9aac118a0614077faa56b779a394c14c2061c.nq.gz
│   ├── 9733a5ef090af62d2e662e504e58b1de8e61d694.nq.gz
│   ├── 9935650cb74e9dc8da112f46680f718a42ff660b.nq.gz
│   ├── 9e62923b7e9d974e8ab46a7f06b048e6da4504dc.nq.gz
│   ├── a21c2fe5f4549e9da1b71fefb7eac8f462b457e6.nq.gz
│   ├── a26d707f9b15d4a29e84370703fce40dbdb46448.nq.gz
│   ├── a477da39fe354b9c9f7dfa140f4129448b4d9a29.nq.gz
│   ├── a716d284e30eade0a6217610d98df99609a012cf.nq.gz
│   ├── a79e5d4343e09bc07819c1a444ef89d509067388.nq.gz
│   ├── b0432912a2ad0cb5e1d2a804a4c9268e2bb0a66f.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b5afac33349517baf20c5ece72a5d4766155d2b9.nq.gz
│   ├── ba5f0abfd09050ed8ca421f7bccafd0942a89422.nq.gz
│   ├── be80e0a16587454e90662ae3e817984f0fec8c71.nq.gz
│   ├── bf763f55a797fb2a769cdc4ca9f0cecc9ed1ca90.nq.gz
│   ├── bffb011d9a1a62bb7e52f9b357445a3e4d69439a.nq.gz
│   ├── c5e51651b20e547b28a01bfb84369ddb76171bc9.nq.gz
│   ├── cecf27baf607209432b11a1ab9e27e330d662e33.nq.gz
│   ├── d3cf0ee9dae56c2200b3a9fdf5c8d62f17f6c87b.nq.gz
│   ├── d45673d0ea5778c3ecccdf5bb0280992ccbc2ba2.nq.gz
│   ├── d5c2aa1692cb82028dac4c84b5eb6c515894d785.nq.gz
│   ├── d933e19ffc2c0a3342edf06c14cbcbff6114c136.nq.gz
│   ├── d997d37ef2b3ac97f96ed7edbbf1ab405d3f0722.nq.gz
│   ├── dba9664cb508c920a94ee5ccc0d27b0746151f5a.nq.gz
│   ├── e08599ba7d67ad9daa435c507d7c31f2c318c6ff.nq.gz
│   ├── e08cee0d9148619f1b7f57d15f4e739f28ffb8be.nq.gz
│   ├── e58180c793f891a5351e5db562f9f688c420c979.nq.gz
│   ├── e59d5cbfaf5502d4f596e301ec26535729687455.nq.gz
│   ├── e630d26404adfcb5080d8e76f8799e5cfb7606ff.nq.gz
│   ├── e81e59a4479885d10ea3700745272d1ed4a80b1c.nq.gz
│   ├── ec997600c20ea6ac55069d6546ba9f88adc651df.nq.gz
│   ├── eccb38dc85d257a8ed459b997295d85f3755e512.nq.gz
│   ├── ecd315fe4319f69cf5da1e3559842b9ac449fc49.nq.gz
│   ├── f07980f8f6d9215cc68a6421fda9cb15c37d588e.nq.gz
│   ├── f6f5c72adbb3cb75bb26ed8f8263910c1ab49cd7.nq.gz
│   ├── f7c3ab704e27b756a97bbbd63eab7a7685ca0de7.nq.gz
│   ├── f7f3bde4196f1e3514c601ec0c0b880e8c75d2fa.nq.gz
│   ├── fbc09860b1a257b5f0335d17e8d3882b16938ba4.nq.gz
│   └── ffeec6e52ce561b3043a2d878cab6f59201e8a62.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1426008dd3c4fa4a7b9199f9e5198cd0b8fb7725.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[canonical/openfga-operator](https://github.com/canonical/openfga-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
