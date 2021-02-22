Manual - SDG16 Survey Solutions Questionnaire Template
================
First draft as of 17/02/2021. To be extended and improved!

-   [Introduction](#introduction)
-   [First steps](#first-steps)
    -   [Accessing the template script](#accessing-the-template-script)
    -   [Copy the questionnaire script](#copy-the-questionnaire-script)
    -   [Adust the questionnaire
        settings](#adust-the-questionnaire-settings)
-   [Adjusting the template](#adjusting-the-template)
    -   [General notes](#general-notes)
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
reference point for contextualization of questions and answer options
itself.

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

Before this questionnaire template will be made publicly available after
the pilot stage, you need to share your <u>Survey Solutions
credentials</u> with the person who is the owner of the Survey Solutions
script of the SDG16 module to get access to the script itself. As of
February 2021, kindly approach [Peter
Brueckmann](mailto:p.brueckmann@mailbox.org).

If you are not registered yet, please follow the steps described
[here](https://docs.mysurvey.solutions/questionnaire-designer/interface/registration-and-signing-in/).

1.  After you have received a questionnaire sharing notification in your
    mail, log in at <https://designer.mysurvey.solutions>

2.  On your [Questionnaire Designer
    Homepage](https://docs.mysurvey.solutions/questionnaire-designer/interface/questionnaire-designer-homepage/),
    click on the Tab “Questionnaires shared with me” at the top. The
    SDG16 module questionnaire template should be displayed there.

3.  Click on the name of the questionnaire to access the questionnaire
    script itself.

Please note, you will only receive “view” access. This means that you
will be able to view and
[test](https://docs.mysurvey.solutions/questionnaire-designer/testing/testing-your-questionnaire-with-the-online-tester/)
the questionnaire content, but not be able to modify nor share the
template itself. To work on your own questionnaire, you will need to
create a copy. See [below](#copy-the-questionnaire-script).

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
itself. As a first step, users are advised to adjust the questionnaire
settings. See
[here](https://docs.mysurvey.solutions/questionnaire-designer/interface/settings/)
for a detailed description on how to access and adjust the settings.

Most importantly, users should rename the [questionnaire
variable](https://docs.mysurvey.solutions/questionnaire-designer/components/questionnaire-variable/)
following [requirements for variable
names](https://docs.mysurvey.solutions/questionnaire-designer/components/variable-names/).

You can also use the settings interface to
[share](https://docs.mysurvey.solutions/questionnaire-designer/interface/share-questionnaire/)
your questionnaire with colleagues.

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

### General notes

#### Placeholders

Both throughout the paper-based as well as Survey Solutions CAPI/CATI
template, various placeholders have been included to allow for a simple
adjustment of the questionnaire content to a country-specific context.

Within the Survey Solutions script, these placeholders are indicated
through \[!!!NAME OF THE PLACEHOLDER!!!\]. Using the [Find and
Replace](https://docs.mysurvey.solutions/questionnaire-designer/interface/find-and-replace-/)
feature and the respective unique names of the placeholder will allow to
adjust reoccurring text objects swiftly.

Please find below a list of placeholders that reocurr multiple times.
Users are advised to Find and Replace those at the beginning of the
adaption process. Additional placeholders which are less frequent will
be mentioned in the [section specific hints](#section-specific-hints)

<details>
<summary>
Click to see the list of placeholders
</summary>

-   <b>`[!!!INSERTCOUNTRY!!!]`</b>  
    This text item is to be used across the questionnaire in various
    question texts as well as interviewer instructions. This includes
    the Introduction Text, SCR1, EPE1 or PHV0, among others. Replace it
    with the respective country name in which the questionnaire is to be
    used. Discuss with your team which notation to use.  
    For example, for a project in the United Republic of Tanzania, one
    could find “\[!!!INSERTCOUNTRY!!!\]” and replace with “Tanzania”

-   <b>`[!!!INSERT COUNTRY NATIONALITY!!!]`</b>  
    Similar to placeholder above, denotes the applicable nationality
    (e.g. at D5). Based on the Tanzania example one could find
    “\[!!!INSERT COUNTRY NATIONALITY!!!\]” and replace with “Tanzanian”

-   <b>`[!!!LOCAL CURRENCY!!!]`</b>  
    Denotes the currency in which interviewer/respondents should report
    values, e.g. used at question D4. Replace with the short form of a
    countries currency.

</details>

#### Variable labels

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

<details>
<summary>
<b>Cover Page</b>
</summary>

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

</details>
<details>
<summary>
<b>Introduction (INT)</b>
</summary>

-   <b>urb (Level of urbanisation)</b>  
    This question has [question
    scope](https://docs.mysurvey.solutions/questionnaire-designer/questions/question-scope-/)
    HIDDEN in the template and is therefore destined to be pre-filled
    during creation of assignments. Decide if you want to change the
    question scope to Interviewer or Supervisor. You could also discuss
    to delete this question from the interview script itself and rather
    create it during data analysis.

-   <b>datetime\_interview</b>  
    This
    [Date](https://docs.mysurvey.solutions/questionnaire-designer/questions/date-question/)
    question aims to capture current date and time when interviewer are
    starting the interview. Based on the value/answer of this question,
    Survey Solutions will render dynamically various reference periods
    across the questionnaire using [text
    substitution](https://docs.mysurvey.solutions/questionnaire-designer/techniques/text-substitution/).  
    Those reference periods are stored in the following variables which
    are placed into the Introduction (INT) section:

    -   `yoi` - Year of Interview (e.g. “2021”)
    -   `yoi_minus2` - Year of Interview minus 2 years (e.g. “2019”)
    -   `yoi_minus5` - Year of Interview minus 5 years (e.g. “2016”)
    -   `myoi_minus1` - Month and Year of Interview minus 1 year (e.g
        “August 2020”)

    Since it is important to capture an answer to `datetime_interview`,
    the current template contains a static text which is displayed until
    an answer is recorded. Interviewers will not be displayed the
    consent form and consent question until then. Adjust the respective
    enabling conditions if deemed necessary.

-   <b>INT1/Consent Form</b>  
    The Introduction Text / Consent Form is stored in a static text.
    Users are advised to revise it substantially according to local
    protocols and best practices! For example, delete/revise the
    existing placeholders, e.g. the approximate amount of minutes needed
    for the interview.

-   <b>consent</b>  
    The consent is obtained through a simple Yes/No question. You can
    consider to obtain verbally recorded consent through the use of
    question type
    [Audio](https://docs.mysurvey.solutions/questionnaire-designer/questions/audio-question/)
    or written consent using the
    [Picture](https://docs.mysurvey.solutions/questionnaire-designer/questions/picture-question/)
    question along with its [signature
    capture](https://docs.mysurvey.solutions/questionnaire-designer/questions/capturing-signatures-with-a-picture-question/)
    feature.  
    Users are advised to consider to add questions or static texts if
    respondents refuse to provide consent (`consent==2`). This often
    implies displaying instructions in static texts to interviewers that
    provide information on how to proceed, e.g. completing the interview
    and informing their supervisor, or asking the interviewer for
    reasons of refusal usingt text questions.

</details>
<details>
<summary>
<b>Socio-demographic variables</b>
</summary>

-   <b>d2</b>  
    Validation condition 3: Checks if respondent is younger than 18
    years. Adjust if you include younger respondents in your sample.

-   <b>d3</b>

    -   Category Titles should be mapped to nationally relevant types of
        education levels
    -   Consider to add validation conditions based on age reported in
        `d2`

-   <b>d0</b> and <b>d1</b>  
    Add “intersex” only if country allowed intersex as a third gender on
    birth certificates

-   <b>d4</b>  
    Consider to add validation conditions to flag error or provide
    warnings if very low or high values are reported. Must be based on
    local currency / income distribution.

-   <b>d4\_cat</b>  
    Update category titles based on national household level income
    statistics

-   <b>d4\_exp</b>  
    Don’t forget to adjust the placeholders “…\[!!!FILL IN AMOUNT
    HERE!!!\] \[!!!LOCAL CURRENCY!!!\]..” based on 25% of the monthly
    relative poverty threshold for a household of one component

-   <b>d6\_a</b>, <b>d6b</b> and <b>d6c</b>  
    Update category title for category value 1: Decide if “(The current
    territory of)” to be removed

-   <b>d7</b>  
    Update category titles that are usually used to clarify ethnic /
    racial background

-   <b>d9</b>  
    Update category titles with nationally relevant denominations

-   <b>d12 (Proxy Respondent)</b>  
    Consider to add instructions based on the protocol that you define
    for proxy respondents. For now, a simple static text is enabled if
    `d12==2`. Consider to revise the text of the existing static text,
    add additional questions and/or static texts etc..

    Please note: If you will not allow for proxy respondents, i.e. the
    interview shall be completed if `d12==2`, you’d need to update all
    enabling conditions for all subsequent sections to

        //Ask this section only if consent has been given and respondent answering him/herself  
        consent==1 && d12==1  

</details>
<details>
<summary>
<b>General screeners (SCR)</b>
</summary>

This section contains several questions that are referenced throughout
the questionnaire. If questions are dropped, carefully revise if this
has consequences in subsequent sections.

-   Variable <b>ips</b>  
    This variable is a dummy that takes values “1” and “0”. It resembles
    the family intimate partner status. According to the paper
    questionnaire, it takes value 1 if any response to question
    `src3_a`, `src3_b` or `src3_c` is “Yes”. The expression makes use of
    the C\# [conditional expression
    operator](https://docs.mysurvey.solutions/syntax-guide/cslanguage/syntax-guide-operators/#other).
    Carefully revise the expression if any of `src3_a`, `src3_b` or
    `src3_c` are dropped or revised.

</details>
<details>
<summary>
<b>Governance</b>
</summary>

-   <b>cv4\_a</b> and <b>cv4\_b</b>  
    Adjust category title for category value 1 based on election cycle
    in country.

-   <b>Introduction text</b> for sub-section <i>Last experience of
    public services (SPS)</i>  
    Adjust placeholder `[!!!PUBLICHEALTHCLINIC!!!]`

-   <b>sps\_e1</b> Revise age range (4-16 years old) with the
    appropriate age range spanning primary and secondary education in
    the country

-   <b>sps\_g1/sps\_g2/sps\_g5</b>, and <b>sps\_g3/sps\_g6</b>  
    Government-issued identification documents need to be tailored to
    national context. If additional documents are listed, a new question
    for SPS.G3 needs to be added, e.g. `sps_g3_f`. In addition, include
    the respective document to the list of categorical answers at
    `sps_g6`.

</details>
<details>
<summary>
<b>Corruption</b>
</summary>

-   <b>CR2\_SUM</b>  
    This variable sums up the number of YES responses to questions
    `cr2_*`. It reflects the number of domains where bribery has
    occurred in the past 12 months. If a new type of official is added
    and therefore a new question for CR2. introduced, e.g. `cr2_p`, this
    newly added question needs to be included the `CountValue(1,...)`
    expression at `CR2_SUM`. The sample applies vice versa if any of
    CR2.A. to CR2.O. are removed.

-   <b>cr4</b>  
    Similar to hint for `CR2_SUM`, adjust the list of category titles
    based on new or removed questions at `cr2_*`. In addition, adjust
    the filter expression. This expression at `cr4` ensures that only
    domains are displayed for which bribery actually has occurred (based
    on `cr(a-o)_1`).

-   <b>cr8</b>  
    Similar to hint for `CR2_SUM`, if questions are added or removed
    from list of questions CR1.A. to CR1.O., this revision needs to be
    incorporated into the enabling condition of `cr8`.

</details>

<br> To be continued (soon)
