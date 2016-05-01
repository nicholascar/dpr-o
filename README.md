# dpr-o
This Data Provider Register ontology is loosely a registry-based version of the [Data Provider Node ontology](http://purl.org/dpn).

It specifies a top-level [Registry Ontology](http://www.epimorphics.com/public/vocabulary/Registry.html) register, the Data Provider Register, which is composed of subregisters for dcat:Dataset, prov:Agent and dcat:Distribution class object. The DPR register must at least define a dcat:Dataset register.

The DPR register's subregisters may not actually function via Linked Data principles but must indicate if they do or not. This is to allow the definition of DPR instances that contain legacy 'registers', things like dataset catalogues.
