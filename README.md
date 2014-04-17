DBpedia Distributed Dump Extractor
=======================

Distributed framework to extract structured data from Wikipedia

Before building, please perform these steps:

<pre>
git submodule init
git submodule update --remote
cd extraction-framework
git am --signoff < namespace_equals_fix.patch
</pre>

After this, build the repos!

<pre>
cd ..
mvn install
</pre>

Tested with liwiki and RedirectExtractor.
