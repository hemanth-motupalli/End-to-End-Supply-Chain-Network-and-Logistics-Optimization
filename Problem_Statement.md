# Problem Statement: Supply Chain Network Optimization

## Objective
A petroleum and gas distribution company receives crude oil at two major ports: Bombay (190 million barrels/month) and Belekeri (110 million barrels/month). This supply must be transported to meet strict consumption demands in Chennai (200 million barrels) and Bangalore (100 million barrels). 

The network consists of intermediate transshipment nodes (Solapur, Hubli, Mangalore, Gulbarga). The objective is to determine the optimal flow quantity through each pipeline link to minimize the total transportation cost.

## Scenario 1: Base Network Flow
Minimize the total cost across the network without any pipeline disruptions or node capacity constraints.

## Scenario 2: Disrupted Network & Capacitated Facilities
Due to severe weather, the pipeline connecting Solapur to Gulbarga is completely disrupted (capacity = 0). Additionally, the Bangalore receiving depot faces a logistical bottleneck and cannot handle an input of more than 150 million barrels. The network flow must be re-optimized to account for these constraints while still strictly satisfying the demand at Chennai and Bangalore.
