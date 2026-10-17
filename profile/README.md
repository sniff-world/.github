# Sniff

Sniff is an open knowledge graph of dog biology. It answers questions about breeds, genes, diseases and variants with the source and sample size attached to every figure, and it says plainly where nobody has measured something yet. Owners can add their own dog and get a free page built from what studies of dogs like theirs have found.

Sniff shows the classifications that curated sources publish and cites them. It assigns no pathogenicity to any variant.

**Use it**

- **The site:** [sniff.world](https://sniff.world)
- **For AI agents:** an MCP server at `https://mcp.sniff.world/mcp/` and a REST API at `https://api.sniff.world/v1/`. The package and setup notes are at [Sniffscore/sniff-mcp](https://github.com/Sniffscore/sniff-mcp) and on [PyPI](https://pypi.org/project/sniff-mcp/).
- **The dataset:** the Sniff Atlas on Zenodo, [doi:10.5281/zenodo.20566358](https://doi.org/10.5281/zenodo.20566358), CC-BY-4.0. The concept DOI always resolves to the latest version.
- **Field infrastructure:** a facts-only export for knowledge-graph stewards at [sniff.world/federation](https://sniff.world/federation).

**Repositories here**

- **[coverage-frame](https://github.com/sniff-world/coverage-frame):** the CoverageFrame LinkML schema family. It records, for a bounded set of questions, which ones the sources answer, which they leave dark, and why each dark one is dark.

**Corrections and contact**

Found something wrong? See [sniff.world/corrections](https://sniff.world/corrections/), or email matt@sniff.world.
