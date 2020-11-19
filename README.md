# campaign-tracker
A Gatsby web app that helps the leader of a campaign track and display their team's campaign progress.
# Features
1. Google Sheets CMS to allow the leader to easily customise:
  a. Characters: stat block, description, imageurl
  b. Maps: name, image, pin locations [], imageurl
  b1. locations: name, types, parent location, description, imageurl
  c. NPCs: name, description, stat block?, imageurl
  d. Monsters: name, description, known loot drops id, imageurl
  e. Items: id, name, type, number on hand, effects, imageurl, isViewable
  f. Shops: shop name, item for sale, cost, weight, description, imageur
  h. Quests: type, name, requested by, where, when, reward, description, guild provisions, parent quest, isCompleted
  i. Rumours: characters of interest, text
  k. Journal: date, entry
  l. Polls: date, questions, url to Google Survey
  m. Organisations: name, type, parent org, location, members,
2. Homepage with critical information for the next session 
  a. Current level
  b. Details for next session
  c. Most important page to link to
3. Custom Maps with hoverable pins (React Leaflet)
4. Calendar so users can quickly inspect when the planned sessions are
5. Push notifications sent out when leader makes changes to homepage or polls

Other ideas:
1. Authentication for users and leader.
2. Track user money and auto calculate shop purchases and sales.
3. Roll20 API integration for items in backpack

Product Ideas:
1. Turn this into a product that can host campaigns for any user. May need to change the way Gatsby pulls information from Google Sheets though
