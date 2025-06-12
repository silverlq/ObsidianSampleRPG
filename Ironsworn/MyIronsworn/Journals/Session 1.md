I consult with Makah. He says: "Wyverns have not been seen in the Hinterlands for generations. This is odd indeed. Are you sure [[Gawnir]] is telling the truth?"

I believe Gawnir, because he swore an iron vow, claiming to be telling the truth. Makah continues: "If this is indeed true, then surely you should be able to find tracks or other evidence of such a huge beast."

I decide to travel back from Summersong in the Havens to the Wolf's Pass near the Hinterlands, where I had first found Gawnir in the woods, while travelling back from a hunting expedition.

```leaflet
id: myironlands
image: [[Ironlands-Map.png]]
bounds: [[0,0], [1784, 1341]]
height: 250px
lat: 970
long: 770
minZoom: -1
maxZoom: 1.5
defaultZoom: 0
zoomDelta: 0.5
scale: 1.12
unit: km
```

```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" status="added"
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=4 adds=0 stat=2 vs1=6 vs2=1
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Hinterlands.md|Journey to Hinterlands]]" rank="dangerous" steps=1
}
oracle name="[Place Oracles \/ Location Descriptor](datasworn:oracle_rollable:classic\/place\/descriptor)" result="Inaccessible" roll=49

```

I reach grassy hills where the terrain is cut by a deep river with a strong current, and find a suitable spot to make camp and spend the night. The next day I search for a suitable place to ford the river and press on northwards.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=1 adds=0 stat=2 vs1=4 vs2=4
}
```
I have a hard time fording the river. The current is stronger than I had remembered. Some of my arrows are lost while crossing (Pay the price).
*What is the nature of the random event?* **Await Creature**

A [[Sodden]] ambushes me while crossing the river. It is a horrendous creature with mottled flesh and dead, milky eyes.
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=1 adds=0 stat=1 vs1=5 vs2=2
    burn from=4 to=2
}
```
The thing grabs me and attempts to drag me underwater and drown me. I fight it, and kick it as hard as I can. I am barely able to escape it's grasp, but I am horrified by it (endure stress) and attempt to flee the water as fast as possible.
```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=3 adds=0 stat=2 vs1=9 vs2=2
}
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=3 vs2=8
}

```
I am able to run and delay the creature by firing at it, but I end up losing many arrows in the process (-1 supply). However, I manage to escape.
I move away from the river and look for a suitable spot to camp and rest. My clothes are still soaked and my spirit is shaken.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=3 adds=0 stat=2 vs1=2 vs2=5
}
```
I am able to relax (+1 spirit) that night, but I realize that I have lost and wasted many arrows the day before, so I decide to forage and to fletch some arrows.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "fletcher"
    roll "Edge" action=3 adds=1 stat=3 vs1=9 vs2=2
}
```
Then, I resume my journey.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=2 vs1=8 vs2=5
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="A person or community you trusted loses faith in you, or acts against you." roll=4

```

I encounter travelers from [[Fool's Fall]] on my way. The caravan leader is a man named Tallus. He says: "Nadros, what are you doing so far north from Summersong? Please don't tell me you are going to the Hinterlands. You are no longer welcome there. You sould have listened to our messengers and returned Gawnir, the traitor, for his judgement and execution". I apologize and attempt to reason with him, explaining that I am investigating Gawnir's incident in the forest, and asking for permission to enter the Hinterlands for this purpose.
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=6 vs2=1
}
```
They allow me to proceed. But they ask something in return. What is the nature of their request? **Capture memory**
The man Gawnir allegedly killed was carrying something valuable, and they ask me to find that item and return it to their possession. I agree to do so (already part of existing vow).
```iron-vault-mechanics
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="History" roll=35 
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Desolation" roll=86{
    - "What is the nature of this item?"
}

```
It is an old damaged axe that used to belong to the founder of [[Fool's Fall]]. I did not see Gawnir with that item when I met him.

I ask details about Gawnir and the victim.
```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1 "Compel"
    roll "Wits" action=1 adds=1 stat=2 vs1=1 vs2=7
}
```

Gawnir and Fanir (the victim) were cousins, and they both longed to wed the same lady. Fanir was the son of the leader of [[Fool's Fall]].

Next: [[Session 2]]




