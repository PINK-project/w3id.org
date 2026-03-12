# SSbD
This [W3ID](https://w3id.org) repository provides a persistent namespace for IRIs for the Safety and Sustainability by Design (SSbD) community.

## Redirection rules

Substitutions:
* `{VERSION}` should be substituted with a version number starting with a digit, e.g. "0.5.3". The `{VERSION}/` part may also be omitted in all rules below.
* `{DOMAIN}` is the name of a SSbD domain ontology.
* `{PATH}` is a file or directory path.
* `{MODULE}` is the name of a (sub-)ontology module.
* `{CONTEXTNAME}` is the name of an additional JSON-LD context.

Redirections to raw files in the GitHub repo
* https://w3id.org/ssbd/raw/{VERSION}/{PATH}

Redirections for domain and application ontologies
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION} -> published html or turtle file (depending on whether the request is from a browser or not)
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/turtle -> published turtle file
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/context -> JSON-LD context
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/context/{CONTEXTNAME} -> additional named JSON-LD context
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/inferred -> inferred ontology
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/dependencies -> dependencies
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/source -> asserted turtle file
* https://w3id.org/ssbd/domain/{DOMAIN}/{VERSION}/{PATH}/{MODULE} -> asserted sub-ontology

Redirections to the SSbD core ontology
* https://w3id.org/ssbd/{VERSION} -> published html or turtle file (depending on whether the request is from a browser or not)
* https://w3id.org/ssbd/{VERSION}/turtle -> published turtle file
* https://w3id.org/ssbd/{VERSION}/context -> JSON-LD context
* https://w3id.org/ssbd/{VERSION}/context/{CONTEXTNAME} -> additional named JSON-LD context
* https://w3id.org/ssbd/{VERSION}/inferred -> inferred ontology
* https://w3id.org/ssbd/{VERSION}/dependencies -> dependencies
* https://w3id.org/ssbd/{VERSION}/source -> asserted turtle file
* https://w3id.org/ssbd/{VERSION}/{PATH}/{MODULE} -> asserted sub-ontology


## Contacts
This space is maintained by the [PINK Project](https://pink-project.eu/).
Contact email: [contact@pink-project.eu](mailto:contact@pink-project.eu)

Current maintainers:
* [Jesper Friis](https://github.com/jesper-friis)
* [Francesca L. Bleken](https://github.com/francescalb)
* [Joh Dokler](https://github.com/joahim)
