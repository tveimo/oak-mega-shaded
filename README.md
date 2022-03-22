# oak-mega-shaded
Lots of small jackrabbit-oak dependencies combines, with some other dependencies shaded to avoid conflicts.

Jackrabbit Oak depends on an older version of Lucene. This might cause problems in projects which included newer versions of Lucene,
and which doesn't make use of osgi or similar to compartmentalize dependencies

This mega jar includes jackrabbit oak, and a shaded version of Lucene (and a few other minor dependencies), so that the shaded Lucene
dependency can coexist with a more recent version of Lucene.

