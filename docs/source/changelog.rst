Changelog
=========

|

Algorithm
---------

:Date: Feburary 1, 2023
* `@duopeng <https://github.com/duopeng>`__:|bug fix e20ed| Fixed two bugs in the dsDNA trimming logic: 1) the right arm was not trimming correctly, 2) report synthesis problems remaining after the trimming step.

:Date: January 25, 2023

* `@duopeng <https://github.com/duopeng>`__:|enhancement bf85b| Fine-tuned the off-limit range for recoding near junctions. Now avoiding 3bp/6bp from exon/intron side of the exon/intron junction, and 3bp/2bp from intron/exon side of the intron/exon junction.

:Date: January 24, 2023
* `@duopeng <https://github.com/duopeng>`__:|bug fix f87f4| Avoid re-mutating by keeping track of mutated bases.
* `@duopeng <https://github.com/duopeng>`__:|bug fix f87f4| Fixed an interference with mutation caused by marking codon-padding sequence with lower-case.
* `@duopeng <https://github.com/duopeng>`__:|enhancement f87f4| Scan and undo isolated mutation of "N" in "NGG".

:Date: January 20, 2023
* `@duopeng <https://github.com/duopeng>`__:|bug fix 94ea9| Codon mutation won't happen in some gRNAs in recut mode.
* `@duopeng <https://github.com/duopeng>`__:|enhancement c2e92| Changed strand names to match the naming convention.

|

Portal
------
:Date: Feburary 1, 2023
* `@duopeng <https://github.com/duopeng>`__:|enhancement b6b91| Change the default minumn homology arm length (dsDNA) to 200.
* `@duopeng <https://github.com/duopeng>`__:|bug fix b6b91| Made "clear example" and "reset button" buttons work correctly, both will reset to the following defaults: Genome: Human, Genes: None, number of gRNA:1, DNA donor type: ssDNA, HA arm length to consider: 500, target strand: non-target strand, recode intensity:full, prioritize recoding in: PAM, minimum homology arm length: 200, enforce maximum donor length: 200, recut cfd threshold: 0.03.

:Date: January 27, 2023
* `@duopeng <https://github.com/duopeng>`__:|enhancement f0ad7| Add a maximum limit of 384 entries per submission list.

:Date: January 26, 2023

* `@duopeng <https://github.com/duopeng>`__:|enhancement 0c23a| Default changed to "non-target strand" (including the example).
* `@duopeng <https://github.com/duopeng>`__:|enhancement 54621| Default changed to "Prioritize recoding in PAM" (including the example).


.. |bug fix 94ea9| image:: https://img.shields.io/badge/94ea9-bug%20fix-red
    :target: https://github.com/czbiohub/protospaceX/commit/3662c9a9b02e958fd3d6f8a94625470b07b94ea9
.. |bug fix f87f4| image:: https://img.shields.io/badge/f87f4-bug%20fix-red
    :target: https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4
.. |enhancement f87f4| image:: https://img.shields.io/badge/f87f4-enhancement-green
    :target: https://github.com/czbiohub/protospaceX/commit/98ab6e0dc698effa2441542771d7d82abbdf87f4
.. |enhancement c2e92| image:: https://img.shields.io/badge/c2e92-enhancement-green
    :target: https://github.com/czbiohub/protospaceX/commit/1b7c70cf2eb6ca6ae8f4783b9337d86a5c7c2e92
.. |enhancement f0ad7| image:: https://img.shields.io/badge/f0ad7-enhancement-green
    :target: https://github.com/czbiohub/protospaceX-portal/commit/687f8faab0839d65da990c9bcbc6487100ff0ad7
.. |enhancement bf85b| image:: https://img.shields.io/badge/bf85b-enhancement-green
    :target: https://github.com/czbiohub/protospaceX/commit/820ed9004c8d33136417ff22733d6812571bf85b
.. |enhancement 0c23a| image:: https://img.shields.io/badge/0c23a-enhancement-green
    :target: https://github.com/czbiohub/protospaceX-portal/commit/823eaff78a281fdfd2627dff329974ccee20c23a
.. |enhancement 54621| image:: https://img.shields.io/badge/54621-enhancement-green
    :target: https://github.com/czbiohub/protospaceX-portal/commit/e80b823bbe1f2a95a9afa6655305402203554621
.. |enhancement b6b91| image:: https://img.shields.io/badge/b6b91-enhancement-green
    :target: https://github.com/czbiohub/protospaceX-portal/commit/1fd046d24253d0fdc8d13d5f1ef9c5f6644b6b91
.. |bug fix b6b91| image:: https://img.shields.io/badge/b6b91-bug%20fix-red
    :target: https://github.com/czbiohub/protospaceX-portal/commit/1fd046d24253d0fdc8d13d5f1ef9c5f6644b6b91
.. |bug fix e20ed| image:: https://img.shields.io/badge/e20ed-bug%20fix-red
    :target: https://github.com/czbiohub/protospaceX/commit/67a4e0df5a33b023e2de834039b4fddd416e20ed

.. autosummary::
   :toctree: generated
