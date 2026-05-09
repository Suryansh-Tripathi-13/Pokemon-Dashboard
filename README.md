#Pokemon Dashboard


1 — Project Title / Headline:-

🎮 Pokémon Complete Pokédex: Types, Stats & Generations Dashboard:-

An interactive and visually stunning Power BI dashboard built to explore the complete Pokémon dataset — focusing on type distribution, generation-wise analysis, legendary breakdown, habitat stats, and top Pokémon rankings from Generation 1 to Generation 9.

2 — Short Description / Purpose:-

The Pokémon Complete Pokédex Dashboard is a visually themed and analytically powerful Power BI report designed to help users explore and understand the entire Pokémon universe through data. Built on a dataset of 1,350+ Pokémon across 18 unique types and 9 generations — this dashboard highlights key metrics like total Pokémon count, total types, legendary Pokémon count, and total generations.
This tool is built for Pokémon fans, data analysts, content researchers, and Power BI learners who want to understand which types are most common, how Pokémon are spread across generations, and which Pokémon have the highest base stats.

3 — Tech Stack:-

* 📊 Power BI Desktop – Main platform used for building all visuals and reports
* 🗂️ Power Query – Used for loading and connecting the cleaned Pokémon dataset
* 🧮 DAX (Data Analysis Expressions) – Used for KPI cards and custom measures like Total Pokemon, Total Types, Legendary Count, Total Generations, and Pokemon Rank
* 🐍 Python (Pandas) – Used for data cleaning, null value handling, column renaming, Legendary_Status column creation, and Sprite URL generation
* 📁 File Format – .pbit for Power BI report template
* 🎨 Theme – Pokémon inspired light pastel theme featuring Pikachu, Charmander, Squirtle, Bulbasaur, Snorlax, Gengar, Charizard, Blastoise, and Eevee characters

4 — Data Source:-

Source: Kaggle — https://www.kaggle.com/datasets/patelris/pokemon-dataset-with-stats-and-types

Dataset contains Pokémon records from Generation 1 to Generation 9 — covering base stats, types, abilities, legendary status, habitat information, and sprite image URLs for 1,350+ unique Pokémon.


Key Fields:

* Name – Name of the Pokémon
* Type_1 – Primary type (Water / Fire / Grass / Electric and more)
* Type_2 – Secondary type if applicable
* HP, Attack, Defense, Sp_Attack, Sp_Defense, Speed – Individual base stats
* Base_Stat_Total – Sum of all base stats
* Generation – Generation number (1 to 9)
* Legendary_Status – Non-Legendary / Legendary / Mythical
* Habitat – Natural habitat of the Pokémon
* Sprite_URL – Official image URL for each Pokémon


5-  Features / Highlights:-

a — Business Problem:-

The Pokémon franchise has grown massively over 30 years — with 1,350+ Pokémon across 9 generations and 18 different types. Without a structured analytical view, it is very difficult to understand which types dominate, how base stats vary by habitat, and which Pokémon are truly the strongest. Fans and researchers need a clear and simple way to explore this massive dataset interactively.


b — Goal of the Dashboard:-


The goal of this Pokémon Complete Pokédex Dashboard is to provide one single interactive report where anyone can:

* ✅ See total Pokémon, total types, legendary count, and generations using KPI Cards
* ✅ Understand type distribution using Pokémon by Type Donut Chart
* ✅ Discover generation-wise Pokémon count using Clustered Column Chart
* ✅ Compare generation data using Clustered Bar Chart
* ✅ Explore average stats across different habitats using Avg. Stats by Habitat Bar Chart
* ✅ See the top 3 strongest Pokémon with images using Top 3 Highest Base Stat Table
* ✅ Filter the entire dashboard by Generation, Type, and Legendary Status using Interactive Slicers


c — Walk Through of Key Visuals:-

* KPI Cards (Top Row):
  
Show Total Pokémon (1,350), Total Types (18), Legendary Pokémon, and Total Generations (9) — gives an instant snapshot of the entire Pokédex in one glance. Each card is themed with a Pokémon character matching the dashboard design.

* Pokémon by Type (Donut Chart):
  
Shows how all 1,350+ Pokémon are distributed across 18 types — clearly highlighting that Water, Normal, and Grass are the most dominant types in the Pokédex.

* Pokémon by Generation (Clustered Column Chart):
  
Displays the total number of Pokémon introduced in each generation vertically — Generation 1 leads with 238 Pokémon, followed by Generation 5 with 185.

* Pokémon by Generation (Clustered Bar Chart):
  
Same generation data displayed horizontally for easy comparison — making it simple to see which generations contributed the most Pokémon to the franchise.

* Avg. Stats by Habitat (Clustered Bar Chart):
  
Shows the average base stats of Pokémon grouped by their natural habitat — revealing which habitats tend to produce stronger Pokémon overall.

* Top 3 Highest Base Stat Pokémon (Table with Images):
  
Displays the top 3 strongest Pokémon by Base Stat Total with their official sprite images and names — making it the most visually engaging element of the dashboard.

* Interactive Slicers (3 Filters):
  
Allow users to filter the entire dashboard by Generation (1-9), Type (18 types), and Legendary Status — enabling dynamic cross-filtering across all visuals with just one click.


d — Business Impact & Insights:-


* 💧 Water is the most common type — leading with 160 Pokémon across all generations
* 🏆 Eternatus-Eternamax is the strongest Pokémon — with a record-breaking Base Stat Total of 1,125
* 📈 Generation 1 introduced the most Pokémon — contributing 238 unique Pokémon to the franchise
* ⭐ Only 11.7% of Pokémon are Legendary or Mythical — making them truly rare and special
* 🌿 Habitat affects average stats — certain habitats consistently produce stronger Pokémon
* 🎮 Dataset spans 9 generations — from Generation 1 (1996) to Generation 9 (2022) covering the full history of the Pokémon franchise
* 🔢 18 unique types exist — with Water, Normal, and Grass being the top 3 most common

6 — Screenshot / Demo:-

Show what the dashboard looks like.

<img width="891" height="499" alt="Pokemon Dashboard" src="https://github.com/user-attachments/assets/465ec5d0-680c-4521-b8db-14216de35d0e" />








