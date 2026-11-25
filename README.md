# Indian Food Nutrition Dataset: 63 Dishes, Recipe-Level, USDA-Sourced

Calories, protein, carbs and fat for 63 Indian dishes, home, restaurant and dhaba versions, with USDA record IDs.

Calories, protein, carbohydrate and fat for 63 common Indian dishes, in 128 rows: the home version of every dish, plus restaurant and dhaba versions where the kitchen changes the dish. Each row is a stated recipe in grams, valued ingredient by ingredient from USDA FoodData Central, with the USDA record IDs listed so every figure can be checked. IFCT 2017 (ICMR-National Institute of Nutrition) is used as a cross reference.

Published figures for Indian dishes disagree widely because almost none state a recipe or a serving weight. This dataset states both. Servings are given in grams, and dals and curries are counted by the katori (150 ml), the small thali bowl.

## Files

| File | What it is |
|---|---|
| [katori-indian-food-dataset.csv](katori-indian-food-dataset.csv) | Full dataset: 128 rows (home, restaurant and dhaba preparations), 19 columns |
| [katori-indian-food-calories.csv](katori-indian-food-calories.csv) | Simple table: 63 rows, 7 columns, home cooking only |

Version 2026.11.17. 50 corrections logged across 41 dish pages.

## Columns (full dataset)

dish, slug, family, preparation, serving, serving_g, serving_ml, kcal, protein_g, carbs_g, fat_g, kcal_per_100g, protein_g_per_100g, carbs_g_per_100g, fat_g_per_100g, fdc_ids, confidence, updated, url.

## Known limits

These are recipe estimates, not lab measurements of plates. One recipe stands for each preparation. USDA values are mostly for US ingredients. The confidence label is a judgement of how well the recipe is anchored, not a statistical interval. Not medical or dietary advice.

## Source and updates

The live source is https://getkatori.com/data. The dish pages show every recipe, and every change is logged in a public corrections log. This repository mirrors the published files; if the two ever differ, getkatori.com/data is current.

## Licence

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Credit line:

> Data: Katori Indian food nutrition dataset, getkatori.com/data (CC BY 4.0)

## How to cite

Verma, S. (2026). Katori Indian food nutrition dataset (Version 2026.11.17) [Data set]. Katori. https://getkatori.com/data
