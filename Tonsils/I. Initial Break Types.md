This is a non-comprehensive list of sets of requirements for breaking.

For purposes of this list, the "kitchen" is the area between the head string; the "semi-circle" is the semi-circle or D on a snooker table; and the "island" is the area contained by lines drawn across the first and second diamonds from the head end of the table and the first and third diamonds across the narrow direction.

1. "8-ball express" style

Based on the rules for the 8-ball express league:
* The cue ball is placed anywhere in the kitchen
* The cue ball must hit an object ball before hitting a cushion
* The cue ball must hit the head object ball (or simultaneously hit the head and second object ball, if the rack includes more than 9 balls)
* Four object balls must be driven to the rail *or* a ball must be pocketed
* (optional) In accordance with 8-ball express rules, the break shot must be hit as hard as possible while maintaining control. This is subjective and therefore hard to enforce.
* If the break is not legal, the balls are reracked and the same player tries again


2. "Straight Pool" style

Usually reserved for games in which every shot, even the break, has to be called, but also applicable for games in which a defensive approach is desired:
* The cue ball is placed anywhere in the kitchen
* The cue ball must hit an object ball before hitting a cushion
* Either a ball must be pocketed in a designated pocket, or the cue ball and at least two additional balls must be driven to a rail
* If the game is a point-accumulating game, fouling on the initial break is a two-point penalty, AND the next player has the choice of accepting the table in position or re-racking and requiring the offending player to try again.

3. "Snooker" style

* The cue ball is placed anywhere in the semi-circle
* TODO: Verify whether the cue ball may strike a cushion first on the break-off shot in snooker

4. "Snook" style

* The cue ball is placed anywhere in the island
* TODO: Verify whether the cue ball may strike a cushion first on the break-off shot in snooker, and whether we want to change this for Snook

5. Parameterized: N[+|*]-drive [or pot], [in]direct, [on waived], [M from head], [uncalled], from [anywhere|kitchen|island|semicircle|...]

* The cue ball is placed anywhere in the area described by the "from" clause. When calling more esoteric games, the player selecting the game may elect to use unconventional restrictions, even going as far as putting the cue ball down and saying "right here," but of course there is always the possibility of the other players all agreeing to forfeit in order to avoid the silliness (or the breaking player simply electing to pass on the break).
* At least N balls must be driven to a cushion or a valid ball must be potted.
** For N+, the cue ball must also be driven to a cushion after contact with the rack.
** For N*, the cue ball is not required to hit a cushion after contact with the rack, but it counts toward the number of balls that must be driven to cushion if it does.
* Inclusion of "or pot" means that the break is valid if a ball is pocketed without fouling, no matter how many balls reach cushions.
* "Direct" means the cue ball must strike an object ball before striking a cushion. "Indirect" means the cue ball must strike a cushion before striking an object ball. Specifying neither means either is allowed.
* "On waived" means that at most times in the game to be played, there is a restriction on what balls may be contacted first, but on the break that requirement is waived. For example, if the calling player wished to allow a 9-ball break with the 1 in an unusual position in the rack or without requiring the head ball to be struck first.
* "M from head" means that the cue ball's first contact must be within M balls of the head of the rack (with 0 meaning the head ball must be struck). Making this a fraction (generally a .5) means that the Mth and M-1th balls may be struck simultaneously.
* "Uncalled," in a game where all shots are required to be called, means the break is excluded from this requirement. For example, if the calling player wanted to play a game similar to 14.1 Continuous but with a hard break, and therefore to allow the breaker to continue if anything were potted on the break. "Called" may be specified if desired, but it is implied if the game is normally known to require calling all shots or if the game is specified as "all called shots."

So, for example, in Parameterized notation, the first four break styles listed are, respectively:

8-ball Express Style (8-ball): 4-drive or pot, direct, .5 from head, uncalled, from kitchen.
8-ball Express Style (9-ball): 4-drive or pot, direct, 0 from head, uncalled, from kitchen.
Straight Pool style: 2+-drive or pot, direct, called, from kitchen.
Snooker style: From semi-circle.
Snook style: From island. (Note: We have been playing this more or less as if Snook had a semi-circle, but given the other adaptations used in the game, the island seems more apporpriate.)
