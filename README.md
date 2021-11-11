# icdo-doid-mappings

This repository includes a script to generate predicted mappings from ICDO terms
to Human Disease Ontology terms using lexical matching from Gilda.

## License

The code in this repository is licensed under the MIT License. Derived mappings
are licensed under CC0.

For information about ICD-O licensing,
see [here](https://apps.who.int/classifications/apps/icd/ClassificationDownloadNR/license.htm).

## Build

The mappings can be regenerated with the following:

```shell
pip install tox
tox
```
