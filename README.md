[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# JSON Schema Corpus
This is a corpus of over 80thousand JSON Schema documents, 
collected from open source GitHub repositories, using Google BigQuery, in July 2020.

You can inspect and download individual schemas from the [JSON Schema Corpus](./json_schema_corpus) or clone the repository to get the whole corpus. The source of each individual file is disclosed and can be downloaded [here](./repos_fullpath.csv).

## Cititation
To refer to this JSON Schema corpus in a publication, please use this BibTeX entry.
```BibTeX
@Misc{schema_corpus,
  author =  {Mohamed Amine Baazizi and Dario Colazzo and Giorgio Ghelli and Carlo Sartiani and Stefanie Scherzinger},
  title =   {A JSON Schema Corpus},
  note =    {\url{https://github.com/sdbs-uni-p/json-schema-corpus}},
  year =    2021
} 
``` 

## Acknowledgements
This work was partly funded by Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) grant #385808805. 
The schema corpus was retrieved using Google BigQuery, supported by Google Cloud.

## License
This work is licensed under the [Apache 2.0 License](./LICENSE.txt).