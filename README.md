<p align="center">
  <img src="https://raw.githubusercontent.com/0vergrown/Origins-Dietary-Delights/main/pack.png" alt="Dietary Delights cover"/>
</p>

# Dietary Delights
**Dietary Delights** extends and refines the functionality of LuaDotExe's "We Have the Meats" by expanding compatibility between the Origins mod and a comprehensive list of other food-related mods. This pack introduces detailed item tags for various diets, facilitating the creation of unique Origin traits based on dietary preferences and restrictions.
## Target Audience
This pack is designed primarily for developers looking to enhance or create custom Origins with specific dietary needs. It is also beneficial for those in the modding community looking to standardize dietary tags across various mods.
## Key Features
- **Expanded Meat Category:** Incorporates modded items into the 'meat' category, ensuring compatibility with Origins’ dietary systems.
- **New Dietary Tags:** Introduces categories like **Ketogenic**, **Organic**, **Vegan**, **Pescatarian**, and **Vegetarian**, allowing for the creation of Origins with unique dietary-based abilities or restrictions.
## Supported Mods
Dietary Delights works with the following mods:

01. (Let's Do) Bakery
02. (Let's Do) Vinery
03. AdventureZ
04. Alaska Native Craft
05. Anthropophagy
06. Aquaculture Delight
07. Autovw's Burger Mod/Burger Mod Fabricated
08. Better Animals Plus
09. Better Nether
10. Born In Chaos
11. Brewin' And Chewin'
12. Chest Cavity
13. Chirpy's Wildlife
14. Corn Delight
15. Croptopia
16. Cultural Delights
17. Ecologics
18. End's Delight
19. Expanded Delight
20. Farmer's Delight
21. Farmer's Respite
22. Fish of Thieves
23. Food+
24. Golden Steak
25. Jellyfishing
26. Kentucky Fried Axolotls (KFA)
27. Midas Hunger
28. Naturalist
29. Nether Depths Upgrade
30. Nether's Delight
31. Ocean's Delight
32. Pam's HarvestCraft 2 - Food Core
33. Promenade
34. Quality Crops
35. Quality's Delight
36. Silent's Delight
37. Snowpig
38. Spit Splat
39. Twilight Forest
40. Turkish Delight
41. Unusual Delight (Hostile Delight)
42. Unusual Fish Mod
43. ValleyCraft
44. Vampire's Delight
45. Vampirism
46. Vegan Delight
47. Vietnam's Delight
48. You've Goat to be Kidding Me
49. Bountiful Fares
50. Spawn
51. (Let's Do) Candlelight
52. Twilight's Flavors & Delight
53. Nears
54. Immersive Weathering
## Implementation Guide
### Specific Dietary Tag
To apply a specific dietary tag, such as Pescatarian, use the following JSON structure:
```json
"item_condition": {
    "type": "origins:ingredient",
    "ingredient": {
        "tag": "origins:pescatarian"
    }
}
```
This setup ensures that the Origin can utilize only items tagged as Pescatarian.
### General Meat Category
For Origins designed to consume any type of meat, the simplified `origins:meat` tag can be utilized:
```json
"item_condition": {
    "type": "origins:meat"
}
```
This configuration allows the Origin to use any item classified under the expanded Meat category.
### Organic Tag
The `organic` tag has been broadly defined to encompass all possible items from supported mods plus vanilla foods, aligning with the literal definition of "organic" in a non-chemical context in Minecraft.
