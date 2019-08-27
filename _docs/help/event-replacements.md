---
title: Event Replacements
permalink: /docs/event-replacements/
redirect_from: /docs/index.html
---

All events in IdleLands have a few base "replacements" that personalize events. They are:

| replacement | replaced with |
| ----------- | ------------- |
| %player     | the event initiaiors name |
| %pet        | the event initiators pet name |
| %guild      | the event initiators guild name |
| %guildMember| a random member from the event initators guild |
| %hisher     | "his", "her" or "their" |
| %hishers    | "his", "hers", or "theirs" |
| %himher     | "him", "her", or "their" |
| %she/%heshe | "he", "she", or "they" |
| %Hisher     | "His", "Her" or "Their" |
| %Hishers    | "His", "Hers", or "Theirs" |
| %Himher     | "Him", "Her", or "Their" |
| %She/%Heshe | "He", "She", or "They" |

Some events also offer their own replacements, they are:

* BlessItem, ForsakeItem, FindItem, Enchant, Merchant, Switcheroo - %item - the new item name
* BlessGold, BlessGoldParty ForsakeGold - %gold - the total gold modifier
* BlessXP, BlessXPParty, ForsakeXP - %xp - the total xp modifier
* Merchant - %shopCost - the cost of the item in the shop
* Party - %partyName - the name of the new party
* Party - %partyMembers - the string of all the other members in the party
* Switcheroo - %stat - the stat being switcheroo'd

TODO: write about $dict$, $chance$ and the other "dig in" replacements.
