Changelog
=========
:Date: January 25, 2023

* `@duopeng <https://github.com/duopeng>`__: Improvement: Fine tuned the avoidance of recoding near junctions. Now avoiding 3bp/6bp from exon/intron side of the junction, and 3bp/2bp from intron/exon side of the junction (`bf85b <https://github.com/czbiohub/protospaceX/commit/820ed9004c8d33136417ff22733d6812571bf85b>`__)


:Date: January 24, 2023

* `@duopeng <https://github.com/duopeng>`__: Bug fix: Avoid re-mutating by keeping track of mutated bases (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)
* `@duopeng <https://github.com/duopeng>`__: Bug fix: Uppercase the 2bp codon-padding sequence to avoid interferring with mutation (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)
* `@duopeng <https://github.com/duopeng>`__: Enhancement: Scan and undo isolated mutation of "N" in "NGG" (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)

:Date: January 20, 2023

* `@duopeng <https://github.com/duopeng>`__: Bug fix: Codon mutation won't happen in some gRNAs in recut mode (`94ea9 <https://github.com/czbiohub/protospaceX/commit/3662c9a9b02e958fd3d6f8a94625470b07b94ea9>`__)
* `@duopeng <https://github.com/duopeng>`__: Enhancement: Changed strand names to match the naming convention (`c2e92 <https://github.com/czbiohub/protospaceX/commit/1b7c70cf2eb6ca6ae8f4783b9337d86a5c7c2e92>`__)

.. autosummary::
   :toctree: generated
