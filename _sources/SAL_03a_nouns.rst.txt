SAL Noun Code Taxonomy
======================

General Explanation of the SAL Noun Code Taxonomy
-------------------------------------------------

Nouns are organized in a taxonomy of :maroon:`supersets`, :red:`sets`, and :blue:`subsets`.

Nouns have twelve :maroon:`supersets`:

* concrete
* mass
* animate
* place
* information
* abstract
* process (intr)
* process (tr)
* measure
* time
* aspective
* unknown     

All noun :maroon:`supersets` have :red:`sets`, but only some :red:`sets` have :blue:`subsets`.

In the following, :maroon:`maroon` denotes noun :maroon:`superset`, red denotes noun :red:`set`, and blue denotes noun :blue:`subset`.  

Mnemonics for each SAL element are provided for coders and rulewriters. Internal to the system, however, SAL codes are represented numerically.  For Nouns, the numeric range signifies place on the taxonomy, as follows:

:maroon:`1-12 = supersets`

:red:`17-99 = sets`

:blue:`100-998 = subsets`

Guidelines to SAL Coders
------------------------
Nouns with Multiple Meanings
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Many nouns fall into more than one SAL category.  For example, passage can be both a conduit under :maroon:`Concrete`, and a path under Place.   It can also be a piece of writing or musical composition under :maroon:`Information`.  

Selection among the multiple meanings of a given noun can often be effected by the use of Subject Matter Codes (SMC) when entering the term in TermBuilder. 

In some cases, however, Subject Matter Codes are not helpful.  In such cases, the user must make an arbitrary choice among SAL codes at the time the word is entered.  (Later development plans include giving the system the ability to resolve among the multiple meanings of a common noun on the basis of extra-sentential context.  This capability does not presently exist in the Logos System.)

When making coding decisions, users should observe the coding priorities listed below.

Noun Coding Priorities
^^^^^^^^^^^^^^^^^^^^^^

There is a critical set of priorities governing coding choices for nouns that should be observed, if translation degradation is to be avoided.  The following represents the coding hierarchy in order of importance:

* Verb-biased Nouns (See :red:`verbal abstracts set` under :maroon:`Abstract Superset`). Nouns coded for verb bias tell the system to expect a verb complement. 

    Verb-biased codes are critical for parsing.  For example:

    (1) ways of cooking lentils
    (2) types of cooking utensils. 

    The :red:`verbal abstracts` code given to ways in (1) biases the parser to expect a verb and therefore allows the parser to resolve cooking correctly to a verb.  In (2) cooking is an adjective.

* Nouns taking prepositional complementation.  (See :red:`strong verbals` under :maroon:`Abstract Superset`.)   For example:

    * attitude towards
    * interest in
    * anxiety about
    * phone connection to
    * attention to

    Prep governance codes are critical for parsing decisions regarding prepositional attachement.

* :maroon:`Mass` Nouns.  Unlike count nouns, mass nouns can occur in the singular without an article or quantifier; e.g., Gold is expensive.

    :maroon:`Mass` codes are critical to parsing.  For example:

    (1) Test gold for . . .
    (2) . . . test tube for. . . .

    In (1), gold as a :maroon:`Mass` noun helps the parser to see test as a verb.  (Unlike count nouns, singular mass nouns without an article can be the object of a verb.)
    In (2), test must be a noun because tube is a singular count noun.

    :maroon:`Mass`-like codes occur in various places in the SAL noun taxonomy.   These include:

        * :maroon:`Mass Superset`, which is mass by definition
        * :blue:`trees/wood subset` (e.g. oak) under :maroon:`Concrete Superset`
        * :blue:`edibles/color subset` (e.g. orange) under :maroon:`Concrete Superset`
        * :blue:`mammals/food/fur subset` (e.g. fox) under :maroon:`Animate Superset`
        * :blue:`fowl/food subset` (e.g. duck) under :maroon:`Animate Superset`
        * :blue:`remote mass subset`

* Nouns denoting agents.  Agentive type nouns occur in various places in the SAL noun taxonomy.  These include:

    * :maroon:`Animate Superset`, which is agentive by definition
    * :red:`agentive set` under :maroon:`Concrete Superset`
    * :blue:`functional location (agentive) subset` under :maroon:`Place Superset`
    * :blue:`geographical entities (agentive) subset` under :maroon:`Place Superset`
    * :blue:`remote agentive subset` (an optional subset code under any set or superset)

SAL Noun Code Hierarchy
^^^^^^^^^^^^^^^^^^^^^^^

For nouns and noun phrases that are able to take more than one code, assign that code which is highest in the following hierarchy.

Note that Process Nouns (WC 4 and 7) are not included here.  Process Noun codes are derived automatically from their verbs.  (Process Noun codes are preemptive.)


.. csv-table:: 
   :header: "Characteristic", "Applicable SAL Type",  "Mnemonic",  "Numeric (:maroon:`SS` :red:`Set` :blue:`Subset`)" 
   :delim: |
   :widths: auto
    
     Takes Verbal Complementation        | purpose subset of ABSTRACT                                                     | ABpur      | :maroon:`6`      :red:`41`      :blue:`748`
                                         | method/process/procedure subset of ABSTRACT                                    | ABmeth     | :maroon:`6`      :red:`41`      :blue:`733`
                                         | cause/potential/disposition subset of ABSTRACT                                 | ABcause    | :maroon:`6`      :red:`41`      :blue:`602`
     Mass (non-count) Noun               | entire MASS noun Superset                                                      | MASS       | :maroon:`11`
                                         | trees/wood subset of CONCRETE Superset                                         | COtrwd     | :maroon:`3`      :red:`32`      :blue:`855`
                                         | edibles/color subset of CONCRETE Superset                                      | COedcol    | :maroon:`3`      :red:`18`      :blue:`855`
                                         | remote MASS (floating subset)                                                  | (variable) | :blue:`855`
     Takes Prepositional Complementation | strong verbals subset of ABSTRACT  (code is specific for each prep governance) | ABxxx      | :maroon:`6`      :red:`nn`      :blue:`749`
                                         | recorded data subset of INFORMATION                                            | INdata     | :maroon:`12`     :red:`76`
     Denotes Agent                       | entire ANIMATE Superset                                                        | AN         | :maroon:`5`                  
                                         | entire agentive set of CONCRETE Superset                                       | COagen     | :maroon:`3`      :red:`35`  
                                         | agentive geographical entity set  of PLACE Superset                            | PLaggeo    | :maroon:`9`      :red:`94` 
                                         | instructional data set of INFORMATION                                          |            | :maroon:`12`     :red:`74`
                                         | agentive functional location of PLACE Superset                                 | PLagfunc   | :maroon:`9`      :red:`26`      :blue:`228`
                                         | remote agentive  (floating subset)                                             | (variable) | :blue:`228`                               

All other SAL noun codes are more or less of equal weight.                         


A Caveat to SAL Coders
----------------------

The organization of nouns into a small number of sub-classifications is inevitably going to be arbitrary and even seem unprincipled at times. 

For example, the LOGOS system codes *table* as a supporting surface under :maroon:`Concrete Superset` and *platform* as a :maroon:`Place` noun, this on the grounds that the latter has human scale.  But, by the same token, words like *wall* and *fence* are coded :maroon:`Concrete` rather than :maroon:`Place` despite their human scale.

There is no real defense of this except to repeat that any taxonomy that reduces 100,000 nouns to 100 categories is bound to incur these inconsistencies. 

As one becomes familiar with SAL, idiosyncrasies such as this  become less troublesome.  It is only fair to say that natural language itself is riddled with unprincipled inconsistencies.

