# DPR-O
This Data Provider Register ontology is loosely a registry-based version of the [Data Provider Node ontology](http://purl.org/dpn). 

It's purpose is to provide a single, Linked Data, entry point from which an organisation's various catalogues of web content can be found in defined ways. It is [DCAT Ontology](https://www.w3.org/TR/vocab-dcat/) and [PROV Ontology](https://www.w3.org/TR/prov-o/)-centric in design given that it focusses on datasets catalogued online, their distributions and agents. 

It specifies a top-level [Registry Ontology](http://www.epimorphics.com/public/vocabulary/Registry.html) register, the Data Provider Register, which is composed of subregisters for dcat:Dataset, prov:Agent and dcat:Distribution class object. The DPR register must at least define a dcat:Dataset register.

The DPR register's subregisters may not actually function via Linked Data principles but must indicate if they do or not. This is to allow the definition of DPR instances that contain legacy 'registers', things like dataset catalogues.

## Example Instances
**dpr_ga.ttl** contains an absolute minimal implementation of the DPR-O for the organisation [Geoscience Australia](http://www.ga.gov.au). It has the DPR register defined with the compulsory subregister for dcat:Dataset objects given. In this instance, the dcat:dataset subregister cannot function as a Linked Data register as it is a legacy dataset catalogue; a GeoNetworks system.

Nicholas Car <nicholas.car@ga.gov.au>
