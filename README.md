#
# Discord Bot SheetBot Project



## Description

This project consists of a Discord bot utilizing libraries such as `nextcord`, `gspread`, and `persiantools` to provide functionalities for managing information in Google Sheets. Please note that the original code is kept in a private repository, and this repository is for demonstration purposes only.

## Dependencies

To run this project, you need to install the following libraries:

- nextcord
- gspread
- oauth2client
- persiantools
- pytz
- asyncio

## Installation and Execution Guide

1. Clone the repository:

```bash
git clone https://github.com/Abbas-Ghazavi/SheetBot.git
```
#

## Adding Data (/add Command)
The /add command allows users to add information to the Google Sheets. Users can use this command followed by the entry text to add data. For example:

``` /add Your entry text here ```

By using this command, the bot will append the provided entry to the Google Sheets, along with additional information such as the user's name, date, and time.

https://github.com/Abbas-Ghazavi/SheetBot/assets/118556497/23da3963-9ef9-4b09-9846-d35f19de5709
#

# Viewing Data ( /get Command )
The /get command enables users to retrieve registered information from the Google Sheets and display it in a paginated format within Discord. This command provides an easy way for users to view the stored data without accessing the Google Sheets directly.

``` /get ```

Executing this command will display the stored information in a paginated format, making it easy for users to navigate through the data.



https://github.com/Abbas-Ghazavi/SheetBot/assets/118556497/e5044dba-0749-49aa-97d7-fdd7fadadf03

#
## Deleting Entries (/delete Command)

Using these commands, users can efficiently manage and update the information stored in the Google Sheets.

``` /delete message_id ```


https://github.com/Abbas-Ghazavi/SheetBot/assets/118556497/928d85d8-3dd2-41aa-857a-544c4f3c128f

#

## Editing Entries (/edit Command)

The `/edit` command allows users to modify existing entries in the Google Sheets. Users need to specify the message ID of the entry they want to edit, followed by the new text. Once executed, the bot will locate the entry with the provided message ID in the Google Sheets and update it with the new text. This command is useful for users who need to make corrections or updates to their previously submitted information.

``` /edit essage_id replace text ```

https://github.com/Abbas-Ghazavi/SheetBot/assets/118556497/cecd14f2-ec97-40c2-8c41-04b8548ebfb8

#
## Searching Data (/search Command)

The /search command enables users to search for specific information within the Google Sheets based on a query. This command retrieves matching entries and displays them in a paginated format, making it easy for users to find relevant information.



``` /search query ```



https://github.com/Abbas-Ghazavi/SheetBot/assets/118556497/027c94c3-4476-47a4-b8e9-cdc09651afd5
#


