# Microsoft Teams - Teams Meeting Buffer Time
Want some time to breathe after your back to back meetings?

## General
This Power Automate flow doesn't end meetings early like the [standard feature of Outlook](https://support.microsoft.com/en-us/office/schedule-a-meeting-with-other-people-5c9877bc-ab91-4a7c-99fb-b0b68d7ea94f). The solution will automatically create a new appointment in your Office 365 calendar with the desired duration after eacht Microsoft Teams meeting.
Now you have time to make some coffee.

_The flow will only be triggerd for Microsoft Teams meetings._

## Connections in use
* Office 365 Outlook

## Setup
1. Please download the [MicrosoftTeamsMeetingBufferTime.zip](/../../raw/main/MicrosoftTeamsMeetingBufferTime.zip).
2. Go to https://emea.flow.microsoft.com/manage/flows/import.
3. Upload and import the `MicrosoftTeamsMeetingBufferTime.zip` file. [Extra help for importing Power Automate projects](/../../../MrAutomate33/blob/main/files/CreateConnectionsInImport.md).
4. Open the Power Automate flow and change the calendar id to the desired calendar (needs to be done in 2 locations).
5. Set your desired buffer time in `Buffer duration`.
6. Save.
7. Don't forget to turn on the Power automate flow.

## Disclaimer
*This code is provided as is without warranty of any kind, either express or implied, including any implied warranties of fitness for a particular purpose, merchantability, or non-infringement.*
