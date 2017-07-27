## Abstract

<!-- Context      -->
Within computer science engineering,
research articles often rely on software experiments
in order to evaluate contributions.
Reproducing such experiments involves setting up
software, benchmarks, and test data.
<!-- Need         -->
Unfortunately,
many articles ambiguously refer to software by name only,
leaving out crucial details for reproducibility,
such as module and dependency version numbers
or the configuration of individual components
in different setups.
<!-- Task         -->
To address this, we created the _Object-Oriented Components_ ontology
for the semantic description of software components and their configuration.
<!-- Object       -->
This article discusses the ontology and its application,
and demonstrates with a use case
how to publish experiments and their software configurations on the Web.
<!-- Findings     -->
In order to enable semantic interlinking between configurations and modules,
we published the metadata of all 480,000+ JavaScript libraries on npm
as 194,000,000+ RDF triples.
<!-- Conclusion   -->
Through our work,
research articles can refer by URL
to fine-grained descriptions of experimental setups.
This brings us faster to accurate reproductions of experiments,
and facilitates the evaluation of new research contributions
with different software configurations.
<!-- Perspectives -->
In the future,
software could be instantiated automatically
based on these descriptions and configurations,
reasoning and querying can be applied to software configurations
for meta-research purposes.
