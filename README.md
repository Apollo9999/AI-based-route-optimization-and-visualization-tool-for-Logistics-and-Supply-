# Title-OF-THE-PROJECT-AI-based-route-optimization-and-visualization-tool-for-Logistics-and-Supply-

Problem Statement Defined as Every day, thousands of orders are placed with retailers and ecommerce companies which are delivered to consumers. These orders are delivered by hundreds of drivers who follow a prescribed route to honor the customers’ availability. At the same time, retailers strive to reduce cost by minimizing routes, trucks and drivers. However, the customer’s availability itself is very dynamic today. Customers today want flexibility- delivery at home/ office/ pickup etc. Can the platforms be capable of adjusting to customer preferences instead of the other way around?


# Project Objective Identified as 

The objective of project is to addresses a new variant of the vehicle routing problem (VRP) with time windows, in which the vehicle fleet comprises units of different capacities and some overloads (i.e., loading vehicles above nominal capacity) are allowed. Although often encountered in practice, the problem, which we call heterogeneous fleet vehicle routing with overloads and time windows Due to technological advancements extensive and rapid development in logistics and supply chain management fields witnessed, one of the critical problems in the decision-making system is that how to arrange a proper supply chain for a lot of destinations and suppliers and produce a detailed supply schedule under a set of constraints. Solutions to the multisource vehicle routing problem(MDVRP) help in solving this problem in case of transportation applications.

Given the locations of sources and destinations, the MDVRP requires the assignment of destination to sources and the vehicle routing for visiting them. Each vehicle originates from one source, serves the destinations assigned to that source, and returns to the same source. The objective of the MDVRP is to serve all destinations while minimizing the total travel distance (hence cost) under the constraint that the total demands of served destinations cannot exceed the capacity of the vehicle for each route.

Solution Approach

The Main motive and aim is to Fleet Optimization improving both route planning and demand forecasting thereby reducing overall time and petrol,diesel etc spend

This project uses a heuristic algorithm to solve problem Statement. The proposed algorithm consists of 4 phases:

Phase 1: Find the destination nodes which will be catered by each source node using a modified k-means clustering algorithm.

Phase 2: Do preliminary analysis on the points for determining the type and number of the vehicles for given constraints.

Phase 3: Assign the vehicle to the subsets of the destination points using K-means while minimizing the fuel cost.

Phase 4: Optimize the routing for the allotted locations using Travelling Salesman optimization for each vehicle.

Technology Stack

Azure Maps (distance API and routing)

Azure Machine Learning (training modified K-NN)

Azure Notebooks (prototyping and data analysis)

Azure App Service (Web-based deployment using MapBox and Streamlit)

Python,Json



