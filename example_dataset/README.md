# IUC17 sample dataset

The folder `dataset_1` contains an example dataset created by `pyscal_rdf` and `pyiron`, using the CMSO ontology. The dataset contains 137 atomic structures. The folder structure is as follows:

- `dataset_1/triples`: contains all the generated triples in the turtle format. These triples also point to the raw data which is stored in the folder `data_1/rdf_structure_core`.
- `data_1/rdf_structure_core/*.json`: raw data of the each atomic structure.

The application profile could be generated from the triples, and all three files could be stored in the given folder structure. This allows for downloading the data, and reconstructing the knowledge graph with `pyscal_rdf`.

The ontology files used for annotation is also uploaded here.
