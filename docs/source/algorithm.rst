Algorithm 
=========

Overview
--------
.. figure:: /_static/images/Algorithm.png
   :width: 55%
   :align: center
   :alt: Algorithm_overview
|
|
gRNA scoring
------------
The gRNAs score is computed from three weights that aims to (1) maximize specifcity, (2) minimize cut-to-insert distance and (3) avoid cutting near splice junctions and 5’ UTRs.

.. figure:: /_static/images/gRNA.png
   :width: 100%
   :align: center
   :alt: gRNA_scoring
| Cutting Frequency Determination (CFD) score wascreated by `Doench et al. <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4744125/>`_  to calculate the off-target potential of sgRNA:DNA interaction.
|
|
Recoding strategy
-----------------
| Silent mutations are included in the DNA donor to:
| - Prevent recutting the genome after editing. 
| - Facilitate payload insertion when the cut-to-insert distance is inevitably large.  
|
| There are three recoding intesities: "full", "prevent recut", and "none". 
| In "full", the cut-to-insert region is recoded to facilitate payload insertion. The gRNA or split gRNA (disrupted by the payload, creating a protopsacer-half and a PAM-half) are also recoded.
| "Prevent recut" differs from "full" by the lack of recoding in the cut-to-insert region.

.. figure:: /_static/images/recode.png
   :width: 100%
   :align: center
   :alt: Recode_strategy
|
|
|
DNA donor processing strategy
-----------------------------
| After recoding, the DNA donors are further processed, in a type-specific way.
| There are two types of DNA donors:
| - Double-stranded DNA (dsDNA) 
| - Single-stranded oligonucleotides (ssODN)

.. figure:: /_static/images/donor.png
   :width: 100%
   :align: center
   :alt: Donor_strategy

   
.. autosummary::
   :toctree: generated
