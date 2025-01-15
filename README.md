# About this app
This app helps you see state-level patterns driving CDC's national predicted overdose data. The corresponding [rendered and interactive app](https://deepnote.com/app/opioiddatalab/WONDER-vs-12-month-Predicted-OD-data-ce7d8424-642b-490e-b484-ef63058a2a98) is for huamn interpretation of overdose trends.

Check out [our post](https://opioiddatalab.ghost.io/peak-od-phenotypes/) about these data for background and data collection and smoothing methods.

# What the lines mean
The 💜 prediction line is the official predicted overdose trend from [CDC NVSS provisional overdose data](https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm) -- you know, the data that media and policymakers use to understand what's happening with overdose trends nationally. The orange 🍊 line is the state's monthly count of final certified overdose deaths, aka the messy "truth." But it takes years for those data to post. We downloaded from [CDC WONDER](https://wonder.cdc.gov/), where they go through 2022 (final) or 2023 (provisional). The blue 💙 line is a yearly line we calculated ourselves by summing the monthly 🍊 "truth" data, a recreation of the official yearly violet 💜 prediction line. 

# About the heatmap
The heatmap below the lines shows 💜 prediction line in shades of purple, the 12-month predicted overdose count. The aqua box is the 12 month window corresponding to the highest overdose month (aqua bar). By comparing the peak month (aqua) to the orange line, you can see get a sense the OD pattern contributing to the predicted peak. Sometimes, the orange peak may not align with the aqua peak month, which we [explain here](https://opioiddatalab.ghost.io/peak-od-phenotypes/).

# Beyond
This app was built by Nabarun Dasgupta at the University of North Carolina at Chapel Hill in January 2025. This app is not scheduled for regular updates, but can be if y'all find it useful and send us a request (opioiddatalab@unc.edu).

# Data and Code
All data used in the app are from public open sources. The app is written in Python 3.10 for data science. The app is hosted within a distributed Deepnote environment. 
