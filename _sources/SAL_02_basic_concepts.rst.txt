Basic Concepts Regarding SAL
============================

What is SAL?
-------------

SAL is the internal representation language of the Logos System. SAL is an acronym for semantico-syntactic abstraction language.

The semantico-syntactic property of SAL means that it represents both the meaning and structure of natural language.

SAL is a language in its own right, not merely a set of so-called syntactic and semantic "primitives."  

Why is SAL called an abstraction language?
------------------------------------------------

Because natural language (NL) is far too rich and complex to be dealt with on its own terms in a computer, it must be simplified.  SAL achieves this simplification through abstraction. 

If NL can be thought of as a first-order abstraction language, SAL is a second-order language.  The simplification achieved through abstraction is fundamental to the processes of the Logos System.

The Logos System exploits simplification afforded by SAL by first translating the NL sentence into an SAL sentence.  What the system actually processes is a SAL sentence that represents the NL sentence at a higher level of semantico-syntactic abstraction.

SAL is an Intermediary Language
------------------------------------------------

In processing a sentence through the Logos System, the source language is re-expressed as SAL and from this SAL representation the target language is generated. 

SAL thus is a kind of intermediate language standing between source NL on the input side and the target NL on the output side.

In principle, from a single SAL representation of a sentence, any number of different target languages can be generated.  This is why the Logos Model is called a multi-target model.

One can map easily from NL to SAL.  In effect such mapping is precisely what a user does when he or she assigns a SAL code to a new entry in a TermBuilder session.

TermBuilder assists the user in this coding/mapping with a variety of options. See the SAL Coding Tips section below. TODO


SAL is a Taxonomy
------------------------------------------------

**SAL is a hierarchical taxonomy.**  As such, it constitutes a representational continuum from syntax (part of speech) to semantics (meaning).

For example, the word highchair can be represented on a semantico-syntactic continuum in SAL as follows:

* highchair -- literal word
* chair -- head morpheme
* supporting surface -- subset within SAL taxonomy
* functional thing -- set within SAL taxonomy
* concrete noun -- superset within SAL taxonomy
* noun -- part-of-speech within SAL taxonomy


**SAL is an ontology.**  This means that reality can be accounted for in SAL classifications.  In the case of nouns, the number of these classifications is roughly 100, which properly suggests that as a representation of reality, SAL is coarse-grained.

SAL attempts to implement certain assumptions about human language processing, chiefly with regard to the use of abstraction. Note that SAL is termed a semantico-syntactic abstraction language.  (more) TODO


What motivated SAL?
------------------------------------------------

First of all, SAL was motivated by the belief that the semantics of a word often affects the surrounding syntax. For example, all verbs that call for indirect objects (so-called "di-transitive" verbs) would appear to be semantically related, e.g. send, communicate, convey, give, transmit, provide, supply, etc. Thus one can relate the syntactic effect of di-transitive verbs to their semantics. 

SAL was designed to subcategorize words according to these property/effect relationships.

Thus, SAL seeks to capture the semantic properties of words having syntactic effect. For example, the nouns resistance, relationship, marriage, accommodation, all share a common SAL code reflecting their governance of the preposition "to"  (e.g resistance to change).  

The adjectives easy, fun, pleasant have SAL codes quite different from the codes for eager, anxious, determined, to reflect the pronounced differences in the syntactic effect of these groups.

1. John is easy/fun/simple to please. --> Pleasing John is easy/fun/simple.
2. John is eager/reluctant/determined to please. --> \*Pleasing John is eager/reluctant/determined.

(Notice the loose semantic kinship shared by members of each adjectival group.)

SAL addresses the Complexity of Natural Language
------------------------------------------------

The second motivation for SAL concerned the complexity of natural language. 

The complexity of language is probably the single most difficult property of language for a computer to handle. 

SAL was conceived as an abstraction language, abstraction being the principal device used by the Logos System to keep things simple.  

The words shelf, table, chair, ledge, bench, sofa would be encoded in SAL as a "support surface".   If the common nouns self, table, etc. are first-order abstractions, then the SAL element "support surface" can be seen as a second-order abstraction.

In total, SAL has about 1000 entities encompassing all parts of speech.  SAL reduces the richness of natural language by several orders of magnitude, while still preserving critical semantic information.

Finally, SAL was conceived of as a "semantico-syntactic abstraction language" so that patterns of natural language could be mapped to abstract semantico-syntactic patterns. 

Being semantico-syntactic, these SAL patterns would allow simultaneous processing of both syntax and semantics. 

Being abstract, these SAL patterns would be less complex and thus more manageable in a digital environment. 

Semantico-syntactic abstraction SAL patterns are powerful and efficient, precisely because one abstract SAL pattern can cover a multitude of NL instantiations of that pattern. 

Analysis and synthesis rules based on SAL patterns have thus proved to be an extremely effective means for effecting digital translation.

There are different SAL dialects
------------------------------------------------

SAL is not a pure interlingua.  Each source language requires its own dialect of SAL to represent it.  This is so in order to capture the idiosyncrasies of each natural language.  Nevertheless, there is a great deal of commonality among the dialects of SAL, reflecting the underlying commonality among languages universally.  (In the case of nouns, this commonality is 100%.)

The SAL Taxonomy
------------------------------------------------

.. For a graphic view of the SAL taxonomy, click on SAL Taxonomy. 

For a detailed presentation of the SAL taxonomy, see SAL Elements.  TODO            


