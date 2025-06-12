I will wake up early, two hours before the sunrise, and set camp on a hill near the lake watching the roads that leave [[Deepwater]] to try to spot [[Ikram]]'s hunting party as they leave.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=6 vs2=1
}
```
I guess correctly that the hunting party will take a small trail northeast towards the woods nearby. I await the party behind a row of trees on a slope as they cross a small brook. I can see [[Ikram]] among them, and they do not seem to spot me. I say:

"Hail, hunters! I was looking for you [[Ikram]], but I could not find you. I just left [[Deepwater]] this morning, it is fortunate that our paths should cross. My name is [[Nadros]], from [[Summersong]]."

Some of them are a bit surprised by my sudden appearance, but I show both my hands empty and slowly walk towards them as a sign of peace.

"[[Makah]] from [[Summersong]] has told me of your great skills in arrow craft, [[Ikram]]. I am in dire need of assistance in preparing an arrow for a foul beast that has been haunting us up north."
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1 "advantage"
    roll "Heart" action=3 adds=1 stat=2 vs1=7 vs2=6
    burn from=10 to=2
}
```
"Walk with us, [[Nadros]]" [[Ikram]] says. I follow them as they walk towards the woods and I share my story and the perils I've encountered. I do not mention my meeting with [[Henna]], but I ask: "it is none of my business, but it saddens me to see the people of [[Deepwater]] divided as it is now. I wonder if there will come a day when your leaders will see eye to eye."
"Yes, [[Nadros]] I can envision such a future. [[Cadigan]] is too eager to attack the southerners, but I believe that [[Henna]]'s plan will work. We will fortify our defenses for now and plan an attack on the southerners once summer comes. Once we succeed in driving them away from our lannds [[Cadigan]] will see that he had been mistaken about [[Henna]]'s leadership. They will come to terms in due time."

I enter the woods with the hunters. They need to resupply the village with meat and leather. I will assist them, and once they are done Ikram has promised to show me a few tricks on the way back.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    add 1
    roll "Wits" action=3 adds=1 stat=2 vs1=5 vs2=4
}
```
"You are a keen hunter, [[Nadros]]" compliments [[Ikram]] as he sees the two bucks I've shot. That night we set up camp and discuss the issue of the Wyvern in [[Fool's Fall]].
```iron-vault-mechanics
progress from=28 name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" rank="dangerous" steps=1
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" score=9 vs1=5 vs2=8
}
roll "Wits" action=3 adds=1 stat=2 vs1=1 vs2=4
track name="[[Ironsworn\/MyIronsworn\/Progress\/Learn to craft arrows deadly for a wyvern 1.md|Learn to craft arrows deadly for a wyvern]]" status="removed"

```

[[Ikram]] shares his secrets with me. We gather wood from a strong hard tree, and cut and prepare a long arrow shaft with great care. He gives me an arrow head with a short metal point and a twisted edge. He shows me how to reinforce the arrow and secure the head to the shaft. The tail is constructed with beautiful clipped feathers from a goose. He gives me a small flask with an oil that will coat the arrow so that it flies true and finds its mark. I hold it with great excitement, knowing that this could be the key to driving the Wyvern away, and thinking that this might unlock even more doors in the future. I think of the terrible basilisk that paralyzed my mother.
"This is incredible. Thank you Ikram. I am in your debt. I will need to go back to [[Fool's Fall]] and make preparations to attack the beast soon, but know that if you ever need my assistance for anything my bow is yours".

We say our farewells and I start my journey back to the northern havens.
```leaflet
id: myironlands
image: [[Ironlands-Map.png]]
bounds: [[0,0], [1784, 1341]]
height: 250px
lat: 913
long: 829
minZoom: -1
maxZoom: 1.5
defaultZoom: -1.5
zoomDelta: 0.5
scale: 1.12
unit: km
```
```iron-vault-mechanics
track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Fool's fall.md|Journey back to Fool's fall]]" status="added"
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1
    roll "Wits" action=3 adds=1 stat=2 vs1=6 vs2=6
}

```
Do [[Cadigan]]'s men ambush me and steal my bow and arrows? **Yes**

I walk westward towards a great hill that is the last place that oversees the lake by [[Deepwater]], and suddenly a group of ruffians springs out of the woods and surrounds me. They are [[Cadigan]]'s men. They take my belongings. "What were you doing with [[Henna]]'s hunters in the woods? What is your business here stranger?" one of them asks.
"I only came to [[Deepwater]] to speak to [[Ikram]] so that he would teach me how to craft that arrow" I point to the black arrow with the twisted tip in my pack. "There is a wyvern up north that must be dealt with. I am not part of your politics. I am not in allegiance with [[Henna]]. Please, there is no need for this. Let me continue my journey north".
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=4 adds=0 stat=2 vs1=4 vs2=10
}
```
They return my belongings, but they take the arrow. "Fancy arrows, hey? So [[Ikram]] is crafting these? We will take it, [[Cadigan]] needs to see this. You may continue your journey, stranger. But we advise you not to return here."

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1
    roll "Wits" action=4 adds=1 stat=2 vs1=1 vs2=1
    progress from=0 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey back to Fool's fall.md|Journey back to Fool's fall]]" rank="dangerous" steps=1
}

```
I press on and find shelter on a cave near the mountainside. A good place to set up camp.
```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=5 adds=0 stat=4 vs1=5 vs2=8
}
```
I recuperate, relax and eat some of the salted deer meet I still had from the hunt with [[Ikram]]. The next day I wake up feeling refreshed and ready for another long walk. I decide I will craft another arrow for the Wyvern along the journey.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1
    roll "Wits" action=1 adds=1 stat=2 vs1=7 vs2=7
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="A surprising development complicates your quest." roll=84
oracle-group name="Action and Theme Oracles: New Action and Theme Oracles" {
    oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Lose" roll=89
    oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Duty" roll=14
}

```
I stop by a stream to rest, and I realize that the flask of oil that Ikram had given me has gone missing.





