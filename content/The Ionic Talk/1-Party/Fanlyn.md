---
publish: true
Type: Player
Level: 1
AC: 13
Prof: 2
HP: 13
HitDice: d8
Speed: 30
STR: 10
DEX: 15
CONST: 12
INT: 10
WIS: 20
CHA: 15
Race:
  - "[[Kitsune]]"
Sub-Race: "[[Kitsune#Seishin]]"
Alignment: "[[Alignment#Chaotic good]]"
Gender: Female
Sexuality: Lesbian
Age: "216"
Location: Feywilds
Class:
  - "[[Druid]]"
Subclass: 
AssociatedGroup: "[[Vizin Family]]"
Likes: Animals
Dislikes: Bad people
Pronouns: She/her
PersonalityTrait:
  - I feel far more comfortable around animals than people.
SocialTrait:
  - An injury to the unspoiled wilderness of my home is an injury to me.
  - I remember every insult I've received and nurse a silent resentment toward anyone who's ever wronged me.
MentalTrait:
  - The natural world is more important than all the constructs of civilization.
Proficiencies:
  - Light Armor
  - Medium Armor
  - Shields
  - Club
  - Dagger
  - Dart
  - Javelin
  - Mace
  - Quarterstaff
  - Scimitar
  - Shortbow
  - Sickle
  - Sling
  - Spear
  - Herbalism Kit
Resistances:
  - NONE
Languages:
  - Common
  - Druidic
  - Elvish
  - Sylvan
---
>[!column|flex 2]
>> [!infobox]
>> # `=this.file.name`
>> # ![[Fanlyn Token.png]]
>> ###### Stats
>>  |
>> ---|---|
>> **Level** |`=this.level` |
>>  **Speed** |`=this.Speed` |
>> **Proficiency** | +2 |
>> **Initiative** | +`=(this.DEX - 10)/2` |
>> **AC** | `=this.AC`
>> **HP** | `=this.HP` |
>> **Hit Dice** | `=this.Level + this.HitDice`  |
>> **Passive Perception** | `=(this.WIS - 10) / 2 + 10`
>>  
>> ###### Bio
>>   |
>> ---|---|
>> **Race** | `=this.race` |
>> **Sub-Race** | `=this.Sub-Race` |
>> **Sex** | `=this.gender` |
>> **Age** | `=this.age` |
>> **Sexuality** | `=this.sexuality` |
>> **Alignment** | `=this.alignment` |
>> ###### Info
>>   |
>> ---|---|
>> **Class(s)** | `=this.Class` |
>> **Sub-Class(s)** | `=this.Subclass`
>> **Group(s)** | `=this.AssociatedGroup` |
>> **Religion(s)** | `=this.AssociatedReligion` |
>
>> [!infobox] Death Saves
>> ### Death Saves
| Success | <input type="checkbox" >  | <input type="checkbox" > | <input type="checkbox" > | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fails | <input type="checkbox" >  | <input type="checkbox" > | <input type="checkbox" > | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Skills
| Skill | Score       | Mod                     | Prof                              | ST                                  |
| ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |
| <font color="#ff0000">**STR**</font>   | `=this.STR` | +`=(this.STR - 10)/2`   | <input type="checkbox" > | +`=(this.STR - 10)/2`               |
| <font color="#ffff00">**DEX**</font>   | `=this.DEX`  | +`=(this.DEX - 10)/2`   | <input type="checkbox" > | +`=(this.DEX - 10)/2`               |
| <font color="#00b050">**CON**</font>   | `=this.CONST` | +`=(this.CONST - 10)/2` | <input type="checkbox" >   | +`=((this.CONST - 10)/2)` |
| <font color="#7030a0">**INT**</font>   | `=this.INT`          | +`=(this.INT - 10)/2`   | <input type="checkbox" checked >   | +`=((this.INT - 10)/2) + 2`   |
| <font color="#245bdb">**WIS**</font>   | `=this.WIS`          | +`=(this.WIS - 10)/2`   | <input type="checkbox" checked >  | +`=(this.WIS - 10)/2 + 2`               |
| <font color="#de7802">**CHA**</font>   | `=this.CHA`          | +`=(this.CHA - 10)/2`   | <input type="checkbox" > | +`=(this.CHA - 10)/2`               |
>> ### Skill Checks
| Ability               |                                   | Mod |
| --------------------- | --------------------------------- | --- |
| Acrobatics (DEX)      | <input type="checkbox" > | +`=(this.DEX - 10)/2`   |
| Animal Handling (WIS) | <input type="checkbox" checked  > | +`=(this.WIS - 10)/2+2`  | 
| Arcana (INT)          | <input type="checkbox" > | +`=((this.INT - 10)/2)`  |
| Athletics (STR)       | <input type="checkbox" checked  > | +`=(this.STR - 10)/2+2`   |
| Deception (CHA)       | <input type="checkbox" > | +`=(this.CHA - 10)/2`  |
| History (INT)         | <input type="checkbox" > | +`=(this.INT - 10)/2`  |
| Insight (WIS)         | <input type="checkbox" >   | +`=((this.WIS - 10)/2)`  |
| Intimidation (CHA)    | <input type="checkbox" > | +`=(this.CHA - 10)/2`  |
| Investigation (INT)   | <input type="checkbox" checked >   | +`=((this.INT - 10)/2)+2`  |
| Medicine (WIS)        | <input type="checkbox" > | +`=(this.WIS - 10)/2`  |
| Nature (INT)          | <input type="checkbox" checked > | +`=(this.INT - 10)/2+2`  |
| Perception (WIS)      | <input type="checkbox" >   | +`=((this.WIS - 10)/2)`  |
| Performance (CHA)     | <input type="checkbox" > | +`=(this.CHA - 10)/2`  |
| Persuasion (CHA)      | <input type="checkbox" > | +`=(this.CHA - 10)/2`  |
| Religion (INT)        | <input type="checkbox" > | +`=(this.INT - 10)/2`  |
| Sleight of Hand (DEX) | <input type="checkbox" > | +`=(this.DEX - 10)/2`   |
| Stealth (DEX)         | <input type="checkbox" > | +`=(this.DEX - 10)/2`   |
| Survival (WIS)        | <input type="checkbox" checked > | +`=(this.WIS - 10)/2+2`  |

![[Druid#Druidic]]
![[Druid#Spellcasting]]
![[Kitsune#Darkvision]]
![[Kitsune#Fox’s Cunning]]
![[Kitsune#Fey Ancestry]]
![[Kitsune#Languages]]
![[Kitsune#Will-o-wisp]]
![[Kitsune#Clandestine]]
