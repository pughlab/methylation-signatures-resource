# Array-based Pan-cancer DMCs

- **Author**: This signature was assembled by Eric Zhao (github: eyzhao)
using regions from the publication
[Vrba and Futscher (2017)](https://www.tandfonline.com/doi/full/10.1080/15592294.2017.1412907).
- **Intended purpose**: For identifying significant hypermethylated regions
in cancer, with an emphasis on use in cfMeDIP-seq experiments.
- **Process of creation**: Marker CpGs probes from supplemental table S3 were
taken and joined to the 450K array manifest in hg38 coordinates.
- **Annotations**:
    - **probeID**: ID of the probe in Illumina 450K array manifest.
    - **probe_strand**: Strand of the probe from 450K array manifest.
    - **dmc_direction**: Hypermethylated or hypomethylated in cancer compared to normal tissues.
