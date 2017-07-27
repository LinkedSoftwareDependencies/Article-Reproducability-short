## Abstract

<!-- Context      -->
The scientific process requires reproducible experiments and findings
to foster trust and accountability.
Within computer science engineering,
reproducing experiments involves setting up
identical software, benchmarks and test data,
which often requires non-trivial manual work.
<!-- Need         -->
Unfortunately,
many research articles ambiguously refer to software by name only,
leaving out crucial details such as module and dependency version numbers
or the configuration of the individual components.
<!-- Task         -->
To this end, we created vocabularies
for the semantic description of software components and their configuration.
<!-- Object       -->
This article discusses the approach and its application,
and explains with a use case
how to publish experiments and their software configurations on the Web.
<!-- Findings     -->
In order to enable semantic interlinking between configurations and modules,
we published the metadata of all 480,000+ JavaScript libraries on npm
as 194,000,000+ RDF triples.
<!-- Conclusion   -->
Through our work,
research articles can refer by URL
to fine-grained descriptions of experimental setups,
completing the provenance chain from specifications 
to implementations, dependencies, and configurations 
all the way to experimental results.
This ultimately brings us closer to faster and more accurate reproductions of experiments,
and facilitates the evaluation of new research contributions.
<!-- Perspectives -->
In the future, this could then be extended
by instantiating software based on these descriptions and configurations,
and by reasoning or querying over software configuration metadata.
