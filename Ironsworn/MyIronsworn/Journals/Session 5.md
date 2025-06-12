I must prepare to leave south, in search of [[Ikram]], the fletcher, who lives in [[Deepwater]].

```leaflet
id: myironlands
image: [[Ironlands-Map.png]]
bounds: [[0,0], [1784, 1341]]
height: 250px
lat: 816
long: 808
minZoom: -1
maxZoom: 1.5
defaultZoom: 0
zoomDelta: 0.5
scale: 1.12
unit: km
```

I set out towards the south. I know that I must go around the great mountain ridge to the east. There is a valley in the south that will allow me to cross the mountains and reach the great Deep Valley where my destination lies.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=6 adds=0 stat=2 vs1=2 vs2=3
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" status="added"
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" rank="formidable" steps=1
}

```
I make good progress. The wind is behind my back and I feel good about this. I find a nice glade at sunset that will be perfect to rest. I wonder what this Ikram will be able to teach me, and what kind of person he is. I look for a suitable place to make camp tonight.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=5 adds=0 stat=4 vs1=3 vs2=10
}
```
I am able to relax that night, and plan for the journey ahead. I decide to test some of Nissa's teachings regarding scouting and hunting with Vasor. I whisper an order to him, and hoist him up. Then start walking. I observe if he is going to follow my directions.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=5 vs2=8
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" rank="troublesome" steps=1
}

```
Vasor is doing great. He scouts the area from the skies and signals there is no danger or small game to hunt. I whisle and he returns to my arms. Time to continue my journey.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=1 vs2=3
}
oracle-group name="Action and Theme Oracles: New Action and Theme Oracles" {
    oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Distract" roll=92
    oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Opportunity" roll=43
}

```
Is my milestone a settlement? No.
I encounter a caravan of merchants that has been waylaid by a group of bandits. "Hail traveler, we've been raided by a bunch of ruffians. We were on our way to Summerland with some provisions for winter and now we have little left to take there". Summerland is my home settlement, those are my people. They will need these supplies for the winter that is to come. I swear an iron vow to find and retrieve the goods.
```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" status="added"
```
Were there more than 4 bandits? 
"They disappeared into the woods to the southeast" one of the men says. Do some of them follow me to aid me in this search? Yes, two of them join me. Two sisters, Nadira and Mila who both have sharp axes and some experience in the woods follow me to the southeast.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=3 vs2=9
}
```
I find the bandit's tracks going into the woods. I show these to [[Nadira and Mila]]. We decide to go forward quietly and watch our flanks and rear with great care.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=6 adds=0 stat=2 vs1=7 vs2=2
}
```
We find their camp as the night falls and the moon rises on the east. 
Are all four of them there? Yes.
We prepare to make an ambush. I will go to a vantage point and ready my arrows, and Nadira and Mila will sneak up to their tents and catch them if they try to run.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=2 adds=0 stat=1 vs1=7 vs2=7
}
```
I step on a dry branch, making a sound. We are spotted! No time to set up the ambush.
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=3 adds=0 stat=1 vs1=10 vs2=3
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" rank="dangerous" steps=1
}

```
I loudly sing my keen as i pull the string of my bow.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1
    roll "Heart" action=5 adds=1 stat=2 vs1=9 vs2=7
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=4 vs2=1
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" status="added"
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" rank="dangerous" steps=2
}

```
I hit one of them in the leg.
Do they have ranged weapons? Yes.
I whistle to Vasor to help distract their archer.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "vasor"
    roll "Edge" action=3 adds=1 stat=3 vs1=5 vs2=5
}
```
Vasor swoops in and scratches the archer in the face, throwing him completely off-guard. This is my chance to strike!
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Edge" action=5 adds=1 stat=3 vs1=9 vs2=6
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" rank="dangerous" steps=1
}

```
 I hit the archer, but he drives Vasor away and is ready to exchange arrows with me.
 

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=2 vs2=9
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" rank="dangerous" steps=1
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=3 adds=0 stat=3 vs1=7 vs2=8
}

```
We are both hit. Nadira and Mila are engaged in combat with two other bandits. I summon Vasor again to help.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "vasor"
    roll "Edge" action=2 adds=1 stat=3 vs1=8 vs2=7
}
move "[Companion Endure Harm](datasworn:move:classic\/suffer\/companion_endure_harm)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=5 vs2=9
}

```
They see Vasor coming and hit him, injuring the poor bird. I must retaliate now!
```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=8 vs2=7
    progress from=32 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" rank="dangerous" steps=1
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" score=10 vs1=3 vs2=8
    progress from=8 name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" rank="dangerous" steps=1
}

```
I kill the archer with a well placed arrow. 
Are [[Nadira and Mila]] ok? Yes. They killed two other bandits.

Did the fourth bandit escape with some supplies? Yes!

I tell Nadira and Mila to secure the area, and take these supplies back to the caravan. I will go track down the final one.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=6 vs2=5
}
```
I find his trail, I'm not too far behind! He runs down a brook and crosses to the other side. I will attempt to line up a shot.
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=1 adds=0 stat=1 vs1=8 vs2=7
}
```
Are there more bandits lying in wait? No.
The bandit disappears into the woods on the other side. I might lose him. I climb down the brook and race up the other bank.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=10 vs2=1
}
```
When I get up, an arrow hits me in the shoulder. He is firing at me!
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=7 vs2=10
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" rank="dangerous" steps=1
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" status="added"
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=4 vs2=2
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" rank="troublesome" steps=2
}

```
I hit him back with a well placed arrow in between the trees. I ready another one to finish him off!
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=2 vs2=7
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" rank="troublesome" steps=1
}

```
He is deeply wounded. Does he surrender?  No.
```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=5 vs2=1
    burn from=6 to=2
    progress from=36 name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" rank="troublesome" steps=1
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" score=10 vs1=4 vs2=7
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Bandits.md|Bandits]]" status="removed"
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Bandit.md|Bandit]]" status="removed"
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" rank="dangerous" steps=1
}
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" score=8 vs1=7 vs2=8
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Find and retrieve the stolen goods.md|Find and retrieve the stolen goods]]" status="removed"
}

```

After a couple more arrows he is dead. I move closer and I see that the bandit turned out to be someone I knew from Summersong. It seems that there is some doubt and conflict within the people of that village. Why would they be stealing from their own?
I return the stolen goods to the caravan. And wish them a safer voyage up the northern road.
```iron-vault-mechanics
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=10 vs2=8
}
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=4 vs2=7
}

```
```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=8 vs2=10
}
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Iron" action=1 adds=0 stat=1 vs1=10 vs2=1
}

```
I shake hands with Nadira and Mila "you are a brave warrior" they say "but we mistrust the people of your village. Who steals from their own?". "I don't blame you, this was very unfortunate indeed" I reply.
I heal my own wounds, but I fail to aid Vasor's. When I ask the caravan if anyone has any knowledge to aid me, they do not answer.
 
I spend the night under a willow tree, thinking about what happened. I feel like something must be done to renew the morale at Summersong when I return there. The next day I look for suitable wood to fletch some more arrows.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "fletch"
    roll "Edge" action=5 adds=1 stat=3 vs1=3 vs2=2
    progress from=20 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" rank="dangerous" steps=1
}

```
My craft improves with each day. I am pleased with these fresh arrows. I will resume my journey now.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=6 vs2=10
}
```
Vasor is yelping in pain. The poor thing needs something to help him. I will look for medicinal herbs in the woods.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=10 vs2=3
}
```
I find some that may be of use. I bring him to a small creek and clean his wound again. I attempt another treatment with some of the herbs I crushed.
```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=7 vs2=8
}
```
Nothing seems to help him. I will not ask him to aid me again until he is fully healed. I will look for some firewood and possibly food for tonight.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=9 vs2=1
}
```
It takes me a long time, but I am able to find some nice firewood. I set up camp.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=3 adds=0 stat=5 vs1=2 vs2=7
}
```
The next day I notice Vasor is willing to fly again. He seems much better. That makes me feel relieved. I will see if he is willing to help me survey the area for any danger. I whisper a command in his ear and let him soar.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=7 vs2=5
}
```
But he quickly returns and is not willing to fly again. I must be patient and give him more time. I hunt for some small game.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=7 vs2=10
}
```
I twist my ankle when crossing a brook. This was unfortunate. Maybe it is a sign that I should just press on with my journey.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=9 vs2=2
    progress from=8 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" rank="dangerous" steps=1
}

```
I am only half way there. The land is flat and mostly grassy around here. I see a herd of mammoths migrating south. I admire the giant creatures. They seem to live a good life. I press on.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=8 vs2=2
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" rank="dangerous" steps=1
}

```

I cross the first arm of the mountain range. I get to a lake with muddy waters and old trees. This is a good spot to stop for the day. But first, I need some more supplies. Time to ask Vasor for help again.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=6 adds=0 stat=2 vs1=6 vs2=4
    progress from=36 name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" rank="troublesome" steps=1
}
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" score=10 vs1=1 vs2=7
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" status="removed"
}

```
Vasor finds a hare, I move in that direction, but before I can even see it Vasor swoops down and grabs two of them at once! What are the chances? It seems that his training is complete. I am so proud. I will give him the best part of the meat to enjoy as a prize.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=2 adds=0 stat=4 vs1=5 vs2=2
}
```
I have a great meal and wake up early the next day. Vasor is eager to go as well, he seems to be in a great mood. I whisper the command, and he guides me on my way.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1 "camp"
    add 1 "vasor"
    roll "Wits" action=3 adds=2 stat=2 vs1=1 vs2=2
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" rank="dangerous" steps=1
}

```

Next: [[Session 6]]














