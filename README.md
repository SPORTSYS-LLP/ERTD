# SPORTSYSTEMS ERTD Files
These ERTD files are to be used with our Scoreboard Writer and Points ERTD applications to send data to Daktronics DMP-8000 systems and Daktronics GalaxyPro boards with an ethernet connection.
## Scoreboard Writer
### Windows 10/11 64-bit
https://get.sportsys.co.uk/ScoreboardWriter/Win64
### MacOS 10.12+ 64-bit/M1
https://get.sportsys.co.uk/ScoreboardWriter/MacOS
## Points ERTD
### Windows 10/11 64-bit
https://get.sportsys.co.uk/PointsERTD/Win64
### MacOS 10.12+ 64-bit/M1
https://get.sportsys.co.uk/PointsERTD/MacOS
## Daktronics Show Control
To use the SPORTSYSTEMS ERTD with Show Control you need to configure a new profile in the Profile Editor if not already present.\
\
You will need to repeat steps two, three and four for each of the SPORTSYSTEMS ITF files you are using.
### Step One
Add a new Profile with the name SPORTSYSTEMS in the Manage Profiles section.
### Step Two
Import the SPORTSYSTEMS ITF file by clicking Import ITF in the Manage DID Files section under Manage Inputs and DIDs
### Step Three
Add a new Data Input in the Manage Data Inputs section under Manage Inputs and DIDs.
#### Scoreboard
Name: SPORTSYSTEMS Scoreboard\
DSRC: SSScoreboard.dsrc
#### Points
Name: SPORTSYSTEMS Points\
DSRC: SSPoints.dsrc
#### Relay Challange
Name: SPORTSYSTEMS Relay Challange\
DSRC: SSRelayChallange.dsrc
#### Top Swimmers
Name: SPORTSYSTEMS Top Swimmers\
DSRC: SSTopSwimmers.dsrc
### Step Four
Add a new Available Data Sources (Pair) under Manage Profiles.
#### Scoreboard
Input: SPORTSYSTEMS Scoreboard\
DID: SSScoreboard
#### Points
Input: SPORTSYSTEMS Points\
DID: SSPoints
#### Relay Challange
Input: SPORTSYSTEMS Relay Challange\
DID: SSRelayChallange
#### Top Swimmers
Input: SPORTSYSTEMS Top Swimmers\
DID: SSTopSwimmers
### Step Five
Save Changes\
\
The profiles will now be available in Content Studio
