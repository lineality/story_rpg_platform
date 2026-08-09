#### story_rpg_platform
(under construction) 

A Rust Story-RPG Platform
Learning From the History of Publishing & Games
https://github.com/lineality/story_rpg_platform 

see: https://github.com/stemnetbenchmarks/social_story_and_cookbook_puzzles 

A. Terminal
B. Browser (e.g. api for rust application)
C. minimal platform agnostic graphics?
D. Multi-Player Games (And the Distributed-MCU scope)

- not 3-D video combat simulator
- no 'level based' progression

////

- map levels modules: nested-regions, town, interior
- dungeon-room module
- dungeon-halls module (Grimrock-ish)
- platformer module (Abe's Odyssey inspired)
- maybe j-RPG map, simplified

- pixel / ~visual-novel module (more ROM-2064 than anime-style)

- map-level-game, iGo
- 2D

- 


////

McLuhan et al

The stories of French Impressionism in Painting & German Expressionism in Film, and modular-expression in Japanese art forms from Jyoruri to Manga to Anime.

...

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

While there is a side-genre of 'bridge simulator' games, it is strange that empirical architecture is so rarely an element of story-based games (that otherwise seem to fail to meaningfully add 'mini-games,' instead adding non-sequitor games that no clear connection to the whole and are (blatantly) arbitrary filler). 


### Cloud Punk
Mix of side-scroll pixel and 3D map, good music, very good integration of story and world-puzzles.
An example of a clear minimal scope: one thing (or few things done well

Notes: some of the voice-acting was exceptionally bad, to the point that maybe that was deliberate? (maybe another part of the argument about how voice-acting maybe too expensive)


### Plants vs. Zombies
Simple humour stories, simple mechanics and interface.
(possibly this adds 'tower defense' as a 'mini-game' mode


### Undertale & DeltaRune (Toby Fox)
These are arguably examples of effective use of minimal interfaces (though for me the game/gameplay of Undertale seems like an inside-joke for internet gamers where I have no idea what they are joking about). 


### Witcher
I have not played the witcher-games, read any of the witcher-novels, or seen any of the witcher-films/series, but I am vaguely aware of them as an example of a story and character based world where the emphasis on story is key. I think this started as a game and then grew to become books, ~films, etc. 


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

#### Open-Morrowwind and Skywind: Resources & Modding

There are so many fascinating aspects to the official and fan-mod world of Elderscrolls. 

Extended Morrowind vs. Skywind

Game-play vs. ever more photo-realistic graphics. 

OS-compatibility

How many years did it take to re-create vanilla morrowind in the skyrim game-engine,
vs. the modularity of extended morrowind
vs. the rather sorry-state of character and story depth in the whole sandcastle of cards.




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

In contrast to Chess, iGo is a game, and represents a type or class of games, that can much more concretely be associated with spatial and temporal dynamics and behaviors across empirical phenomena.

iGo type frameworks (e.g. iGo plus optional distance, plus optional CA-rules, etc.) may represent a viable strategy to allow for world-interactions and world-models within a maintainable computation-cost and interface-cost.

### About iGo
IGo is arguably a kind of game-theory model for equilibria in a system without cost for transportation.
In other words, if you have two 'gradients' and no relative expense for distance, with the only explicit factor being sequence (and where the implicit limiting factor is 'fittness'), what are the pattern and outcome trends for a final distribution of interactive gradient-defined presence in the problem-space of the game-board (19x19 units), where a gradient-defined presence-in-space or owned-space or 'domain of control' is surrounded but not ruined by the process of administration? 

From looking at some examples this may seem strange, because many real-world things are physical-space-cost defined, and time-allocation often is entwined with physical location. 

This presents a modeling puzzle, where is the 'axis' of time on a go-board? Is it the board itself, or is the board over time? What does the board represent? 

The clearest examples may be hybrid environments that usually did not exist on a large scale until later in history: We could look at processes that occurred before or after electronic telecommunications, where processes after the invention of telecommunications may more directly resemble 'igo-space Models.' 


The distance of a phone-call does not matter, only the sequence matters.

A classic example of this may be the outcome of two teams of election-campaigners or sales-teams making calls to a geographically distributed set of households, where there is social-commonality effect between the households: you do not have to sell your product directly to everyone, you just need to manage the boundaries of borders that can shift. And election-calls may be a good example because you can imagine a bell-curve norm where there is no 'speed' advantage or resource advantage, each side effectively has the same resources and the more skillful side takes more territory. 


## Cellular Automata, Distance, and the Howart's Legacy Static-Map Problem

While the connection between a 19x19 iGo board and real life cases such as election jerrymandering maps, pizza-shop and coffee shop locations and distributions, investment and stock behaviors (also time-sequence, not space-distance-length, defined), or epidemiology patterns, or predator-prey population distributions, are a bit abstract, the overall point is that real life stories can be coherently connected to something like an iGo formal system or game.

The rules of iGo itself are what they are, and they are fascinatingly simple and minimal, but to apply an iGo-like system to a game there is no need to only use the single mode of classic iGo.

The standard rules of iGo (I am not aware of any use of other rules) are:
1. Any surrounded 'terretory' (or set of connected nodes) that does not have at least two open, un-ruined, spaces, ("eyes") get taken by the other player (off the board).
2. You are not allowed kill yourself, you cannot cause your own pieces to be surrounded and taken (known as 'the japanese rule' or 'japanese variant of go,' which I think the whole world now uses).


As a note on the 'surrounding' and 'surrounded' nature of territory, I think this entirely makes 'situational' sense using any number of real world analogies:

Examples:
1. A Proper Tea Cup
The point of a tea-cup (or a coffee-mug) is to use the least practical amount of 'wall' to 'contain' the desired amount of tea-space (which you might of as: as much of the given size as possible: if you have a 10cm by 10cm range of space (however shaped) to deal with, you want as much of that to be tea as you can. Contrarywise, there are two alternate bad outcomes. A. Your walls are too thick, and the cup is durable but only holds a drop of tea (or worst-case, no tea at all, just a solid block that can't hold anything), or B. the wall is too thin and it (especially) breaks and spills. These are exactly the failure-extremes in iGo that you are trying to navigate between.

Between two tea-cup producers, if one tea-cup maker cannot strike the right balance in wall-thickness then their products will not work or perform as well: a measure of fittness. (A kind of fractal-go scenario)

2. The boorish example: 
Imagine there are two groups of soldiers, officers, knights, whathaveyou, who are trying to each contain villages. Two extreme ways that they can fail follow the same mode as: "walls too thick" or "walls too thin." If they replace everyone in the whole village with another knight or officer, then there isn't anyone left in the village to contain: the village was lost. On the 'too thin' side, one officer can't possibly defend an entire region, and that under-defended area will be lost due to the other extreme. 

3. Administrative support for classrooms:
Two basic ways for administration of a school to fail also follow the 'walls too thick' or 'walls too thin' sets of problems. If you fail in the 'too thick' direction and the school replaces every teacher with a secretary and every room with an administrative office, then the school has no capacity to operate at all. On the other extreme, if you put a bunch of people in a parking lot and say: 'Go ahead, you are teachers now, go do that.' but there are no students, subjects to teach, walls, classrooms, materials, schedules, or resources of any kind, then that isn't going to work either.


### Neighbor Rules 
Also note that the iGo 'neighbor-rules in time' scenario has much in common with the 'cellular-automata' domain of STEM (somehow part of computer science, systems-theory, game-theory, information-theory, etc., but also mostly a niche abstract domain). Since Von Neuman, much has been studied about cellular automata. 

From epidemiology to cellular automata, neighbor-rules are a potential way to have user-influenced dynamic environmental outcomes within a game-world that are (potentially) computationally easy to manage. 


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




...



(Possible) Roots of RPG:


Gigax

Tolkien

Jung's Redbook

Joyce, Campbell & 'Mythology'

Charles Dodson's Teaching Style

The Goblin Market

Detective-Mysteries

Linked-Verse

Japanese Shrine-Geometry puzzles

Chorus in the Theater

Campfire Stories

Music and Song in Tokien & Shakspeare

Puzzle and antics in detective Noh and humourous Kyogen

From Heikei to Jyoruri to Manga to Anime to Games



...

And a thought experiment, how could we approach: "morrowind in minecraft"?

The problem is not that morrowind did not have graphics as 'high-resolution' as skyrim, the problem is in the other direction as shown by how long it takes to build a story-world like just-vanilla-morrowind with a high-resolution game engine: the problem is that the graphics of vanilla morrowind are too fancy to be maintainable.

E.g. along these lines, the modularity of text-dialogue with NPC is very modular and easy to build with. A studio-audio dialogue system makes it prohibitively difficult and expensive to develop.


A. By looking at the task of putting the morrowind story-world into a minecraft interface, we can see how (perhaps strangely) minecraft has no NPC dialogue or NPC/quest features (though probably that would not be a cumbersome addition (compared with other updates that original minecraft has gotten)). 


B. Simpler than minecraft: 2d- side scroll

How could we reflect a 3-D map in a D2 side-scroll?

another example here may be pixel-art CloudPunk where there are (I think) two modes: 1. fly over map 2. walk along side-scroll line of map. Where the map is 3D, but the walking interface is a lovely side-scroll.



...



Comments on Dispatch:

# Overall:

There are a few scenes that are very successful and story-based, and a few techniques of integrating story and game-play that are successful. These alone are good enough to make the game worth partially playing through, and definitely worth studying and experimenting with. The game has so many problems that overall it is, while perhaps the 'the cleanest dirty shirt in the laundry,' poorly executed with obvious overwhelming problems. The game is far from unplayable, but the many shortcomings are in stark contrast to the successes.

Nevertheless, the scattered elements of success are very noteworthy, and evidently for a significant number of players are 'good enough' to make the game play-able. 

I would say that Dispatch contributes to the case made here more broadly:
1. More high quality narrative story and character development makes the world/game better.
2. Integration of game-play and narrative story is possible.
3. The scope-explosion of branching-story lines needs to be managed very carefully.
4. A photo-realistic first person sandbox is not required for a game.
5. The classic grammar of story, visual novel, high definition avatar-cards, and low-definition interfaces, trace out some (not to say all) best practice game-making.


Part of the backdrop of this is that running a game-studio is virtually impossible. That the makers of dispatch were able to make the game, build and ship, get it to market, have it be well-received, pay the bills, and live to kludge another day, may be the most we can ever ask for; this mixed-result is as good as success is likely to ever possibly be. I think this may be 'try two' for the previously imploded 'telltale games' studio that was loved but did not survive the sustainability-maintainability challenges and they went out of business. I am curious to hear comments from the game-makers; maybe they would say 'this is exactly what we planned' or maybe they would say 'this isn't what we hoped for but it's all we have time and money for' and likely different people will give very different answers and there needs to be some mishmash of all those guiding voices. 

The software development costs are a significant part of this space and a part of the focus of this paper: how and where story-game development and publishing can be sustainable and maintainable.


# Details:

Dispatch, 2025, is an experiment with mixed results.

On the one hand it represents a positive example of the patterns discussed here:
- core-story mode, not open-sandbox mode
- in some ways managing the scope-explosion of a branching story-tree
- overlaying play-able 'mini-games' over the core story
- (semantics aside) more like a gamified visual-novel than FF-7 (where the story-scenes are sparse, very separate from game play, and not-interactive)


What various people like about the game is in some ways ~subjective and hard to pin down. But we should be able to discuss Dispatch in a way that focuses on definable items that allow us to more generally describe 'good game design,' without veering off into arbitrary aesthetic preferences. I would argue that there are concrete and consistent statements that we can make. For example, while surely 'a particular favorite character' will be variable and 'subjective,' but that their well developed characters (as a game-design feature) is not arbitrary or up for debate.


We should be able to concretely make statements such as these:

- deep story and character development is a strong point. 
- more coherent story and character development is a plus
- where story and character development were thin, failed, or incoherent, was a minus

'Favorite part' is arbitrary and fuzzy. That dispatch is not a first-person-shooter is not arbitrary and subjective. 

Other areas would be interesting to explore in terms of how much agreement there may be (or not be). For example, unlike a sort of turn-based traditional visual novel (though there can be continuous scene dialogue progression in some visual novels) the dialogue choices for Dispatch were made in real-time, with an arguably adequate balance of giving enough time to decide with no pause in the dialogue. This might be an area of broad approval (...or perhaps the opposite). 


On a separate track I want to comment on some point (which may or may not have any general agreement).


1. The CCG-like main dispatch game was excellent, a kind of nested game within a story, in which mini-stories were embedded, (and in which mini-games were inserted in those).

2. The computer-hacker mini-games were a near total failure. They were so extremely arbitrary that it made no sense and was a confusing waste of time. E.g. Press a random combination of arrow keys (for absolutely no reason)... ok... Why is this happening? And there is never any connection to anything in the story (or in the realm of logic). To me this was a missed-opportunity. There could have been optional engineering-puzzles, either abstract or game related, but it seemed like they deliberately had no logic to the 'puzzles' in order to make them 'easy and accessible to players who just want to push a button and blow something up.' This may also be ironically inconsistent with the point of the game: players who don't want to think about a story are already not going to like the game. Having a sub-game that is devoid of thinking, in a game that exists to be a thought-provoking-story, seems like a very odd choice, like putting a shoe-store inside a restaurant because maybe someone knowingly came into the restaurant but isn't looking for food (it's a restaurant!). 

3. The issue of needing to fire someone at the beginning of the game.
To me this was in between being another missed-opportunity and being a planning failure stark enough to be called a bug. The drama about the obviously bad decision to fire someone without even having a coherent reason to do so could have been either a main story-line of the game or even the main story line of the game: what the impact was for the team, what the impact was on that NPC, what the impact was on SDN, what the impact was on the criminal-world, and the story-line of that person potentially rejoining SDN. That would be an excellent and coherent story (which could have some branching options (e.g. player-choices)). What happened instead was a completely incoherent word salad of 'this needs to happen!' and 'that was terrible' and 'we still had to do it!' and 'we also need to undo it!' with, amazingly, zero story-coverage of any of that story (just the events happening incoherently in the background with characters saying contradictory things about it: e.g. the flexible Player-character at first chooses to say if they think it is a good idea or not (if unclearly), but then later automatically says that firing someone for no reason had to be done.). 



4. Arguably, overall, episodes 1-6 are excellent or contain a great number of excellent elements.


5. Episodes 7 and 8:
Probably everyone knows of a serial drama that they like where the first season is amazing and the second season is disturbingly incoherent and should never have been made. I think of episodes 1-6 as season-1 of dispatch (highly recommended), where episodes 7-8 are the deranged production-failure that is a season-2 that should never have been made (not recommended in any way). 

Related to #3 above:
A branch related to the first firing is the also amazingly incoherent handling of firing of Visigal. Malevola, the one character so upset at randoming firing the Bat character that she dropped out of the next round of play in protest, was the most adamant that Visi be fired (with no explanation or clue as to why). 

The entire game up to the episode 7 is creating a sympathetic bond with Visi, then, even after Mandy-Blazer says that she isn't saying that Visi should be fired, all but ~two (it's unclear) characters are acting like Chase made a mistake by helping and wanting her off the team. And the moral on the team drops when you do not fire her... with no explanation of why.

The entire arc of episodes 1-6 is, without any explanation, completely contradicted.

Episode 8 is a festival of nonsense. 
- the fighting is illogical
- the story is illogical

The "Visi was a double-agent" did not make sense, in a dis-joined story way similar to how a badly written sequel will ignore events that happened in earlier parts.

And the 'all knowing villain' made no sense and had no story or character development. 

Maybe some people liked the 'final boss battle,' and the fun made up for the lack of logic. 

...

- The whole 'astro-pulse' can't be reproduced because of size is utterly nonsensical and unnecessary.

- The 'testing in the lab' is utterly nonsensical and unnecessary.


...
missed opportunities:
- Flambe's character development to the point of coming to mechman's housewarming party with a housewarming present, is a HUGE character development... and nothing is done with it.

- The opening scene has great potential with 'toxic' being a Frenimy, but nothing is done with it.

- There are aspects of Coupe's character that are great, but mostly completely undeveloped. (maybe sloppily set up as a half-developed villain track?) this might be a case where 'choice' is the wrong option

- No 'previous generation' development (opportunity, and nothing done with it). 


...

The water-boy character is problematic in the same way as the artificial bad-language. It appears that the only reason why his character is in the game is for the player to bully and mock him, even though he is a good person. This is ethically wrong and conspicuously nonsensical in the context of the game. Artificially keeping water-boy as a permanently superficial undeveloped joke character leads to a cynical and sinister overall pattern, though it was more likely sloppy planning.

...

The hyperbolic 'bad language' is so extreme that it is a problem:

1. This game is obviously targeted at children, which makes the 'deliberate bad language' a suspiciously bad choice.

2. The arbitrary extreme 'bad language' everywhere is so common that A. it is annoying, B. when you bleep it out, so much of what is said is bleeped out that in various scenes you cannot understand what people are saying, which is absurd. I have never heard real human language like this; again, not one scene in context, but the entire game is like this. Is this a very sloppy attempt to artificially insert 'grit' because of a C-suite directive that "we need more grit because grit sells! So, just add grit-ness everywhere! Sell sell sell! More Grit!"?

The game is good because of where the story and characters make sense and have depth, not because of places where the story and characters are superficial and nonsensical. The entire point of a story based game is to focus on meaningful (non-arbitrary) characters and story.

For example, in the case of 'Chase' his 'bad language' is part of his character and funny and makes sense (because it is contextually ridiculous), but having every character use artificially bad language everywhere regardless of context is confusing and meaningless. For example, Blaze reacts to and comments on Chase's bad language with sympathetic exasperation: which is good contextual story-writing and makes sense and accentuates Chase's character (and the funny bad language). But where everyone uses as much bad language as Chase arbitrarily, and Blazer mysteriously doesn't comment on anyone else's bad language, that makes the overall scenario muddled and arbitrary and meaningless. 



"... will remember that"

I do not know if this was by design or a necessary mixed-result, but the alert that your choice of action "will be remembered" (and so has an impact on the story) was frustratingly vague, in the same way that a badly written multiple-guess exam is stressful where each option is word-mush that all mean arguably the same thing, but you know
A. that the teacher will personally and subjectively invent very unique meanings for each mush, 
B. that you will never the find out what those meanings are, 
C. that the future is determined by those secret interpretations, and 
D. even in retrospect the threads of connection appear random


While such a story-game system will never be completely clear to everyone equally in this regard, and while a few choices were (probably?) clear in terms of picking a character to take the side of, I think too many of the situations were too ambiguous.

A story-breaking example for me was where everything in the story pointed to the question of 'do you show positive support for the z-team or not' and then you finally convince Chase to support them too, and then when you choose to support them again... and they 'will remember that,' the effect was for morale to drop and everyone to lose motivation and cohesion, which makes no sense and is never explained.

Another more specific instance is when you can either tell Golem to look where he's walking (which you do VERY politely) or say nothing. This is one of those 'he will remember that!' situations... but what on earth is he remembering? And the choice-prompt of 'tell him to look where he's going' sounds like it is going to be aggressive, but what you end up saying is very kind... and there is no way to ever know how the game-system evaluates him 'remembering that,' it is very very ambiguous. 
E.g. He remembered you carefully advised him? or He remembered that you (contrary to the voice acting) rudely insulted him? or He remembered that you stood-up-for-yourself? Or He remembered that you were thin-skinned over something petty? And there is no way to ever find out (short of hacking into the source code... assuming it isn't spaghetti code that even the game-makers can't figure out).

In summary, this ambiguity is marginally unavoidable, but in this case seems extreme.


...

Positives for Dispatch:


- Episodic Framing of Play/Story-Time
In 2026 The Economist posted an article about how, in their view, skipping ahead past the opening and close of serial drama episodes was a detriment to the overall experience and medium of story telling.
https://www.economist.com/culture/2026/06/01/why-you-should-never-skip-a-tv-intro 

While there was no substantial episode intro for each "episode" of Dispatch, the end-credits selection of music (which varied to match the theme and mood of the character-development in that episode) was arguably a very bold and constructive experiment-that-worked-very-well to (perhaps like Lit-RPG) bring the depth of established Drama-Literature media to the too often less-than-literary punch-em-up 'video-game' or 'tv-game' medium.

Side note: "It's Time For The Story"
This may be a stretch or overly subjective, but the wonderful old-schoole Ascii-art DNS-computer boot-screen had (for me) the effect of a good serial drama Title-Intro, which also gives Dispatch a kind of 'story in a story' form, where the title-intro is the start of a drama within a drama, and where the real-game that you play is also desktop computer software the story-main-character is playing in the using through your actions.


Good Story Elements & Balance:
(While this section may not directly relate to the game-design focus, as I have been very critical of Dispatch in some places I want to try to also voice praise for what I see as well done (however subjective).)




This may be very subjective and this may not make as much sense to people in the future who did not experience the plot-arc and end of the Iron-Man to No-Iron-Man marvel films. 

Arguably, the story of Dispatch does an excellent job of presenting a kind of 'next-generation' hero story consistent-with the marvel universe after the (first) marvel-film arc. The 'mecha-man' character is a kind of coherent-successor to various 'irreplaceable' personalities and characters who rose and fell during the Marvel arc: such as Iron-man, Capt. America, and the  Guardians of the Galaxy.

And also a kind of (classic to science fiction) 'what if.'
What if iron man was neither smart, nor rich, nor strong? What if Capt. America never gained super-strength? What if there was no next-generaion A-Team Avengers, and instead what was available was more like the breakfast club (a bunch of bantering semi-criminal knuckle-heads). And, importantly, to make a synthesis like this that is endearing and sympathetic (not just cynical and reveling in dismantling the values of a heroic age).

In a hero-world it is difficult to 'wind back the clock' to the time when those who became the avengers were, many of them, for various reasons, not heros. Captain American and Spider-man etc. were arguably always good people, but Iron-man, Dr. Strange, Thor, Ant-Man, and Star-Prince, etc., were basically aimless criminals until character-development evolved them into becoming heros. In Dispatch, while obviously not officially in the Marvel Universe, there is a coherent and believable narrative where a new generation of people evolves with both themes (such as a mecha suit) and world setting continuity (such as how earth evolves into a 'diverse' planet full of species from across galaxies). 

This dovetailing, whether conscious or not, allows the characters and setting of dispatch (however spotty and inconsistent in execution) to fill a hero-land vacuum that has been empty since the first generation retired.

Also, in various ways, the genuflection to older technology (and to janky technology) is arguably something that makes the story relatable and world-comprehending for people living around 2025. From the vantage of 1925, 2025 was an unimaginable super-future. But the real 2025 is a largely recognizable jumble of good-old-tech (on the edge of being forgotten, from Vinyl (LPs, not bad house-siding), to good classic games), and a landscape of broken tech-debt (that perhaps in the future will be referred to as a kind of 'tech-polution' that should have been cleaned up but instead was dumped in the commons). 












...

Discussion Note:

I am NOT suggesting that the voice acting and animation should not have been done, arguably those (in the good spots) are the high points of the game (where the story makes sense, the voice acting and artful animation bring the coherent-story to very positive levels of high quality experience (good stuff)), but I want to look at the cost of the voice acting and animation.

Obviously if you are making an animation and voice-acting game, then those are part of the game.

But I want to explore the topic of how effective a game can be without those.

For example, if the world of dispatch were made in a format that used pixel graphics, still-images, and no voice acting (perhaps like either a visual novel or ROM-2064, how much easier would it be to develop and expand the story in a maintainable way (without scope-explosion and cost-explosion). 

Part of what is brilliant about the no-audio text-dialogue system of Morrowind (and perhaps the 'avatar-card' on 'scene background' system of pixel-graphics) is that once you have the modular parts of:
1. location backdrop art
2. low definition character representation
3. small high definition avatar cards (e.g. with emotional expression variations) 

then you have a scalable system to implement any story.


While the animation and voice acting in Dispatch is amazing, the old-school CCG(avatar cards)-On-Pixel Map game that is the main game (and... perhaps most of the time of Dispatch playing) is also very good.

Would it be possible to have the elements of coherent-story (well managed into a few branches, or not branched) and the low-definition-game without the overhead of the animation and voice acting?

Or, could there be tools (perhaps like in classic anime that made heavy use of re-used backdrops and re-used visual elements) that could lower the cost of making animations and even help with voice-acting?


...

A variation on these questions, which might be too strange to be entirely coherent, is a variation on the question of how you could implement morrowind in Minecraft:
- How could you implement Dispatch in Minecraft?

(This is not suggesting that it is possible or fully make sense to ask, but rather an exercise in thinking through game design elements, how they can be used, and how the game-system can constrain or help story development.

The Stranger-Things minecraft (which used pixel-mini-games) might be relevant for this question.

...

Another topic that I want to try to re-emphisize (if with mixed relevance in regards to Dispatch) is the topic of having a game-world where player choices are able to have story-related impacts on the world-map itself (with a classic counter example being the illogical static world of Hogwarts legacy where 'poachers' would perpetually respawn in eternal 'poacher camps' making relatively simple prospect of cleaning the area to restore nature an impossibility, thereby also making the story (the whole game is that you are supposed to do something that the game-system arbitrarily by design prevents)

The perhaps too narrow example of restoring power in regions of the city-map may be, or lead to, concrete examples of this.

By having a lower-dimensional, or lower-resolution, map (good) it makes it more possible to have player actions and choices affect the world and what happens in it.


This might be a segue into adding 'sim-city' and 'civilization' elements into this discussion. While 'simulators' are more dynamic than static world maps, both dynamic-world-simulators and static-world open-sandbox games generally completely lack story and characters, with the tragic default-attractor that 'civilization' type games tend to fall into the same meaningless, storyless, characterless, ever-more-narrow contraction trap of being high-resolution combat-battle simulators. In this overall paper such an outcome is seen as falling into a complete-failure-equilibrium. 




...



# Lit-RPG and Computer-RPG

Given the 'too big to read everything' size of the (perhaps still nascent in 2026) lit-RPG collection of books, I am going to frame this as 'What can Lit-RPG books say about video-games' as opposed to a more singular "What does."

In my limited entry to reading Lit-RPG writings

- Dinneman & Haze, Dungeon Crawler Carl
- Rinoz (Pronounced as one word), Chrysalis
- Legend of Zero
- ~'Reincarnated as a Daemonic Tree'

I am going to draw a few tentative observations (with no claim that this could possibly describe every aspect of all Lit-RPG works without debate).

Note: There is a perhaps crucial ambiguity about whether 'RPG' in (lit-RPG) refers to video-games or to RPG more broadly (originally being not video-games).


From 'Human rights for NPCs' to 'all mobs are people' and the 5th-wall breaking arbitrary nature of a 'villain dungeon' that exists for no apparent reason, there appears to be a recognition of and reaction against games that lack a coherent story-world context. 

Could it be possible that this 'reaction' is a kind of 'second stage' (presuming a first) or a sequential process that began with the demand-distortion based creation of ever-less-coherent and story-based games focused instead on (as described above) battle-simulation, photo-realism, and short-term-thrills user-interface-fluff.

For example, this could be a way of viewing the emergence of (at least some lit-RPG books) as a 'hangover' or 'withdrawal symptoms' from a bad decision or bad habit, recognizing that something is amiss. ~"How did we end up in this situation where we fight NPCs and mobs in framework that crosses over meaninglessness into unethical meaning-destruction; and how do I deal with these cravings for meaningful stories and coherent-worlds while A. living in a food-desert of empty-calorie games and B. am still compelled to seek out the empty-calories in a kind of dysfunctional addiction-cycle of bad habits and mis-understood impulses and signals"? 



...

Discussion of stylized vs. 'photo-realism'
https://www.youtube.com/watch?v=EhCPSaOVfz0

...

Steam Users Are Punishing AI Games: Now Tim Sweeney Is Mad
https://www.youtube.com/watch?v=XzSclyZoi4c 



...
Fundamental to the existence of the genre of lit-RPG is a global visceral rejection of the lack of story-character-depth in video-games; it has grown and ebbed and flowed for nearly a century and has exploded as an outpouring of longing that extends beyond any particular demographic of people.

Most people are not like me, trying to overtly write about this and analyze it. But the mass popular engagement with lit-RPG represents active-connection by people who are not involved in any historical and intellectual analysis, this is not flocks of followers begrudgingly doing obligatory work assigned by priests of the public, ivory tower, employment, etc., and this kind of organic widespread empirical action is significant.


...
https://www.youtube.com/watch?v=qzm-nZAVz1g
The background video seems to accurately portray how TES has evolved into a fantasy-battle-simulator, a battle sandbox with lots of battle-simulation options. The video narrative appears to deliberately distance a positive fantasy battle simulator from a story and character based world (portrayed as being negative, (a.k.a. "absolutely fine and great of course... BUT..."), going so far as to shelve "role playing games" as being no longer meaningful. 


...

Games:
https://www.amazon.com/Origins-Political-Order-Prehuman-Revolution-ebook/dp/B00457X7VI 

https://www.amazon.com/Political-Order-Decay-Industrial-Globalization-ebook/dp/B00IQOFS7M 

...

# Type of Choice-Trees

What are the general ways that a character's actions/choices/decisions can affect the story/world?

There may be a kind of illusion or paradox in an 'open sandbox' game that supposedly allows a character to go-anywhere and do-anything, where the nature of the sandbox is such that there is no way to interact with the world beyond exceptionally-superficial 'fake-interaction-points' added on top of the world.


"The road not taken"

First let's look at story-based games and then go back to sandbox RPG and minecraft for comparison.


There is no way around the scale-challenge of making a choice-navigable world, as perhaps goes back to the tangible challenges of a choose-your-own-adventure book. 

Even with a human DM/GM where there is a lot of latitude for the players to make choices, there is still a range of pre-prepared material that the GM can produce. It would be incoherent for a human to GM a game where a player teleports to another galaxy faster than each location can be described (e.g. N times per second), and even in that case it is more of a 'sight-seeing' process where the location changes so quickly that interactivity is minimised.



There may be natural trade-offs that we can set out, which may highlight some themes of gamification.


The more characters there are, the less depth each character can have on average. 



...

# Story-Crafting: 
- Peter Jackson's documentary on the making of King Kong



Question full of Puzzles:
1. Can you make "The Heikei-Monogatari" into a game?
2. Can you make "The Blue Cliff Record" into a game?

..

# Heikei-Monogatari:

Similar to the shakepeare-story tree question, part of what is fascinating about the idea of turning the Heikei-Monogatari into a game is that it is several things:

1. It is, arguably, a paradigmatic model of the fantasy-setting that so many games aspire to reinvent (but are doomed to be overwhelmingly shallow).

2. It lacks the absurdly anachronistic mania that riddles 2026 lit-rpg fiction with non-sequitor idiocy: "I'm super hard, Bro. I swear I don't care about anything. Click like and subscribe! Please? I don't care! I'll show how much I don't care by using random expletives. That's proof right? Did you click like yet??? Oh yeah, this is super-dark medieval fantasy, bro! We're all dark and hard and we don't care, did I mention that? That's really really important. Because we don't care! I swear, no one here sees anything as important. Honest! We're totally dark-hard, and we know we have to say that honesty and truth are meaningless propaganda. You will not catch anyone here lecturing you on the 'correctness' of things or attempting to dictate prudence in your choices of behavior; why would we do that, when we totally don't care? We are strictly orthodox in our disavowal of 'caring.' We are definitely not deliberately assigning value and significance to a specific view point, vested interest, or abstract argument here, and certainly not suggesting that there is validity in the particular argument that we are making compared with the policy-stances of other stakeholders. The official line, that we never deviate from, is that nothing means anything, that you must never listen to anyone or believe anything or care about anything. That's really important to remember! I really hope you buy more of our verified authentic stuff in the reliable strictly rules-based marketplace! And always remember the core tenant of the first pillar of truth: everyone must profess that they do not care, and the secondary adjunct axiom of reality: nothing has any value, function or meaning. See you on the well-maintained chat server over our vital telecommunications infrastructure! We don't care! Take care! Nothing means anything! Oh no, my formatter is saying I need to add more random expletives here, but where? Good luck not caring, bro!" 

3. It is, by and large, not fiction-fantasy new or old, but (relative to usually overly loose accounts) a remarkably accurate and detailed history. One consequence of this is that there is usually a large amount of historical material for going into more detail. This includes still-existing materials and artifacts, with a key area being: the geography of Japan. 

The 'natural history' of Japan, is mindblowing. 

Japan: The Natural History of an Asian Archipelago (Wildlife Explorer Guides)
by Mark Brazil (Author)
https://www.amazon.com/Japan-Natural-Archipelago-Wildlife-Explorer/dp/0691175063

As relatively admirable as the 'world depth' in a game like TES Morrowind is, it may raise the overall topics of maps, 'models', 'parametric models', and 'manifolds' in terms of lower-dimensional patterns vs. high-dimensionsal N-dimensional-hypervolumes (the study of which is (if contrary to popular misunderstanding) ecology). 

The question of high-dimensional and lower-dimensional may be a persistent theme in the story-game-language-User-Interface area of study. 

"Gamification" by making a minimal-manifold-model that contains sufficient pattern data to be useful is a persistently valuable area, from mapping the territory to the aspect of computer-science whereby production-system performance is a different development path from theoretical (if not ideological) approaches.

4. The cases of 'choice tree' in First-Folio Shakespeare and 'choice-tree' in Heikei-Monogatary are interesting to juxtapose. 

Shakespeare (perhaps some 'histories' aside) is limited by the supply of style and content. Whereas Japanese history is more inherently one set of fixed past events. Having a story with choice-branches in either is a challenge. Having a (multiverse) 'sandbox' is generally undefined and impossible. 










### Choices & Interactions


- Maze type "choices" & "interactions"

- "Physical" vs. "Linguistic"
- 


Games & Game-Theory


Signals and Information-Theory



#### language

More abstractly in terms of language, there is also an interesting language-character-set and font questions (that may be more theoretical, but are still interesting).

1. The typeset of First Folio Shakespeare vs. Ascii
- close enough... but not ascii

2. Japan's strange Sanskrit-Hybrid Language...
- 


...

RAG-RPG, State, Language-Difficulty

There may be a significant and understandable contributor to the contraction-tendency for games to move from language-story-richness to violence-combat.



Montesque and 'Trial By Combat'



Law, Code Symbols, and the "Sub-Symbolic"





"Hello, Traveler!"


...


Stories, Probability, and Divination:
- practical language and articulation tricks
- the theme of the problem of contraction
- exploring basic options



- Probability, 'Fooled by Randomness' and Odd Quanta


...

Direct Skills and Represented Skills

...

Repetitive Language in Real Life

..

https://www.youtube.com/watch?v=370pTa2kJo4 
Note: a number of these observations relate to story-depth story-navigation questions and tradeoffs.


...

Note: approaches to optimized graphics


...

2026 08 08

Some people are genuinely attracted to and satisfied by fireworks and simple shell-games, dice, roulette, 'fooled-by-randomness,' 'flashing lights and explosions,' stimulation with no story, character, concepts, language, reading, art, etc.

On the other end of the spectrum there are museums, which are arguably 'static objects in cases' but are usually indicative of an underlying story and of a 'craft.' 

To not underestimate the depth in a single 'painting'
- LP slip-cover art
- Paperback book cover art (which in the case of science fiction in the erra of John W. Cambell (which arguably is 'Science Fiction' proper, book-stories and characters not-uncommonly were secondary homages to cover-art).



There are some games that do not aspire to be anything more than fire-works and shell games, those "games" are not the primary focus here.


- social story-puzzles and 'AI-RPG-Arean' tests
(what technology does it make sense to do what with)
- state and scope depth testing


- castelvania: poster-art

...

Underestimating the difficulty or over-estimating the maturity of a medium:

There were a number of cases, such as the X-file game, perhaps the Blade-Runner game, where an attempt was made to use a 'video game' as a medium for an interactive story, where the producer was proficient in some other form of story-telling. The fact that none of these cases came remotely close to anything of significant depth and value makes it difficult to identify which cases were not really serious attempts (being instead naked money-grabbing vapor-wear) and which were serious attempts.

There has been (to pick a somewhat arbitrary time frame) between 1975 and 2025 an increasing profusion of games, ranging from board games to computer games, etc. There have also been (while the market is marginal and challenging) a significant number of table-top role playing games. 

Another possible angle is RPG-Maker, which might be an example of a story-mode starting to come together, and yet the output is likewise strangely stultified. 

Overall in the interplay between game and story appears to have been characterized by there not being a clean combination of story and game, rather there are stories that are primarily stories but have game-like decorations in the story, and on the other side there are games that have story-like decorations in the game. In other words there are stories that feature games, such as Stranger Things season one. And there are games that include superficial story-like elements (as in (e.g. quests in) massively multi-user games). But the stubborn gap between interactivity and choice on the side of games, and curated artist-created narrative story and character development on the the side of stories, persists.

In-person table-top RPG is probably still the closest thing that there is to a synthesis of art, story, and game, yet this has a potentially critical part in the context of this study: most people are not a proficient (or professional) writer, artist, actor, musician, or story-teller (let alone all of the above). Aside from the technical difficulties of dramatizing open player choices, the art that most people create is simply terrible (with the significant caveat that this is primarily describing America, whereas comparatively speaking the average Japanese elementary or middle school student is more artistically proficient than an the most elite american professionals (perhaps an echo of the perpetual curse of the roman republic and empire (a kind of running joke at the time) that it was doomed to be hopelessly uncultured and artless no matter how wealthy (or violent) it became). 

Along these lines, an interesting example of an exception to this pattern
https://www.sffchronicles.com/threads/589335/, is how (as far I understand) the novels, and then Drama-Series 'The Expanse', was originally a tabletop RPG "campaign" (a game-story written by the players) which was then written out as novels. In this example we see at least two things. 1. When capable artists play a table-top RPG the artistic quality of the 'game world' can be significantly good. 2. These were Europeans, not Americans. 

As far as I know it is not common for the quality of a game-campaign to be notably high in the sense that it could be turned into an enduring work of literature or drama, yet there is probably some microcosm of the overall discussion here within the question of how adept players themselves need to be. Arguably, with the right training and guidance, more or less all people can be good enough at world building to be part of a rewardingly rich tabletop RPG. And this may be part of the brilliant elegance of the recipe of the original ~D&D (or whatever the original name is said to have been), that it allowed more or less any player to channel their sufficient talent into a team-created work of interactive art, and arguably a mode that accommodated the affirmative charm of "amature art" not being brittle through undue exclusivity. This may be similar to the argument that a national education can educate a population. At various times and places education is more or less popular and successful. The default is that educated people, and institutions of education, are attacked and destroyed by violent criminals (for a variety of reasons, amongst which are (in the short term) fun and profit (in the long term self-destruction results in self-destruction)). 


Another example of this strangely stubborn gap is the 'books' in the elder scrolls game series. Given that there is no reason (that I am aware of) for there to be any limitation on the books within the world, there is a suspicious and perplexingly stark 'wall of very low quality' or bubble of superficiality, that holds back the games and game-world. While morrowind arguably strikes a rare closer-balance where if you squint you can sometimes see points of value here and there, the experience never goes beyond the extremely superficial depth that you would expect from a two-pannel comic on the back of a toy-box. Despite the entire history of writing and story-telling on earth, the 'books' (and character-stories) in Morrowind are like what you would get if an alien species who only spent 15 minutes observing one town from orbit were to give an impression of human society: you can recognize it as a parody of society or art, but it is ridiculously shallow.

While it is arguably understandable that story plus game-play plus art is a very difficult medium to create literature in, in the case of text, of books, there is no clear reason why the dialogue, story, and book writing are so uniformly shallow: they could literally have used public domain ancient poems, dramas, and mythology straight from Project Gutenberg. And compared with other games, Morrowind is considered to be 'too bookish.'

The standards of games are shockingly low, which in a history of media may not have a precedent, perhaps suggesting the digital-media are not (to the chagrin of H. Marshall McLuhan and Pierre T'ard de Chardin) media through which people can create, communicate, or participate in art and worlds as they have for millenia through the myriad other media through which worlds are woven. 

There have been various games here and there that have won the hearts of fans (such as FF7), but the shallowness of even these story-worlds compared with, for example, the once reviled John W. Campbell era of Science Fiction magazine stories, is absurd. The people who are making these games are effectively illiterate and yet we are under the duress of coercion to act as if these apathetic grunts are comparable to the language of basic literacy.

Going back to the story-line of 'Dispatch,' in the world of gaming this is 'a staggering achievement', but if you wrote out the story line (including the utterly incoherent last two parts) on a napkin it would not get a passing grade as an elementary school assignment.

If the story is true, Steve Jobs had an epiphany while in a class on brush-caligraphy about what a 'digital' medium and interface needed to be like (for it to empower human expression). If the goal is for the expressiveness and depth of historical calligraphy to be reached using 'high tech media' then in 2026 we have made no progress at all whatsoever towards that goal. Illuminated manuscripts and calligraphy are so far beyond any digital features. Typography, as in the 'First Folio' that is "Shakespeare," represents something that can be somewhat expressed and managed, though it is not clear that this is being done correctly or adequately. 


Between high definition and low definition, it is not clear that what we call high definition is really an option, whereas a pointelist and ascii-minimal medium appears to be what is possible to 'paint with,' yet the results so far of what people are producing with digital pointelism and ascii are distressing.

This is not confined to "games." Look at what has happened to the profession of journalism from the age of printed newspapers to the age of 'digital media.' The expectation and the ambition, like with Steve Job's McLuhan-Caligraphy-Global-Village-Noosphere vision, is that electronic media would at the very least allow more marginal flexibility and production, but what has happened is that the entire profession of journalism, over the fifty years from the Dartmouth time-sharing internet of 1966, to the public internet and app-ecosystems of 2026, has, after more than five hundred years of international development, been most terminated, with an apparent future direction of total extinction.

This is a mystery. What is behind these patterns?
Is the problem the medium itself? Or is the problem a set of other factors. For example, Americans in the 2020's are being so bombarded with blip-vert torrents of flashing-lights and explosions that they are not able to function properly. This may be more of an epidemiology and hygiene problem than a media-limitation problem. 




...

'graduate/promote' model game:
(youth: school graduation, adult: career promotion)


integrating underlying metrics

clear story outcomes coherently based on metrics


mystery-underworld crime-puzzle (xfiles, sherlock holmes, Father brown, etc)
high fantasy (hogwarts)
space pilots (starman Jones)
frontier-mountainaer-sea ()

etc.




region dynamics:
- simcity civilization


... 

The Economics of Story Publishing:

- Investment

innovation comes from lone authors who do all the product development and then go hat-in-hand to a publisher who is completely unable to predict the long and short term publishing value of works, inevitably turning away the best thing when trying to cynically grab for the last supposed 'smash hit' formula


- Demand Distortion


...

# Case Study: Disco Part 1: Feasible, accessible Game Model



# Case Study: Disco Part 2: Story, Theater, Audio

Even in the case of disco, there is also a story-telling element. 
Not having been alive in the mid 1970's nor having lived in Europe, my very vague and shallowly-researched overall understanding is this:

1. The film Saturday Night Fever was a good film with a relatable human story about the difficulties of working-class life in one of the truly most devastatingly depressing time periods in history (the mid 1970's) (that is not a joke or sarcastic: from 1971 a vast proportion of culture that had survived history rapidly died out for reasons that are still not clear)

2. I cannot find clear non-contradictory accounts, but the film Saturday Night Fever appears to have significantly boosted the visibility and popularity of disco. 

3. (Again, I am not an expert on this) In a story similar to writers working on their craft without commercial success for years, the Beegees (an Australian-British band) formed in 1958 and had an up and down career as they refined their craft over many years.

4. The term "Disco" (varying by language etc.) is still in 2026 used throughout Europe as a generic term for 'dance-club' type venues.


While admittedly an abnormal parallel to attempt to draw, there seem to be a number of curious similarities between the factors and phenomena of Disco as with games and writing and their publishing challenges. 

- https://en.wikipedia.org/wiki/Saturday_Night_Fever 
 - https://www.bbc.co.uk/programmes/articles/23hgH64c0cvLlwYjfmzcztJ/6-ways-disco-changed-the-world 
- https://www.theguardian.com/music/2011/jun/15/saturday-night-fever 



...

# Game Design:


We should at least try to draw some lessons, or illustrations, from the Disco case study (assuming there is any validity in the exercise, which is not guaranteed):

1. That there is a persistent wish/belief in a cynical equation for sport entertainment

2. The design of "games" (using the term very broadly here, including specific disco-experiences) is difficult.

Putting one and two together, this may sufficiently describe the dysfunctional atmosphere around online RPG gaming. Publishers and investors have the psychological schema that this is a cynical drug-addiction market, you build flashing lights and lease a location where stupid people can have their flashing-light-violence addiction experience that they pay for, you collect the rent, you pay the lease, that's your business model. 

Most 'users' (a term conveniently the same between illegal narcotics crimes and Agile software development workflow) do not show significant signs that they perceive themselves as existing in an 'anything goes' cynical market, to the contrary they are very picky. For example, even where there is great social enthusiasm for a game such as World of Warcraft, and where effort was made to make that into a perpetual business recipe-delivory publishing model, the cost and difficulty of high-quality-story-investment was too high and what publishers short-sightedly viewed as a perpetual cynical addiction market yet again, to the contrary, showed itself to be a more nuanced temporary phenomena of unrepeatable audience engagement.


Meanwhile, individual artists and scholars (J.R.R.Tolkien was primarily a professor) spent their lives painstakingly creating facets of art that creatively reflect a lifetime of observation, rumination, and refining their craft, usually without any short-term economic reward or realistic expectation of such.

Another example might be the rise and fall of the John W. Campbell era of Science fiction, where style-savvy editors, talented writers, and talented cover-artists for a while were able to maintain an astonishingly high quality, prolonged, and economically sustainable movement. How it was that this disintegrated is an important mystery. Somehow the writing talent, the editing talent, and the audience-demand, all drifted towards low quality garbage. 


3. What people connect with, even games, tend to ebb and flow with biographies and the zeitgeist of time and place. 
