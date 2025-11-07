===================
Expanded Benchmarks
===================
This documentation provides more specific information about how an organization might apply the benchmarks or determine the level of quality for records and collections of metadata.

-   *Benchmark:* criterion that must be met
-   *Metric(s):* mechanism or measurement to determine if a record/value meets the benchmark standard; these may depend on local guidelines and field usage
-   *Examples and Notes:* non-exhaustive list of additional clarifications and/or examples of values that may or may not meet a metric

In this model, the benchmark and metrics set the standard (i.e., the criteria that must be met to qualify for that quality level) and the examples show some ways that the standard might be applied for different local circumstances.  Also note that minimal and ideal levels are clearly defined, while all intermediary benchmarking stages are left up to local organizations.  The benchmarks in the “suggested” section describe suggested priorities for organizations setting “better-than-minimal” benchmarks for their metadata that fall between minimal and ideal.

-   General benchmarks usage:

    -   Each criterion is intended to be “system agnostic” but some may not apply to every situation (e.g., local field requirements)
    -   Criteria are binary -- i.e., the set being evaluated must meet all points or it does not meet the benchmarking standard for that level
    -   These benchmarks focus solely on the quality of metadata entry, not the quality of information (i.e., available information is all entered correctly, although we might wish that additional information is known about an item to improve the record)
    -   This framework is intended to be scalable (it is written in the context of 1 record, but could apply across a collection, resource type, or an entire system)
                             


******************
Minimal Benchmarks
******************
Minimal-level benchmarks are mostly objective (e.g., a value is present/not present) and should apply to all records


+-------------------------------------------+---------------------------------------+---------------------------------------+
|Benchmark                                  |Metrics                                |Examples                               |
+===========================================+=======================================+=======================================+
|The record is specific/scoped correctly    |-  Values in a record for an individual|**Values that may be correct:**        |
|                                           |   item (e.g., a monograph, photograph,|                                       |
|                                           |   newsletter issue, etc.) describe    |-  Name(s) of the people or            |
|                                           |   only that item rather than multiple |   organizations who authored a text or|
|                                           |   collection-level or serial-level    |   issue but not all of the authors    |
|                                           |   items                               |   from a collection of texts          |
|                                           |                                       |-  A publisher value that matches an   |
|                                           |                                       |   individual serial issue rather than |
|                                           |                                       |   multiple possible publisher values  |
|                                           |                                       |   from an entire serial set           |
|                                           |                                       |-  Subject-type values or descriptions |
|                                           |                                       |   of the content that reflect the item|
|                                           |                                       |   rather than general collection-level|
|                                           |                                       |   descriptions or subjects describing |
|                                           |                                       |   multiple items                      |
+                                           +---------------------------------------+---------------------------------------+
|                                           |-  Values in a record describing       |**Possible issues to review:**         |
|                                           |   multiple items, or a collection of  |                                       |
|                                           |   items, reflect all of the content   |-  Multiple records that all have the  |
|                                           |   attached to it                      |   same title and/or description       |
|                                           |                                       |   (especially if there are a large    |
|                                           |                                       |   number)                             |
|                                           |                                       |-  Relevant information is absent from |
|                                           |                                       |   a collection-level record           |
+-------------------------------------------+---------------------------------------+---------------------------------------+
|Every record has a title                   |-  The title field is not empty        |**Possible issues to review:**         |
|                                           |                                       |                                       |
|                                           |                                       |-  Any record that has no value or an  |
|                                           |                                       |   effectively empty title value (e.g.,|
|                                           |                                       |   a value consisting exclusively of   |
|                                           |                                       |   whitespace)                         |
+-------------------------------------------+---------------------------------------+---------------------------------------+
|Value content matches the field type       |-  For fields that have a specific data|**Values that may be correct:**        |
|                                           |   type, content matches the specified |                                       |
|                                           |   type                                |-  A field requiring a date entry      |
|                                           |                                       |   contains a date, e.g., formatted    |
|                                           |                                       |   YYYY-MM-DD, rather than a text      |
|                                           |                                       |   string, e.g., sometime in September |
|                                           |                                       |-  A field requiring a binary entry    |
|                                           |                                       |   (e.g., checked/unchecked) does not  |
|                                           |                                       |   contain an alphanumeric text string |
|                                           |                                       |   or other value                      |
|                                           |                                       |-  A field requiring a standard code   |
|                                           |                                       |   value (e.g., language codes from    |
|                                           |                                       |   ISO 639-2) does not contain other   |
|                                           |                                       |   characters                          |
|                                           |                                       |-  A field requiring a numeric value   |
|                                           |                                       |   does not contain letters or other   |
|                                           |                                       |   symbols                             |
+-------------------------------------------+---------------------------------------+---------------------------------------+
|No values exceed applicable system         |-  No field in a record has more       |**Possible issues to review:**         |
|character limits                           |   characters than any allowable limit |                                       |
|                                           |                                       |-  Any value outside of a standard,    |
|                                           |                                       |   required length (e.g., identifiers) |
|                                           |                                       |-  Any value longer than what is       |
|                                           |                                       |   permitted by a local system on a    |
|                                           |                                       |   technical level                     |
+-------------------------------------------+---------------------------------------+---------------------------------------+
|There is no text encoding that "breaks"    |-  The record displays publicly without|**Note:**                              |
|records                                    |   error messages                      |                                       |
|                                           |-  The record can be successfully      |This is dependent on local system      |
|                                           |   edited/saved administratively and   |limitations                            |
|                                           |   indexed in the system               |                                       |
+-------------------------------------------+---------------------------------------+---------------------------------------+


********************
Suggested Benchmarks
********************

This category includes suggestions about what ought to be prioritized in local benchmarks to make records “better than minimal,” 
based on research and professional experience (noted in the justification column).  These are mostly objective, but also include 
some subjective elements; suggested benchmarks are intended to be adjusted as needed and applied when applicable according to local requirements.


+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|Benchmark                                  |Justification                              |Metrics                                |Examples                                           |
+===========================================+===========================================+=======================================+===================================================+
|The record describes the item that it is   |This is a relatively fundamental need for  |-  The preponderance of information in |**Note:**                                          |
|attached to                                |metadata quality, but generally cannot be  |   the record matches the content of   |                                                   |
|                                           |verified without manual review of every    |   the item                            |-  This requires manually reviewing an             |
|*(i.e., there is not a mismatch between an |record (i.e., not scalable for large       |                                       |   individual record to see if values              |
|item and a record describing a different   |collections).                              |                                       |   largely match the associated item               |
|item)*                                     |                                           |                                       |                                                   |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|All locally-required fields have values    |By definition, required fields should have |-  Any field required by the governing |**Possible issues to remediate:**                  |
|                                           |values, but *which* fields are required (or|   schema is not empty                 |                                                   |
|                                           |available for usage) varies too much among |                                       |-  Any record missing a value in a record          |
|                                           |schemas to be stated in a standardized way.|                                       |   that is deemed “required” by a local or         |
|                                           |                                           |                                       |   relevant consortial schema such as an           |
|                                           |                                           |                                       |   identifier, language, resource type,            |
|                                           |                                           |                                       |   etc.                                            |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|All conditionally-required fields have     |By definition, required fields should have |-  Any field required by the governing |**Possible issues to remediate:**                  |
|values                                     |values, but *which* fields are required (or|   schema under other conditions (e.g.,|                                                   |
|                                           |available for usage) varies too much among |   “required if available”) is not     |-  Any record missing a value in a record          |
|                                           |schemas to be stated in a standardized way.|   empty in records meeting those      |   that is deemed “required when available”        |
|                                           |                                           |   conditions                          |   by a local or relevant consortial               |
|                                           |                                           |                                       |   schema, e.g., fields labeled by DPLA as         |
|                                           |                                           |                                       |   “required when available”:                      |
|                                           |                                           |                                       |                                                   |
|                                           |                                           |                                       |   -   Collection                                  |
|                                           |                                           |                                       |   -   Language                                    |
|                                           |                                           |                                       |   -   Type                                        |
|                                           |                                           +---------------------------------------+---------------------------------------------------+
|                                           |                                           |-  Any field required by the governing |**Possible issues to remediate:**                  |
|                                           |                                           |   schema for a specific material type |                                                   |
|                                           |                                           |   is not empty in records for that    |-  Any record for a resource type that is          |
|                                           |                                           |   type                                |   missing a value that is “required for           |
|                                           |                                           |                                       |   <resource type>” by a local or relevant         |
|                                           |                                           |                                       |   consortial schema -- e.g., “creator is          |
|                                           |                                           |                                       |   required for ETDs”                              |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|Fields that require multiple parts or      |This is an extension of required field     |-  Any field that has a local          |**Possible issues to remediate:**                  |
|qualifiers have all parts                  |values, however, not all assessment        |   governing schema requiring a        |                                                   |
|                                           |considers values and other parts (like     |   qualifier has a qualifier value when|-  Any value missing a qualifier field             |
|                                           |qualifiers) in tandem and this also        |   content is present                  |   (e.g., for QDC or locally-qualified             |
|                                           |incorporates non-required fields when they |-  Any field that has a local governing|   metadata fields)                                |
|                                           |are in usage.                              |   schema requiring multiple components|-  Field values missing parts, e.g., if            |
|                                           |                                           |   has all parts                       |   both publisher name & publisher location        |
|                                           |                                           |                                       |   must be entered in a record and only one        |
|                                           |                                           |                                       |   is present                                      |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|Records have some type of subject value    |Subject-based fields contain some of the   |-  At least one subject-type field     |**Values that may be correct:**                    |
|                                           |only values that can help collocate related|   used by the governing schema has a  |                                                   |
|                                           |items across collections (including        |   value (e.g., subject, keyword,      |-  Terms from a local or general thesaurus,        |
|                                           |aggregations, like DPLA, Europeana, etc.)  |   genre, etc.)                        |   like LCSH                                       |
|                                           |more broadly by topic.  This also makes    |                                       |-  Subjects from a specialized list or             |
|                                           |subject-based values a good candidate for  |                                       |   thesaurus like MeSH, the Art and                |
|                                           |review and normalization, if needed.       |                                       |   Architecture Thesaurus, LC Medium of            |
|                                           |                                           |                                       |   Performance Terms, Chenhall's                   |
|                                           |                                           |                                       |   Nomenclature, Homosaurus, etc.                  |
|                                           |                                           |                                       |-  Genre terms from a local list or                |
|                                           |                                           |                                       |   controlled thesaurus, like the LC               |
|                                           |                                           |                                       |   Genre/Form Terms                                |
|                                           |                                           |                                       |-  Keywords relevant to the content of the         |
|                                           |                                           |                                       |   item                                            |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|A rights statement is present              |Inclusion of rights information is broadly |-  A value describing rights associated|**Values that may be correct:**                    |
|                                           |encouraged within the digital library      |   with the item is in the record      |                                                   |
|                                           |community.  Standardized rights statements |                                       |-  An item has a clearly-defined creative          |
|                                           |were developed through international       |                                       |   commons license listed in the record            |
|                                           |efforts.                                   |                                       |-  The record contains a statement                 |
|                                           |                                           |                                       |   asserting copyright and/or listing the          |
|                                           |                                           |                                       |   rights holder                                   |
|                                           |                                           |                                       |-  When possible, a standardized rights            |
|                                           |                                           |                                       |   statement is in the record;                     |
|                                           |                                           |                                       |   organizations should consider                   |
|                                           |                                           |                                       |   implementing these for shareability             |
|                                           |                                           |                                       |   (see:                                           |
|                                           |                                           |                                       |   https://rightsstatements.org/en/documentation/) |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|Stray character encoding has been removed  |This is a problem that tends to be         |-  Values do not include character     |**Possible issues to remediate:**                  |
|                                           |relatively easy to find programmatically   |   encoding strings, mark-up values, or|                                                   |
|                                           |and, depending on string matching, can make|   other non-displaying text (usually  |-  PDF character encoding, like "\&\#39\;" instead |
|                                           |a significant difference when terms are    |   pasted in from another source)      |   of an apostrophe                                |
|                                           |normalized.                                |                                       |-  LaTex or other technical mark-up, like          |
|                                           |                                           |                                       |   “.pi./sup +/, p”                                |
|                                           |                                           |                                       |-  MARC subfields in names or subjects, like “$c”  |
|                                           |                                           |                                       |   or “\|x”                                        |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|All "placeholder" values have been         |Placeholders can be an indicator of        |-  Values do not include any strings   |**Possible issues to remediate:**                  |
|replaced/removed and are not present in the|information that is missing or records that|   meant to be replaced with other     |                                                   |
|publicly accessible record                 |need review; they may also be easy to find |   text                                |-  The presence of text such as:                   |
|                                           |programmatically if placeholders are       |                                       |                                                   |
|                                           |applied consistently in local records.     |                                       |   -   YYYY-MM                                     |
|                                           |                                           |                                       |   -   {{{name}}}                                  |
|                                           |                                           |                                       |   -   [add info]                                  |
|                                           |                                           |                                       |   -   <date value>                                |
|                                           |                                           |                                       |   -   other placeholder text                      |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+
|Extremely problematic/offensive terms have |Although comprehensive review and revision |-  Any values identified by the        |**Note:**                                          |
|been removed or handled appropriately      |of records likely falls in the “ideal”     |   institution as priorities to remove |                                                   |
|                                           |category, it may be useful to think about  |   for remediation are no longer       |-  This will depend on historic local practice,    |
|                                           |that process iteratively and set           |   present                             |   collection content, and decisions made based on |
|                                           |first-level local priorities to address    |                                       |   current remediation practices; in some          |
|                                           |some problems more immediately.            |                                       |   locations, this may also be affected by         |
|                                           |                                           |                                       |   legislation or other policies                   |
+-------------------------------------------+-------------------------------------------+---------------------------------------+---------------------------------------------------+



****************
Ideal Benchmarks
****************
Ideal-level benchmarks are intended to describe a “perfect” metadata record, i.e.,  if all available information about a specific
item has been entered correctly, according to local standards.  Many of these benchmarks are more subjective or item-dependent and
not every benchmark will apply depending on system requirements.  All applicable benchmarks must be met for a record to be “ideal.”


+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Benchmark                                  |Metrics                                |Examples                                   |
+===========================================+=======================================+===========================================+
|All metadata values align with expectations|-  Values in every field align with    |**Values that may be correct:**            |
|for the material type                      |   usage guidelines according to the   |                                           |
|                                           |   local governing schema              |-  A creator for a photograph is           |
|                                           |                                       |   labeled as a photographer and a         |
|                                           |                                       |   creator for a book is labeled as an     |
|                                           |                                       |   author                                  |
|                                           |                                       |-  A thesis/dissertation has a creator     |
|                                           |                                       |   value (rather than "unknown")           |
|                                           |                                       |-  A published text item has a language    |
|                                           |                                       |   value (rather than "no language")       |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|When applicable, relationships between     |-  Field values reflecting             |**Values that may be correct:**            |
|items and parent collections are clearly   |   relationships are not empty in line |                                           |
|represented                                |   with the local governing schema     |-  "Collection" names (e.g., if this is    |
|                                           |                                       |   an available field)                     |
|                                           |                                       |-  Notes referencing a larger              |
|                                           |                                       |   collection or holdings                  |
|                                           |                                       |-  Link(s) to an archival finding aid,     |
|                                           |                                       |   catalog record, or similar              |
|                                           |                                       |   documentation for a collection          |
|                                           |                                       |-  Series title or archival series         |
|                                           |                                       |   information                             |
|                                           |                                       |-  Relation or source information          |
|                                           |                                       |   referencing a collection (depending     |
|                                           |                                       |   on local usage)                         |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Relevant recommended/optional fields have  |-  Recommended and optional fields are |**Note:**                                  |
|values                                     |   not empty when information is       |                                           |
|                                           |   available                           |-  This requires comparing an individual   |
+-------------------------------------------+---------------------------------------+   record to the item and any available    |
|All relevant information about the item is |-  Values accurately represent complete|   supplementary information sources (e.g.,|
|included                                   |   field information according to local|   catalog records, finding aids,          |
|                                           |   guidelines                          |   handwritten notes in physical           |
|                                           |-  When applicable, multiple entries   |   collections, information provided by a  |
|                                           |   (i.e., all relevant entries) are    |   donor or subject expert, etc.)          |
|                                           |   included in a field                 |   to determine if values have been entered|
+-------------------------------------------+---------------------------------------+                                           |
|Non-required qualifiers or field parts are |-  Qualifiers and field part values are|                                           |
|added to provide enhanced information or   |   not empty when information is       |                                           |
|functionality                              |   available                           |                                           |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|“Null” values are used consistently,       |-  Unused/non-populated fields are     |**Values that may be correct:**            |
|according to local guidelines              |   empty or contain specific required  |                                           |
|                                           |   text based on the local governing   |-  N/A, Not Applicable, Unknown (or        |
|                                           |   schema                              |   similar) -- if the schema requires one  |
|                                           |                                       |   of these values                         |
|                                           |                                       |-  Blank entry -- if the schema requires   |
|                                           |                                       |   unused fields to be left blank          |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Fields/subfields that cannot be repeated   |-  No non-repeatable fields occur      |**Possible issues to remediate:**          |
|occur only once                            |   multiple times in a record          |                                           |
|                                           |-  No qualifier or field part that is  |-  A record for a single item has multiple |
|                                           |   non-repeatable occurs multiple times|   formats                                 |
|                                           |   in a record                         |-  A record has multiple "creation" dates  |
|                                           |                                       |   if only one is allowed                  |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|All values are appropriate lengths for     |-  The total number of characters      |**Possible issues to remediate:**          |
|their fields                               |   and/or number of "tokens" (words or |                                           |
|                                           |   space-separated components) in each |-  Extremely short values (e.g., subjects  |
|                                           |   field value matches expectations of |   that are only 1 or 2 characters long)   |
|                                           |   the local governing schema          |-  Extremely long values (e.g., single name|
|                                           |                                       |   values more than 1,000 characters long) |
|                                           |                                       |                                           |
|                                           |                                       |**Note:**                                  |
|                                           |                                       |                                           |
|                                           |                                       |-  Expected lengths will depend on local   |
|                                           |                                       |   requirements, e.g., whether a field is  |
|                                           |                                       |   repeatable (one term per entry) or if   |
|                                           |                                       |   there is a single field with multiple   |
|                                           |                                       |   separated terms                         |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|All values that ought to align with        |-  Formatting for every field that     |**Values that may be correct**             |
|standards conform to applicable            |   aligns with a controlled vocabulary |                                           |
|vocabularies or rules                      |   or standard is valid according to   |-  Date formatting matches EDTF, W3C, or   |
|                                           |   the relevant authority              |   other date standard in use              |
|                                           |                                       |-  Names match LCNAF, VIAF, or other name  |
|                                           |                                       |   standards in use                        |
|                                           |                                       |-  Locations align with TGM, GeoNames, or  |
|                                           |                                       |   other location standard in use          |
|                                           |                                       |-  Subjects match LCSH, AAT, TGM, LCGFT,   |
|                                           |                                       |   MeSH, or other subject standard(s) in   |
|                                           |                                       |   use                                     |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|All values are spelled correctly           |-  There are no misspelled words       |**Notes:**                                 |
|                                           |-  Unusual spellings have been checked |                                           |
|                                           |   and verified                        |-  If available, a spell-checker may be    |
|                                           |                                       |   helpful (e.g., in a browser, text       |
|                                           |                                       |   editor, etc.)                           |
|                                           |                                       |-  Some values -- like names -- may require|
|                                           |                                       |   manual checking or verification against |
|                                           |                                       |   other sources                           |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Text fields use appropriate punctuation,   |-  Free-text fields meet any style     |**Possible issues to remediate:**          |
|grammar, abbreviations, etc.               |   requirements in the local governing |                                           |
|                                           |   schema                              |-  Text strings (not from controlled       |
|                                           |                                       |   vocabularies or authorities) that don't |
|                                           |                                       |   match local formatting requirements,    |
|                                           |                                       |   e.g.:                                   |
|                                           |                                       |                                           |
|                                           |                                       |   -   duplicated or missing punctuation   |
|                                           |                                       |       and spacing                         |
|                                           |                                       |   -   variations in capitalization or lack|
|                                           |                                       |       of capitalization in proper names   |
|                                           |                                       |   -   unexpected word order (e.g., names  |
|                                           |                                       |       or subjects)                        |
|                                           |                                       |   -   irregular alphanumeric patterns     |
|                                           |                                       |       (e.g., identifiers)                 |
|                                           |                                       |                                           |
|                                           |                                       |**Values that may be correct:**            |
|                                           |                                       |                                           |
|                                           |                                       |-  Text that matches the expected tense    |
|                                           |                                       |   (e.g., use of present or                |
|                                           |                                       |   present-progressive tense)              |
|                                           |                                       |-  Text written in "complete sentences" or |
|                                           |                                       |   written out in specific component parts,|
|                                           |                                       |   according to local requirements         |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Reading level & language use is appropriate|-  If there is a defined user group,   |**Values that may be correct:**            |
|for all (relevant) communities or audiences|   word choice and metadata values meet|                                           |
|                                           |   expectations for the audience       |-  Collections intended for students do not|
|                                           |                                       |   use language above the reading          |
|                                           |                                       |   grade-level of users                    |
|                                           |                                       |-  Materials intended for scientific       |
|                                           |                                       |   research have appropriate technical     |
|                                           |                                       |   terminology or phrasing, based on the   |
|                                           |                                       |   expectations of the particular field    |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Vocabulary usage aligns with the needs of  |-  If there is a defined user group,   |**Values that may be correct:**            |
|the audience and material type             |   controlled fields use values in line|                                           |
|                                           |   with audience expectations          |-  Use of MeSH terms in a medical          |
|                                           |                                       |   collection (or collection intended for  |
|                                           |                                       |   medical professionals) vs. LCSH or more |
|                                           |                                       |   general terms for a non-medical audience|
|                                           |                                       |-  Names come from the Union List of Artist|
|                                           |                                       |   Names (ULAN) for an art-related         |
|                                           |                                       |   collection                              |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Values connected to interface functionality|-  Metadata values associated with more|**Values that may be correct:**            |
|work                                       |   complex functionality function as   |                                           |
|                                           |   intended                            |-  Fields used locally for filtering       |
|                                           |                                       |   searches or browsing (e.g., dates,      |
|                                           |                                       |   subjects, locations, etc.) have values  |
|                                           |                                       |   that are normalized to collocate        |
|                                           |                                       |   information based on user selection or  |
|                                           |                                       |   input                                   |
|                                           |                                       |-  Values that become clickable links in   |
|                                           |                                       |   local systems (e.g., names, resource    |
|                                           |                                       |   types, genres, etc.) are normalized     |
+-------------------------------------------+---------------------------------------+-------------------------------------------+
|Record language has been evaluated/updated |-  Metadata field usage and values     |**Note:**                                  |
|to align with best practices related to    |   align with local best practices     |                                           |
|reparative metadata, inclusive language,   |                                       |-  This will depend on historic local      |
|etc.                                       |                                       |   practice, collection content, and       |
|                                           |                                       |   decisions made based on current         |
|                                           |                                       |   remediation practices; in some          |
|                                           |                                       |   locations, this may also be affected by |
|                                           |                                       |   legislation or other policies           |
+-------------------------------------------+---------------------------------------+-------------------------------------------+

