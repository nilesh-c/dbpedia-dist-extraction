DBpedia Distributed Dump Extractor
=======================

Distributed framework to extract structured data from Wikipedia

Before building, please perform these steps:

```bash
git submodule init
git submodule update --remote
cd extraction-framework
git am --signoff < namespace_equal_fix.patch
```

After this, build the repos!

```bash
cd ..
mvn install
```

Tested with liwiki and RedirectExtractor.
