# BEIR (v1.0.0) - Webis-Touche2020

This Lucene impact index for SPLADE++ (CoCondenser-EnsembleDistil)" was generated on 2023/11/24 at Anserini commit [`a66f86f`](https://github.com/castorini/anserini/commit/a66f86fb463db76df521f58992b000dd4ab39548) on `orca` with the following command:

```
nohup target/appassembler/bin/IndexCollection \ 
  -collection JsonVectorCollection \ 
  -generator DefaultLuceneDocumentGenerator \ 
  -input /store/collections/beir-v1.0.0/splade-pp-ed/webis-touche2020 \ 
  -index indexes/lucene-index.beir-v1.0.0-webis-touche2020.splade-pp-ed.20231124.a66f86f \ 
  -threads 16 -impact -pretokenized -optimize \ 
  >& logs/log.beir-v1.0.0--webis-touche2020.splade-pp-ed.20231124.a66f86f & 
```