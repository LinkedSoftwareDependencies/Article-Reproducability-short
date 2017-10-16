## Conclusion
{:#conclusion}

The core idea of the scientific process is _standing on the shoulders of giants_.
This not only means we should build upon the work of others,
but also that we should enable others to build upon our work.
Reproducibility is an essential aspect of this process.
This concept obviously applies to _Web_ research as well—moreover,
the Web is an ideal platform to _improve_ the scientific process as a whole.

In this article, we introduced an ontology for semantically describing software components and their configuration.
Publishing this information alongside experimental results is beneficial for the reproduction of experiments,
and completes the provenance of experimental results.

Through this work,
vague textual references to software configurations
in works of research
can be replaced with unambiguous URLs.
These URLs point to Linked Data
that exactly captures a single software configuration,
which in turn also uses URLs
to identify existing software modules.
We already made such module URLs and corresponding descriptions
available for all npm modules,
which we interconnected using RDF triples.
The same approach can be applied
to other software ecosystems,
such as for instance the Maven Central repository
of the Java language,
the RubyGems repository for the Ruby language,
the Comprehensive Perl Archive Network (CPAN) repository for the Perl language,
or the Python Package Index (PyPI) for Python.
The usage of Linked Data to describe the software and experiments
has the added advantage of linking different descriptions together,
which allows the answering of such questions as
<q>Which experiments made use of this benchmark?</q>

Semantic descriptions can serve many more roles
in addition to identifying and describing software configurations.
Since the descriptions are exact and machine-readable,
an automated [dependency injection](cite:citesAsAuthority DependencyInjection) framework
could automatically _instantiate_ the software based on a configuration URI
and wire its dependent components together.
Swapping components in and out,
and trying different configurations,
comes down to simply editing the configuration,
which can be shared again as Linked Data.
This leverages the power of the Web to simplify the reproduction of existing experiments
and the creation of new ones.
