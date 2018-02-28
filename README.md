Ever get lost and think "Gee, wish there was some way to indicate where my base is"? Well that's what this plugin does.

## Notes
Please note: This plugin temporarily grants players administrative flags which is needed to display the draws in game. If a player is not an admin they are not able to display these draws normally, but this plugin uses a work around to make this possible. (these administrative permissions are added and removed almost instantly, so there shouldn't be any issues with this afaik)

## Permissions
- `personalbeacon.use` -- players with this permission can use the normal commands
- `personalbeacon.admin` -- players with this permissions can use the admin commands

## Commands
- **/setwp \<name\>** -- sets a beacon for the player
- **/wp \<name\>** -- allows the player to view this waypoint
- **/wplist** -- shows the player all of their waypoints
- **/removewp \<name\>** -- allows the players to remove a certain waypoint from their list
- **/wphelp** -- displays basic help text regarding how to use the commands listed above

## Admin Commands
- **/setglobalwp** -- sets a global waypoint which is visible to everyone
- **/hideglobalwp** -- temporarily disabled a global waypoint
- **/showglobalwp** -- shows a global waypoint that is hidden
- **/wpshowall** -- shows all current waypoints to the user

## Configuration File
```json
{
  "Arrow Settings": {
    "Arrow Head Size": 3.0,
    "Height": 100.0,
    "Levitation from ground": 3.0
  },
  "Settings": {
    "Global Waypoint Refresh Time": 60.0,
    "Max Waypoints": 5,
    "Player Display Time": 60.0
  }
}
```
