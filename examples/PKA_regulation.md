#  Example of the regulation of Protein Kinase A catalytic subunit.

This example of protein regulation shows the effects of cAMP on Protein Kinase A (PKA) catalytic subunit.

PKA is a tetramer composed of two regulatory subunits and two catalytic subunits. The activity of PKA resides in its catalytic subunits. The catalytic subunits are active, able to phosphorylate and regulate targets, only when unbound to the regulatory subunits. When cAMP binds to the regulatory subunits of PKA, the catalytic subunits dissociate with the regulatory subunits.  



<p align="center">
  <img src="https://github.com/vtoure/MI2CAST/blob/master/images/pka.svg" alt="PKA regulation"/>
</p>


## Annotation of the causal interaction following MI2CAST

| Term | Identifier | Name/Label | Database |
|---|---|---|---|
| source | [CHEBI:17489](http://purl.obolibrary.org/obo/CHEBI_17489) | 3',5'-cyclic AMP | ChEBI |
| target | [UniProtKB:P17612](https://www.uniprot.org/uniprot/P17612) | cAMP-dependent protein kinase catalytic subunit alpha (PRKACA) | UniProtKB |
| effect | [MI:2236](http://purl.obolibrary.org/obo/MI_2236) | up-regulates activity | PSI-MI |
| reference | [PMID:26687711](https://www.ncbi.nlm.nih.gov/pubmed/26687711) | "Protein kinase A catalytic subunit... " | Pubmed |
| evidence | [ECO:0000302](http://purl.obolibrary.org/obo/ECO_0000302) | author statement used in manual assertion | Evidence and Conclusion Ontology |
| biological activity source | [GO:0034237]( http://purl.obolibrary.org/obo/GO_0034237) | protein kinase A regulatory subunit binding | GO:MF |
| biological activity target | [GO:0004672]( http://purl.obolibrary.org/obo/GO_0004672) | protein kinase activity | GO:MF |
| compartment | [GO:0005737]( http://purl.obolibrary.org/obo/GO_0005737) | cytoplasm | GO:CC |
| taxon | [NCBI:txid9606](http://purl.obolibrary.org/obo/NCBITaxon_9606) | Homo sapiens | NCBI taxonomy |


## Written explanation of the causal statement
The chemical 3',5'-cyclic AMP has a protein kinase A regulatory subunit binding activity that up-regulates the protein kinase activity of PRKACA in the cytoplasm. This regulation is identified in humans and has been assessed by a curator based on author statement from the following publication: ["Protein kinase A catalytic subunit isoform PRKACA; history, function and physiology" by Turnham and Scott](https://dx.doi.org/10.1016%2Fj.gene.2015.11.052).
