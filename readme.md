Manual - SDG16 Survey Solutions Questionnaire Template
================
2022/01/03

-   [Introduction](#introduction)
    -   [Designer Interface](#designer-interface)
    -   [Common Design Problems](#common-design-problems)
    -   [Questionnaire Testing](#questionnaire-testing)
    -   [Questionnaire Components](#questionnaire-components)
    -   [Question Types](#question-types)
    -   [Syntax Guide](#syntax-guide)
-   [First steps](#first-steps)
    -   [Accessing the template script](#accessing-the-template-script)
    -   [Copy the questionnaire script](#copy-the-questionnaire-script)
    -   [Adust the questionnaire
        settings](#adust-the-questionnaire-settings)
-   [Adjusting the template](#adjusting-the-template)
    -   [General notes](#general-notes)
        -   [Placeholders](#placeholders)
        -   [Variable labels](#variable-labels)
        -   [Unanswered questions](#unanswered-questions)
        -   [Multilingual Questionnaires
            (‘Translations’)](#multilingual-questionnaires-translations)
    -   [Section specific hints](#section-specific-hints)
-   [Disclaimer](#disclaimer)

## Introduction

The following manual aims to provide an overview on necessary steps to
be taken to adjust the CAPI/CATI questionnaire template script of the
SDG16 Survey Module using [Survey
Solutions](https://mysurvey.solutions/) and its [Designer web
application](https://designer.mysurvey.solutions).

This, as a minimum, usually entails revising the cover page and its
identifying questions as well as adapting specific questions or
categorical answer options to the local context. The paper source
questionnaire “SDG16 Survey-based Indicators Questionnaire” as well as
the sections that describe the questionnaire modules in the
Implementation Manual highlight all items that need to be considered and
should be the main reference point for contextualization of questions
and answer options itself.

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
January 2022, kindly approach [Peter
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

In the following, questions are referred to using the variable names as
used in the Survey Solutions Designer, which only in few cases deviates
from the paper source questionnaire.

### General notes

#### Placeholders

Both throughout the paper-based source questionnaire as well as Survey
Solutions CAPI/CATI template, various placeholders have been included to
allow for a simple adjustment of the questionnaire content to a
country-specific context.

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

-   **`[!!!INSERTCOUNTRY!!!]`**  
    This text item is to be used across the questionnaire in various
    question texts as well as interviewer instructions. This includes
    the Introduction Text, SCR1, EPE1 or PHV0, among others. Replace it
    with the respective country name in which the questionnaire is to be
    used. Discuss with your team which notation to use.  
    For example, for a project in the United Republic of Tanzania, one
    could find “\[!!!INSERTCOUNTRY!!!\]” and replace with “Tanzania”.
    Please note: Questions `d5_b`, `d5_c`, `d5_d` make use of [combo
    boxes](https://docs.mysurvey.solutions/questionnaire-designer/questions/categorical-single-select-question/)
    of which some categorical answer options include placeholder
    “\[!!!INSERTCOUNTRY!!!\]”. They can not be changed through [Find and
    Replace](https://docs.mysurvey.solutions/questionnaire-designer/interface/find-and-replace-/).
    Instead, manually download the list of categories, update the file
    using any text editor and re-upload again to the Designer.

-   **`[!!!INSERT COUNTRY NATIONALITY!!!]`**  
    Similar to placeholder above, denotes the applicable nationality
    (e.g. at D5). Based on the Tanzania example one could find
    “\[!!!INSERT COUNTRY NATIONALITY!!!\]” and replace with “Tanzanian”

-   **`[!!!LOCAL CURRENCY!!!]`**  
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

#### Unanswered questions

Contrary to other data collection software, in Survey Solutions any
question may be left
[unanswered](https://docs.mysurvey.solutions/questionnaire-designer/techniques/mandatory-required-questions/)
for reasons beyond the control of the questionnaire designer. That is,
there are no “mandatory/required” questions in the Survey Solutions
SDG16 CAPI template script.

Data quality systems during fieldwork need to account for this and
should monitor the frequency of unanswered questions which can not be
explained by interviewers (e.g through comments).

In addition, to highlight such unanswered questions during the interview
process itself, a red warning text is rendered at the end of each
section in case any unanswered questions remain in the respective
section (calculated using a variable with expression using [section
functions](https://docs.mysurvey.solutions/syntax-guide/functions/section-functions/)):

``` html
[ENUMERATOR:]<br><br>
<font color="red">
ATTENTION, THERE ARE %n_unansweredq_ds% UNANSWERED QUESTIONS IN THIS SECTION. YOU MUST NOT PROCEED BEFORE ANSWERING THE REMAINING QUESTIONS. 
</font>
```

Consider to rephrase these warnings based on the survey project
protocol. Further, in case you add sections, it is recommended to add
the warnings and variables accordingly.

#### Multilingual Questionnaires (‘Translations’)

The SDG16 Pilot CAPI template is developed in English and could be
administered immediately. However, in contexts where respondents of a
survey speak a (or multiple) different languages, one can include those
in an easy manner using the Survey Solutions software.

To this end, users need to use a dedicated excel file produced by the
Survey Solutions Designer, include the translation and upload the file
accordingly.

Users are advised to carefully read the instructions on [multilingual
questionnaires](https://docs.mysurvey.solutions/questionnaire-designer/toolbar/multilingual-questionnaires/).
In addition, please find below some instructions for translators.

<details>
<summary>
<b>Click for detailed instructions for Translators</b>
</summary>

***EXCEL FILE***

-   The CAPI Designer should provide the translators with a single Excel
    file produced by the Survey Solutions Designer template.
-   Translators must not rename the spreadsheet and must not convert to
    any other file format.

The most important columns in the excel template:

-   **Variable** - Indicating the variable name of a question as in the
    Questionnaire Designer, which in most cases aligns with the question
    coding in paper version of SDG16 template.

-   **Type** - Indicates which type of text item the respective row
    reflects. This includes

    -   Title - Question Text itself or titles of Sections
    -   Optiontitle - The categorical answer options at a question
    -   Instruction - Instructions displayed to interviewers below a
        question text
    -   Validation Message - messages flagged if a response triggers an
        inconsistency
    -   Special Values - Similar to Optiontitle, those are options
        interviewers can select at numeric questions

-   **Index** - Indicates the optioncode of a particular OptionTitle and
    usually should align with the paper-based source questionnaire

-   **Original text** - This column contains the text for which a
    translation can be entered. Depending on the type of text item (see
    column Type), it is either a question text, answer option,
    instruction etc.

-   **Translation** - Column in which the translation needs to be
    inserted

***GENERAL INSTRUCTIONS***

-   All sheets within the excel file are to be translated. Sheets
    starting with `@@_` are categories that appear multiple times
    throughout the questionnaire.

-   If the translator can’t or don’t need to translate the original text
    for any reason, the cell in column Translation should be left blank

-   One must not modify any other text/cells anywhere else in the
    spreadsheet, even if there is a typo in the original text (feel free
    to notify the Designer about any discovered typos or problems, but
    not in this file)

-   If there are more than one translations to be used (e.g. Russian and
    Kazakh), translators need to create a separate excel file. Do
    **NOT** include the separate translations into the same file,
    e.g. in a different column.

***TEXT SUBSTITUTION***

To improve the enumerators experience, the CAPI script makes use of
dynamic text substitution. Text substitutions render interview specific
information, which includes the answer to a question collected earlier
or a dynamic reference period, within question texts, instructions or
validation conditions denoted with an identifier enclosed in percentage
signs.

It is **very important** to include these text substitution when a new
language is transferred to the excel spreadsheet. It must be ensured
that there is no typo or white space within the enclosed percentage
signs. Further, any text within the enclosed percentage signs must
**NOT** be translated.

Example:

    SCR1. Please let me know if you have permanently lived in Kazakhstan for the past 12 months (since %myoi_minus1%) or not?

That is, translators need to include the `%myoi_minus1%` item into the
translation itself! For a Russian translation it would be similar to:

    Пожалуйста, дайте мне знать, если вы постоянно проживали в Казахстане  в течение последних 12 месяцев(с %myoi_minus1% года)или нет?

***HTML-TAGS***

Based on the paper-based source questionnaire, important text items
sometimes need to be highlighted, e.g. through underlining or writing
something in bold. In addition, paragraphs added on paper will help the
enumerator to read out complex/long text more easily.

In Survey Solutions, as in other software, this is achieved through
html-tags (e.g. `<u>TEXT</u>` for underlining). These html-tags needs to
be included in the translation and not to be distorted!

Example: D8.A. Do you have difficulty…<u>seeing, even if wearing
glasses</u>?

CAPI Designer:

    D8.A. Do you have difficulty...<u>seeing, even if wearing glasses</u>?

Translation:

    D8.A. Испытываете ли вы трудности со <u>зрением, даже если вы носите очки</u>?

</details>

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

-   **urb (Level of urbanisation)**  
    This question has [question
    scope](https://docs.mysurvey.solutions/questionnaire-designer/questions/question-scope-/)
    HIDDEN in the template and is therefore destined to be pre-filled
    during creation of assignments. Decide if you want to change the
    question scope to Interviewer or Supervisor. You could also discuss
    to delete this question from the interview script itself and rather
    create it during data analysis.

-   **datetime_interview**  
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

-   **INT1/Consent Form**  
    The Introduction Text / Consent Form is stored in a static text.
    Users are advised to revise it substantially according to local
    protocols and best practices! For example, delete/revise the
    existing placeholders, e.g. the approximate amount of minutes needed
    for the interview.

-   **consent**  
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

-   **d1**  
    Validation condition 3: Checks if respondent is younger than 18
    years. Adjust if you include younger respondents in your sample.

-   **d2**

    -   Category Titles should be mapped to nationally relevant types of
        education levels
    -   Consider to add validation conditions based on age reported in
        `d2`

-   **d3_b**  
    Add “intersex” only if country allows intersex as a third gender on
    birth certificates

-   **d4_a**  
    Adjust placeholder \[!!!INSERTCOUNTRY!!!\]

-   **d4_b and d4_d**  
    Makes use of [combo
    box](https://docs.mysurvey.solutions/questionnaire-designer/questions/categorical-single-select-question/).
    Uses list of all countries along with ISO 3166‑1 code. Download and
    adjust in case changes are necessary.

-   **d5_b, d5_c and d5_d** Attention! Adjust the placeholder
    \[!!!INSERTCOUNTRY!!!\] in the combo box: Download existing file,
    open the file using any text editor, replace the placeholder, save
    and upload new file to Designer.

-   **d5_e**  
    Adjust placeholder \[!!!INSERTCOUNTRY!!!\]

-   **d6**  
    Update category titles that are usually used to clarify ethnic /
    racial background

-   **d8**  
    Update category titles with nationally relevant denominations

-   **d11**  
    Update category titles based on national household level income
    statistics

-   **d14 (Proxy Respondent)**  
    Consider to add instructions based on the protocol that you define
    for proxy respondents. Such instructions could for example be
    displayed using a Static Text that is enabled if `d12==2`.

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

-   Variable **ips**  
    This variable is a dummy that takes values “1” and “0”. It resembles
    the family intimate partner status. According to the paper source
    questionnaire, it takes value 1 if any response to question
    `src3_a`, `src3_b` or `src3_c` is “Yes”. The expression makes use of
    the C# [conditional expression
    operator](https://docs.mysurvey.solutions/syntax-guide/cslanguage/syntax-guide-operators/#other).
    Carefully revise the expression if any of `src3_a`, `src3_b` or
    `src3_c` are dropped or revised.

</details>
<details>
<summary>
<b>Governance</b>
</summary>

-   **cv4_a** and **cv4_b**  
    Adjust category title for category value 1 based on election cycle
    in country.

-   **cv4_a** Amend to “legislative and presidential national elections”
    if this is ambiguous

-   **cv4_b** Adapt to the nationally used term for municipal elections
    in the local translation

-   **Introduction text** for sub-section *Last experience of public
    services (SPS)*  
    Adjust placeholder `[!!!PUBLICHEALTHCLINIC!!!]`

-   **sps_e1** Revise age range (5-18 years old) with the appropriate
    age range spanning primary and secondary education in the country

-   **sps_g1, sps_g3, sps_g5, sps_g6**  
    Government-issued identification documents need to be tailored to
    national context. If additional documents are listed, a new question
    for SPS.G3 needs to be added, e.g. `sps_g3_f`. In addition, include
    the respective document to the list of categorical answers at
    `sps_g6`.

-   **sps_g2**  
    Replace ‘civil registration services or other relevant agencies’
    with the name of the particular agency(ies) responsible for issuing
    such identification documents in the country

</details>
<!-- ##Corruption -->
<details>
<summary>
<b>Corruption</b>
</summary>

-   **CR2_INTRO**  
    If questions are added or removed from list of questions `cr1_a` to
    `cr1_o`, adjust the expression of the enabling condition for this
    static text accordingly. For example, if you remove `cr1_o`, revise
    expression to

        CountValue(1,cr1_a,cr1_b,cr1_c,cr1_d,cr1_e,cr1_f,cr1_g,cr1_h,cr1_i,cr1_j,cr1_k,cr1_l,cr1_m,cr1_n)>0

-   **Randomization**  
    Following the source questionnaire, one needs to randomly select a
    type of official for which bribery has occurred in the past 12
    months (YES responses to `cr2_*`). To allow for two ore more
    translations as well the constraint to not make use of
    [Rosters](https://docs.mysurvey.solutions/questionnaire-designer/components/rosters/),
    the template CAPI script follows a non-standard way of randomization
    using Survey Solutions. The following items describe aspects one
    needs to consider when adjusting the template.  
    **Please note:** Users are advised to adjust this section extra
    carefully.

    -   **cr2_a** - **cr2_o**  
        To uniquely identify the YES responses to the set of categorical
        single-select questions `cr2_a` - `cr2_o`, the respective
        category values for category title “Yes” need to be unique
        across the questions. `cr_2a` starts with `101`, `cr2_b` uses
        `102` and so forth. Double check the response codes of **all**
        questions if you add or delete a type of official from this set
        of questions `cr2_a` - `cr2_o`.  
        **Attention**: You need to use codes 100 or above for YES
        responses to have variable `CR2_SUM` correctly calculating the
        number of YES responses.

    -   **CR2_SUM**  
        This variable sums up the number of YES responses to questions
        `cr2_*`. It reflects the number of domains where bribery has
        occurred in the past 12 months. If a new type of official is
        added and therefore a new question for CR2. introduced,
        e.g. `cr2_p`, this newly added question needs to be included to
        the expression at `CR2_SUM`. The same applies vice versa,
        i.e. if any of `cr2_a` to `cr2_o` are removed, remove it from
        the expression at `CR2_SUM`.

    -   **CR2_SEL_code**  
        This variable randomly selects the category value from the list
        of YES responses to questions `cr2_*`. For example, if `cr2_n`
        was among the list of yes responses and has been randomly
        selected, the variable will store the code `114`. Similar to
        `CR2_SUM`, add or remove questions from the expression as
        necessary.  
        **Attention**: You must keep the “Do not export” checkbox
        **unticked**, as this variable will need to be available in the
        data after export to draw conclusions on which type of official
        has been randomly selected.

    -   **CR2_SEL**  
        To display the selected type of official in subsequent
        instructions in at least one language, `CR2_SEL` is used. To
        this end, the [conditional expression
        operator](https://docs.mysurvey.solutions/syntax-guide/cslanguage/syntax-guide-operators/#other)
        is used. Adjust the list of type of officials along with their
        respective code. The value is again based on the code of “YES”
        responses from `cr2_a` - `cr2_o`.  
        **Attention**: Carefully double check that all conditions in the
        expression match the respective type of official E.g. if you
        rephrase `cr2_l` and use a different code, e.g. change from
        `112` to `138`, adjust the expression accordingly:

            [....]
            CR2_SEL_code==111 ? "Public utility officials or inspectors (electricity, water, sanitation, etc.)" :
            CR2_SEL_code==138 ? "X/Y/Z Type of public official" :
            CR2_SEL_code==113 ? "Car registration or driving licence agency officials" :
            [....]

        **Translation**: If you are using a translation in addition to
        the English Original Text, you will need to manually replace the
        English elements in the string array at `CR2_SEL` with the
        respective translations of the type of officials. If there are
        more than one translations to be used, unfortunately, you’d need
        to decide which main language should be used since only one
        language can be defined here.

    -   **Static Texts of type of officials**  
        There are 15 separate static texts placed before `cr4_a` that
        contain the respective type of officials. Each static text is
        enabled if the respective type of official has been randomly
        selected at `CR2_SEL_code`. As before, users need to adjust the
        content and/or enabling conditions of these static texts if
        changes to `cr2_a` - `cr2_o` are introduced.  
        **Purpose**: These static texts will also be included in the
        [questionnaire template in excel
        format](https://docs.mysurvey.solutions/questionnaire-designer/toolbar/multilingual-questionnaires/)
        for translation. The aim is therefore to display the type of
        officials at least once in any language/translation if users
        need 2 or more translations, which is not possible at `CR2_SEL`.
        Since one can not use static texts for substitution, `CR2_SEL`
        is used to substitute the randomly selected type of officials in
        interviewer instructions at subsequent questions.

-   **cr5**  
    Adjust category titles to local currency unit with “natural” bands
    of similar worth to these USD values.

-   **cr8_a**  
    Adjust category titles of category values 2 and 3 based on names of
    respective national institutions. Additional institutions may be
    added for codes 04-07, where applicable.

-   **cr10**  
    Similar to `CR2_INTRO`, if questions are added or removed from list
    of questions `cr1_a` to `cr1_o`, this revision needs to be
    incorporated into the enabling condition of `cr10`. For example, if
    you remove `cr1_o`, revise expression to

        CountValue(1,cr1_a,cr1_b,cr1_c,cr1_d,cr1_e,cr1_f,cr1_g,cr1_h,cr1_i,cr1_j,cr1_k,cr1_l,cr1_m,cr1_n)>0

</details>
<details>
<summary>
<b>Discrimination (DS)</b>
</summary>

-   **ds3** and **ds4** Adjust the enabling condition if you add or
    remove any question to/from the set of questions `ds2_a` - `ds2_x`.
    Needs to be ensured that any ‘YES’ response of discrimination in
    past 12 months is captured

</details>
<!-- ##ACCESS TO JUSTICE -->
<details>
<summary>
<b>Access to Justice (AJ)</b>
</summary>

-   **Introduction Static Text**  
    Substitute placeholder \[!!!EVENT OF NATIONAL RELEVANCE THAT IS
    COMMON KNOWLEDGE!!!\] accordingly to country context

-   **aj1_g**  
    Revise examples in question text if necessary: Lack of access to
    water and electricity to be added only if state managed.

-   **Randomization**  
    Following the source questionnaire, one needs to randomly select a
    dispute which has occured in the past 12 months (YES responses to
    `aj1_*`). To allow for two ore more translations as well the
    constraint to not make use of
    [Rosters](https://docs.mysurvey.solutions/questionnaire-designer/components/rosters/),
    the template CAPI script follows a non-standard way of randomization
    using Survey Solutions. The following items describe aspects one
    needs to consider when adjusting the template.  
    **Please note:** Users are advised to adjust this section extra
    carefully.

    -   **aj_a** - **aj1_k**  
        To uniquely identify the YES responses to the set of categorical
        single-select questions `aj_a` - `aj1_k`, the respective
        category values for category title “Yes” need to be unique
        across the questions. `aj1_a` starts with `101`, `aj1_b` uses
        `102` and so forth. Double check the response codes of **all**
        questions if you add or delete a type of dispute from this set
        of questions `aj1_a` - `aj1_k`.  
        **Attention**: You need to use codes 100 or above for YES
        responses to have variable `AJ_SUM` correctly calculating the
        number of YES responses.

    -   **AJ_SUM**  
        This variable sums up the number of YES responses to questions
        `aj1_*`. It reflects the number of types of disputes that the
        respondend experienced in the past 12 months. If a new type of
        dispute is added and therefore a new question for AJ1
        introduced, e.g. `aj1_m`, this newly added question needs to be
        included to the expression at `AJ_SUM`. Vice versa, if any of
        `aj_a` to `aj_k` are removed, remove the respective variable
        from the expression at `AJ_SUM`.

    -   **AJ1_SEL_code**  
        This variable randomly selects the category value from the list
        of YES responses to questions `aj1_*`. For example, if `aj_g`
        was among the list of yes responses and has been randomly
        selected by the software through expression at this variable
        `AJ1_SEL_code`, the variable will store the code `107`. Similar
        to `AJ_SUM`, add or remove questions from the expression as
        necessary.  
        **Attention**: You must keep the “Do not export” checkbox
        **unticked**, as this variable will need to be available in the
        data after export to draw conclusions on which type of official
        has been randomly selected.

    -   **AJ1_SEL**  
        To display the selected type of dispute in subsequent
        instructions in at least one language, `AJ1_SEL` is used. To
        this end, the [conditional expression
        operator](https://docs.mysurvey.solutions/syntax-guide/cslanguage/syntax-guide-operators/#other)
        is used. Adjust the list of disputes along with their respective
        code. The value is again based on the code of “YES” responses
        from `aj_a` - `aj1_k`.  
        **Attention**: Carefully double check that all conditions in the
        expression match the respective dispute. E.g. if you rephrase
        `aj1_e` and use a different code, e.g. change from `105` to
        `134`, adjust the expression accordingly:

            [....]
            AJ1_SEL_code==104 ? "Seeking compensation for INJURIES OR ILLNESS":
            AJ1_SEL_code==134 ? "XYZ TYPE OF DISPUTE":
            AJ1_SEL_code==106 ? "Problems with GOVERNMENT PAYMENTS":
            [....]

        **Translation**: If you are using a translation in addition to
        the English Original Text, you will need to manually replace the
        English elements in the string array at `AJ1_SEL` with the
        respective translations of the type of dispute If there are more
        than one translations to be used, unfortunately, you’d need to
        decide which main language should be used since only one
        language can be defined here.

    -   **Static Texts of type of disputes**  
        There are 11 separate static texts placed before `aj3` that
        contain the respective type of dispute. Each static text is
        enabled if the respective type of dispute has been randomly
        selected at `AJ1_SEL_code`. As before, users need to adjust the
        content and/or enabling conditions of these static texts if
        changes to `aj1_a` - `aj1_k` are introduced.  
        **Purpose**: These static texts will also be included in the
        [questionnaire template in excel
        format](https://docs.mysurvey.solutions/questionnaire-designer/toolbar/multilingual-questionnaires/)
        for translation. The aim is therefore to display the type of
        dispute at least once in any language/translation if users need
        2 or more translations, which is not possible at `AJ1_SEL`.
        Since one can not use static texts for substitution, `AJ1_SEL`
        is used to substitute the randomly selected type of officials in
        interviewer instructions at subsequent questions.

-   **aj5**  
    Adjust enabling condition of `aj5` in case any of the dispute
    questions `aj4_a`-`aj4_x` are removed or added. For example, if a
    question `aj4_i` is added, add it to the `CountValue` expression and
    adjust the right side of the expression:

        ```
        CountValue(2,aj4_a,aj4_b,aj4_c,aj4_d,aj4_e,aj4_f,aj4_g,aj4_h,aj4_i,aj4_x)==10

        ```

</details>
<!-- ##Physical violence -->
<details>
<summary>
<b>Physical violence (PHV)</b>
</summary>

-   **PHV_SUM**  
    If incidents are added to the list of PHV incidents during past 12
    months, e.g. new question `phv2_m`, include it in the expression of
    `PHV_SUM`. Vice versa, if any of `phv2_a-x` is removed, remove it
    from the expression at this variable.

-   **phv5**  
    Similar to `PHV_SUM`, if you add or remove any incident from the
    list of `phv*_a` - `phar*_x`, at `phv5` you need to:

    -   Adjust the list of categorical options. For example, if `phv*_g`
        is removed, delete category value 7 with title *“Beat you with
        their fist or a hard object, or kicked you”*

    -   Revise the filter expression. By default, the filter ensures
        that only incidents are displayed to the enumerator which
        actually took place in the past 12 months (based on `phv2_a` -
        `phv2_e`). If you add a question, e.g. `phv2_m` and the category
        value of this new category at `phv5` is 14, revise the
        expression to

            [....]
            phv2_l==1 && @optioncode==12  || 
            phv2_x==1 && @optioncode==13  || 
            phv2_m==1 && @optioncode==14  || 

            @optioncode>=98

-   **vr1**  
    Adjust categorical titles to match authorities in country. Use code
    13-19 for **formal** competent authorities, use code 21+ for
    **informal** authorities

</details>
<!-- ##SEXUAL VIOLENCE AND SEXUAL HARASSMENT -->
<details>
<summary>
<b>Sexual violence (SEV) and Sexual Harassment (SHAR)</b>
</summary>

**Sexual Harassment (SHAR)**

-   **SHAR_SUM**  
    If incidents are added to the list of SHAR incidents during past 12
    months, e.g. new question `shar2_h`, include it in the expression of
    `SHAR_SUM`. Vice versa, if any of `shar2_a-g` is removed, remove it
    from the expression at this variable.

    -   **shar5**  
        Similar to `SHAR_SUM`, if you add or remove any incident from
        the list of `shar*_a` - `shar*_g`, at `shar5` you need to:
        -   Adjust the list of categorical options. For example, if
            `shar*_c` is removed, delete category value 3 with title
            *“Unwanted MESSAGES, E-MAILS, CALLS OF A SEXUAL NATURE that
            offended you”*

        -   Revise the filter expression. By default, the filter ensures
            that only incidents are displayed to the enumerator which
            actually took place in the past 12 months (based on
            `shar2_a` - `shar2_g`). If you add a question,
            e.g. `shar2_h` and the category value of this new category
            at `shar5` is 8, revise the expression to

                [....]
                shar2_f==1 && @optioncode==6  || 
                shar2_g==1 && @optioncode==7  || 
                shar2_h==1 && @optioncode==8  || 

                @optioncode>=98
    -   **vr2**  
        Adjust categorical titles to match authorities in country. Use
        code 13-19 for **formal** competent authorities, use code 21+
        for **informal** authorities

    **Sexual violence (SEV)**

    -   **SEV_SUM**  
        If incidents are added to the list of SEV incidents during past
        12 months, e.g. new question `sev2_i`, include it in the
        expression of `SEV_SUM`. Vice versa, if any of `sev2_a-h` is
        removed, remove it from the expression at this variable.

    -   **sev5**  
        Similar to `SEV_SUM`, if you add or remove any incident from the
        list of `sev*_a` - `sev*_h`, at `sev5` you need to:

        -   Adjust the list of categorical options. For example, if
            `sev*_c` is removed, delete category value 3 with title
            *“Someone MADE YOU HAVE SEXUAL INTERCOURSE when YOU COULD
            NOT REFUSE owing to the influence of alcohol or drugs”*

        -   Revise the filter expression. By default, the filter ensures
            that only incidents are displayed to the enumerator which
            actually took place in the past 12 months (based on
            `sev2_a` - `sev2_h`). If you add a question, e.g. `sev2_i`
            and the category value of this new category at `sev5` is 9,
            revise the expression to

                [....]
                sev2_g==1 && @optioncode==7  || 
                sev2_h==1 && @optioncode==8  || 
                sev2_i==1 && @optioncode==9  || 

                @optioncode>=98

    -   **vr3**  
        Adjust categorical titles to match authorities in country. Use
        code 13-19 for **formal** competent authorities, use code 21+
        for **informal** authorities

</details>
<!-- ##Psychological violence (PSV) and Non-sexual Harassment (PHAR) -->
<details>
<summary>
<b>Psychological violence (PSV) and Non-sexual Harassment (PHAR)</b>
</summary>

**Non-sexual Harassment (PHAR)**

-   **PHAR_SUM**  
    If incidents are added to the list of PHAR incidents during past 12
    months, e.g. new question `phar2_f`, include it in the expression of
    `PHAR_SUM`. Vice versa, if any of `phar2_a-e` is removed, remove it
    from the expression at this variable.

-   **phar5**  
    Similar to `PHAR_SUM`, if you add or remove any incident from the
    list of `phar*_a` - `phar*_e`, at `phar5` you need to:

    -   Adjust the list of categorical options. For example, if
        `phar*_c` is removed, delete category value 3 with title
        *“Somebody made OFFENSIVE OR THREATENING GESTURES to demean,
        insult or humiliate you”*
    -   Revise the filter expression. By default, the filter ensures
        that only incidents are displayed to the enumerator which
        actually took place in the past 12 months (based on `phar2_a` -
        `phar2_e`). If you add a question, e.g. `phar2_f` and the
        category value of this new category at `phar5` is 6, revise the
        expression to

<!-- -->

      [....]
      phar2_d==1 && @optioncode==4  || 
      phar2_e==1 && @optioncode==5  || 
      phar2_f==1 && @optioncode==6  || 

      @optioncode>=98

-   **vr4**  
    Adjust categorical titles to match authorities in country. Use code
    13-19 for **formal** competent authorities, use code 21+ for
    **informal** authorities

**Psychological violence (PSV)**

-   **PSV_SUM**  
    If incidents are added to the list of PSV incidents during past 12
    months, e.g. new question `psv2_k`, include it in the expression of
    `PSV_SUM`. Vice versa, if any of `psv2_a-j` is removed, remove it
    from the expression at this variable.

-   **psv5**  
    Similar to `PSV_SUM`, if you add or remove any incident from the
    list of `psv*_a` - `psv*_j`, at `psv5` you need to:

    -   Adjust the list of categorical options. For example, if `psv*_c`
        is removed, delete category value 3 with title *“Family member
        or intimate partner EXPECTED YOU TO ASK PERMISSION TO SEE A
        DOCTOR”*
    -   Revise the filter expression. By default, the filter ensures
        that only incidents are displayed to the enumerator which
        actually took place in the past 12 months (based on `psv2_a` -
        `psv2_j`). If you add a question, e.g. `psv2_k` and the category
        value of this new category at `psv5` is 11, revise the
        expression to

<!-- -->

    [....]
      psv2_i==1 && @optioncode==9  || 
      psv2_j==1 && @optioncode==10  || 
      psv2_k==1 && @optioncode==11  || 
      
      @optioncode>=98

-   **vr5**  
    Adjust categorical titles to match authorities in country. Use code
    13-19 for **formal** competent authorities, use code 21+ for
    **informal** authorities

</details>
<!-- ##Trafficking in persons for forced labour (TIP) -->
<details>
<summary>
<b>Trafficking in persons for forced labour (TIP)</b>
</summary>

-   **tip_5**  
    If any questions are added or removed from the list of questions for
    `tip_1a-tip1_g` or `tip_3a-tip_3f`, adjust the expression of
    enabling condition at `tip_5` accordingly

-   **TIP_VOT_12M and TIP_VOT_3Y**  
    These variables indicate if the respondent was victim of trafficking
    for forced labor in the past 12 months / 3 years. Similar to
    `tip_5`: Carefully revise the expression at these variables in case
    questions are added or removed within this module. The conditional
    expression is based on the source questionnaire.

</details>
<!-- ## Unanswered questions remaining -->
<details>
<summary>
<b>UNANSWERED QUESTIONS REMAINING!</b>
</summary>

To further ensure no questions are left
[unanswered](#unanswered-questions) by mistake, this section is enabled
in case any of the previous sections contain any unanswered questions. A
list of static texts is displayed that contain a hyperlink to the
respective section to facilitate locating these ‘blank’ questions.

-   **Enabling condition**  
    Adjust the enabling condition in case you add or remove any section
    compared to the template script.

-   **Static Texts**  
    Add or remove any of the existing static texts within that section.
    For example, in case you add a section “Household Assets”, assign
    this section the [variable
    name](https://docs.mysurvey.solutions/questionnaire-designer/components/variable-names/)
    `sec_assets` to that section. Add within section “UNANSWERED
    QUESTIONS REMAINING” a static text that is enabled if
    `!IsSectionAnswered(sec_assets)`

</details>

## Disclaimer

Please report any issues with the manual or the Survey Soltuions SDG16
CAPI template script.

No responsibility or liability for the correct functionality of the CAPI
script nor the completeness of this manual is taken!
