# Team 12 CourtSort: Product Backlog

# Team
**Members:** Aahan Aggarwal, Carlo Cirrincione, William Eiffert, Karl Gaertner, Daniel Kambich, and Tyler Ruth.
**Project Coordinator:** Lakshay Kharbanda

# Problem Statement
One of the staples of college life is the dining courts, yet choosing a dining court remains a hard decision. Existing platforms include Purdue’s official dining app, which provides basic menu items and nutritional information, and review platforms such as Google Maps and Yelp, which are unintegrated into the dining court system, meaning they do not provide a rating for each dish. CourtSort seeks to enhance the dining court experience by providing real-time dish ratings, intelligently predicting what dining court is best suited for your social circles, and allowing users to report equipment malfunctions, long lines, and lack of available seating. Ultimately, by collecting information from each user we aim to create a smarter dining court application that learns from the user and provides suggestions that make for a happier Boilermaker.

# Background Information
## Problem/Domain
At large universities, dining courts feed a large portion of the student population. They are locations where food of varying quality combine with large amounts of people. Although Purdue Dining maintains an app to inform eaters what is on the menu, it is inadequate to make an informed decision about the ideal location to eat at. Long lines, equipment malfunctions, and lack of available seating make eating at a court less than satisfactory, and with multiple dining locations, many people eat alone despite the public setting due to friend dispersion and lack of active communication to meet with friends while eating. By implementing not only personal food preferences and restrictions, but also ratings, malfunction warnings, and friend availability, a centralized interface can improve the dining court experience.

## Targeted users
Other food reviewing apps such as Yelp and Google Maps appeal to a broad audience and there are only ratings for establishments/restaurants, not for specific dishes. CourtSort seeks to have ratings for specific menu items and intelligent food recommendations for an individual or group. Therefore, the targeted audience for CourtSort is Purdue students and faculty who regularly eat at Purdue Dining courts, with a focus on students who enjoy eating meals in groups. 

## Limitations
The biggest limitation is that users will need to take an active role in using the application (for instance, ratings will not be accurate unless many people rate the dishes, users will not receive malfunction warnings unless other users report them, group suggestions and other social features rely on friends using the app, etc.). To combat this, we will provide relevant information about dining courts, dishes, equipment malfunctions, etc. in an easy to use format that makes it quick and simple so as not to become a burden. In addition, we will provide useful features for groups and individual users paired with notifications to help urge people to launch the app and contribute to the crowd-sourcing.

## Similar Applications
Purdue Dining does provide an app which allows students to see the hours, menu, nutritional information, and set dietary restrictions and preferences. However, these are organized by location which makes the interface unintuitive for making dining court comparisons. Additionally, other factors that impact the dining experience such as quality of food, wait times, friend locations, and warnings are unaccounted for.

Yelp, Google Maps, and other reviewing services provide ways to rate restaurants, leave comments, and view public opinion about establishments. However, those ratings are for the restaurant as a whole, not the variety of individual dishes and cuisine that are available in a given location. Moreover, those applications have a broad audience as opposed to CourtSort, which is tailored specifically for Purdue Dining courts.  In addition, CourtSort will provide an integrated social and predictive aspect to the dining experience that is lacking from other third party applications.

Eat Out is a service that helps groups of people decide on where to eat. Albeit hard to find, the app’s website is eatout.trofi.io and is in testing. It incorporates Yelp reviews and personal preferences such as distance and price into a voting system. Then, it helps decide the best location. Nevertheless, it applies to whole restaurantes and not individual dishes. Each dining court contains a wide variety of meals, and more integration is needed. Additionally, it is an active platform in that a precondition is establishing a group to eat out with at a particular time. CourtSort will have this functionality, but will help increase the number passive, impromptu meetings.

# Requirements
## Functional 
The following apply to Purdue dining courts unless stated otherwise. Purdue Campus Dining Locations includes dining courts, cafes, markets, restaurants, and food truck.

User stories for a guest user who has not set up an account:
1. [ ] As a guest, I would like to view Purdue campus dining locations. The food truck current location will be included if time is available.
2. [ ] As a guest, I would like to view Purdue campus dining locations’ operating hours.
3. [ ] As a guest, I would like to view Purdue campus dining locations’ menus.
4. [ ] As a guest, I would like to view Purdue campus dining locations’ meal swipe policy.
5. [ ] As a guest, I would like to view nutritional information for each dining court menu item.
6. [ ] As a guest, I would like to view where and when specific dining court dishes are being served at each dining court. 
7. [ ] As a guest, I would like to view each dining court’s public rating.
8. [ ] As a guest, I would like to view a given dining court dish’s public rating.
9. [ ] As a guest, I would like to view how busy a dining court is.
10. [ ] As a guest, I would like to view a map of the layout of each dining court. (if time allows).

User stories for a user who has set up an account:


11. [ ] As a user, I would like to create an account.
12. [ ] As a user, I would like to sign into my account.
13. [ ] As a user, I would like to have the option to use a third party provider such as Google or Facebook for account authentication.
14. [ ] As a user, I would like to reset my password for my account so that in the case my account is created with a unique email password combination rather than a third party provider, I can regain access.
15. [ ] As a user, I would like to use two factor authentication for increased security (if time allows).
16. [ ] As a user, I would like to delete my account.
17. [ ] As a user, I would like to sync my information across devices so that information such as food preferences, group, and ratings can be linked with account and not stored locally on the device.
18. [ ] As a user, I would like to save dish preferences with a numerical rating so that food recommendations consider what I like.
19. [ ] As a user, I would like to view my dish preferences.
20. [ ] As a user, I would like to save cuisine preferences, such as American, Italian, Asian, and so forth, with a numerical rating so that food recommendations consider whole food groups in addition to individual items.
21. [ ] As a user, I would like to view my cuisine preferences.
22. [ ] As a user, I would like to save dietary restrictions so that food recommendations consider what I cannot eat.
23. [ ] As a user, I would like to view my dietary restrictions.
24. [ ] As a user, I would like to view approximately how much time I spend in which dining courts.
25. [ ] As a user, I would like to receive predictions of where to eat considering my food preferences and dietary restrictions.
26. [ ] As a user, I would like to receive timed notifications of these predictions based on my daily eating times.
27. [ ] As a user, I would like to rate dining courts with a numerical rating.
28. [ ] As a user, I would like to rate various dishes from the dining courts with a numerical rating.
29. [ ] As a user, I would like to report malfunctions of equipment.
30. [ ] As a user, I would like to view how busy a dining court is so that I can judge how many seats are available.
31. [ ] As a user, I would like to submit a report on how busy a dining court is so that I can help others determine if there are enough seats available.
32. [ ] As a user, I would like to provide textual feedback to dishes so that my opinions of the food can be better represented rather than just in the form of a numerical rating. (if time allows).
33. [ ] As a user, I would like to report inconsistencies with the menu as opposed to what is actually being served so that others can make a more informed decision of where to eat.
34. [ ] As a user, I would like to share my user information so that I can meet with friends in a mutually desired dining court.
35. [ ] As a user, I would like to notify others of meal swipe pop-ups since there is no available API for meal swipe pop-ups. (if time allows).
36. [ ] As a user, I would like to search usernames so that I can send connect requests.
37. [ ] As a user, I would like to confirm or deny friend connection requests.
38. [ ] As a user, I would like to unconnect with a friend.
39. [ ] As a user, I would like to view who I am connected with.m
40. [ ] As a user, I would like to block a user.
41. [ ] As a user, I would like to check into a dining court and set a passive status for my friends so that they know they are welcome to join me or if I am busy.
42. [ ] As a user, I would like to change my status.
43. [ ] As a user, I would like receive reminders to check in when I have entered a dining court.
44. [ ] As a user, I would like my status to auto revert to a “not at dining court” status when I leave a dining court.
45. [ ] As a user, I would like to enable or disable location tracking.
46. [ ] As a user, I would like to view my friends status and dining court location so that I can join them if they are available.
47. [ ] As a user, I would like to be able to actively invite friends to eat with me.
48. [ ] As a user, I would like to actively request to join a friend who is currently eating.
49. [ ] As a user, I would like to actively respond to invitations so that my friends can know if I will dine with them or not.
50. [ ] As a user, I would like to receive responses to invitations so that I can know if my friends are able to dine with me or not.
51. [ ] As a user, I would like to use prewritten 1-click responses so that responding is hassle-free and simple.
52. [ ] As a user, I would like to receive predictions of where to eat that take friend connections into account.
53. [ ] As a user, I would like to receive notifications if a friend checks into the dining court I am eating at.
54. [ ] As a user, I would like to join a group so that I can share relevant information collectively.
55. [ ] As a user, I would like to invite friends to join a group.
56. [ ] As a user, I would like to leave a group.
57. [ ] As a user, I would like to view which groups I am a part of so that I can choose which groups to share information with.

User stories for a user acting in a group:


58. [ ] As a group, we would like to view what dining court fits our preferences.
59. [ ] As a group, we would like to view what time best fits for eating habits.
60. [ ] As a group, we would like to vote on a dining court.
61. [ ] As a group, we would like to vote on a time to eat.
62. [ ] As a group, we would like to give our group a custom name.
63. [ ] As a group, we would like to be able to set preferences for times and days when the group usually meets for meals.
64. [ ] As a group, we would like to schedule meals based on time and day preferences on our calendar automatically (if time allows).
65. [ ] As a group, we would like to be notified when a meal event starts.
66. [ ] As a group, we would like to share meal events with a selection of friends of each group member.
67. [ ] As a group, we would like to export meal events to third party calendars such as Google Calendar, Outlook, and iCalendar (if time allows).

User stories for a user who is dining court staff:


68. [ ] As dining court staff, I would like to push warnings such as equipment malfunctions or long lines to users (if time allows).

## Nonfunctional
### Performance
Dining court recommendations should be displayed whenever the user requests and will update within 5 seconds. Menu information will be requested once, server side, every 24 hours so the Purdue Dining API is not bombarded by requests and so we are not relying on their API for quick response times. Our own server will distribute menu information to the user when opening the menu section within 5 seconds under optimal network conditions.

We expect the maximum number of users requesting dining recommendations or menus simultaneously at worst case to be approximately 16,000 people, which is approximately the number of students who live on campus with a meal plan which is 40% of  Purdue’s 40,000 student population. Firebase provides up to 100,000 simultaneous database connections which is more than adequate.

When updating user food preferences or other information, the changes will be saved to local storage and will asynchronously update with Firebase. A copy of user information will be saved locally to allow quick viewing of user preferences within 500ms.

When interacting with groups, sending and receiving ‘messages’ will have up to 3 seconds of server delay. When a user joins or leaves a group, the server will update the group information and push the changes to the other users in the group in up to 5 seconds.

### Security
The back-end will consist of a Firebase Realtime Database along with Firebase Authentication to handle user logins. Both technologies are certified by Google to be secure and reliable ensuring that user data cannot be compromised by a third party. In addition, no data will be collected on a user while they are not logged in. Once a user signs into their account they can choose whether to share location data or dietary restriction data. Finally, all ratings and reports from the user will be anonymous (except to friends) and stored in the secure database.

### Usability
The application shall feature a React Native user interface. This allows front end source code to work with iOS greater than iOS 9.0 and Android greater than 4.1, regardless of screen size or resolution. 
The interface will put more important, quick-reference information such as dish ratings and dining court suggestions up front and easily accessible. More intensive functionality such as groups, dining court operating hours, and complete menus will be neatly organized and tucked away so as not to clutter the view.

### Hosting
We will use Firebase to host the back-end and database of all user and group information. The Purdue menus will be periodically updated to the database, along with all ratings on a per dish basis. The front-end will be created using React Native and it will be separate from the Firebase back-end. The back-end will handle most operations such as the food recommendations, notifications, authentication, and group features.
