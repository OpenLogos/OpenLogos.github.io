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

* REMOTE AGENTIVE SUBSET
* REMOTE MASS SUBSET
* APPOSITION-INVITING SUBSET
* UNKNOWN WORDS
* SPECIAL CHARACTERS


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

