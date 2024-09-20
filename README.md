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
02. (Let's Do) Candlelight  
03. (Let's Do) Vinery  
04. AdventureZ  
05. Aether Delight  
06. Alaska Native Craft  
07. Anthropophagy  
08. Aquaculture Delight  
09. Autovw's Burger Mod/Burger Mod Fabricated  
10. Better Animals Plus  
11. Better Nether  
12. Born In Chaos  
13. Bountiful Fares  
14. Brewin' And Chewin'  
15. Chest Cavity  
16. Chirpy's Wildlife  
17. Corn Delight  
18. Croptopia  
19. Cultural Delights  
20. Ecologics  
21. End's Delight  
22. End's Phantasm  
23. Ender's Delight  
24. Expanded Delight  
25. Farmer's Delight  
26. Farmer's Respite  
27. Fish of Thieves  
28. Food+  
29. Galosphere  
30. Golden Steak  
31. Immersive Weathering  
32. Jellyfishing  
33. Kentucky Fried Axolotls (KFA)  
34. Midas Hunger  
35. Naturalist  
36. Nears  
37. Nether Additions  
38. Nether Depths Upgrade  
39. Nether's Delight  
40. Ocean's Delight  
41. Pam's HarvestCraft 2 - Food Core  
42. Promenade  
43. Quality Crops  
44. Quality's Delight  
45. Silent's Delight  
46. Snowpig  
47. Spawn  
48. Spit Splat  
49. The Aether  
50. Twilight Forest  
51. Twilight's Flavors & Delight  
52. Turkish Delight  
53. Unusual Delight (Hostile Delight)  
54. Unusual Fish Mod  
55. ValleyCraft  
56. Vampire's Delight  
57. Vampirism  
58. Vegan Delight  
59. Vietnam's Delight  
60. You've Goat to be Kidding Me
61. Biome Makeover
62. Delightful
63. Ars Nouveau
64. Ecologics
65. Rotten Leather
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
