**Users should be able to**

- Login
- Forgot Password
- Reset Password
- Search Routes
- Wishlist Routes
- See ROTW
- File PIREPS
- Use ACARS to file PIREPS
- See profile of others
- See leaderboards
- News and Events
- Ranking system
============================== Account =====================

Login: 
- To use a simple username and hashed password

First Login
- CHR to generate an OTP to be used by the user, who can set the password to the website using this OTP

Forgot Password:
- Create a one time password which is stored in db
- fetch the one time password with a command to the bot from the database
- Use one time password to create a new password

Reset Password:
- one time password to be fetched from discord
- Use the one time password to reset account password

Update User:
- Simple PUT call with ability to alter all fields except password

-----------

======================== Routes ====================================

Find routes:
- Filter with all possible choices

Suggest route:
- Ability to suggest route to route managers, should accept flight radar 24 link


-------------

===================== File PIREPS =========================

Instructions to file with the discord bot
- Have videos or documentation containing instructions to file with the discord bot

Logbook viewer:
- Fetch the logbook with the option for user to choose the route
- Maybe autofile flight modes and stuff ???!!!!
- when pilots choose a flight mode, the rest should be filtered accordingly
- if they enter the route directly, all other fields should be filled
- multipliers should be automatically calculated
