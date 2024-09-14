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

1. (Let's Do) Bakery
2. (Let's Do) Vinery
3. AdventureZ
4. Alaska Native Craft
5. Anthropophagy
6. Aquaculture Delight
7. Autovw's Burger Mod/Burger Mod Fabricated
8. Better Animals Plus
9. Better Nether
10. Born In Chaos
11. Brewin' And Chewin'
12. Chest Cavity
13. Chirpy's Wildlife
14. Corn Delight
15. Croptopia
16. Cultural Delights
17. Ecologics
18. Expanded Delight
19. Farmer's Delight
20. Farmer's Respite
21. Fish of Thieves
22. Food+
23. Golden Steak
24. Jellyfishing
25. Kentucky Fried Axolotls (KFA)
26. Midas Hunger
27. Naturalist
28. Nether Depths Upgrade
29. Nether's Delight
30. Ocean's Delight
31. Pam's HarvestCraft 2 - Food Core
32. Promenade
33. Quality Crops
34. Quality's Delight
35. Silent's Delight
36. Snowpig
37. Spit Splat
38. Twilight Forest
39. Unusual Delight (Hostile Delight)
40. Unusual Fish Mod
41. ValleyCraft
42. Vampirism
43. Vampire's Delight
44. Vegan Delight
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
