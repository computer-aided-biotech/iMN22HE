[![memote tested](https://img.shields.io/badge/memote-tested-blue.svg?style=plastic)](https://computer-aided-biotech.github.io/imeni452)

# iMN22HE

Genome scale-metabolic model of *Methanoperedens nitroreducens*, a
methanotrophic archaeon capable of anaerobic oxidation of methane.

This model is version-controlled under
[`memote`](https://memote.readthedocs.io/en/latest/). A history report is
publicly visible at https://computer-aided-biotech.github.io/iMN22HE.

|Taxonomy |Reference sequence| Reactions | Metabolites| Genes |
|:-------:|:---------:|:---------:|:----------:|:-----:|
|*Candidatus Methanoperedens nitroreducens*|[NZ\_JMIY01000000](https://www.ncbi.nlm.nih.gov/assembly/GCF_000685155.1/)|813|684|452|

## Model reconstruction

The draft iMN22HE was generated using KBase and ModelSEED from the genome
sequence of *Candidatus Methanoperedens nitroreducens*
([NZ\_JMIY01000000](https://www.ncbi.nlm.nih.gov/assembly/GCF_000685155.1/)).
This was followed by manual curation based on the literature and biochemical
information about ANME-2d and relative organisms. The reversibility of the
reactions was generally determined from ΔG calculation.

The jupyter notebooks at `./notebooks` are mainly about the annotation across
different databases of the reactions, metabolites and genes in the model.

## Generating memote reports

All `memote` commands have extensive help descriptions.

1. For simple command line testing, check out `memote run -h`.
2. To generate a pretty report of the current state of the model, check out `memote report snapshot -h`.

## Cite this model

The model in the publication corresponds to the [release v1.0 at github](https://github.com/computer-aided-biotech/imeni452/releases/tag/1.0).

> A link and the citation will be added here once available.

---

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
