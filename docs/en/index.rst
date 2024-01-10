.. include:: ../common/common_definitions.rst

==============================================
The EUDI Wallet implementation profile
==============================================

Introduction
------------

The European Council requested the update of the 
eIDAS Regulation on electronic identification and trust services by 
implementing a new tool: the `European Digital Identity Wallet <https://commission.europa.eu/strategy-and-policy/priorities-2019-2024/europe-fit-digital-age/european-digital-identity_en>`_.

The purpose of the following technical rules is to define the technical architecture and reference framework to be used as a guideline by all the parties involved in the development of the IT Wallet project.

This documentation defines the national implementation profile of EUDI Wallet, containing the technical details about components of the Wallet ecosystem, as listed below:

 - Entities of the ecosystem according to `EIDAS-ARF`_.
 - Infrastructure of trust attesting realiability and eligibility of the participants.
 - PID and EAAs data schemes and attribute sets.
 - PID/EAA in MDL CBOR format.
 - PID/EAA in `SD-JWT`_ format.
 - Wallet Solution general architecture.
 - Wallet Attestation.
 - Issuance of PID/EAA according to `OpenID4VCI`_.
 - Presentation of PID/EAA according to `OpenID4VP`_.
 - Presentation of pseudonyms according to `SIOPv2`_.
 - PID/EAA backup and restore mechanisms.
 - PID/EAA revocation lists.

Index of content
----------------

.. toctree:: 
   :maxdepth: 3
   
   ssi-introduction.rst
   defined-terms.rst
   trust.rst
   wallet-solution.rst
   wallet-attestation.rst
   pid-eaa-data-model.rst
   pid-eaa-issuance.rst
   relying-party-solution.rst
   revocation-lists.rst
   pseudonyms.rst
   backup-restore.rst
   algorithms.rst
   contribute.rst
   standards.rst

