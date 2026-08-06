# Data Dictionary

This document describes each column in the **Transportation Cost Analysis Project** Excel template.

Understanding each field ensures that all participants collect and record data consistently.

| Column | Description |
|---------|-------------|
| **Location** | The region or area of the city where the journey originates (e.g., Woji, Rumuokoro, GRA Phase 2). |
| **Start_Point** | The major bus stop, junction, or landmark within the selected residential area where the journey begins. |
| **Destination** | The final destination of the journey (e.g., University of Port Harcourt, Rivers State University, Mile 1 Market). |
| **Route_Type** | Indicates whether the journey is **Direct** (the commuter travels to the destination without changing vehicles) or **Multi-Stops** (the commuter changes vehicles one or more times before reaching the final destination). |
| **Stop_Order** | The sequence number of each stage of the journey, beginning with **1** for the first stop. |
| **Stop_Name** | The name of the bus stop, junction, or landmark reached at each stage of the journey. This includes transfer points and the final destination. |
| **Transport_Type** | The type of transportation used for that stage of the journey (e.g., Bus, Taxi, Tricycle, Motorcycle, Boat). |
| **Cost** | The transportation fare paid for that individual stage of the journey. |
| **Cumulative_Cost** | The running total transportation cost from the beginning of the journey up to the current stop. |
| **Total_Cost** | The total transportation fare from the selected starting point to the final destination. This value should remain the same for every row belonging to the same route. |
| **NumberOfStops** | The total number of stops or stages required to complete the journey from the starting point to the final destination. |
| **Latitude** | The geographic latitude of the recorded stop or landmark. This is used for mapping and spatial analysis. |
| **Longitude** | The geographic longitude of the recorded stop or landmark. This is used for mapping and spatial analysis. |
| **Source_Type** | The source used to verify the transportation fare (e.g., Driver, Conductor, Regular Commuter, Transport Union Representative). |
| **Date** | The date the transportation fare was collected or verified. |
| **Notes** | Any additional observations that may help explain the data, such as unusual traffic conditions, road closures, fare negotiations, seasonal events, or other relevant information. |

## Standardized Values

To maintain consistency across the collaborative dataset, participants should use the following standardized values where applicable.

### Route_Type

- **Direct** – The commuter travels from the starting point to the destination without changing vehicles.
- **Multi-Stops** – The commuter changes vehicles one or more times before reaching the final destination.

### Source_Type

Examples include:

- Driver
- Conductor
- Regular Commuter
- Transport Union Representative

### Transport_Type

Examples include:

- Bus
- Taxi
- Tricycle
- Motorcycle
- Boat

Additional transport types may be recorded if they are commonly used within a participant's city.