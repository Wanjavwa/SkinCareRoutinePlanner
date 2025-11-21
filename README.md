Original App Design Project - README Template
APP_NAME_HERE
Table of Contents
Overview
Product Spec
Wireframes
Schema


Overview
Description

The Skincare Routine Calendar App helps users plan, organize, and stay consistent with their skincare routines. Users can add skincare items to specific days of the week, mark them as morning or evening, and view a calendar that shows what products they need to apply each day. The app is designed for beginners, teens, and anyone who struggles with maintaining a consistent skincare regimen.

App Evaluation
[Evaluation of your app across the following attributes]

Category:
Health / Wellness / Lifestyle
Mobile:
This app is designed for mobile use because skincare routines are often checked on-the-go. Mobile allows:
Quick daily checks
Easy adding/removing of products
Notifications (optional later)
Story:
Users want clearer, more consistent skincare habits. This app provides an organized schedule, reducing confusion and helping users avoid overusing strong products like retinol or exfoliants.
Market:
Teens
New skincare users
People with inconsistent routines
Self-care/lifestyle enthusiasts
This has a broad potential audience, especially with the rising interest in skincare.
Habit:
Users will ideally check the app daily to see what products they need to apply (“To Apply Today”). They may update their routine weekly or monthly.
Scope:
The app is simple and achievable as a capstone project, with all essential features working offline. Stretch features can be added later, but MVP remains manageable.



Product Spec

1. User Stories (Required and Optional)
Required Must-have Stories
User can view today’s skincare routine (morning/evening).
User can add a skincare item to specific days of the week.
User can remove a skincare item.
User can edit a skincare item (name, days, morning/evening).
User can view a calendar showing scheduled skincare routines.
User can tap a day to see “To Apply” items.


...
Optional Nice-to-have Stories

Notifications/reminders ("Time to apply your skincare!").
Dark mode or pastel aesthetic themes.
Streak tracking (consistency counter).
Notes for each skincare item.
Product categories (cleanser/serum/exfoliant).
Export routine to iOS Calendar.
Cute icons representing skincare products.
Profile/settings page with theme changes.




...
2. Screen Archetypes
📆 Home Screen (Daily Routine View)
Shows today’s date
Morning routine section
Evening routine section
“To apply today” list
Required user stories:
View today’s skincare
Tap an item to view/edit
Access Add Routine screen

➕ Add/Edit Routine Screen
Form to enter product name
Select morning/evening
Select days of the week
Add notes (optional)
Required user stories:
Add skincare item
Edit skincare item
Delete item

📅 Calendar Screen
Monthly/weekly layout
Indicators on days with routines
Tap day → shows list of items
Required user stories:
View full routine schedule
See what’s assigned to each day

⚙️ Settings Screen (optional)
Theme toggle
Reset all routines
About app
Optional stories:
Dark mode
Export options
Notification preferences

...



3. Navigation
*Tab Navigation
Your app could use 3 main tabs:
Home → Today’s routine
Calendar → Full monthly view
Add Routine → Add/edit routines

(Optional fourth tab: Settings)


*Flow Navigation

Home Screen
Tap “+” → Add Routine Screen
Tap routine item → Edit Routine Screen
Tap Calendar tab → Calendar Screen

Add Routine Screen
Save → Returns to Home
Cancel → Returns to Home

Calendar Screen
Tap a day → Daily Detail view
Tap item → Edit Routine Screen

Settings (Optional)
From Home → Settings
Back → Home
...

Wireframes

[Add picture of your hand sketched wireframes in this section] 

[BONUS] Digital Wireframes & Mockups
[BONUS] Interactive Prototype

Schema
[This section will be completed in Unit 9]

Models

RoutineItem Model

| Property     | Type     | Description                         |
| ------------ | -------- | ----------------------------------- |
| id           | String   | Unique ID                           |
| name         | String   | Skincare product name               |
| isMorning    | Bool     | Morning or evening                  |
| selectedDays | [String] | Days assigned (e.g., ["Mon","Wed"]) |
| notes        | String?  | Optional notes                      |


Networking
[Add list of network requests by screen ]
[Create basic snippets for each Parse network request]
[OPTIONAL: List endpoints if using existing API such as Yelp]
