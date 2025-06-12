I am close to Deepwater now. Probably another day or two and I'll be there. I am at the top of a mountain ridge, looking at the tree-covered lands to the south. I reflect on my quest so far. I wonder if the people of [[Fool's Fall]] are safe from the Wyvern. Anyways, time to hunt. I whisper a command to Vasor and let him do his work.
```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    add 1 "vasor"
    roll "Wits" action=6 adds=1 stat=2 vs1=4 vs2=2
}
```
I score a small deer! I'll get to eat plenty the next few days. Time to press on.
```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1 "vasor"
    roll "Wits" action=4 adds=1 stat=2 vs1=8 vs2=1
    progress from=32 name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" rank="dangerous" steps=1
}
move "[Reach Your Destination](datasworn:move:classic\/adventure\/reach_your_destination)" {
    progress-roll name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" score=10 vs1=10 vs2=4
}

```
Is [[Ikram]] not there? No, he is there but there is a complication.
```iron-vault-mechanics
oracle name="[Settlement Oracles \/ Settlement Trouble](datasworn:oracle_rollable:classic\/settlement\/trouble)" result="Families in conflict" roll=65
track name="[[Ironsworn\/MyIronsworn\/Progress\/Journey to Deepwater.md|Journey to Deepwater]]" status="removed"

```
[[Deepwater]] is under a civil dispute. Their leader has fallen under a sudden illness leaving no heir and two different families are arguing over their claim to the iron circlet. This village is often at war with a group of raiders further to the south, and a lack of leadership could spell disaster if the raiders decide to attack when the people are not united.

I arrive and am greeted by a guard: "these are strange times, traveller. Deepwater is not the same as it once was. Distrust is in the air. Take care and be weary of whom you speak to. The wardens are few and disorder is rampant."

I don't know where this Ikram could be so I go to the nearest tavern and look for shelter. They take me in exchange for some of the dried meat I still have from that deer I hunted the other day.

Where is Ikram? Defend Time.
Does the inn keeper tell me where to find him? No

The inn keeper says "Ikram? Aye, I know him. Craftsman. Smith. I haven't seen him since the clans have started arguing. He used to work down by the water wheel, not sure if he is still there".

I go looking for him the next day, starting with the mill at the river. Is he there? No.

The smithy near the mill seems to be abandoned. No one answers me there. I go to the mill. There is a farmer there. I ask him if he knows where Ikram is. Does he answer me? Yes.

An ugly fat man answers me. "Yes, I know where he is. He stays at the longhouse now with the new chieftain. The chief thinks there will be mutiny so she keeps the smith working for her so that their blades stay sharp".

I head towards the chief's longhouse. It sits on the top of a hill and inside a wooden fence. Guards stop me. "Halt! Who approaches Henna's longhouse?". I hail them and tell them where I come from. "I only wish to greet the chief, and consult with her smith regarding the forging of an object to aid a distant village". 
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=2 vs2=5
}
```
"Very well. However, you must leave all your weapons outside. The bird also cannot enter". I tell Vasor to wait for me outside, and let him fly. Then, I enter the longhouse.

"Greetings Henna of [[Deepwater]]. My name is [[Nadros]], I have come from [[Fool's Fall]], a settlement far away to the north that is being tormented by a terrible beast. I have heard that your people are also going through difficult times" I bow. "Hello, Nadros. I recognize a fellow ironsworn when I see one. I know the people of [[Fool's Fall]], for I have traveled far in my youth. [[Eleri]] is an old friend of mine. Undoubtedly you must be here to request some sort of aid. As you can see my people is divided and we are always on the watch for southerner raiders. We cannot spare any spears" she answers. "I understand. I only ask to speak to your smith, [[Ikram]]. [[Gawnir]], a warden of the north, has sent me here to learn a special craft from Ikram that may aid me in my quest to save [[Fool's Fall]]".
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1
    roll "Heart" action=2 adds=1 stat=2 vs1=6 vs2=8
}
```
"[[Ikram]], huh. I do not allow you to speak to him. He is very occupied at the moment and I do not wish to give him any distractions" she sternly responds. "Is there any way that I may aid you, so that this internal conflict may be resolved for [[Deepwater]]?" I plead. "[[Cadigan]] is the name of my cousin, a fool who seems to believe he has a claim to the iron circlet. He and his followers have caused us great grief, and endanger us with this dispute. If you convince him to swear an iron vow that he will accept me as the true leader of [[Deepwater]], only then I will be able to call this feud ended" she asks. "That sounds like it will not be an easy task. Where may I find this [[Cadigan]]?" I say. "They have a longhouse by the pier on the lake. Don't keep your hopes up" she says. 

I leave the longhouse and retrieve Vasor and my equipment. I go to the pier to seek for [[Cadigan]]. Is he there? Yes.
"Who are you, stranger?" one of the guards asks at the pier. "Hello there, my name is [[Nadros]], from [[Summersong]]. I would like to request an audience with [[Cadigan]]".

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=1 vs2=4
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1
    roll "Wits" action=1 adds=1 stat=2 vs1=2 vs2=3
}
oracle-group name="Action and Theme Oracles: New Action and Theme Oracles" {
    oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Inspect" roll=14
    oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Strategy" roll=99
}

```
I am allowed in the longhouse, but before I enter I ask the guard about this family feud. He says "This is not just about who has a blood-right to the iron circlet. The people of [[Deepwater]] is torn between the more defensive posture of [[Henna]] and the offensive plans of [[Cadigan]]. He claims, and I believe, that we need to attack the southerners with a united strike, and not sit around waiting for them to raid us."
I enter a great longhouse by the water. It serves as a workshop for the boats and nets they use for fishing. Cadigan is finishing carvings on a great war boat. "Master Cadigan, this northerner has asked to see you" the guard says.

"Hail, master Cadigan. I am [[Nadros]], from the north. I have come from the village of [[Fool's Fall]] seeking council about a terrible beast that has haunted it."

"A beast you say? We have enough trouble here as is, with the wretched southerners stalking our borders. What do you hope to find here?"

"I came here looking for [[Ikram]], he is said to have knowledge of fine arrow craft which could help me in my quest."

Is Cadigan in good terms with Ikram?

"Ah, Ikram. Yes, skilled hands, but a fool. He follows [[Henna]] blindly. You probably were denied a meeting with him weren't you? Is that why you came to me?"

"You can see much, master Cadigan. I don't know much about your people and your conflicts. However, I would like to help you. Is there any chance that you and Henna could see eye to eye again? Surely the people would be stronger if reunited."
```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=10 vs2=10
}
```
Cadigan puts down his tools and steps out of the boat, then walks towards me and looks me in the eye. "Listen, northerner. You have no clue who you are talking to or what you are talking about. Henna and I will not see eye to eye, she is a traitor and a coward. You should leave now, before you regret it."

"Forgive me master Cadigan, yes I will take my leave of course. Just know that I am here offering my service if needed."

I leave and go sit by a bridge to gather my thoughts. I may not be destined to help [[Deepwater]] with it's troubles. However, I came here to look for help. I may have to seek Ikram without permission. 

I go to the tavern to gather information. I ask the bartender if he ever sees Ikram. "No, that fellow is hard at work and [[Henna]] does not allow him to go far. He never leaves the fenced area anymore".
```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=5 adds=0 stat=2 vs1=6 vs2=6
}
```
"However, Ikram goes hunting with Henna's men every once in a while. I think I heard the hunting party is setting out tomorrow morning".

I consider going back to Henna's longhouse. However, I feel this will only anger her more. I decide to watch for the hunters as they leave and I will try to approach [[Ikram]] and plead my cause to him and the others.

Next: [[Session 7]]



