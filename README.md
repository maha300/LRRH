# Little Red Riding Hood
 - [Original Story](https://americanliterature.com/childrens-stories/little-red-riding-hood)

Plot - 

  *[Opening dialogue cutscene]* The first scene begins with Red's mother telling her that she needs to take Gma her meds and a dinner because she's ill. She says to go straight there and never stray from the path, so she may get there before nightfall. Red tries to reason with her mother that it may be too dangerous for her to go alone. Mom dismisses Red's concerns and tells her to just listen and go. [Red is given a basket containing the key items] *[This opens the inventory feature, which will appear at the top of the screen]* Red has a thought bubble that implies that this is typical of her mother. [Player gains control of Red] Red may speak to the villagers, but their interactions will be limited to greetings and a scripted baker interaction, where Red will receive a baked good. *[ensures death ending happens first and shows that villagers are interactable]* 
  
  She leaves through the gates of the village and goes into the forest. The forest area is mostly one long horizontal wooded path, with occasional trails (seen only when it's still light out) that may hold something interesting. When the player tries to go off the path in the first run, Red will put up a thought bubble that will reiterate Mom's advice. *[create sense of curiosity but ensure death scenario and keep focus to main task]* Eventually, Red runs into the wolf who smelled the food she was carrying. She is prompted by the wolf to give him one of her food items [*either packed dinner or baked good will work]*, which he eats and he goes away. *[shows what can attract him, way to avoid him if approached, and possible scheme possibility to poison wolf]* Along the rest of the way through the woods, there may be visual signs that the wolf is following Red.
  
  Red arrives at Gma's, where she's alive and reading in her home. Red goes up to Gma to talk to her and tells her that she traveled all on her own to deliver what she needs. Gma tells Red that she's a very brave, smart child and is excited to spend the night with her. *[make Gma into maternal figure and build player bond with her to make her death meaningful]* Gma says they should eat the food Red brought and play games. Gma sends Red on a quick fetch quest to grab something outside within the fenced area around the home. **[possibly a food item from a garden or flowers bc ones on table or dead]** Red goes around the house to grab the item, when she hears some kind of crash/thud. When she gets back to the front door, she has a thought bubble wondering if the sound was something entering the house beause she left the door open. *[introduce door shutting idea and outcome]* She enters the house, but Gma is no longer there, but her bedroom door is now ajar. 
  
  *[Death ending cutscene]* When Red enters the bedroom, the classic Wolf-Gma disguise plays out. The wolf has on Gma's cardigan with a bonnet and is sat in her bed to try to look inconspicuous. Red comments of "Gma's" ears, eyes, hands, and teeth. As the wolf says "better to eat you with," Red has caught on to the Wolf and begs to know what he did to her Gma. The wolf sneers and pounces on Red to eat her, revealing blood from also eating Gma. *[mature rating fepending on how graphic]*

  The game goes to black, with text bubbles calling out Red's name. *[New game begins]* The game restarts at the end of Red's introduction conversation with Mom, with Mom asking "are you listening to me?" New converstaion plays out where Red urges her mother that it isn't safe to go on her own. Mom is, again, dismissive and closes the door on Red, reminding her of her advice, which has now been proven unhelpful. Red, with a new mission, continues onward.
  

Village - 

  Interactions
  - The Baker : Knocking on her door will prompt a dialogue screen, where you can chat with her about your journey and she will offer some baked goods to take along with you on the long walk. You can accept or decline. **[possibly different baked options for different schemes?]**
      - needed : baker character sprite (1 or 2 for speaking), dialogue with choice variables, baked goods sprite(s), bakery background maybe, bakery building art
  - The Woodsman : He will be standing outside on his home with his axe leaned up next to him. Talking to him will prompt dialogue screen where you will tell him about about your mission and ask him for advice(first run) or for help via escort or borrowing his axe yourself **[one unlocked after ending with the other?]**. He is blunt and not charitable, so will need to be convinced to help. To get him to come with you, he requires you to pay him one silver coin, which can be obtained by selling scavenged items to the Herbalist.
      - needed : woodsman character sprite (walking and dialogue), axe sprite, code to make woodsman follow red, variable for if he's willing to help,
  - Axe : The Woodsman's trusty tool that he treasures dearly, but is willing to part with for a fee. If Red has the axe, she is able to threaten the wolf with the axe by swinging it at him. Red, who's inexperiences and too young to wield the axe properly, will miss the wolf and cut herself. The wolf will tell Red that she's an amusing girl and will leave her for now. The drawn blood, however, will allow the wolf to follow Red's scent to Gma's.
      - needed : axe sprite, wolf attraction variable +
  - The Herbalist : The town doctor that deals with herbs. Knocking on his door will prompt dialogue screen outside of his shop, where he kindly says he is busy and asks if there's something you need. If you ask him for a silver coin, he tells you he will buy mushrooms and poison berries that can be found in the forest. You may request poison from him, which will require some of Gma's medicine and poison item.
      - needed : 
  - Lantern - Sat outside of Red's home. Without the lantern, Red can babrely see in the forest and can't go off of the trail even after the first run. Using the lantern will allow the player to explore other parts of the forest even when it turns to night. The light will, however, attract the wolf to follow.
      - needed : lantern sprite, light effect, wolf attraction variable +
        

Forest
 - Mushrooms - Can be found in bunches in some of the dark parts of the forest. They are a mild poison that can be combined with the prepared meal for a scheme. The can be sold to the Herbalist in a fetch quest from silver. If eaten, you'll obtain a poison death ending soon after.
      - needed : mushroom sprite, consumption/death variable, spawn randomization?
 - Berries - Can be collected from bushes throughout the forest map. There are four different colors that spawn (red, orange, blue, and purple), with orange being poionous. You are able to consume all types, but only find out which is poison by asking the herbalist or by eating them. They can be added to baked goods for a scheme.
      - needed : berry bush sprite, berry sprite, color randomization
- Trail one :

- Trail two : In the later half of the forest map, an opening in the bushes trails off of the main path. This can be used as an alternate path to Gma's house to avoid the wolf?


Grandma's House

Grandma's Room

Constant Variables - 
- inventory :
- time :
- hunger? : could be poinsoned if you dont know about the berries

Endings :
- Poison ending : 

Assets :
