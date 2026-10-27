# Smart Household Appliance Scheduling Using MATLAB

## Project Overview

**Smart Household Appliance Scheduling** is a MATLAB-based project that reduces household electricity costs by automatically scheduling appliances during hours when electricity tariffs are lower.

The system analyzes the electricity tariff for 24 hours and identifies the most cost-effective operating time for each appliance while satisfying its operating duration and scheduling constraints.

This project demonstrates how smart scheduling can help households reduce electricity bills and improve energy management.

## Problem Statement

Electricity tariffs may vary throughout the day. Operating high-power household appliances during expensive hours can increase electricity costs.

The objective of this project is to develop an intelligent scheduling strategy that shifts appliance operation to lower-tariff hours without violating the specified operating time constraints.

## Objectives

* Analyze electricity tariffs over a 24-hour period.
* Schedule household appliances during lower-cost hours.
* Compare electricity costs before and after optimization.
* Calculate the total cost savings.
* Visualize electricity tariffs, appliance loads, and cost comparisons using MATLAB graphs.

## Technologies Used

* **Programming Language:** MATLAB
* **Simulation Tool:** MATLAB
* **Optimization Technique:** Minimum-cost time-slot selection
* **Visualization:** MATLAB plots, stairs graphs, and bar charts

## Appliances Considered

| Appliance       | Power Rating | Operating Duration |
| --------------- | -----------: | -----------------: |
| Washing Machine |         1 kW |            2 hours |
| Water Heater    |         2 kW |             1 hour |
| Dishwasher      |       1.2 kW |            2 hours |

The scheduling algorithm considers each appliance's power rating, operating duration, earliest starting time, and deadline.

## Methodology

### 1. Define Electricity Tariffs

The system uses electricity tariff values for all 24 hours of a day.

### 2. Define Appliance Requirements

Each appliance is assigned:

* Power consumption in kW
* Required operating duration
* Earliest permitted start time
* Latest completion deadline
* Baseline starting time

### 3. Calculate the Baseline Cost

The program calculates electricity consumption and cost using the original appliance schedules.

### 4. Optimize Appliance Scheduling

The algorithm checks the permitted starting times for each appliance and calculates the electricity cost for each possible operating period.

It selects the starting time with the lowest calculated cost.

### 5. Compare the Results

The program calculates:

* Baseline electricity cost
* Optimized electricity cost
* Total cost savings

### 6. Generate Graphs

MATLAB generates three graphs to visualize the results.

## Output Graphs

### Graph 1: Electricity Tariff

Displays the electricity tariff for each hour of the day.

### Graph 2: Load Comparison

Compares household power consumption before and after optimization.

* Red line: Baseline load
* Blue line: Optimized load

### Graph 3: Cost Comparison

Displays the total electricity cost before and after optimization.

## How to Run the Project

1. Install MATLAB.
2. Open MATLAB.
3. Create a new script named `smart_household_scheduling.m`.
4. Copy the project MATLAB code into the script.
5. Save the file.
6. Click **Run**.
7. View the optimized appliance schedule, electricity costs, savings, and generated graphs in MATLAB.

## Expected Results

After execution, the program displays:

* Optimized starting time for each appliance
* Baseline electricity cost
* Optimized electricity cost
* Total estimated cost savings

The three graphs provide a visual comparison of electricity tariffs, household load profiles, and total electricity costs.

**Note:** The actual savings depend on the defined tariff values and appliance scheduling constraints.

## Applications

* Smart homes
* Home energy management systems
* Smart grid applications
* Electricity cost optimization
* Energy-efficient appliance scheduling
* Demand-side energy management

## Future Enhancements

* Implement the scheduling strategy using MATLAB Simulink.
* Add more household appliances.
* Include appliance priority and user preferences.
* Prevent multiple appliances from exceeding a specified household power limit.
* Develop a real-time scheduling system using smart meters and IoT devices.
* Explore optimization algorithms that consider interactions between appliances.

## Limitations

* The current algorithm optimizes each appliance independently.
* It does not explicitly enforce a maximum household power limit.
* It uses predefined electricity tariffs rather than live tariff data.
* It assumes that each appliance operates continuously for its required duration.
* It does not account for appliance startup delays or changing user preferences.

## Conclusion

The Smart Household Appliance Scheduling project demonstrates how MATLAB can be used to reduce household electricity costs through intelligent appliance scheduling.

By selecting lower-cost operating periods and comparing baseline and optimized schedules, the system illustrates the potential benefits of smart energy management.

## Project Type

Academic Project | MATLAB Simulation | Smart Energy Management
