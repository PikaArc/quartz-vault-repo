---

publish: true
Type: Player
Level: 1
AC: 12
Prof: 2
HP: 13
HitDice: d8
Speed: 30
STR: 14
DEX: 14
CONST: 7
INT: 16
WIS: 16
CHA: 12
Race:
  - "[[human|Human]]"
Sub-Race: Variant Human
Alignment: Chaotic Good
Gender: Male
Age: "31"
Location: NONE
Class:
  - "[[Cleric]]"
Subclass: Knowledge Domain
AssociatedGroup: NONE
Likes: NONE
Dislikes: The voices in my head
Pronouns: He/Him/Anything
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies:
  - Simple Weapons
  - Light Armor
  - Medium Armor
  - Shields
Resistances:
  - NONE
Languages:
  - Common
  - Latin?
---
>[!column|flex 2]
>> [!infobox]
>> # `=this.file.name`
>> # ![[Ntyss Token.png]]
>> ###### Stats
>>  |
>> ---|---|
>> **Level** |`=this.level` |
>>  **Speed** |`=this.Speed` |
>> **Proficiency** | +`=this.Prof` |
>> **Initiative** | +`=(this.DEX - 10)/2` |
>> **AC** | `=this.AC`
>> **HP** | `=this.HP ` |
>> **Hit Dice** | `=this.Level + this.HitDice`  |
>> **Passive Perception** |
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
| Success | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fails | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Skills
| Skill | Score       | Mod                     | Prof                              | ST                                  |
| ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |
| <font color="#ff0000">**STR**</font>   | `=this.STR` | +`=(this.STR - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`               |
| <font color="#ffff00">**DEX**</font>   | `=this.DEX`  | +`=(this.DEX - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`               |
| <font color="#00b050">**CON**</font>   | `=this.CONST` | +`=(this.CONST - 10)/2` | <input type="checkbox" unchecked>   | +`=((this.CONST - 10)/2)` |
| <font color="#7030a0">**INT**</font>   | `=this.INT`          | +`=(this.INT - 10)/2`   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`   |
| <font color="#245bdb">**WIS**</font>   | `=this.WIS`          | +`=(this.WIS - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`               |
| <font color="#de7802">**CHA**</font>   | `=this.CHA`          | +`=(this.CHA - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`               |
>> ### Skill Checks
| Ability               |                                   | Mod |
| --------------------- | --------------------------------- | --- |
| Acrobatics (DEX)      | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Animal Handling (WIS) | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Arcana (INT)          | <input type="checkbox" unchecked> | +`=((this.INT - 10)/2)`  |
| Athletics (STR)       | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`   |
| Deception (CHA)       | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| History (INT)         | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Insight (WIS)         | <input type="checkbox" unchecked>   | +`=((this.WIS - 10)/2)`  |
| Intimidation (CHA)    | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Investigation (INT)   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`  |
| Medicine (WIS)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Nature (INT)          | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Perception (WIS)      | <input type="checkbox" unchecked>   | +`=((this.WIS - 10)/2)`  |
| Performance (CHA)     | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Persuasion (CHA)      | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Religion (INT)        | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Sleight of Hand (DEX) | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Stealth (DEX)         | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Survival (WIS)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |