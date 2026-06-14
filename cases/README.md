# VirSift Example and Test Cases

The `cases/` directory contains repository-based FASTA inputs and usage notes
for demonstrating and testing VirSift workflows, including upload, parsing,
dataset activation, filtering, deduplication, visualization, temporal analysis,
and export.

Included use-case files may include:

* `All H3N2_20250918_070704.fasta`
* `HA_test_copy1.fasta`
* `RSV-B_for_filtration.fasta`
* `usecase.md`

These files are provided as software use cases and test inputs. They are intended
to help users reproduce interface behaviour, exercise parser logic, verify
filtering and export functions, and explore example analytical workflows.

## Intended use

The files in this directory may be used to:

* Test single-file and multi-file upload
* Confirm FASTA parsing and metadata extraction
* Activate individual or merged datasets
* Apply sequence-quality and metadata filters
* Test exact-sequence deduplication
* Explore the Surveillance Observatory
* Run Molecular Timeline workflows
* Generate Analytics visualizations
* Test FASTA, CSV, JSON, ZIP, accession-list, and session-log exports

## Important interpretation note

The contents of `cases/` are software demonstration materials. They should not
be interpreted as epidemiological case counts, incidence estimates, prevalence
estimates, or a representative surveillance sample.

Results produced from these files describe only the uploaded sequence records
and the metadata contained in them.

## Repository organization

VirSift uses `cases/` as the main directory for test and demonstration inputs.
Do not create a duplicate `examples/` directory unless it serves a clearly
different purpose.

Additional use-case instructions may be documented in `usecase.md`.
::: 
