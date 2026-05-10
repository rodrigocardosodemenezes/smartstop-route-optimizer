# SmartStop — Multi-Stop Route Optimizer

A route optimization algorithm that reorders multi-stop rideshare 
rides to minimize total travel distance and time.

Built as part of a Computer Programming class project at NOVA SBE 
(2nd Year Management, 2025), combining AI prompting, Python logic, 
and product innovation thinking.

## The Problem
Rideshare apps (Uber, Bolt) take multi-stop rides in the order 
passengers type them — not the optimal geographic order. 
This routinely adds 20–40% in unnecessary distance.

## The Solution
SmartStop automatically reorders stops using a constrained TSP 
(Travelling Salesman Problem) solver: Nearest-Neighbor heuristic 
+ 2-opt improvement. Runs in <50ms, client-side.

## Try the Demo
Open SmartStop_RouteOptimizer.html in any browser.

## Integration
See the commented code inside the HTML file for Google Maps API 
and Uber/Bolt API integration examples.
