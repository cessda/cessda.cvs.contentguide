---
title: Versioning
parent: Home
has_children: false
is_hidden: false
nav_order: 070
---

# {{ page.title }}

If a published CV needs amendments, SL admin creates a new SL version,
makes the changes and marks the SL as ‘Ready to be translated’.
The system produces new version TL drafts for TL admins to work on, finalise, and mark ‘Ready to publish’.
At some point, SL admin publishes the vocabulary as a package, including the SL and all finalised TLs.

The versioning policy is based on an intellectual, or logical assessment of the nature of the change,
which distinguishes between major, minor and sub-minor changes in the vocabularies.
To reflect these distinctions, the version numbering system is based on a three-level structure (examples: 1.0.0, 1.2.3).
All version levels will always be included in the version number.

A change in the first digit of the version number will indicate a major change in the controlled vocabulary.
Major changes are any substantive amendments in the content or meaning of a vocabulary (concept scheme) or code (concept),
as specified below. Changes in the second digit of the version number will indicate a minor change.
Minor changes are changes in wording and  spelling in the source language, etc. (i.e., "form")
that do not involve changes in intellectual content or meaning. Major and minor changes affect the source language only.

A change in the third digit will indicate a sub-minor change. Sub-minor changes are changes in content of
language variants at vocabulary or code level, for instance, title, definition or descriptive term amendments
in any other languages than the source language. Sub-minor changes include the addition of a new language.

Major changes that may break the backward compatibility -  **X**.0.0 first digit changes

- Vocabulary definition is amended with meaning change in the source language.
- Code/concept is added.
- Code/concept is deprecated.
- Code is replaced by another code.
- Code value of a concept is changed.
- Code/concept definition change with meaning change in the source language.
- Descriptive term change with meaning change in the source language.

Minor change - 1.**X**.0 second digit changes

- Vocabulary long name (title) is rephrased in the source language with no meaning change, for example, due to a typo.
- Vocabulary definition is rephrased with no meaning change in the source language.
- Code/concept definition is added in the source language.
- Code/concept definition is rephrased without meaning change in the source language.
- Descriptive term is rephrased without meaning change in the source language.

Sub-minor change - 1.0.**X**  third digit changes

- Changes in any other languages than the source language that affect versioning, including:
- Vocabulary long name rephrased with no meaning change.
- Vocabulary definition amended with meaning change.
- Vocabulary definition rephrased with no meaning change.
- Vocabulary definition added.
- Code/concept definition is added.
- Code/concept definition is amended with meaning change.
- Code/concept definition rephrased with no meaning change.
- Descriptive term is amended with meaning change.
- Descriptive term rephrased with no meaning change.

In addition to a change in the version number, each new version of a CV will contain language-specific version history
on how the current CV compares to the previous version. If no version information is added for the language,
there are no changes in the content of that language variant. The changes will be documented using the following format:

CV long name rephrased: *Reponse Unit* changed to *Response Unit*

CV definition amended with meaning change: *AnalysisUnit*

CV definition rephrased: *ModeOfCollection*

Code added: *AutomatedDataExtraction*

Code deprecated: *SelfAdministeredQuestionnaire.FixedForm*, is replaced by *SelfAdministeredQuestionnaire.*

Code value changed: *Interview.FaceToFace.CAPICAMI* changed to *Interview.FaceToFace.CAPIorCAMI*

Code descriptive term amended with meaning change: From *Geographical* to *Geospatial*

Code definition added: *Longitudinal.Panel*

Code definition amended with meaning change: *Longitudinal.Panel*

Code definition rephrased: *SelfAdministeredQuestionnaire.CAWI*

Descriptive term rephrased: *Interview: Face-to-face: CAOI* rephrased into *Interview: Face-to-face: CAPI*

Descriptive term rephrased: *Haastattelu: Kasvokkainen haastattelu: CAOI* rephrased into
*Haastattelu: Kasvokkainen haastattelu: CAPI*  (an example in the language variant Finnish).
