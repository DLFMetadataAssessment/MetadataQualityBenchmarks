==================
Summary Benchmarks
==================
The purpose of these criteria is to suggest an "industry standard" for absolute 
minimum requirements and a "gold standard" for the quality of a descriptive metadata record.


Usage:

-   Each criterion is intended to be “system agnostic” but some may not apply to 
    every situation (e.g., local field requirements)
-   Criteria are binary -- i.e., the set being evaluated must meet all points or 
    it does not meet the benchmarking standard for that level
-   These benchmarks focus solely on the quality of metadata entry, not the quality 
    of information (i.e., available information is all entered correctly, although 
    we might wish that additional information is known about an item to improve the record)
-   This framework is intended to be scalable (it is written in the context of 1 record, 
    but could apply across a collection, resource type, or an entire system)
-   Minimal criteria apply in all cases; suggested criteria do not rise to the level 
    of “absolute minimum” but are suggested as priorities for "better-than-minimal" 
    based on our research and experience; ideal criteria tend to be more subjective and may not apply in every situation


**********
Benchmarks
**********

This is the summary version, listing only the individual benchmarks, organized according to the
various aspects a metadata manager might review or verify in a record.  See the :doc:`Expanded Benchmarks </benchmarks-full>` 
for more details and examples related to each benchmark.
The summary is also downloadable as a :download:`PDF file </summary-metadata-benchmarks.pdf>`.


Content relevance
=================
These criteria are about the relationship between the record and the item.


+-------------------------------------------+---------------------------------------+---------------------------------------+
|Minimal                                    |Suggested                              |Ideal                                  |
+===========================================+=======================================+=======================================+
|-  The record is specific/scoped correctly |-  The record describes the item that  |-  All metadata values align with      |
|                                           |   it is attached to                   |   expectations for the material type  |
|       *(e.g., records for single          |                                       |                                       |
|       manuscripts are not described as    |                                       |       *(e.g., language use for text   |
|       whole collections of materials or   |                                       |       vs. images; theses/dissertations|
|       vice versa)*                        |                                       |       have creator or author values)* |
|                                           |                                       |                                       |
|                                           |                                       |-  When applicable, relationships      |
|                                           |                                       |   between items and parent collections|
|                                           |                                       |   are clearly represented             |
|                                           |                                       |                                       |
|                                           |                                       |-  All information not specific to the |
|                                           |                                       |   item has been removed               |
|                                           |                                       |                                       |
|                                           |                                       |       *(e.g., duplicated records      |
|                                           |                                       |       propagated across a collection  |
|                                           |                                       |       have been individualized;       |
|                                           |                                       |       information not appropriate for |
|                                           |                                       |       the item type is removed)*      |
|                                           |                                       |                                       |
|                                           |                                       |-  Administrative/acquisition          |
|                                           |                                       |   information is appropriately noted  |
|                                           |                                       |   and/or hidden from the public, if   |
|                                           |                                       |   applicable                          |
+-------------------------------------------+---------------------------------------+---------------------------------------+



Existence of values
===================
These criteria are related to when fields should have values or not (regardless of value formatting or correctness).


+-------------------------------------------+---------------------------------------+---------------------------------------+
|Minimal                                    |Suggested                              |Ideal                                  |
+===========================================+=======================================+=======================================+
|-  Every record has a title                |-  All locally-required fields have    |-  Relevant recommended/optional fields|
|                                           |   values                              |   have values                         |
|                                           |                                       |                                       |
|                                           |-  All conditionally-required fields   |-  All relevant information about the  |
|                                           |   have values                         |   item is included                    |
|                                           |                                       |                                       |
|                                           |-  Fields that require multiple parts  |-  Non-required qualifiers or field    |
|                                           |   or qualifiers have all parts        |   parts are added to provide enhanced |
|                                           |                                       |   information or functionality        |
|                                           |-  Records have some type of subject   |                                       |
|                                           |   value                               |-  "Null" values are used consistently,|
|                                           |                                       |   according to local guidelines       |
|                                           |   -   *(e.g., subject, keyword, genre,|                                       |
|                                           |       etc.)*                          |   -   *(e.g., N/A, unknown, leave     |
|                                           |                                       |       blank, etc.)*                   |
|                                           |-  A rights statement is present       |                                       |
|                                           |   (standardized statements preferred) |-  Fields/subfields that cannot be     |
|                                           |                                       |   repeated occur only once            |
+-------------------------------------------+---------------------------------------+---------------------------------------+


Content of values
=================
These criteria are focused on the field values specifically -- e.g., string values, formatting, etc.


+-------------------------------------------+---------------------------------------+---------------------------------------+
|Minimal                                    |Suggested                              |Ideal                                  |
+===========================================+=======================================+=======================================+
|-  Value content matches the field type    |-  Stray character encoding has been   |-  All values are appropriate lengths  |
|                                           |   removed                             |   for their fields                    |
|   -   *(e.g., "date" fields do not contain|                                       |                                       |
|       text strings)*                      |   -   *(e.g., MARC subfields that may |-  All values that ought to align with |
|                                           |       have been pasted in)*           |   standards conform to applicable     |
|-  No values exceed applicable system      |                                       |   vocabularies or rules               |
|   character limits                        |-  All "placeholder values have been   |                                       |
|                                           |   replaced/removed and are not present|   -   *(e.g., names, dates, locations,|
|-  There is no text encoding that "breaks" |   in the publicly accessible record   |       subjects, etc.)*                |
|   records                                 |                                       |                                       |
|                                           |   -   *(e.g., {{{name}}} or           |-  All values are spelled correctly    |
|   -   *(i.e., records are not prevented   |       YYYY-MM or notes intended to be |                                       |
|       from being displayed)*              |       removed by editors)*            |-  Text fields use appropriate         |
|                                           |                                       |   punctuation, grammar, abbreviations,|
|                                           |                                       |   etc.)*                              |
+-------------------------------------------+---------------------------------------+---------------------------------------+


Community/audience
==================
These criteria describe how metadata records reflect the needs of users.


+-------------------------------------------+---------------------------------------+---------------------------------------+
|Minimal                                    |Suggested                              |Ideal                                  |
+===========================================+=======================================+=======================================+
|                                           |-  Extremely problematic/offensive     |-  Reading level & language use is     |
|                                           |   terms have been removed or handled  |   appropriate for all (relevant)      |
|                                           |   appropriately                       |   communities or audiences            |
|                                           |                                       |                                       |
|                                           |                                       |   -   *(e.g., collections intended for|
|                                           |                                       |       students match their reading    |
|                                           |                                       |       level; collections intended for |
|                                           |                                       |       scientific research use         |
|                                           |                                       |       technical terminology)*         |
|                                           |                                       |                                       |
|                                           |                                       |-  Vocabulary usage aligns with the    |
|                                           |                                       |   needs of the audience and material  |
|                                           |                                       |   type                                |
|                                           |                                       |                                       |
|                                           |                                       |   -   *(e.g., technical vocabularies  |
|                                           |                                       |       are used for scientific         |
|                                           |                                       |       materials, but not for          |
|                                           |                                       |       collections intended for        |
|                                           |                                       |       amateurs)*                      |
|                                           |                                       |                                       |
|                                           |                                       |-  Values connected to interface       |
|                                           |                                       |   functionality are correct           |
|                                           |                                       |                                       |
|                                           |                                       |   -   *(e.g., field values used for   |
|                                           |                                       |       browsing or filtering search    |
|                                           |                                       |       results)*                       |
|                                           |                                       |                                       |
|                                           |                                       |-  Record language has been            |
|                                           |                                       |   evaluated/updated to align with     |
|                                           |                                       |   best practices related to reparative|
|                                           |                                       |   metadata, inclusive language, etc.  |
+-------------------------------------------+---------------------------------------+---------------------------------------+
