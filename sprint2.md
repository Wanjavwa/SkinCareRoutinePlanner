Sprint 2 Tasks (Week 9)

1. Build the Add Routine Form
The Add Routine screen should allow users to:
Enter product name (TextField)
Choose Morning or Evening (Toggle or segmented picker)
Select the days of the week (buttons or checkboxes)


2. Save Routines Locally (UserDefaults)
Implement saving with Codable:
Convert the [RoutineItem] list to JSON
Save to UserDefaults under "routines"
Load routines when the app launches


3. Display Routines on the Home Screen
On the Home screen:
Show routines scheduled for today
Split into "Morning" and "Evening" sections
Example:
Morning
- Cleanser
- Vitamin C

Evening
- Retinol
- Moisturizer


4. Edit Routine Items
Allow the user to tap a routine item and:
Update its name
Change the selected days
Toggle morning/evening
Save changes



❌ 5. Delete Routine Items
Add a way to remove a routine:
Swipe to delete
Or an Edit button
Or a Delete button inside the edit screen
Saving after deletion is required.

✔️ 6. Refresh UI After Add/Edit/Delete
Make sure changes update Home and Calendar automatically.
