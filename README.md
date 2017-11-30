# Java-Desktop-RuneScape_NXT_BuildNumber
**Basic Description**:
This program takes the internal build number in a directory path's string inside `rs2client.exe` and adds it to the clipboard in some format options.

This value is NXT's in-house build number separate from the Build Number we, as players, would see. An easy way to think about it is this value is how many updates that NXT has had since it was first created. The more the number grows between updates, the more internal revisions that has happened in NXT.
- - - -
**Current Features**:
* Grabs the Internal build number from `rs2client.exe`
* Formats to some chat formats that I use personally.
  * As-is; Or as it is in the client.
  * Reddit-format; or \`this\` to highlight it slightly in a inline codeblock.
  * Discord-format; or \`\`\`this\`\`\` for a codeblock on a new line.
* Nothing else, really.
- - - -
**TO-DO**:
* Linux/Mac path support. (Assuming the path is still in the binary file used)
