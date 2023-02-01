Changelog
=========

Algorithm
---------
:Date: January 25, 2023

* `@duopeng <https://github.com/duopeng>`__: Improvement: Fine-tuned the off-limit range for recoding near junctions. Now avoiding 3bp/6bp from exon/intron side of the exon/intron junction, and 3bp/2bp from intron/exon side of the intron/exon junction (`bf85b <https://github.com/czbiohub/protospaceX/commit/820ed9004c8d33136417ff22733d6812571bf85b>`__)

:Date: January 24, 2023
* `@duopeng <https://github.com/duopeng>`__: |bug|: Avoid re-mutating by keeping track of mutated bases (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)
* `@duopeng <https://github.com/duopeng>`__: Bug fix: Fixed an interference with mutation caused by marking codon-padding sequence with lower-case (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)
* `@duopeng <https://github.com/duopeng>`__: Enhancement: Scan and undo isolated mutation of "N" in "NGG" (`f87f4 <https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4>`__)

:Date: January 20, 2023
* `@duopeng <https://github.com/duopeng>`__: Bug fix: Codon mutation won't happen in some gRNAs in recut mode (`94ea9 <https://github.com/czbiohub/protospaceX/commit/3662c9a9b02e958fd3d6f8a94625470b07b94ea9>`__)
* `@duopeng <https://github.com/duopeng>`__: Enhancement: Changed strand names to match the naming convention (`c2e92 <https://github.com/czbiohub/protospaceX/commit/1b7c70cf2eb6ca6ae8f4783b9337d86a5c7c2e92>`__)


Portal
------

:Date: January 27, 2023
* `@duopeng <https://github.com/duopeng>`__: Add a maximum limit of 384 entries per submission list (`f0ad7 <https://github.com/czbiohub/protospaceX-portal/commit/687f8faab0839d65da990c9bcbc6487100ff0ad7>`__)

:Date: January 26, 2023

* `@duopeng <https://github.com/duopeng>`__: Default changed to "non-target strand" (including the example) (`0c23a <https://github.com/czbiohub/protospaceX-portal/commit/823eaff78a281fdfd2627dff329974ccee20c23a>`__)
* `@duopeng <https://github.com/duopeng>`__: Default changed to "Prioritize recoding in PAM" (including the example) (`54621 <https://github.com/czbiohub/protospaceX-portal/commit/e80b823bbe1f2a95a9afa6655305402203554621>`__)


.. |bug-fix| image:: /_static/images/bug-fix-red.svg?style=svg
    :alt: bug fix
    :target: 

.. |enhancement| image:: /_static/images/enhancement-green.svg?style=svg
    :alt: enhancement
    :target: 

.. |build status| image:: https://circleci.com/gh/readthedocs/readthedocs.org.svg?style=svg
    :alt: build status
    :target: https://circleci.com/gh/readthedocs/readthedocs.org

|Generic badge|

.. |bug| image:: https://img.shields.io/badge/<SUBJECT>-<bug fix>-<red>.svg
   :target:

.. autosummary::
   :toctree: generated
