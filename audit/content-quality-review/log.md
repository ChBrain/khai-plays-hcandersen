# Content-quality review of the plays

Advisory review, audit-lane style (no `audit.json`: this directory is a one-shot report, not a recurring audit). It never edits content; every finding awaits a human treatment. Data: [`findings.json`](findings.json).

## Method

A budget-shaped funnel over all 269 plays (~4,700 files, ~634k words):

1. **Scripted integrity pass** (no model): links, frontmatter, khai types, stubs, orphans.
2. **Hub triage** (model): every `play_*.md` scored 1-5 on four rubrics — fidelity to the declared H.C. Andersen source, internal coherence, Danish prose quality, playability.
3. **Targeted deep-dive** (model): all files of the 13 severest non-serial plays plus 2 representative *Billedbog uden Billeder* evenings, verifying the triage verdicts.
4. **Scripted enumeration** (no model): the machine-translation calques surfaced by triage, swept exhaustively by pattern.

Averages across the house: fidelity 3.83, coherence 4.36, prose 3.88, playability 3.86. 156 of 269 plays carry at least one finding; most are minor. Structure is clean (0 broken links, 0 stubs, 0 type mismatches; 2 unreferenced files, see F6).

## F1 - The *Billedbog uden Billeder* evenings stage invented content (systemic)

34 of the 34 `*_aften` plays are flagged. Where the actual evening is known, the staged tableau does not match it (First Evening: the Hindu girl's lamp on the Ganges - staged as a garret tableau; Sixth Evening: the moon over Uppsala's burial mounds - staged as a poor student in a garret). The rest are generic moon-tableaux with no anchor in the source. Deep-dive of two representatives (sdu026, sdu031) confirms the invention is pervasive: every persona/plot/plan builds the invented scene, the two boards nearly duplicate each other, and the series re-invents the book's frame narrative per evening.

**Treatment suggestion:** restage each evening from its actual text, and move the shared moon-and-listener frame to one series-level board instead of re-inventing it per play.

## F2 - Severe fidelity: the declared source is not what is staged

Plays whose board tells a different story than the work named in their frontmatter (triage fidelity <= 2, non-serial). All 13 were deep-dived; 12 confirmed, 1 mitigated. The deviation is pervasive in every case - baked into plots, personas and plans, not a summary artifact.

| play | verdict | what is wrong | suggested treatment |
|---|---|---|---|
| sdu061_venskabs_pagten | confirmed | Character names diverge from Andersen's tale, where the narrator and Aphtanides both love Anastasia; 'Anastasius', 'Apoli' and 'Elena' are garbled inventions. | Restage from the actual tale — restore the narrator, Aphtanides, and Anastasia with the renunciation-into-happy-wedding ending — or retitle as a free adaptation. |
| sdu096_en_historie | confirmed | Andersen's 'En Historie' is about the hellfire-preaching pastor whose dead wife's dream-visit teaches him grace; this poet-judged-at-the-market allegory matches nothing in the declared source. | Restage from the actual source (the damnation-preaching pastor taught mercy by his dead wife's dream-visit); the current board shares only the title and must be rebuilt, with the Danish prose cleaned in the process. |
| sdu098_svinene | confirmed | Andersen's 'Svinene' (from I Sverrig) is a travel sketch on Swedish forest pigs opening with Dickens's pig anecdote; the eagle-versus-sow dunghill debate here is an Aesopian fable, not the declared source. | Either retitle as an original Aesopian fable dropping the Andersen attribution, or restage from the actual 'Svinene' travel sketch in I Sverrig; nothing of the source survives. |
| sdu115_et_blad_fra_himlen | confirmed | Andersen's tale is about a heavenly plant that grows and is mocked, is torn up by a swineherd, and whose last leaf comforts a melancholy king; the play's leaf-crumbling-under-the-magnifying-glass plot is largely invented, and its two triggers skip the child's moment. | Restage from Andersen's actual tale (plant mocked and torn up by the swineherd, last leaf comforting the melancholy king), since the invented angel/child/scholar board shares no scene with the source, or retitle as a free adaptation. |
| sdu130_abc_bogen | confirmed | Invented plot: Andersen's tale is a satire of a new ABC book's pretentious verses mocked by the cock on the old book, not personified letters quarreling over rank and learning cooperation after spilled ink. | Restage from Andersen's actual satire (the cock atop the old ABC book mocking the new book's pretentious verses); the quarrelling personified letters A/B/C are wholly invented and cannot be patched by prose cleanup. |
| sdu132_hurtigloeberne | confirmed | Retells Aesop's hare-and-slow-runner race (hare sleeps, snail wins) instead of Andersen's satire of a prize jury that gives the hare first prize and the snail second for diligence. | Restage from Andersen's actual jury satire (no race is run: the hare is awarded first prize and the snail second for diligence, mocking prize committees), or explicitly retitle the current board as an Aesop 'tortoise and hare' adaptation. |
| sdu133_de_vises_steen | confirmed | Generic seeker-vs-shadow allegory replaces Andersen's actual plot of the wise man in the Tree of the Sun whose four sons fail through their senses while the blind daughter finds the stone through faith. | Restage from the actual source: the wise man in the Tree of the Sun, his four sons failing through their senses, and the blind daughter finding the stone through faith — none of which survives anywhere on this board. |
| sdu174_peiter_peter_og_peer | mitigated | Andersen's satirical piece about the stork myth and the brothers' comic ambitions is replaced by a generic 'three souls set out on life journeys' arc with none of the tale's actual content, and the triggers stay equally vague. | Keep the genuinely faithful stork-myth frame (pond souls, shooting stars, clear vs muddy water) but restore Andersen's satire and the brothers' actual comic ambitions and fates in place of the invented sentimental birth-order allegory. |
| sdu184_hvad_man_kan_hitte_paa | confirmed | Ending is inverted: in Andersen's satire the young man never regains poetry even with the wise woman's glasses and is told to become a critic instead, yet the arc has him happily inspired, clashing with the play's own 'Kritisk' and 'Satirisk' entries. | Restage the ending from the source: he never gains the gift of poetry, cannot keep the wise woman's spectacles and ear trumpet, and is told to become a critic and beat the poets instead — or retitle the current version as a free adaptation. |
| sdu185_hvad_tidselen_oplevede | confirmed | The donkey never eats the thistle in the tale (it is tethered and cannot reach it), and the pivotal Scottish young lady picking the thistle as Scotland's emblem, sealing the engagement, is blurred into a generic compassionate girl. | Restage from the actual tale: the tethered donkey that cannot reach the thistle, and the Scottish young lady who picks the emblem-flower for the buttonhole and seals the engagement, replacing the invented devoured-thistle and pressed-keepsake ending. |
| sdu197_portner_noeglen | confirmed | In Portnoeglen the kammerraad is already married and Lotte-Lene is a young protegee whose luck the key foretells (failed stage career, then a good match of her own); the play invents a marriage between the kammerraad and Lene. | Restage from the actual source: restore the already-married kammerraad (with the kammerraadinde) and Lotte-Lene as the young protégée whose theatrical luck the key foretells, removing the invented kammerraad-Lene marriage and the superstition-cured-by-wedlock arc. |
| sdu611_skilles | confirmed | Arc stages the wrong work: Sprogø ice-stranding with agent Blomme/Ingeborg/Theodor is the premise of 'Den Usynlige paa Sprogø', while 'Skilles og mødes' is 'Spanierne i Odense' plus 'Fem og tyve Aar derefter' (25 years, not 20, and no Sprogø). | Restage from the actual 'Skilles og mødes' (Spanierne i Odense plus Fem og tyve Aar derefter), or re-declare the existing Sprogø ice-stranding board under its true source 'Den Usynlige paa Sprogø'. |
| sdu621_lykkens_blomst | confirmed | In Andersen's Lykkens Blomst (1845) Henrik is transformed into the poet Johannes Ewald and Prince Buris, not into an invented jailer couple 'Tage and Elna', and phrases like 'under lykkestest processen' smell mechanical. | Restage from Andersen's actual 1845 play (Henrik's transformations into Johannes Ewald and Prince Buris), or explicitly retitle as a free adaptation, since the invented Tage/Elna prison-test plot is load-bearing in every board file. |

Deep-dive extras (contradictions invisible at hub level) are in `findings.json` under `deepdive[].extra_findings` - e.g. mutually exclusive pre-checked plans (sdu133), a load-bearing antagonist with no persona file (sdu611), a memory-loss mechanic contradicted by every file using it (sdu621).

## F3 - Machine-translation artifacts in the Danish (mechanical, scriptable)

The English preposition **'to' where Danish 'til' belongs** appears in **110 files** (exhaustive sweep: `grep -rEl " to (det|den|dem|dets|dens|en|et|at|sin|sit|sine|hans|hendes|jorden|graensen|aske|evigheden)\b" plays`). Known garbled tokens ('sua', 'mij') hit 6 more files. Triage also caught scattered untranslated English ('they', 'house', 'with', 'gliding', 'stands', 'dandelions'), Danish false friends ('kejsersnit' for an imperial court, 'museet' for 'musen', 'hvisker ud' for 'visker ud') and khai board-vocabulary leaking into prose ('under redningsprocessen', 'sin sjaelefred plan'). Full file list in `findings.json`.

**Treatment suggestion:** one mechanical cleanup pass (the calque list is exact); the false friends and board-speak need a light human read of the listed files only.

## F4 - Unverifiable sources (mostly the dramatic works and posthumous sketches)

39 plays declare sources too obscure to verify from the hub (many sdu6xx stage works, posthumous sketches, juvenilia). Not defects per se, but the house cannot currently prove fidelity for them; two smell actively wrong (sdu645_truth: no matching Andersen work found plus the 'kejsersnit' howler; sdu212_hans_og_grethe: Hans and Grethe called 'brothers').

| play | note |
|---|---|
| sdu003_alferne_paa_heden | Unverifiable: no confidently known Andersen text matches this title's content, and the shepherd/elf-king pact arc reads as an invented pastoral allegory. |
| sdu004_et_boerneeventyr | Unverifiable source, and the arc/triggers are so vague (children play, summer comes, love grows) that there is nothing concrete to direct; a single shared 'Leger' position covers both personas. |
| sdu005_det_sjunkne_kloster | Details of the early 1831 legend piece are unverifiable, and the prose slips (English process name 'Sinking', anglicism 'to det dybe vand' for 'til'). |
| sdu015_den_gamle_gud_lever_endnu | Unverifiable: the title matches a minor Andersen devotional piece but the bird-and-dropped-bread plot cannot be confirmed; persona 'Den gamle' also sits oddly against the arc's 'fader'. |
| sdu036_ellevte_aften | Unverifiable against the real Eleventh Evening, and given the batch-wide pattern of invented vignettes fidelity is doubtful; sick-girl-and-sprout is generic Andersen pastiche. |
| sdu038_trettende_aften | Unverifiable evening, fidelity doubtful given the invented pattern; 'rik paa varme' is Swedish/Norwegian spelling, not Danish 'rig'. |
| sdu039_fjortende_aften | Unverifiable and doubtful; prose stumbles ('pudser sit erobrede minde', the ungrammatical 'de stolte, slag paa volden'). |
| sdu040_femtende_aften | Unverifiable and doubtful; the tutu-clad ballerina alone in an empty theatre reads as modern invention rather than an 1840 Andersen evening. |
| sdu042_syttende_aften | Unverifiable against the real Seventeenth Evening; widow-at-grave is plausible Andersen mood but likely invented given the batch pattern. |
| sdu043_attende_aften | Unverifiable and doubtful; Company lists both 'Baad' as piece and 'Baaden' as place, a redundant/confusing casting. |
| sdu044_nittende_aften | Unverifiable and doubtful; the 'satirisk' pitch contradicts the wholly sympathetic arc and stakes. |
| sdu045_tyvende_aften | Unverifiable and doubtful; 'hvisker alle spor ud' misspells 'visker ud' (writes 'whispers' for 'wipes'), a real Danish error. |
| sdu049_syvogtyvende_aften | Unverifiable: cannot confirm the 27th evening depicts a sinking swan over the sea; the tableau is also thin and template-like. |
| sdu052_treogtyvende_aften | Unverifiable and doubtful: no recollection of any cuckoo-clock-in-Copenhagen evening in Billedbog uden Billeder; the scene smells invented. |
| sdu055_niogtyvende_aften | Unverifiable: cannot confirm a coachman-at-the-inn evening; the scene is generic enough to be interchangeable with any night vignette. |
| sdu069_een_og_tredivte_aften | Unverifiable evening assignment: I cannot confirm the prisoner-scratching-a-melody scene is the thirty-first evening of Billedbog uden Billeder (I associate that evening with the chained bear and the children), and the two triggers are thin and static. |
| sdu201_qvaek | Unverifiable against the obscure posthumous sketch 'Qvaek' (the boy-stoning-a-toad scene rather suggests Skrubtudsen); grammar slip 'begynder at kaster', a templated 'moon shines satirically' line, and only two thin static beats. |
| sdu202_skriveren | Unverifiable against the posthumous 'Skriveren' (which I recall as satire about a copyist with authorial pretensions, not a solemn preserver of memory); typo 'uregistrerde', a templated moon line, an ink persona the arc never uses, and a static all-night-writing scene with no dramatic turn. |
| sdu204_man_siger | Unverifiable against the obscure piece 'Man siger -!'; the arc is a generic rumor-satire with an unnamed 'concerned citizen' and vague whispering-crowd beats, plus another templated moon line. |
| sdu205_den_fattige_kone_og_den_lille_canariefugl | Unverifiable against the early posthumous sketch (details of the woman sharing her last bread cannot be confirmed); internally consistent but the drama is minimal, and the templated moon line recurs. |
| sdu208_aeblet | Unverifiable against the obscure piece 'AEblet'; the planted-seed/dead-girl/surviving-tree arc feels plausible but unconfirmed, the second trigger ('many years pass') is hard to direct, and the templated 'klang' phrase leaks in. |
| sdu209_temperamenterne | Unverifiable and doubtful: a temperaments allegory with only two of four temperaments (mole/melancholy, merman/phlegm), an orphaned 'Ild' piece with no choleric persona, stilted templated prose, and an abstract 'slowly establish balance' arc with nothing concrete to direct. |
| sdu211_de_blaae_bjerge | Unverifiable: no work titled 'De blaae Bjerge' with this sun-worship parable plot is known to me in Andersen's oeuvre, so the source attribution is doubtful. |
| sdu212_hans_og_grethe | Unverifiable source, and internally contradictory: Hans and Grethe are called 'brothers' though Grethe is a female name, which smells like a hallucinated or garbled reading of the source. |
| sdu501_gjenfaerdet | Andersen's juvenile 'Gjenfaerdet ved Palnatokes Grav' (1822) exists, but I cannot verify this Jochum/Stine falling-gravestone plot against it, so fidelity is unverifiable; also the misspelling 'Hjaemsoegning'. |
| sdu503_grammatica | Unverifiable: I cannot confirm the details of Andersen's grammar satire, and the central conceit is grammatically off (amo governs the accusative, not the dative), which suggests invention. |
| sdu602_vissenbjerg | Andersen's early scene 'Roeverne i Vissenbjerg' exists, but the specific Knud/Ulrik/Henning Aasum abduction plot is unverifiable against it. |
| sdu612_soldat | Unverifiable: 'En rigtig Soldat' is too obscure to confirm the aunt/niece fortress premise, and the near-plotless play-soldier arc is thin to direct. |
| sdu615_mikkels_historier | Unverifiable: the 1840 vaudeville monologue exists, but the diligence/homesickness storyline cannot be confirmed beyond title and genre. |
| sdu618_opera_galleriet | Unverifiable: the declamatory frame linking opera tableaux fits the known benefit piece, but the skeptical-critic conversion plot looks invented. |
| sdu631_noekken | Unverifiable: the 1853 one-act opera Nøkken in a Swedish saga setting is real, but the specific Queen-Christine-disguised-as-the-nix plot and character names cannot be confirmed; also one company entry (PehrLaurinForlovelse) is not linked like the others. |
| sdu632_carnevalet | Unverifiable: Andersen did write carnival prologues for the Casino artist balls, but the Marschal/Nisse/Genius scenario cannot be checked against the obscure source; note the typo 'Ordenshaandhaefer' in the company list. |
| sdu639_vognen | Unverifiable: the title is a genuine Andersen stage piece but its actual content (these characters and the proposal plot) cannot be confirmed against the source. |
| sdu643_rasmussen | Andersen's 1846 flop Hr. Rasmussen is obscure so the plot is unverifiable, the Holbergian father 'Jeronimus' smells invented, and the Arc's undecided '(eller Charlottes)' helper is a drafting artifact. |
| sdu644_danmark | Allegorical prologue source unverifiable, and the Arc's 'museet' (the museum) for 'musen' (the muse) is a machine-translation-grade error. |
| sdu645_truth | No verifiable Andersen work 'Truth' matching this generic Truth-vs-Lie allegory, and 'kejsersnit' (caesarean section) used twice for the imperial court is a howler suggesting fabrication or mistranslation. |
| sdu646_maaneskin | Tyrolean 'Alpescener' source unverifiable against Andersen's oeuvre, and triggers are act-length summaries (three years of waiting) rather than concrete stage cues. |
| sdu647_benefice | The vaudeville's actual content is unverifiable, spelling of souffleur/souffleoer wobbles, and triggers are plot summaries rather than directable moments. |
| sdu651_sangerinden | Source play unverifiable (robbers tamed by an aria is a stock motif), company names misspell 'Roever' as 'Roeber', and triggers are summaries not cues. |

**Treatment suggestion:** stage-source these against the SDU/ADL editions (the estate's source of record) before treating them as faithful; retitle any that are genuinely free inventions.

## F5 - Moderate findings (faithful core, flawed detail)

Plays flagged for softened or inverted endings, renamed or missing key characters, over-compression, or vague triggers - the core story is recognizably the declared source. Each needs only a targeted correction, not a restage.

| play | scores f/c/p/pl | finding |
|---|---|---|
| sdu001_dykker_klokken | 3/4/4/4 | Andersen's 1827 poem is a satirical undersea journey mocking the world above, but the play softens it into a generic gentle diver-meets-mermaid wonder scene. |
| sdu002_doedningen | 3/4/3/3 | Arc covers only the opening of the 1830 tale (omitting the princess, riddles, and resolution that form its bulk), the second trigger trails off vaguely, and the Stakes contain the anglicism 'to en fremmed' for 'til'. |
| sdu013_det_er_dig_fabelen_sigter_til | 3/3/4/3 | The source is a brief apologue about why fables were invented, but the play invents a forest scene with a 'truth feather', doubles 'Spejl' as both position and piece, and the abstract allegory offers little concrete to direct. |
| sdu014_talismanen | 5/3/4/4 | Arc faithfully renders the happy-man's-shirt tale, but the Company omits the prince and princess who drive the entire arc and both triggers, and 'indseelse' is unidiomatic Danish. |
| sdu017_kejserens_nye_klaeder | 5/5/3/5 | Faithful and well-structured, but the Danish Arc contains an untranslated English word ('they') — a machine-translation artifact. |
| sdu022_rosen_alfen | 3/4/3/3 | In Andersen's tale the girl plants a jasmine sprig (not a rose) over the head, and the Arc has 'lindebraed' for lindetrae plus an untranslated English 'to'; only two triggers compress a multi-scene story. |
| sdu025_storkene | 4/5/3/4 | Untranslated English words in the Danish text ('house', 'to dammen') and 'uger' for 'unger'; original punishes only the boy who began the song, names him Peter, and it is the storks who take the name. |
| sdu047_toogtyvende_aften | 3/4/4/3 | The Tyrol setting and painted saints on house walls are genuine Billedbog imagery, but the devout man with a cross appears invented in place of the original's human subject, and the vignette is a static formulaic tableau. |
| sdu048_femogtyvende_aften | 3/4/4/3 | The chimney-sweep scene is right, but the original's point — the boy's first triumphant climb and joyful 'Hurra!' with waving broom — is replaced by a melancholic daily-toil framing. |
| sdu051_enogtyvende_aften | 4/4/4/3 | The doll-left-in-a-tree vignette matches a genuine Billedbog evening, but the production is a single static tableau with generic moon-template triggers. |
| sdu054_otteogtyvende_aften | 3/4/4/3 | Vreta cloister church with its buried kings is genuine Billedbog material, but the industrious gravedigger protagonist appears invented and the vignette is formulaic. |
| sdu062_en_rose_fra_homers_grav | 3/4/4/4 | Loose retelling: the nightingale who sings itself to death for the rose and the Northern poet who presses it in his book are replaced by a generic poor harp-singer whose songs carry it over the seas. |
| sdu068_snedronningen | 4/4/3/3 | Heavily compressed: the seven-story journey and its helpers (robber girl, prince and princess, Finn woman, reindeer) collapse into one vague trigger, and the arc has the English-calque typo 'to hendes slot'. |
| sdu070_hyldemoer | 4/4/3/4 | Mostly faithful, but the boy's dreamed future life is reframed as an old couple's memory, 'Bedstefar' replaces the old storytelling man, and the arc contains the English-calque typo 'to alderdommens'. |
| sdu074_hyrdinden | 4/4/3/4 | Faithful arc, but the tyrant's name is garbled (Andersen's 'Gedebukkebeens-Overogundergeneralkrigskommandeersergeant'), and the prose slips into English ('Kineser is faldet ned') plus the misspelling 'Tyrand'. |
| sdu078_stoppenaalen | 4/5/3/4 | English-'to' typo in Stakes ('ophøje enhver ulykke to et tegn') smells of machine processing, and the ending swaps the original eggshell/wagon episode for boys mashing her into anachronistic asphalt. |
| sdu079_svovlstikkerne | 4/5/3/5 | Story arc is very faithful, but the declared title is not Andersen's canonical 'Den lille Pige med Svovlstikkerne', and the Arc contains the typo 'For to at holde' (for 'For at holde'). |
| sdu081_et_billede_fra_kastelsvolden | 3/4/3/4 | The veteran-and-child framing goes beyond Andersen's brief prison/bird/sunbeam sketch and looks invented, and a trigger contains the typo 'ankomst to Kastelsvolden'. |
| sdu082_gadeloegten | 4/5/3/4 | Recognizable but simplified retelling of 'Den gamle Gadeløgte' (omits the stars' gift and wax-candle motif), with the typo 'give nyt liv to det' in Stakes. |
| sdu083_nabofamilierne | 3/4/4/3 | Arc genericizes the tale into seasons-and-transience mood, omitting its defining episodes (the fire, the gilded sparrow pecked to death, the roses' afterlife at Thorvaldsen's grave/museum), which also leaves the triggers vague to direct. |
| sdu085_skyggen | 5/5/3/5 | Faithful and stageable, but grammatical slips ('En lærdes mand' in the Arc, 'En lærds mands skygge' in the description) mar the Danish. |
| sdu095_marionetspilleren | 3/4/4/4 | Drops Andersen's frame (the polytechnic candidate's galvanic wish-dream and the showman's relieved return to contented puppetry) and inverts the moral into a puppets-demand-freedom fable. |
| sdu099_der_er_forskjel | 4/5/3/4 | Arc is faithful, but the Danish prose twice uses the English word 'dandelions' and 'to' for 'til' ('kastes dens hovmod to jorden'), a clear machine-translation smell. |
| sdu102_svanereden | 4/5/4/3 | Genericizes Andersen's patriotic allegory (Denmark as the nest, named swans like the Vikings, Tycho Brahe, Thorvaldsen) into abstract swans-bring-honour beats that give a director little concrete to stage. |
| sdu108_hjertesorg | 3/5/4/4 | In Andersen's tale the excluded child outside the gate is a poor little girl, not a boy, and the entrepreneurial 'niece' running admissions is an invention. |
| sdu109_alt_paa_sin_rette_plads | 3/5/4/4 | Heavily compressed: in the original the willow flute is played generations later by a tutor at a manor party (the goose girl never plays it), and the wind's reordering is a passing episode, not a permanent role swap in her lifetime. |
| sdu110_nissen_hos_spekhoekeren | 5/5/3/5 | Very faithful arc, but the Danish has machine-translation artifacts ('en fad grød' for 'et fad grød', 'lister op to studentens loftkammer' with English 'to' for 'til'). |
| sdu111_under_piletraeet | 5/4/3/4 | Arc speaks of honningkagefigurer while the company piece is 'Peberkage', and the Stakes sentence 'kun drømmen og døden kan heles for tabet' is ungrammatical Danish. |
| sdu112_fem_fra_en_aertebaelg | 4/4/3/3 | Prose errors ('Da bælgens sprækkes', the non-word 'viring'), an unexplained 'Urtepotte' piece absent from the arc, and only two triggers that leave the healing arc undirected. |
| sdu114_den_sidste_perle | 3/5/4/4 | In the original the house of mourning holds a widower grieving at his dead wife's deathbed, not a mother mourning her beloved; the arc also contains the typo 'Met' for 'Men'. |
| sdu116_to_jomfruer | 3/4/3/4 | The ending (engagement actually broken, forced labour under the new name) goes beyond Andersen's short dialogue sketch where the rammers keep their name, and 'lade sig ombøde to en livløs ting' is garbled Danish for 'omdøbe til'. |
| sdu117_ved_det_yderste_hav | 3/5/3/4 | In the original the young sailor dreams of home and wakes in God's peace rather than dying with a watching comrade, so the death plot is added; prose also has the English-leak typo 'tilbage to barndommens varme stue'. |
| sdu120_ib_og_lille_christine | 4/4/4/3 | Triggers cover only childhood and departure; the tale's actual resolution (Ib's gold find, Christine's death in poverty, his adoption of her daughter) is blurred into a vague 'vemodig forløsning', and the metaphorical 'Guldhjerte' piece displaces the plot-critical gold treasure. |
| sdu121_aerens_tornevei | 3/4/4/3 | Andersen's tale is a gallery of named historical martyrs of genius (Socrates, Homer, Columbus, Galileo, Jeanne d'Arc, Tycho Brahe); the play abstracts it to a single allegorical 'Geniet' vs 'Verden', losing the tale's structure and leaving little concrete to stage. |
| sdu123_et_stykke_perlesnor | 3/4/4/3 | Keeps only the generic railway-as-pearl-string idea and drops the tale's defining specifics (the six named towns as pearls and the grandmother's slow-journey counterpart), and the boarding/arrival triggers are too thin to direct. |
| sdu124_klokkedybet | 4/4/3/3 | The kernel (bell in Odense Aa, the river man) is right, but the Arc is a single bare sentence, leaving the production underspecified. |
| sdu126_suppe_paa_en_poelsepind | 3/5/4/4 | Collapses Andersen's four mice and the multi-story frame (three returning travellers each telling her tale) into one traveller, losing the tale's central structure though keeping the wit-wins resolution. |
| sdu127_pebersvendens_nathue | 3/3/3/4 | Renames Anton's lost love Molly as 'Marie' and inverts the breakup (in the tale Molly left him, not duty-bound Anton leaving her); a 'Skygge' persona appears in the company but nowhere in the arc; contains the typo 'sua'. |
| sdu129_det_gamle_egetraes_sidste_droem | 3/4/3/4 | Gets the tree's age wrong (356 vs the tale's pointed 365 years), invents a dryad while omitting the mayfly whose one-day life is the tale's core dialogue, and contains the typo 'Metens'. |
| sdu136_taarnvaegteren_ole | 3/5/4/4 | Core setup (tower watchman, philosophical visits, New Year musings) is right, but the farewell/death ending and the 'we all become tower watchmen' moral are invented; Andersen's sketch ends open, promising further visits. |
| sdu139_barnet_i_graven | 4/4/4/3 | Arc is a single sentence that merely repeats the description, leaving the staging thin; it also softens the tale's descent into the grave into a generic 'heavenly revelation'. |
| sdu141_gaardhanen_og_veirhanen | 3/5/4/4 | Keeps the cucumber and the rival cocks, but flattens Andersen's pointed ending (the weathercock snaps off while the yard cock proves actually good for something) into a generic 'both come to nothing' moral. |
| sdu142_deilig | 3/5/4/4 | Omits Sophie and the second marriage that carries Andersen's point, replacing it with an invented artistic redemption at the wife's grave. |
| sdu143_en_historie_fra_klitterne | 3/5/4/4 | Significant distortions: Clara is the Skagen merchant's daughter met in adulthood, she dies in the shipwreck despite Joergen's rescue attempt, and he loses his mind and dies alone in the sand-buried church; the play invents a childhood romance and a shared redemption scene. |
| sdu144_to_broedre | 4/4/4/3 | Captures the Oersted-brothers homage, but the arc is an abstract panegyric with only two vague triggers, too generic to direct as a live production. |
| sdu149_skarnbassen | 3/5/4/4 | Inverts the satire's point: Andersen's beetle returns unrepentant, concluding the horse got golden shoes for the beetle's sake, whereas the play has him humbled and taught his rightful place. |
| sdu153_det_nye_aarhundredes_musa | 3/5/4/4 | The original is a speculative essay wondering when and how the new century's Muse will appear; the concrete descent-journey-spark-handover plot with a specific poet is invented. |
| sdu157_den_gamle_kirkeklokke | 3/4/3/3 | The original is anchored in Marbach and Schiller — the bell rings at the poor boy's birth and is finally melted into the bronze of the Schiller statue — but the play drops the recasting climax, inverts the chronology into a dug-up bell inspiring a generic poet-child, covers the arc with only two triggers, and has a grammatical slip ('forgængelighed mod overfor'). |
| sdu158_soelvskillingen | 5/5/3/4 | Arc is faithful, but the Stakes contain the English word 'to' for Danish 'til' ('vender hjem to dem'), a machine-translation artifact that recurs across this batch. |
| sdu160_theepotten | 5/5/3/4 | Very faithful (riveted lid, degradation to flowerpot, broken up for the bulb), but the Stakes contain the English 'to' for 'til' ('give liv to noget andet'); also the original's ironic 'fineste hånd' becomes a 'klodset hånd'. |
| sdu161_folkesangens_fugl | 4/4/3/2 | The source is a non-narrative prose poem, and the play stays correspondingly abstract: only two vague triggers, an arc of pure generalities ('sangens og vækningens processer', 'historiens vinge'), giving a director almost nothing concrete to stage. |
| sdu165_guldskat | 4/5/3/4 | Arc captures the drummer's son, the rallying drumbeat, and the musical 'golden treasure', though it drops the red-hair motif behind the title; a trigger contains the English 'to' for 'til' ('hjemkomst to moderen'). |
| sdu168_portnerens_soen | 3/4/4/4 | Georg becomes a painter instead of Andersen's architect, and the rescued saddle and masquerade-ball reunion are inventions or distortions of the tale's fire and ball scenes. |
| sdu172_de_smaa_groenne | 3/5/4/4 | Andersen's piece is a brief humorous dialogue about the conceited aphids; the ladybird massacre and near-extinction drama that carries this arc is invented. |
| sdu173_nissen_og_madamen | 4/3/4/4 | Frontmatter description pits the madam's porridge against 'the gardener's verses' while the Arc correctly has the madam herself writing the verses, and the listed Gartner persona never appears in Arc or Triggers. |
| sdu177_ugedagene | 3/4/4/4 | Inverts the source: in Andersen the days can only feast ON leap day, their one free day, whereas here Skuddag crashes and disturbs the party, and the who-is-most-important contest is invented. |
| sdu178_dryaden | 3/4/3/4 | Invents a Faustian devil's pact absent from Andersen (the dryad's wish is granted by fate at the cost of her life) and omits the tree's transplantation to Paris; 'en enkelt dia' is a garbled word for 'dag'. |
| sdu179_laserne | 4/4/2/4 | Untranslated English fragments ('Rags bliver grebet', 'Here gennemgår de') and 'fører to en heftig disput' give the Danish a clear machine-translation smell despite a faithful Danish-Norwegian rag satire. |
| sdu180_herrebladene | 3/4/4/4 | Keeps William, the card castle and the fiery ending, but the clean-hands moralizing sermon is doubtful and the four knaves' tales of their kings and queens, the substance of Andersen's piece, are missing. |
| sdu182_solskins_historier | 3/4/4/3 | Keeps only the wind-interrupts-sunshine frame and drops the embedded sunbeam stories (swan and feather vignettes) that are the tale's substance, leaving triggers abstract and hard to direct. |
| sdu186_hoense_grethes_familie | 4/4/3/3 | English contamination in the Stakes ('forfalde to aske' for 'til aske') smells machine-generated, only two thin triggers, and the title-bearing point that Grethe is Marie Grubbe's descendant (her 'family') is omitted. |
| sdu187_hvad_hele_familien_sagde | 4/4/4/3 | Spirit is right (godfather's 'life is the loveliest fairy tale'), but the two triggers and the 'deep conversation about aging' are abstract and give a director little concrete action to stage. |
| sdu191_danske_folkesagn | 3/4/3/3 | Invents a single narrator-meets-Aamanden frame for what is actually Andersen's collection of retold Danish legends, and the prose carries an English-'to' slip ('soeger to indsamle') plus the muddled phrase 'under den historiske klang'. |
| sdu192_spoerg_amagermoer | 3/4/4/4 | The verse's defining refrain device, asking the Amager market-wife to vouch for the story, is absent from the arc, and the soup-pot demise elaborates beyond what the nonsense poem verifiably contains. |
| sdu195_gartneren_og_herskabet | 5/4/3/4 | Very faithful to the Larsen tale, but the trigger line 'gaesternes ros to de frembragte frugter' uses English 'to' for 'til', a machine-translation smell, and 'Raegetraeer' garbles raagetraeer. |
| sdu196_hvad_gamle_johanne_fortalte | 3/4/4/4 | In Andersen's tale Rasmus actually goes out into the wide world as a journeyman and returns broken; the play inverts this into him fearing the world and choosing passivity at home. |
| sdu199_tante_tandpine | 3/4/4/4 | The student narrator is misnamed Rasmussen (in the tale Brygger Rasmussen is Aunt Mille's old suitor, not the student) and the toothache figure is renamed Madam Tandpine, though the core pact of pain versus poetry is faithful. |
| sdu206_urbanus | 4/4/3/4 | Core of the monk-and-heavenly-bird legend matches Andersen's posthumous 'Urbanus', but the prose has an English-interference typo 'porten to evigheden' and the templated 'moon shines religiously' line. |
| sdu207_kartoflerne | 3/5/4/4 | Andersen's posthumous sketch is about the potato's generations-long journey from mockery and mishandling to recognition; the play invents a cook-versus-famine plot as the vehicle, keeping the theme but not the actual content. |
| sdu210_vor_gamle_skolemester | 4/4/3/3 | The distinctive garden-laid-out-as-a-map-of-Denmark detail matches the memoir sketch, but khai jargon ('realiserer sin plan om dannelse', 'den nostalgiske klang') leaks into the prose and the second trigger ('generations look back') is too vague to stage. |
| sdu402_ot | 3/4/4/4 | In the novel Eva is revealed to be Otto's lost sister and dies; Otto ends with Louise (absent from the Company), so the arc's romantic resolution 'finder kaerlighed hos Eva' misstates the source's central twist. |
| sdu403_spillemand | 4/3/4/4 | The Arc's compound 'Steffen-Kareth' who drowns contradicts the Company, which splits Steffen (blind godfather) and Kareth into two personas; otherwise a faithful digest of Kun en Spillemand incl. the funeral-carriage ending. |
| sdu601_alfsol | 4/3/4/4 | Arc and first trigger hinge on the seeress Vala, who is missing from the Company, and the ending softens Sigurd Ring's legendary suicide into 'evig sorg'; otherwise true to the saga premise of Andersen's 1822 tragedy. |
| sdu603_nicolaitaarn | 3/3/4/4 | The vaudeville's actual love conflict (Ellen torn between two suitors, the tailor and the watchman, with the parterre voting on who wins her) is missing: no suitor personas at all, so a play titled 'Kjaerlighed' has no love interest on the board. |
| sdu609_agnete | 3/5/4/4 | Arc retells the folk ballad rather than Andersen's 1833 dramatic poem, omitting Hemming and Agnete's mother and replacing Andersen's ending (Agnete's death) with a steadfast eternal-separation close. |
| sdu613_usynlige | 4/5/3/4 | The invisibility-hoax premise fits Andersen's dramatic jest, but the prose has a grammatical agreement slip ('begynder overbeviste om sin usynlighed') and character names are unverified. |
| sdu617_maurerpigen | 3/5/4/4 | Setting and heroine match Andersen's 1840 tragedy, but the captured-Moorish-king-reveals-paternity plot and cliff suicide diverge from the play's known ending and are doubtful. |
| sdu619_kongen_droemmer | 5/5/3/4 | Faithful to the 1844 Christian II/Dyveke/Sigbrit dream drama, but the prose contains the anglicism 'fysisk confinement', a clear machine-translation smell. |
| sdu623_ahasverus | 5/4/3/4 | Arc faithfully tracks the 1847 dramatic poem from Golgotha to the New World, but board-vocabulary leakage ('udfører han sin sjælefred plan') breaks the otherwise good Danish prose. |
| sdu625_como_soeen | 5/4/3/4 | Excellent match to Andersen's Manzoni-based libretto (Renzo, Lucia, Don Rodrigo, plague, chastity vow), but process names welded into the arc ('under adskillelsesprocessen', 'under redningsprocessen') give a machine seam to the prose. |
| sdu626_perler_og_guld | 4/3/4/4 | Spirit-king, diamond statue, truthful girl and Vesterbro balloon ride fit the 1849 eventyrkomedie, but the Stakes praise 'sprogets ... sande værdier' where the arc's theme is truth, a small but real contradiction. |
| sdu627_roeskilde | 4/4/3/4 | Plot (two roommates married to the same woman, dice game, liberating death-and-inheritance letter) matches the vaudeville, but clunky coinages like 'postbudskab' and meta-leaks ('under vaudevillespøgens muntre toner') weaken the Danish. |
| sdu628_ole_lukoeie | 4/4/3/4 | Chimney-sweep Christian's dream of riches and the health-over-gold moral fit the 1850 Casino play, but the arc ends in unidiomatic board-speak ('fuldfører hans plan for sand lykke under den glade eventyrkomedie tone'). |
| sdu630_hyldemoer | 3/4/3/3 | Sick boy, elder tea and Phantasus do echo the 1851 phantasy play, but the arc stays abstract (elements, mole-as-reality allegory, unnamed conflict beats) and is too vague to direct concretely. |
| sdu650_oedeland | 5/5/4/3 | Faithfully mirrors Raimund's Der Verschwender (Flottwell, Valentin, Cheristane, Wolf) which Andersen adapted as En Oedeland, but triggers are summary-level rather than concrete stage cues. |
| sdu801_mit_eget_eventyr | 5/4/2/4 | Biographical beats (Siboni audition, Collin/Frederik VI grant, Meisling, Heine, Thorvaldsen, Oersted prophecy, the Grimm snub and reconciliation) are accurate to the autobiography, but the Arc is corrupted by repeated 'to' for 'til', 'sua' for 'sin', and 'mij' for 'mig'. |

## F6 - Mechanical

- `plays/sdu071_elverhoei/plan_elverkongens_gilde.md` and `plan_dovrekongens_rejse.md` are the only two files in the house not referenced from their play hub.

## Suggested order of treatment

1. **F3 calque cleanup** - cheapest, exact file list, one `play/` PR (it edits `plays/**`).
2. **F2 restagings** - 13 plays, each a management order riding a `play/` PR; sdu611 may only need re-declaring its true source.
3. **F1 evening series** - one order covering the series with a shared frame board; largest but most systematic win.
4. **F4 source-verification** - research pass against SDU/ADL before any restage decisions.
5. **F5** - fold individual fixes into future touches of each play.
