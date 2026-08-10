# Data Collection Guide

This guide explains the standard methodology for collecting transportation fare data for the Transportation Cost Analysis Project.

Following a consistent methodology ensures that data collected from different cities can be combined into a reliable collaborative dataset.

---

## 1. Choose Your Destination

Begin by selecting a destination category that is relevant to your city.

Examples include:

- Universities
- Major Markets
- Government Hospitals
- Business Districts

You may choose one or more destinations within your selected category depending on the scope of your project.

---

## 2. Select Residential Areas

Choose **up to 10 residential areas** that provide good coverage across your city.

Each residential area should be represented by a clearly identifiable starting point that commuters commonly use.

Suitable starting points include:

- Registered transport parks
- Well-known bus stops
- Major junctions
- Other recognizable transport landmarks

Avoid using random or difficult-to-identify roadside locations as starting points.

Using clear reference points makes the routes easier to identify, verify, and revisit during future rounds of data collection.

### Registered Transport Parks

Registered transport parks can be particularly useful for residential areas where commuters need to travel a considerable distance to reach the selected destination.

For example, if a university is located far from a residential area, a registered transport park may serve as an important transport hub from which commuters begin or continue their journey.

However, registered transport parks are **not the only acceptable starting points**. A well-known bus stop, junction, or other clearly identifiable location can also be used where it better represents how commuters normally begin their journey.

---

## 3. Planning Your Data Collection

Before collecting any data, spend some time planning your routes.

### Choosing Your Destinations

Select one destination category for your project, such as:

- Universities
- Major Markets
- Government Hospitals
- Business Districts

Within your chosen category, select **2–3 major destinations** that are well known and frequently visited.

### Choosing Residential Areas

For each destination, identify **up to 10 residential areas** across your city.

Each residential area should be represented by a clearly identifiable starting point, such as:

- A registered transport park
- A major bus stop
- A junction
- Another recognizable transport landmark

Using consistent reference points makes the routes easier to identify, verify, and compare across different participants.

### Choosing Routes

For **each residential location or starting point, select one route** to the chosen destination.

Choose the route based on how **common or practical** it is for commuters travelling from that starting point to the destination.

If multiple routes or transportation options are available, do not record all of them. Select the **one route that is most commonly used or most practical** for commuters.

You do not need to personally know the route before starting the project. You can ask students, commuters, drivers, conductors, or other people who regularly use the route.

If the selected route involves multiple stages of transportation, record each stage separately.

You do not need to force your data to reach 10 residential areas or routes. If fewer suitable locations or routes are available, collect the routes that can be reliably identified rather than adding unreliable routes simply to reach a target number.

---

## 4. Recording Transportation Fares

Each route should be recorded one stage at a time.

Every stage of the journey should be entered as a separate row in the Excel template.

For each stage, record:

- Stop Order
- Stop Name
- Transport Type
- Fare Paid (Cost)
- Cumulative Cost

The final stage should show the complete transportation cost from the selected residential area to the destination.

### Direct Route Example

| Stop Order | Stop Name | Transport Type | Cost | Cumulative Cost |
|------------|-----------|----------------|-----:|----------------:|
| 1 | Choba | Bus | ₦700 | ₦700 |

### Route with Transfers Example

| Stop Order | Stop Name | Transport Type | Cost | Cumulative Cost |
|------------|-----------|----------------|-----:|----------------:|
| 1 | Rumuokoro | Bus | ₦200 | ₦200 |
| 2 | Choba | Bus | ₦300 | ₦500 |
| 3 | University | Bus | ₦200 | ₦700 |

The **Total Cost** for the route should equal the cumulative cost recorded at the final stop.

---

## 5. Ensuring Data Quality

To maintain a reliable and consistent dataset, participants should follow these guidelines:

- Record transportation fares as accurately as possible.
- Confirm fare information with drivers, conductors, or regular commuters whenever possible.
- Avoid estimating transportation fares.
- Record data using the project's Excel template.
- Ensure all required fields are completed before submitting your dataset.
- Record the date each route was surveyed.
- Use consistent naming for locations, destinations, and landmarks throughout the project.
- Review your entries for missing values or data entry errors before submission.
- Avoid using difficult-to-identify roadside boarding points simply to increase the number of routes.

Consistency across all participants is essential to ensure that the combined dataset can be analyzed reliably.

---

## 6. Data Collection Tips

Before heading out to collect data:

- Plan the routes you intend to survey.
- Decide on the destinations you will cover before starting.
- Identify suitable starting points for each residential area.
- If available and appropriate, consider using registered transport parks as starting points, particularly where they serve as important transport hubs.
- Carry a printed or digital copy of the Excel template.
- If possible, collect data during similar periods of the day to improve consistency.
- If multiple routes are available from a starting point, select the route most commonly used or most practical for commuters.
- Record only **one selected route per residential location or starting point**.
- Review each completed route before moving on to the next one.

Taking a few minutes to review your data while still on site can help prevent missing information and reduce the need for repeat visits.

### Collecting Route Information

You do not need to personally know every route before beginning your data collection.

You can obtain route information from people who regularly use the routes, including:

- Students
- Regular commuters
- Drivers
- Conductors
- Transport workers
- Other people familiar with the area

For example, if you are collecting data for a university, you can speak with students or other commuters at the university about how they travel from your selected residential areas and what they typically pay.

### Source Type

Record where the transportation fare information was obtained.

Examples include:

- Driver
- Conductor
- Regular Commuter
- Transport Union Representative

This helps improve the transparency and reliability of the dataset.

---

## 7. Before You Submit

Before uploading your completed project to the GitHub repository, review your work to ensure that:

- All planned routes have been surveyed.
- Transportation fares have been recorded accurately.
- Every stage of each journey has been entered into the Excel template.
- Cumulative costs and total route costs have been calculated correctly.
- Missing values have been checked and completed where possible.
- Location and destination names are consistent throughout the dataset.
- The dataset has been reviewed for typing and formatting errors.
- Your dashboard has been completed.
- Your project report is ready for submission.

---

## 8. Understanding the Excel Template

The project template has been designed to ensure that data collected by different participants follows a consistent structure.

The main worksheet is **Transport_Data**, where each row represents one stage of a transportation journey.

Some of the key fields include:

| Column | Description |
|---------|-------------|
| Location | City where the data was collected |
| Start_Point | Clearly identifiable starting point within the selected residential area |
| Destination | Final destination |
| Route_Type | Indicates whether the journey is direct or indirect |
| Stop_Order | Order of each stage in the journey |
| Stop_Name | Name of the stop or transfer point |
| Transport_Type | Type of transport used |
| Cost | Fare paid for that stage |
| Cumulative_Cost | Running total of transportation cost |
| Total_Cost | Total transportation fare for the complete journey |
| NumberOfStops | Total number of stages in the journey |
| Source_Type | Source used to verify the fare |
| Date | Date the data was collected |
| Notes | Additional observations, if any |