# Flightscry ✈️

Proof of concept UI for Flightscry, built for the Skyscanner Software Engineering job simulation (Task 3).

The app shows a sample flight itinerary using Skyscanner's Backpack Android UI library (`backpack-android:43.0.0`):

- **Flight information card** with the flight number
- **Departure card** with the airport code (LHR) and departure time
- **Arrival card** with the airport code (BOM) and arrival time

The layout lives in `app/src/main/res/layout/activity_main.xml` and uses `BpkCardView` (large corners) and `BpkText` components inside a `ConstraintLayout`.

Built with Kotlin, minimum SDK API 33 (Android 13, Tiramisu).
