---
title: Usage tab
parent: Home
has_children: false
is_hidden: false
nav_order: 040
---

# {{ page.title }}

This section shows how the CV is being used.

The usage information can be added using the 'Edit' button on the
right-hand side of the Usage tab. This opens a rich-text box to enable
you to add links, tables etc.

**Usage for DDI (and CESSDA) vocabularies.**

CVs that are used with the DDI standard have information on how they are used within various versions of DDI.

For example Mode of Collection vocabulary has the following usage information:

DDI-L 3.3

Module name: `datacollection`

Element name: [TypeOfModeOfCollection](https://docs.ddialliance.org/DDI-Lifecycle/3.3/xmlschema/schemas/datacollection_xsd/elements/TypeOfModeOfCollection.html)

[TypeOfPretestCollectionMode](https://docs.ddialliance.org/DDI-Lifecycle/3.3/xmlschema/schemas/datacollection_xsd/elements/TypeOfPretestCollectionMode.html)

DDI-L 3.2

Module name: `datacollection`

Element name: [TypeOfModeOfCollection](https://docs.ddialliance.org/DDI-Lifecycle/3.2/xmlschema/schemas/datacollection_xsd/elements/TypeOfModeOfCollection.html)

DDI-C 2.5

Element/attribute name: [collMode](https://docs.ddialliance.org/DDI-Codebook/2.5/xmlschema/schemas/codebook_xsd/elements/collMode.html)

Element XPath: `/codeBook/stdyDscr/method/dataColl/collMode`

You can create a hyperlink by overshadowing the text to be linked and
by clicking on the 'link' icon ![Image 29](images/image29.png "Image 29")
on the top row of the box and adding the URL there.

For translations of DDI and CESSDA vocabularies, it is best to copy
the Usage information from the SL version. Editing or translating the
copied Usage information text is discouraged, at least for DDI
vocabularies. This is because in future, the Vocabulary Service may enable
translations to inherit the SL Usage information and its updates
automatically. Any translations of it would therefore disappear, but
the advantage is that translators would not need to update Usage
information manually.

If SL admin amends the usage information in the SL (in English) after publication,
it is recommended that they copy this amended information to the TLs as well,
at least for CESSDA and DDI vocabularies. Otherwise there will be a discrepancy between
SL and TL usage information.
Alternatively, they inform the Service Owner so that the Service Owner can do the
copying or ask the TL admins to copy it.
