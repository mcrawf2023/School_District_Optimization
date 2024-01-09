The goal of this problem set was to create a linear programming model in R that minimized the busing cost per student across 6 areas and 3 schools, while holding to the appropriate grade percentage thresholds for each school and not violating the school capacities. Our optimal solution involved sending all 450 students from area 1 to school 2, sending 432 students from area 2 to school 2 and 168 students from area 2 to school 3, 4 students from area 3 to school 1 and 218 from area 3 to school 2 and 328 from area 3 to school 3, sending all 350 students from area 4 to school 1, sending 364 kids from area 5 to school 1 and 136 to school 3, sending 82 kids from area 6 to school 1 and 368 to school 3. After building the model and determining the initial optimal solution, we conducted a sensitivity analysis to determine the impact of road construction on busing costs and how that would change the ideal distribution of students across schools. This revealed that increasing busing costs 10% for area 6 schools would raise the student busing costs to a range within the limit of the optimal solution we initially identified. Therefore, we still recommend the same number of students from each area be sent to each of the different schools as we did in our initial analysis. Finally, in order to evaluate the cost effectiveness of installing a portable classroom to increase a school's capacity, we investigated the school constraint duals (shadow prices) and their respective dual ranges in order to find the largest cost minimization margin over the classroom leasing cost. We recommended the school board install one portable classroom in school 2, as it would lead to a busing cost decrease of $3,333.33, and an overall cost decrease of $833.33 after adding in the cost of leasing the room ($2500).
