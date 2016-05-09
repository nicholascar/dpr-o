# DPR-O
This Data Provider Register ontology is loosely a registry-based version of the [Data Provider Node ontology](http://purl.org/dpn). 

It's purpose is to provide a single, Linked Data, entry point from which an organisation's various catalogues of web content can be found in defined ways. It is [DCAT Ontology](https://www.w3.org/TR/vocab-dcat/) and [PROV Ontology](https://www.w3.org/TR/prov-o/)-centric in design given that it focusses on datasets catalogued online, their distributions and agents. 

It specifies a top-level [Registry Ontology](http://www.epimorphics.com/public/vocabulary/Registry.html) register, the Data Provider Register, which is composed of subregisters for dcat:Dataset, prov:Agent and dcat:Distribution class object. The DPR register must at least define a dcat:Dataset register.

The DPR register's subregisters may not actually function via Linked Data principles but must indicate if they do or not. This is to allow the definition of DPR instances that contain legacy 'registers', things like dataset catalogues.

## Example Instances

**Minimal Example Diagram**: This diagram shows the most minimal legal set of classes that much be defined for an instance of the DPR:
https://docs.google.com/drawings/d/19Jc0Ipe1c1WT36Q-vavubHqV0l3hty6qixwIks5cUAE/edit?usp=sharing

**Geoscience Australia**: [dpr_ga.ttl](https://github.com/nicholascar/dpr-o/blob/master/dpr_ga.ttl) is an RDF document containng an absolute minimal implementation of the DPR-O for the organisation [Geoscience Australia](http://www.ga.gov.au). It has the DPR register defined with the compulsory subregister for dcat:Dataset objects given. In this instance, the dcat:dataset subregister cannot function as a Linked Data register as it is a legacy dataset catalogue; a GeoNetworks system. https://docs.google.com/drawings/d/1rLKN8pfZv4vjR5AW_GYvFkLXX--xFdR9GsbQNoKgOOg/edit?usp=sharing shows the contents of *dpr_ga.ttl* in diagram form.


Nicholas Car <nicholas.car@ga.gov.au>
