# TweetExtractor

## Overview

**TweetExtractor** is a .NET-based GUI application designed to extract detailed information from Twitter profiles and tweets. It aims to provide users with comprehensive insights and media related to Twitter accounts and their posts.

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
  - Total Tweets Liked by the User Count
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
  - Tweeted By (Username)
  - Profile Picture (Click to download)
  - Verification Ticks (Blue, Grey, Gold)
    - Click on tick to get details about verification status.
  - Affiliated Logo (if available) with user ID (clickable for user details).

- **Media Downloads:**
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
1. Download the latest release of **TweetExtractor** from the [releases page](https://github.com/yourusername/TweetExtractor/releases). Note that the release binary is protected by obfuscation for enhanced security.

### Install the .NET Framework
2. Ensure that .NET Framework 4.7.2 or above is installed on your system. You can download it from the official [Microsoft website](https://dotnet.microsoft.com/download/dotnet-framework).

### Run the Application
3. If you downloaded the release, simply run the `TweetExtractor.exe` file.

## Using the Application
- Enter the profile or tweet URL to get the desired details.

## Contact
For any questions or support, please open an issue on the GitHub repository or contact me directly at [contact@narendradwivedi.org](mailto:contact@narendradwivedi.org).

> **Note:** This application is intended for educational purposes only. Please respect Twitter's terms of service when using this tool.
