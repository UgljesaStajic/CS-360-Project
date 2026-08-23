# MakerStock

MakerStock is an Android inventory app I created for CS 360. I based the idea on my own robotics and 3D-printing hobby, where I constantly need to keep track of small parts, quantities, and where they are stored.

## App Features

- User login and account creation
- SQLite database with persistent inventory
- Add, edit, delete, and view inventory items
- Separate inventory for each user
- Optional SMS alerts when stock reaches zero
- App continues working if SMS permission is denied

## Project Reflection

I kept the UI simple with login, inventory, and SMS settings screens so the main functions are easy to reach.

When coding the app, I worked feature by feature and tested each part as I went. Testing helped me find issues I would not have noticed just by looking at the code, especially with SMS permissions and switching between different accounts.

One challenge was making SMS settings work correctly for individual users even though Android permission is shared across the whole app. I also improved the flow so after saving SMS settings, the app confirms it and automatically returns to the inventory screen.

I think the strongest part of the project was connecting the login system with the SQLite database so every user has their own persistent inventory. Since the original idea came from something I actually do outside of class, I would like to continue improving MakerStock and use it for my own projects.
