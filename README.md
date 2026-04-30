#### story_rpg_platform

# A Rust Story-RPG Platform
Learning From the History of Publishing & Games
https://github.com/lineality/story_rpg_platform 
(under construction) 

A. Terminal
B. Browser (e.g. api for rust application)
C. minimal platform agnostic graphics?
D. Multi-Player Games (And the Distributed-MCU scope)

- not 3-D video combat simulator
- no 'level based' progression

////

Games over the years have suffered from some specific problems:

1. platform and dependencies
- Software often cannot run anymore, with then a scramble for emulation

2. over-reach for trendy fancy UI and graphics

3. Getting lost in-between the known-space of set/fixed narratives and the 'open-sandbox' or 'board-game' space where everything is a user-choice: namely, stories are under-emphasized (or left out entirely) in favor of fancy features that lack a meaningful context without a story.

4. a general lack of modularity and maintainability

5. The visicalc/lotus123 problem of budget-scope unsustainability.

#### Model games that in the past did at least one thing well include:
- Dungeon/Zork: 1977
- Dungeon Master 1987, Eye of the Beholder 1991, Legend of Grimrock 2012
- Hero's Quest 1989 (QFG)
- Elder Scroll's Arena, 1994 (pixel art, story)
- FF IV, 1994
- Elder Scrolls Daggerfall 1996 (pixel art, story)
- Oddworld 1997: Abe's Odyssey 
- Final Fantasy VII 1997 (classic balance of: pixel art, low-resolution, narrative story, side-games, backgrounds, still & animated art scenes, selected user choices and navigation)
- Defender's Quest, Level Up Labs 2012 (simple interface well blended with story & simple-art)
- Dwarf Tower, iosoftware 2014 (pixel, minimal, ediface-architecture)
- 2064 Read Only Memories - Midboss 2015 (exquisite pixel art, minimal interface, deep story)




# Special Mentions:

### Castle Storm
('Castle Storm' is not fabulous or famous game, but it illustrates 'type' of game that is strangely under-represented: empirical architecture)

Castle storm 2013: One element that castle storm got right is the building of individual buildings (as opposed to tower-defense)
Like Dwarf Tower, you are building a physical structure with empirical properties, and the design of the structure empirically works or not. Bridge-simulators are similar and popular, but bridges and setting-location-buildings (with characters in rooms) are not the same. 

I remember when I was young playing a quasi-board-game called (I think) 'Vikings and Barbarians'. It was in part a board game with pieces and logic rules, and in part an entirely physical-empirical game of building physical structures (with physical blocks) to withstand physical impacts.

While there is a side-genre of 'bridge simulator' games, it is strange that empirical architecture is so rarely an element of story-based games (that otherwise seem to fail to add 'mini-games' that usually have nothing to do with the whole and are arbitrary filler). 


### Cloud Punk
Mix of side-scroll pixel and 3D map, good music, very good integration of story and world-puzzles.
An example of a clear minimal scope: one thing (or few things done well


### Plants vs. Zombies
Simple humour stories, simple mechanics and interface.
(possibly this adds 'tower defense' as a 'mini-game' mode


### Undertale & DeltaRune (Toby Fox)
These are arguably examples of effective use of minimal interfaces (though for me the game/gameplay of Undertale seems like an inside-joke for internet gamers where I have no idea what they are joking about (not in the private club I guess...not playing that game)).


### Witcher
I have not played the witcher-games, read any of the witcher-novels, or seen any of the witcher-films/series, but I am vaguely aware of them as an example of a story and character based world where the emphasis on story is key.


# Negative Examples: 
### Shaping the Landscape or Lack thereof
One of the especially story-breaking aspects of Hogwarts Legacy, is that you go around in a sandbox of mob-spawners, where ostensibly there are poachers depleting the population of animals (in the story) but  in reality no matter how many poachers or animals you remove from the world, the numbers of each are static, which just makes no sense and breaks the facade of the story completely. 

### The Degradation of the Elder Scrolls
While the early elder-scrolls games have a wonderful charm to them, the progression of the games includes a lot of cautionary tales.

Redguard was likely an over-reach into fancy graphics that are awkward.

Morrowind is somewhat a good balance, but it is also extremely time consuming to play, as the interface and game-play require a huge time commitment. Morrowind is sort of half-way between a low-resolution story-based text game, and a high-resolution no-narrative sandbox. 

The community-mod aspect of morrowind, including the flexible text-based character-story interface, made morrowind largely modular. (also see the open-morrowind project). 

Oblivion and Skyrim focused more on graphics than story (and ironically Oblivion was a smaller shallower world and had worse graphics than modded-morrowind, making its existence entirely questionable). 

The ever-escallating hardware requirements and ever-shrinking story are a significant departure from the Arena-Daggerfell balance of charming art and story.

This pattern of moving from coherent story-narrative to a 'high resolution battle simulator without a coherent story' also matches Alien's FireTeam, which was mechanically clean but had an almost unbelievable lack of logical-setting around the high-rez explosions. 



Note: There are several examples of a loved-game trying to 'fix' the already good minimal interface by creating a bloated high resolution cacophony (that lacks the story-coherence that people liked originally).



# Modes & Elements

The idea is to combine successful ideas from past games, and specifically reject options and assumptions such as fancy graphics and overly elaborate interfaces.

While a first MVP should not try to include all elements at once, it should try under the hood to plan for future compatibility. 


## Scales
The world should be view-able on different scales:
- Region
- Town
- Ediface/Dungeon
- Room

(note: some locations on a map may simply be one-room-dungeons)


### Side Scroll (2D)

### J-RPG Town (~2D)

### Dungeon View (pseudo 3-D, still frames)

### NxN Grid games
- tic tac toe (3x3)
- checkers (8x8)
- chess (8x8)
- igo (19x19)

### Text Interface

# Maybe, Maybe Not
- CCG card-deck games (though 'avatar as card' makes sense, but seems theoretical at this time): possibly: any choice among action-options is a choice of 'cards'

- visual novel (background + avatar + text): for some 'scenes' this might be a good modular form (e.g. if you walk into a room and see a conversation between two NPC's that is part of the story)


# Strategies
1. Make use of static 'location backgrounds' (perhaps just like physical stage-theater), on which minimal representations are functional. 

2.  Make use of 'avatar-art' to supplement minimalist representations (J-RPG may be the best synthesis of this)
 
3. The blending of 'hand drawn (if pixel)' art with minimal representations, as may be exemplified by the blend of subtle Yoshitaka Amano are with minimal FF games, is preferable to having one intermediate mode between the two (the worst of both worlds). 

Between the 'visual novel' mode of modular background and modular avatars (e.g. a set of emotional expression avatars) and '16-bit game mode' using the avatar in box on a lower-resolution character/object representation (as with ROM-2064), there are various ways to use higher or lower resolution aspects.



# Sport & Sportsmanship


## Chess: Not a model game
- The junkfood psychology of chess, however revered.
- The 'representation' problems of chess and story.

Major flaws.
1. That most games essentially never end (have no clear, clean ending) is a perpetual issue frustrating everyone yet despite being an obvious problem there is a taboo against discussing it.
2. The amount of noise in the game is extremely high, leading to an 'additive gambling psychology' that is more gang-sport than sportsmanship. This is not negative in theory, but this leads to very toxic and pathological language and perhaps psychology from commentators and players.
3. Two of the three phases of a game are essentially broken-designs that do not work.
- The first 20-40 moves of a game are to be pre-memorized.
- The end-game is entirely broken, with most games being a draw or a pedantic very lengthy few-pieces end-game. 
4. The number of kludge-rules and house-rules options are problematic, where even at a top level people cannot figure out what the game-state is: e.g. if an exact board configuration has or has not repeated three times before or after fifty moves having passed with no taken piece or a move of a pawn... etc. Even double-pawn starts and 'en passent' are an arbitrary confusion.
5. The overall enduring culture of the sport, with rare exception, is highly similar to the most toxic internet gaming culture: petty, vindictive, toxic, anti-social, completely lacking in humanity or sportsmanship, both nihilistic and somehow greedy to believe sport-gambling-magic power-fantacies. Chess has become a personification for the utterly pointless waste of using time and energy to passionately fantasize about hurting other people for no reason and to no productive end.
6. The game has no point or coherence: Why are we trying to 'take the king'? What is the point? 


On the other hand there is the 'romanticized chess' of Charles Dodson, The Bladerunner Film, Harry Potter, and early AI academic literature, (to name a scant few) where Chess is seen as embodying a renaissance (interdisciplinary) integration of the humanities, STEM and other areas of broader world engagement. 


# iGo

While this is speculative, and possibly a tangent out of scope, iGo type frameworks (e.g. iGo plus optional distance, plus optional CA-rules, etc.) may represent a viable strategy to allow for world-interactions and world-models within a maintainable computation-cost and interface-cost.

### About iGo
IGo is arguably a kind of game-theory model for equilibria in a system without cost for transportation.
In other words, if you have two 'gradients' and no relative expense for distance, with the only explicit factor being sequence (and where the implicit limiting factor is skill), what are the patterns and outcomes trends for a final distribution of gradient-presence in the problem-space of the game-board (19x19 units), where a gradient-defined space is surrounded but not ruined itself? 
By looking at some examples this may seem strange, because many things are physical-space-cost defined, and time-allocation often is entwined with physical location. 

This presents a modeling puzzle, where is the 'axis' of time on a go-board? Is it the board itself, or the board over time? What does the board represent? 

The clearest examples may be hybrid environments that usually did not exist on a large scale until later in time: tele-communications.


The distance of a phone-call does not matter, only the sequence matters.

A classic example of this may be the outcome of two teams of election-campaigners or sales-teams making calls to a geographically distributed set of households, where there is social-commonality effect between the households: you do not have to sell your product directly to everyone, you just need to manage the boundaries of borders that can shift.


## Cellular Automata, Distance, and the Howart's Legacy Static-Map Problem

While the connection between a 19x19 iGo board and real life cases such as election jerrymandering maps, pizza-shop and coffee shop locations and distributions, investment and stock behaviors (also time-sequence, not space-distance-length, defined), or epidemiology patterns, or predator-prey population distributions, are a bit abstract, the overall point is that real life stories can be coherently connected to something like an iGo formal system or game.

The rules of iGo are what they are, and they are fascinatingly simple and minimal, but to apply an iGo-like system to a game there is no need to only use the single mode of classic iGo.

The rules of iGo are:
1. Any surrounded 'terretory' (or set of connected nodes) that does not have at least two open, un-ruined, spaces, gets removed.
2. You can't kill yourself (known as the 'japanese rule' or 'japanese variant of go,' which I have heard much of the world now uses)


As a note on the 'surrounding' and 'surrounded' nature of territory, I think this entirely makes 'situational' sense using any number of real world analogies:

Examples:
1. A Proper Tea Cup
The point of a tea-cup (or a coffee-mug) is use the least practical amount of 'wall' to 'contain' the desired amount of tea-space (which you might of as: as much of the given size as possible: if you have a 10cm by 10cm range of space (however shaped) to deal with, you want as much of that to be tea as you can. Contrarywise, there are two alternate bad outcomes. A. Your walls are too thick, and the cup is durable but only holes a thimble of tea (or worst-case, no tea at all, just a solid block that can't hold anything), or B. the wall is too thin and it (especially) breaks and spills. 

Between two tea-cup producers, if one tea-cup maker can't strike the right balance in wall-thickness their products won't work. (A kind of fractal-go scenario)

2. The boorish example: 
Imagine there are two groups of soldiers, officers, knights, whathaveyou, who are trying to each contain two villages. Two extreme way that they can fail follow the same mode as: walls to thick or walls too thin. If they replace everyone in the whole village with another knight or officer, then there isn't anyone left in the village to contain: the village was lost. on the 'too thin side,' one officer can't possibly defend an entire region, and that undefended area will lost due to the other extreme. 

3. Administrative support for classrooms:
Two basic ways for administration of a school to fail also follow the 'walls too thick' or 'walls too thin' sets of problems. If you fail in the 'too thick' direction and the school replaces every teacher with a secretary and every room with an administrative office, then the school has no capacity to operate at all. On the other extreme, if you put a bunch of people in a parking lot and say: 'Go ahead, you are teachers now, go do that.' but there are no students, subjects to teach, walls, classrooms, materials, schedules, or resources of any kind, then that isn't going to work either.

Also note that the iGo 'neighbor-rules in time' scenario has much in common with the 'cellular-automata' domain of STEM (somehow part of computer science, systems-theory, game-theory, information-theory, etc., but also mostly a niche abstract domain). Since Von Neuman, much has been studied about cellular automata. 


### iGo-type Scenarios 
The idea is that something like an iGo (perhaps with added distance-costs and other cellular automata (CA) rules) may be a story-compatible way of solving the 'Hogwarts-Legacy static map' problem. 

It is important to have a workable mechanism for having the actions and choices of a player impact events in the 'world-space' of a 'game.'

'Sandbox' type worlds including Minecraft, Hogwarts Legacy, and later ElderScrolls games (and probably many others, perhaps inherently in platforms such as 'unreal engine'), are often non-dynamic settings that focus on extreme detail in areas such as:
1. individual object interactions (picking something up)
2. photo-realistic 3D visual space
3. combat-simulation

(e.g. minecraft focuses on interacting with every block, whereas Unreal focuses on combat and visual modeling).

But neither allows (well) for a population or city-sim type development or degradation of the landscape. 

The idea is to be able to, for the purposes of a story, have a game-compatible set of player-actions and computations that do not involve the super-computers needed to do climate or biological population modeling. 


## The Space Armada iGo Example

Another analogy that may be helpful to see a real-world analogy for the very abstract space of iGo (some intersecting lines, two types of nodes, and two rules) is the Space-Armada iGo Analogy: imagining a scenario where two 'nations' with 'space ships' are vying for zones of territorial influence and have sufficient technology to make distance a non-issue. 

If any 'nation' can send ("beam," "warp," "worm-hole," "star-gate," etc.) any ship anywhere, how does that play out in terms of territory? What matters is where you send resources, not the relative logistical cost of getting something there: not a race to plant a symbolic flag.

Layers on Layers of Tactics and Strategy:
This minimalist removal of transportation costs certainly makes iGo unlike the many cases where logistics are either significant in the problem space or effectively define most or all of the problem space. But it is interesting to separate logistical and edge-case tactics from overall deeper strategy. In the short term, tactical details can "win" something. But there is often a strategic level (or more than one) even where tactics are short term decisive. 

In iGo-space, long term dynamics are emphasized and short term tactical details are ignored entirely (could one ship occasionally fend off ten others? yes, but in iGo (rightly or wrongly) this is ignored as a marginal edge case).
 
IGo is not a space of noise and incidental advantage. There are no dice-rolls or random card picks; iGo is an administrative competence game.

And in some cases removing spatial distance might be more realistic in the long term. Perhaps as with the market-analogy, (in the long term) any nation or company can open an office or send a ship anywhere. The question is: Do they have the skills to make that work in that location in the long term?

Igo is about shaping and maintaining spaces defined by local configurations and neighbor-rules (as with cellular-automata, and perhaps cultural/linguistic-proximity). 


## Adding Space and more 'roles' to iGo

While the scope and rules of iGo are fascinatingly minimal and abstract (two rules, real world situations with distances abstracted away, etc.) for overall world-game design there is no requirement to only use this most minimal form of an igo-space.

Specifically, spatial-distance and other roles-&-rules can easily be added.
For example, you can only place an abstract-role-piece within N (say, 5 spaces from an existing space (or, from an 'eye,' ~an in-tact space in your territory). This combines the idea of giving more 'neighbor rules' to configurations of pieces with the specific goals of adding a cost for distance.

For us the puzzle is how to maintain an emphasis on story, art, and process, supported by a game-framework, without a collapse of the enterprise into decontextualized battle tactics (devoid of story) or completely abstract "level" progress (in the absence of any meaning or implication of "level").

As with the sport vs. sportsmanship problems with chess and other digital-computer games, there is a strong tendency for players to be attracted into getting stuck in bad-equilibria of short term super-signal thrill seeking that leads away from the interconnected worlds of stories, art, literatures, culture, language, meaning, and into the nihilistic vacuum of blind-addiction, cosersive-violence, and unconscious destruction. 

The tendency for people to become addicted to gambling, joining gangs, joining cults, senseless substance abuse, antisocial behavior, etc., is a gauntlet of design obstacles. These are obstacles to survival that if not avoided will destroy the game-world and art-story curation, not 'try everything' 'culturally-relative' neutralities to casually put into a game for the fire-works fun of seeing 'viral' pathological behaviors for the sake of doing so.

The mindless nihilistic firehose of disinformation will endlessly tell you that all stories and worlds are meaningless violence addictions (and also that everything including meaningless violent addictions are equally sustainable family friendly options that everyone should try). It takes dedication and skill to navigate the pitfalls in the landscape of language and meaning.



# The LitRPG-Novels Paradox:

It is strange that there are story-based novels that are set in, or about, games that themselves conspicuously lack meaningful stories. In the case of Matt Dinniman, the stories are most popular as physical books that are more popular than any of the referenced video-games (thirty years after books were supposed to have been entirely replaced by video-games). And in the case of Dinniman, the stories clearly criticize the anti-social 'story-less' 'meaning-less' nature of games and gaming culture.

I remember that in the time period from 1996-2026, there was a genuine question of how 'Science-Fiction' the future would be. It was genuinely unknown if there would be newspapers, books, cities, jobs, computers, schools, governments, money, etc. It seemed likely, more than remotely possible, that everything about life would be replaced or significantly altered in a VR-Mobile blending of digital and physical world. But by 2026, at least the first 'push' into "digital-transformation" was a failure that mostly resulted in a large mess made for traditional forms to recover and clean up; and that it was a 'push' by people with half-baked plans rather than an inevitable evolution (to a more-stable equilibrium). 

Arguably, novels such as Dungeon Crawler Carl and perhaps the Witcher fantasy novels, not echos of Tron and Ready-Player-One, both of which were popular (or cult-classic popular) but were more about 'fans of the technology' rather than being traditional romantic humanistic novels.

This seemingly indicates that there is a fundamental story-literary part of language and society that is NOT being adequately interfaced with by digital-media.

In phase one, we were told that digital media would include culture and the arts: e.g. From Marshall McLuhan to the early days of the journal Wired.

In phase two, digital media failed to include culture arts and language.

In phase three, traditional human arts of songs and story telling reflect on a failed daliance with digital media. 

One key question is whether digital-media are inherently incapable of including literature and the arts, or it was a combination of problems:

1. Bad engineering (various software failures and horrendous design failures)

2. Insufficient hardware and software development

3. A general lack of education and social capacity for education: in theory nothing is stopping chimpanzees, bonobos, dolphins, and octopi from using the internet for their societies, but clearly they are not doing so.

4. Cost: The investment needed for a painter to paint a painting or a novelist to write a novel (or other book) was barely affordable. The term 'struggling artist' applies not only to writers such as J.K.Rowling (and perhaps most of the authors we now see as indispensable contributors to mind and language) but also to retrospectively revered historians such as William L. Shirer who faced the same situation while writing 'The Rise and Fall of the Third Reich,' he was essentially starving to death to get the book researched and written while being trolled by every publisher that no one wanted to read his stupid book, not to mention other scientists and researchers who often work in obscurity. This kind of retroactive-interest cannot support the significant software development that would be needed to make a truly deep interactive digital novel.

#### Moving in the Other Direction
The Witcher Game and The Witcher Novels & "Films"

Fortnight (American Arena Battle Game) -> Arcane (French Film Series)


# The Unspoken Challenge of Table-Top Gaming for 'Video' (or 'TV') Games

Table top games, either typified by or most popularly associated with the classic Dungeons & Dragons game, where a single book-sized box contained everything a small group of people needed to make and act out their own story. Parts of the original 'table top' gaming world included:
- oral story telling
- dice roles
- tables of data
- 'character-sheet' dashboards of data reporting
- visual artwork 
- and game-mechanics rules



One important question is: was this a novel-like story of characters with all the inclusions of literature and the arts, or was this a battle-simulator or context-free number generator that contained no story per se? My understanding is that devolving into uneducated violence (on various levels) has been a persistent problem for tabletop gaming.

The simple-elegance of original D&D might fall into the John McCarthy 'Easy things are hard' category. The thrifty means of basic rules, basic guidebook, a few fun dice, and basic character-sheet, was a maintainable way for people to create worlds and stories. How difficult would it be to put those same elements into a digital form?

One of the most difficult elements to replace may be the person running the game (sometimes called the dungeon-master or game-master, DM or GM), and it may not be entirely understood how this is a challenge. For example, a naive attempt at this might be 'let Brand-XYZ AI Chatbot do it,' which might cover individual 'tasks' such as 'What does this NPC say?' or 'Which monster is in the room?' but it does not at all solve the 'game state' problem, because as of 2026 generative AI are inherently state-less: you cannot solve a state problem with a stateless technology.


## "mini-games"
- NxN
- FF-Battle
- Side Scroll
- Tower Defense
- physics-builder
- crafting: spellcraft, potioncraft, objectcraft



## Puzzles, Stories, and Combat

- skills vs. stats
- world-puzzles
- world-objects
- 



Q: Minimalizing a J-RPG/FF 'battle'
and-or generalizing to other encounters

...


## Another technically tricky issue is 'multi-player'

where high resolution multi-player games are
A. combat-simulators (not the goals here at all)
B. bloated and too compute intensive


Whereas, it should be possible to have multiple players in a lower resolution setting where the data to be exchanged were far fewer map/object items and their state data.





# Shakespeare & Co.

Case Studies:
1. Trying to turn Shakespeare plays into navigable worlds (not trivial)
2. Monty Python vs. 'the monty python game' (not effective)
3. X-Files vs. the X-Files game (not effective)
4. Blade Runner, vs. The Bladerunner Game (not effective)
5. 
6. Stranger-Things and the Minecraft Stranger-Things Game (counter-example: as usual minecraft is an effective minimal mode)




The dearth of story in games, and 'LitRPG' Novels



# World Objects

- scale
- the 'river of numbers'
- 

................


Grinding to Level Up

Mini Games

"Side-Quest" & "Monster of the Week": Why derided?

...

...

# Discussions


### Chess and Tabletop Gaming

While I do not think that chess is a good game, and should be called out more for its various problems, Chess is often an excellent topic and example for discussion. 

As an example to compare with the juxtaposition of pencil and paper tabletop gaming vs. digital computer based RPG games, chess presents an interesting minimal design and interface challenge. 

Case: 
Correspondence-Chess has for centuries or millenia been something that people have done using any technology that record moves for each person (e.g. each player has a chess board) and some way to convey what your next/last move is/was: I moved here. (There are various forms of more or less ambiguous notation in use, e.g. https://www.chess.com/terms/chess-notation) 

The other day, to continue a game started during travel, a family member sent me a photo of the board, showing his last move, with the simple message: "Your move."

This extremely simple, and historically ancient, gesture was a kind of anti-epiphony for me: For all of the assumed omnipotence of computers and the internet, how is the only/best way to play correspondence-chess in the super-beyond-science-fiction age of the 2020's (envisioned during the preceding century and more as being full of technology and means beyond comprehension and fantasy) a kludge the bypasses any technology at all: sketch a picture of the board and brute-force send-it.

(As part of this exploration I built a few experimental chess servers (first in python, then in Rust) to explore how this could be better done.)

See: https://www.chess.com/terms/chess-notation

The result of which was calling into question the whole way that the internet is used.

This, and the Uma project (see: T is for Task (also a work in progress), outlines yet more issues with how seemingly simple game-logistics problems are approached. 

A repeating theme is that people create ever larger and growing stacks of erroneous solutions, and get so lost in the drama of those bad solutions, that perspective on persistent historical, timeless, and future real design scope becomes hopelessly obscured. The depth of this dysfunction should not be underestimated, such as where potemkin villages and overt hostility to the basic concept of pointing out issues-and-problems, and a self-destructive culture of nihilistically attacking assets and cultivating liabilities knowingly is a set of problems that a persistent in part because people are unable or unwilling to recognize and document that those problems are both possible and real. 

Other notes on toxicity in chess-culture:
1. Russian Vladimir Kramnik hounding beloved kind Danya Naradidski to death (yes, to death when Danya was still in his 20s)
2. Chess as a tool in war against Europe and Good-Governance https://www.youtube.com/watch?v=0WXUlcca8-Y 
Apr 27, 2026 4 years and 62-days since the full scale invasion began.


...

more fireteam elite commentary


...


To be clear:

the entire paradigm of 

putting unstable, incomprehensible, stacks of 3rd party dependencies into dockerized Kubernetes virtual servers on the public internet with js/ts web mobile app interfaces, unsustainable and unmaintainable without either agressive distruptive advertising and or rediculous subscription fees (not the tiny micro-transactions people have been asking for since the at least the 1990s, probably the 1960s) is entirely wrong. 

I am sympathetic to it being wrong, in the same way that the 'churches of science' in the French Revolution of 1791 were wrong: it was early days, STEM wasn't evolved enough, it was an understandable mistake, but it was fully wrong period. 

The same with internet-version-1: Even in the software world the pattern is, (As Steve Gibson has reported) "1. Built it, 2. Build it better. 3. Build it right." It should be expected to take at least three completely from scratch builds/rebuilds for a design to be expected to possibly be coherent. 

Again, this is not a trolling criticism of the 


...



...

The minecraft story-gap problem

...

Who Shakespeare Puzzles

'world of shakespeare'
choose your own adventure-shakespeare

1. a big folio, but only one folio: weaknesses

2. mechanics of situations: strengths

stateful stories and games: "Shakespeare" and Thomas Hobbes




...


Modes:

1. fully preset story game (pre-set interaction choices)
2. Dynamic game world (e.g. iGo scenario modeling)
2. semi-generated content
3. fully automated GM story writer role

Interactive modes: (still, a focus on story)
4. multi-writer story worlds
5. Multi-writer plus story worlds

Note: completely random is technically an option but that is not considered here, e.g. a table-top game where virtually everything is randomly decided (which in the extreme replaces not only the GM but also the players)


...

mozaic of elements:

"side-quests" are the 'narrative stories'







...
ROM 2064:
- sense of place
- subtle character relationships (non-book-novel closest)
- 

...

sim-city and sid meyers civilizations:

A. no story
B. no strategic level maintainability in dynamic interplay

1. abstract tactics and combat
vs.
2. abstract static sandbox (abstract 'levels' may fit here)
vs.
3. narrative story
vs.
4. dynamic-outcomes




...
Hypothetical outcome-based modular story plot:
...




art note about realism:
- 
- 
- 

...
dishonpored, oil painting,
'uncanny vary'

not photo-realism

zork:
- inspiring imagination vs. showing


quest for glory 4: voiced


allan commings



...

Minimal Interface:

Based on the excellent ROM-2064 design:
there may be three or four options for player interaction with a 'game-object'
1. Look at
2. Use something in your inventory with/for/on this 'object'
3. Pick up / Interact with this object.

This can work as a pop-up choice (or choice-tree), so there is no elaborate key-shortcut system needed to be memorized. 

...

## Thought Experiment: The world of 'morrow-wind' but taken in a different direction, not photo-realistic combat simulator VR.

What would be the pros and cons of leaning into a text, still-art, and impressionistic mode of interface, and to deliberately avoid the rabbit-hole of ever more expensive and less maintainable (and less artistically rich) hi-resolution VR 1:1 simulation. 

What parts of (what parts of) the experience of playing morrow-wind would be potentially helped or hindered by going in this or that direction?


- more options
- possibly alternative art-styles for the stills and avatars (e.g. as a mod-able area)

- 



- more 'organization tools' to help manage quests


...

Probably a tangent...

Project areas, definition collapse, and tractable areas for both stories and how to scaffold how a choose-you-own-adventure could become a dynamic tree.

... 

Basic tensions:

1. an open-sandbox has no curated stories

2. curated stories have no open-sandbox

3. key choices should 'matter' and shape the world and future events.
But choose-your-own-adventure trees are overly expensive and unmaintainable.

How can these be integrated together?


Bad Graphics Make Better Games, Actually
Juniper Dev
https://www.youtube.com/watch?v=-tNvoDw7Pq4 


...

Books in Elderscrolls (Games)
https://www.youtube.com/watch?v=k_pvWTP2lL8 
...


Time Tracking Tabletop
https://www.youtube.com/watch?v=zyl73XLJWhE&t=430s 
