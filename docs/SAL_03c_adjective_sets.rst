SAL Adjective Supersets
========================

General Explanation of SAL Adjective Taxonomy
---------------------------------------------

.. In the following, maroon denotes adjective superset, red denotes adjective set, and blue denotes adjective subset.  

Adjectives are organized in a taxonomy of supersets, sets, and subsets.

Adjectives have three supersets:  descriptive, present-participial, and past-participial.

The descriptive superset includes a broad range of adjectives divided into the sets shown at left.  The sets are based on the syntactic relationships shared by its set members (e.g. adjectives that take clausal complements, etc.)

When coding an adjective, if the adjective can participate in more than one superset or set, it is important that the highest code be assigned according to the following priority:

* descriptive

    * pre-clausal
    * pre-verbal
    * adverbial*
    * non-adverbial
    * post-nominal
    * prefixes
    
* present participial\*
* past participial\*

\* participial adjectives are automatically coded by TermBuilder, based on their respective verbs

Descriptive Adjectives Superset
----------------------------------------------------

Non-participial, Descriptive Adjectives are organized as a single Superset with seven  sets.  Most of these sets contain subsets.

As with most other parts of speech in SAL, adjectives are subclassified according to the syntactic relationships that they tend to have with other words.  

The sets within the Descriptive Adjective Superset are: 

* pre-clausal adjectives [PC]. Adjectives like evident, apparent introduce "that" clauses ("It was evident that . . .")

* preverbal adjectives [PV]. Adjectives like eager, dangerous, ready, etc. introduce "infinitive" clauses ("They were eager to go.").  Adjectives like instrumental, capable, etc. introduce other types of verbal clauses ("They were instrumental in solving . . ." -  "They were capable of solving . . .")

* adverbial adjectives [AV]. Adjectives like slight, real, minimal, etc. have adverbial counterparts (slightly, really, minimally).  This classification allows the system to transform phrases like rapid oscillation to oscillate rapidly, a transformation often called for in certain target languages. 
 
 The adverbial adjective set is further broken down into adjective subsets with adverbial coloration;  e.g., manner (intrepid); time (immediate); place (local); order (previous); degree (utter).  

 Adverbial adjectives may also be coded for governance of a particular preposition;  e.g. adjacent to, distant from, indifferent about.

* non-adverbial adjectives [NAV]  Adjectives in this set do NOT have adverbial counterparts and CANNOT be converted to adverbs (e.g. yellow)  The non-adverbial adjective set is distributed over two subsets:  

  * predicate adjective:  adjectives which functions as a predicate adjective.They fit  the pattern: NP is ADJ.  (E.g., The flower is yellow.)
  * non-predicate adjective:  An adjective which functions only attributively.  (E.g., Atlantic, bridal, naval). They fit the pattern DET ADJ N

* Pure post-nominal [POST]: An adjective which can only occur in post-nominal position. (E.g., money galore).  There are only a few such adjectives in English.  These adjectives occur in the pattern NP ADJ, and usually stand for collapsed relative clauses.  E.g., The phrase The house ablaze with light can be parsed as a shortened form of The house that is ablaze with light. . . .  Note that these adjectives may be coded for prepositional governance, as in ablaze with.
* Prefix:   Adjectives that appear exclusively in pre-nominal position.  E.g., anti-, pro-, omni-, etc.

**Caution:**  Many adjectives fit in more than one category (e.g., lucky fits in most of the above categories).  In such cases, it is essential to choose the highest category according to the order of priority shown above. 

 

Pre-Clausal Adjectives 
--------------------------------

An adjective belongs in this set if it can be followed by a subordinate clause (E.g., It is mandatory that . . .; John was certain that... ). 

Some adjectives in this set may also be pre-verbal if they can be followed by a verbal complement.  (E.g., It is mandatory to V;  John is good at V'ing, etc. ).  

There are three subgroupings of pre-clausal adjectives, as follows:

* Pure logical: (It is ADJ that/to)

  These adjectives take the logical it as a subject.  (E.g., It is apparent that . . . or It is urgent that/to . . . )  Pure Logical subsets are:

  * urgent type (that/to)
  * clear type (that)

* Mixed logical: (It/NP is ADJ that/to)

  These adjectives take either a normal NP subject or the logical it.   (E.g., She is certain that/to . . . or It is certain that/to . . . ).  Mixed logical subsets are:

  * certain type (that/to)
  * good type (that/to)

* Non-logical: (NP is ADJ that/to)

  These adjectives take a normal NP subject, but cannot take the logical it.   (E.g., He is happy that/to . . . or She is hopeful that . . . ).

  * happy type (that/to)
  * aware type (that)


pre-clausal: urgent type [mnemonic: PCurgent]  [code: 13 86 432]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   Urgent-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation, but only with logical it subject
* may also take infinitive verb clause complementation, but only with logical it subject  (e.g., It is essential that they go/(for them) to go).
* generally takes the subjunctive (e.g., It is important that he go.)

**Examples:**  appropriate, absurd, better, best, bizarre, compulsory, convenient, crucial, essential, feasible, important, irrelevant, mandatory, natural, necessary, optional, possible, proper, ridiculous, typical, unfair, unusual, urgent

**Patterns:**

    It is ADJ that . . .
         It was urgent that food be rushed to the refugees.
    It is ADJ to NP that . . .
         It is essential to the democratic process that voters be informed.
    It is ADJ to V.
         It is crucial to meet the deadline.
    It is ADJ for N to V.
         It is feasible for the two companies to merge.

**Tips:**  For some adjectives in this subset, the test for that clause complementation may be extended to include wh- clauses.  E.g., It is optional whether they do this or not.


**Caution:**   When in the predicate adjective position, PCurgent adjectives cannot take a normal NP subject and have that clause complementation ( e.g. \*He is essential that...).

When in the predicate adjective position,  PCurgent adjectives that do have a normal NP subject (e.g. Vitamins are important) cannot simultaneously take infinitive clause complementation.  For example, in sentences (1) and (2) below, the infinitive clause is adverbial.  (In both (1) and (2), the particle to has the sense of in order to.)

    (1) John's contribution is essential to accomplish this task.
    (2) John is the best person to accomplish this task.

**Developers' Tips:**  

    (1)  It was important for the citizens of Boston that the team won.
    (2)  The coach held aloft the Keys to the City of Boston that the team won.
    (3)  It was important for the citizens of Boston to win this series.
    (4)  The team needed the support of the citizens of Boston to win this  series.

In (1), the assignment of PCurgent to the adjective important allows a deterministic parser to interpret that the team won as a subordinate clausal complement to the adjective, and not as a relative clause as in (2).  This code also allows the parser to see the verb won as intransitive rather than transitive (as it is in (2)). 

Similarly, in (3), the PCurgent code assigned to important enables a deterministic parser to interpret the infinitive clause to win this series as complementary to the adjective and not as adverbial to the sentence as in (4).  In (4), but not in (3), the particle to would be rendered in order to in the target language.

 

pre-clausal: certain type [mnemonic: PCcertain]  [code: 13 87 438]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Certain-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation.
* may have logical it for a subject only with that complementation  (e.g., It is certain that they will win.)
* may have normal NP subject only with infinitive verb clause complementation (e.g., The team is certain to win.). 

**Examples:**    certain, curious, fortunate, likely, lucky, sure, unfortunate, unlikely

**Patterns:**  

    It is ADJ that . . .
         It is unlikely that the winds will shift.
    It is ADJ for NP that . . . (for some adjectives in this subset)
         It is fortunate for our investors that the market rose.
    NP is ADJ to VP . . .
         The women's team was certain to win.

**Tips:**  For some adjectives in this subset, the test for that clause complementation may be extended to include wh- clauses.  E.g., It is not certain when/whether they will come.


**Caution:**   Note that some adjectives, like indisputable, undecided, uncertain, incurious, etc., which bear a partial resemblance to PCcertain type adjectives, nevertheless do not satisfy all the conditions of this subset and hence should not be so encoded.   E.g. \*John is undecided to vote in the election.

**Developers' Tips:**  The PCcertain code allows a deterministic parser to distinguish between that clauses which complement the adjective and relative clauses, and between infinitive clauses which complement the adjective and adverbial clauses.  See Developers' Tips under PCurgent.

 

pre-clausal: good type  [mnemonic: PCgood]  [code: 13 87 439]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Good-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation.
* may have logical it subject for both that clause and verbal complements  (e.g., It is good that . . ./ It is good to . . . )
* may have normal NP subject only for verbal complements  (e.g., John is good at V'ing.)
* may take the subjunctive  (e.g., It is good that he go.)

**Examples:**   excellent, good, great, horrible, mad, nice, odd, optimistic,  prudent, selfish, sensible, silly, smart, vital

**Patterns:**  

    It is ADJ that . . .

         It is silly that . . .

    It is ADJ for NP that. . .

         It is good for the employees that . . .

    It is ADJ to VP

         It is smart to exercise.

    It is ADJ for NP to VP

         It was silly for them to expect. . .

    It is ADJ of NP to VP

         It was optimistic of them to expect. . .

    It is ADJ V'ing. . .

         It is smart doing the right thing. 

    NP is ADJ to VP.

         John is smart to exercise.

**Patterns specific to good-type sub-groups:**

    It is ADJ to NP that. . .

         It was vital to him that . . .

    NP is ADJ V'ing. . .

         He is smart doing the right thing.  . .

    NP is ADJ at V'ing. . .

         She is good at teaching.

    NP is ADJ in V'ing. . .

         He was selfish in doing this.

     NP is ADJ for V'ing. . .

         Salt is good for seasoning food.

    It was an ADJ NP to VP . . . (see Tips, below)

**Tips:** Note that this type of adjective, when used attributively (e.g., nice gesture) may still take its verbal complementation.  For example:
          
               It was a great party to attend  (i.e. It was great to attend that party)


**Caution:**   Note that good-type adjectives do NOT take that clause complementation when used attributively. E.g., the that clause in It was a great game that we won is a relative clause, not an adjective complement.

**Developers' Tips:**  The PCgood code allows a deterministic parser to distinguish between that clauses which complement the adjective and relative clauses, and between infinitive clauses which complement the adjective  and adverbial clauses.  See Developers' Tips under PCurgent.

 

pre-clausal: happy type  [mnemonic: PChappy]  [code: 13 88 442]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


**Definition:**    Happy-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation.
* may never have logical it for a subject
* may also take various verbal clause complementation (e.g., proud to win;  sorry for losing; proud of having won).
* may take the subjunctive  (e.g., John is anxious that we do it.)

**Examples:**    afraid, anxious, ashamed, careful, desperate, frantic, furious, glad, grateful, happy, overjoyed, proud, sad, sorry, unhappy

**Patterns:**      

    NP is ADJ that . . .
         The team was proud that they won the World Cup.
    NP is ADJ to VP.
         She is glad to help.
    NP is ADJ V'ing. . .
         He is unhappy looking for work.
    NP is ADJ for N to VP.
         They are anxious for us to come. 

**Adjective-Specific Patterns:**

    NP is ADJ of V'ing. . .
         The team was proud/afraid/ashamed of having . . .
    NP is ADJ for V'ing. . .
         He was sorry for having said it.
    NP is ADJ about/over V'ing. . .
         Investors were anxious about/over losing money.
    NP is ADJ with (one's) V'ing. . .
         He was unhappy with my doing that.

**Tips:**   Note that this type of adjective, when used attributively (e.g., proud father) may still take its usual verbal (but not clausal) complementation.  E.g.:
          
      He was a **proud** father **to see his daughter graduate with honors**.


**Caution:**  

**Developers' Tips:**   The PChappy code allows a deterministic parser to distinguish between that clauses which complement the adjective and relative clauses, and between infinitive clauses which complement the adjective and adverbial clauses.  See Developers' Tips under PCurgent.

 

pre-clausal: clear type  [mnemonic: PCclear]  [code: 13 86 433]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Clear-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation.
* may only have logical it for a subject (e.g., It was clear that . . .)
* takes only that/which clause complementation (e.g., It was not         apparent which team would win.)

**Examples:**    apparent, arguable, clear, definite, evident, implicit, incongruous, inevitable, ironic, obvious, pertinent, probable, significant, true, worrisome

**Patterns:**  

    It is ADJ that . . .
         It is probable that a crime was committed.
    It is ADJ who . . .
         It is obvious who was to blame.
    It is ADJ which . . .
         It is apparent which lawyer was most skillful.   
    It is ADJ to N that . . .
         It is vital to the case that forensic evidence be submitted.


**Caution:**   PCclear type adjectives do not take verb clause complementation. Also, PCclear adjectives do not take the subjunctive.

**Developers' Tips:**   The PCclear code allows a deterministic parser to distinguish between that clauses which complement the adjective and relative clauses.  See Developers' Tips under PCurgent.

 

pre-clausal: aware type  [mnemonic: PCaware]  [code: 13 88 443]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Aware-type adjectives, when used as predicate adjectives, have the following characteristics:

* may take that clause complementation.
* may never have logical it for a subject  (\*It is aware that . . . )
* may also take various verbal clause complementation (e.g., unimpressed with having won; cognizant of having broken a record; unconcerned about helping them, etc.
* may take the subjunctive  (e.g., They are adamant that he come.) 
 
**Examples:**   adamant, apologetic, angry, aware, bitter, cognizant, confident, downcast, emphatic, exuberant, hopeful, indignant, insistent, joyful, mindful, unconvinced, unconcerned, unimpressed, unsure

**Pattern:**

    NP is ADJ that . . .
         Investors are **confident** that the economy will improve.

**Possible Verbal Clause Complementation Patterns:**

    NP is ADJ of V'ing. . .
         He is **unsure of** succeeding.
    NP is ADJ about V'ing. . .
         Managers are **emphatic about** keeping to schedules.
    NP is ADJ with Process Noun. . .
         Voters were **angry** with ballot-box tampering.
    NP is ADJ at V'ing. . .
         The team was **downcast** at losing

**Complex Patterns:**  

    NP is ADJ with/at/to NP for/about V'ing  . . .
         They were **apologetic** to him about V'ing . . .
         They are **indignant** at him for V'ing. . .
         They were **pleased** with him for V'ing . .


**Caution:**  PCaware adjectives do not take infinitive clause complements.
Also note that PCaware adjectives, unlike PCurgent adjectives, would not cause the parser to see the that clause in (1) below as a that clause complement.

    (1)  They were exuberant at the response from the citizens of Boston **that the team won**.

**Developers' Tips:**   The PCaware code allows a deterministic parser to recognize the clause for fishing in shallow waters as complementing the adjective in (1).  In (2) the clause is an adverbial clause.

    (1) They were **indignant at** him **for** fishing in shallow waters.
    (2) They criticized him for fishing in shallow waters.

 

 

Pre-verbal Adjectives [PV]
--------------------------------------------------------------------------------

An adjective belongs to the pre-verbal set if, in the predicate adjective position, it can take verb clause complementation of one kind or another.

Note that pre-verbal adjectives DO NOT govern that clauses.     

There are three subgroupings of pre-verbal adjectives:

* Pure logical: (It is ADJ to VP)
  These adjectives may take the logical it as a subject when in the predicate adjective position.  (E.g., It is meaningless to VP. All such adjectives fall into a single Pure Logical subset:

    * valid type (It is awkward to VP)

* Mixed logical: (It/NP is ADJ to VP)
  These adjectives take both the logical it subject and a normal NP subject.  Mixed Logical subsets are:

    * easy type (It was easy to VP / NP is difficult to VP)
    * wise type (It is wise to VP / NP was rude to VP)
    * akin type (NP is akin to V'ing)

* Non-logical:  (NP is ADJ to VP)
  These adjectives only take normal NP subjects. Non-Logical subsets are

    * eager type (NP is eager to VP)
    * first type (NP is next to VP)
    * busy type (NP is adverse to VP)

When pre-verbal adjectives occur in the predicate adjective position, certain transformations are possible, depending on the subset type.  For example, in the valid subset, the adjective modifies the action rather than the agent, as in (1) below. This characteristic is also true of the easy and wise subsets.It is true in a more restricted sense in the case of the akin subset, as sentence (2), below, illustrates.  

    (1) It is **awkward** to say such things-->Saying such things is **awkward**.
    (2) It is **akin** to lying to do such things--> Doing such things is **akin** to lying.

In all the remaining subsets, eager, first, and busy, the adjective modifies the agent rather than the activity, as illustrated in (3), below

    (3) John is **eager** to please--> \*Pleasing John is **eager**.

**Caution:**  A great many adjectives can take verbal complements when preceded by the intensifier too. (E.g., His hands were too cold to turn the knob.)  Unless such adjectives also take verbal complementation without the adverb too, they do NOT qualify as pre-verbals.

 

pre-verbal: valid type  [mnemonic: PVvalid]  [code: 13 83 418]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Valid-type adjectives, when used as predicate adjectives, have the following characteristics:

* may have logical it for a subject when used with verbal complementation
* takes various verb clause complementation (e.g., to V; for V'ing; for NP to VP)

**Examples:**     arduous, awkward, bad, beneficial, common, counter-productive, fraudulent, healthy, impractical,   meaningless, pointless, profitable, tedious, treacherous, useful, valid, wholesome, worthwhile

**Patterns:**

    It is ADJ to VP
        It would be counter-productive to appeal the verdict.
    It is ADJ for NP to VP
        It would not be healthy for her to exercise.


**Caution:**   PVvalid adjectives cannot take that clause complementation. 
PVvalid adjectives that have a normal NP subject (e.g. Jogging is wholesome) cannot simultaneously take infinitive clause complementation (See (1) below).  

**Developers' Tips:**  In (1), below, the PVvalid code assigned to useful enables a deterministic parser to interpret the infinitive clause to build up one's muscle tone as adverbial to the sentence. 
In (1), therefore, the particle to would be rendered in order to in the target language.

    (1) Jogging is **useful** to build up one's muscle tone.

 

pre-verbal: easy type  [mnemonic: PVeasy]  [code: 13 84 420]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Easy-type adjectives, when used as predicate adjectives, have the following characteristics:

* may have logical it for a subject with verb clause complementation (E.g., It is pleasant to sail.)
* may take a normal NP subject with verb clause complementation (E.g., Some people are hard to please.)
* the pattern NP is ADJ to V e.g., (John is easy to please) transforms to: V'ing NP is ADJ where the ADJ modifies the V'ing and never the NP (e.g., Pleasing John is easy.)

Adjectives preceded by a noun which becomes the direct object of the infinitive when the adjective is patterned as follows:

        (NOUN) is easy TO (VERB) = It is easy TO (VERB) (NOUN). 

Other examples are: 

        Golf is difficult to master = It is difficult to master golf.  
        Sky diving is dangerous to attempt = It is dangerous to attempt sky diving.

**Examples:**    calamitous, catastrophic, costly, dangerous, difficult, easy, hard,   hazardous, pleasant, safe, safer, simple, tough, unpleasant, unsafe

**Patterns:** 

    It is ADJ to VP
        It is pleasant to sail.
    It is ADJ to VP
         It is easy to fix the pipe.
    It is ADJ for N to VP
        It is easy for a plumber to fix the pipe.
    NP is ADJ to VP
         The pipe is easy to fix.

**Tips:**  In the case of the normal NP subject, easy-type adjectives always require the main verb of the VP (in the above patterns) to be transitive.  (See **Developers' Tips**, below).


**Caution:**  

**Developers' Tips:**   In constructions like NP is ADJ to VP, if the ADJ is easy-type, the verb in VP must be resolved to the transitive, with the NP subject as its object. (E.g., John was **easy** to teach.)  Compare the case with other PV wise-, eager-, next-, and busy- types. (E.g., John was **eager** to teach.)

 

pre-verbal: wise type [mnemonic: PVwise]  [code: 13 84 423]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Wise-type adjectives, when used as predicate adjectives, have the following characteristics:

* may have logical it for a subject with verb clause complementation (E.g., It is prudent (of us) to leave when we did.)
* may take a normal NP subject with infinitive clause complementation (E.g., Mary was very shrewd to avoid an argument.
* may also take other verbal clause complementation (with normal NP subjects).  (E.g., They were very imprudent speaking that way; they were negligent in allowing this to happen.)

**Examples:**    audacious, astute, bestial, bold, brilliant, careless, childish, discriminatory, early, far-sighted, heroic, humane, impudent, intelligent, late, negligent, noble, perceptive, polite, provocative, reckless, rude, shrewd, thoughtful, undiplomatic, unprincipled, wise

**Patterns:**

    He is ADJ to V.
         He was reckless to speed.
    It is ADJ (of N ) to V.
         It was reckless of him to speed.
         It was perceptive of the doctor to notice.
    It is ADJ (for N ) to V.
         It was humane for the judge to acquit.
    ADJ V'ing
         He was impudent speaking that way.
    ADJ in V'ing
         Congress was far-sighted in planning so carefully.

**Tips:**  The ADJ in NP is ADJ to V  ( e.g., John was wise to leave) modifies the NP subject, unlike easy-type pre-verbal adjectives which modify the V complement.


**Caution:**  

**Developers' Tips:**   In constructions like NP is ADJ to VP, if the ADJ is wise-type and the V in VP has no object, the V is intransitive. (E.g., John was polite to refuse.)

 

pre-verbal: akin type  [mnemonic: PVakin]  [code: 13 84 419]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Akin-type adjectives, in the predicate adjective position, have the following characteristics:

* takes a normal NP subject 
* takes clausal complementation of the second-infinitive type only (-ing form)
* may have logical it for a subject with infinitive complementation, but only in the pattern: It is ADJ to NP/Gerund to VP.  (E.g., It was tantamount to a proposal (for him) to speak as he did)  

**Examples:**   akin, analogous, conducive, tantamount

**Patterns:**

    NP is ADJ to V'ing. . .
        Vacationing in France is conducive to learning French.
    It is ADJ to V'ing to VP
          It is akin to lying to conceal such facts.
    It is ADJ to NP to VP
         It is conducive to health to eat well.
    It is ADJ to V'ing/NP the way NP VP
         It was hardly conducive to building up confidence the way things went.

**Tips:**  This is a very restricted subset. Note that the construction NP is ADJ, without further complementation, is not normal with akin-type adjectives.


**Caution:**  Akin-type adjectives can only be used with the logical it subject in constructions like those shown above.   Otherwise an it subject with akin-type adjective represents a pronoun subject(with antecedent) (E.g., It was hardly conducive to building our confidence).

**Developers' Tips:**   

 
pre-verbal: eager type [mnemonic: PVeager]  [code: 13 85 428]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Eager-type adjectives, when used as predicate adjectives, have the following characteristics:

* takes a normal NP subject with infinitive clause complementation (E.g., Mary was very shrewd to avoid an argument.
* may NEVER have logical it for a subject (apt and liable are known exceptions).
* less commonly, may also take other types of verbal complementation. (E.g., They were quick in replying to their accusers; They were unfit for taking on  such a large responsibility)

**Examples:**   able, apt, available, competent, eager, eligible, free, hesitant, liable, powerless, prone, quick, ready, reluctant, swift, unfit, untrained, unwilling, worthy

**Patterns:**  

    N is eager for X.
         John is eager for vacation.
    N is ADJ to VP.
         The suspect was unwilling to cooperate with the police.
    N is ADJ for V'ing.   
         Mary is eligible for training. 
    It is liable/apt to VP
        It is apt to rain

**Tips:**  The great majority of eager-type adjectives effect an intransitive bias to the V in the VP complementation in cases where the V has no object.  (E.g., He was hesitant to argue.)  The adjective unfit is an exception: (E.g., The food is **unfit** to eat).


**Caution:**   Except for the adjectives liable and apt, an it subject with eager-type adjective always denotes a pronoun subject(with antecedent) (E.g., It was ready to begin).

**Developers' Tips:**  

 

pre-verbal: first type [mnemonic: PVfirst]  [code: 13 85 429]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


**Definition:**    Valid-type adjectives, when used as predicate adjectives, have the following characteristics:

* takes a normal NP subject with infinitive clause complementation. (E.g., Mary was first to arrive)
* may NEVER have logical it for a subject
* less commonly, may also take other types of verbal complementation. (E.g., They were first in replying to their accusers; They were the last arriving on the scene.)

**Examples:**   first, next, second, slow, eighteenth, fifth, seventh, thirtieth, etc.

**Patterns:** 

    He is ADJ to V.
         We were the first to know.
         She is the first to win such an honor.
    He is ADJ in V'ing.
         His work was slow in gaining recognition.
    He is ADJ V'ing?
         The police proved too slow pursuing the thief.  


**Caution:**  The adjectives last and second normally should be coded as first-type adjectives, but because these words are so ambiguous with respect to their part of speech,, they are coded as noun/adjective homographs. (Click here for explanation)

Adjectives late and early belong to the wise-type subset (they can take a logical it subject).

**Developers' Tips:**   It is the responsibility of the rulewriter to insure that the noun/adjective homographs last and second are correctly resolved to wise-type adjectives.

 

pre-verbal: busy type [mnemonic: PVbusy]  [code: 13 85 430]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**    Valid-type adjectives, when used as predicate adjectives, have the following characteristics:

* takes a normal NP subject 
* may take various types of verb clause complementation. (E.g., Mary was adept at handling such matters)
* may NEVER have logical it for a subject

**Examples:**    adept, aggressive, allergic, assiduous, averse, busy, candid, capable, conscientious, deft, diligent, effective, forceful, handy, inept, proficient, resolute, resourceful, selective, thorough, unused, versatile

**Patterns:**

    NP is ADJ V'ing. 
         He is busy answering phone calls.
    NP is ADJ to V'ing 
         He is unused to speaking in public.
    NP is ADJ to V.  
         The candidate was deft to escape criticism.
    NP is ADJ of V'ing    
         That team is capable of winning the series.
    NP is ADJ in V'ing. 
         They were selective in choosing the candidates.
    NP is ADJ at V'ing
         The student was adept at learning languages.
    He is ADJ at/in PN. 
         The new dean is adept at crisis management.
         She is conscientious in the performance of her duties.

**Tips:**  In some of the patterns above ), the number of applicable adjectives may be as few as one (e.g. ADJ at V'ing: adept at V'ing). 


**Caution:**   The adjective close normally should be coded as busy-type adjectives (closer and closest are so encoded), but because close is ambiguous with respect to its part-of-speech,, it is coded as a noun/adjective homograph. (Click here for explanation)

**Developers' Tips:**   It is the responsibility of the rulewriter to insure that the noun/adjective homograph close is correctly resolved to a busy-type adjective.

 

Adverbial Adjectives [AV]
--------------------------------------------------------------------------------

**Definition:**    Adverbial type adjectives are a broad adjectival class distinguished by the following characteristics:

* denotes adverbial concepts of manner, place, time, degree, etc.
* always has an adverb counterpart.  Either it is interchangeable with the adverb, (e.g., back, above, lower) or it is convertible to an adverb (e.g., immense/ immensely, former/formerly, lower/ lower, utter/utterly.
* may (but not in all cases) function as predicate adjective

Types: There are seven subsets under the adverbial adjective set.

    * prep governance type
    * state/manner type
    * time/order type
    * locative type
    * quantity/measure type
    * degree (intensifier) type

**Tips:**   adverbial adjectives provide the translation system with information pertaining to stylistic transformations that may be required by the target language. 

For example, if an adverbial adjective is followed by a Process Noun (e.g., swift movement), the NP can be transformed stylistically in the target language as move swiftly.  Such transformations are made possible because the lexical entry for the adjective points to both a target adjectival transfer and a target adverbial transfer (called the alternate word class).  (These transfers are entered during the TermBuilder session.)

On the other hand, NP's like inner movement are NOT thus transformable and its adjective code would tell the system not to attempt such a transformation.


**Caution:** In coding adverbial adjectives, be sure to consider prepositional governance.  If an adverbial adjective governs a preposition (as, e.g., adjacent to) this fact preempts any other consideration for this type of adjective. (For more on this, see **Developers' Tips**)

**Developers' Tips:**  Codes for preposition governance are often of critical importance to parsing decisions. For example, in (1), below, the adjective tall is a state/manner type adverbial adjective, which does not govern prepositions, whereas in (2), adjacent is a prep governance type adjective, coded as governing the preposition to.

    (1)  He built his garage **tall** to store his truck.
    (2)  He built his garage **adjacent to** mine.

In (1), the particle to has the value of in order to (and store is properly seen as a verb). In (2), the governance code assigned to adjacent allows the parser to see to as a preposition (and mine as a pronoun). If adjacent has not been properly coded for governance here, very likely to mine would have been seen as an adverbial infinitive clause. The only intelligence the parser has to work with in order to properly analyze (2) is the prep governance code assigned to the adjective adjacent.

 

prep-governance adjectives   [AV] [13 17,20,26,46,57,59,68,90 180,417]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. csv-table:: 
   :header: "Preposition", "Mnemonic", "Numeric", "Examples"
   :delim: |
   :widths: auto


    Locative prepositions (at, on, in, under, above, etc.) | AVloc   | 13 68 180/417 | asleep (on),  submersible (in)
    for                                                    | AVfor   | 13 46 180/417 | ineligible, avid, famous, suitable (for)
    from                                                   | AVfrom  | 13 26 180/417 | distinct, inseparable, remote (from)
    in (non-locative) =  e.g.,  with respect to            | AVin    | 13 20 180/417 | active, deficient, fluent, foremost, methodical, prevalent, well-versed (in)
    of                                                     | AVof    | 13 17 180/417 | apprehensive, devoid, envious, intolerant, suspicious (of)
    about/over/on (non-locative)                           | AVabout | 13 90 180/417 | jittery, joyous, jumpy, obdurate (about/over), reliant, conditional (on)
    to                                                     | AVto    | 13 57 180/417 | adjacent, detrimental, extraneous (to)
    with                                                   | AVwith  | 13 59 180/417 | consistent, familiar, incompatible (with)

\* 180 signifies pre-nominal, 417 post-nominal, which is rare
\* Note that the set/subset coding convention here is anomalous 
 

adverbial adjectives: state/manner [mnemonic: AVstate]  [code: 13 80 180]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   state/manner type adjectives constitute the largest class of adjectives.  They have the following characteristics:

* concern the state or condition of something, or the way something behaves or is done (e.g., clean, boylike, exhaustive)
* have an adverbial counterpart (e.g., exhaustive, exhaustively)
* may occur in the predicate adjective position (e.g. Mary is charismatic)
* do NOT govern prepositions

**Examples:**    charismatic, exhaustive, graphical, intrepid, inveterate, iridescent, irreverent, jovial, joyless, laconic, personable, sly

**Tips:**  See **Tips** for the adverbial adjective set.


**Caution:**   All adjectives in this class MUST be convertible to adverbs.

**Developers' Tips:**  

 

adverbial adjectives: time/order [mnemonic: AVtime]  [code: 13 80 181]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   time/order type adjectives have the following characteristics:

* denote notions of time or order (e.g., recent, former)
* have an adverbial counterpart (e.g., recently, formerly)
* may (but not in all cases) occur in the predicate adjective position (e.g. The need is immediate.)
* do NOT govern prepositions

**Examples:**    bi-annual, cyclical, consecutive, daily, final, former, hourly, immediate, momentary, part-time, primary, random, recent, secondary, sequential, sporadic, temporary, weekly, yearly

**Tips:**  See Tips for the adverbial adjective set.


**Caution:**   All adjectives in this class MUST be convertible to adverbs. Thus, the adjective untimely, for example, does not belong here (it should be placed in predicate subset of the non-adverbial adjective set).

A very few time/order type adjectives may not function as predicate adjectives, e.g., former.

**Developers' Tips:**  

 
adverbial adjectives: locative [mnemonic: AVloc]  [code: 13 80 182]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   locative type adjectives have the following characteristics:

* denote notions of place  (e.g., recent, former)
* have an adverbial counterpart (e.g., backward movement; he moved backward)
* may (but not in all cases) occur in the predicate adjective position (e.g. Their culture is backward, his glance was skyward.   The problem is nationwide.
* do NOT govern prepositions

**Examples:**  above, backward, forward, homeward, inward, nationwide, outbound, overseas, regional, skyward

**Tips:**  See **Tips** for the adverbial adjective set.

**Caution:**  All adjectives in this class MUST be convertible to adverbs. Thus, the adjective interoffice, for example, does not belong here (it should be placed in non-predicate subset of the non-adverbial adjective set).

Note, however, that some locative type adjectives lose their adjectival function and becomes adverbs when in the predicate adjective position, e.g., The answer is above.   Their son is overseas.  Also note that whereas above can function as an adjective (e.g. the above example) the morpheme below is never an adjective.

**Developers' Tips:**  

 

adverbial adjectives: quantity/measure [mnemonic: AVquan]  [code: 13 80 183]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   quantity/measure type adjectives have the following characteristics:

* denote notions of quantity or measure   (e.g., slight, extensive)
* have an adverbial counterpart (e.g., slightly, extensively)
* may occur in the predicate adjective position (e.g. The effect was extensive).
* do NOT govern prepositions

**Examples:**   approximate, colossal, countless, endless, enormous, extensive, huge, immeasurable, immense, lengthy, massive, minimal, monumental, numberless,  numerous, slight, voluminous

**Tips:**  See **Tips** for the adverbial adjective set.


**Caution:**  All adjectives in this class MUST be convertible to adverbs. Thus, adjectives such as extra, gargantuan, king-size, large-scale, oversized do not belong here (they should be placed in the predicate subset of the non-adverbial adjective set).

**Developers' Tips:**  

 

 

adverbial adjectives: degree [mnemonic: AVdegree]  [code: 13 80 184]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   degree type adjectives have the following characteristics:

* denote notions of intensity or degree   (e.g., actual, utterly, mere)
* have an adverbial counterpart (e.g., merely, substantially)
* may (but not in all cases) occur in the predicate adjective position (e.g. The effect was substantial).
* do NOT govern prepositions

**Examples:**   actual, acute, comprehensive, downright, entire, intense, interminable, mere, outstanding, profound, real, substantial, utter

**Tips:**  See **Tips** for the adverbial adjective set.


**Caution:**  All adjectives in this class MUST be convertible to adverbs.

**Developers' Tips:**  

 

 

Non-adverbial Adjectives [NAV]
--------------------------------------------------------------------------------

**Definition:**    non-adverbial type adjectives have the following characteristics:

* have NO adverbial counterpart (e.g., bombproof, cordless, Baltic)
* do NOT govern prepositions

The non-adverbial adjective set has two subsets:

* predicate adjectives (adjectives which can occur in the predicate adjective position)
* non-predicate adjectives (adjectives which CANNOT normally occur in the predicate adjective position, e.g. bridal, Atlantic)

**Caution:** These adjectives DO NOT have adverbial counterparts.

 

 
non-adverbial: predicate adjective [mnemonic: NAVpred]  [code: 13 81 186]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   non-adverbial predicate type adjectives constitutes a broad class of adjective having the following characteristics:

* has NO adverbial counterpart (e.g., bombproof, cordless)
* does NOT govern prepositions
* may appear in the predicate adjective position

**Examples:**  above-mentioned, adversarial, all-purpose, auditory, bivalent, bombproof, cellular, cordless, deluxe, editable, exploratory, far-reaching, fungible, grainy, hard-core, hereditary, inferior, jobless, leaky, marbled, non-partisan, scholarly, slow-acting, undamaged, wooded, untimely

**Tips:**  See **Tips** for the adverbial adjective set.


**Caution:**  All adjectives in this class MUST NOT be convertible to adverbs.

**Developers' Tips:**  

 
 

non-adverbial: non-predicate adjective [mnemonic: NAVnpred]  [code: 4 81 187]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Definition:**   non-adverbial non-predicate type adjectives is a small adjective class with the following characteristics:

* has NO adverbial counterpart (e.g., bridal, Atlantic, Baltic, naval)
* does NOT govern prepositions
* may NOT appear in the predicate adjective position, i.e. are used ONLY attributively.

**Examples:**    Atlantic, bridal, naval

**Tips:**  See **Tips** for the adverbial adjective set.


**Caution:**  All adjectives in this class MUST NOT be convertible to adverbs.

**Developers' Tips:**  

 

 

Pure Post Nominals [mnemonic: POST]  [code: 4 81 417]
--------------------------------------------------------------------------------

**Definition:**   An adjective which can **only** occur in post nominal position; i.e., NP ADJ.  (E.g., The lottery winner suddenly had **money galore**.)

**Examples:**    galore, ablaze, abloom, astir, fraught, replete, unacquainted, asleep, unafraid, alike, alone, unalike, unsuited, afire, aflame, aglow, awash, alive, indebted, resistant, aground, ajar, amiss, awake, awry, aground,

**Tips:**   Pure post nominals, like galore, are rare in English. More often, when these adjectives occur, they usually stand for collapsed relative clauses.  For example, the phrase The house ablaze with light can be parsed as a short form of The house that is ablaze with light. . . ..  

Frequently, a pure post nominal may govern a particular preposition.  E.g., awash with, unsuited for, fraught with, indebted to.  In such cases, the adjective is coded to reflect the prepositional governance. 

**Caution:**   An adjective should only be coded as a pure post-nominal if it can never be preposed, such as galore, ablaze or alike.  Adjectives which may occasionally function as postposed, but which are normally preposed, should not be coded as post- nominal; e.g., green in the following example: She flashed eyes green with envy.  The reason for this is made clear in the following examples:

    (1) He painted a house with shutters galore.
    (2) He painted the house with shutters green.

In (1), if galore is correctly coded as pure post nominal, the parser would see it correctly as an adjective modifying shutters.  However, in (2), if green were incorrectly coded as pure post nominal, the parser would be unable to see green as a predicate complement and would therefore parse it incorrectly.

**Developers' Tips:**    On the basis of the numeric codes, pure post nominal adjectives constitute a subset under the non-adverbial adjective set . For purposes of taxonomic clarity, however, it is being treated in the tutorial as a separate set.  There are no hidden implications in this change.

 

 

prefixes [mnemonic: PRE]  [code: 13 82 100]
------------------------------------------------

**Definition:**  Adjectives that appear exclusively in pre-nominal position.  E.g., anti-, pro-, omni-, etc.

**Examples:**  aero-, anti-, bi-, non-, omni-, mid-, contra-, infra-, micro-, multi-, semi-, pseudo-, trans-, re-

* re- has a word-specific subset code:  mnemonic:  PREre; numeric:  318.

**Tips:**  Since these prefixes are used used with hyphenation, they need to be in the lexicon as distinct entities.

**Caution:**  

**Developers' Tips:**  

 

 

Participial Adjectives Superset
--------------------------------------------------------------------------------

Present Participle [mnemonic: PRES] [code: 15] [form: 60]
Past Participial [mnemonic: PAST] [code: 16] [form: 50]
-ABLE Participles [mnemonic: ABLE] [code 16] [form: 23]

**Definition:**   An adjective belongs in this category if it is a participial form of a verb in current usage. Participles are of three kinds:

* present participle (e.g., hoping, designing, realizing)
* past participle (e.g., seen, revised, displayed)
* -ABLE participle   (e.g. consignable, obtainable, etc.)

Participial adjectives derive their coding automatically from their respective verbs.

**Tips:** Participial adjectives may also function as attributive descriptive adjectives, as in a telling glance, the known world, adjustable amount.  However, it is the participial function that determines their classification (e.g., the reporter covering this meeting, or the reporter assigned to cover this meeting.

**Caution:**  A fair number of present participles are used only attributively and in effect lose their verbal coloration.  Consider the following sentences:

    (1) This book is interesting, fascinating, riveting, pleasing, etc.
    (2) The author's reputation is growing. 

In (1) the proper parse for is interesting, etc. is BE + PREDICATE ADJ. In (2) the parse for is growing would be V(PRES PROGRESSIVE TENSE).  The verbal -ING form in (2) can always be modified by an adverb (...is growing slowly).  This is never the case in (1), indicating that it is no longer verbal in function. (The adjectival -ING form of course can be modified by intensifier adverbs like very, exceedingly, etc.) 

Much the same can be said of certain -ABLE participles. For example:

    (1) This kitten is adorable.
    (2) This book is obtainable from the author.

In (1) the proper parse for is adorable is BE + PREDICATE ADJ.  In (2) the parse would see obtainable as the main verb.

All adjectival -ING and -ABLE forms are stored in the lexicon as participles. Parsing rules that draw upon the the Semantic Table are responsible for recognizing when an -ING form or -ABLE form is functioning purely attributively. In such cases, the Semantic Table will change the target language transfer supplied by the lexicon, where necessary.

**Developers' Tips:**  Note that the only numeric coding distinction between past participles and -ABLE participles is the form codes of 60 and 23, respectively.

 
