.. _how-is-sal-used:

How is SAL used
===============

General Discussion
------------------

A primary function of source language analysis is the resolution of ambiguities regarding the function and meaning of words and phrases.  For example, the following strings both have a similar syntactic structure:

                      1)   to citizens of Rome and friends

                      2)   to citizens of Rome and environs

yet it is clear that they parse very differently.  

Seen purely as a syntactic string,

                    PREP1 N1 PREP2 N2 CONJ N3

this string could be parsed in several ways, depending on how the scope of PREP1 and PREP2is interpreted:

                    PREP1 (N1 PREP2 N2)) CONJ N3

                    PREP1 (N1 PREP2 N2 CONJ N3)

In order to resolve correctly, some handle on meaning must be available to the parse.  This handle is provided by the semantico-syntactic representation afforded in SAL.  Here is a simple example of how SAL codes (at the most general, Superset level) are used to resolve structural ambiguity:

                      1)   to citizens of Rome and friends

                              to  N(HUM) of N(PLACE) and (HUM)

                      2)   to citizens of Rome and environs

                              to N(HUM) of N(PLACE) and N(PLACE)

Because of the semantic symmetry of the SAL classifications shared by the first and last nouns (citizens and friends) in (1), the Logos parser would interpret the preposition to as applying to both.  By the same token, in (2), because Rome and environs are semantically symmetrical, the preposition of is seen as apply to both

.. rst-class:: center

    \*\*\*

How SAL is used to resolve ambiguity as to part of speech.  

* Many Verb Particles are homographic with prepositions, and often the parser has difficulty in resolving this ambiguity.  For example:
   
    1)  He turned in the driveway.
    2)  He turned in his badge.

  In (1), turned is an intransitive verb and in is a preposition.  In (2), turned is a transitive verb and in is a verb particle. The SAL code for driveway as a path in the Place Noun Superset would provide a critical clue to the intransitive, motional nature of turned in (1).

.. rst-class:: center

    \*\*\*

How SAL is used to resolve ambiguity regarding attachment of prepositional phrases.  

* Codes assigned to adjectives, e.g., to reflect preposition governance, are often of critical importance to parsing decisions. For example, in (1), below, the adjective tall is a non-governance type adverbial adjective, whereas in (2), adjacent is a prep governance type adjective, coded as governing the preposition "to".

        (1)  He built his garage tall to house his truck.
        (2)  He built his garage adjacent to mine.

  In (1), the particle to has the value of in order to (and house is properly seen as a verb). In (2), the governance code assigned to adjacent allows the parser to see to as a preposition (and mine as a pronoun). If adjacent has not been properly coded for governance here, very likely to mine would have been seen as an adverbial infinitive clause. The only intelligence the parser has to work with in order to properly analyze (2) is the prep governance code assigned to the adjective adjacent.


.. rst-class:: center

    \*\*\*

How SAL is used to resolve ambiguity regarding the scope of adjectives and prepositions.  

* Resolving the scope of adjectives in compound noun phrases is accomplished in a straightforward manner with the use of SAL codes.  For example:

        (1) smart boys and girls
        (2) blue sky and sunshine

  In (1), the adjective smart clearly applies to both boys and girls, but in (2), the adjective blue does not apply to both nouns in the compound NP.   Parsing rules test for symmetry or lack of symmetry among the SAL codes when making decisions about the scope of the descriptive adjective.  In (1), for example, both boys and girls are found to have the same SAL noun code, viz., HUM.  In (2), sky and sunshine are found to have different SAL noun codes and thus the parsing rule can limit the scope of blue to sky. This rather straightforward methodology obviously has its limits.  For example:

          (3) old people and children 

  In (3) the adjective old does not apply to both nouns, despite that fact that people and children are both HUM.  To resolve (3) correctly, the parser needs a finer grained semantic taxonomy than is afforded in SAL.  And even were such a fine-grained taxonomy in place (one in fact is presently under development), the question remains as to how general or how specific the test must be.   There are dangers in testing too finely as well as too coarsely.  And knowing what the appropriate level to test for is a good question.

.. rst-class:: center

    \*\*\*

How SAL is used to resolve ambiguity regarding verbs.  

* Codes assigned to adverbs, e.g., to reflect durative time vs. punctative time, are often of critical importance to translation decisions. For example, the distinction between the punctative set and the durative set in the Temporal Adverb Superset are important when translating into languages whose verbs are sensitive to time aspects.  For example, in Russian, the imperfective aspect of the Russian verb must be used to express sustained action;   the perfective aspect denotes completed action or time-specific action.  (In English the durative is usually expressed by the present progressive tense;  e.g. He was/is eating.)

  It is often difficult when translating English into Russian to know which aspect of the verb to use. In such cases, the classification of the adverb may be helpful. For example, the verb to drink would take the perfective in Russian in (1), below, and the imperfective in (2). 

  (1)  The doctor said I should never drink milk.
  (2)  The doctor said I must drink the medicine immediately.
  
  In (1), the durative adverb never indicates sustained repetitive action, expressed in Russian with the imperfective aspect.  In (2), the punctual adverb immediately calls for the perfective aspect of the Russian verb for drink.

  Note how in the following sentences the adverbial SAL codes for tense (or the absence of tense) is critical to the analysis of tense-ambiguous verbs like set, re-set, put, etc..
  
  (1)  They re-set the clock daily at noon.
  (2)  They re-set the clock yesterday at noon.
  
  In (1), the absence of a tense subset code for daily (a Frequency Superset Adverb) causes re-set to be seen as its default setting, i.e., present tense.  In (2), the past tense subset code for yesterday causes the parser to interpret re-set as past.
  
  Note that these adverbial codes also contribute to the interpretation of the verb's aspects (critical for translating into Russian).  

  Adverb codes can be helpful in resolving ambiguities regarding the BE + ADJ(ED) construction in the following types of sentences:
  
  (1) X is attached to Y
  (2) X is very attached to Y
  
  The parser would normally interpret is attached . . . in (1) as a passive VP, as in e.g., the picture is attached to the wall.  In (2), however, the pre-adverbial code of the adverb very would prevent a VP interpretation and would instead allow the parser to interpret is attached as BE + PREDADJ, as in John is very attached to his family. (Pre-adverbial adverbs are intensifier-type adverbs that can appear before both adverbs and adjectives.  There are six intensifier-type adverbs, each distinguished by its position relative to the morpheme that it intensifies.)

.. rst-class:: center

    \*\*\*


How SAL is used to resolve questions regarding the meaning of prepositions. 

* Prepositions frequently acquire their meaning from the word to which they are attached.  For example:

  (1) John put the book on chemistry on the shelf.

  In (1) both the meaning and the grammatical function of the preposition on differs in each of its instances.  In the first instance, on acquires the meaning of about or concerning because of its attachment to book.  A parsing rewrite rule for the following pattern effects this analysis:

      NP(INFORMATION TYPE) + PREP(on) + NP(~SURFACE)   -->  NP / (on = concerning)

  The SAL classifications INFORMATION and SURFACE provide the intelligence for this analysis.

  The SAL classification of the verb put also allows the parser to attach on the shelf to the verb. (The verb put has a SAL code which indicates governance for locative prepositions.)

.. rst-class:: center

    \*\*\*

How SAL is used to effect context-sensitive target transfers of source verbs, prepositions, and adjectives. 


* See SEMTAB rules for the verb, e.g. raise in TermBuiilder's View Function.   There you will find thirty rules governing the meaning and transfer for raise based on context.

.. rst-class:: center

    \*\*\*

Other typical uses of SAL.


* Parsing entails decisions regarding how sentence components relate.  In the following sentences, the SAL code of the adjective important provides information critical to such parsing decisions.

  (1)  It was important for the citizens of Boston that the team won.
  (2)  The coach held aloft the Keys to the City of Boston that the team won.
  (3)  It was important for the citizens of Boston to win this series.
  (4)  The team needed the support of the citizens of Boston to win this  series.

  In (1), the SAL code assigned to the adjective important [PCurgent type adjective] allows the Logos System's deterministic parser to interpret that the team won as a subordinate clausal complement to the adjective, and not as a relative clause as in (2).  This code also allows the parser to see the verb won as intransitive rather than transitive (as it is in (2)). 
  Similarly, in (3), the PCurgent code assigned to important enables a deterministic parser to interpret the infinitive clause to win this series as complementary to the adjective and not as adverbial to the sentence as in (4).  In (4), but not in (3), the particle to would be rendered in order to in the target language.


How SAL is used in RES
----------------------

First some General Facts About RES
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In English source, RES performs a macro-parse of the input sentence.  Specifically,  RES:

* tags every element as to part of speech
* resolves all words with multiple parts of speech (i.e. disambiguates syntactic homographs)
* identifies all clauses by type, including clausal subjects, clausal objects and clausal complements
* identifies the subject and predicate of every clause
* recognizes all transitions from one clause to another
* recognizes the syntactic function of all punctuation
* recognizes embedded parenthetical material and absolute constructions
* passes this information to subsequent steps of analysis (TRANs)

RES is a left-to-right, bottom-up parser that produces a single parse, not a parse tree.  RES also employs a top-down control function that constrains the parse.

To produce a single, correct parse, RES relies heavily upon the semantics of the SAL codes that represent the input sentence.  (RES also has a limited look-ahead capability, needed in order to avoid so-called "garden-path" situations.)

Some examples of how SAL codes effect parsing decisions in RES (in order of importance).  
*-to be developed-*

    1.  How SAL codes for MASS nouns effect parsing.

    2.  How SAL codes for VERBAL ABSTRACTS effect parsing

    3.  How SAL codes for AGENT nouns effect parsing. 

        SAL taxonomy for nouns contain a number of elements that can function as agents.  Some are specifcally labeled "agentive", others are "agentive" by implication.  These include the following: (to be expanded).

    4.  How SAL codes effect parsing of coordinate structures

    5.  How SAL codes effect parsing of relative clauses

    6.  How SAL codes effect etc. etc..


How SAL is used in SEMTAB
-------------------------

*-to be developed-*

How SAL is used in PARSE/TRAN
-----------------------------

*-to be developed-*


