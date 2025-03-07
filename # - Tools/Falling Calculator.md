---
title: Falling Calculator
aliases: 
fall_dist: 55
time_unit: 1
dist_unit: 0
fall_time: 1
v: 29.84881315372245
x: 148.35483197987398
v2: 254
drop_dist: 0
dicenum: "2"
drop_DC: 0
drop_DC_half: 0
drop_dmg: 0
acr: 
fall_dmg: 15
dex_save: 11
---
# Falling Calculators

###### **Variant Rule:** Fall damage with drag
The following calculators will give you information on falling, which take into account drag. The [[The Player's Handbook|PHB]] limit on falling damage is removed in favor of terminal velocity (52.18 m/s). The damage scale is calibrated such that 10ft of falling equates exactly 1d6 of damage. Available units are m, ft, s, and rounds (6s).

> [!column| 3 no-t]+
>> [!note| clean no-t]
>>  ### **Units**
>> ||
>> -|-|
>> Length Unit:<BR />`INPUT[inlineSelect(option(0,m), option(1,ft)):dist_unit]` | Time Unit:<BR />`INPUT[inlineSelect(option(0,s), option(1,rounds)):time_unit]`
>
>> [!note| clean no-t]
>>  ### **Time**
>> ||
>> -|:-:|
>> | Falling distance | `INPUT[number(class(nb-mb-55)):fall_dist]` `VIEW[{dist_unit} ? "ft" : "m"]`                                                                                                     |
>> | Falling speed   | `VIEW[52.184894023 * tanh(acosh(exp((9.81*{fall_dist}*(1-0.6952*{dist_unit}))/52.184894023^2)))][math(hidden):v]` `VIEW[round((1+5*{time_unit})*{v}, 0)]` `VIEW[{dist_unit} ? "ft" : "m"]`/`VIEW[{time_unit} ? "round" : "s"]` |
>> | Falling time | `VIEW[round(52.184894023/(9.81*(1+5*{time_unit})) * acosh(exp(9.81*{fall_dist}*(1-0.6952*{dist_unit})/(52.184894023^2))), 0)]` `VIEW[{time_unit} ? "round" : "s"]`
>> | Damage           | `VIEW[round(({v}/7.690899087747)^2, 0)]`d6 
>
>> [!note| clean no-t]
>>  ### **Distance**
>> ||
>> -|:-:|
>> | Falling time     | `INPUT[number(class(nb-mb-55)):fall_time]` `VIEW[{time_unit} ? "rounds" : "s"]` |
>> | Falling speed    | `VIEW[round(52.184894023*(1+5*{time_unit})/(1-0.6952*{dist_unit})*tanh({fall_time}*(1+5*{time_unit})*9.81/52.184894023), 0)][:v2]` `VIEW[{dist_unit} ? "ft" : "m"]`/`VIEW[{time_unit} ? "rounds" : "s"]` |
>> | Falling distance | `VIEW[(52.184894023)^2/9.81 * log(cosh(9.81*{fall_time}*(1+5*{time_unit})/52.184894023))][math(hidden):x]` `VIEW[round({x}/(1-0.6952*{dist_unit}), 0)]` `VIEW[{dist_unit} ? "ft" : "m"]` |'
>>  | Damage           | `VIEW[round(({v2}*(1-0.6952*{dist_unit})/(7.690899087747*(1+5*{time_unit})))^2, 0)]`d6 
^FallingCalculator

> [!info | bg-c-red]- Requirements
> * **ITS Theme**
> * **Meta Bind**
>  ###### CSS-Snippets:
> * nb-mb-55.css

# Landing
###### **Variant Rule:** Dropping

> [!infobox]
> # Dropping
> ||
> -|:-:|
> Height |`INPUT[number(class(nb-mb-55)):drop_dist]` `VIEW[{dist_unit} ? "ft" : "m"]`|
> Acrobatics roll | `INPUT[number(class(nb-mb-55)):acr]`|
> DC:  `VIEW[round({drop_dist}/(0.3048+0.6952*{dist_unit}), 0)][:drop_DC]` | Half DC: `VIEW[round(1/2 * {drop_dist}/(0.3048+0.6952*{dist_unit}), 0)][:drop_DC_half]`
> **Damage** | **`VIEW[round(((52.184894023 * tanh(acosh(exp((9.81*{drop_dist}*(1-0.6952*{dist_unit}))/52.184894023^2))))/7.690899087747)^2, 0)][math(hidden):drop_dmg]` `VIEW[{acr} >= {drop_DC} ? "No damage" : {acr} >= {drop_DC_half} ? round({drop_dmg}/2, 0) : {drop_dmg}]`­`VIEW[{acr} < {drop_DC} ? "d6" : ""]`**
> **Prone?** | **`VIEW[{acr} < {drop_DC_half} ? "Yes": "No"]`** |

When jumping off a short cliff, house, or dropping down a ledge or out of a tree, your character is aware they are falling and picking their opportunity. It therefore make sense for the character to be able to land safer and reduce or even negate any falling damage that they would otherwise take. 

When a creature make a conscious drop to a lower level that risks damaging the creature, roll an acrobatics (dexterity) check against the drop in feet. If the creature succeeds on the check, they take no damage and does not land prone. If they succeed on half the DC, the creature takes half damage and does not land prone. Otherwise on a failure, the creature takes full damage and lands prone.

###### **Variant Rule:** Landing Prone (fall)
> [!infobox]
> # Landing [[Prone]]
> ||
> -| :-: |
> Fall damage | `INPUT[number(class(nb-mb-55)):fall_dmg]`
> Dexterity Save | `INPUT[number(class(nb-mb-55)):dex_save]`
> DC | `VIEW[round(sqrt(10*{fall_dmg}), 0)]`
> **Prone?** | **`VIEW[{dex_save} >= round(sqrt(10*{fall_dmg}), 0) ? "No" : "Yes"]`**

Even when a creature unwillingly falls, they might be able to use some of the momentum to get back up standing at the end of their fall. To determine if the creature ends its fall prone, roll a Dexterity Saving Throw against the square root of 10 times the fall damage taken. On a success, the creature is not prone. On a failure, the creature is [[prone]].




