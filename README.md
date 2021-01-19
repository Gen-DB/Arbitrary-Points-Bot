# Arbitrary-Points-Bot
Discord bot written with discord.py for the Good Vibes server.

Requirements: Python39 https://www.python.org/downloads/

Instructions:
1. Download and install DB Browser for SQLite at https://sqlitebrowser.org/dl/
2. Open SQLite, select "New Database", and navigate to your bot folder. Name it "pointdata.sqlite".
3. Select "Execute SQL" and paste the following, then click the run button:

    CREATE TABLE "pointdata" (
	    "member"	INTEGER,
	    "points"	INTEGER,
	    "nickname"	INTEGER
    )

4. Click File > Save all. 
5. Open config.json and fill in your bot TOKEN and your desired command role ("Good Vibes Stream Team"). Leave everything else alone.
6. Run the bot.
