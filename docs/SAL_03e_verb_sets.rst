SAL Verb Supersets
========================

General Explanation of the SAL Verb Code Taxonomy
--------------------------------------------------


Verbs are organized in a taxonomy of Supersets and sets. There are no subsets as the subset codes are used for verb-specific verb ID's.

Verbs have eleven Supersets.  Nine of these Supersets represent Transitive Verbs, three represent Intransitive Verbs.  

* Intransitives

    * Existential
    * Operational
    * Motional

* Weak Transitives

    * Subjective Transitives
    * Reciprocal Transitives

* Strong Transitives

    * Objective Transitives
    * Di-Transitives
    * Pre-Process
    * Simple Pre-Verbals
    * Pre-Verbal Di-Transitives
    * Pre-Clausals
    * Pre-Clausals/Verbals

Verb Superset and set codes denote the valence or argument structure common to its verb members. 

.. In the following, maroon denotes verb Superset, red denotes verb set.  

It is important to note that verbs are always encoded for their most complex argument structure. 


Intransitive Verbs  [WC02]
-----------------------------------------------------------------------------

* Existential Intransitives

    * INEXbe

      She is the valedictorian of her class.

    * INEXbecome-type

      He became a doctor at a very young age.

    * INEXgrow-type

      Their voices sounded cheerful.

    * INEXseem-type

      He seemed happy with the results.


* Operational Intransitives

    * INOPmisc

      She sings well.

    * INOPloc

      He stood in the rain.

    * INOPpcl

    * INOPprev

      They refrained from smoking.
      They conspired to defeat the candidate. 


* Motional Intransitives

    * INMOinto-type

      They walked into the room.

    * INMOin-type

      They danced in the streets.

     

 
Existential Intransitive Superset  [INEX]   [11]
-----------------------------------------------------------------------------

**Definition:**    Existential Intransitive verbs include the verb be and various be-substitute verbs that take predicate nominatives (e.g., become, remain) and predicate ajectives (e.g., grow, sound).

**Examples:**   is, appear, become, feel, grow, remain, seem

Existential Intransitives include the following sets:

    * INEXbe-type  [11 60]  (be)

        She is the valedictorian of her class.
        She was at the seashore all summer.
        
    * INEXbecome-type  [11 61]  (become, remain)

        He became a doctor at a very young age.
        He remained a Democrat all his life.
        She remained at the seashore all summer.
     
    * INEXgrow-type  [11 64]  (grow, look, sound)

        Their voices sounded cheerful.
        The day grew cooler as evening drew nigh.
         
    * INEXseem-type  [11 76]  (appear, seem)

        He seemed happy with the results.
        It seems that the operation was successful.
    

**Tips:**  Coders may experience possible confusion as to whether a pre-clausal verb  should be coded for the transitive or the intransitive. In general, pre-clausals should be coded as transitive, except for a very small class of exceptions;  e.g., appear, seem, and insist.  To be sure, verbs like agree and think should also be coded for their non-pre-clausal intransitive function;  e.g., She thought about her days at school, and She agreed with me.   In the case of a sentence like She agreed with me that . . ., it will be up to the parser to select the transitive pre-clausal rather than the intransitive.

**Developers' Tip:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

Operational Intransitive Superset  [INOP]   [12]
-----------------------------------------------------------------------------

**Definition:**    Operational Intransitive verbs denote all intransitive verbs that are not existential or verbs of motion.   This includes all those intransitive verbs that take clausal and verbal complementation (except for appear, seem which are Existential Intransitives).

**Examples:**  close, come, conspire, end, open, participate, persist, refrain, sing, sleep, snore, stand, stay

Operational Intransitives include the following sets:

    * INOPmisc  [12 29, 31, 97, 29]  

         She sings well.

    * INOPloc  [12 68] 

         He stood in the rain.

    * INOPpcl  [12 69] 

         ?

    * INOPprev  [12 72] 

         They refrained from smoking.
         They set out to break a record.
         She persisted in pursuing her goals.
         They came to realize their mistake.
         The work consisted in checking papers.
         They conspired to defeat the candidate.
         He participated in solving the problem.

    * INOPprecv  [12 73] 

         He insisted on joining them.
         They insisted that the answer was correct.

**Tips:**  Code the verb INOPloc if it strongly claims locative prepositions, e.g., He stayed at the office until midnight. 

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

Motional Intransitive Superset  [INMO]   [10]
-----------------------------------------------------------------------------


**Definition:**    Motional Intransitive verbs comprise all verbs of motion.

**Examples:**    dance, depart, fly, go, run, sail, skip, walk,

Motional Intransitives include the following sets:
    
    * INMOinto-type  [10 24]  (depart, go, walk)

         They departed for Chicago this morning.
         They walked into the room.
         They drove to the library.

    * INMOin-type  [10 68]  (dance, sail) 

          They sailed around the lake all morning. 
          They danced in the streets.

**Tips:**   Code the verb INMOinto-type if it can take kinetic-type prepositions,  e.g., into, onto, up to, etc., denoting directed motion. Otherwise, code verbs of motion INMOin-type.

**Caution:**   The verb come should not be coded here, but rather as INOPprev because it takes verbal complementation, e.g., He came to realize his mistake.

**Developers' Tips:**    Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

 
Transitive Verbs [WC02]
-----------------------------------------------------------------------------

Weak Transitives
^^^^^^^^^^^^^^^^

* Subjective Transitives

    * SUBTRregard-type

         They regard him to be a genius.

    * SUBTR (+ prep governance)
        

     
* Reciprocal Transitives

    * RECTRinclude-type

        The contract includes an escape clause.    

    * RECTR (+ prep governance)

        They **located** the pearls **in the drawer**. 
        The unit **exuded** oil **from the cracks**.  
        The heirs **fought** one another **over money**.

 

Strong Transitives
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Objective Transitives (Human Subject)

    * OBHUMundif

        The sculptor **created** a statue.

    * OBHUM   (+ prep governance)

        The boy **stole** apples **from the orchard**. 
        The dean **praised** her **for her contributions**.

 
* Objective Transitives  (Undifferentiated Subject)

    * OBJTRundif 

         The sprayer shellacked the surface.

    * OBJTR (+ prep governance)

         They **increased** the count **to** ten.
         The machine **pressed** the grommet **into** place.
         They **abbreviated** his title **to** V. P.

 
* Di-Transitives

    * DITRdispense-type (requires to) 

         They **contributed** money **to** good causes.

    * DITRgive-type (optional to)

         She **gave him** the book.

    * DITRfetch-type (optional for)

         He **bought** her a ring.

    * DITRprovide-type (optional with, to)

         They furnished us the answers.

 
* Pre-Process

    * PREPRaccomplish-type

         He effected a reduction in expenditures.

 
* Simple Pre-Verbals

    * PREVfinish-type  

         He finished cleaning up the basement.

    * PREVbegin-type 

         She began playing the piano.
         She began to play the piano.

    * PREVfail-type

         They refused to surrender.

 
* Pre-Verbal Di-Transitives

    * PREVDIpermit-type

        (1)  V N to V
        (2)  V V'ing  (only in some verbs in this set)

    * PREVDIaccustom-type

        (1)  V N to V  (limited application)

                      \- or -

        (2)  V N to V'ing

    * PREVDIaid-type

        (1)  V N to V

                      \- or -

        (2)  V N in/into V'ing

    * PREVDIdare-type

        (1)  V N to V (obligatory)
        (2)  V to V (obligatory)  
        (3)  V N V'ing (possible)
        (4)  V N PstP (possible)
        (5)  V V'ing (for love and like only)

    * PREVDIbar-type

        (1)  V N from V'ing
        (2)  V one's V'ing

    * PREVDIkeep-type

        (1)  V V'ing
        (2)  V N from V'ing
        (3)  V one's V'ing

    * PREVDIleave-type

        (1)  V N V'ing

    * PREVDIappoint-type

        (1)  V N to V
        (2)  N is V'd N/ V N N
        (3)  N is V'd as N

    * PREVDImisc-type

        (1)  V N  Prep V'ing  
        (2)  V one's V'ing  (limited application)

    * PREVDIbid-type

        (1)  V N V
        (2)  N V'd to V  (limited application)
        (3)  V V (help only)

 
* Pre-Clausal Verbs

    * PCLdoubt-type

         We doubt/calculate/etc. that

    * PCLdeclare-type  

         We declare/predict/etc. that
         We declare/predict/etc. to them that
         We declare/predict/etc. them to be . . .
         We declare/proclaim/etc. them the winner.

    * PCLinform-type
      
         We answer/grant/etc. that . . .
         We inform/assure/etc. them that . . .

    * PCLexplain-type  

         We explain/reply/etc. that . . .
         We explain/reply/etc. to them that

    * PCLstrike-type

         It strikes me that . . .
         They bet me that . . .


* Pre-Clausals/Verbals

    * PRECVagree-type 

        (1)  V to V
        (2)  V th-/wh-

    * PRECVtell-type 

        (1)  V N to V
        (2)  V N th-/wh-
        (3)  V N of N

    * PRECVask-type 

        (1)  V to V
        (2)  V N to V
        (3)  V that
        (4)  V N th-/wh-

    * PRECVwish-type 

        (1)  V to V
        (2)  V N to V
        (3)  V th-/wh-

    * PRECVenjoin-type 

        (1)  V N to V
        (2)  V th-/wh-

    * PRECVadmit-type 

        (1)  V one's V'ing
        (2)  V to V'ing
        (3)  V th-/wh-
        (4)  V to N that
        (5)  V N N
        (6)  V N as N
        (7)  V N to N

    * PRECVrecall-type 

        (1)  V one's V'ing
        (2)  V one V'ing
        (3)  V th-/wh-

    * PRECVsee-type 

        (1)  V N V'ing
        (2)  V N V
        (3)  V th-/wh-
        
    * PRECVwarn-type 

        (1)  V N to V
        (2)  V N that
        (3)  V that

    * PRECVintend-type 

        (1)  V V'ing
        (2)  V that
        (3)  V N to N and V N N
        (4)  V to V
        (5)  V N to V
        (6)  V N that N V (subjunctive)

    * PRECVplease-type 

        (1)  It V N to V
        (2)  It V N that
        (3)  N be PP that


 

Subjective Transitive Superset  [SUBTR]   [04]
-----------------------------------------------------------------------------

**Definition:**    Subjective Transitive verbs denote verbs where the object of the verb is mentally engaged.  Subjects of this verb, therefore, are typically human.  (To be sure, not all verbs that take human subjects belong here, however.) 

Subjective Transitives are considered Weak Transitives (an informal SAL grouping) because the effect of the verb tends to be on the subject rather than the object.

**Examples:**   pronounce, rate, regard, view

Subjective Transitives include the following sets:

    * SUBTRregard-type  [04 38]

         They regard him to be a genius.
         They view him as their leader.
         She is rated the head of her class.

    * SUBTR (+ prep governance)  [04 xx]

        (See Verb Prep Governance Chart.) 
        

**Tips:**  SUBTRregard-type verbs take a nominative complement (e.g., They pronounced her the winner.)  This is also true of the second set, reflecting prep governance;  i.e., the verb is also complemented by a prepositional phrase indicated by the lower case mnemonic, e.g., SUBTRin.

In the verbs of this superset, the effect of the action is on the subject.  In all sets under this Subjective Transitive Superset, the object is mentally engaged (contrast with Objective Transitives, where the effect of the action is on the object).

**Caution:**   Verbs like consider do not belong here because they also take clausal complementation, and are therefore to be coded as Pre-Clausal.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

Reciprocal Transitive Superset  [RECTR]   [13]
-----------------------------------------------------------------------------

**Definition:**   The Reciprocal Transitive Superset denotes verbs where the effect of the action tends to be on both the subject and the object especially in terms of a relationship (or lack of one) or interaction between them. Examples are fight, include, etc.

Reciprocal Transitives are considered Weak Transitives (an informal SAL grouping) because the effect of the verb tends to be on both the subject and the object rather than on the object alone, as in Objective Transitives.

**Examples:**   clasp, compose, comprise, contain, descend, discard, disgorge, exhale, exude, grab, include, locate, ooze, situate, spawn

Reciprocal Transitives include the following sets:

    * RECTRinclude-type   [13 54]

         The contract includes an escape clause.    

    * RECTR (+ prep governance codes)  [13 xx]

         They **located** the pearls **in the drawer**.  RECTRloc
         The unit **exuded** oil **from the cracks**.   RECTRfrom19
         The heirs **fought** one another **over money**. RECTRon90
         (See Verb Prep Governance Chart.)

**Tips:**   Whereas verbs like wrestle and fight (which imply reciprocal action between subject and object) belong in this superset, the verb love cannot be included here because it takes pre-verbal complementation, a verb characteristic which takes higher precedence.  In general, verbs are always coded for their most complex complementation structure.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

Objective Transitive
-----------------------------------------------------------------------------

(a) Human Subjects  [OBHUM]   [02]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

(b) Undifferentiated Subjects  (OBTR]  [07]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   A broad class of transitive verbs where the subject/agent performs an action on an object/patient.  This class of verb is divided into two supersets:   a) OBHUM where the subject/agent is typically human;  and b) OBTR where the subject/agent could be typically human or non-human.The two supersets share common sets and therefore are combined here. 

Note that many of these verbs take prepositional phrase complementation and are given set codes to reflect this. 

**Examples:**   abbreviate, create, increase, praise, press, shellac

 
* Objective Transitives (Human Subject)  [02]

    * OBHUMundif  [02 21, 92, 75, 98]

         The sculptor **created** a statue.

    * OBHUM  (+ prep governance) [02 xx]

         The boy **stole** apples **from the orchard**. 
         The dean **praised** her **for her contributions**.
         They **acquainted** him **with the situation**. 

                                                                OBJHUMwith74

         A worker **pressed** the cover **onto the barrel**.

                                                                OBJHUMinto-type

        (See Verb Prep Governance Chart.)

 
* Objective Transitives   (Undifferentiated Subject)  [07]

    * OBJTRundif [07 21, 92, 75, 98]

         The sprayer shellacked the surface.

    * OBJTR (+ prep governance)  [07 xx]

         They **increased** the count **to ten**.

                                                            OBJTRto18

         The machine **pressed** the grommet **into place**.

                                                            OBJTRin20

         They **abbreviated** his title **to V.P.**

                                                            OBJTRto35 

         The system **disconnected** the printer **from the network**.

                                                             OBJTRfrom19

         The umbrella **protected** the bathers **from the sun**.

                                                             OBJTRfrom78

         The medicine **cured** the patient **of his affliction**.

                                                             OBJTRof

         The sensor **aligned** the insert **with the hole**.

                                                             OBJTRwith59

         The crane **swung** the crate **onto the truck**.

                                                             OBJTRinto-type

         The printer **printed** his signature **on the checks**.

                                                             OBJTRin-type

         The bee **stung** him **on his neck**.   OBJTRin-type

        (See Verb Prep Governance Chart.)

**Developers' Tips:**  Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.  The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.   SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 
Di-Transitive Superset  [DITR]   [09]
-----------------------------------------------------------------------------

**Definition:**   The Di-Transitive Superset denotes verbs that take both direct and indirect objects.   These verbs are distributed over sets according to their argument structure.   

**Examples:**   allocate, allot, contribute, dispatch, fetch, furnish, give, introduce, issue, offer, pass, procure, provide, send, supply

* Di-Transitives include the following sets:

    * DITRdispense-type (requires to)  [09 32]

         They **contributed** money **to** good causes.

    * DITRgive-type (optional to)   [09 37]

         She **gave him** the book.
         He **gave** the book **to** him. 

    * DITRfetch-type (optional for)  [09 41]

         He **bought** her a ring.
         He **bought** a ring **for** her.

    * DITRprovide-type (optional with, to)  [09 39]

         They furnished us the answers.
         They furnished the answers **to** us.
         They furnished us with the answers.

**Caution:**   Some verbs that take indirect objects also take clausal and verbal complementation (e.g., teach, write, explain).   Such verbs should not be encoded here, but should be coded for their more complex argument structure.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

Pre-Process Transitive Superset  [PREPR]   [06]
-----------------------------------------------------------------------------

**Definition:**   The Pre-Process Superset denotes a small group of verbs that take as objects process nouns (nouns derived from verbs).  These verbs may lend themselves to the following type of transformation: 

    **Accomplish the removal = remove**

**Examples:**   accomplish, effect, instigate,  perform, restart

* Pre-Process Superset comprises a single set as follows:

    * PREPRaccomplish-type [06 33]

         He effected a reduction in expenditures.
         They instigated a reform of the party.

**Caution:**   Verbs in this set do not ever take verbal or clausal complementation.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

Simple Pre-Verbal Transitive Superset  [PREV]   [05]
-----------------------------------------------------------------------------

**Definition:**   The Simple Pre-Verbal Superset denotes a class of verbs which take infinitival verb complementation, including the -ing form of the verbal complement.  Note that this class of verbs has a simple argument structure and therefore it does not accommodate the indirect object, for example.

**Examples:**  begin, complete, continue, fail, finish, grow, omit, practice, refuse, resume, start, volunteer

* The Simple Pre-Verbal Superset includes the following three sets:

    * PREVfinish-type (V-ing)  [05 40] 

         He finished cleaning up the basement.

    * PREVbegin-type  (V-ing and to V)  [05 48] 

         She began playing the piano.
         She began to play the piano.

    * PREVfail-type (to V)  [05 49] 

         They refused to surrender.

**Caution:**   Verbs taking verbal complementation that also invite indirect objects should not be coded here, but under Pre-Verbal Di-Transitives.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

Pre-Verbal Di-Transitive Superset  [PREVDI]   [14]
-----------------------------------------------------------------------------

**Definition:**   The Pre-Verbal Di-Transitive Superset is a class of verbs that takes compound complementation in the same sentence: (1) verb clause of various patterns and (2) direct or indirect object. 

Note that verbs in this superset do not take th-clause complementation. 

* Pre-Verbal Di-Transitives comprise the following sets shown with their argument structure:  

    * PREVDIpermit-type [14 93]  (enable, encourage, favor, permit, program, suffer)

        (1)  V N to V

               This will enable everyone to prosper.

        (2)  V V'ing  (only in some verbs in this set)

               Town ordinances do not permit fishing from beaches.
               We should always encourage their helping the poor.

    * PREVDIaccustom-type [14 34]  (accustom, dedicate, devote, equate)

        (1)  V N to V  (limited application)

               He could never accustom himself to speak frankly to them.
                
                      \- or -

        (2)  V N to V'ing

               They devoted great efforts to saving the environment.

    * PREVDIaid-type [14 67]  (aid, assist, inveigle, involve, talk, trick, pressure)

        (1)  V N to V

               Circumstances pressured them to agree.

                      \- or -

        (2)  V N in/into V'ing

               The salesman talked them into buying.

    * PREVDIdare-type [14 89]  (dare, get, like, love, prepare, want) 

        (1)  V N to V (obligatory)

               They couldn't get him to concede.
               They prepared the students to take the test.

        (2)  V to V (obligatory)  

               I didn't get to speak my mind.
               Residents prepared to evacuate.

        (3)  V N V'ing (possible)

               His remarks got the students thinking.

        (4)  V N PstP (possible)

               The nation wants him pardoned.

        (5)  V V'ing (for love and like only)

               She liked playing with the children.

    * PREVDIbar-type [14 83]  (bar, block, inhibit, prevent, prohibit) 

        (1)  V N from V'ing

               The seal prevented gas from escaping.

        (2)  V one's V'ing

               They barred his entering the race.

    * PREVDIkeep-type [14 36]  (keep, preclude, stop) 

        (1)  V V'ing

               Stop talking.  Start acting.

        (2)  V N from V'ing

               Nothing should keep you from participating.

        (3)  V one's V'ing

               Nothing should stop your participating in the race.

    * PREVDIleave-type [14 23]  (leave, behold) 

        (1)  V N V'ing

               The news left her reeling.

    * PREVDIappoint-type [14 95]  (appoint, assign, choose, designate, qualify) 

        (1)  V N to V

               This qualifies them to participate.

        (2)  N is V'd N/ V N N

               She was designated president.

               He was assigned a programmer.

               They appointed her chairperson.

        (3)  N is V'd as N

               She was qualified as a professional

    * PREVDImisc-type [14 70]  (accuse, credit, criticize, thank, value) 

        (1)  V N  Prep V'ing  

               The government accused him of spying.

               They credited him with saving the day.

               Everyone thanked her for helping.

        (2)  V one's V'ing  (limited application)

                They criticized his arguing the case so vehemently.

                They valued her researching the question so well.

    * PREVDIbid-type [14 88]  (bid, have, help, let, make)

        (1)  V N V

               The judge would not let the witness answer.

               They made him do it.

        (2)  N V'd to V  (limited application)

               He was made to do it.

        (3)  V V (help only)

               He helped carry the packages.


**Caution:**   If the Pre-Verbal verb you are seeking to code also takes th-clause complementation, it should not be coded here, but under the Pre-Verbal/ Pre-Clausal Superset.

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

Pre-Clausal Transitive Superset  [PCL]   [03]
-----------------------------------------------------------------------------

**Definition:**    Pre-Clausal verbs take th-clause complementation.  Some members of this superset also take wh-clause complementation.  Verbs in this superset do not take verb clause complementation (for which see Pre-Clausals/ Verbals superset on the Index to the left).

**Examples:**  answer, ascertain, assure, believe, cable, calculate, certify, denote, doubt, ensure, estimate, explain, foretell, inform, judge, notify, predict, protest, prove, read, relate, signify

* Transitive Pre-Clausals include the following sets:

    * PCLdoubt-type   [03 53]

         We doubt/calculate/etc. that

    * PCLdeclare-type     [03 22]

         We declare/predict/etc. that

         We declare/predict/etc. to them that

         We declare/predict/etc. them to be . . .

         We declare/proclaim/etc. them the winner.

    * PCLinform-type  [03 30]

         We answer/grant/etc. that . . .

         We inform/assure/etc. them that . . .

    * PCLexplain-type     [03 32]

         We explain/reply/etc. that . . .

         We explain/reply/etc. to them that

    * PCLstrike-type  [03 87]

         It strikes me that . . .

         They bet me that . . .



**Tips:**   Do not confuse Transitive Pre-Clausal verbs with Intransitive Pre-Clausal verbs. Transitive Pre-Clausal verbs are so designated because these verbs can also take simple direct objects (e.g., He conceded that . . . /  He conceded the point.)  Intransitive Pre-Clausals cannot take direct objects (e.g., insist, appear, etc.)

**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 

 

 

Pre-Clausal/Verbal Transitive Superset [PRECV]   [08]
-----------------------------------------------------------------------------

**Definition:**   The Pre-Clausal/Verbal Superset comprises a class of verbs that takes both verbal and th-clause complementation.  Verbs in this superset may take a variety of other argument structures as well. 

* Pre-Clausal/Verbal Superset includes the following sets:

    * PRECVagree-type  [08 55] (agree, claim, decide, forget, hope, learn, plan, presume, think)

        (1)  V to V

               They agreed to pay the debt.

        (2)  V th-/wh-

               We thought that the rain would stop.

               Forget what I said earlier.

    * PRECVtell-type  [08 62] (convince, fate, persuade, petition, remind, tell)

        (1)  V N to V

               They persuaded him to run for office.

        (2)  V N th-/wh-

               Convince her that this is the best course of action.

               Tell us what your thoughts are on the subject.

        (3)  V N of N (limited application)

                We reminded him of his promise.

    * PRECVask-type  [08 63] (ask, beg, promise, suffice)

        (1)  V to V

               They promised to accompany us.

        (2)  V N to V

               They begged her to join them.

        (3)  V that

               The governor promised that taxes would be lowered.

        (4)  V N th-/wh-

               Tell him that she agrees.

               Ask him whether he agrees.

    * PRECVwish-type  [08 91] (desire, determine, expect, mean, request, wish)

        (1)  V to V

               He meant to make reservations.

        (2)  V N to V (limited application)

               We expect you to comply.

        (3)  V th-/wh-

               The doctor has determined that the illness would soon pass.

               They could not determine what caused the illness.

    * PRECVenjoin-type  [08 65] (command, direct, enjoin, order, require, trust, understand)

        (1)  V N to V

               The police ordered residents to evacuate the area.

        (2)  V th-/wh-

               We trust that you'll be comfortable.

               You will understand what the reason was.

    * PRECVadmit-type  [08 85] (acknowledge, admit, confess, consider, deny, own, report)

        (1)  V one's V'ing

               The judges acknowledged her winning the competition.

        (2)  V to V'ing

               He confessed to being the author.

        (3)  V th-/wh-

               Consider what the consequences may be.

        (4)  V to N that

               Students reported to the teacher that the project was done.

        (5)  V N N (limited application)

               They considered him their leader.

               They denied him the promotion.

        (6) V N as N (limited application

              They admitted her as a full member.

               They considered him as their leader.

        (7)  V N to N (limited application)

               Report the matter to the authorities.

    * PRECVrecall-type  [08 45] (anticipate, appreciate, fancy, recall, recollect)

        (1)  V one's V'ing

               They appreciated John's helping them.

        (2)  V one V'ing

               I cannot fancy Mary doing that.

        (3)  V th-/wh-

               Try to recollect what happened.

               She recalled that it was raining that day.

    * PRECVsee-type  [08 43] (hear, notice, observe, perceive, see, watch, discover (ing only), find (ing only), imagine (ing only)

        (1)  V N V'ing

               They saw him running with the ball.

               Imagine yourself winning the lottery!

        (2)  V N V (limited application)

               They watched him make a touchdown.

               They heard her deliver the speech.

        (3)  V th -/wh-

               They noticed that the rain had stopped.

               They could not imagine who might have done it.

    * PRECVwarn-type  [08 50] (caution, forewarn, instruct, teach, warn, advise (v V'ing)

        (1)  V N to V

               He taught his son to swim.

        (2)  V N that

               Warn them that a storm is coming.

        (3)  V that

               He advised that we proceed with caution.

    * PRECVintend-type  [08 42] (allow, forbid, intend, prefer,  propose, recommend, remember, regret)

        (1)  V V'ing 

               He prefers dining alone.

        (2)   V that

               They regret that they could not participate.

        (3)  V N to N and V N N (in limited applications)

              They recommended her to them.

              They prefer city life to rural living.

              They allowed him entrance.

        (4)  V to V  (limited application)

               I intend to vote this year.

        (5)  V N to V  (limited application)         

               They allowed the students to express their views.

        (6)  V N that N V (subjunctive)  (limited application)

              I propose that he do that.

              I recommend that she attend the session.

    * PRECVplease-type  [08 77] (amuse, bother, concern, please)

        (1)   It V N to V

               It pleased her to be chosen.

        (2)  It V N that

               It amused us that he said so.

        (3)  N be PP that

              We were concerned that his health was failing.


**Developers' Tips:**   Because of the endless richness of verb argument structures, the SAL Verb Taxonomy can only hope to capture salient features, and even that  imperfectly.   The Logos Model depends upon use of the Semantic Table (SEMTAB) to capture argument structures not provided for in the taxonomy.  SEMTAB rules to cover fine points of verb argument structures can be written via TermBuilder.

 


 

Transitive Verbs: Pre-Clausals  [PCL]   [03]
-----------------------------------------------------------------------------

[mnemonic: PCLdoubt-type]  [code: 3 53]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    A simple class of pre-clausal verbs that take th-clause complementation.  Some of these verbs may also take wh-clause complementation;  e.g., Inquire which . . .

**Examples:**    calculate, check, doubt, ensure, inquire

**Patterns:**  

    (1)  V that/what

           Meteorologists calculated that the storm would veer northward.
           He doubted what he had been told.
           Check which fuse is functional.

**Caution:**   These verbs do not allow indirect objects.

**Developers' Tips:**

 

 

 

Transitive Verbs: Pre-Clausals  [PCL]   [03]
-----------------------------------------------------------------------------

[mnemonic: PCLdeclare-type]  [code: 3 22]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    A mixed class of pre-clausal verbs that satisfy some combination of the **Patterns** shown below, notably the th-clause complementation.   These verbs also take indirect objects and, in many cases, predicate nominative complementation.  Less commonly, they may take wh-clause complementation;   e.g., We cannot describe what happened.

**Examples:**    ascertain, believe, certify, concede, declare, demonstrate, describe, estimate, infer, judge, note,  predict, proclaim, prove, say, show, suggest, suspect

**Patterns:**  

    (1)  V that/what

           Evidence suggests that . . .
           Scientists predict that . . .
           We noted what they said . . .

    (2)  V to N that/what

           The witness conceded to the examiner that . . .
           Certify to the police that . . .
           Show them what you bought.

    (3)  V N1 to be N2

           They believed him to be the author.

    (4)  V N1 N2 =  V N1 to be N2
    
           They declared her a genius (i.e., declared her to be a genius).

    (5)  V N1 N2 =  V N1 to N2

           They conceded him the point (i.e., conceded the point to him).

**Tips:**  Pattern (1) above represents the minimum obligatory complementation for this set of verbs insofar as they function pre-clausally.  Some of the optional (facultative) complementation obviously is not pre-clausal;  e.g., Patterns (3), (4), and (5).

**Caution:**   Not all verbs in this class satisfy all patterns;  e.g., \*We believe to him that . . .

**Developers' Tips:**

 

 

 

Transitive Verbs: Pre-Clausals  [PCL]   [03]
-----------------------------------------------------------------------------

[mnemonic: PCLinform-type]  [code: 3 30]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    A class of pre-clausal verbs that satisfy the Patterns shown below, notably the th-clause complementation with optional indirect objects.  Less commonly, some verbs in this class may take wh-clause complementation.

**Examples:**    answer, assure, cable, grant, inform, notify, telephone, wire, write

**Patterns:**  

    (1)  V that/what

           Notify residents that . . .
           Inform us what . . .

    (2)  V to NP that/what

           We wrote to them that . . .
           We wrote to them what/why . . .

    (2)  V NP that/what

           We wrote them that . . .
           We notified them why . . .

**Tips:**  None of the patterns above are obligatory.

**Caution:**  This set may express the indirect object without the preposition to; e.g., Wire me the results.  In that regard, it differs from the explain-type set where the preposition to cannot be omitted for the indirect object.

**Developers' Tips:**

 

 

Transitive Verbs: Pre-Clausals  [PCL]   [03]
-----------------------------------------------------------------------------

[mnemonic: PCLexplain-type]  [code: 3 32]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    A class of pre-clausal verbs that satisfy the Patterns shown below, notably the th-clause complementation with optional indirect objects.  Less commonly, some verbs in this class may take wh-clause complementation.

**Examples:**    cry, denote, explain, foretell, imply, indicate, object, protest, read, relate, reply, signify, testify

**Patterns:**  

    (1)  V that/what

           They implied that   
           They related what . . . 

    (2)  V to NP that/what

            Explain to them what . . .

**Tips:**  Neither of the above patterns is obligatory.

**Caution:**  This set may not express the indirect object without the preposition to; e.g., Explain to me the results.  In that regard, it differs from the inform-type set where the preposition to can be omitted for the indirect object.

**Developers' Tips:**

 

 

 

Transitive Verbs: Pre-Clausals  [PCL]   [03]
-----------------------------------------------------------------------------

[mnemonic: PCLstrike-type]  [code: 3 87]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   A class of pre-clausal verbs that satisfy some combination of the Patterns shown below, notably the th-clause complementation with optional direct or indirect objects.

**Examples:**    bet, strike, wager

**Patterns:**  

    (1)  V DO that

           They bet ten dollars that . . .

    (2)  V IO that

           They bet him that . . .

    (3)  V IO DO that

           They bet him ten dollars that . . .

    (4)  It V DO that

           It strikes me that . . .

**Tips:**  This set differs from other pre-clausal sets in allowing a direct object combined with clausal complementation (Patterns 1, 3, and 4).

 

 

 

 
Verb Prepositional Governance Codes
-----------------------------------------------------------------------------

XX in the mnemonic is replaced by the appropriate superset mnemonic; e.g., OBHUMwith. 
(This applies to the following transitive supersets:  OBHUM, OBTR, SUBTR, and RECTR
and to the intransitive INOP.) 

.. csv-table:: 
   :header: "Mnemonic", "Description", "Set Code", "Examples"
   :delim: |
   :widths: auto


    XXinto-type | motional sense preps = on, upon, to, onto, in (acc), towards, from, underneath                            | 24                                | march, place, press
    XXin-type   | locative preps = in, on, under (dat), at (place)                                                          | 68                                |
    XXafter     | after/upon/on = along the lines of/after                                                                  | 86                                | base, model
                | against (see for/as)                                                                                      |                                   |
    XXaround    | around/about = around                                                                                     | 56                                | coil, twist, wind
                | as (see for/as)                                                                                           |                                   |
    XXat28      | at = to, on (static place); to = onto                                                                     | 28                                | affix, anchor, apply, attach, clamp, couple
    XXat94      | at = toward                                                                                               | 94                                | aim, point
    XXfor71     | for = for the presence of or to know or to get                                                            | 71                                | assess, consult, review
                | away from (see from)                                                                                      |                                   |
    XXfor46     | for/as = for the sake of/against/as being                                                                 | 46                                | preserve, save
    XXfor80     | for = with respect to                                                                                     | 80                                | correct
    XXfor84     | for/as = for the purpose of/against                                                                       | 84                                | employ, utilize, use
    XXfor81     | for = in place of, in exchange for                                                                        | 81                                | exchange, substitute, trade
                | from (from . . . to) see to                                                                               |                                   |
    XXfrom78    | from = against                                                                                            | 78                                | defend, guard, preserve, protect, shelter
    XXfrom19    | from = away from, off of, out of                                                                          | 19                                | bite, detach, disconnect, dismiss
    XXfrom96    | from/between = with respect to, vis a vis                                                                 | 96                                | discriminate, distinguish, abstain
    XXfrom26    | from . . . to = what . . . to become                                                                      | 26                                | alter, change, demote,  transform
    XXin82      | in = default (misc.)                                                                                      | 82                                | calibrate
    XXin27      | in/into = so as to become                                                                                 | 27                                | assemble, cut, divide
    XXin20      | in/into = within                                                                                          | 20                                | house, lock
    XXof17      | of = converbal prep                                                                                       | 17                                | cleanse, clear, cure, empty, rid, rob
                | Off/off of = from, away from                                                                              |                                   | pick, pull, scrape
                | out of = (see from)                                                                                       |                                   |
    XXon86      | on/upon = after                                                                                           | 86                                | base, model, pattern
    XXon90      | on/over/about = about, concerning; "at" in passive construction = about, over                             | 90                                | annoy, bother, brief, challenge
    XXto28      | to = onto;  at = on (static)                                                                              | 28                                | affix, anchor, apply, attach, clamp, couple
    XXto57      | to/toward = relational sense                                                                              | 57                                | adapt, appeal, order, orient
    XXto35      | to = so as to become                                                                                      | 35                                | abbreviate, degrade, modify, simplify
    XXto24      | to (from . . . to) = into, onto, toward (motional) or to (destination)                                    | 24                                | carry, copy, divert, drip, take, transport, turn
    XXto18      | to = up to, until, down to, within limits of (esp. measure/time/place)  (see also 18, 32:  up to/down to) | 18                                | accelerate, increase, postpone, reduce, incline
    XXto58      | to = with                                                                                                 | 58                                | bond, connect, join
                | toward (see to)                                                                                           |                                   |
    XXwith74    | with = about                                                                                              | 74                                | acquaint, familiarize
    XXwith52    | with = by means of (may be ambiguous)                                                                     | 52                                | accommodate, balance, choke, overwhelm, fill
    XXwith59    | with = in relation to, with respect to                                                                    | 59                                | align, accord, compare
    XXwith47    | with = together with                                                                                      | 47                                | associate, combine, mix
    XXundif     | To cover cases where a verb belonging to the superset has no prep governance                              | VT: 21, 75, 92, 98 VI: 29, 31, 97 |

