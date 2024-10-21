# General Settings

(1)

SETTINGS

\*\*Pin-code Size: \*\* Allows customization of the auto-generated PIN code length, ranging from 4 to 20 digits. The system sends this PIN code in personal invitation letters.

**Clear Visits, Visitors Data, and Visit Log (Days):** Initiates a daily procedure to permanently delete visit logs where the current date exceeds a specified number of days (\[Visit.EndDate + \[number of days, 180d]]). This ensures data remains relevant and uncluttered.

(2)

AUTO-CHECKOUT

**Checkout Time:** Possible to choose between options:

1. Choose Exact Time: Allows selection of a specific time (Time in UTC+0) for auto-checkout.
2. Define Hours After Visit End: Enables defining the number of hours after the visit ends when the system will automatically check out visitors.

**Show Visitors Names In The Visit Preview:** When enabled, the system displays all visitor names associated with each visit within the "Visits" tab table, enhancing visit preview information.

![](https://lh5.googleusercontent.com/MRjSWYeGOYwMuQjLMu9GqxNv0YOVKo9wnuI9Ka7VPwNApfFBDb3-mpwxGQ36PUYeLeZaVt9bNYczqx-q0uXlDLFNweauonP7beH-Od7Y46TTDl6AbDlwVNoNB9indmdFobV6qfThCJ0kWiRWcd0BAKI)

**Hide Self-Registered Visitors:** The system hides self-registred visits in the tab "Visits" and hides visitors in the "Visitors" tab who have previously completed self-registration.

:::hint{type="info"} You also can quickly hide or show self-registered users using Column-Based Filters.

&#x20;:::

(3)

CHECK-IN RESTRICTIONS

**Before Start of Visit (h):** Sets a time slot before the visit start during which visitors can initiate the check-in process (e.g., 3 hours before the visit). If empty, visitors can check in only from the visit’s start date and time.

**After End of Visit (h):** Defines a time slot after the visit's end during which visitors can start the check-in process (e.g., 3 hours after the visit concludes). If empty, visitors can check in only before the visit’s finish date and time.

:::hint{type="info"} **Default Behavior:** By default, visitors are only able to check in during visits with the status "Running." :::
