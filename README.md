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
- Alaska Native Craft
- Anthropophagy
- Autovw's Burger Mod/Burger Mod Fabricated
- Better Animals Plus
- Better Nether
- Chest Cavity
- Chirpy's Wildlife
- Corn Delight
- Croptopia
- Cultural Delights
- Ecologics
- Expanded Delight
- Farmer's Delight
- Farmer's Respite
- Fish of Thieves
- Food+
- Golden Steak
- Kentucky Fried Axolotls (KFA)
- Midas Hunger
- Nether Depths Upgrade
- Nether's Delight
- Promenade
- Twilight Forest
- ValleyCraft

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
