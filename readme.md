Manual - SDG16 Survey Solutions Questionnaire Template
================
First draft as of 15/02/2021. To be extended and improved!

-   [Introduction](#introduction)
-   [First steps](#first-steps)
    -   [Accessing the template script](#accessing-the-template-script)
    -   [Copy the questionnaire script](#copy-the-questionnaire-script)
    -   [Adust the questionnaire
        settings](#adust-the-questionnaire-settings)
-   [Adjusting the template](#adjusting-the-template)
    -   [Cover Page](#cover-page)
    -   [Placeholders](#placeholders)
    -   [Variable labels](#variable-labels)
    -   [Section specific hints](#section-specific-hints)

## Introduction

The following manual aims to provide an overview on necessary steps to
be taken to adjust the CAPI/CATI questionnaire template script of the
SDG16 Survey Module using [Survey
Solutions](https://mysurvey.solutions/) and its [Designer
component](https://designer.mysurvey.solutions).

This, as a minimum, usually entails revising the cover page and its
identifying questions as well as adapting specific questions or
categorical answer options to the local context. The paper-based SDG16
Survey-based Indicators Questionnaire as well as the sections that
describe the questionnaire modules in the Implementation Manual
highlight all items that need to be considered and should be the main
reference point for contextualization of questions and answer options.

Please note that the following guideline does not provide an
introduction or training on the use of the Designer itself. Instead,
some experience and a basic understanding of the Designer and its
capabilities is assumed.

Nevertheless, if you are new to Survey Solutions, please find a list of
useful links below that are relevant to the SDG16 module script. They
might help you in getting an overview on the functionalities of the
Designer to be able to adjust the template script.

<details>
<summary>
Click for useful links to get started with Survey Solutions Designer
</summary>

The following links are a selection of the extensive documentation
provided by the Survey Solutions team at
<https://docs.mysurvey.solutions/>

#### Designer Interface

-   [Registration and Signing
    In](https://docs.mysurvey.solutions/questionnaire-designer/interface/registration-and-signing-in/)
-   [Questionnaire Designer
    Homepage](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-designer-homepage/)
-   [Questionnaire Edit
    Screen](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-edit-screen/)
-   [Sharing a
    questionnaire](https://docs.mysurvey.solutions/questionnaire-designer/interface/share-questionnaire/)
-   [Questionnaire
    Settings](https://docs.mysurvey.solutions/questionnaire-designer/interface/settings/)
-   [Questionnaire
    variable](https://docs.mysurvey.solutions/questionnaire-designer/components/questionnaire-variable/)
-   [Find and
    Replace](https://docs.mysurvey.solutions/questionnaire-designer/interface/find-and-replace-/)
-   [Compile](https://docs.mysurvey.solutions/questionnaire-designer/interface/compile/)
-   [Compile
    errors](https://docs.mysurvey.solutions/questionnaire-designer/messages/compile_errors/)
-   [Comments in
    Designer](https://docs.mysurvey.solutions/questionnaire-designer/toolbar/comments-in-designer/)

#### Common Design Problems

-   [Text
    substitution](https://docs.mysurvey.solutions/questionnaire-designer/techniques/text-substitution/)
-   [Formatting
    text](https://docs.mysurvey.solutions/questionnaire-designer/techniques/formatting-text/)

#### Questionnaire Testing

-   [Online
    Tester](https://docs.mysurvey.solutions/questionnaire-designer/testing/testing-your-questionnaire-with-the-online-tester/)
-   [Testing
    scenarios](https://docs.mysurvey.solutions/questionnaire-designer/testing/scenarios/)

#### Questionnaire Components

-   [Questionnaire
    Components](https://docs.mysurvey.solutions/questionnaire-designer/components/questionnaire-components-/)
-   [Create and Modify
    Components](https://docs.mysurvey.solutions/questionnaire-designer/components/create-and-modify-components-/)
-   [General Component
    Properties](https://docs.mysurvey.solutions/questionnaire-designer/questions/general-component-properties/)
-   [Variable
    names](https://docs.mysurvey.solutions/questionnaire-designer/components/variable-names/)
-   [Special Section: Cover
    Page](https://docs.mysurvey.solutions/questionnaire-designer/components/special-section-cover/)
-   [Static
    Text](https://docs.mysurvey.solutions/questionnaire-designer/components/static-text/)

#### Question Types

-   [Text
    Question](https://docs.mysurvey.solutions/questionnaire-designer/questions/text-question/)
-   [Numeric
    Question](https://docs.mysurvey.solutions/questionnaire-designer/questions/numeric-question/)
-   [Special values for numeric
    questions](https://docs.mysurvey.solutions/questionnaire-designer/questions/special-values-for-numeric-questions/)
-   [Categorical: Single-Select
    Question](https://docs.mysurvey.solutions/questionnaire-designer/questions/categorical-single-select-question/)
-   [Categorical: Multi-Select
    Question](https://docs.mysurvey.solutions/questionnaire-designer/questions/categorical-multi-select-question/)
-   [Date
    question](https://docs.mysurvey.solutions/questionnaire-designer/questions/date-question/)

#### Syntax Guide

-   [Full list of syntax guides for different type of
    questions](https://docs.mysurvey.solutions/syntax-guide/questions/)

</details>

## First steps

### Accessing the template script

To get access to the script itself, you need to share your Survey
Solutions credentials with the person who is the owner of the Survey
Solutions script of the SDG16 module. As of February 2021, kindly
approach [Peter Brueckmann](p.brueckmann@mailbox.org).

If you are not registered yet, please follow the steps described
[here](https://docs.mysurvey.solutions/questionnaire-designer/interface/registration-and-signing-in/).

After you have received a questionnaire sharing notification in your
mail, log in at <https://designer.mysurvey.solutions>

On your [Questionnaire Designer
Homepage](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-designer-homepage/),
click on the Tab “Questionnaires shared with me” at the top. The SDG16
module questionnaire template should be displayed there.

Click on the name of the questionnaire to access the questionnaire
script itself.

Please note, you will only receive “view” access. This means that you
will be able to view and
[test](https://docs.mysurvey.solutions/questionnaire-designer/testing/testing-your-questionnaire-with-the-online-tester/)
the questionnaire content, but not be able to modify nor share the
template itself.

To be able to adjust the template to your projects context and needs,
you will need to create a copy of the questionnaire. See below.

### Copy the questionnaire script

You will need to create your [own
copy](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-designer-homepage/#copy)
of the questionnaire to make use of all Survey Solutions capabilities
and to use the template for your own project.

To do so,

1.  Click on the “Questionnaires shared with me” tab on your
    [Questionnaire Designer
    Homepage](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-designer-homepage/)
2.  Click on the Action menu to the right of the questionnaire you would
    like to make a copy of
3.  Select copy from the menu
4.  Enter a name of the questionnaire of your preference. It may be in
    any language and contain multiple words, though it is still a good
    idea to keep it short. Please note: This name will be visible to
    interviewers, so keep it intuitive. You can also change the
    questionnaire name at any point (see below)
5.  Click on COPY

### Adust the questionnaire settings

Once you copied the template, you will be redirected to the script
itself. As a first step, ssers are advised to adjust the questionnaire
settings. See
[here](https://docs.mysurvey.solutions/questionnaire-designer/interface/settings/)
for a detailed description on how to access and adjust the settings.

Most importantly, users should rename the [questionnaire
variable](https://docs.mysurvey.solutions/questionnaire-designer/components/questionnaire-variable/)
following [requirements for variable
names](https://docs.mysurvey.solutions/questionnaire-designer/components/variable-names/).

You can also use the settings interface to
[share](https://docs.mysurvey.solutions/questionnaire-designer/interface/share-questionnaire/)
your questionnaire version with colleagues.

## Adjusting the template

You can build upon this copy of the template to develop your own
country/project specific SDG16 questionnaire.

While incorporating changes to question texts or instructions seem
trivial to be adjusted in the CAPI/CATI script, it might also imply
updating particular enabling or validation conditions. The following
sub-sections will highlight issues that users need to look out for.

Please note: Especially if Survey Solutions Designer users are not
involved in the adaption of the SDG16 module template, team members are
advised to keep track on the changes made, e.g. through the Word Track
Change feature, so that they can be reflected in the CAPI/CATI script as
well.

### Cover Page

The Cover Page is a distinct feature within the Survey Solutions
application and will require substantial revision by the user.

To get an understanding of this feature, users are advised to read the
documentation on the [Special Section: Cover
Page](https://docs.mysurvey.solutions/questionnaire-designer/components/special-section-cover/)
as well as the [Question Scope:
Identifying](https://docs.mysurvey.solutions/questionnaire-designer/questions/question-scope-/).
As the documentation states, the cover page may contain some of the
information that is present on an actual cover page of a paper prototype
and may also contain other information.

In regular survey scenarios, the content of the Cover Page is related to
the [Survey Solutions
Workflow](https://docs.mysurvey.solutions/headquarters/interviews/survey-workflow/),
in particular the idea and use of
[Assignments](https://docs.mysurvey.solutions/getting-started/assignments/).
Users are advised to discuss closely with their colleagues who will
prepare and maintain the pre-determined sample, if it exists, since the
variable names of the Questions on the Cover Page need to match the
variable names used during [uploading of
assignments](https://docs.mysurvey.solutions/headquarters/preloading/uploading-many-assignments-at-a-time/).

The template lists three exemplary Text Questions that can be used to
denote specific administrative levels. Users can delete those and or add
additional (types) of questions.

### Placeholders

Both throughout the paper-based as well as Survey Solutions CAPI/CATI
template, various placeholders have been included to allow for a simple
adjustment of the questionnaire content to a country-specific context.

Within the Survey Solutions script, these placeholders are indicated
through \[!!!NAME OF THE PLACEHOLDER!!!\]. Using the [Find and
Replace](https://docs.mysurvey.solutions/questionnaire-designer/interface/find-and-replace-/)
feature and the respective unique names of the placeholder will allow to
adjust reoccurring text objects swiftly.

Please find below a list of all placeholders that users are strongly
advised to Find and Replace during the adaption process.

<details>
<summary>
Click to see the list of placeholders
</summary>

-   <b>\[!!!INSERTCOUNTRY!!!\]</b>  
    This text item is to be used across the questionnaire in various
    question texts as well as interviewer instructions. This includes
    the Introduction Text, SCR1, EPE1 or PHV0, among others. Replace it
    with the respective country name in which the questionnaire is to be
    used. Discuss with your team which notation to use.  
    For example, for a project in the United Republic of Tanzania, one
    could find “\[!!!INSERTCOUNTRY!!!\]” and replace with “Tanzania”

-   <b>\[!!!INSERT COUNTRY NATIONALITY!!!\]</b>  
    Similar to placeholder above, denotes the applicable nationality
    (e.g. at D5). Based on the Tanzania example one could find
    “\[!!!INSERT COUNTRY NATIONALITY!!!\]” and replace with “Tanzanian”

-   <b>\[!!!LOCAL CURRENCY!!!\]</b>  
    Denotes the currency in which interviewer/respondents should report
    values, e.g. used at question D4. Replace with the short form of a
    countries currency.

</details>

### Variable labels

By default, Survey Solutions automatically exports the question text as
its [variable
label](https://docs.mysurvey.solutions/questionnaire-designer/questions/general-component-properties/#variable%20label).
Therefore, the large majority of questions in the SDG16 module template
are not labeled. This usually facilitates data analysis if end-users can
see the question text itself in the data.

It is up to the user to provide other specific labels which will be
associated to the variable name when exporting the data to a statistical
software package.

### Section specific hints

To be continued (soon)
