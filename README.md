# SparqlPress

SPARQL connector for WordPress

_2024 reboot of SparqlPress, SparqlPress2_

**Status 2024-09-19** - repo created (I reckon enough time has passed to legitimise recycling the original name), planning...

I have other FOAFish things to do, so this came back in scope.

I did [SparqlPress2](https://github.com/danja/sparqlpress2) in 2021. The req was simply to update the old version that had gone stale, abandoned. I kind-of did that, but ran out of steam & enthusiasm. The PHP SPARQL store used was ARC2, and at that point in time it appeared to have gone stale, abandoned. I felt a more current store was needed for a proper update, nothing seemed quite suitable.

But a re-jig was going on my TODO list whatever. I imagined going down the route of using JS libs for an RDF model in browser LocalStorage, pushing the SPARQL to client calls against a remote store. Which defeated the object somewhat. SparqlPress is meant to be self-contained (aside from connectors to other Web data, naturally) and very easy to set up for someone that's unfamiliar with the Linked Data stack.

But I just discovered [ARC2](https://github.com/semsol/arc2) is alive again!

Next steps are to set up for docs in this repo, then revisit the original SparqlPress features, SparqlPress2 code, figure out how to work with PHP 8 and the current ARC2.

Libs I'll likely be drawing on :

- [ARC2](https://github.com/semsol/arc2) - PHP SPARQL store
- [EasyRDF](https://www.easyrdf.org/) - general RDF in PHP
- [RDF-Ext](https://rdf-ext.org/) - JS libs that extend the RDF/JS specs to make them easier in practice

Watch this space!
