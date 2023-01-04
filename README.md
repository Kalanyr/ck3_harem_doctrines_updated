# Harem Doctrines For CK3 / Crusader Kings III version 1.7.*+ aka khd aka ck3_harem_doctrines_updated
This mod updates <a href="https://steamcommunity.com/workshop/filedetails/?id=2221765598" target="_blank">**Harem Doctrines**</a> to work with 1.7.*+

It allows you to select Doctrines allowing more Spouses / Concubines than vanilla, and introduces a Managed Harem doctrine that allows for both secondary spouses and concubines. 

It's a code rewrite that incorpates fixes for the various problems with the old mod (eg being unable to Offer Concubines, and opinion penalties that don't make sense, it also reinstates some opinion penalties that couldn't otherwise be reached) and attempts to treat the ideas a *little* more seriously (the doctrine descriptions could use some work on this front, as they are pretty much copies)

It also reconciles the conflicts in the base game between Cultural Traditions and Doctrines a little better. 

It does this by introducing additional paremeters to doctrines / cultures allows_concubinage and allows_polygamy. As such it is not compatible with anything that adds marriage doctrines  or that change/add to the marriage type Cultural Traditions (Monogamy / Concubines / Polygamy) without considering these parameters. 

And a pair of triggers accepts_polygamy and acepts_concubinage , which checks if the current character belongs to either a faith or culture with a doctrine / tradition that has the appropriate parameter. 

A Managed Harem tradition has also been added for symmetry (I have left the cultural traditions at the minimum size for all of these, as it gets too cumbersone otherwise,  it might make sense to use the maximum instead)

The Head of Faith event that strips Cultural Traditions that disagree with the Faith has been updated to account for the new Traditions / Doctrines.   As have the Hold Court triggers for testing if polygamy / concubinage are accepted.  This makes this mod incompatible with mods that change
-\events\activities\hold_court_activity\hold_court_events_general.txt
or
- \events\culture_events\culture_tradition_events.txt

This mod uses the relationship tabs code from <a href="https://steamcommunity.com/workshop/filedetails/?id=2222540784" target="_blank">**Better Character UI**</a> in order to display an arbitrary amount of both Secondary Spouses and Concubines. While I recommend using Better Character UI (which should be loaded after this mod), I elected to include that code here for the sake of making this mod standalone. (If the maintainer has an issue with this, I'll remove their code and write my own version)

A fix from <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=2345748273" target="_blank">**AI takes lover as concubine**</a> was incorporated and expanded: 
-The AI will take a lover as a concubine if it's not a crime to do so, unless the lover is unwilling (does not accept concubinage or it would be a crime  for them to be in the revealed relationship) unless they are also rivals).  
- The AI will also take a concubine for the specific purpose of having children, if they are getting older and don't have an heir or  another way to have an heir even if they otherwise would not. 

- Anyone who wishes to is free to reuse my code to handle mixed spouses/concubines or having multiple doctrines / traditions that allow for different numbers of spouses /concubines.

Acknowledgements: 
- Russian Translation by <a href="https://steamcommunity.com/id/yola_jess">**YoBa**</a>


Uploads for Steam Workshop can be found at:
https://steamcommunity.com/sharedfiles/filedetails/?id=2873545950

Uploads for Paradox Plaza can be found at:
https://mods.paradoxplaza.com/mods/51143/Any
