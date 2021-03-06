# Thanks for taking a look!

## 1. Football pool - 
I run a small office-style football pool with a few dozen friends and family members. Everyone pays into the pot at the beginning of the season, and whoever picks the most games correctly each week wins that weeks pot. Everyone trusts me to collect everyone’s picks each week on a google form, not make alterations, and not share them with anyone else until Sunday. They also trust me to correctly allocate wins and losses, then pay whoever has the most correct games at the end of the week. It all works well since I am a fair and just ruler, but in the name of transparency, I could probably put everyone’s picks on a blockchain so that everyone can tell who has submitted their picks for the week without anyone (including me) knowing who has picked whom until everything locks on game day. I could then hook the picks up to some sort of oracle (more likely a sports scores API), and have smart contracts pay out the winners.

*Pros*- seems straight-forward enough and a good use case for blockchain technology

*Cons*- sorta small potatoes and for a very narrow use case. Also, I’m positive no one would have the understanding, patience, or interest to audit the blockchain (they like to just blindly trust me anyway), so in reality, theres’ very little real-world value-added by the project and if anything, it may make the whole process more opaque than the Google Form -> Google Sheet system I have set up currently.


## 2. Valet and Coat check - 
A friend works as a valet at a high end restaurant and told me about a recent spate of carjackings (none at his restaurant of course) where car thieves have been pretending to have “lost” their valet ticket and then convincing the valet to grab them “their Mercedes” so they can then drive off with it. If you could prove ownership of the car to the valet through your private key, the valet process could be more secure.

*Pros*- again, seems like a fairly straightforward implementation, but this time with a bit more real-world relevance

*Cons*- I’m not sure a blockchain is needed for this. QR codes issued to your phone from the valet and stored in your phone’s wallet (https://developer.apple.com/wallet/) would probably be just as secure a system and likely more convenient, and the end user wouldn’t even need to install a new app on their phone


## 3. Fishing tournament
A lot of fishing tournaments (some with pretty big calcuttas on the line) run mostly on some sort of honor system. They’re all judged differently (some quantity of fish caught, some by total weight, and others are points/species-based), but regardless of which type of tournament it is, at the end of the day, you are usually expected to document each fish caught (sometimes with just a pen and paper, sometimes with a timestamped photo) and report the fish landed to the committee boat over the radio either immediately or once you’re back at the dock (tournaments vary). No matter what, there’s a whole lot of trust involved, and I’d imagine blockchain could eliminate the need for some trust in the system.

*Pros*-I f^#&ing love fishing. In fact that’s why I’m getting such a late jump on this course—because commercial season and tournaments are just wrapping up.

*Cons*- Oftentimes you’re out of cell range, so publishing landings to a publicly visible blockchain might not be feasible at all times. Still, you could store the data securely and immutably on your phone and push it to the rest of the competitors when you have a signal. You’re generally in radio contact with at least one or two other boats though, so I feel like these tournaments already lend themselves to the need for a sort of decentralized system without needing a single central authority “committee boat” anyway. Another con, is you’re still mostly relying on an honor system even with a blockchain; for example, you’re still trusting everyone not to lie about catching and releasing two fish when really they just took a photo of the same one twice.
… A blockchain for something like golf tournaments could probably be more easily implemented, but I’m kinda lukewarm toward golf and don’t have as much experience with how those sorts of tournaments are run.


## 4. Seafood supply chain
The fishing industry has some pretty huge problems, not the least of which is deliberate mislabeling of species: E.g. the non-profit Oceana claims that one in 3 seafood samples worldwide is mislabeled, and that number is still worse in my local grocery stores. Another word for mislabelled seafood is “fraud.” Seafood can be mislabelled for many reasons: by mistake (unlikely but I’m sure it happens), to get a higher price from a consumer, to skirt regulations and limits, etc. By entering seafood on a blockchain when it is caught and tracking it through the supply chain, you can’t eliminate bad actors mislabelling, but you’d at least have the ability to follow the ledger all the way back to find who initially mislabeled the product and hopefully hold them accountable. 

*Pros*- again, I love fishing and personally care about this cause

*Cons*- this seems like it could be a massive project that needs more resources than I have, also others seem to be doing work in this space already (https://www.ledgerinsights.com/knowseafood-consumer-seafood-marketplace-blockchain/) that said, I’d love to join one of these sorts of projects when I’m through with this course
