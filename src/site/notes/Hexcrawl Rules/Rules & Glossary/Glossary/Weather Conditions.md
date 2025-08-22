---
{"dg-publish":true,"permalink":"/hexcrawl-rules/rules-and-glossary/glossary/weather-conditions/"}
---

For each [[Hexcrawl Rules/Rules & Glossary/Glossary/Hexcrawl\|Hexcrawl]] a unique table for weather conditions should be generated to reflect the conditions and season of the region where the exploration takes place. Weather conditions affect travel pace, difficulty of navigation and discovering locations as well as how taxing it is to travel. 
### Weather Conditions
Below is a table of the different types of weather and their effects with the following associated mechanics. 
- Speed states a modifier to the travel speed it takes to [[Hexcrawl Rules/Rules & Glossary/Regional Hexcrawl Rules\|enter a hex]].
- Visibility states from how many hexes away from a character can see a [[Hexcrawl Rules/Rules & Glossary/Glossary/Landmark\|landmark]] or how far they can see from a [[Hexcrawl Rules/Rules & Glossary/Glossary/Hexcrawl Vista\|Vista]], with a 0 meaning that they only see their current hex.
- Navigation, Marching (Forced March) and Foraging states - or ADV/DIS which means that a weather condition doesn't change or imposes either Advantage or Disadvantage on the associated checks. If a weather condition imposes disadvantage on navigation it imposes disadvantage on check made to attempt to find hidden or secret locations above ground.
- Resting can state either -, no change from normal resting, camp, meaning that a camp is required to gain the effect of any short or long rest, or shelter, which means that a camp in a sheltered location is required to gain the effects of any long rest.

| Weather          | Speed | Visibility | Navigation | Marching | Foraging | Resting |
| ---------------- | ----- | ---------- | ---------- | -------- | -------- | ------- |
| Clear            | 1     | 5          | ADV        | -        | ADV      | -       |
| Overcast         | 1     | 4          | -          | -        | -        | -       |
| Cloudy           | 1     | 3          | -          | -        | -        | -       |
| Foggy            | 3/4   | 0          | DIS        | -        | DIS      | -       |
| Rain (light)     | 1     | 2          | -          | -        | -        | -       |
| Rain (moderate)  | 3/4   | 1          | -          | -        | -        | Camp    |
| Rain (heavy)     | 3/4   | 0          | DIS        | DIS      | DIS      | Shelter |
| Monsoon          | 1/2   | 0          | DIS        | DIS      | DIS      | Shelter |
| Storm            | 3/4   | 1          | DIS        | DIS      | DIS      | Camp    |
| Storm (powerful) | 1/2   | 0          | DIS        | DIS      | DIS      | Shelter |
| Hurricane        | 1/10) | 0          | DIS        | DIS      | DIS      | Shelter |
| Snow (Light)     | 1     | 2          | DIS        | -        | -        | -       |
| Snow (moderate)  | 1/2   | 1          | DIS        | DIS      | DIS      | Camp    |
| Snow (heavy)     | 1/4   | 0          | DIS        | DIS      | DIS      | Camp    |
Weather Conditions can be combined with the following adverse temperature conditions, taking the most penalizing modifier or affect for each effect. A temperature can be ruled to only apply to certain watches during the day and the conditions imposed by temperature can be counteracted by players actions or resource expenditure at the GMs discretion.

| Temperature | Speed | Visibility | Navigation | Marching | Foraging | Resting |
| ----------- | ----- | ---------- | ---------- | -------- | -------- | ------- |
| Hot         | 1     | -          | -          | DIS      | -        | -       |
| Scorching   | 3/4   | -          | DIS        | DIS      | DIS      | Camp    |
| Cold        | 1     | -          | -          | DIS      | -        | Camp    |
| Freezing    | 3/4   | -          | DIS        | DIS      | DIS      | Shelter |

##### Optional Rule - Severe Weathers
Certain weather are considered severe, indicated by either or both a visibility of 0 or a shelter resting requirement. In these conditions traveling along a coastline, tree line or river does not cause characters to automatically succeed on navigation checks.
#### Weather Table 1 - Salt Desert Summer
To determine the weather condition for the day, roll 2d6 at the end of a long rest or at dawn of no long rest was taken.

| Roll  | Weather               | Speed | Visibility | Navigation | Marching | Foraging | Resting |
| ----- | --------------------- | ----- | ---------- | ---------- | -------- | -------- | ------- |
| 2     | Dust Storm (Powerful) | 1/2   | 0          | DIS        | DIS      | DIS      | Shelter |
| 3     | Dust Storm            | 3/4   | 1          | DIS        | DIS      | DIS      | Camp    |
| 4-6   | Hot and Dry           | 1     | 4          | -          | DIS      | -        | -       |
| 7-9   | Warm and Windy        | 1     | 4          | -          | -        | -        | -       |
| 10    | Warm and Light Rain   | 1     | 2          | -          | -        | -        | -       |
| 11-12 | Clear & Scorching     | 3/4   | 5          | DIS        | DIS      | DIS      | Camp    |

#### Weather Table 2 - Salt Desert Autumn

| Roll  | Weather               | Speed | Visibility | Navigation | Marching     | Foraging | Resting     |
| ----- | --------------------- | ----- | ---------- | ---------- | ------------ | -------- | ----------- |
| 2     | Dust Storm (Powerful) | 1/2   | 0          | DIS        | DIS          | DIS      | Shelter     |
| 3     | Dust Storm            | 3/4   | 1          | DIS        | DIS          | DIS      | Camp        |
| 4-6   | Hot and Dry           | 1     | 4          | -          | DIS          | -        | -           |
| 7-9   | Warm and Windy        | 1     | 4          | -          | -            | -        | -           |
| 10    | Cold Nights           | 1     | 4          | -          | DIS at night | -        | Camp  night |
| 11-12 | Heavy Rain            | 3/4   | 0          | DIS        | DIS          | DIS      | Shelter     |
