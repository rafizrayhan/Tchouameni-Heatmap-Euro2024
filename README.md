# Aurélien Tchouaméni — Action Heatmap | UEFA Euro 2024

## Question
Where does Aurélien Tchouaméni operate on the pitch — 
and does his positional data support why Manchester United 
are linked with signing him?

## Data
StatsBomb Open Data — UEFA Euro 2024
All actions by Tchouaméni across France's tournament matches.

## Methodology
- Loaded StatsBomb free event data using statsbombpy
- Filtered all events to Tchouaméni specifically
- Extracted x/y coordinates for every action
- Plotted a KDE heatmap on a professional pitch 
  using mplsoccer
- Overlaid individual action dots for granularity

## Key Finding
Tchouaméni's heatmap shows a clear concentration 
just right of centre in the defensive and central 
midfield zones — with significant coverage across 
both halves of the pitch. His positional footprint 
confirms he operates as a high-coverage defensive 
midfielder, protecting the backline while 
contributing to build-up play through the centre.

For a Manchester United side that has lacked 
defensive midfield solidity, the data supports 
why he is a primary target — his positioning 
profile fills exactly the gap they need.

## Tools Used
Python · Pandas · Matplotlib · mplsoccer · 
StatsBomb Open Data · statsbombpy · Jupyter Notebook

## Author
Rafiz Rayhan
linkedin.com/in/rafiz-rayhan
github.com/rafizrayhan
