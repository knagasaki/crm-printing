# A CIDOC CRM extension for printed books

## About this project

This repository is the working space of a project at Keio University (Kiyonori Nagasaki and Mari Agata) that documents Western and East Asian printed books in one framework: TEI/XML as the scholar's record, and the CIDOC CRM family as the semantics.

Its core is **CRMtyp** (prefix `crmtyp:`), a small extension of the [CIDOC Conceptual Reference Model](https://cidoc-crm.org/) for movable-type printing: printed impressions, the physical sorts that made them, type-forms and founts, formes, and the events of punchcutting, casting, carving, composition and printing. Every CRMtyp class and property specialises a CIDOC CRM (or LRMoo) class or property. The extension is designed to be used together with [CRMtex](https://cidoc-crm.org/crmtex/) (written text and graphemes), [LRMoo](https://cidoc-crm.org/lrmoo/) (works, manifestations and items), [CRMdig](https://cidoc-crm.org/crmdig/), [CRMsci](https://cidoc-crm.org/crmsci/) and [CRMinf](https://cidoc-crm.org/crminf/). It covers European metal type and Japanese wooden and metal type alike; woodblock-printed canons and manuscripts are on the agenda.

The repository shares provisional data, experimental models and tools developed in the course of the project. The materials are work in progress and may be revised or reorganised as the research develops. CRMtyp is the project's own extension: it is not a CRM-SIG ontology and should not be regarded as a finalised or officially endorsed extension of CIDOC CRM or CRMtex.

## Namespace

The CRMtyp namespace IRI is provisional and will change before a first release; the prefix `crmtyp:` is stable. Until then, do not rely on the IRIs in the ontology file outside this repository.

## Images and rights

No page images are distributed here. Zones and measurements refer to the IIIF canvases of the holding institutions: the 42-line Bible to the Digital Collections of Keio University Libraries, under their Terms of Service, and the Fumonbon to the National Institute of Japanese Literature (kokusho.nijl.ac.jp, 200013336), under its terms. Transcriptions and Tesseract box files derived from these images are shared for research use under the licence below.

## Licence

Unless otherwise indicated, data and documentation in this repository are made available under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). Source code is released under the [MIT License](LICENSE). The bundled viewer uses [OpenSeadragon](https://openseadragon.github.io/) (BSD-3-Clause).

## How to cite

Nagasaki, K., and Agata, M. (2026). From Comparing Letterforms to Inferring Production Processes: One Documentation Infrastructure for Eastern and Western Rare Books. Poster, CIDOC 2026, Tervuren.

## Acknowledgements

This work was supported by JSPS KAKENHI Grant Numbers JP26K03238, JP25K24684, JP25K00452, JP25K00398, JP25H00001, JP24K15660, JP24K03232 and JP24K03229.

## Contact

Kiyonori Nagasaki, Keio University / International Institute for Digital Humanities: nagasaki@dhii.jp

## References

* [CIDOC CRM](https://cidoc-crm.org/)
* [CRMtex](https://cidoc-crm.org/crmtex/) · [LRMoo](https://cidoc-crm.org/lrmoo/) · [CRMdig](https://cidoc-crm.org/crmdig/) · [CRMsci](https://cidoc-crm.org/crmsci/) · [CRMinf](https://cidoc-crm.org/crminf/)
* [TEI Guidelines](https://tei-c.org/guidelines/) · [IIIF](https://iiif.io/)
