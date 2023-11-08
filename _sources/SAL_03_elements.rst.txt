SAL Elements
============

There are 12 parts of speech in SAL, divided into open and closed word classes. 

Open word classes are:  nouns, adjectives, adverbs and verbs.  As a user you are able to add or modify open word classes (except for verbs).

Closed word classes are:  articles, prepositions, auxiliary verbs, pronouns, interrogatives, negative particles, conjunctions and punctuation.  These classes are privileged and only users with the appropriate profile can modify them.



SAL Taxonomy for Rulewriters and Coders
----------------------------------------

* NOUNS   -   [N]   [WC 01]    
* ADJECTIVES   -  [ADJ]  [WC 04]
* DETERMINERS  -   [DET]  [WC 14 & 15]
* ARITHMATES   -   [AR]  [WC 16]    (See also WC 04, 14)
* PRONOUNS   -   [PRO] [WC 05]
* RELATIVES/INTERROGATIVES  -  [INTREL]  [WC 18]
* VERBS   -  [VT / VI] [WC 02]  
* AUXILIARY VERBS   -   [AUXMO]  [WC 12]
* ADVERBS   -   [ADV]  [WC 03 & 06]
* PREPOSITIONS   -   [PREP]  [WC 11 & 13]
* NEGATIVES  -    [NEG]  [WC 17]
* CONJUNCTIONS   -   [CONJ]  [WC 19]
* PUNCTUATION   -    [PUNC]  [WC 20]

.. * REMOTE AGENTIVE SUBSET - these are not POS
.. * REMOTE MASS SUBSET
.. * APPOSITION-INVITING SUBSET
.. * UNKNOWN WORDS
.. * SPECIAL CHARACTERS


In these SAL Taxonomy Tables, the :navy:`navy` color denotes :navy:`Word Class`, :maroon:`maroon` denotes :maroon:`Superset`, :red:`red` denotes :red:`set`, and **black** denotes **subset** (in other contexts, :blue:`blue` is used to denote :blue:`subset`).

The SAL Taxonomy Tables provided here include word-specific codes for the closed Word Classes and also for Adverbs, but only give generic codes for Nouns, Adjectives, and Verbs.  To access word-specific codes for Nouns, Adjectives, Verbs and closed Word Classes, use the TermBuilder View Function.

Numeric Codes denote Taxonomy position (:maroon:`Superset`, :red:`set` and :blue:`subset`) by their range:  Numbers 1-16 denote :maroon:`Superset`, 17-99 denote :red:`set`, and 100-998 denote :blue:`subset`.  Note, however, that there are exceptions to this arrangement in the case of :navy:`Adverbs` (Non-Locatives), where :maroon:`Superset` codes range from 1-26 and there are no :red:`set` codes.



SAL Noun  Supersets
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Supersets", "Mnemonics", ""
   :delim: |
   :widths: auto

    CONCRETE     | CO  | 3
    MASS         | MA  | 11
    ANIMATE      | AN  | 5
    PLACE        | PL  | 9
    INFORMATION  | IN  | 12
    ABSTRACT     | AB  | 6
    PROCESS-INTR | PNI | 4
    PROCESS-TR   | PNT | 7
    MEASURE      | ME  | 8
    TIME         | TI  | 10
    ASPECTIVE    | AS  | 2
    UNKNOWN      | UN  | 1
 

.. csv-table:: Concrete Noun Sets [3]   
   :header: "Sets", "Mnemonics", ""
   :delim: |
   :widths: auto

    agentives         | COagen  | 35
    functionals       | COfunc  | 34
    natural things    | COnat   | 32
    lights            | COlight | 37
    edibles(non-mass) | COednm  | 18
    amorphous         | COamor  | 33
    atomistic         | COatom  | 19
    blemishes         | COblem  | 44
    classifiers       | COclass | 39

 
.. csv-table:: CO  -  CONCRETE Noun Sets and Subsets [3] 
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    agentives                        | COundagt  | [3 35 248]  | See subsets
    software                         | COsoft    | [3 35 300]  | routine
    concrete chemical agents         | COchem    | [3 35 702]  | catalyst, warhead
    machines/systems                 | COmach    | [3 35 750]  | battery, camera
    vehicles                         | COvehic   | [3 35 611]  | truck, ship
    meters                           | COmeter   | [3 35 716]  | clock, gauge
    communication agents             | COcomm    | [3 35 708]  | radio, radar
    functionals                      | COundfunc | [3 34 217]  | trinket, ornament
    devices/tools                    | COtool    | [3 34 720]  | pliers, muscle
    fasteners                        | COfast    | [3 34 721]  | nail, tendon
    bearing surfaces                 | COsurf    | [3 34 722]  | table, shelf
    receptacles                      | COrecp    | [3 34 659]  | bottle, barrel
    conduits                         | COcond    | [3 34 745]  | chute, artery
    thresholds/focal points/barriers | CObarr    | [3 34 525]  | wall, door
    links/bridges                    | COlink    | [3 34 526]  | circuit, nerve
    cloth things                     | COcloth   | [3 34 785]  | shirt, blanket
    structural elements              | COstruc   | [3 34 612]  | spar, bone
    concretizations of verbals       | COverb    | [3 34 211]  | threading
    concretizations of mass nouns    | COmass    | [3 34 210]  | acid lining
    product/brand names              | CObrand   | [3 34 209]  | Windows NT
    natural things                   | COnat     | [3 32 32]   | See subsets
    minute flora                     | COflora   | [3 32 382]  | algae, spore
    plants                           | COplant   | [3 32 383]  | rose, weed
    trees                            | COtree    | [3 32 384]  | apple, willow
    trees/wood                       | COtrwd    | [3 32 855]  | oak, maple
    misc. natural things             | COmnat    | [03 32 381] | pebble, iceberg
    edibles (non-mass)               | COednm    | [3 18 18]   | pork chop
    edibles/color                    | COedcol   | [3 18 855]  | orange, cherry
    impulses/lights                  | COlight   | [3 37 37]   | lamp, beam
    blemishes/marks                  | COblem    | [3 44 44]   | scratch, freckle
    classifiers                      | COclass   | [3 39]      | element
    amorphous                        | COamor    | [3 33]      | breeze, tide
    atomistic                        | COatom    | [3 19]      | electron, atom
    undifferentiated                 | COobj     | [3 3 212]   | trifle, curio

 

 

.. csv-table:: MA - MASS Noun Sets and Subsets [11]   
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    raw materials/metals    | MAraw   | [11 38]     | wool, iron
    functional mass         | MAfunc  | [11 49]     | wiring, cable
    -gear/equipment         | MAgear  | [11 49 324] | radio gear
    financial               | MA fina | [11 97]     | money, stock
    energy                  | MAener  | [11 23]     | fire, heat
    vegetative              | MAvege  | [11 60]     | grass, wheat
    animate mass            | MAanim  | [11 82]     | skin, hair
    natural minerals/solids | MAmine  | [11 84]     | rock, ore
    chemical agents         | MAchem  | [11 83]     | adrenalin
    chemical compounds      | MAcomp  | [11 52]     | chlorophyll
    liquids                 | MAliqu  | [11 45]     | water, oil
    edible mass             | MAedib  | [11 43]     | food, meat
    gases                   | MAgas   | [11 50]     | gas, air
    wastes                  | MAwaste | [11 98]     | dross, chaff
    undifferentiated mass   | MAundif | [11 20]     | film, fiber

 

.. csv-table:: AN - ANIMATE Noun Sets and Subsets [5]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    designations/professions  | ANdes    | [5 91]     | mother, lawyer
    titles                    | ANtitle  | [5 91 807] | Mr. / Mrs.
    people/place              | ANplace  | [5 91 205] | Canadian
    people/language           | ANlang   | [5 91 206] | Spanish
    proper names              | ANname   | [5 91 207] | Smith / Mary
    human collective          | ANcoll   | [5 94]     | agency
    proper organization names | ANorg    | [5 94 193] | Congress
    non-human animates        | ANanim   | [5 51]     |
    non-human aggregate       | ANaggr   | [5 51 208] | herd, bevy
    mammals                   | ANmamm   | [5 51 126] | lion
    mammals/food/fur          | ANmammfd | [5 51 855] | rabbit
    fowl                      | ANfowl   | [5 51 125] | sparrow
    fowl/food                 | ANfowlfd | [5 51 855] | chicken
    fish                      | ANfish   | [5 51 124] | shark
    reptiles                  | ANrept   | [5 51 123] | lizard
    bugs/insects              | ANbugs   | [5 51 122] | spider
    microorganisms            | ANmicro  | [5 51 121] | virus
    other animates            | ANother  | [5 51 213] | angel, ghost

 

.. csv-table:: PL - PLACE Noun Sets and Subsets [9]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    functional locations                            | PLfunc    | [9 26]     | dock
    agentive functional locations                   | PLagfunc  | [9 26 228] | bank
    enclosed spaces                                 | PLencl    | [9 27]     | closet
    paths                                           | PLpath    | [9 55]     | orbit
    non-agentive common-noun geographical locations | PLnagcom  | [9 29]     | frontier
    agentive geog. entities                         | PLaggeo   | [9 94]     | See subsets
    countries/states/provinces                      | PLcoun    | [9 94 230] | England
    cities                                          | PLcity    | [9 94 226] | New York
    agentive common-noun geog. entities             | PLagcom   | [9 94 236] | empire
    non-agentive proper geog. entities              | PLnagprop | [9 56]     | See subsets
    continents                                      | PLcont    | [9 56 227] | Africa
    bodies of water                                 | PLwater   | [9 56 229] | Gulf of Mexico
    other non-agentive proper geog. entities        | PLothprop | [9 56 238] | Mt. Fuji
    undifferentiated place                          | PLundif   | [9 57]     | zone

 


.. csv-table:: IN - INFORMATION Noun Sets and Subsets [12] 
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    instructional/legal             | INinst  | [12  74]    | rule, contract
    games/rituals                   | INgame  | [12 74 224] | chess, hockey
    symbolic data                   | INsymb  | [12 75]     | number, code
    recorded data                   | INdata  | ]12 76]     | book, map
    scripted events                 | INevent | [12 76 223] | opera, movie
    evidence/symptoms               | INevid  | [12 96]     | clue, cue, hint
    fields of knowledge             | INknow  | [12 78]     | chemistry
    the arts                        | INarts  | [12 78 225] | ballet, drama
    storage media for recorded data | INstor  | [12 77]     | disk, buffer
    undifferentiated information    | INundif | [12 79]     | fact, adage

 

 

.. csv-table:: AB - ABSTRACT Noun Sets and Subsets [6]    
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    verbal abstracts (re processes, behavior, persons as agents) | ABverb  | [6 41]     |
    purpose                                                      | ABpur   | [6 41 748] | task, function
    method/process/procedure                                     | ABmeth  | [6 41 733] | mode, way
    cause/potential/disposition                                  | ABcause | [6 41 602] | basis, reason
    quality of action/agent                                      | ABqual  | [6 41 655] | rapidity, ease
    negative causes                                              | ABnegc  | [6 41 764] | danger, risk
    strong verbal abstracts                                      | ABstrvb | [6 41 749] | See Chart
    time events                                                  | ABtime  | [641 732]  | holiday
    contrary events                                              | ABcont  | [6 41 765] | accident
    non-verbal abstracts (re things, persons as non-agents)      | ABnonvb | [6 40]     |
    properties/qualities/nature                                  | ABprop  | [6 40 609] | form, trait
    states/conditions/relationships                              | ABstate | [6 40 736] | parity, coma
    classifications                                              | ABclass | [6 40 731] | species, rank
    sources/origins                                              | ABorig  | [6 40 723] | fund, store
    general abstract concepts                                    | ABgen   | [6 42]     | idea, truth

 

 

.. csv-table:: ABstrv - Strong Verbal Abstracts (with Prepositional Governance) 
   :header: 
   :delim: |
   :widths: auto

    to, onto, into, over (motional preps + acc.)     | ABmot24   | [6 24 749] | stumble, reach, reroute
    at, on, in, under, above (locative preps + dat.) | ABloc68   | [6 68 749] | cutover, dent, puncture, scribble, slap
    at = relational sense                            | ABat94    | [6 94 749] | balk, peek, smile
    for                                              | ABfor46   | [6 46 749] | affinity, flair, respect
    from/off of/ out of                              | ABfrom26  | [6 26 749] | egress, deliverance, rescue, absence, reprieve, exile
    in (non-locative)                                | ABin82    | [6 82 749] | breakthrough, competency, debut, exam, growth, lapse
    into (non-motional)                              | ABin20    | [6 20 749] | insight, etc.
    about/on/over = concerning                       | ABabout90 | [6 90 749] | publicity, rivalry, outrage, flap, fuss, grief, criticism
    to/toward  (relational sense, may take "from")   | ABto57    | [6 57 749] | allergy, civility, injury, service, tribute, reply
    with                                             | ABwith59  | [6 59 749] | combat, merger, stay

 

 


.. csv-table:: ME - MEASURE Noun Sets and Subsets [8]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto


    abstract concepts measured by unit | MEabs   | [8 46]     | humidity, length
    discrete measurable concepts       | MEdis   | [8 95]     | sum, increment
    units of measure                   | MEunit  | [8 61]     | See subsets
    units of weight                    | MEwt    | [8 61 161] | ounce, pound
    units of velocity                  | MEvel   | [8 61 162] | mph, megahertz
    units of volume measure            | MEvol   | [8 61 163] | gallon, liter
    units of temperature               | MEtemp  | [8 61 164] | degrees celsius, BTU
    units of energy/force              | MEener  | [8 61 165] | watt, horsepower
    measurement systems                | MEsys   | [8 61 234] | fahrenheit, kelvin
    units of duration                  | MEdur   | [8 61 166] | hour, minute, year
    specialized units of measure       | MEspec  | [8 61 167] | oersted, ohm, phon
    units of money/value               | MEvalue | [8 61 168] | dollar, mark, franc
    units of linear/area measure       | MElin   | [8 61 170] | inch, yard, mile
    general undifferentiated measure   | MEundif | [8 61 169] | degree, gross, share

 

 

.. csv-table:: TI - TIME Noun Sets and Subsets [10]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    days of the week      | TIday   | [10 30 171] | Monday, Friday
    months of the year    | TImo    | [10 30 172] | July, December
    seasons of the year   | TIsea   | ]10 30 173] | winter, spring
    periods of the day    | TIper   | [10 30 174] | rush hour, dawn
    adverbial time nouns  | TIadv   | [10 30 176] | today's, tonight's
    undifferentiated time | TIundif | [10 30]     | epoch, era, antiquity

 

 

.. csv-table:: AS - ASPECTIVE Noun Sets and Subsets [2]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    aspective bearing surfaces                         | ASsurf | [2 21]     | seat, ledge
    aspective functionals                              | ASfunc | [2 58]     | tooth, arm, tab
    members/portions/parts                             | ASpart | [2 24]     | unit, phase
    aggregates                                         | ASaggr | [2 92]     | group, pair, set
    numeric groupings                                  | ASnum  | [2 92 101] | tens, hundreds
    aspective receptacles                              | ASrecp | [2 36]     | cavity, rut, groove
    aspective thresholds/focal points/ barriers/limits | ASbarr | [2 25]     | axis, hole, target
    model/copy                                         | AScopy | [2 31]     | duplicate, image
    configurations/order                               | ASconf | [2 28]     | network, row, pile
    aspective conduits                                 | AScond | [2 22]     | link, span

 

.. csv-table:: UN - UNKNOWN Words Subsets [1]
   :header: "Subsets", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    words without distinguishing features | UN      | [1 1 1] [Form=33]
    words w/ initial cap                  | UNinit  | [1 1 859]   "
    words in all caps                     | UNcaps  | [1 1 228]   "
    alpha-numeric string                  | UNalnum | [1 1 989]   "

\* Unknown Words always default to the Noun Word Class
 

 

.. csv-table:: FL - FLOATING Subsets
   :header: "Subsets", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    remote agentive subset     | reagen  | [228]
    remote mass subset         | remass  | [855]
    apposition-inviting subset | apinvit | [986]



DET - Determiners   [14]
---------------------------

.. csv-table:: 
   :header: "Superset", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    Definite Article | ART | 1
    Demonstratives   | DEM | 2
    Arithmates       | AR  | 9 (form = 8)


.. csv-table:: ART  -  Definite Article  [1]
   :header: "Superset", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    Definite Article | the | [1 1 101]

 

 

.. csv-table:: DEM  -  Demonstratives  [2]
   :header: "Superset", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    Demonstrative | that  | [2 2 103]
    Demonstrative | these | [2 2 102]
    Demonstrative | this  | [2 2 102]
    Demonstrative | those | [2 2 103]

 

.. csv-table:: [WC 14]  AR - Arithmates as Determiners [9]   [Form = 8]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    mixed numbers                                     | NUMmixed     | [9 18 818] | 1 1/2;  2 1/4
    all fractions                                     | NUMfrac      | [9 19 919] | 1/2  1/3  1/4
    zero                                              | NUM0         | [9 20 020] | 0
    word-specific code for number one                 | NUM1         | [9 21 123] | 1
    word-specific code for number two                 | NUM2         | [9 21 222] | 2
    word-specific code for numbers 3 and 4            | NUM3-4       | [9 21 234] | 3, 4
    generic subset for numbers from 5 - 31            | NUM5-31      | [9 21 567] | 5, 6, 7 . . . 31
    generic subset for numbers from 32 - 99           | NUM32-99     | [9 23 567] | 32 . . . 99
    word-specific code for word one hundred           | NUMhundred   | [9 40 601] | one hundred
    generic subset for numbers from 100 - 999         | NUM100-999   | [9 40 789] | 100 . . . 999
    word-specific code for one thousand               | NUMthousand  | [9 51 602] | one thousand
    generic subset for numbers from 1000 - 1776       | NUM1000-1776 | [9 51 789] | 1000 . . . 1776
    generic subset for numbers from 1777 - 1999       | NUM1777-1999 | [9 52 789] | 1777 . . . 1999
    generic subset for numbers from 2000 - 2400       | NUM2000-2400 | [9 53 789] | 2000 . . . 2400
    generic subset for numbers from 2401 and up       | NUM2401plus  | [9 54 890] | 2401 . . .
    word-specific code for million                    | NUMmillion   | [9 54 603] | million
    word-specific code milliard                       | NUMmilliard  | [9 54 604] | milliard
    word-specific code billion                        | NUMbillion   | [9 54 605] | billion
    word-specific code trillion                       | NUMtrillion  | [9 54 606] | trillion
    specific code for asterisk symbol                 | NUMast       | [9 60 60]  | *
    specific code for dollar sign                     | NUMdolsign   | [9 60 989] | $
    specific code for percent sign                    | NUMpctsign   | [9 60 980] | %
    specific code for year with an apostrophe         | NUM'29-'99   | [9 90]     | '29-'99
    specific code for the roman numerals              | NUMroman     | [9 92 092] | I, II, III, IV, V, .......
    specific code for the arithmate-arithmate         | NUMn-n       | [9 94 094] | 2-2    5-3    8-1
    specific code for miscellaneous arithmate strings | NUMstring    | [9 96 096] | 1.1 / 83-05-12

 
AR -  Arithmates  [WC 16, Superset 4]
----------------------------------------

Arithmates are distributed over three parts of speech: 


.. csv-table:: AR -  Arithmates  [WC 16, Superset 4]
   :header: "Description", "WC Mnemonic", WC", "Superset", "Form"
   :delim: |
   :widths: auto

    Arithmate: Free-Standing/Apposition | AR          | 16 | 4        | 1
    Arithmates as Other Parts of Speech | WC Mnemonic | WC | Superset | Form
    Arithmate as Definite Article       | DET         | 14 | 9        | 8
    Arithmate as Adjective              | AJ          | 4  | 13       | 9

 

 

.. csv-table:: [WC 16]  AR - Arithmates  (Free Standing and in Apposition) [Superset 4]   [Form = 1]
   :header: "Sets and Subsets", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    dates                                             | NUMdates     | [4 10 176] | 6/2/90
    mixed numbers                                     | NUMmixed     | [4 18 818] | 1 1/2;  2 1/4
    all fractions                                     | NUMfrac      | [4 19 919] | 1/2  1/3  1/4
    zero                                              | NUM0         | [4 20 020] | 0
    word-specific code for number one                 | NUM1         | [4 21 123] | 1
    word-specific code for number two                 | NUM2         | [4 21 222] | 2
    word-specific code for numbers 3 and 4            | NUM3-4       | [4 21 234] | 3, 4
    generic subset for numbers from 5 - 31            | NUM5-31      | [4 21 567] | 5, 6, 7 . . . 31
    generic subset for numbers from 32 - 99           | NUM32-99     | [4 23 567] | 32 . . . 99
    word-specific code for word one hundred           | NUMhundred   | [4 40 601] | one hundred
    generic subset for numbers from 100 - 999         | NUM100-999   | [4 40 789] | 100 . . . 999
    word-specific code for one thousand               | NUMthousand  | [4 51 602] | one thousand
    generic subset for numbers from 1000 - 1776       | NUM1000-1776 | [4 51 789] | 1000 . . . 1776
    generic subset for numbers from 1777 - 1999       | NUM1777-1999 | [4 52 789] | 1777 . . . 1999
    generic subset for numbers from 2000 - 2400       | NUM2000-2400 | [4 53 789] | 2000 . . . 2400
    generic subset for numbers from 2401 and up       | NUM2401plus  | [4 54 890] | 2401 . . .
    word-specific code for million                    | NUMmillion   | [4 54 603] | million
    word-specific code milliard                       | NUMmilliard  | [4 54 604] | milliard
    word-specific code billion                        | NUMbillion   | [4 54 605] | billion
    word-specific code trillion                       | NUMtrillion  | [4 54 606] | trillion
    specific code for asterisk symbol                 | NUMast       | [4 60 60]  | *
    specific code for dollar sign                     | NUMdolsign   | [4 60 989] | $
    specific code for percent sign                    | NUMpctsign   | [4 60 980] | %
    specific code for year with an apostrophe         | NUM'29-'99   | [4 90 90]  | '29-'99
    specific code for the roman numerals              | NUMroman     | [4 92 092] | I, II, III, IV, V, .......
    specific code for the arithmate-arithmate         | NUMn-n       | [4 94 094] | 2-2    5-3    8-1
    specific code for miscellaneous arithmate strings | NUMstring    | [4 96 096] | 1.1 / 83-05-12

 

Special Characters
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Special Characters occur in Arithmate Word Class [AR] [WC 16] and in Punctuation Word Class [PUNC] [WC 20].  For a complete list of Special Characters, refer to the EXCEL document named "alphanum7" maintained at the Logos Technology Center.  This is the definive file for Arithmates, Punctuation, and Special Characters.



ADJECTIVE Supersets 
-----------------------------------------------------------------------------


.. csv-table:: ADJECTIVE Supersets 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Descriptive Adjectives         | DESC | 13 (form 23)
    Arithmetic Adjectives          | NUM  | 13 (form 9)
    Past Participial Adjectives    | PAST | 16 (form 60)
    Present Participial Adjectives | PRES | 15 (form 50)
    -ABLE Participial Adjectives   | ABLE | 16 (form 23)

\* See Verb Taxonomy for Generic Participial ADJ Codes.  
\* See Lexicon for word-specific Participial ADJ Codes


.. csv-table:: Descriptive Adjective Sets 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Pre-Clausal                                  | PC   | [13 86/87/88]
    Pre-Verbal                                   | PV   | [13 83/84/85]
    Adverbial Type                               | AV   | [13 80]
    Adverbial Type with Prepositional Governance | AV   | [13 17,20,26,46,57,59,68,90]
    Non-Adverbial Type                           | NAV  | [13 81]
    Pure Post-Nominal Type                       | POST | [13 81 417]
 
.. csv-table:: PC - Pre-Clausal Descriptive Adjective Sets and Subsets [13 86/87/88]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

    pure logical [it]; that/to     | PCurgent  | [13 86 432] | urgent, absurd, feasible
    mixed logical [it/he]; that/to | PCcertain | [13 87 438] | certain, fortunate, unlikely
    mixed logical [it/he]; that/to | PCgood    | [13 87 439] | good, odd, silly, smart, great
    non-logical [he]; that/to      | PChappy   | [13 88 442] | happy, afraid, grateful, sad
    pure logical [it]; that only   | PCclear   | [13 86 433] | clear, ironic, pertinent, vital
    non-logical [he]; that only    | PCaware   | [13 88 443] | aware, adamant, cognizant

 

.. csv-table:: PV - Pre-Verbal Descriptive Adjective Sets and Subsets [13 83/84/85]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     pure logical [it]; to verb                                          | PVvalid | [13 83 418] | valid, beneficial, pointless, impractical, fraudulent
     mixed logical [it/he]; to v’ing                                     | PVakin  | [13 84 419] | akin, conducive, tantamount
     mixed logical [it/he]; to verb                                      | PVeasy  | [13 84 420] | easy, dangerous, difficult, hard
     mixed logical [it/he]; to verb                                      | PVwise  | [13 84 423] | wise, bol, heroic, humane, polite
     non-logical [he]; to verb                                           | PVeager | [13 85 428] | eager, eligivle, prone, reluctant
     non-logical [he]; to verb; in v’ing                                 | PVfirst | [13 85 429] | first, next, last, second, fifth, etc.
     non-logical [he]; to v’ing; to verb; of v’ing; with v’ing; in v’ing | PVbusy  | [13 85 430] | busy, diligent, resolute, handy thorough, versatile, effective

 

.. csv-table:: AV - Adverbial Type Descriptive Adjective Set and Subsets [13 80]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     adjectives governing a preposition | AVxxx    | [13 xxx 180] | See chart below for specific prep governance and code
     state/manner adjectives            | AVstate  | [13 80 185]  | euphoric, faint, glamorous, heliocentric, helpless, implacable, inane, leisurely, needy, ominous, omnipotent, silent, joyless, laconic, sly
     time/order adjectives              | AVtime   | [13 80 181]  | former, primary
     locative adjectives                | AVloc    | [13 80 182]  | inner, marginal
     quantity/measure adjectives        | AVquan   | [13 80 183]  | minimal, slight, prolific, scarce
     degree/intensity adjectives        | AVdegree | [13 80 184]  | real, utter, genuine

\* Note: adverb subsets are listed in order of priority.
 


.. csv-table:: AVxxx - Adverbial Adjectives Chart for Prep Governance  [13, 17,20,26,46,57,59,68,90]
   :header: "Preposition", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     Locative prepositions (at, on, in, under, above, etc.) | AVloc   | 13 68 180/417 | asleep, aground, submersible (in)
     for                                                    | AVfor   | 13 46 180/417 | ineligible, avid, famous, suitable (for)
     from                                                   | AVfrom  | 13 26 180/417 | absent,  distinct, inseparable, remote (from)
     in = with respect to                (non-locative)     | AVin    | 13 20 180/417 | active, deficient, fluent, foremost, methodical, prevalent, well-versed, unique (in)
     of                                                     | AVof    | 13 17 180/417 | barren, devoid, envious, intolerant, suspsicious (of)
     about/over/on =  concerning                            | AVabout | 13 90 180/417 | jittery, joyous, jumpy, obdurate (about/over)
     to                                                     | AVto    | 13 57 180/417 | adjacent, detrimental, extraneous (to)
     with                                                   | AVwith  | 13 59 180/417 | consistent, familiar, incompatible (with)

\* 180=preposed adj; 417=postposed adj
 

.. csv-table:: NAV - Non-Adverbial Type Descriptive Adjective Set and Subsets [13 81]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     predicate adjective type     | NAVpred  | [13 81 186] | yellow, exploratory
     non-predicate adjective type | NAVnpred | [13 81 187] | bridal, naval

 

.. csv-table:: POST - Pure Post Nominal Descriptive Adjective Set (Subset)  [13 81]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     pure post nominal type | POST | [13 81 417] | galore, ablaze, fraught, replete, alike, awash

\* Note that Pure Post Nominal Adjectives can govern prepositions, e.g., awash, fraught, ablaze with.  When approrpiate, replace 81 set code with set code in PREP GOV Chart above.
 

.. csv-table:: PRE - Prefix-Type Descriptive Adjective Set  [13 82]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     prefix-type adjectives | PREmid | [13 82 100] | mid-, anti-, omni-, bi-, aero-
     unique subset for re-  | PREre  | [13 82 318] | re-

 
Arithmates as Adjectives  
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. csv-table:: [WC 04]  Arithmates as Adjectives  [Superset 13]  [Form 9]
   :header: "Sets and Subsets", "Mnemonic", "Numerics", "Examples"
   :delim: |
   :widths: auto

     dates                                             | NUMdates       | [13 10 176] | 6/2/90
     mixed numbers                                     | NUMmixed       | [13 18 818] | 1 1/2;  2 1/4
     all fractions                                     | NUMfrac        | [13 19 919] | 1/2  1/3  1/4
     zero                                              | NUM0           | [13 20 020] | 0
     word-specific code for number one                 | NUM1           | [13 21 123] | 1
     word-specific code for number two                 | NUM2           | [13 21 222] | 2
     word-specific code for numbers 3 and 4            | NUM3-4         | [13 21 234] | 3, 4
     generic subset for numbers from 5 - 31            | NUM5-31        | [13 21 567] | 5, 6, 7 . . . 31
     generic subset for numbers from 32 - 99           | NUM32-99       | [13 23 567] | 32 . . . 99
     word-specific code for word one hundred           | NUMhundred     | [13 40 601] | one hundred
     generic subset for numbers from 100 - 999         | NUM100-999     | [13 40 789] | 100 . . . 999
     word-specific code for one thousand               | NUMthousand    | [13 51 602] | one thousand
     generic subset for numbers from 1000 - 1776       | NUM1000-1776   | [13 51 789] | 1000 . . . 1776
     generic subset for numbers from 1777 - 1999       | NUM1777-1999   | [13 52 789] | 1777 . . . 1999
     generic subset for numbers from 2000 - 2400       | NUM2000-2400   | [13 53 789] | 2000 . . . 2400
     generic subset for numbers from 2401 and up       | NUM2401 and up | [13 54 890] | 2401 . . .
     word-specific code for million                    | NUMmillion     | [13 54 603] | million
     word-specific code milliard                       | NUMmilliard    | [13 54 604] | milliard
     word-specific code billion                        | NUMbillion     | [13 54 605] | billion
     word-specific code trillion                       | NUMtrillion    | [13 54 606] | trillion
     specific code for asterisk symbol                 | NUMast         | [13 60 60]  | *
     specific code for dollar sign                     | NUMdolsign     | [13 60 989] | $
     specific code for percent sign                    | NUMpctsign     | [13 60 980] | %
     specific code for year with an apostrophe         | NUM'29-'99     | [13 90]     | '29-'99
     specific code for the roman numerals              | NUMroman       | [13 92 092] | I, II, III, IV, V, .......
     specific code for the arithmate-arithmate???      | NUMn-n         | [13 94 094] | 2-2    5-3    8-1
     specific code for miscellaneous arithmate strings | NUMstring      | [13 96 096] | 1.1 / 83-05-12

    
NEG - Negatives  [17]  
-----------------------------------------------------------------------------

.. csv-table:: Descriptive Adjective Sets 
   :header: "Negative", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    not     | not    | [1 1 460]
    not yet | notyet | [1 1 461]

 
 
PRO  -  Pronouns   [5]
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Class of Pronoun", "Description", "Mnemonic", "Set"
   :delim: |
   :widths: auto

    Personal   | (First Person)             | PERfirst     | Set 21
    Personal   | (Second Person)            | PERsecond    | Set 22
    Personal   | (Third Person: (Masculine) | PERmasc      | Set 23
    Personal   | (Third Person: (Feminine)  | PERfem       | Set 26
    Personal   | (Third Person: (Neuter)    | PERneut      | Set 27
    Reflexive  | myself, etc.               | REFL         | Set 24
    Reflexive  | one's, etc.                | REFLone-type | Set 25
    Possessive | hers, etc.                 | POSS         | Set 50
    Possessive | her own, etc.              | POSSown-type | Set 52
    Indefinite | (Singular and Plural)      | INDSP        | Set 30
    Indefinite | (Plural Only)              | INDP         | Set 40
    Indefinite | (Singular Only)            | INDS         | Set 42
    Indefinite | else/else's                | INDelse-type | Set 44

 

 
.. csv-table:: PRO - Pronouns  [5]  List by Set and Subset 
   :header: "Pronouns by Set", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    Personal (First Person)            | PERfirst       | Set 21
    I                                  | I              | [5 21 795]
    me                                 | me             | [5 21 795]
    we                                 | we             | [5 21 796]
    us                                 | us             | [5 21 796]
    Personal (Second Person)           | PERsecond      | Set 22
    you                                | you            | [5 22 797]
    Personal: Masculine (Third Person) | PERmasc        | Set 23
    he                                 | he             | [5 23 798]
    him                                | him            | [5 23 798]
    they                               | they           | [5 23 799]
    them                               | them           | [5 23 799]
    Personal: Feminine (Third Person)  | PERfem         | Set 26
    she                                | she            | [5 26 798]
    her                                | her            | [5 26 798]
    Personal: Neuter (Third Person)    | PERneut        | Set 27
    it                                 | it             | [1 27 303]
    Reflexive                          | REFL           | Set 24
    myself                             | myself         | [5 24 286]
    ourselves                          | ourselves      | [5 24 415]
    yourself                           | yourself       | [5 24 454]
    yourselves                         | yourselves     | [5 24 496]
    oneself                            | oneself        | [5 24 581]
    himself                            | himself        | [5 24 582]
    herself                            | herself        | [5 24 590]
    itself                             | itself         | [5 24 594]
    themselves                         | themsleves     | [5 24 631]
    Reflexive                          | REFLone-type   | Set 25
    one                                |                | [classified in dictionary as other POS]
    ones                               | ones           | [5 25 802]
    one's                              | one's          | [5 25 802]
    Possessive                         | POSS           | Set 50
    mine                               | mine           | [5 50 327]
    yours                              | yours          | [5 50 328]
    ours                               | ours           | [5 50 329]
    his                                | his            | [5 50 221]
    theirs                             | theirs         | [5 50 330]
    hers                               | hers           | [5 50 331]
    Possessive                         | POSSown-type   | Set 52
    own                                | own            | [5 52 395]
    her own                            | herown         | [5 52 332]
    his own                            | hisown         | [5 52 333]
    its own                            | itsown         | [5 52 334]
    my own                             | myown          | [5 52 335]
    their own                          | theirown       | [5 52 336]
    your own                           | yourown        | [5 52 337]
    Indefinite (Singular and Plural)   | INDSP          | Set 30
    all                                | all            | [1 30 140]
    any                                | any            | [1 30 115]
    enough                             | enough         | [1 30 146]
    more                               | more           | [1 30 148]
    more . . .                         | more . . .     | [1 30 202]
    most                               | most           | [1 30 149]
    no other                           | noother        | [1 30 231]
    none                               | none           | [1 30 203]
    none at all                        | noneatall      | [1 30 204]
    some                               | some           | [1 30 151]
    that                               |                | (See Relatives/Interrogatives)
    these                              | these          | [1 30 102]
    this                               | this           | [1 30 102]
    those                              | those          | [1 30 103]
    Indefinite (Plural Only)           | INDP           | Set 40
    a couple                           | acouple        | [1 40 280]
    a few                              | afew           | [1 40 245]
    all k of things                    | allkofthings   | [1 40 281]
    both                               | both           | [1 40 250]
    few                                | few            | [1 40 251]
    fewer                              | fewer          | [1 40 252]
    many                               | many           | [1 40 253]
    quite a few                        | quiteafew      | [1 40 263]
    several                            | several        | [1 40 266]
    the two of them                    | thetwoofthem   | [1 40 274]
    too many                           | toomany        | [1 40 255]
    very few                           | veryfew        | [1 40 273]
    Indefinite (Singular Only)         | INDS           | Set 42
    a little bit                       | alittlebit     | [1 42 361]
    a little more                      | alittlemore    | [1 42 347]
    another                            | another        | [1 42 317]
    anybody                            | anybody        | [1 42 378]
    anybody else                       | anybodyelse    | [1 42 501]
    anyone                             | anyone         | [1 42 362]
    anyone else                        | anyoneelse     | [1 42 502]
    anything                           | anything       | [1 42 363]
    anything else                      | anythingelse   | [1 42 503]
    each                               | each           | [1 42 319]
    each one                           | eachone        | [1 42 364]
    each other                         | eachother      | [1 42 375]
    each thing                         | eachthing      | [1 42 365]
    either                             | either         | [1 42 825]
    everybody                          | everybody      | [1 42 379]
    everybody else                     | everybodyelse  | [1 42 505]
    everyone                           | everyone       | [1 42 380]
    everyone else                      | everyoneelse   | [1 42 506]
    everything                         | everything     | [1 42 366]
    everything else                    | everythingelse | [1 42 507]
    less                               | less           | [1 42 341]
    little                             | little         | [1 42 342]
    much                               | much           | [1 42 343]
    neither                            | neither        | [1 42 821]
    no one else                        | nooneelse      | [1 42 509]
    nobody                             | nobody         | [1 42 381]
    nobody else                        | nobodyelse     | [1 42 510]
    nothing                            | nothing        | [1 42 368]
    nothing else                       | nothingelse    | [1 42 511]
    one another                        | oneanother     | [1 42 369]
    one's own                          | one'sown       | [1 42 513]
    our own                            | ourown         | [1 42 514]
    plenty                             | lenty          | [1 42 360]
    self                               | self           | [1 42 227]
    selves                             | selves         | [1 42 227]
    somebody                           | somebody       | [1 42 377]
    somebody else                      | somebodyelse   | [1 42 515]
    someone                            | someone        | [1 42 370]
    someone else                       | someoneelse    | [1 42 516]
    something                          | something      | [1 42 371]
    something else                     | somethingelse  | [1 42 517]
    such a thing                       | suchathing     | [1 42 372]
    too much                           | toomuch        | [1 42 344]
    very little                        | verylittle     | [1 42 345]
    Indefinite                         | INDelse-type   | Set 44
    else                               | else           | [1 44 396]
    else's                             | else's         | [1 44 396]
 


.. csv-table:: PRO  -  Pronouns  [5]  Alpha List 
   :header: "Pronouns", "Mnemonic", "Numerics"
   :delim: |
   :widths: auto

    a couple        | acouple        | [1 40 280]
    a few           | afew           | [1 40 245]
    a little bit    | alittlebit     | [1 42 361]
    a little more   | alittlemore    | [1 42 347]
    all             | all            | [1 30 140]
    all k of things | allkofthings   | [1 40 281]
    another         | another        | [1 42 317]
    any             | any            | [1 30 115]
    anybody         | anybody        | [1 42 378]
    anybody else    | anybodyelse    | [1 42 501]
    anyone          | anyone         | [1 42 362]
    anyone else     | anyoneelse     | [1 42 502]
    anything        | anything       | [1 42 363]
    anything else   | anythingelse   | [1 42 503]
    both            | both           | [1 40 250]
    each            | each           | [1 42 319]
    each one        | eachone        | [1 42 364]
    each other      | eachother      | [1 42 375]
    each thing      | eachthing      | [1 42 365]
    either          | either         | [1 42 825]
    else            | else           | [1 44 396]
    else's          | else's         | [1 44 396]
    enough          | enough         | [1 30 146]
    everybody       | everybody      | [1 42 379]
    everybody else  | everybodyelse  | [1 42 505]
    everyone        | everyone       | [1 42 380]
    everyone else   | everyoneelse   | [1 42 506]
    everything      | everything     | [1 42 366]
    everything else | everythingelse | [1 42 507]
    few             | few            | [1 40 251]
    fewer           | fewer          | [1 40 252]
    he              | he             | [5 23 798]
    her             | her            | [5 26 798]
    her own         | herown         | [5 52 332]
    hers            | hers           | [5 50 331]
    herself         | herself        | [5 24 590]
    him             | him            | [5 23 798]
    himself         | himself        | [5 24 582]
    his             | his            | [5 50 221]
    his own         | hisown         | [5 52 333]
    I               | I              | [5 21 795]
    it              | it             | [5 27 303]
    its own         | itsown         | [5 52 334]
    itself          | itself         | [5 24 594]
    less            | less           | [1 42 341]
    little          | little         | [1 42 342]
    many            | many           | [1 40 253]
    me              | me             | [5 21 795]
    mine            | mine           | [5 50 327]
    more            | more           | [1 30 148]
    more . . .      | more . . .     | [1 30 202]
    most            | most           | [1 30 149]
    much            | much           | [1 42 343]
    my own          | myown          | [5 52 335]
    myself          | myself         | [5 24 286]
    neither         | neither        | [1 42 821]
    no one else     | nooneelse      | [1 42 509]
    no other        | noother        | [1 30 231]
    nobody          | nobody         | [1 42 381]
    nobody else     | nobodyelse     | [1 42 510]
    none            | none           | [1 30 203]
    none at all     | noneatall      | [1 30 204]
    nothing         | nothing        | [1 42 368]
    nothing else    | nothingelse    | [1 42 511]
    one             |                | (stored as other POS)
    ones            | ones           | [5 25 802]
    one's           | one's          | [5 25 802]
    one's own       | one'sown       | [1 42 513]
    one another     | oneanother     | [1 42 369]
    oneself         | oneself        | [5 24 581]
    our own         | ourown         | [1 42 514]
    ours            | ours           | [5 50 329]
    ourselves       | ourselves      | [5 24 415]
    own             | own            | [5 52 395]
    plenty          | lenty          | [1 42 360]
    quite a few     | quiteafew      | [1 40 263]
    self            | self           | [1 42 227]
    selves          | selves         | [1 42 227]
    several         | several        | [1 40 266]
    she             | she            | [5 26 798]
    some            | some           | [1 30 151]
    somebody        | somebody       | [1 42 377]
    somebody else   | somebodyelse   | [1 42 515]
    someone         | someone        | [1 42 370]
    someone else    | someoneelse    | [1 42 516]
    something       | something      | [1 42 371]
    something else  | somethingelse  | [1 42 517]
    such a thing    | suchathing     | [1 42 372]
    that            |                | (See Relatives/Interrogatives)
    the two of them | thetwoofthem   | [1 40 274]
    their own       | theirown       | [5 52 336]
    theirs          | theirs         | [5 50 330]
    them            | them           | [5 23 799]
    themselves      | themsleves     | [5 24 631]
    these           | these          | [1 30 102]
    they            | they           | [5 23 799]
    this            | this           | [1 30 102]
    those           | those          | [1 30 103]
    too many        | toomany        | [1 40 255]
    too much        | toomuch        | [1 42 344]
    us              | us             | [5 21 796]
    very few        | veryfew        | [1 40 273]
    very little     | verylittle     | [1 42 345]
    we              | we             | [5 21 796]
    you             | you            | [5 22 797]
    your own        | yourown        | [5 52 337]
    yours           | yours          | [5 50 328]
    yourself        | yourself       | [5 24 454]
    yourselves      | yourselves     | [5 24 496]
    


INTREL - Relatives/Interrogatives  [18] 
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Description", "Mnemonic", "Superset/Set"
   :delim: |
   :widths: auto

    Relatives (Mixed) | REL          | Superset 1
    that/which, etc.  | THATtype     | Set 1
    whatever-type     | WHATEVERtype | Set 48
    Interrogatives    | INTER        | Superset 02
    How/What Type     | HOW/WHATtype | Set 20
    Quantitative      | QUAN         | Set 21
    Temporal          | TEMP         | Set 22
    Place             | PL           | Set 24
    Reason            | RSN          | Set 26

 
 

.. csv-table:: INTREL - Relatives/Interrogatives  [18] 
   :header: "Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

                     | THATtype     | Set 01
    that             | that         | [1 01 103]
    which            | which        | [1 01 392]
    who              | who          | [1 01 401]
    whom             | whom         | [1 01 401]
    whose            | whose        | [1 01 402]
    whereby          |              | (See WC 19)
                     | WHATEVERtype | Set 48
    whatever         | whatever     | [1 48 122]
    whichever        | whichever    | [1 48 123]
    whoever          | whoever      | [1 48 403]
    whomever         | whomever     | [1 48 403]
    (how/what set)   | HOWWHATtype  | Set 20
    how              | how          | [2 20 410]
    what             | what         | [2 20 393]
    to what extent   | towhatextent | [2 20 976]
    (quantitive set) | QUAN         | Set 21
    how far          | howfar       | [2 21 420]
    how many         | howmany      | [2 21 390]
    how much         | howmuch      | [2 21 391]
    (temporal set)   | TEMP         | Set 22
    at what time     | atwhattime   | [2 22 926]
    when             |              | (See WC 19, Superset 04)
    (place set)      | PL           | Set 24
    from where       | fromwhere    | [2 24 441]
    where            | where        | [2 24 440]
    wherever         | wherever     | [2 24 442]
    (reason set)     | RSN          | Set 26
    why              | why          | [2 26 450]
    the fact that    | thefactthat  | [2 26 963]

 
.. csv-table::  INTREL - Relatives/Interrogatives [18]  Alpha List 
   :header: "Relative", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Relative       | Mnemonic     | Numeric
    at what time   | atwhattime   | [2 22 926]
    from where     | fromwhere    | [2 24 441]
    how            | how          | [2 20 410]
    how far        | howfar       | [2 21 420]
    how many       | howmany      | [2 21 390]
    how much       | howmuch      | [2 21 391]
    that           | that         | [1 01 103]
    the fact that  | thefactthat  | [2 26 963]
    to what extent | towhatextent | [2 20 976]
    what           | what         | [2 20 393]
    whatever       | whatever     | [1 48 122]
    when           |              | (See WC 19, Superset 04)
    where          | where        | [2 24 440]
    whereby        | whereby      | [See WC 19]]
    wherever       | wherever     | [2 24 442]
    which          | which        | [1 01 392]
    whichever      | whichever    | [1 48 123]
    who            | who          | [1 01 401]
    whoever        | whoever      | [1 48 403]
    whom           | whom         | [1 01 401]
    whomever       | whomever     | [1 48 403]
    whose          | whose        | [1 01 402]
    why            | why          | [2 26 450]

 
AUXMO -  Auxiliary/Modal Verbs  [WC 12]
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Auxiliaries              | AUX  | Supersets 1, 2, 3, 4
    Modals                   | MOD  | Superset 6
    Subjunctive Modals       | SMOD | Superset 7
    Particles                | PART | Superset 8
    Miscellaneous            | MISC | Superset 10
    Ambiguous Contractions   | AUX  | Superset 12

 

.. csv-table:: AUXMO -  Auxiliary/Modal Verbs  [WC 12]   
   :header: "Auxiliary/Modal Verbs", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto


    Auxiliaries                        |                | Supersets 1, 2, 3, 4
    be                                 | AUXbe          | [1 60 886]
    have                               | AUXhave        | [2 88 710]
    do                                 | AUXdo          | [3 33 466]
    would                              | AUXwould       | [4 17 887]
    will (set)                         | AUXwill-type   |
    shall                              | AUXshall       | [4 20 893]
    will                               | AUXwill        | [4 20 894]
    Modals                             |                | Superset 6
    ought (set)                        | MODcan-type    |
    can                                | MODcan         | [6 21 735]
    cannot                             | MODcannot      | [6 21 895]
    may                                | MODmay         | [6 22 896]
    must                               | MODmust        | [6 23 897]
    have to                            | MODhaveto      | [6 24 898]
    Subjunctive Modals                 |                | Superset 7
    ought (set)                        | SMODought-type | [7 16]
    should                             | SMODshould     | [7 16 912]
    ought                              | SMODought      | [7 16 951]
    ought to                           | SMODoughtto    | [7 16 951]
    ought not to                       | SMODoughtnotto | [7 16 867]
                                       |                |
    could                              | SMODcould      | [7 18 948]
    might                              | SMODmight      | [7 19 965]
    Particles                          |                | Superset 8
    particle (set)                     | PARTto-type    | [8 8]
    to                                 | PARTto         | [8 8 945]
    in order to                        | PARTinorderto  | [8 8 946]
    Miscellaneous                      |                | Superset 10
    about to                           | MISCaboutto    | [10 10 899]
    supposed to                        | MISCsupposedto | [10 10 751]
    Ambiguous Contractions             |                | Superset 12
    is/has (ambiguous contractions)    | AUXis/has      | [12 12 886]
    had/would (ambiguous contractions) | AUXhad/would   | [12 12 710]

 

\* List by Superset   
 

.. csv-table:: AUXMO -  Auxiliary/Modal Verbs  [WC 12]   
   :header: "Auxiliary/Modal Verbs", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    about to                                                       | MISCaboutto    | [10 10 899]
    be                                                             | AUXbe          | [1 60 886]
    can                                                            | MODcan         | [6 21 735]
    cannot                                                         | MODcannot      | [6 21 895]
    could                                                          | SMODcould      | [7 18 948]
    do                                                             | AUXdo          | [3 33 466]
    had/would (ambiguous contraction: He'd spoken. He'd do that. ) | AUXhad/would   | [12 12 710]
    have                                                           | AUXhave        | [2 88 710]
    have to                                                        | MODhaveto      | [6 24 898]
    in order to                                                    | PARTinorderto  | [8 08 946]
    is/has (ambiguous contraction: John's gone)                    | AUXis/has      | [12 12 886]
    may                                                            | MODmay         | [6 22 896]
    might                                                          | SMODmight      | [7 19 965]
    must                                                           | MODmust        | [6 23 897]
    ought                                                          | SMODought      | [7 16 951]
    ought not to                                                   | SMODoughtnotto | [7 16 867]
    ought to                                                       | SMODoughtto    | [7 16 951]
    shall                                                          | AUXshall       | [4 20 893]
    should                                                         | SMODshould     | [7 16 912]
    supposed to                                                    | MISCsupposedto | [10 10 751]
    to                                                             | PARTto         | [8 08 945]
    will                                                           | AUXwill        | [4 20 894]
    would                                                          | AUXwould       | [4 17 887]

\* Alpha List       

 
Verbs  [WC 02] 
-----------------------------------------------------------------------------

.. csv-table:: Descriptive Adjective Sets 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Transitive Verbs   | VT | WC 02
    Intransitive Verbs | VI | WC 02

 
.. csv-table:: VT  -   Transitive Verbs     [02] 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Weak Transitives         |        |
    Subjective Transitive    | SUBTR  | [4]
    Reciprocal Transitive    | RECTR  | [13]
    Strong Transitives       |        |
    Objective Transitive     | OBHUM  | [2]
    Objective Transitive     | OBTR   | [7]
    Di-Transitive            | DITR   | [9]
    Pre-Process              | PREPR  | [6]
    Simple Pre-Verbal        | PREV   | [5]
    Pre-Verbal Di-Transitive | PREVDI | [14]
    Pre-Clausal              | PCL    | [3]
    Pre-Clausal/Verbal       | PRECV  | [8]

 

.. csv-table:: VI  -   Intransitive Verbs     [02] 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Motional    | INMO | [10]
    Existential | INEX | [11]
    Operational | INOP | [12]

 
 

.. csv-table:: OBHUM - Objective Transitive Verbs  [02]   
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     The sculptor created a statue.                                                     | OBHUMundif                | [2   21, 92, 75, 98} | create, etc.
     The boy stole apples from the orchard. The dean praised her for her contributions. | OBHUM (+ prep governance) | [2 xx]               | praise, steal, etc.

\* Human Subject
 

 

 

.. csv-table:: OBTR - Objective Transitive Verbs  [07] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     The sprayer shellacked the surface.                                          | OBTRundif                | [7   21, 92, 75, 98} | shellac
     They increased the count to ten. The machine pressed the grommet into place. | OBTR (+ prep governance) | [7 xx]               | abbreviate, increase, press

\*  Undifferentiated Subject
 

 

 

.. csv-table:: PCL - Pre-Clausal Transitive Verbs  [03] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     We doubt that . . .                                                                                           | PCLdoubt-type   | [3 53] | doubt, ensure, calculate
     We declared that . . . We declared to them that . . . We declared them to be . . . We declared them the . . . | PCLdeclare-type | [3 22] | declare, believe, predict
     We answered that . . . We informed them that . . .                                                            | PCLinform-type  | [3 30] | inform, notify, grant
     We explained that . . . We explained to them that . . .                                                       | PCLexplain-type | [3 32] | explain, indicate, relate
     It strikes me that . . .                                                                                      | PCLstrike-type  | [3 87] | strike, bet, wager

 

 

 

.. csv-table:: SUBTR - Subjective Transitive Verbs  [04] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     They regard him to be . . . | SUBTRregard-type | [4 38] | rate, regard, pronounce

 

 

 

.. csv-table:: PREV - Simple Pre-Verbal Transitive Verbs [05] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     V V'ing or PN     | PREVfinish-type | [5 40] | finish, practice, resume
     V V'ing or V to V | PREVbegin-type  | [5 48] | being, continue, start
     V to V            | PREVfail-type   | [5 49] | fail, grow, refuse

 

 

.. csv-table:: PREPR - Pre-Process Transitive Verbs  [06] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     N V PN - or - N V Verbal Intangible | PREPRaccomplish-type | [6 33] | accomplish,  instigate, perform

 

 

.. csv-table:: PRECV - Pre-Clausal/Verbal  Transitive Verbs [08] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     V to V, V th-/wh-                                                                   | PRECVagree-type  | [8 55] | agree, claim, decide
     V N to V, V N th-/wh-, V N of N                                                     | PRECVtell-type   | [8 62] | convince, persuade, tell
     V to V, V N to V, V that . . ., V N th-/wh-                                         | PRECVask-type    | [8 63] | ask, promise, beg
     V to V, V N to V, V th-/wh-                                                         | PRECVwish-type   | [8 91] | desire, determine, expect
     V N to V, V th-/wh-                                                                 | PRECVenjoin-type | [8 65] | command, direct, enjoin
     V one's V'ing, V to V'ing, V th-/wh-, V to N that . . ., V N N, V N as N, V N to N  | PRECVadmit-type  | [8 85] | admit, confess, report
     V one's V'ing, V one V'ing, V th-/wh-                                               | PRECVrecall-type | [8 45] | recall, anticipate, recollect
     V N V'ing, V N V, V th-/wh-                                                         | PRECVsee-type    | [8 43] | see, hear, notice
     V N to V, V N that . . ., V that . . .                                              | PRECVwarn-type   | [8 50] | warn, advise, instruct
     V V'ing, V that . . ., V N to N and V N N, V to V, V N to V, V N that N V (subjunc) | PRECVintend-type | [8 42] | intend, prefer, remember
     It V N to V, It V N that . . ., N be PP that . . .                                  | PRECVplease-type | [8 77] | please, amuse, concern

 

 

 

.. csv-table:: DITR - Di-Transitive Verbs  [09] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto


    They contributed money to . . . (requires to)      | DITRdispense-type | [9 32] | address, allocate, dispense
    She gave him the book. (optional to)               | DITRgive-type     | [9 37] | pass, allot, give
    He bought her a ring. (optional for)               | DITRfetch-type    | [9 41] | buy, procure, win
    They furnished us the answers. (optional to, with) | DITRprovide-type  | [9 39] | supply, provide, furnish

 

 

 

.. csv-table:: RECTR - Reciprocal Transitive Verbs  [13] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     The contract includes an escape clause.                                 | RECTRinclude-type         | [13 54] | include, exude, contain
     They located pearls in the drawer. The unit exuded oil from the cracks. | RECTR (+ prep governance) | [13 xx] | descend, disgorge, discard

 

 

 

.. csv-table:: PREVDI - Preverbal Di-Transitive Verbs  [14] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     V N to V, V V'ing (limited application)                                                                                    | PREVDIpermit-type   | [14 93] | enable, favor, permit
     V N to V (limited application) -  or - V N to V'ing                                                                        | PREVDIaccustom-type | [14 34] | accustom, dedicate, equate
     V N to V -  or - V N in/into V'ing                                                                                         | PREVDIaid-type      | [14 67] | aid, assist, involve
     V N to V (obligatory), V to V  (obligatory), V N V'ing  (possible), V N PstP  (possible), V V'ing (for love and like only) | PREVDIdare-type     | [14 89] | dare, get, like
     V N from V'ing, V one's V'ing                                                                                              | PREVDIbar-type      | [14 83] | bar, inhibit, prevent
     V V'ing, V N from V'ing, V one's V'ing                                                                                     | PREVDIkeep-type     | [14 36] | keep, preclude, stop
     V N V'ing                                                                                                                  | PREVDIleave-type    | [14 23] | leave, behold
     V N to V, N is V'd N / V N N, N is V'd as N                                                                                | PREVDIappoint-type  | [14 95] | appoint, designate, qualify
     V N  Prep V'ing, V one's V'ing  (limited application)                                                                      | PREVDmisc-type      | [14 70] | accuse, credit, criticize
     V N V, N V'd to V  (limited application), V V (help only)                                                                  | PREVDIbid-type      | [14 88] | bid, help, let
 

.. csv-table:: INMO - Motional Intransitive Verbs  [10] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     They walked into the room.  | INMOinto-type | [10 24] | walk, go, depart, run, fly
     They danced in the streets. | INMOin-type   | [10 68] | sail, dance


.. csv-table:: INEX - Existential Intransitive Verbs  [11] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

     She is the valedictorian of her class.      | INEXbe          | [11 60] | be
     He remained a Democrat all his life.
     She remained at the seashore all summer.    | INEXbecome-type | [11 61] | become, remain
     Their voices sounded cheerful.              | INEXgrow-type   | [11 64] | grow, look, sound
     He seemed happy with the results.
     It seems that the operation was successful. | INEXseem-type   | [11 76] | seem, appear


.. csv-table:: INOP - Operational  Intransitive Verbs  [12] 
   :header: "Patterns", "Mnemonics", "Numerics", "Examples"
   :delim: |
   :widths: auto

    She sings well.                                                      | INOPmisc | [12 29, 31, 97] | end, sing, open
    He stood in the rain.                                                | INOPloc  | [12 68]         | stand, sleep,
                                                                         | INOPpcl  | [12 69]         |
    They refrained from smoking. They conspired to defeat the candidate. | INOPprev | [12 72]         | refrain, conspire, participate, persist, desist

 

Adverbs 
-----------------------------------------------------------------------------

.. csv-table:: INEX - Existential Intransitive Verbs  [11] 
   :header: "Word Class", "Mnemonic", "Numeric", "Supersets"
   :delim: |
   :widths: auto

    Locative Adverbs     | ADV  | WC 03 | temporal, spatial, etc.
    Non-Locative Adverbs | ADVN | WC 06 | manner, degree, etc.

\* Note to Rulewriters

During analysis phase (PARSE 1), the two Adverbial Word Classes are combined under the single ADV [WC03] word class.  Distinctions between the two classes are preserved at the set and subset level.

                     

.. csv-table:: ADV - Locative Adverbs [03] 
   :header: "Sets and Supersets", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Temporal adverbs                                       | TEMP      | [10]
    punctual temporal  (e.g., right now)                   | TEMPpunc  | [10 91]
    durative temporal (e.g., forever)                      | TEMPdur   | [10 92]
    undifferentiated temporal (e.g., someday)              | TEMPundif | [10 93]
    Spatial (e.g., inside)                                 | SPAT      | [11]
    Verb Particles (that can act as adverbs) (e.g., about) | PART      | [12]
    Stative constructions (e.g., pro tem)                  | STAT      | [13]
    Rank/Order (e.g., consecutively)                       | RANK      | [14]
    Frequency (e.g., always)                               | FREQ      | [15]

 
.. csv-table:: ADVN - Non-Locative Adverbs  [06] 
   :header: "Sets and Supersets", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Manner  (e.g., carefully, by hand)                            | MANR      | [18]
    Sentence adverbs (e.g., usually)                              | SENT      | [21]
    Clausal phrase (e.g., if necessary)                           | CL        | [22]
    Probability (e.g., probably)                                  | PROB      | [23]
    Intensifier (adverbs of degree)                               | no code   | no code
    preadverbial intensifier  (e.g., very soon)                   | INTpreav  | [20]
    prenominal intensifer  (e.g.,  just coffee )                  | INTpren   | [24]
    pre-pre-adverbial intensifier (e.g., so very soon)            | INTprepre | [25]
    pre-adjectival/pre-participial intensifier  (e.g., well-said) | INTpreaj  | [27]
    postposed adverb intensifier   (e.g., food enough)            | INTpost   | [28]

 

 


 

.. csv-table:: TEMPpunc  -   Locative Temporal Adverbs: punctuals   [10 91]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs expressing concept of punctual time            | TEMPpunc       | [10 91 91]  |
     subset for adverbs designating past time               | TEMPpuncpast   | [10 91 540] | a long time ago, at an early stage, formerly,  just recently, yesterday,  previously
     subset for adverbs designating present time            | TEMPpuncpres   | [10 91 541] | right now, right this minute, etc.
     subset for adverbs designating future time             | TEMPpuncfut    | [10 91 542] | eventually, in a little while, momentarily, shortly, soon, later
     undifferentiated adverb phrases denoting   punctuality | TEMPpuncundif  | [10 91 543] | at one time or another, early, immediately, instantaneously, instantly
     temporal adverb phrases that can precede "of"          | TEMPofphr      | [10 91 681] | at this point, at the very beginning
     word-specific code                                     | TEMPalready    | [10 91 302] | already
     word-specific code                                     | TEMPatonetime  | [10 91 303] | at one time
     word-specific code                                     | TEMPbythattime | [10 91 335] | by that time

 

.. csv-table:: TEMPdur  -  Locative Temporal Adverbs: duratives  [10 92]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs expressing concept of duration                              | TEMPdur      | [10 92 92]  |
     subset for durative adverbs designating past time                   | TEMPdurpast  | [10 92 540] | ever since then, etc.
     subset for durative adverbs designating present time                | TEMPdurpres  | [10 92 541] | at the present time, now,   currently, for the time being, nowadays
     subset for durative adverbs designating future time                 | TEMPdurfut   | [10 92 542] | henceforth, heretofore, until further notice
     undifferentiated adverb phrases expressing duration of undiff. time | TEMPdurundif | [10 92 543] | at all times, forever, full-time, temporarily, year-round, ad infinitum, from moment to moment, in the short term
     word-specific code                                                  | TEMPever     | [10 92 304] | ever
     word-specific code                                                  | TEMPnever    | [10 92 322] | never

 

.. csv-table:: TEMPundif - Locative Temporal Adverbs: undifferentiated  [10 93]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     subset for undifferentiated temporal adverbs of undifferentiated time | TEMPundif | [10 93 543] | thereafter, apropros, hereinafter, ahead of schedule, ahead of time, at any one time, indefinitely, punctually, etc.
     subset for undifferentiated adverbs designating past time             | TEMPpast  | [10 93 540] | at length, etc.
     subset for undifferentiated adverbs designating present time          | TEMPpres  | [10 93 541] | immanently, etc.
     subset for undifferentiated adverbs designating future time           | TEMPfut   | [10 93 542] | in due course, someday, sometime

 

 

.. csv-table:: SPAT - Locative Spatial Adverbs  [11]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs denoting place or direction (spatial)  | SPAT               | [11 11 11]  | inside, to the right, underneath, alongside, downstairs, elsewhere, globally, online, overseas
     spatial adverb phrases that can precede "of"   | SPATof phr         | [11 11 681] | en route, in opposite directions, in sight, on top
     spatial adverb phrases that can precede a noun | SPATajphr          | [11 11 682] | bottom front, counter-clockwise, incoming/ outgoing, off-line, world-wide
     undifferentiated spatial adverb phrases        | SPATphr            | [11 11 683] | at the bottom of the screen, at the top of the file,  backwards and forwards, far and near,  in mid-flight
     word-specific code                             | SPATthere          | [11 11 350] | there
     word-specific code                             | SPATanywhere       | [11 11 351] | anywhere
     word-specific code                             | SPATatthebeginning | [11 11 353] | at the beginning
     word-specific code                             | SPATherein         | [11 11 357] | herein
     word-specific code                             | SPAThere           | [11 11 359] | here
     word-specific code                             | SPATthereon        | [11 11 377] | thereon
     word-specific code                             | SPATabroad         | [11 11 521] | abroad
     word-specific code                             | SPATaboard         | [11 11 537] | aboard
     word-specific code                             | SPATabeam          | [11 11 590] | abeam
     word-specific code                             | SPATalongside      | [11 11 596] | alongside
     word-specific code                             | SPATfrominside     | [11 11 673] | from inside
     word-specific code                             | SPATfromoutside    | [11 11 678] | from outside
     word-specific code                             | SPATfromwithin     | [11 11 696] | from within
     word-specific code                             | SPATunderneath     | [11 11 733] | underneath
     word-specific code                             | SPATabaft          | [11 11 796] | abaft

 

.. csv-table:: PART  -  Locative Verb Particles (that can act as adverbs) [12]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     verb particles that can act as adverbs | PART                    | Word-Specific Codes | Uniquely-Coded Words
     word-specific code                     | PARTabout               | [12 12 591]         | about
     word-specific code                     | PARTabove               | [12 12 746]         | above
     word-specific code                     | PARTacross              | [12 12 747]         | across
     word-specific code                     | PARTahead               | [12 12 409]         | ahead
     word-specific code                     | PARTalong               | [12 12 595]         | along
     word-specific code                     | PARTallthewayaround     | [12 12 594]         | all the way around
     word-specific code                     | PARTapart               | [12 12 577]         | apart
     word-specific code                     | PARTaround              | [12 12 598]         | around
     word-specific code                     | PARTaside               | [12 12 352]         | aside
     word-specific code                     | PARTatfullspeed         | [12 20 718]         | at full speed
     word-specific code                     | PARTaway                | [12 12 354]         | away
     word-specific code                     | PARTbackward            | [12 12 403]         | backward
     word-specific code                     | PARTbackwards           | [12 12 408]         | backwards
     word-specific code                     | PARTbehind              | [12 12 798]         | behind
     word-specific code                     | PARTbelow               | [12 12 726]         | below
     word-specific code                     | PARTby                  | [12 12 132]         | by
     word-specific code                     | PARTdown                | [12 12 728]         | down
     word-specific code                     | PARTforward             | [12 20 718]         | forward
     word-specific code                     | PARTforwards            | [12 12 720]         | forwards
     word-specific code                     | PARTforth               | [12 12 410]         | forth
     word-specific code                     | PARTfront               | [12 12 407]         | front
     word-specific code                     | PARTfwd                 | [12 20 718]         | fwd
     word-specific code                     | PARTfwd.                | [12 20 718]         | fwd.
     word-specific code                     | PARTin                  | [12 12 481]         | in
     word-specific code                     | PARTinside              | [12 12 486]         | inside
     word-specific code                     | PARTinsideout           | [12 12 489]         | inside out
     word-specific code                     | PARTnear                | [12 12 623]         | near
     word-specific code                     | PARToff                 | [12 12 690]         | off
     word-specific code                     | PARToffandon            | [12 12 424]         | off and on
     word-specific code                     | PARTofforon             | [12 12 425]         | off or on
     word-specific code                     | PARTon                  | [12 12 522]         | on
     word-specific code                     | PARTon-and-off;onandoff | [12 12 422]         | on-and-off; on and off
     word-specific code                     | PARTonoroff             | [12 12 423]         | on or off
     word-specific code                     | PARTout                 | [12 12 697]         | out
     word-specific code                     | PARToutside             | [12 12 699]         | outside
     word-specific code                     | PARTover                | [12 12 748]         | over
     word-specific code                     | PARTpast                | [12 12 801]         | past
     word-specific code                     | PARTthrough             | [12 12 703]         | through
     word-specific code                     | PARTto                  | [12 12 945]         | to
     word-specific code                     | PARTtogether            | [12 12 158]         | together
     word-specific code                     | PARTunder               | [12 12 732]         | under
     word-specific code                     | PARTup                  | [12 12 749]         | up

 

.. csv-table:: STAT  -  Locative Stative Constructions  [13]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     stative constructions                  | STAT          | [13 13 13]  | alone, c.o.d., okay, under construction, underway, upright
     stative phrase that can precede "of"   | STATof phr    | [13 13 681] | on account, on approval, on delivery
     stative phrase that can precede a noun | STATajphr     | [13 13 682] | citywide, companywide, in bulk, in depth, nationwide, per capita
     undifferentiated stative phrases       | STATphr       | [13 13 683] | at any cost, in the long run, in the limelight, on credit, on tap, out of order, pro tem
     word-specific code                     | STATalike     | [13 13 575] | alike
     word-specific code                     | STATinadvance | [13 13 616] | in advance
     word-specific code                     | STATinandout  | [13 13 583] | in and out

 

.. csv-table:: RANK -  Locative Rank/Order Adverbs  [14]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs denoting  rank or order                          | RANK          | [14 14 14]  | alternately, beforehand, consecutively, initially, sequentially, successively, last, second, fifth, fifteenth,
     undifferentiated adverb phrases denoting   rank or order | RANKphr       | [14 14 683] | in reverse order, in succession, in the proper sequence, on a one to one basis, thirty-first, etc.
     word-specific code                                       | RANKatonce    | [14 14 752] | at once
     word-specific code                                       | RANKfirst     | [14 14 753] | first
     word-specific code                                       | RANKprimarily | [14 14 756] | primarily

 

.. csv-table:: FREQ  -  Locative Frequency Adverbs  [15]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs denoting  frequencey                 | FREQ        | [15 15 15]  | always, annually, daily, concurrently, constantly,  endlessly, frequently, often, incessantly, regularly, seldom
     frequency phrase that can precede "of"       | FREQof phr  | [15 15 681] | on request, etc.
     undifferentiated adverb phrases of frequency | FREQphr     | [15 15 683] | day after day, every so often, from time to time, now and again, on occasion, over and over
     word-specific code                           | FREQagain   | [15 15 786] | again
     word-specific code                           | FREQhereof  | [15 15 789] | hereof
     word-specific code                           | FREQonce    | [15 15 787] | once
     word-specific code                           | FREQthereof | [15 15 789] | thereof
     word-specific code                           | FREQtwice   | [15 15 788] | twice

 

.. csv-table:: MANR - Non-Locative Manner Type Adverbs   [18]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

    adverb of manner (how)                | MANR                 | [18 18 18]   | abruptly, capably, discernibly, freely, impartially, literally, routinely persistently,
    adverb phrase that can precede a noun | MANRajphr            | [18 18 682]  | ad hoc, by airmail, face-to-face, from scratch, non-stop, step-by-step
    undifferentiated adverb phrase        | MANRphr              | [18 18 683]  | at random, ex officio, head to foot, upside down, with abandon
    word-specific code                    | MANRbest             | [18 18  102] | best
    word-specific code                    | MANRinthebestpossway | [18 18 102]  | in the best possible way
    word-specific code                    | MANRbetter           | [18 18 103]  | better
    word-specific code                    | MANRpre              | [18 18 317]  | pre-
    word-specific code                    | MANRre               | [18 18 318]  | re-
    word-specific code                    | MANRnon              | [18 18 319]  | non-
    word-specific code                    | MANRsemi             | [18 18 319]  | semi-
    word-specific code                    | MANRde               | [18 18 321]  | de-
    word-specific code                    | MANRinter            | [18 18 324]  | inter-
    word-specific code                    | MANRun               | [18 18 325]  | un-
    word-specific code                    | MANRcontra           | [18 18 326]  | contra-
    word-specific code                    | MANRdis              | [18 18 327]  | dis-
    word-specific code                    | MANRmis              | [18 18 329]  | mis-
    word-specific code                    | MANRtrans            | [18 18 330]  | trans-
    word-specific code                    | MANRbi               | [18 18 331]  | bi-
    word-specific code                    | MANRinmoredetail     | [18 18 684]  | in more detail

 

 

.. csv-table:: INTpreav - Non-Locative Intensifier Adverbs: pre-adverbial   [20]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     pre-adverbial adverbs expressing intensity or degreee | INTpreav       | [20 20 20]  | amazingly, extremely, intensively, largely, moderately, passably, pretty, surprisingly
     word-specific code                                    | INTmore        | [20 20 148] | more
     word-specific code                                    | INTmost        | [20 20 149] | most
     word-specific code                                    | INTfarmore     | [20 20 150] | far more
     word-specific code                                    | INTfairly      | [20 20 153] | fairly
     word-specific code                                    | INTleast       | [20 20 160] | least
     word-specific code                                    | INTquite       | [20 20 163] | quite
     word-specific code                                    | INTtoo         | [20 20 170] | too
     word-specific code                                    | INTvery        | [20 20 171] | very
     word-specific code                                    | INTless        | [20 20 341] | less
     word-specific code                                    | INTalittlemore | [20 20 347] | a little more
     word-specific code                                    | INTalittlebit  | [20 20 361] | a little bit

 

 

.. csv-table:: INTpren -  Non-Locative Intensifier Adverbs:  pre-nominal   [24]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     pre-nominal adverbs expressing intensity or degree | INTpren       | [24 24 270] | by far, either in whole or in part, in whole or in part, mostly, particularly, predominantly, preferably, solely, strictly, surely
     word-specific code                                 | INTespecially | [24 24 271] | especially
     word-specific code                                 | INTjust       | [24 24 272] | just
     word-specific code                                 | INTmerely     | [24 24 273] | merely
     word-specific code                                 | INTonly       | [24 24 274] | only
     word-specific code                                 | INTtoomuch    | [24 24 344] | too much
     word-specific code                                 | INTeven       | [24 24 933] | even
     word-specific code                                 | INThardly     | [24 24 291] | hardly
     word-specific code                                 | INTalmost     | [24 24 151] | almost

 

.. csv-table:: INTprepre -  Non-Locative Intensifier Adverbs:  pre-pre-adverbial   [25]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     pre-preadverbial adverbs expressing intensity or degree | INTprepre   | [25 25 281] | considerably, eminently, increasingly, infinitely, relatively, remarkably, significantly, substantially
     word-specific code                                      | INTreally   | [25 25 164] | really
     word-specific code                                      | INTso       | [25 25 167] | so
     word-specific code                                      | INTsomewhat | [25 25 168] | somewhat
     word-specific code                                      | INTslightly | [25 25 282] | slightly
     word-specific code                                      | INTfar      | [25 25 283] | far
     word-specific code                                      | INTmuch     | [25 25 343] | much

 

 

.. csv-table:: INTpreadj -  Non-Locative Intensifier Adverbs:  pre-adjective   [28]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     pre-descriptive / pre-participial adverbs denoting intensity or degree | INTpreadj     | [28 28 28]  | absolutely, decreasingly, fully, partially, rarely, thoroughly, utterly
     word-specific code                                                     | INTall        | [28 28 140] | all
     word-specific code                                                     | INTcompletely | [28 28 152] | completely
     word-specific codee                                                    | INTfull       | [28 28 154] | full
     word-specific code                                                     | INTwell       | [28 28 172] | well

 

.. csv-table:: INTpost -  Non-Locative Intensifier Adverbs:  postposed adverb  [27]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     post-adjectival adverbs denoting intensity or degree | INTpost   | [27 27 27]  | apiece, etc.
     word-specific code                                   | INTenough | [27 27 146] | enough

 

 

.. csv-table:: SENT  -  Non-Locative Sentence Adverbs   [21]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     sentence adverbs   | SENT               | [21 21 21]  | as a rule, basically, to wit,  fundamentally, ideally, most of all, anyhow, anyway, correspondingly, evidently, overall, in retrospect
     word-specific code | SENTplease         | [21 21 208] | please
     word-specific code | SENTadmittedly     | [21 21 209] | admittedly
     word-specific code | SENTinmostcases    | [21 21 210] | in most cases
     word-specific code | SENTsincerelyyours | [21 21 211] | sincerely yours
     word-specific code | SENTyourstruly     | [21 21 212] | yours truly
     word-specific code | SENTessentially    | [21 21 214] | essentially
     word-specific code | SENTallinall       | [21 21 638] | all in all

 

 

.. csv-table:: CL - Non-Locative Clausal Phrase Adverbs   [22]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     clausal adverbs that act as collapsed clauses | CL                         | [22 22 22]  | if in doubt, regardless, seemingly, generally speaking, etc.
     purposive prepositional phrases               | CLpurp                     | [22 22 226] | for this  reason, for display purposes, for security reasons, for research use only, for testing purpses,
     postposed clausal adverbs                     | CLpost                     | [22 22 228] | anyhow, anyway, unawares,   as a matter of course, in the following manner,  per se
     word-specific code                            | CLviceversa                | [22 22 227] | vice versa
     word-specific code                            | CLvice-versa               | [22 22 227] | vice-versa
     word-specific code                            | CLandsoforth               | [22 22 229] | and so forth
     word-specific code                            | CLandsoon                  | [22 22 229] | and so on
     word-specific code                            | CLetc                      | [22 22 229] | etc
     word-specific code                            | CLetc.                     | [22 22 229] | etc.
     word-specific code                            | CLetcetera                 | [22 22 229] | et cetera
     word-specific code                            | CLuntilproventothecontrary | [22 22 257] | until proven to the contrary
     word-specific code                            | CLin fact                  | [22 22 980] | in fact

 

 

.. csv-table:: PROB - Non-Locative Probability Adverbs  [23]
   :header: "Subset Designation", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto

     adverbs denoting chance, probability, certainty | PROB | [23 23 23] | by chance, by luck, per chance, luckily. assuredly, certainly, for sure, truly, definitely, allegedly, conceivably, in all likelihood, probably, possibly, all things being equal

 

 

.. csv-table:: Alphabetical Listing of Uniquely Coded Adverbs: Locative and Non-Locative
   :header: "Adverb", "Mnemonic", "Word Class", "Description", "Superset, Set, and Subset"
   :delim: |
   :widths: auto

    a little bit                 | INTalittlebit              | ADVN[06]  | Pre-Adverbial        | [20 20 361]
    a little more                | INTalittlemore             | ADVN[06]  | Pre-Adverbial        | [20 20 347]
    abaft                        | SPATabaft                  | ADV  [03] | Spatial              | [11 11 796]
    abeam                        | SPATabeam                  | ADV  [03] | Spatial              | [11 11 590]
    aboard                       | SPATaboard                 | ADV  [03] | Spatial              | [11 11 537]
    about                        | PARTabout                  | ADV  [03] | Verb Particle        | [12 12 591]
    above                        | PARTabove                  | ADV  [03] | Verb Particle        | [12 12 746]
    abroad                       | SPATabroad                 | ADV  [03] | Spatial              | [11 11 521]
    across                       | PARTacross                 | ADV  [03] | Verb Particle        | [12 12 747]
    admittedly                   | SENTadmittedly             | ADVN[06]  | Sentence             | [21 21 209]
    again                        | FREQagain                  | ADV  [03] | Frequency            | [15 15 786]
    ahead                        | PARTahead                  | ADV  [03] | Verb Particle        | [12 12 409]
    alike                        | STATalike                  | ADV  [03] | Stative Construction | [13 13 575]
    almost                       | INTalmost                  | ADVN[06]  | Pre-Nominal          | [24 24 151]
    along                        | PARTalong                  | ADV  [03] | Verb Particle        | [12 12 595]
    alongside                    | SPATalongside              | ADV  [03] | Spatial              | [11 11 596]
    already                      | PUNCalready                | ADV  [03] | Punctual             | [10 91 302]
    all                          | INTall                     | ADVN[06]  | Pre-Adjective        | [28 28 140]
    all in all                   | SENTallinall               | ADVN[06]  | Sentence             | [21 21 638]
    all the way around           | PARTallthewayaround        | ADV  [03] | Verb Particle        | [12 12 594]
    and so forth                 | CLandsoforth               | ADVN[06]  | Clausal Phrase       | [22 22 229]
    and so on                    | CLandsoon                  | ADVN[06]  | Clausal Phrase       | [22 22 229]
    anywhere                     | SPATanywhere               | ADV  [03] | Spatial              | [11 11 351]
    apart                        | PARTapart                  | ADV  [03] | Verb Particle        | [12 12 577]
    around                       | PARTaround                 | ADV  [03] | Verb Particle        | [12 12 598]
    aside                        | PARTaside                  | ADV  [03] | Verb Particle        | [12 12 352]
    at full speed                | PARTatfullspeed            | ADV  [03] | Verb Particle        | [12 20 718]
    at one time                  | PUNCat one time            | ADV  [03] | Punctual             | [10 91 303]
    at once                      | RANKatonce                 | ADV  [03] | Rank/Order           | [14 14 752]
    at the beginning             | SPATatthebeginning         | ADV  [03] | Spatial              | [11 11 353]
    away                         | PARTaway                   | ADV  [03] | Verb Particle        | [12 12 354]
    backward                     | PARTbackward               | ADV  [03] | Verb Particle        | [12 12 403]
    backwards                    | PARTbackwards              | ADV  [03] | Verb Particle        | [12 12 408]
    behind                       | PARTbehind                 | ADV  [03] | Verb Particle        | [12 12 798]
    below                        | PARTbelow                  | ADV  [03] | Verb Particle        | [12 12 726]
    best                         | MANRbest                   | ADVN[06]  | Manner               | [18 18  102]
    better                       | MANRbetter                 | ADVN[06]  | Manner               | [18 18 103]
    bi-                          | MANRbi                     | ADVN[06]  | Manner               | [18 18 331
    by                           | PARTby                     | ADV  [03] | Verb Particle        | [12 12 132]
    by that time                 | PUNCby that time           | ADV  [03] | Punctual             | [10 91 335]
    completely                   | INTcompletely              | ADVN[06]  | Pre-Adjective        | [28 28 152]
    contra-                      | MANRcontra                 | ADVN[06]  | Manner               | [18 18 326]
    de-                          | MANRde                     | ADVN[06]  | Manner               | [18 18 321]
    dis-                         | MANRdis                    | ADVN[06]  | Manner               | [18 18 327]
    down                         | PARTdown                   | ADV  [03] | Verb Particle        | [12 12 728]
    enough                       | INTenough                  | ADVN[06]  | Post Adj/Adverb      | [27 27 146]
    especially                   | INTespecially              | ADVN[06]  | Pre-Nominal          | [24 24 271]
    essentially                  | SENTessentially            | ADVN[06]  | Sentence             | [21 21 214]
    et cetera                    | CLetcetera                 | ADVN[06]  | Clausal Phrase       | [22 22 229]
    etc                          | CLetc                      | ADVN[06]  | Clausal Phrase       | [22 22 229]
    etc.                         | CLetc.                     | ADVN[06]  | Clausal Phrase       | [22 22 229]
    even                         | INTeven                    | ADVN[06]  | Pre-Nominal          | [24 24 933]
    ever                         | TEMPever                   | ADV  [03] | Temporal             | [10 92 304]
    far                          | INTfar                     | ADVN[06]  | Pre-Preadverbial     | [25 25 283]
    far more                     | INTfarmore                 | ADVN[06]  | Pre-Adverbial        | [20 20 150]
    fairly                       | INTfairly                  | ADVN[06]  | Pre-Adverbial        | [20 20 153]
    first                        | RANKfirst                  | ADV  [03] | Rank/Order           | [14 14 753]
    forth                        | PARTforth                  | ADV  [03] | Verb Particle        | [12 12 410]
    forward                      | PARTforward                | ADV  [03] | Verb Particle        | [12 20 718]
    forwards                     | PARTforwards               | ADV  [03] | Verb Particle        | [12 12 720]
    from inside                  | SPATfrominside             | ADV  [03] | Spatial              | [11 11 673]
    from outside                 | SPATfromoutside            | ADV  [03] | Spatial              | [11 11 678]
    from within                  | SPATfromwithin             | ADV  [03] | Spatial              | [11 11 696]
    front                        | PARTfront                  | ADV  [03] | Verb Particle        | [12 12 407]
    full                         | INTfull                    | ADVN[06]  | Pre-Adjective        | [28 28 154]
    fwd                          | PARTfwd                    | ADV  [03] | Verb Particle        | [12 20 718]
    fwd.                         | PARTfwd.                   | ADV  [03] | Verb Particle        | [12 20 718]
    hardly                       | INThardly                  | ADVN[06]  | Pre-Nominal          | [24 24 291]
    here                         | SPAThere                   | ADV  [03] | Spatial              | [11 11 359]
    herein                       | SPATherein                 | ADV  [03] | Spatial              | [11 11 357]
    hereof                       | FREQhereof                 | ADV  [03] | Frequency            | [15 15 789]
    in                           | PARTin                     | ADV  [03] | Verb Particle        | [12 12 481]
    in advance                   | STATinadvance              | ADV  [03] | Stative Construction | [13 13 616]
    in and out                   | STATinandout               | ADV  [03] | Stative Construction | [13 13 583]
    in fact                      | CLin fact                  | ADVN[06]  | Clausal Phrase       | [22 22 980]
    in more detail               | MANRinmoredetail           | ADVN[06]  | Manner               | [18 18 684]
    in most cases                | SENTinmostcases            | ADVN[06]  | Sentence             | [21 21 210]
    inside                       | PARTinside                 | ADV  [03] | Verb Particle        | [12 12 486]
    inside out                   | PARTinsideout              | ADV  [03] | Verb Particle        | [12 12 489]
    inter-                       | MANRinter                  | ADVN[06]  | Manner               | [18 18 324]
    in the best possible way     | MANRinthebestpossway       | ADVN[06]  | Manner               | [18 18 102]
    just                         | INTjust                    | ADVN[06]  | Pre-Nominal          | [24 24 272]
    least                        | INTleast                   | ADVN[06]  | Pre-Adverbial        | [20 20 160]
    less                         | INTless                    | ADVN[06]  | Pre-Adverbial        | [20 20 341]
    merely                       | INTmerely                  | ADVN[06]  | Pre-Nominal          | [24 24 273]
    mis-                         | MANRmis                    | ADVN[06]  | Manner               | [18 18 329]
    more                         | INTmore                    | ADVN[06]  | Pre-Adverbial        | [20 20 148]
    most                         | INTmost                    | ADVN[06]  | Pre-Adverbial        | [20 20 149]
    much                         | INTmuch                    | ADVN[06]  | Pre-Preadverbial     | [25 25 343]
    near                         | PARTnear                   | ADV  [03] | Verb Particle        | [12 12 623]
    never                        | TEMPnever                  | ADV  [03] | Temporal             | [10 92 322]
    non-                         | MANRnon                    | ADVN[06]  | Manner               | [18 18 319]
    off                          | PARToff                    | ADV  [03] | Verb Particle        | [12 12 690]
    off and on                   | PARToffandon               | ADV  [03] | Verb Particle        | [12 12 424]
    off or on                    | PARTofforon                | ADV  [03] | Verb Particle        | [12 12 425]
    on                           | PARTon                     | ADV  [03] | Verb Particle        | [12 12 522]
    on-and-off; on and off       | PARTon-and-off;onandoff    | ADV  [03] | Verb Particle        | [12 12 422]
    on or off                    | PARTonoroff                | ADV  [03] | Verb Particle        | [12 12 423]
    once                         | FREQonce                   | ADV  [03] | Frequency            | [15 15 787]
    only                         | INTonly                    | ADVN[06]  | Pre-Nominal          | [24 24 274]
    out                          | PARTout                    | ADV  [03] | Verb Particle        | [12 12 697]
    outside                      | PARToutside                | ADV  [03] | Verb Particle        | [12 12 699]
    over                         | PARTover                   | ADV  [03] | Verb Particle        | [12 12 748]
    past                         | PARTpast                   | ADV  [03] | Verb Particle        | [12 12 801]
    please                       | SENTplease                 | ADVN[06]  | Sentence             | [21 21 208]
    pre-                         | MANRpre                    | ADVN[06]  | Manner               | [18 18 317]
    primarily                    | RANKprimarily              | ADV  [03] | Rank/Order           | [14 14 756]
    quite                        | INTquite                   | ADVN[06]  | Pre-Adverbial        | [20 20 163]
    re-                          | MANRre                     | ADVN[06]  | Manner               | [18 18 318]
    really                       | INTreally                  | ADVN[06]  | Pre-Pre-adverbial    | [25 25 164]
    semi-                        | MANRsemi                   | ADVN[06]  | Manner               | [18 18 319]
    sincerely yours              | SENTsincerelyyours         | ADVN[06]  | Sentence             | [21 21 211]
    slightly                     | INTslightly                | ADVN[06]  | Pre-Pre-adverbial    | [25 25 282]
    so                           | INTso                      | ADVN[06]  | Pre-Pre-adverbial    | [25 25 167]
    somewhat                     | INTsomewhat                | ADVN[06]  | Pre-Pre-adverbial    | [25 25 168]
    there                        | SPATthere                  | ADV  [03] | Spatial              | [11 11 350]
    thereof                      | FREQthereof                | ADV  [03] | Frequency            | [15 15 789]
    thereon                      | SPATthereon                | ADV  [03] | Spatial              | [11 11 377]
    through                      | PARTthrough                | ADV  [03] | Verb Particle        | [12 12 703]
    to                           | PARTto                     | ADV  [03] | Verb Particle        | [12 12 945]
    together                     | PARTtogether               | ADV  [03] | Verb Particle        | [12 12 158]
    too                          | INTtoo                     | ADVN[06]  | Pre-Adverbial        | [20 20 170]
    too much                     | INTtoomuch                 | ADVN[06]  | Pre-Nominal          | [24 24 344]
    trans-                       | MANRtrans                  | ADVN[06]  | Manner               | [18 18 330]
    twice                        | FREQtwice                  | ADV  [03] | Frequency            | [15 15 788]
    un-                          | MANRun                     | ADVN[06]  | Manner               | [18 18 325]
    under                        | PARTunder                  | ADV  [03] | Verb Particle        | [12 12 732]
    underneath                   | SPATunderneath             | ADV  [03] | Spatial              | [11 11 733]
    until proven to the contrary | CLuntilproventothecontrary | ADVN[06]  | Clausal Phrase       | [22 22 257]
    up                           | PARTup                     | ADV  [03] | Verb Particle        | [12 12 749]
    very                         | INTvery                    | ADVN[06]  | Pre-Adverbial        | [20 20 171]
    vice versa                   | CLviceversa                | ADVN[06]  | Clausal Phrase       | [22 22 227]
    vice-versa                   | CLvice-versa               | ADVN[06]  | Clausal Phrase       | [22 22 227]
    well                         | INTwell                    | ADVN[06]  | Pre-Adjective        | [28 28 172]
    yours truly                  | SENTyourstruly             | ADVN[06]  | Sentence             | [21 21 212]

    

Prepositions 
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: 
   :delim: |
   :widths: auto

    Non-Locatives | PRPN | WC11
    Locatives     | PRP  | WC13


Note to Rulewriters 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

During analysis phase (PARSE 1), the two Prepositional Word Classes are combined under the single PRP [WC13] word class.  Distinctions between the two Word Classes classes are preserved at the set and subset level.

                 


.. csv-table:: PRPN - Non-Locative Prepositions [11] Supersets and Sets
   :header: "Preposition Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    possessive superset (of)                             | POSS               | 1
    of (uniquely)                                        | POSSof             | [1 51 101]
    benefactive (for, etc.)                              | BENE               | 3
    for type                                             | BENEfortype        | [3 53]
    instrumental (by, etc.)                              | INST               | 4
    by type                                              | INSTbytype         | [4 54]
    associative (with, etc.)                             | ASSOC              | 5
    with type                                            | ASSOCwithtype      | [5 55]
    analogical (unlike, etc.)                            | ALOG               | 6
    in accord with type                                  | ALOGinaccwithtype  | [6 24]
    unlike type                                          | ALOGunliketype     | [6 25]
    reference (relative to, etc.)                        | REF                | 7
    vis a vis type                                       | REFvisavistype     | [7 26]
    in opposition to type                                | REFinopptotype     | [7 27]
    causes/conditions (because of, etc.)                 | CAUS               | 9
    owing to type                                        | CAUSowingtotype    | [9 28]
    despite type                                         | CAUSdespitetype    | [9 29]
    inclusion/exclusion (in lieu of, etc.)               | INCL               | 11
    inclusive of type                                    | INCLinclusoftype   | [11 30]
    exclusive of type                                    | INCLexclusoftype   | [11 31]
    pre-verbal prep phrases (with a view to [v'g], etc.) | PREV               | 12
    with a view to type                                  | PREVwithviewtotype | [12 62]

 

.. csv-table:: PRP- Locative Prepositions [13] Supersets and Sets 
   :header: "Preposition Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    in/among type                                            | IN            | 1
    in/among type                                            | INtype        | [1 71]
    on type                                                  | ON            | 2
    on type                                                  | ONtype        | [2 72]
    through type                                             | THRU          | 3
    through type                                             | THRUtype      | [3 73]
    toward type                                              | TWRD          | 4
    toward type                                              | TWRDtype      | [4 74]
    at/near type                                             | AT            | 5
    at/near type                                             | ATtype        | [5 75]
    from/off/out type                                        | FROM          | 6
    from/off/out type                                        | FROMtype      | [6 76]
    in front of type                                         | OPPOS         | 7
    in front of type                                         | OPPOStype     | [7 77]
    reserved for "to"                                        | TO            | 8
    word-specific code for "to"                              | TOtype        | [8 78 945]
    under/below type                                         | UNDR          | 9
    under/below type                                         | UNDRtype      | [9 79]
    above type                                               | ABOVE         | 10
    above type                                               | ABOVEtype     | [10 80]
    during/prior to type                                     | TEMP          | 11
    expect process noun type (e.g., during removal of . . .) | TEMPpntype    | [11 41]
    expect v'ing type (e.g., prior to forming the . . .)     | TEMPvingtype  | [11 42]
    expect arithmate type (e.g., at a rate of seven . . .)   | TEMParithtype | [11 43]
    behind type                                              | BEHD          | 12
    behind type                                              | BEHDtype      | [12 82]
    around type                                              | ARND          | 13
    around type                                              | ARNDtype      | [13 83]
    outside type                                             | OUTSD         | 14
    outside type                                             | OUTSDtype     | [14 84]

 

.. csv-table:: POSS - Possessive Prepositions [1] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    of | POSSof | word-specific code for "of" | [1 51 101]


.. csv-table:: BENE - Benefactive Prepositions [3] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     for type           | set code           | BENEfortype         | [3 53]
     as a favor to      | word-specific code | BENEasafavor to     | [3 53 105]
     for                | word-specific code | BENEfor             | [3 53 106]
     for ease of        | word-specific code | BENEforeaseof       | [3 53 110]
     for purposes of    | word-specific code | BENEforpurposesof   | [3 53 111]
     for the benefit of | generic code       | BENEforthebenefitof | [3 53 53]
     for use by         | word-specific code | BENEforuseby        | [3 53 113]

 

.. csv-table:: INST - Instrumental Prepositions [4] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     by type             | set code           | INSTbytype           | [4 54]
     by                  | word-specific code | INSTby               | [4 54 132]
     by a combination of | word-specific code | INSTbycombof         | [4 54 133]
     by arrangement with | word-specific code | INSTbyarrangwith     | [4 54 134]
     by means of         | word-specific code | INSTbymeansof        | [4 54 135]
     by means other than | word-specific code | INSTbymeansotherthan | [4 54 136]
     by type of          | word-specific code | INSTbytypeof         | [4 54 137]
     by way of           | word-specific code | INSTbywayof          | [4 54 138]
     under contract to   | word-specific code | INSTundercontractto  | [4 54 143]
     via                 | word-specific code | INSTvia              | [4 54 141]
     with the aid of     | word-specific code | INSTwithaidof        | [4 54 142]

 

.. csv-table:: ASSOC - Associative Prepositions [5] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     with type           | set code           | ASSOCwithtype         | [5 55]
     along with          | word-specific code | ASSOCalongwith        | [5 55 156]
     in anticipation of  | generic code       | ASSOCinanticipationof | [5 55]
     in combination with | word-specific code | ASSOCincombwith       | [5 55 163]
     together with       | word-specific code | ASSOCtogetherwith     | [5 55 158]
     with                | word-specific code | ASSOCwith             | [5 55 159]
     with and without    | word-specific code | ASSOCwithandwithout   | [5 55 160]
     with or without     | word-specific code | ASSOCwithorwithout    | [5 55 161]
     with/without        | word-specific code | ASSOCwith/without     | [5 55 162]

 

.. csv-table:: ALOG - Analogical Prepositions [6] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     in accord with type        | set code           | ALOGinaccwithtype     | [6 24]
     as a substitute for        | word-specific code | ALOGasasubfor         | [6 24 188]
     as compared to             | word-specific code | ALOGascomparedto      | [6 24189]
     as compared with           | word-specific code | ALOGascomparedwith    | [6 24 190]
     as related to              | word-specific code | ALOGasrelatedto       | [6 24 193]
     corresponding to           | word-specific code | ALOGcorrespondingto   | [6 24 199]
     for reasons of             | word-specific code | ALOGforreasonsof      | [6 24 192]
     in accord with             | generic code       | ALOGinaccordwith      | [6 24]
     in accordance with         | word-specific code | ALOGinaccordancewith  | [6 24 204]
     in agreement with          | word-specific code | ALOGinagreementwith   | [6 24 205]
     in congruence with         | word-specific code | ALOGincongruencewith  | [6 24 206]
     in contact with            | word-specific code | ALOGincontactwith     | [6 24 226]
     in sync with               | word-specific code | ALOGinsyncwith        | [6 24 229]
     less than or equal to      | word-specific code | ALOGlessthanorequalto | [6 24 230]
     proportional to            | word-specific code | ALOGproportionalto    | [6 24 232]
     unlike type                | set code           | ALOGunliketype        | [6 25]
     as contrasted to           | word-specific code | ALOGascontrastedto    | [6 25 246]
     in contrast to             | word-specific code | ALOGincontrastto      | [6 25 248]
     for the differentiation of | word-specific code | ALOGforthediffof      | [6 25 247]
     unlike                     | word-specific code | ALOGunlike            | [6 25 252]
     versus                     | word-specific code | ALOGversus            | [6 25 253]
     vs.                        | word-specific code | ALOGvs.               | [6 25 253]

 

.. csv-table:: REF - Reference/Non-Reference Type Prepositions [7] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     vis a vis type        | set code           | REFvisavistype         | [7 26]
     according to          | word-specific code | REFaccordingto         | [7 26 261]
     as a basis for        | word-specific code | REFasbasisfor          | [7 26 262]
     as concerns           | word-specific code | REFasconcerns          | [7 26 263]
     as per                | word-specific code | REFasper               | [7 26 265]
     as regards            | word-specific code | REFasregards           | [7 26 266]
     from the viewpoint of | word-specific code | REFfromviewptof        | [7 26 268]
     in charge of          | word-specific code | REFinchargeof          | [7 26 269]
     in collaboration with | word-specific code | REFincollaborationwith | [7 26 270]
     in comparison to      | word-specific code | REFincompto            | [7 26 271]
     in comparison with    | word-specific code | REFincompwith          | [7 26 272]
     in compliance with    | word-specific code | REFincompliancewith    | [7 26 272]
     in conjunction with   | word-specific code | REFinconjwith          | [7 26 274]
     in connection with    | word-specific code | REFinconnecwith        | [7 26 275]
     in coordination with  | word-specific code | REFincoordwith         | [7 26 277]
     in proportion to      | word-specific code | REFinproportionto      | [7 26 278]
     in regard to          | word-specific code | REFinregardto          | [7 26 279]
     in relation to        | word-specific code | REFinrelationto        | [7 26 280]
     in response to        | word-specific code | REFinresponseto        | [7 26 301]
     in terms of           | word-specific code | REFintermsof           | [7 26 302]
     in the case of        | word-specific code | REFinthecaseof         | [7 26 303]
     in the course of      | word-specific code | REFincourseof          | [7 26 304]
     in the face of        | word-specific code | REFinfaceof            | [7 26 305]
     in the form of        | word-specific code | REFintheformof         | [7 26 306]
     in the judgement of   | word-specific code | REFinjudgmentof        | [7 26 307]
     in the light of       | word-specific code | REFinthe lightof       | [7 26 308]
     in the light of       | word-specific code | REFinthematterof       | [7 26 323]
     in view of            | word-specific code | REFinviewof            | [7 26 309]
     of concern to         | word-specific code | REFofconcernto         | [7 26 310]
     on the matter of      | word-specific code | REFonmatterof          | [7 26 323]
     out of regard for     | word-specific code | REFoutofregardfor      | [7 26 312]
     per                   | word-specific code | REFper                 | [7 26 311]
     pursuant to           | word-specific code | REFpursuantto          | [7 26 320]
     relative to           | word-specific code | REFrelativeto          | [7 26 313]
     under the aegis of    | generic code       | REFunderaegisof        | [7 26]
     under the auspices of | generic code       | REFunderauspicesof     | [7 26]
     vis a vis             | word-specific code | REFvisavis             | [7 26 207]
     with regard to        | word-specific code | REFwithregardto        | [7 26 314]
     with respect to       | word-specific code | REFwithrespectto       | [7 26 315]
     with the goal of      | word-specific code | REFwithgoalof          | [7 26 316]
     in opposition to type | set code           | REFinopptotype         | [7 27]
     in opposition to      | word-specific code | REFinoppositionto      | [7 27 338]
     regardless of         | word-specific code | REFregardlessof        | [7 27 339]
     without reference to  | word-specific code | REFwithoutrefto        | [7 27 340]
     without regard to     | word-specific code | REFwithoutregardto     | [7 27 341]
     without respect to    | word-specific code | REFwithoutrespecto     | [7 27 342]

 

.. csv-table:: CAUS - Cause and Condition Prepositions [9] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     owing to type          | set code           | CAUSowingtotype      | [9 28]
     as a result of         | word-specific code | CAUSasaresult of     | [9 28 351]
     at the request of      | word-specific code | CAUSattherequestof   | [9 28 352]
     because of             | word-specific code | CAUSbecause of       | [9 28 353]
     by action of           | word-specific code | CAUSbyactionof       | [9 28 354]
     by reason of           | word-specific code | CAUSbyreasonof       | [9 28 355]
     by virtue of           | word-specific code | CAUSbyvirtueof       | [9 28 356]
     for the sake of        | word-specific code | CAUSforsakeof        | [9 28 375]
     in behalf of           | word-specific code | CAUSinbehalfof       | [9 28 372]
     in case of             | word-specific code | CAUSincaseof         | [9 28 360]
     in consequence of      | word-specific code | CAUSinconsequenceof  | [9 28 362]
     in favor of            | word-specific code | CAUSinfavorof        | [9 28 402]
     in support of          | word-specific code | CAUSinsupportof      | [9 28 363]
     in the event of        | word-specific code | CAUSineventof        | [9 28 364]
     in the interest of     | word-specific code | CAUSininterestof     | [9 28 365]
     on account of          | word-specific code | CAUSonaccountof      | [9 28 366]
     on behalf of           | word-specific code | CAUSonbehalfof       | [9 28 367]
     on the advice of type  | set code           | CAUSonadviceof       | [9 28]
     on the basis of        | word-specific code | CAUSonbasisof        | [9 28 368]
     on the part of         | word-specific code | CAUSonpartof         | [9 28 374]
     on the strength of     | word-specific code | CAUSonstrengthof     | [9 28 369]
     on the verge of        | word-specific code | CAUSonvergeof        | [9 28 349]
     owing to               | word-specific code | CAUSowingto          | [9 28 370]
     pending                | word-specific code | CAUSpending          | [9 28 371]
     to the advantage of    | word-specific code | CAUStoadvantageof    | [9 28 373]
     upon initiation by     | word-specific code | CAUSuponinitiationby | [9 28 376]
     despite type           | set code           | CAUSdespitetype      | [9 29]
     at the expense of      | word-specific code | CAUSatexpenseof      | [9 29 396]
     despite                | word-specific code | CAUSdespite          | [9 29 397]
     for lack of            | word-specific code | CAUSforlackof        | [9 29 398]
     in spite of            | word-specific code | CAUSinspiteof        | [9 29 399]
     in the absence of      | word-specific code | CAUSinabsenceof      | [9 29 400]
     independently of       | word-specific code | CAUSindependentlyof  | [9 29 401]
     to the debit of        | word-specific code | CAUStodebitof        | [9 29 405]
     to the disadvantage of | word-specific code | CAUStodisadvantageof | [9 29 406]

 

.. csv-table:: INCL - Inclusion/Exclusion Prepositions [11] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     inclusive of type     | set code           | INCLinclusoftype    | [11 30]
     in addition to        | word-specific code | INCLinadditionto    | [11 30 417]
     inclusive of          | word-specific code | INCLinclusiveof     | [11 30 421]
     plus/minus            | word-specific code | INCLplus/minus      | [11 30 426]
     exclusive of type     | set code           | INCLexclusoftype    | [11 31]
     apart from            | word-specific code | INCLapartfrom       | [11 31 431]
     aside from            | word-specific code | INCLasidefrom       | [11 31 432]
     devoid of             | word-specific code | INCLdevoidof        | [11 31 434]
     except for            | word-specific code | INCLexceptfor       | [11 31 435]
     exclusive of          | word-specific code | INCLexclusive of    | [11 31 436]
     in lieu of            | word-specific code | INCLinlieuof        | [11 31 437]
     in place of           | word-specific code | INCLinplaceof       | [11 31 438]
     in the place of       | word-specific code | INCLintheplaceof    | [11 31 440]
     instead of            | word-specific code | INCLinsteadof       | [11 31 441]
     other than            | word-specific code | INCLotherthan       | [11 31 442]
     with the exception of | word-specific code | INCLwithexceptionof | [11 31 445]
     without               | word-specific code | INCLwithout         | [11 31 446]

 

.. csv-table:: PREV - Pre-Verbal Prepositional Phrases [12] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     for the pupose of [v'g] | word-specific code | PREVforpurposeof | [12 62 359]
     with a view to [v'g]    | word-specific code | PREVwithaviewto  | [12 62 443]

 

.. csv-table:: IN - in/among Type Prepositions [1] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     amid             | word-specific code | INamid          | [1 71 475]
     amidst           | word-specific code | INamidst        | [1 71 476]
     among            | word-specific code | INamong         | [1 71 477]
     amongst          | word-specific code | INamongst       | [1 71 478]
     between          | word-specific code | INbetween       | [1 71 480]
     in               | word-specific code | INin            | [1 71 481]
     in and out of    | word-specific code | INinandoutof    | [1 71 482]
     in between       | word-specific code | INinbetween     | [1 71 483]
     in the middle of | word-specific code | INinmiddleof    | [1 71 484]
     in the midst of  | word-specific code | INinmidstof     | [1 71 485]
     inside           | word-specific code | INinside        | [1 71 486]
     into             | word-specific code | INinto          | [1 71 487]
     on the inside of | word-specific code | INontheinsideof | [1 71 488]
     throughout       | word-specific code | INthroughout    | [1 71 491]
     within           | word-specific code | INwithin        | [1 71 493]

 

.. csv-table:: ON - on Type Prepositions [2] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     aboard             | word-specific code | ONaboard      | [2 72 537]
     on                 | word-specific code | ONon          | [2 72 522]
     on top of          | word-specific code | ONontopof     | [2 72 523]
     on the far side of | word-specific code | ONonfarsideof | [2 72 693]
     onto               | word-specific code | ONonto        | [2 72 524]
     upon               | word-specific code | ONupon        | [2 72 525]

 

.. csv-table:: THRU - through Type Prepositions [3] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     at a distance of | word-specific code | THRUatdistanceof | [3 73 674]
     through          | word-specific code | THRUthrough      | [3 73 703]
     thru             | word-specific code | THRUthru         | [3 73 703]

 

.. csv-table:: TWRD - toward Type Prepositions [4] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     all the way to      | word-specific code | TWRDallwayto      | [4 74 562]
     in the direction of | word-specific code | TWRDindirectionof | [4 74 565]
     to a minimum of     | word-specific code | TWRDtominimumof   | [4 74 567]
     to a maximum of     | word-specific code | TWRDtomaximumof   | [4 74 568]
     to the rear of      | word-specific code | TWRDtorearof      | [4 74 572]
     toward              | word-specific code | TWRDtoward        | [4 74 574]
     toward the rear of  | word-specific code | TWRDtowardrearof  | [4 74 576]
     towards             | word-specific code | TWRDtowards       | [4 74 574]

 

.. csv-table:: AT - at/near Type Prepositions [5] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     abeam                          | word-specific code | ATabeam             | [5 75 590]
     against                        | word-specific code | ATagainst           | [5 75 593]
     along                          | word-specific code | ATalong             | [5 75 595]
     alongside                      | word-specific code | ATalongside         | [5 75 596]
     alongside of                   | word-specific code | ATalongsideof       | [5 75 597]
     at                             | word-specific code | ATat                | [5 75 599]
     at the back of                 | word-specific code | ATatbackof          | [5 75 601]
     at the bottom of               | word-specific code | ATatbottomof        | [5 75 603]
     at the left of                 | word-specific code | ATatleftof          | [5 75 606]
     at the left side of            | word-specific code | ATatleftsideof      | [5 75 607]
     at the rear of                 | word-specific code | ATatrearof          | [5 75 608]
     at the right of                | word-specific code | ATatrightof         | [5 75 609]
     at the right side of           | word-specific code | ATatrightsideof     | [5 75 610]
     at the side of                 | word-specific code | ATatsideof          | [5 75 611]
     at the top of                  | word-specific code | ATattopof           | [5 75 612]
     at the very top of             | word-specific code | ATatverytopof       | [5 75 613]
     beside                         | word-specific code | ATbeside            | [5 75 616]
     in line with                   | word-specific code | ATinlinewith        | [5 75 536]
     in parallel with               | word-specific code | ATinparallelwith    | [5 75 621]
     near                           | word-specific code | ATnear              | [5 75 623]
     on the left hand side of       | word-specific code | ATonlefthandsideof  | [5 75 627]
     on the other side of           | word-specific code | ATonothersideof     | [5 75 628]
     on the side of                 | word-specific code | ATonsideof          | [5 75 629]
     on this side of                | word-specific code | ATonthissideof      | [5 75 630]
     to the east of                 | word-specific code | ATtoeastof          | [5 75 633]
     to the left of                 | word-specific code | ATtoleftof          | [5 75 634]
     to the left or right of        | word-specific code | ATtoleftorrightof   | [5 75 638]
     to the left or to the right of | word-specific code | ATtoleftortorightof | [5 75 638]
     to the north of                | word-specific code | ATtonorthof         | [5 75 635]
     to the right of                | word-specific code | ATtorightof         | [5 75 637]
     to the right or left of        | word-specific code | ATtorightorleftof   | [5 75 636]
     to the south of                | word-specific code | ATtosouthof         | [5 75 639]
     to the west of                 | word-specific code | ATtowestof          | [5 75 640]
     within reach of                | word-specific code | ATwithinreachof     | [5 75 642]

 

.. csv-table:: FROM - from/off/out Type Prepositions [6] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     from               | word-specific code | FROMfrom            | [6 76 679]
     from inside        | word-specific code | FROMfrominside      | [6 76 673]
     from inside of     | word-specific code | FROMfrominsideof    | [6 76 677]
     from outside       | word-specific code | FROMfromoutside     | [6 76 678]
     from outside of    | word-specific code | FROMfromoutsideof   | [6 76 691]
     from within        | word-specific code | FROMfromwithin      | [6 76 696]
     further away from  | word-specific code | FROMfurtherawayfrom | [6 76 689]
     off                | word-specific code | FROMoff             | [6 76 690]
     off of             | word-specific code | FROMoffof           | [6 76 675]
     off to the side of | word-specific code | FROMofftosideof     | [6 76 692]
     out of             | word-specific code | FROMoutof           | [6 76 676]
     out of reach of    | word-specific code | FROMoutofreachof    | [6 76 698]

 

.. csv-table:: OPPOS - opposite Type Prepositions [7] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     abreast of      | word-specific code | OPPOSabreastof   | [7 77 671]
     across          | word-specific code | OPPOSacross      | [7 77 747]
     across from     | word-specific code | OPPOSacrossfrom  | [7 77 672]
     ahead of        | word-specific code | OPPOSaheadof     | [7 77 716]
     at the front of | word-specific code | OPPOSatfrontof   | [7 77 605]
     in advance of   | word-specific code | OPPOSinadvanceof | [7 77 716]
     in front of     | word-specific code | OPPOSinfrontof   | [7 77 719]
     opposite        | word-specific code | OPPOSopposite    | [7 77 717]
     opposite to     | word-specific code | OPPOSoppositeto  | [7 77 695]
     past            | word-specific code | OPPOSpast        | [7 77 801]

 

.. csv-table:: TO -  The Preposition to [8] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     to | word-specific code | TOto | [8 78 945]

 

.. csv-table:: UNDR - under/below Type Prepositions [9]
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     below      | word-specific code | UNDRbelow      | [9 79 726]
     beneath    | word-specific code | UNDRbeneath    | [9 79 727]
     down       | word-specific code | UNDRdown       | [9 79 728]
     under      | word-specific code | UNDRunder      | [9 79 732]
     underneath | word-specific code | UNDRunderneath | [9 79 733]

 

.. csv-table:: ABOVE - above Type Prepositions [10] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     above | word-specific code | ABOVEabove | [10 80 746]
     over  | word-specific code | ABOVEover  | [10 80 738]
     up    | word-specific code | ABOVEup    | [10 80 749]

 

.. csv-table:: TEMP - Temporal Type Prepositions [11] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     type                 | set code           | TEMP??                 | [11 41]
     at the beginning of  | word-specific code | TEMPatbeginningof      | [11 41 602]
     at the end of        | word-specific code | TEMPatendof            | [11 41 604]
     at the time of       | word-specific code | TEMPattimeof           | [11 41 771]
     during               | word-specific code | TEMPduring             | [11 41 773]
     during the time of   | word-specific code | TEMPduringtimeof       | [11 41 783]
     with the advent of   | word-specific code | TEMPwithadventof       | [11 41 779]
     type                 | set code           | TEMP??                 | [11 42]
     on the occasion of   | word-specific code | TEMPonoccasionof       | [11 42 775]
     preparatory to       | word-specific code | TEMPpreparatoryto      | [11 42 776]
     prior to             | word-specific code | TEMPpriorto            | [11 42 772]
     simultaneously with  | word-specific code | TEMPsimultaneouslywith | [11 42 778]
     type                 | set code           | TEMP??                 | [11 43]
     at a rate of         | word-specific code | TEMPatarateof          | [11 43 766]
     at intervals of      | word-specific code | TEMPatintervalsof      | [11 43 767]
     at the rate of       | word-specific code | TEMPattherateof        | [11 43 768]
     at the speed of      | word-specific code | TEMPatspeedof          | [11 43 770]
     within the period of | word-specific code | TEMPwithinperiodof     | [11 43 780]

 

.. csv-table:: BEHD - behind Type Prepositions [12] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     abaft          | word-specific code | BEHDabaft        | [12 82 796]
     aft of         | word-specific code | BEHDaftof        | [12 82 797]
     behind         | word-specific code | BEHDbehind       | [12 82 798
     beyond         | word-specific code | BEHDbeyond       | [12 82 799]
     in back of     | word-specific code | BEHDinbackof     | [12 82 800]
     in the back of | word-specific code | BEHDintheback of | [12 82 800]

 

.. csv-table:: ARND - around Type Prepositions [13] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     about              | word-specific code | ARNDabout        | [13 83 591]
     all the way around | word-specific code | ARNDallwayaround | [13 83 594]
     around             | word-specific code | ARNDaround       | [13 83 598]

 

.. csv-table:: OUTSD - outside Type Prepositions [14] 
   :header: "Preposition", "Code Type", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

     on the outside of | word-specific code | OUTSDonoutsideof | [14 84 694]
     out               | word-specific code | OUTSDout         | [14 84 697]
     outside           | word-specific code | OUTSDoutside     | [14 84 699]

 

.. csv-table:: Alphabetic Listing - All Prepositions   
   :header: "Preposition", "Mnemonic", "WC", "Superset Membership", "Superset, Set, and Subset"
   :delim: |
   :widths: auto

    abaft                          | BEHDabaft              | PRP [13]  | behind type                 | [12 82 796]
    abeam                          | ATabeam                | PRP [13]  | at/near type                | [5 75 590]
    aboard                         | ONaboard               | PRP [13]  | on type                     | [2 72 537]
    about                          | ARNDabout              | PRP [13]  | around type                 | [13 83 591]
    above                          | ABOVEabove             | PRP [13]  | above type                  | [10 80 746]
    abreast of                     | OPPOSabreast of        | PRP [13]  | opposite type               | [7 77 671]
    according to                   | REFaccording to        | PRPN [11] | reference type              | [7 26 261
    across                         | OPPOSacross            | PRP [13]  | opposite type               | [7 77 747]
    across from                    | OPPOSacross from       | PRP [13]  | opposite type               | [7 77 672]
    aft of                         | BEHDaftof              | PRP [13]  | behind type                 | [12 82 797]
    against                        | ATagainst              | PRP [13]  | at/near type                | [5 75 593]
    ahead of                       | OPPOSaheadof           | PRP [13]  | in front of type            | [7 77 716]
    along                          | ATalong                | PRP [13]  | at/near type                | [5 75 595]
    along with                     | ASSOCalong with        | PRPN [11] | associative type            | [5 55 156]
    alongside                      | ATalongside            | PRP [13]  | at/near type                | [5 75 596]
    alongside of                   | ATalongsideof          | PRP [13]  | at/near type                | [5 75 597]
    all the way around             | ARNDallwayaround       | PRP [13]  | around type                 | [13 83 594]
    all the way to                 | TWRDallwayto           | PRP [13]  | toward type                 | [4 74 562]
    amid                           | INamid                 | PRP [13]  | in/among type               | [1 71 475]
    amidst                         | INamidst               | PRP [13]  | in/among type               | [1 71 476]
    among                          | INamong                | PRP [13]  | in/among type               | [1 71 477]
    amongst                        | INamongst              | PRP [13]  | in/among type               | [1 71 478]
    apart from                     | INCLapart from         | PRPN [11] | inclusion/exclusion type    | [11 31 431]
    around                         | ARNDaround             | PRP [13]  | around type                 | [13 83 598]
    as a basis for                 | REFasbasisfor          | PRPN [11] | reference type              | [7 26 262]
    as a favor to                  | BENEasafavor to        | PRPN [11] | benefactive type            | [3 53 105]
    as a result of                 | CAUSasaresult of       | PRPN [11] | causes/conditions type      | [9 28 351]
    as a substitute for            | ALOGasasubfor          | PRPN [11] | analogical type             | [6 24 188]
    as compared to                 | ALOGascomparedto       | PRPN [11  | analogical type             | [6 24 189]
    as compared with               | ALOGascomparedwith     | PRPN [11  | analogical type             | [6 24 190]
    as concerns                    | REFasconcerns          | PRPN [11] | reference type              | [7 26 263]
    as contrasted to               | ALOGascontrastedto     | PRPN [11] | analogical type             | [6 25 246]
    as per                         | REFasper               | PRPN [11] | reference type              | [7 26 265]
    as regards                     | REFasregards           | PRPN [11] | reference type              | [7 26 266]
    as related to                  | ALOGasrelatedto        | PRPN [11] | analogical type             | [6 24 193]
    aside from                     | INCLasidefrom          | PRPN [11] | inclusion/exclusion type    | [11 31 432]
    at                             | ATat                   | PRP [13]  | at/near type                | [5 75 599]
    at a distance of               | THRUatdistanceof       | PRP [13]  | through type                | [3 73 674]
    at a rate of                   | TEMPatarateof          | PRP [13]  | temporal type               | [11 43 766]
    at intervals of                | TEMPatintervalsof      | PRP [13]  | temporal type               | [11 43 767]
    at the back of                 | ATatbackof             | PRP [13]  | at/near type                | [5 75 601]
    at the beginning of            | TEMPatbeginningof      | PRP [13]  | temporal type               | [11 41 602]
    at the bottom of               | ATatbottomof           | PRP [13]  | at/near type                | [5 75 603]
    at the end of                  | TEMPatendof            | PRP [13]  | temporal type               | [11 41 604]
    at the expense of              | CAUSatexpenseof        | PRPN [11] | causes/conditions type      | [9 29 396]
    at the front of                | OPPOSatfrontof         | PRP [13]  | opposite type               | [7 77 605]
    at the left of                 | ATatleftof             | PRP [13]  | at/near type                | [5 75 606]
    at the left side of            | ATatleftsideof         | PRP [13]  | at/near type                | [5 75 607]
    at the rate of                 | TEMPattherateof        | PRP [13]  | temporal type               | [11 43 768]
    at the rear of                 | ATatrearof             | PRP [13]  | at/near type                | [5 75 608]
    at the request of              | CAUSattherequestof     | PRPN [11] | causes/conditions type      | [9 28 352]
    at the right of                | ATatrightof            | PRP [13]  | at/near type                | [5 75 609]
    at the right side of           | ATatrightsideof        | PRP [13]  | at/near type                | [5 75 610]
    at the side of                 | ATatsideof             | PRP [13]  | at/near type                | [5 75 611]
    at the speed of                | TEMPatspeedof          | PRP [13]  | temporal type               | [11 43 770]
    at the time of                 | TEMPattimeof           | PRP [13]  | temporal type               | [11 41 771]
    at the top of                  | ATattopof              | PRP [13]  | at/near type                | [5 75 612]
    at the very top of             | ATatverytopof          | PRP [13]  | at/near type                | [5 75 613]
    because of                     | CAUSbecause of         | PRPN [11] | causes/conditions type      | [9 28 353]
    behind                         | BEHDbehind             | PRP [13]  | behind type                 | [12 82 798]
    below                          | UNDRbelow              | PRP [13]  | under/below type            | [9 79 726]
    beneath                        | UNDRbeneath            | PRP [13]  | under/below type            | [9 79 727]
    beside                         | ATbeside               | PRP [13]  | at/near type                | [5 75 616]
    between                        | INbetween              | PRP [13]  | in/among type               | [1 71 480]
    beyond                         | BEHDbeyond             | PRP [13]  | behind type                 | [12 82 799]
    by                             | INSTby                 | PRPN [11] | instrumental type           | [4 54 132]
    by a combination of            | INSTbycombof           | PRPN [11] | instrumental type           | [4 54 133]
    by action of                   | CAUSbyactionof         | PRPN [11] | causes/conditions type      | [9 28 354]
    by arrangement with            | INSTbyarrangwith       | PRPN [11] | instrumental type           | [4 54 134]
    by means of                    | INSTbymeansof          | PRPN [11] | instrumental type           | [4 54 135]
    by means other than            | INSTbymeansotherthan   | PRPN [11] | instrumental type           | [4 54 136]
    by reason of                   | CAUSbyreasonof         | PRPN [11] | causes/conditions type      | [9 28 355]
    by type of                     | INSTbytypeof           | PRPN [11] | instrumental type           | [4 54 137]
    by virtue of                   | CAUSbyvirtueof         | PRPN [11] | causes/conditions type      | [9 28 356]
    by way of                      | INSTbywayof            | PRPN [11] | instrumental type           | [4 54 138]
    corresponding to               | ALOGcorrespondingto    | PRPN [11] | analogical type             | [6 24 199]
    despite                        | CAUSdespite            | PRPN [11] | causes/conditions type      | [9 29 397]
    devoid of                      | INCLdevoidof           | PRPN [11] | inclusion/exclusion type    | [11 31 434]
    down                           | UNDRdown               | PRP [13]  | under/below type            | [9 79 728]
    during                         | TEMPduring             | PRP [13]  | temporal type               | [11 41 773]
    during the time of             | TEMPduringtimeof       | PRP [13]  | temporal type               | [11 41 783]
    except for                     | INCLexceptfor          | PRPN [11] | inclusion/exclusion type    | [11 31 435]
    exclusive of                   | INCLexclusiveof        | PRPN [11] | inclusion/exclusion type    | [11 31 436]
    for                            | BENEfor                | PRPN [11] | benefactive type            | [3 53 106]
    for ease of                    | BENEforeaseof          | PRPN [11] | benefactive type            | [3 53 110]
    for lack of                    | CAUSforlackof          | PRPN [11] | causes/conditions type      | [9 29 398]
    for purposes of                | BENEforpurposesof      | PRPN [11] | benefactive type            | [3 53 111]
    for reasons of                 | ALOGforreasonsof       | PRPN [11] | analogical type             | [6 24 192]
    for the benefit of             | BENEforthebenefitof    | PRPN [11] | benefactive type            | [3 53 53]
    for the differentiation of     | ALOGforthediffof       | PRPN [11] | analogical type             | [6 25 247]
    for the pupose of [v'g]        | PREVforpurposeof       | PRPN [11] | pre-verbal prep phrase type | [12 62 359]
    for the sake of                | CAUSforsakeof          | PRPN [11] | causes/conditions type      | [9 28 375]
    for use by                     | BENEforuseby           | PRPN [11] | benefactive type            | [3 53 113]
    from                           | FROMfrom               | PRP [13]  | from/off/out type           | [6 76 679]
    from inside                    | FROMfrominside         | PRP [13]  | from/off/out type           | [6 76 673]
    from inside of                 | FROMfrominsideof       | PRP [13]  | from/off/out type           | [6 76 677]
    from outside                   | FROMfromoutside        | PRP [13]  | from/off/out type           | [6 76 678]
    from outside of                | FROMfromoutsideof      | PRP [13]  | from/off/out type           | [6 76 691]
    from the viewpoint of          | REFfromviewptof        | PRPN [11] | reference type              | [7 26 268]
    from within                    | FROMfromwithin         | PRP [13]  | from/off/out type           | [6 76 696]
    further away from              | FROMfurtherawayfrom    | PRP [13]  | from/off/out type           | [6 76 689]
    in                             | INin                   | PRP [13]  | in/among type               | [1 71 481]
    in accord with                 | ALOGinaccordwith       | PRPN [11] | analogical type             | [6 24]
    in accordance with             | ALOGinaccordancewith   | PRPN [11] | analogical type             | [6 24 204]
    in addition to                 | INCLinadditionto       | PRPN [11] | inclusion/exclusion type    | [11 30 417]
    in advance of                  | OPPOSinadvanceof       | PRP [13]  | opposite type               | [7 77 716]
    in agreement with              | ALOGinagreementwith    | PRPN [11] | analogical type             | [6 24 205]
    in and out of                  | INinandoutof           | PRP [13]  | in/among type               | [1 71 482]
    in anticipation of             | ASSOCinanticipationof  | PRPN [11] | associative type            | [5 55]
    in back of                     | BEHDinbackof           | PRP [13]  | behind type                 | [12 82 800]
    in behalf of                   | CAUSinbehalfof         | PRPN [11] | causes/conditions type      | [9 28 372]
    in between                     | INinbetween            | PRP [13]  | in/among type               | [1 71 483]
    in case of                     | CAUSincaseof           | PRPN [11] | causes/conditions type      | [9 28 360]
    in charge of                   | REFinchargeof          | PRPN [11] | reference type              | [7 26 269]
    in collaboration with          | REFincollaborationwith | PRPN [11] | reference type              | [7 26 270]
    in combination with            | ASSOCincombwith        | PRPN [11] | associative type            | [5 55 163]
    in comparison to               | REFincompto            | PRPN [11] | reference type              | [7 26 271]
    in comparison with             | REFincompwith          | PRPN [11] | reference type              | [7 26 272]
    in compliance with             | REFincompliancewith    | PRPN [11] | reference type              | [7 26 272]
    in congruence with             | ALOGincongruencewith   | PRPN [11] | analogical type             | [6 24 206]
    in conjunction with            | REFinconjwith          | PRPN [11] | reference type              | [7 26 274]
    in connection with             | REFinconnecwith        | PRPN [11] | reference type              | [7 26 275]
    in consequence of              | CAUSinconsequenceof    | PRPN [11] | causes/conditions type      | [9 28 362]
    in contact with                | ALOGincontactwith      | PRPN [11] | analogical type             | [6 24 226]
    in coordination with           | REFincoordwith         | PRPN [11] | reference type              | [7 26 277]
    in favor of                    | CAUSinfavorof          | PRPN [11] | causes/conditions type      | [9 28 402]
    in front of                    | OPPOSinfrontof         | PRP [13]  | opposite type               | [7 77 719]
    in lieu of                     | INCLinlieuof           | PRPN [11] | inclusion/exclusion type    | [11 31 437]
    in line with                   | ATinlinewith           | PRP [13]  | at/near type                | [5 75 536]
    in opposition to               | REFinoppositionto      | PRPN [11] | reference type              | [7 27 338]
    in parallel with               | ATinparallelwith       | PRP [13]  | at/near type                | [5 75 621]
    in place of                    | INCLinplaceof          | PRPN [11] | inclusion/exclusion type    | [11 31 438]
    in proportion to               | REFinproportionto      | PRPN [11] | reference type              | [7 26 278]
    in regard to                   | REFinregardto          | PRPN [11] | reference type              | [7 26 279]
    in relation to                 | REFinrelationto        | PRPN [11] | reference type              | [7 26 280]
    in response to                 | REFinresponseto        | PRPN [11] | reference type              | [7 26 301]
    in spite of                    | CAUSinspiteof          | PRPN [11] | causes/conditions type      | [9 29 399]
    in support of                  | CAUSinsupportof        | PRPN [11] | causes/conditions type      | [9 28 363]
    in sync with                   | ALOGinsyncwith         | PRPN [11] | analogical type             | [6 24 229]
    in terms of                    | REFintermsof           | PRPN [11] | reference type              | [7 26 302]
    in the absence of              | CAUSinabsenceof        | PRPN [11] | causes/conditions type      | [9 29 400]
    in the back of                 | BEHDinthebackof        | PRP [13]  | behind type                 | [12 82 800]
    in the case of                 | REFinthecaseof         | PRPN [11] | reference type              | [7 26 303]
    in the course of               | REFincourseof          | PRPN [11] | reference type              | [7 26 304]
    in the direction of            | TWRDindirectionof      | PRP [13]  | toward type                 | [4 74 565]
    in the event of                | CAUSineventof          | PRPN [11] | causes/conditions type      | [9 28 364]
    in the face of                 | REFinfaceof            | PRPN [11] | reference type              | [7 26 305]
    in the form of                 | REFintheformof         | PRPN [11] | reference type              | [7 26 306]
    in the interest of             | CAUSininterestof       | PRPN [11] | causes/conditions type      | [9 28 365]
    in the judgement of            | REFinjudgmentof        | PRPN [11] | reference type              | [7 26 307]
    in the light of                | REFinthelightof        | PRPN [11] | reference type              | [7 26 308]
    in the matter of               | REFinthematterof       | PRPN [11] | reference type              | [7 26 323]
    in the middle of               | INinmiddleof           | PRP [13]  | in/among type               | 1 71 484]
    in the midst of                | INinmidstof            | PRP [13]  | in/among type               | [1 71 485]
    in the place of                | INCLintheplaceof       | PRPN [11] | inclusion/exclusion type    | [11 31 440]
    in view of                     | REFinviewof            | PRPN [11] | reference type              | [7 26 309]
    inclusive of                   | INCLinclusiveof        | PRPN [11] | inclusion/exclusion type    | [11 30 421]
    independently of               | CAUSindependentlyof    | PRPN [11] | causes/conditions type      | [9 29 401]
    inside                         | INinside               | PRP [13]  | in/among type               | [1 71 486]
    instead of                     | INCLinsteadof          | PRPN [11] | inclusion/exclusion type    | [11 31 441]
    into                           | INinto                 | PRP [13]  | in/among type               | [1 71 487]
    of                             | POSSof                 | PRPN [11] | word-specific code for "of" | [1 51 101]
    of concern to                  | REFofconcernto         | PRPN [11] | reference type              | [7 26 310]
    off                            | FROMoff                | PRP [13]  | from/off/out type           | [6 76 690]
    off of                         | FROMoffof              | PRP [13]  | from/off/out type           | [6 76 675]
    off to the side of             | FROMofftosideof        | PRP [13]  | from/off/out type           | [6 76 692]
    on                             | ONon                   | PRP [13]  | on type                     | [2 72 522]
    on account of                  | CAUSonaccountof        | PRPN [11] | causes/conditions type      | [9 28 366]
    on behalf of                   | CAUSonbehalfof         | PRPN [11] | causes/conditions type      | [9 28 367]
    on the advice of               | CAUSonadviceof         | PRPN [11] | causes/conditions type      | [9 28]
    on the basis of                | CAUSonbasisof          | PRPN [11] | causes/conditions type      | [9 28 368]
    on the far side of             | ONonfarsideof          | PRP [13]  | on type                     | [2 72 693]
    on the inside of               | INontheinsideof        | PRP [13]  | in/among type               | [1 71 488]
    on the left hand side of       | ATonlefthandsideof     | PRP [13]  | at/near type                | [5 75 627]
    on the matter of               | REFonmatterof          | PRPN [11] | reference type              | [7 26 323]
    on the occasion of             | TEMPonoccasionof       | PRP [13]  | temporal type               | [11 42 775]
    on the other side of           | ATonothersideof        | PRP [13]  | at/near type                | [5 75 628]
    on the outside of              | OUTSDonoutsideof       | PRP [13]  | outside type                | [14 84 694]
    on the part of                 | CAUSonpartof           | PRPN [11] | causes/conditions type      | [9 28 374]
    on the side of                 | ATonsideof             | PRP [13]  | at/near type                | [5 75 629]
    on the strength of             | CAUSonstrengthof       | PRPN [11] | causes/conditions type      | [9 28 369]
    on the verge of                | CAUSonvergeof          | PRPN [11] | causes/conditions type      | [9 28 349]
    on this side of                | ATonthissideof         | PRP [13]  | at/near type                | [5 75 630]
    on top of                      | ONontopof              | PRP [13]  | on type                     | [2 72 523]
    onto                           | ONonto                 | PRP [13]  | on type                     | [2 72 524]
    opposite                       | OPPOSopposite          | PRP [13]  | opposite type               | [7 77 717]
    opposite to                    | OPPOSoppositeto        | PRP [13]  | opposite type               | [7 77 695]
    other than                     | INCLotherthan          | PRPN [11] | inclusion/exclusion type    | [11 31 442]
    out                            | OUTSDout               | PRP [13]  | outside type                | [14 84 697]
    out of                         | FROMoutof              | PRP [13]  | from/off/out type           | [6 76 676]
    out of reach of                | FROMoutofreachof       | PRP [13]  | from/off/out type           | [6 76 698]
    out of regard for              | REFoutofregardfor      | PRPN [11] | reference type              | [7 26 312]
    outside                        | OUTSDoutside           | PRP [13]  | outside type                | [14 84 699]
    over                           | ABOVEover              | PRP [13]  | above type                  | [10 80 738]
    owing to                       | CAUSowingto            | PRPN [11] | causes/conditions type      | [9 28 370]
    past                           | OPPOSpast              | PRP [13]  | opposite type               | [7 77 801]
    pending                        | CAUSpending            | PRPN [11] | causes/conditions type      | [9 28 371]
    per                            | REFper                 | PRPN [11] | reference type              | [7 26 311]
    plus/minus                     | INCLplus/minus         | PRPN [11] | inclusion/exclusion type    | [11 30 426]
    preparatory to                 | TEMPpreparatoryto      | PRP [13]  | temporal type               | [11 42 776]
    prior to                       | TEMPpriorto            | PRP [13]  | temporal type               | [11 42 772]
    proportional to                | ALOGproportionalto     | PRPN [11] | analogical type             | [6 24 232]
    pursuant to                    | REFpursuantto          | PRPN [11] | reference type              | [7 26 320]
    regardless of                  | REFregardlessof        | PRPN [11] | reference type              | [7 27 339]
    through                        | THRUthrough            | PRP [13]  | through type                | [3 73 703]
    throughout                     | INthroughout           | PRP [13]  | in/among type               | [1 71 491]
    thru                           | THRUthru               | PRP [13]  | through type                | [3 73 703]
    to                             | TOto                   | PRP [13]  | specific code for "to"      | [8 78 945]
    to a minimum of                | TWRDtominimumof        | PRP [13]  | toward type                 | [4 74 567]
    to a maximum of                | TWRDtomaximumof        | PRP [13]  | toward type                 | [4 74 568]
    to the advantage of            | CAUStoadvantageof      | PRPN [11] | causes/conditions type      | [9 28 373]
    to the debit of                | CAUStodebitof          | PRPN [11] | causes/conditions type      | [9 29 405]
    to the disadvantage of         | CAUStodisadvantageof   | PRPN [11] | causes/conditions type      | [9 29 406]
    to the east of                 | ATtoeastof             | PRP [13]  | at/near type                | [5 75 633]
    to the left of                 | ATtoleftof             | PRP [13]  | at/near type                | [5 75 634]
    to the left or right of        | ATtoleftorrightof      | PRP [13]  | at/near type                | [5 75 638]
    to the left or to the right of | ATtoleftortorightof    | PRP [13]  | at/near type                | [5 75 638]
    to the north of                | ATtonorthof            | PRP [13]  | at/near type                | [5 75 635]
    to the rear of                 | TWRDtorearof           | PRP [13]  | toward type                 | [4 74 572]
    to the right of                | ATtorightof            | PRP [13]  | at/near type                | [5 75 637]
    to the right or left of        | ATtorightorleftof      | PRP [13]  | at/near type                | [5 75 636]
    to the south of                | ATtosouthof            | PRP [13]  | at/near type                | [5 75 639]
    to the west of                 | ATtowestof             | PRP [13]  | at/near type                | [5 75 640]
    together with                  | ASSOCtogetherwith      | PRPN [11] | associative type            | [5 55 158]
    toward                         | TWRDtoward             | PRP [13]  | toward type                 | [4 74 574]
    toward the rear of             | TWRDtowardrearof       | PRP [13]  | toward type                 | [4 74 576]
    towards                        | TWRDtowards            | PRP [13]  | toward type                 | [4 74 574]
    unlike                         | ALOGunlike             | PRPN [11] | analogical type             | [6 25 252]
    under                          | UNDRunder              | PRP [13]  | under/below type            | [9 79 732]
    under contract to              | INSTundercontractto    | PRPN [11] | instrumental type           | [4 54 143]
    under the aegis of             | REFunderaegisof        | PRPN [11] | reference type              | [7 26]
    under the auspices of          | REFunderauspicesof     | PRPN [11] | reference type              | [7 26]
    underneath                     | UNDRunderneath         | PRP [13]  | under/below type            | [9 79 733]
    up                             | ABOVEup                | PRP [13]  | above type                  | [10 80 749]
    upon                           | ONupon                 | PRP [13]  | on type                     | [2 72 525]
    versus                         | ALOGversus             | PRPN [11] | analogical type             | [6 25 253]
    via                            | INSTvia                | PRPN [11] | instrumental type           | [4 54 141]
    vis a vis                      | REFvisavis             | PRPN [11] | reference type              | [7 26 207]
    vs.                            | ALOGvs.                | PRPN [11] | analogical type             | [6 25 253]
    with                           | ASSOCwith              | PRPN [11] | associative type            | [5 55 159]
    with a view to [v'g]           | PREVwithaviewto        | PRPN [11] | pre-verbal prep phrase type | [12 62 443]
    with and without               | ASSOCwithandwithout    | PRPN [11] | associative type            | [5 55 160]
    with or without                | ASSOCwithorwithout     | PRPN [11] | associative type            | [5 55 161]
    with regard to                 | REFwithregardto        | PRPN [11] | reference type              | [7 26 314]
    with respect to                | REFwithrespectto       | PRPN [11] | reference type              | [7 26 315]
    with the aid of                | INSTwithaidof          | PRPN [11] | instrumental type           | [4 54 142]
    with the exception of          | INCLwithexceptionof    | PRPN [11] | inclusion/exclusion type    | [11 31 445]
    with the goal of               | REFwithgoalof          | PRPN [11] | reference type              | [7 26 316]
    within                         | INwithin               | PRP [13]  | in/among type               | [1 71 493]
    within reach of                | ATwithinreachof        | PRP [13]  | at/near type                | [5 75 642]
    within the period of           | TEMPwithinperiodof     | PRP [13]  | temporal type               | [11 43 780]
    without                        | INCLwithout            | PRPN [11] | inclusion/exclusion type    | [11 31 446]
    without reference to           | REFwithoutrefto        | PRPN [11] | reference type              | [7 27 340]
    without regard to              | REFwithoutregardto     | PRPN [11] | reference type              | [7 27 341]
    without respect to             | REFwithoutrespecto     | PRPN [11] | reference type              | [7 27 342]
    with/without                   | ASSOCwith/without      | PRPN [11] | associative type            | [5 55 162]

 

 


 
NEG - Negatives  [17]  
-----------------------------------------------------------------------------

.. csv-table:: Descriptive Adjective Sets 
   :header: "Negative", "Mnemonic", "Numerics"
   :delim: |
   :widths: auto

    not     | not    | [1 1 460]
    not yet | notyet | [1 1 461]

 

 
PRO  -  Pronouns   [5]
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Class of Pronoun", "Description", "Mnemonic", "Set"
   :delim: |
   :widths: auto

    Personal   | (First Person)             | PERfirst     | Set 21
    Personal   | (Second Person)            | PERsecond    | Set 22
    Personal   | (Third Person: (Masculine) | PERmasc      | Set 23
    Personal   | (Third Person: (Feminine)  | PERfem       | Set 26
    Personal   | (Third Person: (Neuter)    | PERneut      | Set 27
    Reflexive  | myself, etc.               | REFL         | Set 24
    Reflexive  | one's, etc.                | REFLone-type | Set 25
    Possessive | hers, etc.                 | POSS         | Set 50
    Possessive | her own, etc.              | POSSown-type | Set 52
    Indefinite | (Singular and Plural)      | INDSP        | Set 30
    Indefinite | (Plural Only)              | INDP         | Set 40
    Indefinite | (Singular Only)            | INDS         | Set 42
    Indefinite | else/else's                | INDelse-type | Set 44

 

 

.. csv-table::  PRO - Pronouns  [5]  List by Set and Subset 
   :header: "Pronouns by Set", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    Personal (First Person)            | PERfirst       | Set 21
    I                                  | I              | [5 21 795]
    me                                 | me             | [5 21 795]
    we                                 | we             | [5 21 796]
    us                                 | us             | [5 21 796]
    Personal (Second Person)           | PERsecond      | Set 22
    you                                | you            | [5 22 797]
    Personal: Masculine (Third Person) | PERmasc        | Set 23
    he                                 | he             | [5 23 798]
    him                                | him            | [5 23 798]
    they                               | they           | [5 23 799]
    them                               | them           | [5 23 799]
    Personal: Feminine (Third Person)  | PERfem         | Set 26
    she                                | she            | [5 26 798]
    her                                | her            | [5 26 798]
    Personal: Neuter (Third Person)    | PERneut        | Set 27
    it                                 | it             | [1 27 303]
    Reflexive                          | REFL           | Set 24
    myself                             | myself         | [5 24 286]
    ourselves                          | ourselves      | [5 24 415]
    yourself                           | yourself       | [5 24 454]
    yourselves                         | yourselves     | [5 24 496]
    oneself                            | oneself        | [5 24 581]
    himself                            | himself        | [5 24 582]
    herself                            | herself        | [5 24 590]
    itself                             | itself         | [5 24 594]
    themselves                         | themsleves     | [5 24 631]
    Reflexive                          | REFLone-type   | Set 25
    one                                |                | [classified in dictionary as other POS]
    ones                               | ones           | [5 25 802]
    one's                              | one's          | [5 25 802]
    Possessive                         | POSS           | Set 50
    mine                               | mine           | [5 50 327]
    yours                              | yours          | [5 50 328]
    ours                               | ours           | [5 50 329]
    his                                | his            | [5 50 221]
    theirs                             | theirs         | [5 50 330]
    hers                               | hers           | [5 50 331]
    Possessive                         | POSSown-type   | Set 52
    own                                | own            | [5 52 395]
    her own                            | herown         | [5 52 332]
    his own                            | hisown         | [5 52 333]
    its own                            | itsown         | [5 52 334]
    my own                             | myown          | [5 52 335]
    their own                          | theirown       | [5 52 336]
    your own                           | yourown        | [5 52 337]
    Indefinite (Singular and Plural)   | INDSP          | Set 30
    all                                | all            | [1 30 140]
    any                                | any            | [1 30 115]
    enough                             | enough         | [1 30 146]
    more                               | more           | [1 30 148]
    more . . .                         | more . . .     | [1 30 202]
    most                               | most           | [1 30 149]
    no other                           | noother        | [1 30 231]
    none                               | none           | [1 30 203]
    none at all                        | noneatall      | [1 30 204]
    some                               | some           | [1 30 151]
    that                               |                | (See Relatives/Interrogatives)
    these                              | these          | [1 30 102]
    this                               | this           | [1 30 102]
    those                              | those          | [1 30 103]
    Indefinite (Plural Only)           | INDP           | Set 40
    a couple                           | acouple        | [1 40 280]
    a few                              | afew           | [1 40 245]
    all k of things                    | allkofthings   | [1 40 281]
    both                               | both           | [1 40 250]
    few                                | few            | [1 40 251]
    fewer                              | fewer          | [1 40 252]
    many                               | many           | [1 40 253]
    quite a few                        | quiteafew      | [1 40 263]
    several                            | several        | [1 40 266]
    the two of them                    | thetwoofthem   | [1 40 274]
    too many                           | toomany        | [1 40 255]
    very few                           | veryfew        | [1 40 273]
    Indefinite (Singular Only)         | INDS           | Set 42
    a little bit                       | alittlebit     | [1 42 361]
    a little more                      | alittlemore    | [1 42 347]
    another                            | another        | [1 42 317]
    anybody                            | anybody        | [1 42 378]
    anybody else                       | anybodyelse    | [1 42 501]
    anyone                             | anyone         | [1 42 362]
    anyone else                        | anyoneelse     | [1 42 502]
    anything                           | anything       | [1 42 363]
    anything else                      | anythingelse   | [1 42 503]
    each                               | each           | [1 42 319]
    each one                           | eachone        | [1 42 364]
    each other                         | eachother      | [1 42 375]
    each thing                         | eachthing      | [1 42 365]
    either                             | either         | [1 42 825]
    everybody                          | everybody      | [1 42 379]
    everybody else                     | everybodyelse  | [1 42 505]
    everyone                           | everyone       | [1 42 380]
    everyone else                      | everyoneelse   | [1 42 506]
    everything                         | everything     | [1 42 366]
    everything else                    | everythingelse | [1 42 507]
    less                               | less           | [1 42 341]
    little                             | little         | [1 42 342]
    much                               | much           | [1 42 343]
    neither                            | neither        | [1 42 821]
    no one else                        | nooneelse      | [1 42 509]
    nobody                             | nobody         | [1 42 381]
    nobody else                        | nobodyelse     | [1 42 510]
    nothing                            | nothing        | [1 42 368]
    nothing else                       | nothingelse    | [1 42 511]
    one another                        | oneanother     | [1 42 369]
    one's own                          | one'sown       | [1 42 513]
    our own                            | ourown         | [1 42 514]
    plenty                             | lenty          | [1 42 360]
    self                               | self           | [1 42 227]
    selves                             | selves         | [1 42 227]
    somebody                           | somebody       | [1 42 377]
    somebody else                      | somebodyelse   | [1 42 515]
    someone                            | someone        | [1 42 370]
    someone else                       | someoneelse    | [1 42 516]
    something                          | something      | [1 42 371]
    something else                     | somethingelse  | [1 42 517]
    such a thing                       | suchathing     | [1 42 372]
    too much                           | toomuch        | [1 42 344]
    very little                        | verylittle     | [1 42 345]
    Indefinite                         | INDelse-type   | Set 44
    else                               | else           | [1 44 396]
    else's                             | else's         | [1 44 396]
 
 

 
.. csv-table:: PRO  -  Pronouns  [5]  - Alpha List 
   :header: "Pronouns", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

    a couple        | acouple        | [1 40 280]
    a few           | afew           | [1 40 245]
    a little bit    | alittlebit     | [1 42 361]
    a little more   | alittlemore    | [1 42 347]
    all             | all            | [1 30 140]
    all k of things | allkofthings   | [1 40 281]
    another         | another        | [1 42 317]
    any             | any            | [1 30 115]
    anybody         | anybody        | [1 42 378]
    anybody else    | anybodyelse    | [1 42 501]
    anyone          | anyone         | [1 42 362]
    anyone else     | anyoneelse     | [1 42 502]
    anything        | anything       | [1 42 363]
    anything else   | anythingelse   | [1 42 503]
    both            | both           | [1 40 250]
    each            | each           | [1 42 319]
    each one        | eachone        | [1 42 364]
    each other      | eachother      | [1 42 375]
    each thing      | eachthing      | [1 42 365]
    either          | either         | [1 42 825]
    else            | else           | [1 44 396]
    else's          | else's         | [1 44 396]
    enough          | enough         | [1 30 146]
    everybody       | everybody      | [1 42 379]
    everybody else  | everybodyelse  | [1 42 505]
    everyone        | everyone       | [1 42 380]
    everyone else   | everyoneelse   | [1 42 506]
    everything      | everything     | [1 42 366]
    everything else | everythingelse | [1 42 507]
    few             | few            | [1 40 251]
    fewer           | fewer          | [1 40 252]
    he              | he             | [5 23 798]
    her             | her            | [5 26 798]
    her own         | herown         | [5 52 332]
    hers            | hers           | [5 50 331]
    herself         | herself        | [5 24 590]
    him             | him            | [5 23 798]
    himself         | himself        | [5 24 582]
    his             | his            | [5 50 221]
    his own         | hisown         | [5 52 333]
    I               | I              | [5 21 795]
    it              | it             | [5 27 303]
    its own         | itsown         | [5 52 334]
    itself          | itself         | [5 24 594]
    less            | less           | [1 42 341]
    little          | little         | [1 42 342]
    many            | many           | [1 40 253]
    me              | me             | [5 21 795]
    mine            | mine           | [5 50 327]
    more            | more           | [1 30 148]
    more . . .      | more . . .     | [1 30 202]
    most            | most           | [1 30 149]
    much            | much           | [1 42 343]
    my own          | myown          | [5 52 335]
    myself          | myself         | [5 24 286]
    neither         | neither        | [1 42 821]
    no one else     | nooneelse      | [1 42 509]
    no other        | noother        | [1 30 231]
    nobody          | nobody         | [1 42 381]
    nobody else     | nobodyelse     | [1 42 510]
    none            | none           | [1 30 203]
    none at all     | noneatall      | [1 30 204]
    nothing         | nothing        | [1 42 368]
    nothing else    | nothingelse    | [1 42 511]
    one             |                | (stored as other POS)
    ones            | ones           | [5 25 802]
    one's           | one's          | [5 25 802]
    one's own       | one'sown       | [1 42 513]
    one another     | oneanother     | [1 42 369]
    oneself         | oneself        | [5 24 581]
    our own         | ourown         | [1 42 514]
    ours            | ours           | [5 50 329]
    ourselves       | ourselves      | [5 24 415]
    own             | own            | [5 52 395]
    plenty          | lenty          | [1 42 360]
    quite a few     | quiteafew      | [1 40 263]
    self            | self           | [1 42 227]
    selves          | selves         | [1 42 227]
    several         | several        | [1 40 266]
    she             | she            | [5 26 798]
    some            | some           | [1 30 151]
    somebody        | somebody       | [1 42 377]
    somebody else   | somebodyelse   | [1 42 515]
    someone         | someone        | [1 42 370]
    someone else    | someoneelse    | [1 42 516]
    something       | something      | [1 42 371]
    something else  | somethingelse  | [1 42 517]
    such a thing    | suchathing     | [1 42 372]
    that            |                | (See Relatives/Interrogatives)
    the two of them | thetwoofthem   | [1 40 274]
    their own       | theirown       | [5 52 336]
    theirs          | theirs         | [5 50 330]
    them            | them           | [5 23 799]
    themselves      | themsleves     | [5 24 631]
    these           | these          | [1 30 102]
    they            | they           | [5 23 799]
    this            | this           | [1 30 102]
    those           | those          | [1 30 103]
    too many        | toomany        | [1 40 255]
    too much        | toomuch        | [1 42 344]
    us              | us             | [5 21 796]
    very few        | veryfew        | [1 40 273]
    very little     | verylittle     | [1 42 345]
    we              | we             | [5 21 796]
    you             | you            | [5 22 797]
    your own        | yourown        | [5 52 337]
    yours           | yours          | [5 50 328]
    yourself        | yourself       | [5 24 454]
    yourselves      | yourselves     | [5 24 496]
    

CONJ  -   Conjunction [WC 19]
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Superset", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    Conjoining    | JOIN | 01
    Disjunctive   | DISJ | 02
    Cordinating   | COOR | 03
    Subordinating | SUB  | 04


.. csv-table:: CONJ  -   Conjunction  - Alphabetic Listing of all Conjunctions
   :header: "Conjunction", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

     accordingly                | COORaccordingly           | [3 36 870]
     after                      | SUBafter                  | [4 04 911]
     also                       | COORalso                  | [3 36 871]
     although                   | SUBalthough               | [4 04 913]
     and                        | JOINand                   | [1 20 820]
     and/or                     | JOINand/or                | [1 20 823]
     anytime                    | SUBanytime                | [4 04 914]
     as                         | SUBas                     | [4 04 915]
     as a result                | COORasaresult             | [3 36 901]
     as far as                  | SUBasfaras                | [4 04 916]
     as follows                 | COORasfollows             | [3 37 906]
     as if                      | SUBasif                   | [4 04 917]
     as it were                 | COORasitwere              | [3 36 872]
     as long as                 | SUBaslongas               | [4 04 918]
     as many times as           | SUBasmanytimesas          | [4 04 983]
     as often as                | SUBasoftenas              | [4 04 919]
     as soon as                 | SUBassoonas               | [4 04 920]
     as though                  | SUBasthough               | [4 04 921]
     as to whether              | SUBastowhether            | [4 04 977]
     as well                    | COORaswell                | [3 36 910]
     as well as                 | JOINaswellas              | [1 20 824]
     aside from the fact that   | SUBasidefromthefactthat   | [4 04 923]
     at a point where           | SUBatapointwhere          | [4 04 972]
     at a time when             | SUBatatimewhen            | [4 04 925]
     at least, at most, at best | COORatleastatmostatbest   | [3 36 897]
     at the same time           | COORatthesametime         | [3 36 902]
     at the time that           | SUBatthetimethat          | [4 04 924]
     at times when              | SUBattimeswhen            | [4 04 925]
     because                    | SUBbecause                | [4 04 927]
     before                     | SUBbefore                 | [4 04 928]
     before then                | COORbeforethen            | [3 36 750]
     besides                    | COORbesides               | [3 37 416]
     both                       | JOINboth                  | [1 21 250]
     but                        | DISJbut                   | [2 33 854]
     but rather                 | DISJbutrather             | [2 33 845]
     by the time                | SUBbythetime              | [4 04 930]
     consequently               | COORconsequently          | [3 36 896]
     cont., cont'd, cont        | COORcont                  | [3 37 922]
     depending on whether       | SUBdependingonwhether     | [4 04 931]
     e.g.                       | COOReg                    | [3 38 873]
     either                     | JOINeither                | [1 21 825]
     even if                    | SUBevenif                 | [4 04 934]
     even so                    | SUBevenso                 | [4 04 963]
     even though                | SUBeventhough             | [4 04 935]
     even when                  | SUBevenwhen               | [4 04 938]
     ever since                 | SUBeversince              | [4 04 937]
     except                     | DISJexcept                | [2 33 846]
     except that                | SUBexceptthat             | [4 04 939]
     except when                | SUBexceptwhen             | [4 04 940]
     finally                    | COORfinally               | [3 36 985]
     for example                | COORforexample            | [3 38 873]
     for instance               | COORforinstance           | [3 38 873]
     for the most part          | COORforthemostpart        | [3 36 981]
     further                    | COORfurther               | [3 36 907]
     furthermore                | COORfurthermore           | [3 36 874]
     hence                      | COORhence                 | [3 36 875]
     hereafter                  | COORhereafter             | [3 36 864]
     however                    | COORhowever               | [3 36 876]
     i.e.                       | COORi.e.                  | [3 37 912]
     if                         | SUBif                     | [4 04 942]
     in addition                | COORinaddition            | [3 36 878]
     in any case                | COORinanycase             | [3 36 879]
     in as far as               | SUBinasfaras              | [4 04 960]
     in case                    | SUBincase                 | [4 04 975]
     in contrast                | DISJincontrast            | [2 33 847]
     in each case               | COORineachcase            | [3 36 904]
     in either case             | COORineithercase          | [3 36 880]
     in no case                 | COORinnocase              | [3 36 880]
     in no event                | COORinnoevent             | [3 36 881]
     in order that              | SUBinorderthat            | [4 04 946]
     in spite of the fact that  | SUBinspiteofthefactthat   | [4 04 929]
     in such a case             | COORinsuchacase           | [3 36 894]
     in such a way that         | SUBinsuchawaythat         | [4 04 947]
     in that case               | COORinthatcase            | [3 36 903]
     in that event              | COORinthatevent           | [3 36 903]
     in the event that          | SUBintheeventthat         | [4 04 949]
     in this case               | COORinthiscase            | [3 36 882]
     in this respect            | COORinthisrespect         | [3 36 202]
     in which case              | SUBinwhichcase            | [4 04 905]
     indeed                     | COORindeed                | [3 36 987]
     insofar as                 | SUBinsofaras              | [4 04 950]
     instead                    | DISJinstead               | [2 32 855]
     just as                    | SUBjustas                 | [4 04 951]
     lastly                     | COORlastly                | [3 36 755]
     like                       | COORlike                  | [3 38 231]
     long after                 | SUBlongafter              | [4 04 973]
     long before                | SUBlongbefore             | [4 04 979]
     meanwhile                  | COORmeanwhile             | [3 36 984]
     minus                      | JOINminus                 | [1 22 826]
     moreover                   | COORmoreover              | [3 36 883]
     namely                     | COORnamely                | [3 37 898]
     needless to say            | COORneedlesstosay         | [3 36 114]
     neither                    | JOINneither               | [1 21 821]
     nevertheless               | COORnevertheless          | [3 36 900]
     next                       | COORnext                  | [3 36 908]
     no                         | COORno                    | [3 37 895]
     no longer                  | COORnolonger              | [3 36 308]
     no matter                  | COORnomatter              | [3 37 869]
     nonetheless                | COORnonetheless           | [3 36 900]
     nor                        | JOINnor                   | [1 20 827]
     notwithstanding            | COORnotwithstanding       | [3 37 404]
     of course                  | COORofcourse              | [3 36 115]
     of such a degree that      | SUBofsuchadegreethat      | [4 04 953]
     on condition that          | SUBonconditionthat        | [4 04 954]
     on the assumption that     | SUBontheassumptionthat    | [4 04 955]
     on the condition that      | SUBontheconditionthat     | [4 04 954]
     on the contrary            | COORonthecontrary         | [3 36 895]
     on the other hand          | DISJontheotherhand        | [2 32 848]
     or                         | JOINor                    | [1 20 828]
     or else                    | DISJorelse                | [2 33 822]
     otherwise                  | DISJotherwise             | [2 32 849]
     plus                       | JOINplus                  | [1 22 829]
     rather                     | DISJrather                | [2 32 853]
     shortly after              | SUBshortlyafter           | [4 04 974]
     shortly before             | SUBshortlybefore          | [4 04 957]
     since                      | SUBsince                  | [4 04 959]
     so as to                   | SUBsoasto                 | [4 04 961]
     so long as                 | SUBsolongas               | [4 04 969]
     so that                    | SUBsothat                 | [4 04 962]
     still                      | COORstill                 | [3 36 956]
     such as                    | COORsuchas                | [3 38 117]
     than                       | DISJthan                  | [2 33 850]
     then                       | COORthen                  | [3 36 116]
     thereby                    | COORthereby               | [3 36 889]
     therefore                  | COORtherefore             | [3 36 890]
     therein                    | COORtherein               | [3 37 941]
     thereupon                  | COORthereupon             | [3 36 891]
     though                     | SUBthough                 | [4 04 982]
     thus                       | COORthus                  | [3 36 892]
     times                      | JOINtimes                 | [1 22 830]
     unless                     | SUBunless                 | [4 04 964]
     until                      | SUBuntil                  | [4 04 965]
     until then                 | COORuntilthen             | [3 36 751]
     up to now                  | COORuptonow               | [3 37 978]
     when                       | SUBwhen                   | [4 04 966]
     whenever                   | SUBwhenever               | [4 04 967]
     whereas                    | DISJwhereas               | [2 33 851]
     whereby                    | SUBwhereby                | [4 04 958]
     wherein                    | SUBwherein                | [4 04 943]
     wherewith                  | COORwherewith             | [3 37 952]
     whether                    | SUBwhether                | [4 04 968]
     while                      | SUBwhile                  | [4 04 970]
     with the reservation that  | SUBwiththereservationthat | [4 04 971]
     yes                        | COORyes                   | [3 37 893]
     yet                        | DISJyet                   | [2 32 852]
     &                          | JOIN&                     | [1 20 130]

 

 

.. csv-table:: [JOIN] - Conjoining Conjunctions - Sets and Subsets [1]   
   :header: "Conjoining Conjunctions", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

     and-type   | JOINandtype    | [1 20]
     and        | JOINand        | [1 20 820]
     and/or     | JOINand/or     | [1 20 823]
     as well as | JOINas well as | [1 20 824]
     nor        | JOINnor        | [1 20 827]
     or         | JOINor         | [1 20 828]
     &          | JOIN&          | [1 20 130]
     both-type  | JOINbothtype   | [1 21]
     both       | JOINboth       | [1 21 250]
     neither    | JOINneither    | [1 21 821]
     either     | JOINeither     | [1 21 825]
     minus-type | JOINminustype  | [1 22]
     minus      | JOINminus      | [1 22 826]
     plus       | JOINplus       | [1 22 829]
     times      | JOINtimes      | [1 22 830]

 

.. csv-table:: [DIS] - Disjunctive Conjunctions - Sets and Subsets [2] 
   :header: "Disjunctive Conjunction", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

     yet-type          | DISJyettype           | [2 32 ]
     instead           | DISJinstead           | [2 32 855]
     on the other hand | DISJon the other hand | [2 32 848]
     otherwise         | DISJotherwise         | [2 32 849]
     rather            | DISJrather            | [2 32 853]
     yet               | DISJyet               | [2 32 852]
     but-type          | DISJbuttype           | [2 33 ]
     but               | DISJbut               | [2 33 854]
     but rather        | DISJbut rather        | [2 33 845]
     except            | DISJexcept            | [2 33 846]
     in contrast       | DISJin contrast       | [2 33 847]
     or else           | DISJor else           | [2 33 822]
     than              | DISJthan              | [2 33 850]
     whereas           | DISJwhereas           | [2 33 851]

 

.. csv-table:: COOR - Coordinating Conjunctions  Sets and Subsets [3]  
   :header: "Coordinating Conjunction", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

     also-type                  | COORalsotype                   | [3 36]
     accordingly                | COORaccordingly                | [3 36 870]
     also                       | COORalso                       | [3 36 871]
     as a result                | COORas a result                | [3 36 901]
     as it were                 | COORas it were                 | [3 36 872]
     as well                    | COORas well                    | [3 36 910]
     at least, at most, at best | COORat least, at most, at best | [3 36 897]
     at the same time           | COORat the same time           | [3 36 902]
     before then                | COORbefore then                | [3 36 750]
     consequently               | COORconsequently               | [3 36 896]
     finally                    | COORfinally                    | [3 36 985]
     for the most part          | COORfor the most part          | [3 36 981]
     further                    | COORfurther                    | [3 36 907]
     furthermore                | COORfurthermore                | [3 36 874]
     hence                      | COORhence                      | [3 36 875]
     hereafter                  | COORhereafter                  | [3 36 864]
     however                    | COORhowever                    | [3 36 876]
     in addition                | COORin addition                | [3 36 878]
     in any case                | COORin any case                | [3 36 879]
     in each case               | COORin each case               | [3 36 904]
     in either case             | COORin either case             | [3 36 880]
     in no case                 | COORin no case                 | [3 36 880]
     in no event                | COORin no event                | [3 36 881]
     in such a case             | COORin such a case             | [3 36 894]
     in that case               | COORin that case               | [3 36 903]
     in that event              | COORin that event              | [3 36 903]
     in this case               | COORin this case               | [3 36 882]
     in this respect            | COORin this respect            | [3 36 202]
     indeed                     | COORindeed                     | [3 36 987]
     lastly                     | COORlastly                     | [3 36 755]
     meanwhile                  | COORmeanwhile                  | [3 36 984]
     moreover                   | COORmoreover                   | [3 36 883]
     needless to say            | COORneedless to say            | [3 36 114]
     nevertheless               | COORnevertheless               | [3 36 900]
     next                       | COORnext                       | [3 36 908]
     no longer                  | COORno longer                  | [3 36 308]
     nonetheless                | COORnonetheless                | [3 36 900]
     of course                  | COORof course                  | [3 36 115]
     on the contrary            | COORon the contrary            | [3 36 895]
     still                      | COORstill                      | [3 36 956]
     then                       | COORthen                       | [3 36 116]
     thereby                    | COORthereby                    | [3 36 889]
     therefore                  | COORtherefore                  | [3 36 890]
     thereupon                  | COORthereupon                  | [3 36 891]
     thus                       | COORthus                       | [3 36 892]
     until then                 | COORuntil then                 | [3 36 751]
     besides-type               | COORbesidestype                | [3 37]
     as follows                 | COORas follows                 | [3 37 906]
     besides                    | COORbesides                    | [3 37 416]
     cont., cont'd, cont        | COORcont                       | [3 37 922]
     i.e.                       | COORi.e.                       | [3 37 912]
     namely                     | COORnamely                     | [3 37 898]
     no                         | COORno                         | [3 37 895]
     no matter                  | COORno matter                  | [3 37 869]
     notwithstanding            | COORnotwithstanding            | [3 37 404]
     therein                    | COORtherein                    | [3 37 941]
     up to now                  | COORup to now                  | [3 37 978]
     wherewith                  | COORwherewith                  | [3 37 952]
     yes                        | COORyes                        | [3 37 893]
     like-type                  | COORliketype                   | [3 38]
     e.g.                       | COOReg                         | [3 38 873]
     for example                | COORfor example                | [3 38 873]
     for instance               | COORfor instance               | [3 38 873]
     like                       | COORlike                       | [3 38 231]
     such as                    | COORsuch as                    | [3 38 117]

 

.. csv-table:: SUB - Subordinating Conjunctions - Subsets [4] 
   :header: "Subordinating Conjunction", "Mnemonics", "Numerics"
   :delim: |
   :widths: auto

     after                     | SUBafter                     | [4 04 911]
     although                  | SUBalthough                  | [4 04 913]
     anytime                   | SUBanytime                   | [4 04 914]
     as                        | SUBas                        | [4 04 915]
     as far as                 | SUBas far as                 | [4 04 916]
     as if                     | SUBas if                     | [4 04 917]
     as long as                | SUBas long as                | [4 04 918]
     as many times as          | SUBas many times as          | [4 04 983]
     as often as               | SUBas often as               | [4 04 919]
     as soon as                | SUBas soon as                | [4 04 920]
     as to whether             | SUBas to whether             | [4 04 977]
     as though                 | SUBas though                 | [4 04 921]
     aside from the fact that  | SUBaside from the fact that  | [4 04 923]
     at a point where          | SUBat a point where          | [4 04 972]
     at a time when            | SUBat a time when            | [4 04 925]
     at the time that          | SUBat the time that          | [4 04 924]
     at times when             | SUBat times when             | [4 04 925]
     because                   | SUBbecause                   | [4 04 927]
     before                    | SUBbefore                    | [4 04 928]
     by the time               | SUBby the time               | [4 04 930]
     depending on whether      | SUBdepending on whether      | [4 04 931]
     even if                   | SUBeven if                   | [4 04 934]
     even so                   | SUBeven so                   | [4 04 963]
     even though               | SUBeven though               | [4 04 935]
     even when                 | SUBeven when                 | [4 04 938]
     ever since                | SUBever since                | [4 04 937]
     except that               | SUBexcept that               | [4 04 939]
     except when               | SUBexcept when               | [4 04 940]
     if                        | SUBif                        | [4 04 942]
     in which case             | SUBin which case             | [4 04 905]
     in as far as              | SUBin as far as              | [4 04 960]
     in case                   | SUBin case                   | [4 04 975]
     in order that             | SUBin order that             | [4 04 946]
     in spite of the fact that | SUBin spite of the fact that | [4 04 929]
     in such a way that        | SUBin such a way that        | [4 04 947]
     in the event that         | SUBin the event that         | [4 04 949]
     insofar as                | SUBinsofar as                | [4 04 950]
     just as                   | SUBjust as                   | [4 04 951]
     long after                | SUBlong after                | [4 04 973]
     long before               | SUBlong before               | [4 04 979]
     of such a degree that     | SUBof such a degree that     | [4 04 953]
     on condition that         | SUBon condition that         | [4 04 954]
     on the condition that     | SUBon the condition that     | [4 04 954]
     on the assumption that    | SUBon the assumption that    | [4 04 955]
     shortly after             | SUBshortly after             | [4 04 974]
     shortly before            | SUBshortly before            | [4 04 957]
     since                     | SUBsince                     | [4 04 959]
     so as to                  | SUBso as to                  | [4 04 961]
     so long as                | SUBso long as                | [4 04 969]
     so that                   | SUBso that                   | [4 04 962]
     though                    | SUBthough                    | [4 04 982]
     unless                    | SUBunless                    | [4 04 964]
     until                     | SUBuntil                     | [4 04 965]
     until then                | SUBuntil then                | [4 04 751]
     when                      | SUBwhen                      | [4 04 966]
     whenever                  | SUBwhenever                  | [4 04 967]
     whereby                   | SUBwhereby                   | [4 04 958]
     wherein                   | SUBwherein                   | [4 04 943]
     whether                   | SUBwhether                   | [4 04 968]
     while                     | SUBwhile                     | [4 04 970]
     with the reservation that | SUBwith the reservation that | [4 04 971]

 
 
PUNC - PUNCTUATION [WC 20] 
-----------------------------------------------------------------------------

.. csv-table:: 
   :header: "Type of Punctuation", "Mnemonic", "Superset"
   :delim: |
   :widths: auto

    beginning of sentence | BOS           | [1]
    comma                 | COMMA         | [2]
    colon / semi-colon    | COLON / SEMIC | [3]
    slash                 | SLASH         | [4]
    hyphen                | HYPH          | [5]
    left parens           | LPAREN        | [6]
    right parens          | RPAREN        | [7]
    end of sentence       | EOS           | [10]

\* Consult the EXCEL document named "alphanum7" maintained at the Logos Technology Center for additional punctuation codes.


.. csv-table:: PUNC - PUNCTUATION [WC 20] 
   :header: "Punctuation", "Mnemonic", "Numeric"
   :delim: |
   :widths: auto

    beginning of sentence                                                       | BOS            | [1 1 001]
    interrogative sentence                                                      | INTERG         | [1 1 909]
    sentence within list (first sentence of list and each sentence within list) | LIST           | [1 1 385]
    comma                                                                       | COMMA          | [2 2 888]
    colon                                                                       | COLON          | [3 3 887]
    semi-colon                                                                  | SEMIC          | [3 3 886]
    dash                                                                        | DASH           | [3 3 885]
    ellipsis                                                                    | ELLIP          | [3 3 885]
    slash                                                                       | SLASH          | [4 4 884]
    hyphen                                                                      | HYPH           | [5 5 005]
    left parenthesis                                                            | LPAREN         | [6 26 866]
    left angle bracket                                                          | LANGBR         | [6 26 386]
    left double quote                                                           | LDQUOTE        | [6 56 666]
    right parenthesis                                                           | RPAREN         | [7 27 877]
    right angle bracket                                                         | RANGBR         | [7 27 387]
    right double quote                                                          | RDQUOTE        | [7 57 777]
    end of sentence                                                             | EOS            | [10 10 10]  form = 01
    exclamation point                                                           | EXCLPT         | [10 10 10]  form = 08
    period                                                                      | PERIOD         | [10 10 10]  form = 01
    question mark                                                               | QUES           | [10 10 10]  form = 09
    exclamation point / rt parens                                               | EXCLPTRP       | [10 7 877]  form = 01, [10 10 10]  form = 08
    period / rt parens                                                          | PERIODRP       | [10 7 877]  form = 01, [10 10 10]  form = 01
    question mark /  rt parens                                                  | QUESRP         | [10 7 877]  form = 01, [10 10 10]  form = 08
    EOS of a broken sentence / or / EOS before list mode                        | BROK           | Set 51
    Colon occurs at break                                                       | BROKcolon      | [10 51 186]
    Semi-colon occurs at break                                                  | BROKsemi-colon | [10 51 185]
    Comma occurs at break                                                       | BROKcomma      | [10 51 188]
    Dash or space occurs at break                                               | BROKdashspace  | [10 51 189]
    Final sentence in a list / or / EOS of the end of a broken sentence         | LISTFINAL      | Set 52

                 

Special Characters
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Special Characters occur in Punctuation Word Class [PUNC] [WC 20] and in Arithmate Word Class [AR] [WC 16].   
For a complete list of Special Characters, refer to the EXCEL document named "alphanum7" maintained at the Logos Technology Center.  
This is the definive file for Arithmates, Punctuation, and Special Characters.

