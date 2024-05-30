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

1. AdventureZ
2. Alaska Native Craft
3. Anthropophagy
4. Aquaculture Delight
5. Autovw's Burger Mod/Burger Mod Fabricated
6. Better Animals Plus
7. Better Nether
8. Born In Chaos
9. Chest Cavity
10. Chirpy's Wildlife
11. Corn Delight
12. Croptopia
13. Cultural Delights
14. Ecologics
15. Expanded Delight
16. Farmer's Delight
17. Farmer's Respite
18. Fish of Thieves
19. Food+
20. Golden Steak
21. Jellyfishing
22. Kentucky Fried Axolotls (KFA)
23. Midas Hunger
24. Naturalist
25. Nether Depths Upgrade
26. Nether's Delight
27. Ocean's Delight
28. Promenade
29. Quality Crops
30. Quality's Delight
31. Silent's Delight
32. Snowpig
33. Spit Splat
34. Twilight Forest
35. ValleyCraft
36. Vegan Delight
37. (Let's Do) Bakery
38. (Let's Do) Vinery

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
