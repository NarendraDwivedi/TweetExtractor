# TweetExtractor

## Overview

**TweetExtractor** is a professional .NET-based GUI application designed to extract comprehensive details from Twitter profiles and tweets. This tool offers users insightful information and media related to Twitter accounts, enhancing the way you interact with Twitter data.

## Features

### Profile Extraction
- **Extracted Information:**
  - Name
  - Username
  - Bio
  - Location (if available)
  - URL (if available)
  - Joining Date on Twitter
  - Birthday (if available)
  - Followers & Following Count
  - Total Tweets Count
  - Total Media Count
  - Total Tweets Liked by the User
  - Pinned Tweet (if available)
  - Profile Picture (if available)
  - Cover Image (if available)
 - Verification Tick (Blue, Grey, Gold)
    - Click on any tick to find out why it's verified and when the account was verified.
  - Affiliated Accounts: Shows logo and details of affiliated accounts.

- **Image Downloads:**
  - Click on the Profile Picture to download in high quality.
  - Click on the Cover Image to download in high quality.

### Tweet Extraction
- **Extracted Information:**
  - Tweet Content
  - Tweeted On (Date)
  - Total Quote Count (if available)
  - Total Views (if available)
  - Total Replies
  - Total Reposts
  - Total Likes
  - Total Bookmarks
  - Tweeted By (Name, Username) - Click To Get That User's Detail
  - Profile Picture (Click to download)
  - Verification Ticks (Blue, Grey, Gold)
    - Click on tick for verification details.
  - Affiliated Logo (if available) with clickable user ID for further details.

 **Media Downloads:**
  - Total Image Count available in that tweet (batch download available).
  - Total Video Count (if available) with an option to add to download.

### Download Features
- **Download List:**
   - Columns: Username, Type (e.g., video), Quality (e.g., 1280x720), Size (File Size in MB), Date (Added to Download List), Filename (double-click to open download folder), Link (double-click to open in VLC or Windows Media Player).
  
  - **Action Buttons:**
    - Download / Open Folder: Opens the downloaded file or initiates a download with progress details (size, speed, progress bar).
    - Pause/Resume features for active downloads.
    - Remove: Removes the file detail from the download list (does not delete the downloaded file).
    
  - Users can batch download multiple files by clicking on multiple download buttons.

## Prerequisites

- **.NET Framework:** Version 4.7.2 or above

## Installation

### Download the Application
1. Download the latest release of **TweetExtractor** from the [Releases page](https://github.com/NarendraDwivedi/TweetExtractor/releases). The release binary is protected by obfuscation for security.

### Install the .NET Framework
2. Ensure that .NET Framework 4.7.2 or above is installed. Download it from the official [Microsoft website](https://dotnet.microsoft.com/download/dotnet-framework).

### Run the Application
3. After downloading, run the `TweetExtractor.exe` file to start using the application.

## Using the Application
- Enter the profile or tweet URL to extract the desired details.

## Screenshots
![TweetExtractor Screenshot](https://github.com/NarendraDwivedi/TweetExtractor/blob/main/tweetextractor.JPG)  
*Example of TweetExtractor in action.*

## Contact
For questions or support, please open an issue on the GitHub repository or contact me directly at [contact@narendradwivedi.org](mailto:contact@narendradwivedi.org).

> **Note:** This application is intended for educational purposes only. Please respect Twitter's terms of service when using this tool.
