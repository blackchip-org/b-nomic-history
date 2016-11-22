# Rules of B Nomic - August 27, 2008

## Foundation

### Rule 4E83: The Game of Monopoly

The name of this game is B Nomic.

### Rule 4E84: The Game of Calvinball

The name of this game is C Nomic.

### Rule 4E2: Game Objects

The game of B Nomic consists entirely of Game Objects, which may be known simply as Objects. Anything that exists in the game is an Object, and anything that is not an Object is not in the game.

Game Objects can only be created, destroyed, or modified if allowed by the Rules, in a manner explicitly governed by the Rules.

### Rule 4E11: Attributes

Game Objects have a set of zero or more Attributes. Each Attribute has a Value. The Rules define Attributes by specifying:

- A Name
- A Scope which defines the set of Objects that have this Attribute
- A Range which defines the set of allowed Values
- A Default Value that sets the Value when an Object gains the Attribute
unless otherwise specified in the Rules.

A Property is an Attribute with a Range of True and False. An Object with a value of True for a given Property possesses that Property, and an Object with a value of False for a Property does not possess that Property. The adjective form of an Property or its negation can be applied to an Object to unambiguously denote whether the Object possesses the relevant Property /*e.g., an Active Player is the same as a Player who possesses the "Active" Property; a Non-Vested Player does not possess the "Vested" property. */

### Rule 4E3: Outsiders

An External Force is anything which exists independently of the game. That is, it would still exist if the game stopped existing, and would still exist if the game had never started existing.

An Outsider is a Game Object representing the projection into the Game of an External Force. As a Game Object, an Outsider is bound by the Rules. These Rules do not purport to regulate External Forces except in relation to their interaction with the Game as Outsiders. [[ i.e., something that exists outside of the game but is also acknowledged by the rules as influencing the state of the game, and thus exists within the game as well, such as a player.]]

### Rule 4E6: Fora

A Forum is any External Force that allows Outsiders to communicate. Each forum may be designated as one of the terms Private, Public, or Discussion. All Fora are initially Private.

### Rule 4E5: Game Documents

Game Documents are Game Objects that consist of text.

In each Game Document, with the exception of this paragraph, text between a forward slash+asterisk character combination and an asterisk+forward slash character combination or between double square brackets (that is, text between "/*" and "*/" or between "[[" and "]]") shall be deemed Comment Text. Comment Text has no direct effect on the state of the game, although it can be read.

### Rule 4E36: Rules

Rules are Game Documents. Non-Repealed Rules define how this game is played. Each Rule must have a number and may have a name. Rule are numbered from a set that initially contains all positive integers and zero. When a new rule is created, the Minister of Law is obligated to assign it the lowest number available in the set, and then remove that number from the set. Each rule number shall be prefixed with the notation "4E" (for Fourth Era) to distinguish it from past rules in previous eras of B Nomic. Where a Rule, Proposal, Game Action, or other Game Document refers to a Rule by its number without a prefix, it shall be taken, by default, to refer to a Rule prefixed with the notation "4E". /* For example, one can say "Rule 15" to refer to Rule 4E15 */

There exists a ministry known as the Ministry of Law. The Minister of Law, also known as the Rulekeeper, is responsible for maintaining a Public Display of the current Rules and Victory Conditions.

The Rulekeeper may, as a Game Action without Objection, change a Rule's Title.

### Rule 4E75: Rule Powers and Precedence

There is an Attribute called Power with a Scope of all Rules, a Range of all rational numbers from 0 to 1 inclusive, and a Default Value of 1/2. The Rulekeeper is responsible for maintaining a Public Display of the current Powers of Rules.

If two Rules of different Powers contradict each other, the one with a higher Power takes precedence, unless the one with a higher Power states otherwise.

If two Rules of the same Power contradict each other and exactly one says it takes precedence over the other, that one takes precedence. If two Rules of the same Power contradict each other and exactly one says the other takes precedence over it, that other one takes precedence.

If two Rules of the same Power contradict each other and the above paragraph does not state which takes precedence, the one with a lower number takes precedence.

This Rule takes precedence over all other Rules that determine precedence of Rules.

When any changes to the state of the game are scheduled to occur simultaneously (e.g. at the start of an nweek), they occur in the following order:

- Changes specified by a Victory Condition.
- Changes detailed in the Rules, in order of precedence (highest first) of the Rules that call for each change.
- Non-Trick Game Actions.

## Time

### Rule 4E14: NTime

#### Definition

There is a Game Object known as The Clock. The Clock consists of the following values:

- A positive integer known as the nweek
- A positive integer known as the nday
- A state of being Off or On
- A nonnegative integer known as the ndelay

#### Clock Changes

At midnight (00:00:00) Coordinated Universal Time (UTC), if the Clock is On, then the nday is incremented by 1. Otherwise, the ndelay is incremented by 1. [[An online UTC clock is available at http://www.time.gov/.]]

If the nday would be set to a value greater than 12, instead it is set to 1, the nweek is incremented by 1, and the Clock becomes Off.

At the beginning of each Voting Period, the Clock becomes Off, and until the Clock next becomes On, the Chairman may as a Game Action change the clock to be On, provided he has first published to a Public Forum a Ballot listing any Open Proposals and their text or a link to said text.

The Clock may be changed from On to Off as a Game Action by the MoM.

If the Clock is Off and there are no Vacant Ministries, the MoM is obligated to turn the Clock On. When the Clock is turned On, the ndelay is set to zero.

#### Time

Each time that the Clock nday value changes a new nday begins. /\*the previous nday ends in the moment immediately before the Clock change\*/ A period of one nday is the time intervening between two consecutive changes of the Clock nday value. Each time that the Clock nweek value changes a new nweek begins. /\*the previous nweek ends in the moment immediately before the Clock change\*/ A period of one nweek is the time intervening between two consecutive changes of the Clock nweek value.

When the clock turns off, and each time that the Clock ndelay value changes to a value different from 0 a new ndelay begins. When the clock turns on, the current ndelay immediately ends. While the clock is off a period of one ndelay is the time intervening between two consecutive changes of the Clock ndelay value.

#### Durations

A duration to the effect of "X ndays", where X is a number, shall be interpreted to mean that the duration ends at the end of the nday after X consecutive changes of that value. [[Thus, if it is currently the middle of nday 2, something happening "in 2 ndays" will occur at the end of nday 4.]]

A duration to the effect of "X ndelays", where X is a number, shall be interpreted to mean that the duration ends at the end of the ndelay after X consecutive changes of that value. The resetting of an ndelay to 0 from the Clock being turned On does not count as a change for the purposes of this paragraph.

A duration to the effect of "X nweeks", where X is a number, shall be interpreted to mean that the duration ends at the end of the nday when the nday is the same value, but the nweek is increased by X.

A duration to the effect of "X rdays", where X is a number, shall be interpreted to mean the duration ends after X occurrences of midnight UTC.

#### Nyears

A period of 10 nweeks is known as an nyear. Hence, the first 10 nweeks (1-10 on the Clock) comprise nyear 1, the second (11-20 on the Clock) comprise nyear 2, and so on.

#### Starts and ends of nday

All events occurring at the end of an nday occur before all events occurring at the beginning of the next nday.

#### The Ministry of Time

There exists a Ministry known as the Ministry of Time. The Minister of Time, also known as The Doctor, is responsible for maintaining a Public Display of Game Actions and other changes to the state of the game scheduled for the future, including the time at which and order in which these will occur.

### Rule 4E31: Calendar

The ndays of the nweek have the following names:
- nday 1 = Breakday
- nday 2 = Winday
- nday 3 = Mulberry
- nday 4 = Tango
- nday 5 = Wonko
- nday 6 = Halfday
- nday 7 = Joel
- nday 8 = Rushnight
- nday 9 = Ballotday
- nday 10 = Teucer
- nday 11 = Zarpint
- nday 12 = Thirnight
- nday 13 = Armageddon

#### Public Holidays

Corvette of the 4th nweek of an nyear is known as "Agoran Silly Hat Day", in commemoration of the epic Agoran surrender of nyear 14. On this holiday, it is customary for B to send Agora a mildly offensive message.

Breakday of the 5th nweek of an nyear is known as "Paranoia-Free Day", in commemoration of the salutary relegation of all irrational panic to an upstart foreign nomic. On this holiday, it is customary for Players of B to flick their Panic Buttons.

Zarpint of the 10th nweek of an nyear is known as "Gift Day".

### Rule 4E9: Eras

The First Era of B Nomic is the time starting with the creation of the game (approx. 5 Dec 2001, prompted by a five-month lull in A Nomic) and ending immediately before the start of The Second Era of B Nomic.

The Second Era of B Nomic is the time starting with nweek 85 (approx. 4 Apr 2005, prompted by data loss when the bnomic.org server crashed) and ending immediately before the start of The Third Era of B Nomic.

The Third Era of B Nomic is the time starting with nweek 112 (approx. 14 Nov 2006, prompted by another five-month lull) and ending immediately before the start of The Fourth Era of B Nomic

The Fourth Era of B Nomic is the time starting with nweek 135 (10 Dec 2007, prompted by a second State of Emergency in 2 nweeks), and continuing to the present.

### Rule 4E26: The Temporal Prime Directive

No rule or game action may require or force any retroactive changes to the game state. It is, however, permissible, to create rules or perform otherwise-legal game actions that simulate retroactive changes to the game state.

## Actions

### Rule 4E7: Game Actions

A Game Action is defined as any activity specified by the Rules that changes the state of the game. To perform a Game Action, an Outsider must post a message to a Public Forum specifying that he is taking that action. He must also specify any targets and/or parameters necessary for that action [[for example, you must specify a proposal in order to vote against a proposal]]. Unambiguous targets and parameters specified in Game Actions are valid regardless of capitalization, punctuation, or exact wording unless explicitly required by a Rule. He may list multiple actions that he wishes to take, in which case he takes them in the order he lists them. He may also state a specific positive integer to perform a particular action that many times (if legal, of course) sequentially. The Rules also have the power to cause an Outsider to take Game Actions whether he posts or not.

Game Actions occur upon reaching the appropriate fora, in the order they arrived, unless a rule states otherwise. A Game Action that is caused by a Rule instead of by a Forum Post takes place at the time specified by the rule.

An Outsider may post a message to a Public Forum specifying that he will perform a specified Game Action at a specified time in the future, with reference either to The Clock or to Coordinated Universal Time (UTC). A Game Action performed in this manner takes place at the time specified by the Outsider, defaulting to the start of the next occurrence of any period of time unless otherwise specified by the Outsider [[ *e.g.* if one writes "I do X on nday 8", X happens at the start of the next nday 8]]. If multiple Game Actions are set to be performed in this manner at the same time, they occur in the order they arrived at the appropriate forum.

Text to the effect that "any player may do X" should be interpreted to mean that X is a Game Action; but such a declaration implies that only players may take the Game Action X (unless another declaration permits other Outsiders to as well).

### Rule 4E21: Objecting

The Rules may explicitly require a specific type of action to be performed "without N objections" where N is a positive natural number. The phrase "without objection" is synonymous to "without 1 objection"

To perform an action that must be performed without N objections, a Player must first announce his intention to perform that action. Having made such an announcement, the Player can perform the action between 2 and 4 ndays after the nday the intent to perform the action was announced if, and only if, fewer than N Players object to the action. A rule may give a different time that must elapse before a specific action occurs without objection, and in that case, that rule takes precedence and the Player has two ndays following the required elapsed time to perform the Action.

Objecting is a Game Action.

A Player may not object to an action he attempted to perform.

### Rule 4E22: Supporting

The Rules may explicitly require a specific type of action to be performed "with N supporters" where N is a positive natural number. The phrase "with support" is synonymous to "with 1 supporter"

To perform an action that must be performed with N supporters, a Player must first announce his intention to perform that action. Having made such an announcement, the Player can perform the action within 2 ndays after at least N Players support the action. If the action does not receive the required support 2 ndays after the nday the intent to perform the action was announced, the Player cannot perform the action under this rule. A rule may give a different time that must elapse before a specific action fails without support, and in that case, that Rule takes precedence.

Supporting is a Game Action.

A Player may not support an action he attempted to perform.

### Rule 4E12: Transactions

As a Game Action, an Outsider can submit a Transaction. A Transaction consists of:

A clear statement marking the Start of the Transaction, such as "BEGIN TRANSACTION".
A list of Game Actions and assertions about the state of the game.
A clear statement marking the End of the Transaction, such as "END TRANSACTION".
The list is considered in sequence. If it would be legal for the Outsider to take each Game Action within the Transaction exactly as specified, and each assertion would be true at the time it occurs within the list if the Game Actions were so taken, then the Transaction is said to Succeed. Otherwise, the Transaction is said to Fail. If it cannot be determined with finality and certainty whether or not one of a Transaction's assertions is true, or whether one of its Game Actions is legal, then the Transaction Fails.

The Game Actions in a Transaction that Succeeds occur just as though the Outsider had taken them individually.

A Transaction that Fails has no effect.

The verb "to repeal" means "to give the Repealed Property to".

### Rule 4E8: Submission

The rules may state that it is legal for Outsiders to Submit certain document types as a Game Action. To Submit a Game Document, an Outsider must provide a full description of the Document in the Public Forum message where they take the Action of Submitting.

### Rule 4E4: Joining and Leaving

There exists a ministry known as the Ministry of Society. The Minister of Society, also known as the Registrar, is responsible for maintaining a Public Display of the current Players and their Attributes and Properties, as well as a Public Display of the current Public and Discussion Fora.

A Player is an Outsider who consents to be governed by the rules, fulfills all requirements for continued playerhood specified by the rules, and has become a Player in a manner specified by the rules that were in effect at the time e became a Player.

Any Human External Force who is not already a Player and who has not been a player in the current or previous nweek can become a Player by posting a message to a Public Forum containing a request to become a Player and a uniquely identifying name that e wishes to be known by.

A Player may cease to be a Player by Forfeiting the game; this must be done in a Public Forum unless there are no working public fora, in which case he may notify the Player he most recently knew was Registrar privately instead.

No restrictions may be placed on when a player may forfeit; any player may forfeit the game at any time (regardless of any timekeeping device used in the game).

Notwithstanding any requirements that would deny it this status, in this Rule or any other, The Operantly Conditioned Beast is to be considered an Outsider and a Player.

In its request to become a player, an External Force may name a group of current players that were responsible for it's desire to join the game. A recruitment bonus of 60 mackerel shall be evenly divided between the players so named when the External Force becomes a Player, with any fractional mackerel being destroyed.

## Ministries

### Rule 4E45: Ministries

A Ministry is a Game Object that can be assigned to at most one Legal Entity. It represents the responsibility of that Legal Entity to keep Players aware of the state of a particular aspect of the game, and may also represent the power of that Legal Entity to affect the gamestate in ways specified in the Ministry's definition. If a Ministry's defined powers conflict with any other part of the Rules, the latter takes precedence.

A Minister may delegate some or all of its Ministry's defined powers to another Legal Entity or to multiple Legal Entities, as specified by a Contract to which both the Minister and the Legal Entities in question are Parties. In all cases, any penalties that the Rules impose for failure to fulfill any ministerial obligations are incumbent only upon the Minister itself.

A Ministry that is not assigned to a Legal Entity is Vacant.

The terms "post holder", "pot holster", "post holder designate", and "Minister" refer to the Legal Entity in possession of a given Ministry. This can be abbreviated "PHD".

### Rule 4E46: Assigning Ministries

A Legal Entity may, as a Game Action, assign a Vacant Ministry to itself, specifying for this Ministry a new Reward Value, which must be less than or equal to its current Reward.

### Rule 4E47: Leaving Ministries

A Minister may Resign from its Ministry via Game Action. At that time, the Ministry becomes Vacant.

A Minister which loses the Active property or ceases to be a Legal Entity immediately vacates any Ministries it holds upon doing so.

### Rule 4E48: Usurping Ministries

There exists an attribute Reward with a scope of all Ministries, a range of all integer amounts of mack between (and including) m1 and m100, and a default value of m100. At the beginning of each nweek, the Reward for any Vacant Ministry is set to the default value.

A Minister may, as a Game Action, Revise the Reward Value of its Ministry, immediately changing it to a value lower than the current Reward.

As a Game Action a Legal Entity with sufficient mack may Usurp a Ministry that is currently held by a different Legal Entity, proposing for this Ministry a new Reward Value, which must be less than its current Reward. A Legal Entity is defined as having sufficient mack to Usurp a Ministry if it holds at least half that Ministry's (pre-Usurpation) Reward. If, 2 rdays after a Ministry is Usurped, that Ministry's Reward is still higher than the Reward proposed by the Usurping Legal Entity, the following events occur (in order from top to bottom, with each change only if the previous change was successful):

Half of the Ministry's Reward is automatically transferred from the Usurping Legal Entity to the current Minister.
The Ministry becomes assigned to the Usurping Legal Entity.
The Ministry's Reward is set to match the proposed Reward.

### Rule 4E49: Ministry Rewards

At the end of each nweek, for each Ministry that has been continuously held by the same minister since the clock was first turned on that nweek, its Minister earns that Ministry's Reward.

### Rule 4E50: Public Displays

A Public Display is a display of an aspect of the current state of the game in a form easily accessible to all Players. Good Public Displays can include the B Nomic wiki or posting on a regular basis to a Public Forum.

If the rules require a Ministry to maintain a public display, then that Ministry is obligated to update that public display to reflect the current gamestate whenever the data related to it is modified. However, this obligation is fulfilled even if there are accidental errors and/or omissions in the updated data of the public display.

Any player may challenge a public display that is maintained by a Ministry as a Game Action by listing any errors he believes to be present in that public display. The Minister who maintains that display is obligated to address those errors by either correcting them or indicating why he believes them to be already correct.

A Player may, as a Game Action with 4 Support and no Objections within 2 rdays, Approve a Public Display. The Public Display in question must either be provided in full as part of the Game Action or linked to on a static web page [[e.g. permanent link on the wiki]]. When a Player successfully Approves a Public Display, the Gamestate is changed to reflect what it would be if the Approved Public Display were accurate as of the time the Player attempted to Approve it. Any subsequent changes (Game Actions or automatically triggered events) that would normally be reflected in this Public Display are retroactively simulated.

Any public display which has not been challenged within 1 nweek is automatically considered to be approved.

### Rule 4E51: The MetaMin

There exists a Ministry called the Ministry of Ministry, also known as the MetaMinistry. The Minister of Ministry may be referred to as the MoM, the MetaMin, or Kurt Gödel.

The MetaMin is responsible for maintaining a Public Display of all existing Ministries, showing their names, responsibilities, retainers, and current holders.

The MetaMin is also responsible for tracking and displaying any state of the game that isn't covered by another Ministry.

### Rule 4E53: Ministerial Obligations

A rule or passed proposal can create an obligation for a Ministry to take some action within its powers. A Minister shall fulfill any obligations on his Ministry in a Jiffy. Unless the rules explicitly state otherwise, a Minister has the power to make any changes to Game Objects strictly necessary to fulfill his Ministerial Obligations.

Any Minister who fails to perform an obligation within the allotted time can be removed from his Ministry by any Player as a Game Action.

Whenever a new Minister takes over a Ministry, the time limit for any obligations on that Ministry are reset. Therefore a new Minister shall always have a Jiffy to fulfill any obligations on the Ministry he has taken over.

## Gameplay

### Rule 4E17: Points

Any Game Object may have points. Points are Game Objects. The number of points an object possesses may also be referred to as that object's "score." An object's score cannot be less than zero.

### Rule 4E33: Currency

A "currency owning object", or COO, is a type of game object that can own currency (also called "money"). All players are currency owning objects.

The rule or rules defining a new currency will define an attribute the scope of which is all COOs. The value of this attribute shows how much of that currency the COO has.

A COO can give currency to another COO by a game action, as follows: e specifies an amount (which cannot be greater than the value of his currency attribute, or less than zero) and a currency; that amount is deducted from eir currency attribute; the receiving COO's currency attribute is increased by the amount.

If the COO has a non-positive currency attribute for a given currency, then he cannot give that currency to another COO. If for any reason the receiving COO's currency attribute cannot go up, or the giving COO's currency attribute cannot go down, then nothing happens.

Players can, via game action, exchange points for currency. The rule or rules defining the currency will set the exchange rate. The player declares how many points he wishes to exchange (which cannot be less than 0 or more points than he has) and the currency he wishes to receive. He loses that many points and gains (exchange rate x points) in the currency. If for any reason the amount of his points cannot go down or the amount of his chosen currency cannot go up, then nothing happens.

### Rule 4E34: Mackerel

The default currency of this game is mackerel, also known as a mack (singular) or macks (plural). This can be shortened to a lowercase m. [[See below.]]

There is an attribute "mackerel": scope is all currency owning objects; range is non-negative integers; default value is 0. The value of this attribute should always be expressed starting with a lowercase m, for example, m50.

The points -> mackerel exchange rate is 5.0 - that is, 1 point may be exchanged for m5.

Whenever an entity becomes a Player, if he has less than 50 macks, his mackerel is set to 50.

At the beginning of each nweek, each player who has the Active Property gains m25.

### Rule 4E39: Message Of The nweek

There exists a unique Game Object called the Message Of The nweek, also known as the motnw. The motnw has one Attribute called the Message, with a Scope of the motnw Object, a Range of any string of between 1 and 256 characters inclusive, and a Default Value of "This space intentionally left blank".

The Registrar, as a Game Action with Support, may change the value of the motnw Message, but cannot change the value more than once in an nweek.

The value of the motnw Message Attribute should be prominently posted on a Public Display. [[the main page of the B Nomic wiki is ideal]]

### Rule 4E40: Threat Awareness

There exists a unique Game Object called the Threat Awareness Flagpole. There exists an Attribute named the Threat Flag, with a Scope of the unique Threat Awareness Flagpole, a Range of either "Pink Ponies", "Polka Dots", "Setting Orange", "Jolly Roger", or "Black Watch Plaid", and has a Default Value of Pink Ponies.

The Minister of Ministries is responsible for updating the Threat Flag, as he sees fit, to notify players of the potential dangers to the state and integrity of the Game. The Minister of Ministries, as a Game Action, may change the value of the Threat Flag to either Pink Ponies, Polka Dots, Setting Orange, or Jolly Roger, but shall not change this value more than once per nday. A statement that says "hoisting the X flag" is equivalent to saying "setting the Threat Flag value to X".

The meanings of the Threat Flags, in order of ascending threat, are as follows:

- Pink Ponies: None (Nothing to see here, move along)
- Polka Dots: Low (Strange things are afoot at the Circle B)
- Setting Orange: Moderate (Something is rotten in the state of B)
- Jolly Roger: High (Find a helmet)
- Black Watch Plaid: Imminent (Put on the helmet)

If, at any time, there are four or more PEPs who are Paranoid, the value of the Threat Flag is set to Black Watch Plaid. If, at any time, there are less than four PEPs who are Paranoid, and the value of the Threat Flag is Black Watch Plaid, the value of the Threat Flag is set to Jolly Roger.

### Rule 4E68: Socks

Socks are Game Objects.

There exists an Attribute called "Sock Color" with a Scope of all Socks, a Range of {Blue, Black, Brown, Burnt Sienna, Beige, Burgundy, Brick Red, Baby Blue}, and a Default Value of Blue. There exists an Attribute called "Sockholder" with a Scope of all Socks, a Range of all Potential Sockholders, and a default value of the XXX Corporation, where XXX is the color of that sock.

A Potential Sockholder who is the Sockholder of a Sock is said to "hold", "possess", or "own" that Sock. A Sock is said to "belong" to its Sockholder.

A Sock whose Sock Color is [color] may be referred to as "a [color] Sock", "a Sock of the Color [color]", "a Sock of [color]", or "a piece of [color] foowear". A Sock's Sock Color may be referred to as its Color.

A Potential Sockholder may transfer a Sock of a specified Color to another Potential Sockholder as a Game Action. One Sock of the specified Sock Color belonging to the Potential Sockholder has its Sockholder attribute changed to the other Potential Sockholder.

A Laundry Corporation is a Corporation which may create or destroy socks of its appropriate color. For each sock color there exists one Laundry Corporation titled "XXX Corporation" where XXX is the color of that sock. No other Corporation is a Laundry Corporation. A Laundry Corporation may only destroy socks of its color that are in its ownership.

### Rule 4E80: Laundress

There exists a ministry known as the Ministry of Laundry. The Minister of Laundry, also known as the Washerwoman, is responsible for maintaining a Public Display of all Sock Market activity, including the color of proposals.

### Rule 4E69: Investments & Earnings

There exists an Attribute called "Proposal Color" with a Scope of all Pending or Open Proposals, a Range of {Blue, Black, Brown, Burnt Sienna, Beige, Burgundy, Brick Red, Baby Blue, Blank}, and a Default Value of Blank.

A Player may, as a Game Action, change the Proposal Color of a Pending Proposal to a value of his choice. No Player may make more than one such change per nday.

When a Proposal Passes, if that proposal had a Proposal Color other than Blank, the XXX Corporation (where XXX is the color of that Proposal) has its macks increased by m100

### Rule 4E71: Operant Conditioning

#### The Beast

The Operantly Conditioned Beast (aka The Beast or The OCB) is an Outsider and a Player. The Beast perfoms Game Actions in one of two ways:

- Any given Player may, once per nweek, as a Game Action with no objection in two rdays, cause the Beast to take a single Game Action.
- The Beast is also capable of causing certain changes to the state of the Game, which are specified in Tricks*. Tricks are randomly performed on a fixed schedule (see below), and no Player may cause the Beast to perform a Trick as a Game Action.

#### The Tricks

There is an Attribute "Response" with a scope of all Tricks, a range of all positive integers, and a default value of 10.

As a Game Action, a Player may Reinforce the last Trick that has been performed, increasing its Response value by 1.

As a Game Action, a Player may Punish the last Trick that has been performed, decreasing its Response value by 1.

A Player who has Reinforced or Punished may not perform either of these Game Actions until the OCB next performs a Trick.

There is an Attribute "Timing" with a scope of all Tricks, a range of "Anytime" and "Voting", and a default value of "Anytime".

At the start of each nday 1, 5, and 9, the OCB performs a single Trick, randomly selected from among existing Tricks. The probability that a specific Trick is selected to be performed is equal to the proportion of the sum total of all Response values represented by the Response value of that Trick. When neither a Voting Period nor a Particular Voting Period are in progress, Tricks with a Timing of "Voting" are not included in the selection process and may not be performed.

As a Game Action, with support and without objection, a Player may Teach the OCB a new Trick, defining the changes to the gamestate that its performance enacts and, optionally, its Timing.

A Trick whose Response value would become 0 ceases to exist.

#### The Ranger

There exists a Ministry known as the Ministry of Fauna. The Minister of Fauna, also known as the Ranger, is responsible for maintaining a Public Display of the OCB's Attributes and Properties and of all Tricks as well as their Attributes.

Whenever the OCB is scheduled to perform a Trick according to the Rules, the Ranger is obliged to select a Trick to be performed, in accordance with the probabilities above and having previously announced the mode and modalities of this selection to the Public Forum. If the Ranger fails to do so within 1 rday, any Player who is the first to do so may carry out this selection, provided e respects all associated requirements.

### Rule 4E82: Subgames

There exists a Ministry known as the Ministry of Games. The Minister of Games, also known as the Gamemaster or GM, is responsible for maintaining a public display with the details of the current Subgame(s).

A Subgame is a Game Document. In order to be valid, a Subgame must: -Have a name -Specify how players may join or leave the Subgame -Specify a way for that Subgame to end and how winners will be decided -Specify a means of communication for players to take actions -Specify a Trophy to be awarded to the winner(s) of the Subgame

Subgames have the Attribute "Status" with a range of: Pending, Open, and Historical. When a Subgame is created, its status is set to Pending. The Gamemaster may change any Subgame status from Pending to Open as a game action. When a subgame is won, it's status is set to Historical.

## Rule Changes

### Rule 4E15: Proposals

#### The Ministry of Change

There exists a ministry known as the Ministry of Change. The Minister of Change, also known as the Chairman, is responsible for maintaining a Public Display of the current Proposals, including whether they have passed or failed if applicable.

At the end of the nday prior to the beginning of a voting period, the Minister of Change is obligated to publish a Game Document known as a ballot. Such a document should list all items to be voted upon during that voting period.

At the end of a voting period, the Minister of Change is obligated to publish the results of the voting, including each vote received, the final outcome for each item being voted upon, and the changes to any scoring as a result of voting.

#### Definition

Proposals are Game Documents. Each of the following Attributes has a Scope of Proposals:

- Title (Range: all strings; Default: the empty string)
- Body (Range: all strings; Default: the empty string)
- Status (Range: Pending, Open, Historical; Default: Pending)
- Success (Range: Won, Discarded, Lost, Undecided; Default: Undecided)
- Proposal Number (Range: null + all integers; Default: null)
- Conflicts (Range: all sets of other proposals; Default: the empty set)
- Dependencies (Range: all sets of other proposals; Default: the empty set)

If, in a set of two proposals, either lists the other as a Conflict, those proposals are said to Conflict with each other.

If one proposal lists another on its list of Dependencies, then the first is said to Depend on the second.

/* Note that a proposal may contain text in addition to its list of gamestate changes, but this text is generally ignored. It may be unclear whether or not a particular part of the text is a gamestate change; determining this is left to the Chairman and the justice system. */

#### Submission and Revision

Any player may submit a proposal at any time, or may revise a Pending proposal he owns by resubmitting it, unless a rule says otherwise. To submit a proposal, a player need only specify its Body. He may optionally also specify its Title, Conflicts, and Dependencies; if any of these are not specified, they default to being empty.

The player who submits a proposal is known as the Proposal's Author, and is said to own that proposal.

When a new proposal is submitted, it is assigned the Status Pending, the Success state Undecided, and the Proposal Number null. The Chairman is obligated to assign a new Proposal Number that is greater than all previously used Proposal Numbers to each proposal with a number of null.

/* Note that this doesn't include other things called Proposal Numbers from the distant past; the fact that five years ago there were proposals numbered in the thousands is irrelevant. */

As a Game Action a Player may withdraw a proposal with a status of Pending if they are the Author of that Proposal. A Proposal that is withdrawn has its Status set to Historical and its Success state set to Lost.

#### Voting

The Voting Period for a given nweek, or just "Voting", is defined as the period of time from the beginning of nday 9 of that nweek until the end of that nweek.

At the beginning of each Voting Period, all Pending proposals become Open.

A Registered Voter is an Outsider that is allowed to vote on Proposals.

A Registered Voter may submit a Vote on an Open proposal at any time. The Vote must be one of the words FOR, AGAINST, ABSTAIN, or SHELVE; other words are ignored

The most recent Vote on a proposal by a Registered Voter is called that Registered Voter's Final Vote on that proposal.

#### Tallying the votes

A Proposal's Stamina is equal to the number of Registered Voters whose Final Vote on that Proposal is FOR, plus the number of Registered Voters whose Final Vote on that Proposal is AGAINST, plus number of Registered Voters whose Final Vote on that Proposal is SHELVE.

A proposal's Strength is equal to the number of Registered Voters whose Final Vote on that proposal is FOR minus the number of Registered Voters whose Final Vote on that proposal is AGAINST or SHELVE.

When Voting or Particular Voting ends, the following events happen, in order:

- Each Open proposal with a Stamina less than one half the number of Vested players becomes Discarded.
- Each Open proposal with positive Strength becomes Won; each Open proposal with negative Strength that would have positive Strength if SHELVE votes were counted as FOR votes is Discarded; and all other proposals become Lost.
- Dependency Culling occurs (see below).
- Conflict Culling occurs (see below).
- Dependency Culling occurs again.
- All Open proposals that are Won Pass, in order by Proposal Number.
- All Open proposals become Historical

When a proposal Passes, the game is changed according to the instructions in its Body.

Proposals that do not Pass and are not Discarded are said to have Failed.

A proposal that is Shelved in two consecutive nweeks is considered both Lost and Failed and shall not appear on a later ballot.

#### Dependency Culling

When Dependency Culling occurs, every Open proposal is processed in ascending order by Proposal Number. When a proposal is processed in this manner, if it Depends on a proposal that is Lost or Discarded, then it becomes Lost itself. This process is repeated as long as there is any Open proposal that Depends on a Lost proposal and is not Lost itself.

#### Conflict Culling

When Conflict Culling occurs, every Open proposal is processed in descending order of Strength, and of Proposal Number when Strength is equal. When a proposal is processed in this manner, if it is Won, then every proposal that Conflicts with it becomes Lost.

### Rule 4E20: Players May Vote

All Players are Registered Voters unless otherwise specified by the rules.

### Rule 4E19: Scoring

Whenever a Proposal becomes Historical,

- Each Player, whose Final Vote on the Proposal was not ABSTAIN, gains 1
point.
- If the Proposal Passed, its Author's points increases by the amount of the
Proposal's Strength.
- If the Proposal Failed and was never Won, its Author loses 3 points.
Rule 4E28: Active Players

The group of Players that do not currently possess the Active property may be called "The Horde".

At the beginning of each nweek, the players that voted in the previous nweek gain the "Vested" property, the players that failed to vote in the previous nweek lose the "Vested" property.

When any Player performs a Game Action /*including registering as a Player */, he gains the Active property. Any Player can, as a Game Action, remove the Active property of another Player who has not performed a Game Action in the current or previous nweek.

### Rule 4E77: Tweaks

A Tweak is a Game Document describing changes to be made to the rules and/or game state of B Nomic. A Player may submit a single Tweak per nweek. A submitted Tweak cannot be revised after it has been submitted.

As a Game Action without Objection, a Player can Activate a Tweak he submitted during the current or previous nweek, provided he has not previously attempted to Activate the same Tweak. When a Tweak is Activated, the changes it describes take effect.

## Justice

### Rule 4E18: Judgment

#### The Oracle

There exists a ministry known as the Ministry of Questions. The Minister of Questions, also known as the Oracle, is responsible for maintaining a Public Display of the current Consultations. There exists an Object called the staff of ZOT. The Oracle holds the staff of ZOT.

#### Consultations

Any External Force may as a Game Action submit a Consultation.

Consultations are Game Documents that contain a Question that is to be Answered. The Question must be posed in such a form as to permit a yes or no reply. Consultations may also contain:

- Reasoning, meaning text that clarifies the intent of the Consultation.
- the name of a Player that is to be considered as the Unbeliever for that Consultation.
That player submitting the consultation will be known as Supplicant regarding that consultation.

Consultations are given a Consultation Number by the Oracle when assigned to a Priest. For each new Consultation, the Consultation number is usually equal to 1 or, if such Number is already in use, to the greatest existing Consultation Number incremented by one. The Oracle may arbitrarily override the normal assignment of Consultation numbers, and choose a number of his liking for a new Consultation.

A Consultation is in one of the states of Waiting, ZOTTED and Pondered. A Consultation is initially Waiting.

Whenever there exists a Consultation which has no priest assigned, the Oracle is obligated to either assign a priest to that Consultation or ZOT it.

#### ZOTTING

Upon submission of a Consultation the Oracle shall as a Game Action select a Priest for that Consultation. Alternatively the Oracle may wield the staff of ZOT and cause the Consultation to be ZOTTED, if in his insight he considers the contained Question to be malformed, ambiguous, irrelevant or otherwise unworthy. ZOTTED consultations have no further effect.

The Oracle may also ZOT a Waiting Consultation if has not been Answered yet and its assigned Priest requests him to do so. In this case the Oracle is required to grant the request or immediately reassign the Consultation to a new Priest instead.

If a Consultation is ZOTTED by the Oracle before he assigns it to a Priest, the Oracle is not required to record the Consultation in the Public Display.

#### Selecting a Priest

An Active Player, as a Game Action, may gain the Ordained Property. Any Player, as a Game Action, may remove their Ordained Property. Any Player that loses the Active Property also loses the Ordained Property.

Whenever a Priest is to be selected for a Consultation, the Oracle shall select one between the eligible Players. All Ordained Players, except the Supplicant, the Unbeliever if the Consultation names one, the Oracle and Players that have already been selected as Priests for that Consultation, are eligible for selection as Priests. If no Player is eligible, the Oracle is automatically selected as Priest.

#### The Answer

The selected Priest shall find inspiration in his knowledge of the Rules and, as a Game Action, Answer his assigned Consultation YES, NO, or , in cases where neither of these two answers can potentially be logically correct, PARADOX, causing it to become Answered. The Priest may also submit his own Reasoning, explaining how his mystical interpretation of the Rules has guided him in his Answer. If he deems it necessary the Priest may also submit as a game action an Oracularity detailing changes needed to correct the state of the game.

If a Consultation remains Answered for four full Ndays (or Ndelays if the clock is off), it becomes Pondered.

For the purposes of answering Consultations the words "True", "Affirmative" and "Correct" are to be considered synonymous with "Yes", the words "False", "Negative" and "Incorrect" are to be considered synonymous with "No", and the words "Maybe", "Undecidable" and "Göd Knows" are to be considered synonymous with "Paradox".

#### Automatic Reassignment

Any Priest, who is not the Oracle and has not answered a Consultation he has been assigned to within a Jiffy, ceases to be the Priest for any Consultations he is assigned to and loses the Ordained Property. If a Player loses the Ordained Property in this manner, he cannot regain the Ordained Property until the next nweek.

#### Overriding Consultations

When a Priest submits an answer to a consultation, within three ndays (or ndelays if the clock is off) since its submission, any player except the Priest, Unbeliever, and the Supplicant may, as a Game Action, make a Claim regarding the Answer and the Oracularity (if one exists). Such Claims will ultimately state that the player believes the answer (and Oracularity) to be Consistent or Inconsistent. If a Player submits multiple Claims, only the last one submitted shall be counted.

A Jiffy after the Answer has been submitted the Oracle shall tally any such Claims. If there exist more Claims of Inconsistency than claims of Consistency, the consultation ceases to be Answered and becomes Waiting. The Oracle shall then assign a new Priest to the Consultation. The previous Priest's answer and Oracularity (if any) is discarded.

#### Oracularities

As part of their answer a Priest may submit an Oracularity. An Oracularity is a Game Document which includes a list of changes to the rules and gamestate of B Nomic. By nature, an Oracularity is a transaction and is implied to be enclosed in "BEGIN TRANSACTION" and "END TRANSACTION" clauses.

If the answered question is in relation to an ambiguity in the rules, the Oracularity should address that ambiguity by including changes to the rules in question to clarify.

When a Consultation becomes Pondered then any Oracularity submitted with the answer is followed and the gamestate and rule changes it calls for take effect.

### Rule 4E72: Since We're not Using the Word...

A Indictment is a Game Document, which may be submitted at any time. It consists of

- An Accusation, which is a Crime
- An Example, which is an Offense of the Accusation that occured no more than one nweek before the time of submission of the Indictment
- An Offender, which is the Player allegedly involved in the Example criminally
- A Tidbit, which is the word "cheese," the word "CREAMPUFF," or the numeral "3"
- Reasoning clarifying the intent of the Indictment may also be submitted.

### Rule 4E73: The Judge

There exists a Ministry called the Ministry of Judging. The Minister of Judging, also known as the Judge, is responsible for maintaining a Public Display of all Indictments and their outcomes.

When a Indictment is submitted, the Judge becomes obligated to randomly select a Jury. To select a Jury, the Judge follows the following procedure (or an equivalent one):

- (1) Assign all Active Players a priority of 1. Assign the Judge a priority of 1/2. Assign the Offender and the Player who submitted the Indictment a priority of 0. Assign all members of The Horde a priority of 0. 
- (2) If there are at least three Players with a priority of 1, select a random group of three of them to be the Jury and exit the procedure. 
- (3) If any Players have nonintegral priority, round each Player's priority up to the nearest integer and repeat step 2. 
- (4) Place all Active Players on the Jury.

Each member of the Jury shall deliver an answer to the Public Forum. If a majority of the members of the Jury deliver answers of "GUILTY", the Jury Decides the Offender to be Guilty.

When the Judge Assigns a Punishment of a fine in macks the Guilty Player is obligated and is able to destroy that number of macks for no effect. Any Player who has not fulfilled their obligation to destroy macks as a result of a punishment is not a Registered Voter.

When the Judge Assigns a Punishment other than a fine in macks the results of that Punishment are carried out upon the Guilty Player as described in the rules.

### Rule 4E56: Shall I?

Taking a Game Action which the rules state a Player "shall not" take is a Misdemeanor.

Failing to take, within a Jiffy, a Game Action which the rules state a Player "shall" take is a Misdemeanor.

### Rule 4E59: Stop that!

Mildly spamming one of the mailing lists or the wiki is a Misdemeanor.

Severely spamming one of the mailing lists or the wiki is a Felony.

/* You can make the case to the Priest as to whether what you're doing counts as spamming, and as to how severe it is. */

### Rule 4E60: Contempt of Court

If a player submits 5 Consultations in the same nweek that are all ZOTTED, that player is Held in Contempt of Court.

Being Held in Contempt of Court is a Misdemeanor. The minimum penalty for being Held in Contempt of Court is a fine of 10m. The maximum penalty for being Held in Contempt of Court is a fine of 60m, plus a limit of at most one proposal during the following nweek.


## Stuff that doesn't really fit anywhere else

### Rule 4E30: Official Quantities

For all game purposes the following phrases are defined to mean the indicated numbers.

- A Few = 4
- A Jiffy = 3 rdays
- A Handful = 6
- An nDozen = 11
- A Thirnight = 12
- A Confused Baker's Dozen = 14
- A Bunch = 24
- A Metric Bunch = 25
- A Lot = 63
- A Bucketful = 96
- A Metric Bucketful = 100
- A Heck of a Lot = 365
- A Hell of a Lot = 366
- A Truckload = 960
- A Metric Truckload = 1000
- A Zillion = 100 000 000
- A Bajillion = 100 000 000 000 000
- An Insane Number = The number of players in the game

### Rule 4E27: Disambiguation

No text in any Rule shall be interpreted as a specific Player's name, unless that rule explicitly states that said text shall be interpreted as a specific Player's name.

### Rule 4E38: Pronouns

All personal pronouns shall be taken to refer to entities of any gender or of no gender regardless of the purported gender of the words used. Language intended to apply only to members of a specific gender must explicitly say that it does so.

### Rule 4E32: Tidiness Lists

If the Rules contain errors of spelling, inconsistent capitalization, or other trivial errors, any Player may as a Game Action and without objection correct these errors by submitting a Tidiness List.

A Tidiness List is a Game Document that lists spelling errors in the rules, and the proposed corrections. The time limit on objections for tidiness lists is set to two ndays.

/* for practical purposes it is allowed to actually go on and make the changes to the wiki at the same time as posting the Tidiness List, but please mark your changes clearly so that they may be reverted easily */

If the corrections in a Tidiness List take place the Player that submitted the Tidiness List gains one point for every three errors corrected. Tidiness Lists correcting less than three errors give no points.

### Rule 4E70: Contracts

A Legal Entity, as a Game Action, may create a Game Document known as a Contract. Upon doing so that legal entity becomes bound by that Contract. Legal Entities who are bound by a contract are known as parties to that Contract. A Contract may be changed only as the text of that Contract allows.

As a Game Action any Legal Entity may voluntarily become bound to a Contract unless the text of that contract would prohibit such an action. A Legal Entity may not become bound by a contract by any other means. A Contract may provide a means by which a Legal Entity may cease to be bound by that Contract. A Legal Entity may not cease to be bound by a contract by any other means.

A Player may submit a Consultation indicating that a specified Legal Entity who is bound by a specified Contract has failed (through either action or inaction) to fulfill the obligations and/or requirements bestowed on them by that Contract. If the Priest of the Consultation finds that specified Legal Entity did indeed violate the Contract in question, they shall submit an Oracularity which endeavors to equitably rectify the breach.

There exists a Ministry known as the Ministry of Business. The Ministry of Business, also known as the Arbiter, is responsible for maintaining a Public Display of all Contracts and their current text and parties.

If, at any time, a contract has less than one party, it ceases to be a Game Document.

### Rule 4E79: Incorporation

A Corporation is an entity defined by a Contract declaring itself to be a set of Articles of Incorporation. These Articles must, at a minimum, give the Corporation a name and define at least one Officer. Officers of a Corporation shall collectively ensure that the Corporation fulfills the obligations specified in its Articles. An Officer can, *unless otherwise specified in the Articles of Incorporation,* act on behalf of a Corporation by sending a message to the Public Forum explicitly stating that the Actions described in the message are being performed by the Corporation.

A Corporation is a Legal Entity.

### Rule 4E81: Legal Entities

A Legal Entity is a Potential Sockholder and a Currency Owning Object. Players are Legal Entities.

### Rule 4E76: Living up to our Name

Having recently come out of a slump, B is just now getting moving again. It has always and will always have recently come out of a slump. It will always be just now getting moving again.

## Emergencies

### Rule 4E0: In Case of Emergency

For the purposes of this rule, the term "Potential Emergency Participant" (or PEP) shall mean each of the current players of the game as defined by other rules. However, if who the current players are in the game is unclear, uncertain, or ambiguous, or if there are less than four such players, then it shall instead mean who the players were before such uncertainty or drop in player count. Each PEP has a Mental State, which is exactly one of Calm (default) or Paranoid. Mental States can only change as explicitly described by this rule.

A PEP can set his Mental State by posting a message to a Public Forum (or any forum that was a Public Forum within the past month) stating that he does so, and specifying his new Mental State.

If at least four PEPs are Paranoid, B Nomic becomes in a State Of Emergency. When this occurs, the following Procedure happens:

1. Game time is stopped. Whatever means used in the Game to track time is stopped as of the beginning of the Emergency. Pending events and deadlines relative to Game time, with the exception of those specified in this rule, are postponed until Game time resumes. Pending events and deadlines with absolute dates and times do not occur.
2. The PEP who most recently held the Minister of Ministries becomes the Emergency Coordinator.
3. The Emergency Coordinator shall designate a means for PEPs to communicate as the Emergency Forum and make a reasonable effort to notify other PEPs about the Forum's existence. If the Emergency Coordinator fails to do either of these within 24 hours, any PEP can designate an Emergency Forum if he notifies the other PEPs of its existence. The Emergency Forum must be reasonably accessible to all PEPs.
4. The Emergency Coordinator shall make a statement to the Emergency Forum that he is initializing the Pause. If he fails to do so within 24 hours, any PEP can do so instead. The Procedure tracks time spent using the Pause. When the the pause is initialized it is zero. Thereafter, until the completion of the Procedure, the Pause is increased by one each day at 00:00:00 UTC. Once per day, the Emergency Coordinator may announce to the Emergency forum their intention to increment the pause. If no PEP voices objection to this action on the Emergency Forum within 24 hours, then the value of the Pause is incremented by one. If, at any time, the Pause has been initialized but has not been incremented in the last 48 hours, it is incremented by one.
5. At any time before the value of the pause is 5, each PEP may submit a Refresh Proposal, aimed at either resuming or ending the Game, and may revise or withdraw his own Refresh Proposal, via the Emergency Forum. A Refresh Proposal consists of a list of changes which may affect any aspect of the Game or the state of the Game, including, but not limited to: rules, scores or other player attributes, the valid list of players, current holders of any Ministries, the legitimacy and/or actuality of any action taken in the context of the Game, etc.
6. When the value of the Pause is 5, any PEP can, and the Emergency Coordinator shall, gather all submitted Refresh Proposals into a Ballot and publish it.
7. Each PEP may cast a single Ballot by announcing it via the Emergency Forum. This Ballot shall rank some (or all) of the Refresh Proposals in order of preference, with the most-preferred alternative being ranked first, and less-preferred alternatives being given subsequently higher integers.
8. When the value of the Pause is 7, any PEP can, and the Emergency Coordinator shall, tally the votes in the following manner:
    - All Ballots are counted as one vote for the top choice given that has not been eliminated. If all ranked candidates on a Ballot have been eliminated, that Ballot is discarded and not counted in future rounds of voting.
    - If a Refresh Proposal holds a majority of the votes, that Refresh Proposal is selected and the Procedure moves to Step 9.
    - If not, The Refresh Proposal with the fewest votes is eliminated. In case of a tie for having the fewest votes, one RP is selected at random from among the tied options and eliminated.
9. All changes listed in the selected Refresh Proposal occur, implemented by the Emergency Coordinator as needed. All PEPs become Calm.

If all current Emergency Procedures have been running for 14 days or more, any PEP can initiate another one, to run independently of the current one. This Emergency Procedure will start at step 3, and the PEP that initiated it will be the Emergency Coordinator.

If, at any point during the State of Emergency, there are less than four Paranoid PEPs, all running Emergency Procedures stop and B Nomic stops being in a State of Emergency, and normal Game time resumes.

At the beginning of Mulberry, nday 3, any PEPs who are Paranoid become Calm if, and only if, the value of the Threat Flag is Pink Ponies.

