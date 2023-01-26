---
title: Vocabulary management
parent: Home
has_children: false
is_hidden: false
nav_order: 010
---

# {{ page.title }}

## Creating and publishing a new source language CV

To create a new vocabulary you need to have SL admin rights in an agency.

Sign in (top right hand corner) and select 'Editor' from the top menu.
All actions that you can perform are presented as a series of buttons
in the list down the left hand side of the screen (depending on your
user role, these may vary).

- 'Add CV' allows you to start a new CV from scratch.

- If you click on one of the listed CVs, you will see 'CV actions'
  that allow you to make changes to the vocabulary as a whole,
  including options to add a new CV, add a translation,
  create a new version and delete a version of the vocabulary or the whole vocabulary.

For now, choose 'Add CV'. The system opens a pop-up window where you can add the basic information on the new vocabulary.
There are several mandatory fields to complete, marked with a red asterisk.

![Image 1](images/image1.png "Image 1")

A new draft vocabulary with a version number 1.0.0 DRAFT is created.
You can edit this draft using the editing buttons.

### Agency

Choose your Agency from the drop-down list. The agency you can choose depends on your
rights and role. If the Agency you require is not available you will
need to discuss the possibility to add it with the Service Owner of the
CESSDA Vocabulary Service.

### Language (source)

Choose the source language; for both CESSDA and DDI CVs, this is
English. Other source languages are available in the drop-down list.
The Vocabulary Service may also be used for in-house vocabularies.

### CV short name

This is a machine-actionable field, so read the instructions below carefully before giving the short name.

Add the short name for the CV. If you are entering a CV
that has already been published elsewhere, the same short name used
elsewhere should be used here. If you try to enter a short name
that already exists within the Vocabulary Service, the system will prevent you from
saving it.

The short name can be based on the human readable vocabulary name.
For instance, the short name of Mode of Collection vocabulary would be  ‘ModeOfCollection’.
It is formed by putting the words together and starting each word with an uppercase character.
The system only allows alphanumeric characters, as well as: ‘ +  ‘  -’   ‘ : ‘  characters.
Using abbreviations is not recommended. The short name can also be some other type of identifier
and not be based on the  name of the vocabulary.
Note that it still cannot hold other characters than specified above.

Please check the short name carefully before saving in case of errors.
**Important: read the naming rules carefully first and take care to ensure that whatever short name you enter,
it is correct from the start.**
As this machine-actionable name is one of the IDs for the vocabulary,
**the system prevents editing it once it has been saved.**

If you do make an error in the CV short name, you should proceed as follows:

If the CV is unpublished:

1\) Delete the SL vocabulary (if unpublished)

2\) Create a new CV with the corrected short name.

If the CV has already been published:

1\) Produce and save an export/download of the vocabulary in its
current state, including all language versions, for reference.

2\) Delete the CV. This will delete all versions of it and all other
language versions that have been created.

3\) Create a new CV with the corrected short name, copy pasting from
the saved file. Ensure that you enter the same version number and
version information as shown in your download. It is not possible to
bring earlier versions back to the system. You need to send the saved
file to translators and ask them to copy and paste their translation.
There is no copying functionality available yet, so it
is best **not** to make an error in the short name code, as recreating
the CV will mean a lot of manual copying. You can access the deleted
CV in the Editor.

If the CV already has several versions and language variants,
consult the Service Owner to discuss whether the technical admin can change the short name.
It may or may not be possible.

### CV name (human-readable title of the CV)

Next, add a name for the CV.

### CV definition

Add a definition that describes the vocabulary.

### CV notes

Optional element where information can be added or edited later in the Editor without having to change the version of the CV.
Notes do not therefore affect versioning. CV notes are notes that apply to the whole vocabulary.
For example, information that the vocabulary is meant for quantitative data only.

Now click on ‘Save’ to save the CV. Note: You will not be able to save the entry if the CV already exists,
i.e. the CV short names are identical.

## Adding codes and editing your new, not-yet-published CV

There are now several actions you can take.

![Image 2](images/image2.png "Image 2")

You can make changes to the vocabulary level fields you have already added by using the ‘Edit SL’ button.
If you close the pop-up window without saving,  no changes will be made.

![Image 3](images/image3.png "Image 3")

You can choose to delete your whole draft CV at any point before
publication. Click on 'Delete CV.' **Be careful with Delete CV; since
this is the first ever version of the vocabulary, the whole CV will be
erased. If needed, save a download/export of the draft CV in your
files before deleting.** Clicking on 'Cancel' in the deleting pop-up window
will retain the CV.

![Image 4](images/image4.png "Image 4")

‘Add code’ allows you to add codes (terms) within the CV.
The system adds the new code to the end of the vocabulary.
If you have already added codes and have clicked on an already added code before choosing ‘Add code’,
the system asks if you want the new code  to be added after or before this existing code or become its child (i.e. narrower code).

Complete the ‘Code value’ field, add the descriptive term and definition, and click Save.
If you would like to see the code on one line in the Details tab, you can extend column length by dragging on the line.

Code values are created in the SL and are the same across languages,
this way they function as identifiers for the codes.
DDI Alliance and CESSDA use code values based on human readable descriptive terms.
However, this has the consequence that if a descriptive term changes, the code value is changed as well.
This makes the code values less useful and  persistent as identifiers.
Code value changes should be extremely rare.
The system requires code values to be alphanumeric, but '+' '-' ':' are accepted as well.

Guidelines for creating code values for DDI Alliance and CESSDA:

A code value is a single word or a concatenation of several words.

- Each word starts with an uppercase character.
- Only alphanumeric characters are allowed, as well as: '+' '-' ':'
- No slashes (/) are allowed in the code value: they should be replaced with ‘Or’, e.g. EventOrProcess,
  or left out altogether, if it seems a better alternative.
- No abbreviations are allowed. Only a few exceptions are allowed in the case of acknowledged abbreviation code lists,
  such as the two-letter ISO code for the US.

Code values should be not too long, to ensure readability.
There is no hard rule, but it is reasonable to use no more than 5 words and 50 characters.
If spaces are added within a code, the system will automatically remove them.

The code value is just a code value, and its purpose is to be machine-actionable.
Search interfaces should search on the list of captions (descriptive terms) and/or definitions i.e. the human-readable part.

A pipeline from the CVS to the DDI Alliance controlled vocabularies website produces code-level persistent
identifiers for each code in DDI vocabularies.
These can be found in the SKOS/RDF exports of the vocabularies on the DDI Alliance website.

## Creating a hierarchy

CVs can be hierarchical. First, add the new code using the 'Add code'.
Then ‘Move code’ action can be used to create a hierarchy.

**Note that in the code value element only the value for the
individual term is to be entered in the code pop-up window; the hierarchy in
the code (i.e. broader term code value) is automatically added by the
system when the user uses the functionality ‘Move code’.**

Using 'Move code': Click on the code you want to move in the table in the Details tab,
and choose 'Move code' from the action buttons. In the moving pop-up window,
click on the code you want to move the other code next to and select
from the blue action buttons whether you want the other code to come
before or after or as a child.

![Image 6](images/image6.png "Image 6")

If you want to move *CodeYellow* to be the child of *CodeGreen*, click
on *CodeGreen* in the list on the right and select 'Insert as child'.
Now you see in the Code List the change made, with hierarchy
introduced into the code and can save.

If you now want *CodeRed* to be another child of *CodeGreen* but to
be placed above *CodeYellow*, click on *CodeRed* in the Details tab
table, and select 'Move code' from the actions. In the moving pop-up window,
click on *CodeGreen.CodeYellow* and select 'Insert before' as the
action. You can now see *CodeRed* in its right place as a child
above *CodeYellow*. Remember to save.

![Image 7](images/image7.png "Image 7")

Dragging is no longer possible in this
version of the software since it caused various problems. Note: Codes
can only be ordered within the SL - this is not an option for
translations.

## Editing codes

All edit buttons for a code will appear when you click on a code in
the table. Term-level values of the code are editable, unlike the
CV-level Short Name (see the CV Short Name section above).
Descriptive terms and definitions can be edited as well.

![Image 8](images/image8.png "Image 8")

The rest of the items can now be added to the CV.

Note that deleting a parent code (broader term) deletes the children
as well. If you want to keep the children, use 'Move code' pop-up window to
insert them before or after another broader code first. You can
rearrange the hierarchy later.

If entering codes from an already existing controlled vocabulary, you
can enter the codes by using the 'Import codes from CSV' functionality
(see [Import codes from CSV section](import-from-csv.html) for step by step details of how to do this).
This is quite complicated, so contact the Service Owner first.

![Image 9](images/image9.png "Image 9")

## Reviewing the CV

Once all the codes have been added, ordered and any changes have been
made the CV is ready to be reviewed. You can download your draft vocabulary in PDF or HTML
format in the ‘Export/Download’ tab  and ask others to review it.
When the vocabulary has been reviewed, change the status to 'Review'.

![Image 12](images/image12.png "Image 12")

The screen will display the vocabulary as it is after all changes
made. However, in 'Review' status, changes can still be made to all
parts of the CV.

## Adding usage information

Before finalising the vocabulary, consider whether you want to add something to the Usage section of the vocabulary.
For instance, for DDI vocabularies, information is added on which elements in the DDI standard this vocabulary can be used.

Usage information can be added or edited at any time in the Editor,
it does not affect versioning and does not therefore require creating a new version.

## Ready to be translated status and CV publication

Once you have carefully reviewed all information entered, including vocabulary and code-level information and the CV is finalised,
mark the vocabulary as ready to be translated by clicking on this button:

![Image 13](images/image13.png "Image 13")

In the following pop-up window, select the licence for the vocabulary.
If the licence you want is not in the drop-down list, interrupt the work for now by clicking on ‘Close’
and contact the Service Owner. The Service Owner can add the licence you want to the system. Once this is done,
return to this stage, click on ‘Ready to translate SL [source language code]’ again and select the relevant licence in the pop-up window.

The system suggests 1.0.0 as the version number as this is a new, never-published vocabulary.
If this is a vocabulary that has previously been published elsewhere and you want to keep the original version number,
enter the previous version number. The CVS system enforces a three-digit version number,
so if your vocabulary previously had a two-digit number, enter it (e.g. 2.1) and the version will be changed to a
three-digit number with 0 at the end (2.1.0). You cannot edit the third digit.

![Image 30](images/image30.png "Image 30")

When the SL vocabulary has been moved the ‘Ready to translate’ status, SL is frozen and language variants can be added
by Target Language admins.
If there are language variants to be created for the vocabulary, the SL admin gives a deadline by which time translations should be
finalised and moved to ‘Ready to be publish’ status.  When the deadline date has been reached, the SL admin can publish by clicking
on the ‘Publish CV’ button. Both the SL and all language variants that are at ‘Ready to be publish’ status are published. Only the
SL admin has the right to publish and has the ‘Publish’ button. TL admins do not have publishing rights.

Language variants that are in the ‘Draft’ or ‘Review’ status at the publication date  are not included in the publication package,
they remain in the Editor only. When these translations are finalised and moved to ‘Ready to be publish’ status,
they will be published at some point later,  at a time agreed between the SL and TL admins.

You can also just  save the information in the ‘Ready to be translated’ pop-up window without moving the status just yet.
Once the SL content  is ready to, click on the button again and move the status to ‘Ready to be translate’.

If no language variants are expected or needed, the SL admin can publish the vocabulary straight away.

![Image 31](images/image31.png "Image 31")

Publishing allows this version of the CV to be viewed by all.
See Usage tab and Licence and citation tab for information about the usage, copyright and licensing of CVs.

## Creating a new version of a SL CV

Once a CV has been published the SL cannot be edited; only translations can be added or amended.
To update the SL of a published CV, you need to create a new SL version. See [Versioning section](versioning.html)
for details on whether this will be a major or minor version of the CV.

![Image 14](images/image14.png "Image 14")

Choose 'Create new version' from the left hand side action.
The create new version pop-up window shows the current version information.

The version will have now changed to (DRAFT).

You now have the editing buttons:

![Image 15](images/image15.png "Image 15")

You can make changes to the CV-level information using the 'Edit SL
en' button. CV Notes can be edited at any time by using the 'Add
notes' or 'Edit notes' buttons, before or after publication, without
this affecting the versioning.

When you make changes you will also need to include a reason for the
change, selected from the drop-down list:

- CV name changed

- CV definition amended with meaning change

- CV definition rephrased

**Only one change can be made at a time - select the change type and
save.** If you need to make more CV-level changes, open 'edit SL'
again and make the next change, select the change type and save.
As the system only allows users to enter one change type at a time, it is
only possible to record all by making the changes separately.
The change logs needed for producing the version history in the publication pop-up window will then include everything.
If you accidentally made more than one change at a time, enter one
change type and make a note for yourself to add the other change
manually later to version change information.

Change information is needed for versioning and for letting users know what has changed.
This will allow them to keep their metadata and systems up-to-date.
There is also an option to describe the changes you
have made in more detail in the description field of change notes in the pop-up window.

Note: If you add or deprecate a code, the system records this change
automatically to the version changes.

When you want to edit a code, first click on the row of that particular code. Code editing buttons appear.
‘Edit code’ allows you to update the information about that code (code value, descriptive term and definition).
When you do this you will need to add a reason for the change (Type) from the drop-down list before you can save.
Make only one change at a time and choose a change type carefully, it is copied as such to the change logs and
Version changes field in the ‘Ready to be translated’ pop-up window. Your change choices are:

- Code value changed

- Code descriptive term rephrased

- Code definition amended with meaning change

- Code definition rephrased

There is also a non-mandatory field, 'Description', where you can add
any other information about the changes made, if needed, such as the
reason for the amendments. The field contains the code value of the code being edited as well, so do not remove that.

**You can cancel at any time and no changes will be made. Remember to
save if you have made changes. Take care to check that you have the
correct change type before saving.**

If you accidentally make more than one change at a time, select one appropriate change type
in the window and make a careful manual note to yourself of the other changes you made.
You  need to add them manually to ‘Version changes’ field in the ‘Ready to translate’ pop-up window.
Remember that it is vital for users to know what has been changed between the CV versions.

When everything is ready, click on Publish.

![Image 16](images/image16.png "Image 16")

At the  pop-up window you can see the changes between this version and the previous one by opening the change logs
and the comparison between the current and previous version.
Change logs include added and deprecated codes and the changes you selected from the change type list
in the code editing pop-up window.
The comparison table shows all changes between the two versions, even if you made two changes at the time in one pop-up window
(not recommended). It should therefore be used for checking that you document them all.

Finalise ‘Version changes’ field manually by adding any missing information, for example,
in which codes the changes have taken place.
Verify from the comparison and change logs that all the changes have been documented in this field and that none are duplicated.
Now you can also correct any errors in change type as this field is editable.

Check that all changes that have been made are documented according to
the rules of the DDI Alliance (CESSDA follows the same rules),
detailed on the controlled vocabularies web page under the versioning
policy:
[DDI Alliance Controlled Vocabularies](https://www.ddialliance.org/controlled-vocabularies).

If you added any free-text descriptions to editing pop-up windows, they are shown by the system at the top of the
‘Ready to translate’ pop-up window. Consider whether to add them to version notes.

**Check version number (see [Versioning section](versioning.html)), updating it if necessary.**

The 'Versions' tab will have details of all changes to the version visible for users.

It is possible to add or edit information in version notes and version
changes in the Versions tab after publication, so you can correct
mistakes made in version information after publication in the Editor without this
affecting the version number.

When everything is ready, click on ‘Ready to translate’ in the pop-up window.
The SL is frozen and TL admins can update their language variants.
At some agreed date, publish the new CV version by clicking on ‘Publish CV’.
The system will publish the amended SL and those TLs that were in the status ‘Ready to be published’.
The TLs that were not finalised remain in draft status and when finalised and moved to status ‘Ready to publish’,
can be published later at some agreed point by the SL admin. TL admins do not have publishing rights.

When the SL is in the status ‘Ready to translate’ but there are no language variants,
you can publish the CV straight away by clicking on the publish button.

![Image 17](images/image18.png "Image 17")

## Deleting a SL CV version or the whole vocabulary

Deleting a version: You can delete a new, unpublished version of the CV when the status is DRAFT, REVIEW or ‘Ready to translate’.
Click on ‘Delete SL’ and choose ‘Delete SL CV and TLs v. x.x.’
**Take care not to choose ‘Delete CV’ as this will erase all versions of the whole vocabulary and all its translations.**

![Image 18](images/image18.png "Image 18")

Please note that this action does not change the status of the CV to the previous status
(e.g. from READY TO TRANSLATE  to REVIEW) but drops the whole version, returning to the previous version of the CV.
There is no way to change status back once the version is dropped.
Returning to the previous status is never possible in the system.

Deleting the whole CV: This will erase the whole vocabulary and all
its translations. Do not do this without consulting the TL admins.
When you delete a CV from the system,
**the same CV short name cannot be reused for a new CV**.
The system prevents this and only a technical administrator can change this.
