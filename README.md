# Quran Reading Tracker
# [Live Demo](https://that1parrot.github.io/QR/)
A web-based Quran reading tracker designed to help you manage and monitor your progress in reading and completing Surahs. This tool allows users to mark Surahs as completed, export progress in CSV format, and import progress from a CSV file to sync across multiple devices.

## Features

- **Track Reading Progress**: Mark Surahs as read, and see your reading progress at a glance.
- **Bookmark Ayahs**: Save and access your favorite Ayahs quickly.
- **CSV Export/Import**: Export your progress to a CSV file and import it on another device to continue tracking.
- **Login and Signup UI**: Basic authentication setup (optional) for future use with backend solutions.

## Usage

### Main Features

1. **Marking Surahs as Completed**
   - Click on any Surah to view its Ayahs and mark it as completed once read.
   - Your progress is automatically saved to `localStorage`.

2. **Exporting Progress to CSV**
   - Use the "Export Progress" button to download a CSV file containing only the Surahs you've marked as read.
   - This CSV file can be shared between devices to sync progress.

3. **Importing Progress from CSV**
   - Use the "Import Progress" button to upload a CSV file.
   - Only Surahs marked as read in the CSV file will be added to your current progress without overwriting other completed Surahs.
