# HEMA Longsword Cutting Rankings
Python · Jupyter · Tableau

## Problem
In Historical European Martial Arts (HEMA), a longsword cutting tournament ranks competitors on a series of scored tasks. Events vary in field size, scoring rules, and division structure, which makes it hard for organizers to compare results when placing competitors into skill tiers.

## Data
I used HEMA Scorecard tournament placements and feat scores, plus rankings from 10 experienced organizers and competitors. Placements were available across more events than detailed scores, so I used each source where it could support a comparison.

## Approach
I built a Tableau dashboard to explore event history, medals, finishes, and recent activity. In Python, I tested ranking approaches that considered prior placements, division, field size, and recency. I compared one experimental ranking for active competitors with the expert survey.

## What I found
The experimental ranking and the expert survey shared eight of their top ten competitors. That overlap gave me a way to check whether the ranking broadly agreed with experienced organizers. Predicting future placements is a separate question, and the amount of evidence varies by competitor.

## What to open
Open the Jupyter notebook for data preparation and model comparisons. The companion Tableau dashboard is designed for browsing competition histories and comparing results by tier.
