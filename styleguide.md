This style guide introduces a collection of rules which facilitate the authoring of accessible documentation and ensure consistency of contents.

The rules given in this style guide are grouped based on their application to documentation. In outline, this style guide sets rules in the following groups:

*   **Storytelling**: how information is delivered to the target audience
*   **Grammar**: grammatical structures that should prevail
*   **Text**: how to use text components like lists, tables, and graphics

Each rule in this style guide has a title in the form of a concise statement and one or more recommendations to make the rule practical. When necessary, there is a short explanation which gives reasoning why a specific rule is actually needed.

**Audience**

We write for a global audience with different skill levels. The audience can be expert DBAs as well as non-DBA users. The language of documentation is standard American English.

**Conformance**

This guide is a living document and can change with time. It may not always match existing documents. The general recommendation is to follow this style guide when writing documentation. If in doubt, use the style guide than matching the style of older documents.

**References**

This style guide is based on and supplements several standard style guides and dictionaries. When in doubt or unable to find information in this style guide, look in these references:

[Google developer style guide](https://developers.google.com/style/tone)

 [Microsoft Style Guide](https://docs.microsoft.com/en-us/style-guide/welcome/) 

[Chicago Manual of Style](https://www.chicagomanualofstyle.org/home.html).

 [Merriam-Webster’s Collegiate Dictionary](https://www.merriam-webster.com/) 

/\*<!\[CDATA\[\*/ div.rbtoc1662031016811 {padding: 0px;} div.rbtoc1662031016811 ul {list-style: disc;margin-left: 0px;} div.rbtoc1662031016811 li {margin-left: 0px;padding-left: 0px;} /\*\]\]>\*/

*   [Overview](#StyleGuide-Overview)
*   [Storytelling](#StyleGuide-Storytelling)
    *   [Be Translation Friendly](#StyleGuide-BeTranslationFriendly)
    *   [Voice and tone](#StyleGuide-Voiceandtone)
    *   [Keep the Structure Simple](#StyleGuide-KeeptheStructureSimple)
    *   [Use Cross-References Appropriately](#StyleGuide-UseCross-ReferencesAppropriately)
    *   [Use spell and grammar checkers](#StyleGuide-Usespellandgrammarcheckers)
*   [Text](#StyleGuide-Text)
    *   [General guidelines](#StyleGuide-Generalguidelines)
    *   [Hyphens](#StyleGuide-Hyphens)
    *   [Paragraphs](#StyleGuide-Paragraphs)
    *   [Lists](#StyleGuide-Lists)
    *   [Headings](#StyleGuide-Headings)
    *   [Tables](#StyleGuide-Tables)
    *   [Graphics](#StyleGuide-Graphics)
    *   [Callouts and admonitions](#StyleGuide-Calloutsandadmonitions)
    *   [Code description](#StyleGuide-Codedescription)
    *   [Links](#StyleGuide-Links)
    *   [Legal information](#StyleGuide-Legalinformation)
    *   [Reference materials](#StyleGuide-Referencematerials)
*   [Grammar](#StyleGuide-Grammar)
    *   [Keep the Syntax Simple](#StyleGuide-KeeptheSyntaxSimple)
    *   [Capitalization](#StyleGuide-Capitalization)
    *   [Punctuation](#StyleGuide-Punctuation)
    *   [Spelling](#StyleGuide-Spelling)
    *   [Word usage](#StyleGuide-Wordusage)
    *   [Numbers](#StyleGuide-Numbers)
*   [Markup](#StyleGuide-Markup)

Overview
========

This style guide enables implementing the principle of _simple documentation_. While there may be different ways to understand what simple documentation is, this style guide sticks to the following definition:

> Simple documentation is a source of information about a software product which enables the target  
> audience to use the product effectively and efficiently, discover new features, and easily locate  
> all available information about the topics they are interested in by using their own language.

This definition implies that the documentation is perceived by the target audience to be simple. The structure and underlying routines, however, may be as complex as necessary.

Storytelling
============

This section contains general rules about how to make documentation accessible to the target audience. Its main focus is on the language of documentation as a whole. Each rule implicitly begins with **Compliant documents should ...**.

Be Translation Friendly
-----------------------

Many readers are not fluent in English and may find some grammatical structures (which are quite popular in English) confusing.

**Rules**

*   Do not use \*multiple attributes\* that precede a noun.
*   Do not omit \*that\* which introduces a subordinate clause.
*   Do not use such forms of expression as _jargon_ or _metaphors._
*   Do not use synonyms. Each concept should be referred to by only one term.
*   Reuse terms when referring to the facts you have already stated instead of using pronouns such as _it_, _they_, and so on to refer back to them.

Voice and tone
--------------

How you speak and write are usually different. You may speak in long sentences and use colloquial phrases. Traditional technical writing is formal and could be considered dry. The documentation should be clear, accurate, and direct, but also casual.

Write your documents with the user's needs and expectations in mind. Imagine that you are helping a professional acquaintance.

The target audience includes people who belong to different cultures. Remember that some forms of expressions that are normal for one culture are insulting for another. Sound professional, attentive, and emotionally neutral.

**Rules**

*   Write in a friendly, conversational, and respectful tone but don’t be frivolous. Do not use a _playful tone_.
*   Focus on facts, real user tasks, and real user benefits. Avoid promotional hype at all costs.
*   Write in second person and, where appropriate, in an imperative mood (e.g. “Do this”.)
*   Write in the present tense. Keep sentences short.  
    
*   Use active voice where possible. Passive voice is acceptable when any of these conditions is true:
    *   The system performs the action.
    *   It is more appropriate to focus on the receiver of the action.
    *   You want to avoid blaming the user for an error, such as in an error message.
    *   The information is clearer in passive voice.
*   Introduce abbreviations before using them. At the first occurrence in the document, an abbreviation should contain the expanded version in parentheses.
*   Do not write that something is _easy_ or _simple_.
*   Do not use subjective attributes such as _simple_, _efficient_, and so on in combination with the feature that you are describing. Subjective attributes are permissible if you intend to demonstrate these characteristics.
*   Remove modal verbs (must, may, could, should, etc.) if they do not add to the meaning of the sentence.

Keep the Structure Simple
-------------------------

Documents, like tutorials and manuals, are read from cover to cover. New information is based on what the reader already knows.

Technical documentation is not valuable as a standalone product but only in combination with a certain software product. Therefore, the reader must be involved in doing something with the product as soon as possible. Any digression makes it harder to follow the story and breaks the comprehension of information.

**Rules**

*   Do not give references to future sections which actually require knowing more than the reader knows at the point of reference.
*   When wriring release notes, make sure to list new version on top of the release notes list. Users seek for the new information so we should provide the easiest way to find it.
*   Structure the text in such a way that the reader is involved as soon as possible
*   Do not introduce graphics or tables as if they are a continuation of the current sentence.
*   Notes are a way to give additional information which actually does not belong to the current topic

Sometimes, however, it is hard to determine if a given paragraph belongs to the current topic or should be treated as additional information. In this case, do not transform this information into a note but start the sentence with **Note that ...**.

Use Cross-References Appropriately
----------------------------------

By using cross-references in manuals and in similar documents, you delegate telling part of your story to another part of your document or to an entirely another document. After reading the cross-referenced material, the reader should be able to return to the current story.

On the other hand, in documents that are used as references, such as release notes, glossaries, indexes, and so on, cross-references are a helpful tool which is should be used frequently. These types of documentation are not read from cover to cover: the reader must quickly locate the most specific information. 

**Rules for Manuals**

*   Do not cross-reference totally new material that the reader might not understand based on the current context.
*   Give references to material that may become outdated, such as external resources, in the **See also** section at the end of the current section.
*   Do not make cross-references a continuation of the current story: readers should be able to understand the current section even if they decide not to read the cross-referenced material.

**Rules for Reference Documentation**

*   Cross-reference each occurrence of valuable assets, such as identifiers of JIRA tickets, bug reports, or security issues. However, make sure that you do not refer the reader to restricted information which may not be disclosed in the given document.

Use spell and grammar checkers
------------------------------

Documentation with spelling and grammar mistakes looks unprofessional. Use spell and grammar checking tools (e.g. [Grammarly](https://grammarly.com/) or [LanguageTool](https://languagetool.org/)) to proofread your document.

Text
====

This section contains rules which are related to common text components such as paragraphs, headings, tables, and images.

General guidelines
------------------

In English, a mood indicates how a verb expresses an action or state of being. The three moods are:

*   Indicative
*   Imperative
*   Subjunctive

An Indicative mood is used to make a factual statement:

*   The software runs in the Linux operating system.
*   When starting, the application checks to see if another instance is running.

An imperative mood is used to express commands or requests:

*   Open the pod bay doors, Hal
*   Run the command from the terminal

A subjunctive mood is infrequently used and often is used when suggesting or recommending an action. The subjunctive mood may cause doubt.

*   It is important that only administrators should read the log
*   The example shows a type of variable you could use when starting the application

When writing, use either the indicative or imperative mood. Use the subjunctive mood when the information may be different for different users, such as presenting the output of a command (Your results should be similar).

**Guidelines:**

*   Wrap lines at 80 characters
*   Filenames. Suggestion: Use a “-“ as a word separator in filename

Hyphens
-------

Only hyphenate words when needed for clarity. For more information, see [Google developer documentation style guide - hyphens](https://developers.google.com/style/hyphens?hl=en)

Paragraphs
----------

Complicated syntax structures require additional effort to comprehend.

**Rules**

*   Break up long paragraphs (longer than 3-7 lines)
*   Make your text scannable: add sections, break paragraphs into lists
*   Do not use sentences with more than two clauses. Put conditional clauses before the instructions (e.g. For more information, see \[link to the document\])
*   Organize sentences in an intuitive manner. Move from common to specific, from known to unknown.

Lists
-----

Lists are used to organize information with a common subject or in a particular sequence.

**Rules**

*   Each list has an introductory sentence/paragraph. The introductory sentence can be either a complete sentence or a partial sentence. End the introductory sentence with a colon.  
    
*   Align the grammatical structure of every item in a list. For example, start each item with a noun or a verb. Avoid using an article.  
    
*   Make lists 2-7 items long. Transform shorter lists into paragraphs. Split too-long lists into several lists.
*   A multilevel list may not have more than two levels of nesting. The shortest sub-list is allowed to consist of two items at least.
*   A multilevel list should be balanced where each list item has a similar number of sub-items.
*   Avoid inline lists unless you enumerate simple known facts. Inline lists should not contain more than five items.
*   Use sentence punctuation if every item in a list is a sentence.
*   Do not use any punctuation, such as commas or semicolons, if list items are not sentences.
*   Use numbered lists if the order of items matters.
*   Use bullet lists if the order of items does not matter.
*   Use numbered lists if in doubt.

Headings
--------

Use the imperative style

Write titles using short, descriptive words

Focus on what the user can do rather than describe a feature

**Rules**

*   Do not use stacked headings: a subsection heading immediately following a section heading
*   Avoid using one or two word headings
*   Write brief but descriptive headings
*   Keep the structure of headings of the same level grammatically aligned
*   Avoid formatting headings (italic, bold, underlined, etc.) and using abbreviations (because they should be introduced first)
*   Don’t end headings with a period or a colon
*   There should be only one H1 in the document

Tables
------

Tables are a way to represent a sequence of items each of which is described by its attributes. Tabular data are organized either by columns or by rows.

In the column representation, the top row contains names of the attributes which describe items on the following rows. In the row representation, the first column contains the names of the attributes.

For items that are characterized by two dimensions, it is useful to have tables where one set of attributes appears as column titles and the other set (or dimension) appears as row titles.

**Rules**

*   Add a caption.
*   Add a lead-in paragraph.
*   Do not use consecutive tables.
*   Avoid using tables with columns or row spans.

Graphics
--------

Graphical objects such as diagrams or screenshots illustrate explanations given in text form in the same section. If possible, consider using image formats that support keeping the graphics up to date and putting them under revision control (e.g. an SVG file, or embed graphics using ascii art tools like [ditaa](http://ditaa.sourceforge.net/), [Mermaid](https://mermaid-js.github.io/mermaid/) or [blockdiag et. al](http://blockdiag.com/en/)).

**Rules**

*   Add a caption to each diagram or screenshot.

Callouts and admonitions
------------------------

Callouts emphasize important or helpful information. The following callouts are used:

<table class="wrapped confluenceTable"><colgroup><col style="width: 89.0px;"><col style="width: 1002.0px;"></colgroup><tbody><tr><td class="confluenceTd"><p><strong>Name</strong></p></td><td class="confluenceTd"><p><strong>Description</strong></p></td></tr><tr><td class="confluenceTd"><p><span>Tip</span></p></td><td class="confluenceTd"><p><span>Provides helpful suggestions or useful information to improve user experience or provide alternative ways of doing something</span></p></td></tr><tr><td class="confluenceTd"><p><span>Important</span></p></td><td class="confluenceTd"><p><span>Provides essential points to complete a task or understand a topic</span></p></td></tr><tr><td class="confluenceTd"><p><span>Warning</span></p><p><span>Caution</span></p></td><td class="confluenceTd"><p><span>Highlight critical information that users must be aware of to avoid data loss, system misbehavior, etc.</span></p></td></tr><tr><td class="confluenceTd"><p><span>Note</span></p><p><span>Info</span></p></td><td class="confluenceTd"><p><span>Provides information to supplement the main idea and /or help users better understand the topic. Also provides information that applies in certain cases.</span></p></td></tr><tr><td class="confluenceTd"><p><span>See also</span></p></td><td class="confluenceTd"><p><span>Provides additional materials (common cases, deeper context)&nbsp; that are related to the preceding text.</span></p></td></tr><tr><td colspan="1" class="confluenceTd">Example</td><td colspan="1" class="confluenceTd">Highlights examples</td></tr></tbody></table>

**Rules**:

*   Separate callouts with text paragraphs
*   Don’t stack callouts of the same type. Organize the content as a bullet list within a single callout
*   Avoid using code-block inside callouts

Code description
----------------

It’s recommended to split the command and its output into separate blocks

**Rules**

*   Write code samples for package installation without -y flag
*   Don’t use screenshots for code samples. Give the ability for users to copy & paste the code
*   Use spaces, instead of tabs for indentation
*   Remove white space from the end of lines (= no trailing tabs or spaces)

For code samples, use the following prompts:

```terminal
$> type a command here
#> type a command as root here
mysql> type a mysql statement here
```

Links
-----

Links are used to reference other parts of the document, other documents, and resources.

**Rules**

*   Do not refer to here, see this page, etc. Use the title of doc, section heading, name of the resource, or provide the full URL (not recommended).
*   When linking to another section, another document, or resource, use the following construction: **_For more information \[about ...\], see ..._** (Example: For more information about using Docker, see [Docker Documentation](https://docs.docker.com/).)

Legal information
-----------------

To protect the intellectual property of Percona, include the following documents in every doc project:

*   [Trademark](https://www.percona.com/doc/percona-server/LATEST/trademark-policy.html). It seems to be the same 
*   Copyright & license info. Clarify the licensing terms with the product owner

Reference materials
-------------------

Include reference materials to your doc projects to help users find useful information 

*   Release notes. Follow the [Release notes process](https://confluence.percona.com/display/DOC/Release+Notes+Process) to prepare release notes
*   API  - TBD
*   Config file options
*   FAQ
*   Dashboards reference
*   Glossary
*   Index

Grammar
=======

The grammatical structure of sentences is key to making the contents of the document easy to follow.

Keep the Syntax Simple
----------------------

Complicated syntax structures require additional effort to comprehend.

**Rules**

*   Do not use sentences with more than two clauses.

Capitalization
--------------

**Rules**

*   Capitalize all proper names. When referring to GUI elements, match the capitalization used on the interface
*   Use sentence-style capitalization in headings and captions
*   In text, capitalize the first word after a colon if it starts a complete sentence. In headings, always capitalize the first word after the colon.

Otherwise, if in doubt, don’t capitalize.

Punctuation
-----------

Use [American punctuation](https://www.thepunctuationguide.com/british-versus-american-style.html).

Spelling
--------

Use American spelling

Word usage
----------

**Rules**

*   Use **_enable_** instead of _allow_. Allowing is about giving permission. (Example: This feature enables you to ...)
*   Do not refer to images, tables, examples, lists using _above_ and _below_. Use _the_ **_following_** _table_ and _in the_ **_previous_** _example_.
*   One word are: _metadata, timestamp, filesystem_
*   Use **_As of version_** instead of _Starting from_ or another form. (Example: As of version 5.7, this variable is no longer available.)

Numbers
-------

*   Spell numbers from 1 through 9.
*   Spell numbers if a sentence starts with them (e.g. Three nodes in a cluster). However, it’s better to rewrite the sentence so that the number appears in the middle. 
*   Use dot in decimal numbers (e.g. 3.7)

Markup
======

Percona documentation is written in restructured text (.rst) and Markdown (.md)

To keep documentation format consistent, follow these specifications:

For restructured text: [OpenStack Docs: RST conventions](https://docs.openstack.org/doc-contrib-guide/rst-conv.html)

For Markdown: [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)