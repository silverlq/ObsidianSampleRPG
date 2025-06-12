I will try and apply Nissa's teachings and train Vasor to hunt small game. I know that there are rabbits in the grasslands nearby this time of year.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=2 vs2=1
    progress from=12 name="[[Ironsworn\/MyIronsworn\/Progress\/Train Vasor to learn how to hunt.md|Train Vasor to learn how to hunt]]" rank="troublesome" steps=1
}

```
"Excellent Vasor! You found a hare!". He is getting the gist of it. It seems that he is not far off from being ready to do this properly.  I meet with Makah, and he tells me the plan. We have set up a trap for the Varou in one of the farms at the perimeter of Summersong. We placed sheep back into one of the pastures that was raided a while ago, and set up a watch on it. Makah said that one Varou was spotted last night watching from afar. He believes that they will try to do something tonight. We will wait in hiding and spring up on them when they get close.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=8 vs2=3
}
```
I lie under a pile of branches and mud, patiently waiting for them to show up. Do they? Yes.
As they approach, I grip my bow and start to quietly hum my keen of the dead, invoking the ritual Nissa taught me.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=9 vs2=4
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Spirit" action=5 adds=0 stat=2 vs1=2 vs2=6
}

```
I can feel my fingers tingling, and hear the whispers of the spirits of those that were slain by this bow. I feel sweat hit my brow, as I feel nervous about the battle, but at the same time glad that the ritual seems to have worked. The varou are getting close. There are five of them, and three of us.

```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Varou.md|Varou]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=5 adds=0 stat=1 vs1=5 vs2=8
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=3 vs2=4
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Varou.md|Varou]]" rank="dangerous" steps=2
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" rank="dangerous" steps=1
}

```
I fire my arrow and get a clean hit. The beast cries in pain, but very quickly falls on all fours, and spins around searching for me. Does the creature flee? No.
I prepare to shoot another arrow, humming my keen quietly again.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=8 vs2=6
    burn from=8 to=2
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=8 vs2=1
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Varou.md|Varou]]" rank="dangerous" steps=2
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Varou.md|Varou]]" score=8 vs1=7 vs2=3
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Varou.md|Varou]]" status="removed"
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=7 vs2=4
}

```
I can hear the spirits whispering in my ear louder this time. I ready my second arrow and let it loose. It flies, guided by the power of the ritual, and drives deep into the varou's chest, piercing it's heart.
```iron-vault-mechanics
progress from=8 name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" rank="dangerous" steps=1
```
My allies also fire against the other varou, who get hit and injured. Is there any varou left that is willing to fight? Yes.
```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Varou 1.md|Varou]]" status="added"
```
One of the varou who did not get hit by any arrows sees me and charges in my direction. I whistle to Vasor to help while I ready another arrow.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "Vasor"
    roll "Edge" action=3 adds=1 stat=3 vs1=7 vs2=6
}
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Edge" action=3 adds=0 stat=3 vs1=5 vs2=9
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Varou 1.md|Varou]]" rank="dangerous" steps=2
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=2 adds=0 stat=2 vs1=3 vs2=3
}

```
Vasor swoops at it, distracting it for a moment, then I fire, scoring a hit. The varou does not stop, and is able to scratch me with it's claws. I dodge and roll, whistle again and attempt to get some distance to prepare another shot.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "Vasor"
    roll "Edge" action=2 adds=1 stat=3 vs1=3 vs2=3
}
```
This is when I notice, that this varou is different from the others. It is larger and has intricate paint over its face. It also wears a necklace of bones. Vasor swoops in again from the back, and breaks the necklace, carrying it away. The varou is taken by surprise, and it seems that the other varou nearby notice this and it seems to affect their morale, as if the necklace being taken signals an ill omen.
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Edge" action=4 adds=1 stat=3 vs1=10 vs2=10
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=1 vs1=1 vs2=6
}

```
I fire an arrow at it, but it dodges with unnatural speed, then roars and jumps towards me. It seems to be enraged. It bites me and throws me down. I must dodge out of the way and gain some distance now!
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=3 adds=0 stat=3 vs1=5 vs2=6
}
```
I gain some distance, but hear the varou leader howling. And the others answer. He seems to be rallying them for a final charge. I keep running and look for a good spot to stop and take aim.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=5 vs2=4
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Edge" action=2 adds=1 stat=3 vs1=1 vs2=5
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Varou 1.md|Varou]]" rank="dangerous" steps=3
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Varou 1.md|Varou]]" score=10 vs1=9 vs2=8
    progress from=16 name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" rank="dangerous" steps=1
}

```
The varou advance towards us. They are all furious. I ready an arrow, hold my breath, and fire towards the leader. The arrow hits it in the gut. It is too much for that varou, it groans and falls. Makah also scores a kill on another varou. The remaining varou grab their leader and start to drag him away.
I step forward and shout: "Listen, creatures of the woods! This is our land, and our cattle. Do not return here again unless you seek death! We will always be ready for you, and watching. Stay within the tree line and we shall not hurt you!"
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=5 adds=0 stat=1 vs1=1 vs2=9
}
```
The varou stare at me, and seem to understand what I am saying. "Let's kill all of them now that we have the chance!" says one of the hunters with me. "No! We shall let these live, so that they tell the others not to return" I respond.
```iron-vault-mechanics
progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" rank="dangerous" steps=1
track name="[[Ironsworn\/MyIronsworn\/Progress\/Varou 1.md|Varou]]" status="removed"
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" score=8 vs1=4 vs2=2
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Drive Varou away from Summersong.md|Drive Varou away from Summersong]]" status="removed"
}

```
One of the varou who heard this talk looks at me, and nods with a slight bow, then howls and retreats with the others, carrying their dead leader. "That's it. I think we've done it!" cheers Makah with a smile. "You've kept your promise to me Nadros, now I am in your debt" he says. I look down at my bow, and feel the tingling go away. The whispers of the spirits quietly disappear into the wind.
```iron-vault-mechanics
progress from=24 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern.md|Learn to craft arrows deadly for a wyvern]]" rank="troublesome" steps=1
move "[Advance](datasworn:move:classic\/quest\/advance)" {
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern.md|Learn to craft arrows deadly for a wyvern]]" status="removed"
    track name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" status="added"
}

```
Makah meets me the next day to discuss the matter of the arrow crafting. "I've seen twisted arrows that could pierce through anything. And I had said that I could teach you but... I exaggerated I bit. I can show you what I know, but to really learn the proper way to craft these you must search for [[Ikram]], the fletcher. He is the one who taught me this long ago. He lives in a settlement far to the south named [[Deepwater]]". Makah showed me what he knew, and helped me craft a few arrows.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "fletcher"
    roll "Edge" action=1 adds=1 stat=3 vs1=4 vs2=6
    progress from=12 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" rank="dangerous" steps=1
}

```
I seek medical help at Summersong to treat my wounds, then I rest for a long while.
```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=4 vs2=2
}
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "bond"
    roll "Heart" action=4 adds=1 stat=2 vs1=7 vs2=2
}
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=1 vs2=4
}

```
I speak to Gawnir, who is really pleased about what I did for him. He invites me over to his shack and we share a meal. "I can't thank you enough, Nadros. You risked yourself for me, I am in debt" he says. "Are you going back to [[Fool's Fall]] now that you are no longer hunted?" I ask.
Is he? "Yes, I suppose I will. I need to make amends with [[Eleri]] and the others. But not yet, I am not in a hurry. Maybe the next time you go there I will join you in your travel" he says as we finish our potato soup.

Next: [[Session 5]]


















