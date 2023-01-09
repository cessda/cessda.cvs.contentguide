---
title: Lifecycle of a CV
parent: Home
has_children: false
is_hidden: false
nav_order: 060
---

# {{ page.title }}

This is a simplified version of the lifecycle for creation and publication of a vocabulary.

- Vocabularies are published as a package with all finalised language content included.
- SL admin creates a draft version of a CV in the source language.
- SL admin moves the status to review. The SL can still be edited.
- SL admin finalises the vocabulary. When satisfied that the SL CV is correct, SL admin moves the status to ‘Ready to translate’.
  The SL is frozen and cannot be edited anymore.
- TL admins can now begin their translation work. They add their TL version to the vocabulary if the language was not present before.
  If the TL had been added to the vocabulary earlier, the system copies the latest TL version as a new draft TL for them to work on.
- TL admins move the status to review. The TL can still be edited.
- TL admins finalise their version. When satisfied that the TL is correct, the TL admin moves the status to ‘Ready to publish’.
  The TLs in this status are frozen and cannot be edited anymore.
- At an agreed point in time, SL admin publishes the vocabulary. The published CV contains the SL and all TLs that were
  in the status ‘Ready to publish’ at the time of publication. TLs in draft or review status are not included.
- The CV is now visible to all users in the general search interface.
- If there are no other languages than the source language involved in the vocabulary, SL admin can publish the CV directly
  after moving the status to ‘Ready to translate’ by using the ‘Publish’ button and moving the status to ‘Published’.
- If a TL admin wants to make amendments to their language version without the SL changing,
  they create a new version of the TL vocabulary. When the version is finalised, they move the status to ‘Ready to publish’.
  If a new TL is added, the TL admin adds a new TL version, moves it from draft to review and when finalised, to ‘Ready to publish’.
  SL admin publishes the vocabulary again with the amended or added TLs that are in the ‘ready’ status at an agreed point in time.
  In this case,  the third digit of the vocabulary version number changes one up.
- When there is need for changes in a published vocabulary (concept scheme represented by the SL),
  SL admin creates a new SL version and a new cycle begins.
