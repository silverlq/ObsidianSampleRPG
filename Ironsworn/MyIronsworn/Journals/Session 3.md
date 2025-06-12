I feel well rested after a week sojourning in [[Fool's Fall]],  and I ask [[Torrens]] to help me explore the northern mountains, and try and find a vantage point to the Wyvern's nest.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1 "Bond"
    roll "Wits" action=6 adds=1 stat=2 vs1=10 vs2=5
}
```
We find the way up the mountain, and climb up on top of the mountain ridge. We can see more or less where the Wyvern's nest should be l located, but there is a big cleft in the way, and no easy way to reach the other side. It would be a somewhat dangerous climb to attempt to cross.
"Maybe we don't need to reach the nest on foot. Maybe we can lure the beast, or hit it from the ground with a well placed arrow" I wondered.
"I've heard that wyvern scales are as hard as iron, what kind of arrow could pierce through that?" Torrens warned.
That gave me an idea, I swore an Iron vow to refine my arrow craft, and produce a projectile that would be deadly even to a creature such as this one.
```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=6 vs2=10
    burn from=8 to=2
}
```
Does Makah know how to aid me in this vow? Yes.

I must journey back to [[Summersong]] and ask Makah for help.

```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern.md|Learn to craft arrows deadly for a wyvern]]" status="added"
track name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" status="removed"
track name="[[Ironsworn\/MyIronsworn\/Progress\/Clear Gawnir's name.md|Clear Gawnir's name]]" status="removed"
track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" status="removed"

```

Before I go, I will investigate the proximity of the nest, under the rock wall and near the bone remains - looking for clues on how to pierce the monster's hide.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=7 vs2=8
}
```
I am spotted by the creature as I get too close to the nest! It dives in to swoop at me! I must dodge out of the way now!

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=4 vs2=8
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=4 adds=0 stat=1 vs1=4 vs2=5
}

```

It is too fast for me to dodge. It hits me with its sharp jaws, cutting into my body, and throwing me many meters away bleeding. I catch my breath and the adrenaline kicks in. I must be fast beyond anything that I've done before.
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=5 vs2=5
}
```
The Wyvern roars loud at me, making the ground beneath my feet tremble. It is a horrifying sight.
```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=10 vs2=6
}
```
My legs are frozen, but I must overcome this fear and move now!!!
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=2 vs2=10
}
```
I flee, running as fast as I can, without looking back. My pack gets caught in a branch and rips open. Some of my supplies are lost, and I have no time to worry about such things. I make my way to a shelter.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=3 vs2=2
}
```
I find a suitable dry and quiet shelter under the roots of a large tree by a little brook. There are some herbs nearby that might help soothe my pain and prevent an infection.
```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    add 1 "herbs"
    roll "Iron" action=2 adds=1 stat=1 vs1=8 vs2=1
}
```
I am able to treat my wounds reasonably well. I have time to breathe now. But I am still shaken by that encounter. I thought I was going to die. As I close my eyes I can still visualize the dreadful creature in front of me. But at least I got to see it up close.
Were it's scales made of iron? No. They were a thick green color. They were about an inch wide each. I think this information might be helpful later.
```iron-vault-mechanics
progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern.md|Learn to craft arrows deadly for a wyvern]]" rank="troublesome" steps=1
```
I am eager to journey to [[Summersong]] but I was just attacked by the Wyvern. I must report to [[Eleri]] and sojourn here for a while in [[Fool's Fall]].
```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "bond"
    roll "Heart" action=4 adds=1 stat=2 vs1=9 vs2=6
}
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "bond"
    roll "Heart" action=1 adds=1 stat=2 vs1=4 vs2=3
}

```
I spend another week to recuperate. And I share what happened with the locals. Some of them think that I am a mad man who seeks death. Others admire my courage. I am able to restock my supplies for my journey south. I set off the next day.
```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" status="added"
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=2 vs2=4
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" rank="troublesome" steps=1
}

```
I make my way back to the great hollow tree. Last time I had a great time camping here. I look forward to do so again.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=3 adds=0 stat=4 vs1=4 vs2=5
}
```
This spot did not let me down. I saw a meteor shower this time as I stared into the heavens while I lied in the grass. The next day I wake up feeling refreshed. I decide to fletch some fine quality arrows and practice my skill.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "fletcher"
    roll "Edge" action=3 adds=1 stat=3 vs1=3 vs2=8
}
```
I am pleased with the results, but I know that I need a mentor to further develop my skills. I press on southwards.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=10 vs2=8
}
```
A few days later it starts to pour rain and the wind is really strong. It seems to be pushing me away from my destination. I decide to stop and wait it out. I use my hook and line to try and catch some fish in the meantime.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=8 vs2=3
}
```
The waters are agitated with the rain. I don't think I will catch anything until.. Something bites! But it is too strong, it breaks my line. I've lost my fishing hook. After a day the weather clears and I continue south.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=3 vs2=10
    progress from=12 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" rank="troublesome" steps=1
}

```
I am out of the hills and back into the havens. I decide to hunt for some food. First, I send Vasor up to see if he spots any prey.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=4 vs2=9
}
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=10 vs2=7
}

```
Vasor spots something but does not come back. I follow it.
What did Vasor see? Refuse Ability
I walk into some woods where he flew to and see if I find him
```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=8 vs2=5
}
```
Vasor is landed on the carcass of a dead elk. But the meat is long gone, dry and rotten. I call him but he does not answer. "What is wrong my friend?" I ask. "Don't worry, we will soon be back in Summersong and mother will spoil you with treats."
```iron-vault-mechanics
move "[Test Your Bond](datasworn:move:classic\/relationship\/test_your_bond)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=9 vs2=1
}
```
Vasor is hesitant, but it comes back to my hand when I reach for him. "I must train you better. You have been loyal and strong, but you deserve better training", I swear to you on iron, that I will train to you to be the smartest hawk of the Havens.
```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    add 1 "Vasor"
    roll "Heart" action=3 adds=1 stat=2 vs1=6 vs2=2
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" status="added"
}

```
I press on southwards.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=7 vs2=9
}
```
The rain comes back, and it is even stronger than before. My gear is soaked, it is hard to make a fire, and I begin to get frustrated. I must try and ressuply now. I look for roots and small animals to eat.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=9 vs2=10
}
```
The rain turns into a thunderstorm. I must find shelter for it now.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=1 vs2=5
}
```
I find a small crack in a large rock outcrop where I can be sheltered from the rain and the wind. I somehow even manage to start a little bonfire to keep me warm. The next morning I press on.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=7 vs2=5
    burn from=10 to=2
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" rank="troublesome" steps=1
}
move "[Reach Your Destination](datasworn:move:classic\/adventure\/reach_your_destination)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" score=9 vs1=4 vs2=10
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Summersong.md|Journey back to Summersong]]" status="removed"
}

```
I arrive at Summersong, but something is wrong. Most of the wardens are out on a mission. 
What is the nature of this trouble?
```iron-vault-mechanics
oracle name="[Settlement Oracles \/ Settlement Trouble](datasworn:oracle_rollable:classic\/settlement\/trouble)" result="Conflict with firstborn" roll=79
```
Varou have been spotted near our village. It is said that some of our cattle went missing. I must speak to Nissa about this.
She tells me that the Varou used to be shy around ironlanders, but are getting too comfortable now, and we must send them a message that we are not going to stand for this abuse.
I ask her about how to better train Vasor. Can she help? Yes. She actually knows much about such birds, she used to hunt with vasor's parent before she got paralyzed. She teaches me many useful lessons.
```iron-vault-mechanics
progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" rank="troublesome" steps=1
```

When Makah returns from his scouting mission we speak. He is happy to see me well and strong. He laughs at my stories when I tell him what happened north. "Only you could accomplish such crazy things! And it sounds like you traded that woodman's life for your own! How do you plan to face a Wyvern anyways?". I tell him about my plan, and ask for advice.
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1 "bond"
    roll "Heart" action=1 adds=1 stat=2 vs1=3 vs2=9
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1
    roll "Wits" action=3 adds=1 stat=2 vs1=3 vs2=4
}

```
Makah is very interested when I describe the Wyvern's scales. "Yes, you know what, you are not going to believe this, but I do know a twisted tip design for an arrow head that might just do the trick. I will teach you, but you must help me with these Varou first". I accept the offer.
```iron-vault-mechanics
progress from=12 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern.md|Learn to craft arrows deadly for a wyvern]]" rank="troublesome" steps=1
```

I spend some time in Summersong, and I make plans with Makah to get back at the Varou.
```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "bond"
    roll "Heart" action=3 adds=1 stat=2 vs1=4 vs2=5
}
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    add 1 "bond"
    add 1 "sojourn"
    roll "Heart" action=3 adds=2 stat=2 vs1=9 vs2=4
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" status="added"
}

```

Next: [[Session 4]]




















