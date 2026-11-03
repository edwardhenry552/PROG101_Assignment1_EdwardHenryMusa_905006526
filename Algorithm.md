Algorithm: Flood Early Warning Alert System

1. Start.
2. Define the constants RAIN_LIMIT = 50, RIVER_WARNING = 3.5 and RIVER_DANGER = 5.0.
3. Input the location, rainfall and river level.
4. Validate the readings. If either reading is negative, display "Invalid reading" and return to step 3.
5. Calculate the risk level (Low, Medium or High) using the thresholds.
6. If the risk level is Low, display "No alert needed" and go to step 9.
7. Generate the alert message for the location and risk level.
8. For each registered contact in the location, send the alert message by SMS.
9. Record the location, risk level and time in the log.
10. Ask whether another location should be checked. If yes, return to step 3.
11. End.
