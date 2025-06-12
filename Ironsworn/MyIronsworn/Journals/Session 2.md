I say farewell to Tallus and his men and press on towards [[Wolf's Pass]].

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=3 vs2=5
    burn from=7 to=2
    progress from=8 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" rank="dangerous" steps=1
}

```

I find my way to the top of a large hill, where I can see [[Summersong]] far to the south in the grassy fields of the [[Havens]]. The vegetation starts to get denser, and the trees taller. I hunt for some food.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=4 vs2=7
}

```
I miss a wild boar with an arrow and it charges at me.
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=3 vs2=8
}
```
The boar charges so fast I don't have time to think. Before I am ready to fire again it hits me in the leg (2 harm).

```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" status="added"
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=4 vs2=1
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" rank="dangerous" steps=2
}

```

The boar charges at me again, but this time I hit it with a well placed arrow and roll out of the way. Then, I run atop a small hill and whistle to Vasor the Hawk, commanding it to distract the boar 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "Hawk"
    roll "Edge" action=2 adds=1 stat=3 vs1=5 vs2=6
}
```

while I prepare another shot. Then I fire.
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=7 vs2=9
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" rank="dangerous" steps=1
}

```
The boar is hit, but is able to climb around the hill and reach me.
```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=5 vs2=7
}
```
I am hit again and my chest hits the floor as I lose my breath.

I get up bleeding, and whistle again to Vasor, trying to gain some distance from the boar.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "vasor"
    roll "Edge" action=3 adds=1 stat=3 vs1=10 vs2=10
}
```

The boar sees Vasor coming and is able to hit it with its great tusks.
```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    add 2
    roll "Health" action=1 adds=2 stat=1 vs1=3 vs2=9
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=6 adds=0 stat=1 vs1=1 vs2=6
}
move "[Companion Endure Harm](datasworn:move:classic\/suffer\/companion_endure_harm)" {
    roll "Heart" action=4 adds=0 stat=2 vs1=2 vs2=10
}

```
I grip my bow hard and sing the keen of the dead, invoking their help, but I don't feel their presence. I must kill this boar. I draw my bow once again for another shot.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=1 vs2=2
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" rank="dangerous" steps=2
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Boar.md|Boar]]" score=10 vs1=8 vs2=7
}

```
It is hit right between the eyes and it falls, dead.
```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Spirit" action=2 adds=0 stat=3 vs1=4 vs2=6
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=4 vs2=1
}

```
I must treat my wounds and stop them bleeding. I clean them with water and bandage them as best as I can.
```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Iron" action=4 adds=0 stat=1 vs1=6 vs2=6
}
```
My wounds are painful and my hands are shaky. I'm not sure I could properly heal them. Then, I notice Vasor is gone, and not answering my calls. I search for it in desperation.


```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=9 vs2=5
}
```

I find Nadros, hiding under a tree trunk. he is hurt and does not want to fly. I gather herbs and water in preparation to heal him
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=9 vs2=4
}
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=2 vs2=3
}

```
I am able to help Nadros. I clean his wing and apply herbs to number the pain. Nadros seems pleased, he chirps happily at me.
The sun will set soon. I must 

```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    add 7 "killed boar"
    roll "Wits" action=5 adds=7 stat=2 vs1=7 vs2=8
}
```

harvest the meat off of that Boar. I set camp and eat the meat.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=2 adds=0 stat=4 vs1=2 vs2=3
}
```

I am able to have a full night's rest with a full belly. The sky was clear and the moon was out. The next day I wake up feeling quite a bit better. I must fletch some more arrows before I continue my journey just in case I encounter any more dangers on the way.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "fletcher"
    roll "Edge" action=2 adds=1 stat=3 vs1=2 vs2=10
}
```

Now I must press on. [[Fool's Fall]] is not far and I wish to rest there before going to [[Wolf's Pass]].

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=3 vs2=8
}
```
I'm getting close now. I am by the ancient hollow tree. I should get to [[Fool's Fall]] tomorrow if everything goes well. But first I need to make Camp. I am still hurt and stressed from my adversities on the last few days.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=4 adds=0 stat=3 vs1=3 vs2=1
}
```

I could eat some more boar meat and relax stargazing under the hollow tree. I'm feeling a bit hopeful. 

I wake up early and prepare a nice breakfast, then clean my boots, in preparation for the journey.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=6 vs2=7
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="Your action has an unintended effect." roll=23

```
I accidentally start a fire, and my belongings might catch on fire. I must put it out now!
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=1 adds=0 stat=1 vs1=1 vs2=5
    burn from=6 to=2
}
```
I am able to put it out. I feel stupid, gather my things and press on.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=6 vs2=2
    progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" rank="dangerous" steps=1
}
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=57 {
    - "I make it to [[Fool's Fall]].  It is a small settlement atop a steep hill. I could see the waterfall from afar, and it lifted my spirits. I really needed to take a break from my journey. I pass and greet a few villagers who are out foraging or gathering water. They do not recognize me. I enter the settlement and look for the master's hall. Is the master present?"
}

```
I greet the guard and request an audience. I am taken inside.
The settlement master's name is Eleri, the fox. She is an elder woman with one arm. She recognizes me.
Is she angry at me? Yes.
"You... Please tell me you have brought the traitor with you, so that he can be brought to justice"
I plead for time and permission to search [[Wolf's Pass]], I tell her that I met Tallus and have promised to retrieve the lost axe-head of the first master. I say that I believe I can help solve this mystery, and that she should give me a chance to uncover the truth, to avoid innocent blood being spilled.
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=10 vs2=1
}
```
She begrudgingly agrees, but under the condition that I make myself useful and help them hunt while I am here, since their best hunter has fallen ill. I thank her for her generosity and take my leave.
```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=8 vs2=10
}
```
The community is not welcoming to me. They all think that I am aiding the traitor. I must at least fulfill my promise to Eleri and hunt some meat for them
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=1 vs2=5
}
```
I fulfill my promise, and deliver a couple of large deers to the butcher. I feel that I have overstayed my welcome and take my leave.
```iron-vault-mechanics
move "[Reach Your Destination](datasworn:move:classic\/adventure\/reach_your_destination)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" score=8 vs1=3 vs2=10
}
```
I've arrived at Wolf's pass. But I face a hazard or complication.
I see signs of a protection ritual there. Someone has placed a warning ward there, letting travelers know to beware of danger, and turn around. However, I can't go back now. I must track the beast that Gawnir saw.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=1 vs2=10
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Spirit" action=5 adds=0 stat=2 vs1=10 vs2=7
}

```
I pass the wards and search for signs of the beast. I can hear spirits talking to me, wailing in the wind that rushes through the mountain gap. This does not bode well.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=3 vs2=7
}
```
I find half the carcass of a great elk, but do not see the other half anywhere around. I find one of the missing bones very far away, up the hill towards the gap. When I look up I see the top of the gap, against the sun. It is a steep rocky cliff. On the bottom of the cliff I see many shattered bones, as if they fell all the way from the top. I presume the beast's lair must be up there.
I search for another way to climb, which is less dangerous.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=9 vs2=3
}
```
I fail to find a better way up, and unfortunately have a misstep and stumble, dropping some of my arrows down a cliff. I decide to go back and find a hole where I can hide in while I can monitor the cliff, waiting to see if I spot the creature.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=3 adds=0 stat=1 vs1=9 vs2=1
}
```
I find a suitable spot and wait patiently the rest of the day. Do I see the creature? No I do not.
I must rest here tonight. There is a chance that the creature shows up at night.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=1 adds=0 stat=3 vs1=9 vs2=7
}
```
I do not see Nadros the next morning and I get worried. Did I see any signs of the creature at night? Yes
I saw it leaving it's nest, high above the steep rock, and returning many hours later, before sunrise.

I look for Nadros, and try to signal to him, then I whistle.
```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=5 vs2=4
}
```
Nadros comes to me, and with him a leather band with runes. It has the rune of [[Fool's Fall]]. Nadros retrieved something that could have been from Fanir!

I take it back to [[Fool's Fall]] and request an audience with Eleri. I tell her what I had seen, then show her the band.
```iron-vault-mechanics
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Clear Gawnir's name.md|Clear Gawnir's name]]" score=8 vs1=6 vs2=6
}
```
Eleri takes the leather strap, and closes her eyes. "I am sorry if I judged you too hastily before. I fear I did worse to poor Gawnir. I did hear stories about the sighting of a flying creature at night, but I did not take heed to them."
```iron-vault-mechanics
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=1 vs2=4
}
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=9 vs2=9
}

```
I forge a bond with the community of [[Fool's Fall]], but only after swearing an Iron vow to drive the Wyvern back away from the region
```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    add 1 "Fool's Pass bond"
    roll "Heart" action=1 adds=1 stat=2 vs1=7 vs2=1
}
```
I must take some time to rest now that I fulfilled my quest and cleared Gawnir's name.
```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "Bond"
    roll "Heart" action=6 adds=1 stat=2 vs1=3 vs2=5
}
```
I spend a week living among them, helping them with hunting and other chores. I tell but mostly hear stories around the campfire. They make me laugh, I lift my spirits and recover my lost supplies.
I meet with an experienced mountain climber named [[Torrens]]. He knows the region well and might be able to assist me in finding a vantage point to better inspect the creature's nest.

```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Drive the Wyvern away from Wolf's Pass.md|Drive the Wyvern away from Wolf's Pass]]" status="added"
```

Next: [[Session 3]]













