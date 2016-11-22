# Rules of B Nomic - February 1, 2008

From: https://web.archive.org/web/20070906014937/http://b.nomic.net/index.php/Rules

## Foundation

### Rule 4E1: The Game of B

The name of this game is B Nomic.

### Rule 4E2: Game Objects

The game of B Nomic consists entirely of Game Objects, which may be known simply as Objects. Anything that exists in the game is an Object, and anything that is not an Object is not in the game.

Game Objects can only be created, destroyed, or modified if allowed by the Rules, in a manner explicitly governed by the Rules.

### Rule 4E10: A Peculiar Quality

Any Game Object may possess a non-negative, finite, number of Properties.

A Property is described by a unique string of alphanumeric characters.

Properties may only be granted or removed as described in the rules, or by proposal.

### Rule 4E11: Attributes

An Attribute is a game object, defined in the rules. Each Attribute has a Scope, a Range, and a Default Value. The Scope is a set of Game Objects to which the Attribute applies. The Range is the set of possible values for the Attribute. The Default Value is an element of the Range.

Each element of the Scope of an Attribute possesses an Instance of that Attribute. If the element in question does not possess such an Instance, one is created immediately. If a Game Object outside the Scope of an Attribute possesses an Instance of that Attribute, the Instance in question is destroyed immediately.

Instances of an Attribute are Game Objects which have a Value. The Value of an Attribute must be a member of the Range of the Attribute. When created, the Value of an Instance is its Attribute's Default Value, unless otherwise specified.

For brevity, the value of an instance of an attribute of some object may be referred to as the value of that attribute on the object in question.

The Scope, Range, and Default Value of Attributes are static and defined in the Rules. The Value of Instances of Attributes can be changed only as specified in the Rules.

### Rule 4E3: Outsiders

An External Force is anything which exists independently of the game. That is, it would still exist if the game stopped existing, and would still exist if the game had never started existing.

An Outsider is a Game Object representing the projection into the Game of an External Force. As a Game Object, an Outsider is bound by the Rules. These Rules do not purport to regulate External Forces except in relation to their interaction with the Game as Outsiders. [[ i.e., something that exists outside of the game but is also acknowledged by the rules as influencing the state of the game, and thus exists within the game as well, such as a player.]]

### Rule 4E6: Fora

A Forum is any External Force that allows Outsiders to communicate. Each forum may be designated as one of the terms Private, Public, or Discussion. All Fora are initially Private.

### Rule 4E5: Comment Text

In each Game Document, with the exception of this paragraph, text between a forward slash+asterisk character combination and an asterisk+forward slash character combination or between double square brackets (that is, text between "/*" and "*/" or between "[[" and "]]") shall be deemed Comment Text. Comment Text has no direct effect on the state of the game, although it can be read.

### Rule 4E36: Rules

Rules are Game Documents that define how this game is played. Each Rule must have a number and may have a name. Rule are numbered from a set that initially contains all positive integers and zero. When a new rule is created, the Minister of Law is obligated to assign it the lowest number available in the set, and then remove that number from the set. Each rule number shall be prefixed with the notation "4E" (for Fourth Era) to distinguish it from past rules in previous eras of B Nomic. Where a Rule, Proposal, Game Action, or other Game Document refers to a Rule by its number without a prefix, it shall be taken, by default, to refer to a Rule prefixed with the notation "4E". /* For example, one can say "Rule 15" to refer to Rule 4E15 */

Rules may be contained in named Sections.

There exists a ministry known as the Ministry of Law. The Minister of Law, also known as the Rulekeeper, is responsible for maintaining a Public Display of the current Rules and Victory Conditions.

The Rulekeeper may, as a Game Action without Objection, do any of the following:
- Create a Section.
- Remove a Section, causing all Rules in that section to no longer be contained by a Section.
- Move a Rule into or out of a Section.
- Change a Rule's Title

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

If the Clock is Off, there are no Vacant Ministries, and there are no outstanding ministerial obligations (other than the one described in this paragraph) the MoM is obligated to turn the Clock On. When the Clock is turned On, the ndelay is set to zero.

#### Time

Each time that the Clock nday value changes a new nday begins. /\*the previous nday ends in the moment immediately before the Clock change\*/ A period of one nday is the time intervening between two consecutive changes of the Clock nday value. Each time that the Clock nweek value changes a new nweek begins. /* the previous nweek ends in the moment immediately before the Clock change*/ A period of one nweek is the time intervening between two consecutive changes of the Clock nweek value.

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
- nday 5 = Corvette
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

### Rule 4E9: Eras

The First Era of B Nomic is the time starting with the creation of the game (approx. 5 Dec 2001, prompted by a five-month lull in A Nomic) and ending immediately before the start of The Second Era of B Nomic.

The Second Era of B Nomic is the time starting with nweek 85 (approx. 4 Apr 2005, prompted by data loss when the bnomic.org server crashed) and ending immediately before the start of The Third Era of B Nomic.

The Third Era of B Nomic is the time starting with nweek 112 (approx. 14 Nov 2006, prompted by another five-month lull) and ending immediately before the start of The Fourth Era of B Nomic

The Fourth Era of B Nomic is the time starting with nweek 135 (10 Dec 2007, prompted by a second State of Emergency in 2 nweeks), and continuing to the present.

### Rule 4E26: The Temporal Prime Directive

No rule or game action may require or force any retroactive changes to the game state. It is, however, permissible, to create rules or perform otherwise-legal game actions that simulate retroactive changes to the game state.

## Actions

### Rule 4E7: Game Actions

A Game Action is defined as any activity specified by the Rules that changes the state of the game. Other Outsiders may also take Game Actions if explicitly permitted by the rules. To perform a Game Action, an Outsider must post a message to a Public Forum specifying that he is taking that action. He must also specify any targets and/or parameters necessary for that action [[for example, you must specify a proposal in order to vote against a proposal]]. Unambiguous targets and parameters specified in Game Actions are valid regardless of capitalization, punctuation, or exact wording unless explicitly required by a Rule. He may list multiple actions that he wishes to take, in which case he takes them in the order he lists them. He may also state a specific positive integer to perform a particular action that many times (if legal, of course) sequentially. The Rules also have the power to cause an Outsider to take Game Actions whether he posts or not.

Game Actions occur upon reaching the appropriate fora, in the order they arrived, unless a rule states otherwise. A Game Action that is caused by a Rule instead of by a Forum Post takes place at the time specified by the rule.

An Outsider may post a message to a Public Forum specifying that he will perform a specified Game Action at a specified time in the future, with reference either to The Clock or to Coordinated Universal Time (UTC). A Game Action performed in this manner takes place at the time specified by the Outsider, defaulting to the start of the next occurrence of any period of time unless otherwise specified by the Outsider [[ *e.g.* if one writes "I do X on nday 8", X happens at the start of the next nday 8]]. If multiple Game Actions are set to be performed in this manner at the same time, they occur in the order they arrived at the appropriate forum.

Text to the effect that "any player may do X" should be interpreted to mean that X is a Game Action; but such a declaration implies that only players may take the Game Action X (unless another declaration permits other Outsiders to as well).

### Rule 4E21: Objecting

The Rules may explicitly require a specific type of action to be performed "without N objections" where N is a positive natural number. The phrase "without objection" is synonymous to "without 1 objection"

An action that must be performed without N objections occurs 2 ndays after the nday the action was attempted if, and only if, N Players do not object to the action. A rule may give a different time that must elapse before a specific action occurs without objection, and in that case, that rule takes precedence.

Objecting is a Game Action and must be performed in a Public Forum.

A Player may not object to an action he attempted to perform. Neither may a Player object to an action that another Player who is currently his Twin attempted to perform.

### Rule 4E22: Supporting

The Rules may explicitly require a specific type of action to be performed "with N supporters" where N is a positive natural number. The phrase "with support" is synonymous to "with 1 supporter"

An action that must be performed with N supporters occurs after N Players support the action. If the action does not receive the required support 2 ndays after the nday the action was attempted, the action shall fail and does not occur. A rule may give a different time that must elapse before a specific action fails without support, and in that case, that Rule takes precedence.

Supporting is a game action and must be performed on a public forum.

A Player may not support an action he attempted to perform.

### Rule 4E12: Transactions

As a Game Action, an Outsider can submit a Transaction. A Transaction consists of:

- A clear statement marking the Start of the Transaction, such as "BEGIN TRANSACTION".
- A list of Game Actions and assertions about the state of the game.
- A clear statement marking the End of the Transaction, such as "END TRANSACTION".

The list is considered in sequence. If it would be legal for the Outsider to take each Game Action within the Transaction exactly as specified, and each assertion would be true at the time it occurs within the list if the Game Actions were so taken, then the Transaction is said to Succeed. Otherwise, the Transaction is said to Fail. If it cannot be determined with finality and certainty whether or not one of a Transaction's assertions is true, or whether one of its Game Actions is legal, then the Transaction Fails.

The Game Actions in a Transaction that Succeeds occur just as though the Outsider had taken them individually.

A Transaction that Fails has no effect.

### Rule 4E8: Submission

The rules may state that it is legal for Outsiders to Submit certain document types as a Game Action. To Submit a Game Document, an Outsider must provide a full description of the Document in the Public Forum message where they take the Action of Submitting.

### Rule 4E13: Unregulated Actions

Whatever is not prohibited or regulated by a rule is permitted and unregulated. However, for the purposes of this rule an action or object is regulated if described by a rule.

### Rule 4E4: Joining and Leaving

There exists a ministry known as the Ministry of Society. The Minister of Society, also known as the Registrar, is responsible for maintaining a Public Display of the current Players and Factions and their Attributes and Properties, as well as a Public Display of the current Public and Discussion Fora.

A Player is an Outsider who consents to be governed by the rules, fulfills all requirements for continued playerhood specified by the rules, and has become a Player in a manner specified by the rules that were in effect at the time e became a Player.

Any Human External Force that is not already a Player may request to join the game by posting a message to a Public Forum containing a request to become a Player and a uniquely identifying name that e wishes to be known by.

As a Game Action, any player may Ratify or Reject such a request within 10 rdays of its being made. The External Force making the request becomes a Player as soon as all of the following are true:

- At least two rdays have passed since the request was made.
- The request has been Ratified by at least two Players.
- Fewer than two players have Rejected the request.

A Player may cease to be a Player by Forfeiting the game; this must be done in a Public Forum unless there are no working public fora, in which case he may notify the Player he most recently knew was Registrar privately instead.

No restrictions may be placed on when a player may forfeit; any player may forfeit the game at any time (regardless of any timekeeping device used in the game).

## Ministries

### Rule 4E45: Ministries

A Ministry is a Game Object that can be assigned to at most one Player. It represents the responsibility of that Player to keep Players aware of the state of a particular aspect of the game, and may also represent the power of that Player to affect the gamestate in ways specified in the Ministry's definition. If a Ministry's defined powers conflict with any other part of the Rules, the latter takes precedence.

A Ministry that is not assigned to a player is Vacant.

The terms "post holder", "pot holster", "post holder designate", and "Minister" refer to the Player in possession of a given Ministry. This can be abbreviated "PHD".

### Rule 4E46: Assigning Ministries

A Player may, as a Game Action, assign a Vacant Ministry to himself.

### Rule 4E47: Resigning from Ministries

A Minister may Resign from his Ministry via Game Action. At that time, the Ministry becomes Vacant.

### Rule 4E48: Usurping Ministries

There exists an attribute Retainer with a scope of all Ministries, a range of all integers, and a default value of 50. At the end of each nweek, the Retainer for each Ministry is reduced by 10.

As a Game Action, a Minister may pay any number of points to increase the Retainer of his Ministry by a corresponding amount, provided this does not cause him to have a negative number of points.

As a Game Action, any Player may pay any number of points to reduce the Retainer of any Ministry by a corresponding amount, provided this does not cause him to have a negative number of points.

As a Game Action, any Player may pay a number of points equal to the Retainer of a non-vacant Ministry to usurp that Ministry, unless the current Minister of that Ministry is his Twin. The previous Minister ceases to be the MInister of that Ministry, and the usurper becomes the new MInister of that Ministry.

Whenever a Ministry has a new Minister, the retainer for that Ministry is set to the default value. Whenever a Ministry has a non-positive Retainer, that Ministry is vacated.

### Rule 4E49: Ministry Rewards

At the end of each nweek, for each Ministry that has been continuously held by the same minister since the clock was first turned on that nweek, its Minister earns 50 macks (or 10 macks if the Ministry is a mini-Ministry).

### Rule 4E50: Public Displays

A Public Display is a display of an aspect of the current state of the game in a form easily accessible to all Players. Good Public Displays can include the B Nomic wiki or posting on a regular basis to a Public Forum.

If the rules require a Ministry to maintain a public display, then that Ministry is obligated to update that public display to reflect the current gamestate whenever the data related to is is modified. However, this obligation is fulfilled even if there are accidental errors and/or omissions in the updated data of the public display.

Any player may challenge a public display that is maintained by a Ministry as a Game Action by listing any errors he believes to be present in that public display. The Minister who maintains that display is obligated to address those errors by either correcting them or indicating why he believes them to be already correct.

### Rule 4E51: The MetaMin

There exists a Ministry called the Ministry of Ministry, also known as the MetaMinistry. The Minister of Ministry may be referred to as the MoM, the MetaMin, or Kurt Gödel.

The MetaMin is responsible for maintaining a Public Display of all existing Ministries, showing their names, responsibilities, retainers, and current holders.

The MetaMin is also responsible for tracking and displaying any state of the game that isn't covered by another Ministry.

### Rule 4E52: MiniMinistries

A MiniMinistry is a Ministry that is not explicitly defined by the rules. Any Minister of a MiniMinistry may be referred to as a MiniMin.

The MetaMin may create a MiniMinistry at any time, specifying its name and its responsibilities. He may also dissolve any MiniMinistry at any time.

### Rule 4E53: Ministerial Obligations

A rule or passed proposal can create an obligation for a Ministry to take some action within its powers. A Minister shall fulfill any obligations on his Ministry in a Jiffy.

ny Minister who fails to perform an obligation within the allotted time can be removed from his Ministry by any Player as a Game Action.

Whenever a new Minister takes over a Ministry, the time limit for any obligations on that Ministry are reset. Therefore a new Minister shall always have a Jiffy to fulfill any obligations on the Ministry he has taken over.

## Gameplay

### Rule 4E17: Points

Any Game Object may have points. Points are Game Objects. The number of points an object possesses may also be referred to as that object's "score." An object's score cannot be less than zero.

### Rule 4E33: Currency

A "currency owning object", or COO, is a type of game object that can own currency (also called "money"). All players are currency owning objects.

The rule or rules defining a new currency will define an attribute the scope of which is all COOs. The value of this attribute shows how much of that currency the COO has.

A COO can give currency to another COO by a game action, as follows: he specifies an amount (which cannot be greater than the value of his currency attribute) and a currency; his currency attribute for that currency goes down by the amount; the receiving COO's currency attribute for that currency goes up by the amount.

If the COO has a non-positive currency attribute for a given currency, then he cannot give that currency to another COO. If for any reason the receiving COO's currency attribute cannot go up, or the giving COO's currency attribute cannot go down, then nothing happens.

Players can, via game action, exchange points for currency. The rule or rules defining the currency will set the exchange rate. The player declares how many points he wishes to exchange (which cannot be less than 0 or more points than he has) and the currency he wishes to receive. He loses that many points and gains (exchange rate x points) in the currency. If for any reason the amount of his points cannot go down or the amount of his chosen currency cannot go up, then nothing happens.

### Rule 4E34: Mackerel

The default currency of this game is mackerel, also known as a mack (singular) or macks (plural). This can be shortened to a lowercase m. [[See below.]]

There is an attribute "mackerel": scope is all currency owning objects; range is positive integers; default value is 50. The value of this attribute should always be expressed starting with a lowercase m, for example, m50.

The points -> mackerel exchange rate is 5.0 - that is, 1 point may be exchanged for m5.

### Rule 4E35: devices

A "device" is a type of game object.

A "device owner object", or DOO, is a type of game object that may own devices. All players are device owner objects.

There is an attribute "device owner": scope is all devices; range is all device owner objects. The default value is defined when the device is defined. The "owner" of any given device is the value of the device owner attribute of that device (that is, the owner is the DOO that the attribute points to).

A device is either "unique" or "non-unique". There cannot be more than one of each unique device in the game at any given time. When a non-unique device is defined, the definition must state how many such devices exist.

A device may have powers. Each power consists of:

- An Effect: what happens when the power is used; and
- A Trigger: something that must happen to trigger the effect; and
- Zero or more Conditions: things that must be true for the effect to take place; and
- Zero or more Properties.

The rule or rules defining a device detail the powers associated with it.

If there is any choice to be made about how a device is triggered or what objects it affects then the owner and only the owner of the device makes that decision; and must make it when it is triggered. The rules must explicitly state the nature of the choice. If there is any other ambiguity in the rules about how a power assigned to a device works, then that power has no effect.

The owner of a device may transfer ownership to another DOO. If the owner is a player, then this is done via a game action - the player declares who/what the new owner is. If the owner is not a player, then the rules must explicitly state under what circumstances ownership changes and exactly what happens. In both cases the owner attribute changes to the new DOO.

The owner of a device may destroy it by expressing the wish to do so in a public forum.

A "blueprint" is a type of game object that has no powers, but specifies a set of Attributes (except for device owner), Properties, powers, Properties of powers, and default states that can be used to define a device.

A blueprint is either "unique" or "non-unique". A unique blueprint is used to define a unique device, and ceases to exist upon definition of said device. A non-unique blueprint is used to define a non-unique device, and may be used repeatedly and indefinitely.

Price is an Attribute with a Scope of all blueprints, a Range of nonnegative rational amounts of currency, and a Default Value of 50 mackerel.

If a Device has the Cursed Property, the Owner of the Device:

- cannot destroy the device; and
- cannot transfer ownership of the device unless allowed by a power of the device.

If a power has the Cooldown Property, that power can only be triggered if it has not been triggered on that device during the current nweek.

If a power has the RPG Property, the owner of the device can only use that power of the device if he is not Dead, and, unless that power specifies otherwise, it has no effect if it targets a Dead Player.

If a power has the Disposable Property, that device ceases to exist after that power's effects have occurred.

### Rule 4E37: The Ministry of Goods

There exists a ministry known as the Ministry of Goods. The Minister of Goods, also known as the Artisan, is responsible for maintaining a Public Display of all currently existing devices and their Attributes, Properties, and current states. In addition, the Artisan must maintain a Public Display of all currently existing blueprints and their Attributes, Properties, and default states.

The Artisan may, as a Game Action on behalf of the Ministry of Goods and without 2 objections within 2 ndays, create a blueprint. The Ministry of Goods may only create a single blueprint in a given nweek, and can do so no later than Corvette [[nday 5]] of that nweek.

Any player with sufficient currency may purchase a device from the Ministry of Goods. Upon purchase, a device is instantly defined based on a blueprint designated by this player, who becomes the device owner. The price, as specified by the blueprint in question, is instantly subtracted from this player's currency.

To purchase a non-unique device, a player announces his intent via a Public Forum, as a Game Action. The Artisan may, at any time and without 2 objections within 2 ndays, alter the price of any non-unique blueprint.

Any unique blueprint is put to auction immediately upon creation. Any player, including the Artisan, may, as a Game Action, submit a non-retractable bid via a Public Forum, specifying an amount of mackerel. All bids must be an amount of macks divisible by A Metric Bunch. The highest amount of mackerel bid on a blueprint is its price. Bidding ends at the start of Zarpint [[nday 11]], at which time the unique device is purchased, if possible, by the highest bidder. A highest bidder with insufficient mackerel may attempt to collect sufficient mackerel during 1 additional nday, at the end of which purchase occurs if possible. If he fails to collect sufficient mackerel, his Voting Power is set to 0, he loses 25 points, and the next highest bidder may purchase the unique device 1 nday later. If neither of the two highest bidders successfully purchases the unique device, or if such bidders do not exist, the unique blueprint ceases to exist without device creation.

### Rule 4E39: Message Of The nweek

There exists a unique Game Object called the Message Of The nweek, also known as the motnw. The motnw has one Attribute called the Message, with a Scope of the motnw Object, a Range of any string of between 1 and 256 characters inclusive, and a Default Value of "This space intentionally left blank".

The Registrar, as a Game Action with Support, may change the value of the motnw Message, but cannot change the value more than once in an nweek.

The value of the motnw Message Attribute should be prominently posted on a Public Display. [[the main page of the B Nomic wiki is ideal]]

### Rule 4E24: RPG

There is an attribute "Hit Points", also known as "HP", with a scope of all Players, a range of all non-negative integers, and a default value of 10.

If a Player's Hit Points would ever be set to a value less than 0, it is instead set to 0. Any Player whose Hit Points equal 0 is considered to be "Dead". All other players are considered to be "Alive".

There is an attribute "Maximum Hit Points" with a scope of all players, a range of all non-negative integers, and a default value of 10. Thrice per nweek (at the end of ndays 4, 8, and 12), any player who is "Alive" whose hit points are lower than his attribute "Maximum Hit Points" shall recover 1 hit point up to the value of their attribute "Maximum Hit Points."

A Player may not perform any action that directly causes the Hit Points of another Player who is currently his Twin to be reduced.

### Rule 4E25: Levels

There is an Attribute, named Level, with a Scope of all Players, a Range of integers between 1 and 10 inclusive, and a default of 1. On nday 1 of each nweek, each Player whose current Level is less than the Level corresponding to his Points in the table below has his Level set to the corresponding Level in the table. Each Player whose current Level is higher than the Level corresponding to his Points in the table below has his Level reduced by 1.

- Level 1: 0 <= Points < 6
- Level 2: 6 <= Points < 13
- Level 3: 13 <= Points < 20
- Level 4: 20 <= Points < 33
- Level 5: 33 <= Points < 53
- Level 6: 53 <= Points < 86
- Level 7: 86 <= Points < 140
- Level 8: 140 <= Points < 226
- Level 9: 226 <= Points < Heck of a Lot
- Level 10: Heck of a Lot <= Points < 591
- Level 11: 591 <= Points < A Truckload
- Level 12: Points >= A Truckload

### Rule 4E57: The Field

The Field is a map consisting of a grid of squares arranged into rows and columns. Each square on The Field is adjacent to the four squares directly bordering it. Unless otherwise specified in the current Field Match, The Field is a torus, and squares along the edges are adjacent to squares along the corresponding edges.

There exists a Ministry known as the Ministry of Play. The Minister of Play, also known as the Referee, is responsible for maintaining a Public Display of the Field, all Field Objects, and their attributes and properties.

A Field Object is a type of Game Object which may occupy one or more squares on The Field. Each Field Object has an owner, which is typically a Player. Each Field Object has a Size property which represents how many squares that Field Object occupies on The Field, and is by default 1 x 1. In addition, each Field Object may have other properties and attributes assigned to it by it's describing Field Match.

The Field and each Field Object may have one or more actions attached to it. Every action has: A Trigger - This is a set of conditions that must be true for this action to take place. An Effect - This is what takes place when the conditions in the Trigger are true. Such effects might be (but are not limited to):

- Creating, destroying, or modifying a Field Object
- Placing a Field Object onto a paticular location in the Field
- Moving a Field Object on the Field.
- Modifying the ownership, size, or another property or attribute of a Field Object.

If the effects of an action of The Field or a Field Object would conflict with the rules, that portion of the effect is null and void.

An Invokable Action is an action of The Field or a Field Object which has a triggering condition of a Player taking a specific Game Action. Typically, players can only use Invokable Actions only on Field Objects they own.

### Rule 4E58: Field Matches

A Field Match is a Game Document. The Referee is responsible for maintaining a Public Display of all Field Matches. A proposal may create, modify, or destroy a Field Match. In order to be valid, a Field Match must:

- Have a name
- Specify a size for the field in rows & columns.
- Describe one or more types of Field Objects.
- Specify any actions for The Field and the described Field Objects, including at least one Invokable Action.
- Specify one action whose effect to cause the end of that Field Match, and possibly declare one or more winners of that Field Match.
- Specify a means of communication for Invokable Actions (ie: a private message to the Referee, a public message to the forum)
- Specify a Trophy to award when the Win by Field Match Victory Condition is triggered.

If there is not presently one, the Referee may choose one Field Match to be the Current Field Match as a Game Action. Players are encouraged not to modify the Current Field Match by proposal unless necessary. When the Referee selects a Current Field Match, he sets the size of The Field to what is specified in the Current Field Match, and then carries out the effects of any actions of The Field which occur when that Field Match becomes current (in the order they are listed in the Field Match).

When there is a Current Field Match, an Outsider may make an Invokable Action related to the Current Field Match by the means specified in the Current Field Match. When the Referee receives a request to make an Invokable Action, he is obligated to Turn the Field.

The Priority List is a Public Display maintained by the Referee. The Priority List shall contain a list of all Field Objects currently in existence on The Field. Whenever a new Field Object is created by an action, the Referee shall add that object to the bottom of the Priority List. If multiple Field Objects are created at the same time, the Referee shall add them in random order. If a Field Object is destroyed, the Referee shall remove it from the Priority List.

When the Referee Turns the Field, he does the following:

1. For each action of The Field (in the order they are listed in the Current Field Match) if the triggering conditions are true, the Referee carries out the effects of that action.
2. Starting at the top of the Priority List and evaluating each Field Object in order, for each action of that Field Object (in the order actions are listed in the Current Field Match) if the triggering conditions of that action are true, the Referee carries out the effects of that action.
3. The Referee updates The Field and the Priority List to reflect their current state. Note that some actions (such as Invokable Actions) may be triggered multiple times in the same Turn of the Field. When such is the case, the Referee carries out the effects of that action for each time the action is triggered.

If, while Turning the Field, the effects of an action cause the end of the Current Field Match, that Field Match ceases to be the Current Field Match, all Field Objects are destroyed, and the Priority List and Field are cleared.

### Rule 4E61: DNA and twins

There is an Attribute "DNA" with a Scope of all Players, a Range of two-character-strings composed entirely of the uppercase letters A, T, G, and C, and a Default Value of AA.

Once per nweek, as a Game Action, a Player who has not yet Voted on any currently Pending Proposals may Mutate, changing only one of the characters that forms his DNA but leaving both characters in the same order.

Players with identical DNA are said to be Twins. In no case shall a Player be considered to be his own Twin.

### Rule 4E16: Victory

Trophies are Game Objects. The number of Trophies held by a player is known as that player's Win Count. Players may only receive Trophies in accordance with this rule. Each Trophy has a description, which is a block of text describing what the Trophy looks like.

Victory Conditions are Game Documents.

Each Victory Condition has four parts:

- A Trigger: The event that must happen to cause someone to win, plus any required conditions on the gamestate.
- Victors: A clause defining which player(s) win.
- A Cleanup: A set of gamestate changes that happen when this condition takes effect (presumably that make it so that the condition is no longer satisfied).
- A Prize: A description of the Trophy that is awarded to each Victor.

If the events in a Victory Condition's Trigger happen, then that Condition becomes Fulfilled, unless it already was. When a condition becomes Fulfilled, its Victors are each awarded a Trophy with the description given by its Prize, and then its Cleanup happens.

At the end of each nweek, every Fulfilled Victory Condition ceases to be Fulfilled.

/* In other words, you can't win the same way twice in an nweek. */

### Rule 4E40: Threat Awareness

There exists a unique Game Object called the Threat Awareness Flagpole. There exists an Attribute named the Threat Flag, with a Scope of the unique Threat Awareness Flagpole, a Range of either "Pink Ponies", "Polka Dots", "Setting Orange", "Jolly Roger", or "Black Watch Plaid", and has a Default Value of Pink Ponies.

The Minister of Ministries is responsible for updating the Threat Flag, as he sees fit, to notify players of the potential dangers to the state and integrity of the Game. The Minister of Ministries, as a Game Action, may change the value of the Threat Flag to either Pink Ponies, Polka Dots, Setting Orange, or Jolly Roger, but shall not change this value more than once per nday. A statement that says "hoisting the X flag" is equivalent to saying "setting the Threat Flag value to X".

The meanings of the Threat Flags, in order of ascending threat, are as follows:

Pink Ponies: None (Nothing to see here, move along)
Polka Dots: Low (Strange things are afoot at the Circle B)
Setting Orange: Moderate (Something is rotten in the state of B)
Jolly Roger: High (Find a helmet)
Black Watch Plaid: Imminent (Put on the helmet)
If, at any time, there are four or more PEPs who are Paranoid, the value of the Threat Flag is set to Black Watch Plaid. If, at any time, there are less than four PEPs who are Paranoid, and the value of the Threat Flag is Black Watch Plaid, the value of the Threat Flag is set to Jolly Roger.

## Voting

### Rule 4E15: Proposals

#### The Ministry of Change

There exists a ministry known as the Ministry of Change. The Minister of Change, also known as the Chairman, is responsible for maintaining a Public Display of the current Proposals, including whether they have passed or failed if applicable.

At the end of the nday prior to the beginning of a voting period, the Minister of Change is obligated to publish a Game Document known as a ballot. Such a document should list all items to be voted upon during that voting period.

At the end of a voting period, the Minister of Change is obligated to publish the results of the voting, including each vote received, the final outcome for each item being voted upon, and the changes to any scoring as a result of voting.

#### Definition

Proposals are Game Documents. Each of the following Attributes has a Scope of Proposals:

- Title (Range: all strings; Default: the empty string)
- Body (Range: all strings; Default: the empty string)
- Status (Range: Pending, Hurried, Open, Historical; Default: Pending)
- Success (Range: Won, Shelved, Lost, Undecided; Default: Undecided)
- Proposal Number (Range: null + all integers; Default: null)
- Conflicts (Range: all sets of other proposals; Default: the empty set)
- Dependencies (Range: all sets of other proposals; Default: the empty set)

If, in a set of two proposals, either lists the other as a Conflict, those proposals are said to Conflict with each other.

If one proposal lists another on its list of Dependencies, then the first is said to Depend on the second.

/* Note that a proposal may contain text in addition to its list of gamestate changes, but this text is generally ignored. It may be unclear whether or not a particular part of the text is a gamestate change; determining this is left to the Chairman and the justice system. */

#### Submission and Revision

Any player may submit a proposal at any time, or may revise a Pending proposal he owns by resubmitting it, unless a rule says otherwise. To submit a proposal, a player need only specify its Body. He may optionally also specify its Title, Conflicts, and Dependencies; if any of these are not specified, they default to being empty. He may not specify a Conflict with a Proposal whose Author is currently his Twin.

The player who submits a proposal is known as the Proposal's Author, and is said to own that proposal.

When a new proposal is submitted, it is assigned the Status Pending, the Success state Undecided, and the Proposal Number null. The Chairman is obligated to assign a new Proposal Number that is greater than all previously used Proposal Numbers to each proposal with a number of null.

/* Note that this doesn't include other things called Proposal Numbers from the distant past; the fact that five years ago there were proposals numbered in the thousands is irrelevant. */

As a Game Action a Player may withdraw a proposal with status Pending if they are the Author of that Proposal. A Proposal that is withdrawn has its Status set to Historical and its Success state set to Lost.

#### Voting

The Voting Period for a given nweek, or just "Voting", is defined as the period of time from the beginning of nday 9 of that nweek until the end of that nweek.

At the beginning of each Voting Period, all Pending and Hurried proposals become Open.

A Registered Voter is an Outsider that is allowed to vote on Proposals. There is an Attribute Vote Power with a Scope of Registered Voters, a Range of the nonnegative rational numbers, and a Default Value of 0.

A Registered Voter may as a Game Action set their Vote Power to a number lower than its current value.

A Registered Voter may submit a Vote on an Open proposal at any time. The Vote must be one of the words FOR, AGAINST, ABSTAIN, or SHELVE; other words are ignored

Voting AGAINST a Proposal whose Author is currently one's Twin constitutes a Felony known as Blood Betrayal, for which both the minimum and maximum punishment is a fine of m100. Having Given one's Allegiance to a Faction that Votes AGAINST a Proposal whose Author is currently one's Twin also constitutes Blood Betrayal. Committing Blood Betrayal multiple times in a given nweek cannot result in more than a single punishment.

The most recent Vote on a proposal by a Registered Voter is called that Registered Voter's Final Vote on that proposal.

#### Tallying the votes

A Proposal's Stamina is equal to the sum of the Vote Power of the Registered Voters whose Final Vote on that Proposal is FOR, plus the sum of the Vote Power of the Registered Voters whose Final Vote on that Proposal is AGAINST, plus the sum of the Vote Power of the Registered Voters whose Final Vote on that Proposal is SHELVE.

A proposal's Strength is equal to the sum of the Vote Power of the Registered Voters whose Final Vote on that proposal is FOR minus the sum of the Vote Power of the Registered Voters whose Final Vote on that proposal is AGAINST or SHELVE.

When Voting or Particular Voting ends, the following events happen, in order:

- Each Open proposal with a Stamina less than or equal to A Quiggle becomes Pending.
- Each Open proposal with positive Strength becomes Won; each Open proposal with negative Strength that would have positive Strength if SHELVE votes were counted as FOR votes is Shelved and becomes Shelved and Pending; and all other proposals become Lost.
- Dependency Culling occurs (see below).
- Conflict Culling occurs (see below).
- Dependency Culling occurs again.
- All Open proposals that are Won Pass, in order by Proposal Number.
- All Shelved proposals become Undecided.
- All Open proposals become Historical

When a proposal Passes, the game is changed according to the instructions in its Body.

Proposals that do not Pass are said to have Failed.

A proposal that is Shelved in two consecutive nweeks is considered both Lost and Failed and shall not appear on a later ballot.

#### Dependency Culling

When Dependency Culling occurs, every Open proposal is processed in ascending order by Proposal Number. When a proposal is processed in this manner, if it Depends on a proposal that is Lost, then it becomes Lost itself; then, if it Depends on a proposal that is Shelved and is not Lost, then it becomes Shelved. This process is repeated as long as there is any Open proposal that Depends on a Lost proposal and is not Lost itself, or Depends on a Shelved proposal and is neither Shelved or Lost.

#### Conflict Culling

When Conflict Culling occurs, every Open proposal is processed in descending order of Strength, and of Proposal Number when Strength is equal. When a proposal is processed in this manner, if it is Won, then every proposal that Conflicts with it becomes Lost.

#### Hurrying Votes

The Particular Voting Period for a given nweek, or just "Particular Voting", is defined as the period of time from the beginning of nday 4 of that nweek until the end of nday 7 of that nweek.

At the beginning of each Particular Voting Period, all Hurried proposals become Open.

When the clock is On, as a Game Action, any Player may, if he obtains a number of supporters that is a Quiggle minus one, Hurry a specific Pending Proposal. When a proposal is Hurried in this manner, if its Status was Pending, its Status becomes Hurried.

### Rule 4E20: Players May Vote

All Players are Registered Voters.

At the beginning of Ballotday, each Player who Gave his Allegiance to a Faction during that nweek has his Vote Power set to 0. All other players have their Vote Power set to 1.

### Rule 4E19: Scoring

Whenever a Proposal becomes Historical,

- Each Player whose Final Vote on the Proposal was not ABSTAIN gains 1 point.
- If the Proposal Passed, its Author gains 1 point for each Player whose Final Vote on the proposal was FOR.
- If the Proposal was ever Won, its Author gains 1 point for each Player whose Final Vote on the proposal was FOR.
- If the Proposal Failed and was never Won, then its Author loses 3 points.

### Rule 4E28: Active Players

The group of players that currently possess the Active property may be called the Active Players.

The group of Players that do not currently possess the Active property may be called "The Horde".

At the beginning of each nweek, the players that voted in the previous nweek gain the "Active" property, the players that failed to vote in the previous nweek lose the "Active" property.

## Justice

### Rule 4E18: Judgment

#### the Oracle

There exists a ministry known as the Ministry of Questions. The Minister of Questions, also known as the Oracle, is responsible for maintaining a Public Display of the current Consultations. There exists an Object called the staff of ZOT. The Oracle holds the staff of ZOT.

#### Consultations

Any External Force may as a Game Action submit a Consultation.

Consultations are Game Documents that contain a Question that is to be Answered. The Question must be posed in such a form as to permit a yes or no reply. Consultations may also contain:

Reasoning, meaning text that clarifies the intent of the Consultation.
the name of a Player that is to be considered as the Unbeliever for that Consultation.
That player submitting the consultation will be known as Supplicant regarding that consultation.

Consultations are given a Consultation Number by the Oracle when assigned to a Priest. For each new Consultation, the Consultation number is usually equal to 1 or, if such Number is already in use, to the greatest existing Consultation Number incremented by one. The Oracle may arbitrarily override the normal assignment of Consultation numbers, and choose a number of his liking for a new Consultation.

A Consultation is in one of the states of Waiting, ZOTTED and Pondered. A Consultation is initially Waiting.

Whenever there exists a Consultation which has no priest assigned, the Oracle is obligated to either assign a priest to that Consultation or ZOT it.

#### ZOTTING

Upon submission of a Consultation the Oracle shall as a Game Action select a Priest for that Consultation. Alternatively the Oracle may wield the staff of ZOT and cause the Consultation to be ZOTTED, if in his insight he considers the contained Question to be malformed, ambiguous, irrelevant or otherwise unworthy. ZOTTED consultations have no further effect.

The Oracle may also ZOT a Waiting Consultation if has not been Answered yet and its assigned Priest requests him to do so. In this case the Oracle is required to grant the request or immediately reassign the Consultation to a new Priest instead.

If a Consultation is ZOTTED by the Oracle before he assigns it to a Priest, the Oracle is not required to record the Consultation in the Public Display.

#### Selecting a Priest

Whenever a Priest is to be selected for a Consultation, the Oracle shall select one between the eligible Players. All Active Players, except the Supplicant, the Unbeliever if the Consultation names one, the Oracle and Players that have already been selected as Priests for that Consultation, are eligible for selection as Priests. If no Player is eligible, the Oracle is automatically selected as Priest.

#### The Answer

The selected Priest shall find inspiration in his knowledge of the Rules and, as a Game Action, Answer his assigned Consultation YES or NO. The Priest may also submit his own Reasoning, explaining how his mystical interpretation of the Rules has guided him in his Answer. If he deems it necessary the Priest may also submit as a game action an Oracularity detailing changes needed to correct the state of the game.

When a Priest submits the answer to a public forum that Consultation becomes Answered. If a Consultation remains Answered for four full Ndays (or Ndelays if the clock is off), it becomes Pondered.

For the purposes of answering Consultations the words "True", "Affirmative" and "Correct" are to be considered synonymous with "Yes", and the words "False", "Negative" and "Incorrect" are to be considered synonymous with "No".

#### Automatic Reassignment

Any Priest which has not answered a consultation he has been assigned to within a Jiffy ceases to be the Priest for that Consultation.

#### Overriding Consultations

When a Priest submits an answer to a consultation, within three ndays (or ndelays if the clock is off) since its submission, any player except the Unbeliever and the Supplicant may, as a Game Action, make a Claim regarding the Answer and the Oracularity (if one exists). Such Claims will ultimately state that the player believes the answer (and Oracularity) to be Consistent or Inconsistent. A Player may not Claim an answer submitted by a Priest who is currently his Twin to be Inconsistent. If a Player submits multiple Claims, only the last one submitted shall be counted.

At the end of the third nday (or ndelay) since the Answer has been submitted the Oracle shall tally any such Claims. If there exist more Claims of Inconsistency than claims of Consistency, the consultation ceases to be Answered and becomes Waiting. The Oracle shall then immediately assign a new Priest to the Consultation. The previous Priest's answer and Oracularity (if any) is discarded.

#### Oracularities

As part of their answer a Priest may submit an Oracularity. An Oracularity is a Game Document which includes a list of changes to the rules and gamestate of B Nomic. By nature, an Oracularity is a transaction and is implied to be enclosed in "BEGIN TRANSACTION" and "END TRANSACTION" clauses.

If the answered question is in relation to an ambiguity in the rules, the Oracularity should address that ambiguity by including changes to the rules in question to clarify.

When a Consultation becomes Pondered, if the answer for that Consultation is the same as the answer originally supplied by its Priest, then any Oracularity submitted with that answer is followed and the gamestate and rule changes it calls for take effect.

### Rule 4E54: Criminal Offenses

The rules may make certain Game Actions or gamestates involving a Player as Crimes by defining them as one of the subcategories of Crimes--Felonies or Misdemeanors.

A Player can be punished for a Criminal Action if he has been found guilty by a Consultation on a Question of his guilt for a particular action.

When an Answer to a Consultation on a Player's guilt becomes Pondered as True, he shall be assigned a Punishment. This punishment must accord with the minimum and maximum sentencing guidelines for the Crime in question. The punishment shall be assigned by the Priest who answered the Question of guilt if his Answer indicated that the Player in question was guilty, or by the Oracle if the Priest's answer indicated that the Player was not guilty and his Answer was subsequently found to be INCONSISTENT. Any Player can, with 4 support, declare a penalty to be UNFAIR and reduce it to the minimum for the crime in question.

The Oracle cannot ZOT a question into his own guilt in a criminal matter.

When not otherwise specified, the minimum punishment for a Misdemeanor shall be a fine of 1m and the maximum a fine of 50m.

When not otherwise specified, the minimum punishment for a Felony shall be a fine of 25m and the maximum a fine of 500m.

### Rule 4E55: Murder

Murder is a Felony that consists of intentionally causing another Player's Hit Points to become nonpositive.

### Rule 4E56: Shall I?

Taking a Game Action which the rules state a Player "shall not" take is a Misdemeanor.

Failing to take, within a reasonable period of time, a Game Action which the rules state a Player "shall" take is a Misdemeanor.

### Rule 4E59: Stop that!

Mildly spamming spoon-business or spoon-discuss is Misdemeanor with a minimum penalty of 5m and a maximum penalty of 20m.

Severely spamming either list is a Felony with a minimum penalty of 30m and a maximum penalty of 100m, plus loss of all points and/or mackerel that would be gained by the perpetrator as a result of passed proposals during that nweek. /* You can make the case to the Priest as to whether what you're doing counts as spamming, and as to how severe it is. */

### Rule 4E60: Contempt of Court

If a player submits 5 Consultations in the same nweek that are all ZOTTED, that player is Held in Contempt of Court.

Being Held in Contempt of Court is a Misdemeanor. The minimum penalty for being Held in Contempt of Court is a fine of 10m. The maximum penalty for being Held in Contempt of Court is a fine of 60m, plus a limit of at most one proposal during the following nweek.

## Stuff that doesn't really fit anywhere else

### Rule 4E41: Ceci n'est pas un titre

There is no Rule 4E41.

### Rule 4E23: Foreign Relations

There exists a ministry known as the Ministry of Foreign Relations. The Minister of Foreign Relations, also known as the Ambassador, is responsible for maintaining a Public Display of the status of B Nomic's relationships with other Nomics and for relaying messages from B Nomic to other Nomics.

Where an external Nomic's rules make it possible for B Nomic to perform some action, the Ambassador may use that Nomic's mechanisms of action to cause B Nomic to perform that action with 2 supporters and without objection, unless the Rules of B Nomic provide for a different threshold of support for a particular action.

### Rule 4E30: Official Quantities

For all game purposes the following phrases are defined to mean the indicated numbers.

- A Few = 4
- A Jiffy = 4 rdays
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
- A Quiggle = Half the number of Active Players
- A Quorum = See Quiggle

### Rule 4E27: Disambiguation

No text in any Rule shall be interpreted as a specific Player's name, unless that rule explicitly states that said text shall be interpreted as a specific Player's name.

### Rule 4E38: Pronouns

All personal pronouns shall be taken to refer to entities of any gender or of no gender regardless of the purported gender of the words used. Language intended to apply only to members of a specific gender must explicitly say that it does so.

### Rule 4E32: Tidiness Lists

If the Rules contain errors of spelling, inconsistent capitalization, or other trivial errors, any Player may as a Game Action and without objection correct these errors by posting a Tidiness List on a public forum.

A Tidiness List is a Game Document that lists spelling errors in the rules, and the proposed corrections. The time limit on objections for tidiness lists is set to five ndays.

/* for practical purposes it is allowed to actually go on and make the changes to the wiki at the same time as posting the Tidiness List, but please mark your changes clearly so that they may be reverted easily */

If the corrections in a Tidiness List take place the Player that submitted the Tidiness List gains one point for every three errors corrected. Tidiness Lists correcting less than three errors give no points.

## Emergencies

### Rule 4E0: In Case of Emergency

For the purposes of this rule, the term "Potential Emergency Participant" (or PEP) shall mean each of the current players of the game as defined by other rules. However, if who the current players are in the game is unclear, uncertain, or ambiguous, or if there are less than four such players, then it shall instead mean who the players were before such uncertainty or drop in player count.

Each PEP has a Mental State, which is exactly one of Calm (default) or Paranoid. Mental States can only change as explicitly described by this rule.

A PEP can set his Mental State by posting a message to a Public Forum (or any forum that was a Public Forum within the past month) stating that he does so, and specifying his new Mental State.

If at least four PEPs are Paranoid, B Nomic becomes in a State Of Emergency. When this occurs, the following Procedure happens:

1. Game time is stopped. Whatever means used in the Game to track time is stopped as of the beginning of the Emergency. Pending events and deadlines relative to Game time, with the exception of those specified in this rule, are postponed until Game time resumes. Pending events and deadlines with absolute dates and times do not occur.

2. The PEP who most recently held the Minister of Ministries becomes the Emergency Coordinator. If this Emergency Coordinator does not exist, or it is unclear which PEP it is, or if he does not possess the Active property, then the PEP that first attempts to organize running this Procedure becomes the Emergency Coordinator.

3. The Emergency Coordinator designates a means for PEPs to communicate as the Emergency Forum and makes a reasonable effort to notify other PEPs about the Forum's existence. The Emergency Forum must be reasonably accessible to all PEPs.

4. The Emergency Coordinator makes a statement to the Emergency Forum that he is initializing the Pause. The Procedure tracks time spent using the Pause. When the Emergency Coordinator initializes the Pause it is zero. Thereafter, until the completion of the Procedure, the Pause is increased by one each day at 00:00:00 UTC. Once per day, the Emergency Coordinator may announce to the Emergency forum their intention to increment the pause. If no PEP voices objection to this action on the Emergency Forum within 24 hours, then the value of the Pause is incremented by one.

5. At any time before the value of the pause is 5, each PEP may submit a Refresh Proposal, aimed at either resuming or ending the Game, and may revise or withdraw his own Refresh Proposal, via the Emergency Forum. A Refresh Proposal consists of a list of changes which may affect any aspect of the Game or the state of the Game, including, but not limited to: rules, scores or other player attributes, the valid list of players, current holders of any Ministries, the legitimacy and/or actuality of any action taken in the context of the Game, etc.

6. When the value of the Pause is 5, the Emergency Coordinator gathers all submitted Refresh Proposals into a first-round Ballot.

7. Each PEP casts a single vote to select one of the Refresh Proposals in the Ballot by announcing his vote via the Emergency Forum.

8. When the value of the Pause is 6, the Emergency Coordinator counts all submitted votes and announces to the Emergency Forum the number of votes received by each Refresh Proposal. If a Refresh Proposal received more than half the votes, it is selected and the Procedure skips to step 15; otherwise the Procedure continues to Step 9.

9. A second-round Ballot is formed of those Refresh Proposals that received at least two votes in the first round. If there are less than two Refresh Proposals that received at least two votes in the first round, then all Refresh Proposals that received one vote are also included in the second-round Ballot. If there are less than two Refresh Proposals that received at least one vote in the first round, then all Refresh Proposals are included in the second-round Ballot.

10. Each PEP casts a single vote to select one of the Refresh Proposals in the Ballot by announcing his vote via the Emergency Forum.

11. When the value of the Pause is 7, the Emergency Coordinator counts all submitted votes and announces to the Emergency Forum the number of votes received by each Refresh Proposal. If a Refresh Proposal received more than half the votes, it is selected and the Procedure skips to step 15; otherwise the Procedure continues to Step 12.

12. An *n*th-round Ballot is formed, where *n* is the number of voting rounds that have previously taken place in the current Emergency plus one. The Ballot includes only the two Refresh Proposals that received the largest number of votes in the previous round. If any Refresh Proposals are tied for the second largest number of votes in the previous round, they are included in the Ballot as well.

13. Each PEP casts a single vote to select one of the Refresh Proposals in the Ballot by announcing his vote via the Emergency Forum.

14. When the value of the Pause is 5 + *n*, the Emergency Coordinator counts all submitted votes and announces to the Emergency Forum the number of votes received by each Refresh Proposal. If a Refresh Proposal received more than half the votes, it is selected and the Procedure skips to step 15; otherwise the Procedure returns to Step 12.

15. All changes listed in the selected Refresh Proposal occur, implemented by the Emergency Coordinator as needed. All PEPs become Calm.

If, at any point during the procedure, there are less than four Paranoid PEPs, the procedure stops and B Nomic stops being in a State of Emergency, and normal Game time resumes.

At the beginning of Mulberry, nday 3, any PEPs who are Paranoid become Calm if, and only if, the value of the Threat Flag is Pink Ponies.

