# Rimworld-Crop-Calculator
Rimworld Crop Calculator
# First of all we need to find how many crop we can produce from a single block in 30 days. Later we are going to calculate the harvest.
# IMPORTANT NOTE: THE DATA IN RIMWORLDWIKI.COM ISN'T DETAILED ENOUGH TO CALCULATE CORRECTLY THE FOLLOWING PLANTS:
# HOP,HEALROOT,POTATO,PSYCHOID,SMOKELEAF,STRAWBERRY
# If you have the necessary informations about these plants, please inform us from our reddit or discord.

# Calculations

# Let's say we are going to produce potato.

# Potato eaten by a single colonist perday would be 30 potatoes which means 3 meals a day each colonist.
# potato_for_30_days = potato_eaten_by_a_single_colonist_perday * colonists * 30.0 # for 30 days / we calculate the amount of potato we need in this line
# then we assume 30% of the harvest would go bad because of the harvest fail.
# corn_for_30_days_final = corn_for_30_days * 0.7
# After this line we make another calculation to find how many crops we are going to need
# potato1 = potato_for_30days_final / PotatoPlant1 (potato1-2-3-4 represents each dirt type in the game.)
# The amount of crop you need = the amount of potatoes you will have at the end of 30 days / The amount of product it gives from every plant.
# "PotatoPlant1 = 40 # gravel" thats the one we used in this example.
# PotatoPlant2 = 40 # soil
# PotatoPlant3 = 40 # rich soil
# PotatoPlant4 = 40 # hydroponics
# 
