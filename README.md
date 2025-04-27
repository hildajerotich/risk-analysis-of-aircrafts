# Aircraft Incident Analysis for Operational Risk Mitigation

## Overview

This project analyzes aircraft incident and accident data to guide a company in safely entering the aviation industry by selecting aircraft with the lowest operational risk. By examining factors such as total injuries, aircraft make/model, weather conditions, flight phases, engine configurations, and aircraft categories, we identify patterns influencing injury rates. Insights from this analysis will inform strategic decisions on fleet procurement, pilot training protocols, weather-related safety measures, and engine preferences to minimize risk and build customer trust.

---

## Business Understanding

### Stakeholders

- **Directors / Business Owners**: Prioritize purchasing aircraft with minimal safety risks to protect reputation and financial stability.
- **Operations Manager**: Optimize fleet scheduling and logistics using safety-focused insights.
- **Pilots and Crew Members**: Ensure aircraft reliability and safety across diverse operational conditions.

### Key Business Questions

1. Which aircraft makes/models have the lowest historical injury rates?
2. How do weather conditions impact injury severity?
3. Which flight phases (takeoff, cruise, landing) are most injury-prone?
4. Does engine configuration (number/type) influence safety?
5. Are certain aircraft categories (e.g., helicopters) riskier for commercial use?
6. What operational strategies minimize risk when building a new fleet?

---

## Data Understanding and Analysis

### Source of Data

The dataset is sourced from the **National Transportation Safety Board (NTSB)**, detailing incidents/accidents involving injuries, aircraft characteristics, and environmental factors.

### Description of Data

The dataset includes the following key columns:

| Column Name                        | Description                                                         |
| ---------------------------------- | ------------------------------------------------------------------- |
| Make                               | Aircraft manufacturer (e.g., Cessna, Bell)                          |
| Model                              | Aircraft model                                                      |
| Total fatal/serious/minor injuries | Number of injuries by severity level                                |
| Injury severity                    | Classification of incident severity (Fatal, Serious, Minor)         |
| Broad phase of flight              | Flight phase during incident (Takeoff, Landing, Cruise)             |
| Weather Condition                  | Weather at incident time (e.g., VMC, IMC)                           |
| Number of engines and engine type  | Engine count and type (e.g., Single-engine reciprocating, Turbojet) |
| Aircraft Category                  | Classification (Small Airplane, Helicopter)                         |

A new `total_injuries` column was created by aggregating injury columns for streamlined analysis.

### Key Visualizations

#### _Aircraft Make By Total Injuries Visualization_

![Aircraft Make By Total Injuries Visualization](./Aircraft%20Make%20Visualization.png)

#### _Weather Condition By Total Injuries Visualization_

![Number Of Engines And Engines Types By Total Injuries Visualization](./Engine%20configurations%20visualization.png)

#### _Weather Condition By Total Injuries Visualization_

## ![Weather Condition By Total Injuries Visualization](./Weather%20condition%20visualization.png)

## Conclusion

### Summary of Findings

1. **Aircraft Make/Model**: Manufacturers like **Bell** demonstrated lower total injuries, making them safer choices.
2. **Weather Impact**: While most injuries occurred in **Visual Meteorological Conditions (VMC)** due to higher flight volumes, **Instrument Conditions (IMC)** posed higher severity risks.
3. **Engine Configuration**: Single-engine reciprocating aircraft were linked to more incidents, favoring multi-engine turbine models for commercial safety.

### Operational Recommendations

- **Fleet Procurement**: Prioritize multi-engine, turbine-powered aircraft (e.g., Bell 206) with low injury histories.
- **Training Protocols**: Focus on takeoff and landing phases, where injuries are most frequent.
- **Weather Policies**: Implement strict safety checks for IMC conditions despite fewer flights.
- **Aircraft Diversity**: Avoid high-risk categories (e.g., small single-engine planes) for commercial operations.

By leveraging these insights, the company can strategically reduce operational risks and establish a trusted aviation brand.
