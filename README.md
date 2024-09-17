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

01. AdventureZ
02. Alaska Native Craft
03. Anthropophagy
04. Aquaculture Delight
05. Autovw's Burger Mod/Burger Mod Fabricated  
06. Better Animals Plus  
07. Better Nether  
08. Born In Chaos  
09. Bountiful Fares  
10. Brewin' And Chewin'  
11. Chest Cavity  
12. Chirpy's Wildlife  
13. Corn Delight  
14. Croptopia  
15. Cultural Delights  
16. Ecologics  
17. Ender's Delight  
18. End's Delight  
19. Expanded Delight  
20. Farmer's Delight  
21. Farmer's Respite  
22. Fish of Thieves  
23. Food+  
24. Golden Steak  
25. Immersive Weathering  
26. Jellyfishing  
27. Kentucky Fried Axolotls (KFA)  
28. (Let's Do) Bakery  
29. (Let's Do) Candlelight  
30. (Let's Do) Vinery  
31. Midas Hunger  
32. Naturalist  
33. Nears  
34. Nether Depths Upgrade  
35. Nether's Delight  
36. Ocean's Delight  
37. Pam's HarvestCraft 2 - Food Core  
38. Promenade  
39. Quality Crops  
40. Quality's Delight  
41. Silent's Delight  
42. Snowpig  
43. Spawn  
44. Spit Splat  
45. Twilight Forest  
46. Twilight's Flavors & Delight  
47. Turkish Delight  
48. Unusual Delight (Hostile Delight)  
49. Unusual Fish Mod  
50. ValleyCraft  
51. Vampire's Delight  
52. Vampirism  
53. Vegan Delight  
54. Vietnam's Delight  
55. You've Goat to be Kidding Me
56. End's Phantasm
57. Galosphere
58. Nether Additions
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
