========================
Types of Quality Metrics
========================
This is a synthesis of possible criteria for quality metrics based on a wide array of frameworks and literature (see :doc:`citations </citations>`), organized roughly into the seven categories identified by the Bruce/Hillmann framework.  Individual criteria could be used to create measurable benchmarks depending on the priorities and technical capabilities of a specific digital collection/organization for "better-than-minimal" benchmarks.  

Additionally, the scope of the metadata benchmarks focuses specifically on descriptive metadata values, but this list includes aspects contributing to overall quality, such as the role of data structures, sharability, technical maintenance and other components of digital collection description and maintenance.  However, note that technical specifications are still primarily within the context of descriptive metadata (e.g., may include technical criteria related to displaying values but not general UI/UX of digital libraries)

-   Technical specifications: relate to system requirements, modeling, shareability, and other aspects outside of descriptive metadata values
-   Metadata values: applies to values in metadata fields, primarily descriptive metadata, unless otherwise noted


Accessibility
-------------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  The schema or element set describes the items in|-  Values use terminology and a reading level that |
|   a way that is understandable to its designated  |   is understandable and appropriate for the       |
|   communities                                     |   audience or user community                      |
|-  Infrastructure:                                 |-  Shortened data values -- e.g., abbreviations,   |
|                                                   |   acronyms, initialisms, etc. -- include          |
|   -   has a stable source of access (e.g., a      |   definitions, or fuller values for clarification |
|       service provider guarantee)                 |                                                   |
|   -   can be maintained with available local      |                                                   |
|       resources (monetary, technical, personnel,  |                                                   |
|       etc.)                                       |                                                   |
|   -   is extensible to add features when needed   |                                                   |
|                                                   |                                                   |
|-  Technical components for sharing metadata, such |                                                   |
|   as URIs and OAI endpoints, are stable and and   |                                                   |
|   reliable                                        |                                                   |
|-  Metadata is clearly licensed -- with machine-   |                                                   |
|   and human-readable licenses -- regarding harvest|                                                   |
|   republishing, and other applicable uses         |                                                   |
|-  Metadata records are shareable, preferably as a |                                                   |
|   bulk download                                   |                                                   |
|-  Each metadata record has a unique, persistent   |                                                   |
|   identifier                                      |                                                   |
|-  User displays have human-readable labels for    |                                                   |
|   fields and for values represented with          |                                                   |
|   machine-readable text (e.g., URIs)              |                                                   |
|-  Metadata is indexed and searchable              |                                                   |
+---------------------------------------------------+---------------------------------------------------+


Accuracy
--------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  The schema or element set truthfully describes  |-  All relevant fields/information are free of     |
|   the items                                       |   formatting, spelling, and other kinds of        |
|                                                   |   typographical errors that impact findability    |
|   -   Both properties and values are defined      |                                                   |
|                                                   |-  "Noise" in elements is absent (e.g., tag        |
|-  Any metadata creation, including  extraction,   |   fragments)                                      |
|   migration, transformation, etc. results in      |                                                   |
|   appropriate records according to the local      |-  Any default values are correct and appropriately|
|   schema                                          |   used                                            |
|-  Measures are in place for validation of:        |                                                   |
|                                                   |                                                   |
|   -   Record structure                            |                                                   |
|   -   Values (when applicable)                    |                                                   |
|   -   Schema properties                           |                                                   |
+---------------------------------------------------+---------------------------------------------------+


Completeness
------------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  The schema or element set is able to fully      |-  All relevant fields/information are included in |
|   describe the items                              |   all item records                                |
|                                                   |                                                   |
|-  Controlled vocabularies or authorities contain  |   -   Required/mandatory fields have values       |
|   all values needed for records                   |       (locally-required and/or required by        |
|                                                   |       consortia)                                  |
|                                                   |   -   Relevant optional fields are included       |
|                                                   |   -   Overall field values-per-record are         |
|                                                   |       appropriate and provide sufficient          |
|                                                   |       information                                 |
|                                                   |   -   Entries-per-field meet requirements or      |
|                                                   |       expectations of the local schema            |
|                                                   |                                                   |
|                                                   |       (e.g., a schema could require or prefer     |
|                                                   |       multiple subject-type entries)              |
|                                                   |                                                   |
|                                                   |-  Field values contain all expected information   |
|                                                   |   and syntactic components (e.g., qualifiers)     |
|                                                   |                                                   |
|                                                   |-  Enough *unique* information is included in an   |
|                                                   |   item record to be useful                        |
|                                                   |                                                   |
|                                                   |-  Values that support findability are included    |
|                                                   |   (e.g., field values connected to user interface |
|                                                   |   functionality)                                  |
+---------------------------------------------------+---------------------------------------------------+


Conformance to expectations
---------------------------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  The data model describes what it claims to      |-  Values in the record describe the associated    |
|-  Controlled vocabularies are aligned with the    |   item (e.g., vs. a different item or a collection|
|   needs of the user community or audience         |   of items when not applicable)                   |
|-  Data models or schemas that have been brought   |-  Data from varied sources has been normalized in |
|   together from different sources have been       |   a way that is appropriate to the audience or    |
|   reconciled                                      |   user group                                      |
|-  Data from different sources can be merged       |                                                   |
|   without duplication or variants within a        |                                                   |
|   controlled field                                |                                                   |
|-  Compromises in schema usage are documented and  |                                                   |
|   align with the needs of the user community      |                                                   |
+---------------------------------------------------+---------------------------------------------------+


Consistency
-----------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  Whenever possible, controlled vocabularies or   |-  Rules about "blank" (i.e., non-populated/null)  |
|   system tools are used to enforce consistency    |   or non-relevant elements are applied            |
|   within field values                             |   consistently (e.g., left blank, filled with     |
|-  The metadata schema is clearly defined and      |   prescribed values like N/A, etc.)               |
|   applied to every applicable record in the same  |-  Values for the same referent (e.g., a particular|
|   way                                             |   city, person, etc.) are identical               |
|-  The data model is                               |-  Metadata values are formatted in alignment with |
|                                                   |   local guidelines                                |
|   -  well-structured and logical                  |-  Values are consistent with similar usage in the |
|   -  in line with similar models from the same    |   user community                                  |
|      domain                                       |                                                   |
|   -  uses consistent relationship directions      |                                                   |
+---------------------------------------------------+---------------------------------------------------+


Provenance
----------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  Information is documented about how records can |*Administrative/preservation metadata*             |
|   be shared via OAI                               |                                                   |
|-  Data is protected from unauthorized changes     |-  The names of metadata creators and editors are  |
|-  Security measures, such as digital signatures,  |   documented, including anyone responsible for    |
|   can be used to verify data authenticity         |   harvesting or normalizing records from another  |
|                                                   |   source                                          |
|                                                   |-  All changes to a record are documented          |
|                                                   |-  Methods of creating, extracting, or transforming|
|                                                   |   metadata are documented                         |
|                                                   |-  Attribution for the source of the metadata      |
|                                                   |   record is included                              |
|                                                   |-  Appropriate vocabularies are used for           |
|                                                   |   documenting provenance information              |
+---------------------------------------------------+---------------------------------------------------+


Timeliness
----------

+---------------------------------------------------+---------------------------------------------------+
|TECHNICAL SPECIFICATIONS                           |METADATA VALUES                                    |
+===================================================+===================================================+
|-  Controlled vocabularies are managed and updated |-  Record values are updated regularly, e.g.:      |
|   as needed                                       |                                                   |
|-  "Age" of records and last edits/updates are     |   -   As resources change                         |
|   recorded                                        |   -   As new information is available             |
|                                                   |   -   As local standards change                   |
|                                                   |   -   To meet changing needs within the user      |
|                                                   |       community or audience                       |
|                                                   |   -   As general practice or industry standards   |
|                                                   |       shift                                       |
|                                                   |   -   Information supports current search and     |
|                                                   |       usage activities for the user community or  |
|                                                   |       audience                                    |
+---------------------------------------------------+---------------------------------------------------+
