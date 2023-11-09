SAL Coding Tips
===============

**Coding tips for Nouns, for Adjectives, for Adverbs**


Tips on Coding Nouns in TermBuilder
------------------------------------

The easiest and most accurate method for encoding new nouns and noun phrases is presented below.

This instruction presupposes that you have used TermBuilder's AutoCode function to encode a new entry and that you have not yet actually updated the dictionary.   You should be looking in TermBuilder's New Entry Window where your entry and the automatically assigned codes are displayed. 

#. In the left-hand frame of TermBuilder's New Entry Window, scroll to Category (just below Part of Speech).  (Category will contain the SAL superset value automatically assigned by Auto Code.)
#. Click on the value shown in the row labeled Category.  A small box icon will display to the right.
#. Click on the box icon.  This will take you to the SAL Wizard.
#. In the SAL Wizard, you are presented with several options. The easiest and most accurate way to code your new entry is to use the "prompts" option.
#. Click on the "prompts" option.  If TermBuilder has some knowledge about your word, it will display all the meanings it knows to be associated with your entry (or with the head word of your entry if it is a compound noun phrase). (TermBuilder has a large store of information about basic nouns and their various meanings)
#. Click on the meaning that most applies.
#. If none of the meanings seem to apply, click on the "default" option. "Default" gives you a wide range of possible codes for you to choose from.
#. You must also click on the "default" option to code the entry in cases where the "prompts" option does not have a + sign before it, meaning that TermBuilder has no information about your entry. In such cases, AutoCode assignments cannot be relied upon and you should recode the entry using the "default" option, or the "SAL" option if available and appropriate
#. If you are tutored in SAL coding, and the "SAL" option is available on your system, you may click on "SAL".  This option gives you the full SAL taxonomy to work with and affords the most accurate codes possible.   Working with SAL, however, presupposes prior tutoring.

Overview of Noun Coding Methods
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. csv-table:: 
   :header: "TERMBUILDER OPTION", "DIFFICULTY", "ACCURACY", "COMMENT"
   :delim: |
   :widths: 10 20 20 40

    AutoCode     | easiest | lowest  | least recommended; should **not** be used if term is unknown to TermBuilder                    
    Prompts      | easy    | good    | the **recommended** method if TermBuilder has some prior knowledge of your head word           
    Default      | harder  | good    | the recommended method if your entry is completely unknown to TermBuilder's knowledge base 
    SAL Taxonomy | hardest | highest | the superior method, reserved for tutored users and developers                             



Guideline to SAL Noun Coding
------------------------------------


Nouns with Multiple Meanings
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Many nouns fall into more than one SAL category.  For example, passage can be both a conduit under :maroon:`Concrete`, and a path under :maroon:`Place`.   It can also be a piece of writing or musical composition under :maroon:`Information`.  

Selection among the multiple meanings of a given noun can often be effected by the use of Subject Matter Codes (SMC) when entering the term in TermBuilder. 

In some cases, however, Subject Matter Codes are not helpful.  In such cases, the user must make an arbitrary choice among SAL codes at the time the word is entered.  (Later development plans include giving the system the ability to resolve among the multiple meanings of a common noun on the basis of extra-sentential context.  This capability does not presently exist in the Logos System.)

When making coding decisions, users should observe the coding priorities listed below.

.. _noun-coding-priorities:

Noun Coding Priorities
""""""""""""""""""""""""""

There is a critical set of priorities governing coding choices for nouns that should be observed, if translation degradation is to be avoided.  The following represents the coding hierarchy in order of importance:

* Verb-biased Nouns (See :red:`verbal abstracts` set under :maroon:`Abstract Superset`).   Nouns coded for verb bias tell the system to expect a verb complement. 

  Verb-biased codes are critical for parsing.  For example:

          (1) ways of cooking lentils
          (2) types of cooking utensils. 

  The :red:`verbal abstracts` code given to ways in (1) biases the parser to expect a verb and therefore allows the parser to resolve cooking correctly to a verb.  In (2) cooking is an adjective.

* Nouns taking prepositional complementation.  (See :red:`strong verbals` under :maroon:`Abstract Superset`.)   For example:

  attitude towards
  interest in
  anxiety about
  phone connection to
  attention to

  Prep governance codes are critical for parsing decisions regarding prepositional attachement.

* :maroon:`Mass` Nouns.  Unlike count nouns, mass nouns can occur in the singular without an article or quantifier; e.g., Gold is expensive.

  :maroon:`Mass` codes are critical to parsing.  For example:

      (1) Test gold for . . .
      (2) . . . test tube for. . . .

  In (1), gold as a :maroon:`Mass` noun helps the parser to see test as a verb.  (Unlike count nouns, singular mass nouns without an article can be the object of a verb.)
  In (2), test must be a noun because tube is a singular count noun.

  :maroon:`Mass`-like codes occur in various places in the SAL noun taxonomy.   These include:

  *  :maroon:`Mass Superset`, which is mass by definition
  *  :blue:`trees/wood subset` (e.g. oak) under :maroon:`Concrete Superset` 
  *  :blue:`edibles/color subset` (e.g. orange) under :maroon:`Concrete Superset`
  *  :blue:`mammals/food/fur subset` (e.g. fox) under :maroon:`Animate Superset`
  *  :blue:`fowl/food subset` (e.g. duck) under :maroon:`Animate Superset`
  *  :blue:`remote mass subset`

* Nouns denoting agents.  Agentive type nouns occur in various places in the SAL noun taxonomy.  These include:

  * :maroon:`Animate Superset`, which is agentive by definition
  * :red:`agentive set` under :maroon:`Concrete Superset`
  * :blue:`functional location (agentive) subset` under :maroon:`Place Superset`
  * :blue:`geographical entities (agentive) subset` under :maroon:`Place Superset`
  * :blue:`remote agentive subset` (an optional subset code under any set or superset)

  See :ref:`sal-noun-code-hierarchy`.


Tips for Coding Descriptive Adjectives
-----------------------------------------

Note that participial adjectives (-ed, -ing, and -able forms) derive their codes from their verb form automatically. Users and developers cannot code participial adjectives.

_______________________________________________________

Adjective Coding Procedure
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Working from Right to Left, choose the first Row that fits your adjective and click on the associated Table.

.. csv-table:: 
   :header: "Attributive", "Predicate", "Convert. to Adverb*", "TO-V Comp.", "WH-Clause Comp.", "Table"
   :delim: |
   :widths: auto

    ADJ N | NP is ADJ | ADJ N = V ADV | NP is ADJ TO V | NP is ADJ THAT |
    Y     | Y         | Y             | Y              | Y              | Table A
    Y     | Y         | Y             | Y              |                | Table B
    Y     | Y         | Y             |                |                | Table C
    Y     | Y         |               |                |                | Table D
    Y     |           |               |                |                | Table D


\* Adjective Convertible to Adverb:  E.g., **slow** movement = move **slowly**

_______________________________________________________

.. csv-table:: Table A - Preclausal Adjectives
   :header: "It is ADJ that", "It is ADJ to v", "NP is ADJ to v", "NP is ADJ that", "ADJ type"
   :delim: |
   :widths: auto
 
    Y | Y | - | -       | :blue:`urgent` subset
    Y | - | - | -       | :blue:`clear` subset
    Y | Y | Y | limited | :blue:`certain` subset
    Y | Y | Y | -       | :blue:`good` subset
    - | - | Y | Y       | :blue:`happy` subset
    - | - | - | Y       | :blue:`aware` subset
  
\* Select the ADJ Type that most closely fits 

**RuleWriters' Note:** Preclausal codes are to be specified at the :maroon:`superset` or :blue:`subset` level only

 
.. csv-table:: Table B - Preverbal Adjectives
   :header: 
   :delim: |
   :widths: auto

    **It is ADJ to V** | **NP is ADJ to V** | **NP is ADJ V'ing** | **It is ADJ to V'ing** | **NP is ADJ to V'ing** | **NP is ADJ {in,with,of,etc.} V'ing** | **ADJ modifies SUBJ NP** | **ADJ Type**
    Y              | -              | -               | -                  | -                  | -                                 | -                    | :blue:`valid` subset
    -              | -              | -               | Y                  | -                  | -                                 | -                    | :blue:`akin` subset
    Y              | Y              | -               | -                  | -                  | -                                 | -                    | :blue:`easy` subset
    Y              | Y              | Y               | -                  | -                  | limited                           | Y                    | :blue:`wise` subset
    -              | Y              | -               | -                  | -                  | limited                           | Y                    | :blue:`eager` subset
    -              | Y              | Y               | -                  | -                  | limited                           | Y                    | :blue:`first` subset
    -              | -              | limited         | -                  | limited            | Y                                 | Y                    | :blue:`busy` subset

\* Select the ADJ Type that most closely fits 

**RuleWriters' Note:**   Preverbal codes should be specified at the :maroon:`superset` or :blue:`subset` level only

.. csv-table:: Table C - Adverbial Adjectives
   :header: "Description", "Examples", "SAL Adjective Type"
   :delim: |
   :widths: auto

    Adjectives governing  prepositions | adjacent  (to), compilant (with), famous (for) | :blue:`prep governance` subset
    Adjectives of state or manner      | clean, joyful, sly, personable                 | :blue:`state/manner` subset
    Adjectives of time or order        | recent, random, daily, final                   | :blue:`time/order` subset
    Adjectives of place                | above, backward, overseas, regional            | :blue:`locative` subset
    Adjectives ofquantity or measure   | minimal, slight, countless, lengthy            | :blue:`quantity/measure` subset
    Adjectives of degree or intensity  | real, utter, mere, entire                      | :blue:`degree` subset

\* Select the ADJ Type that most closely fits 


.. csv-table:: Table D - Non-Adverbial Adjectives
   :header: "Description", "Examples", "SAL Adjective Type"
   :delim: |
   :widths: auto
 
    Can be predicate adjective     | all purpose             | :blue:`predicate adjective` subset
    Cannot be predicate adjective  | Atlantic, bridal, naval  | :blue:`non-predicate adjective` subset




Tips on Coding Adverbs
-------------------------------------------


.. csv-table:: Intensifier Adverb Decision Table
   :header: "Placement", "Pre-Adv", "Pre-Nom", "Pre-Pre-Adv", "Pre-Adj", "Post-Nom"
   :delim: |
   :widths: auto
 
    Examples:         | extremely, tolerably, too, \*more, most | especially, just, only, even, strictly | \*much, really, so, somewhat | \*all, full, well, completely | \*enough, apiece
    Before Adv        | Y                                       |                                        | Y                            |                               |
    Before Noun       | \*                                      | Y                                      | \*                           | \*                            | \*
    Before Quantifier |                                         | Y                                      |                              |                               |
    Before Pre-Adv    |                                         |                                        | Y                            |                               |
    Before Adj        | Y                                       | Y                                      |                              | Y                             |
    Post-Noun         |                                         |                                        |                              |                               | Y
    Illustrations:    |                                         |                                        |                              |                               |
    Before Adv        | extremely well said                     |                                        | **much** more useful             |                               |
    Before Noun       |                                         | **just** cheese                            |                              |                               |
    Before Quantifier |                                         | **just** one day                           |                              |                               |
    Before Pre-Adv    |                                         |                                        | **really** too hot               |                               |
    Before Adj        | **extremely** adept                         | **just** ready                             |                              | **well**-received                 |
    Post-Noun         |                                         |                                        |                              |                               | food **enough**

\* Signifies that the morpheme before a noun becomes a determiner.
