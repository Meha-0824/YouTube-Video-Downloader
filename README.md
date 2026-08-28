# YouTube-Video-Downloader

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MEHA JABEEN A M

**INTERN ID**: CITS7879 

**DOMAIN**: PYTHON PROGRAMMING 

**DURATION**: 4 WEEKS



## DESCRIPTION

The YouTube Video Downloader is a Python-based desktop application developed using Tkinter to provide a simple and interactive graphical interface for downloading YouTube videos that the user is authorized to download. The application allows users to enter a YouTube URL, retrieve video information, select an available video quality, choose a destination folder, and download the selected video.

The application uses Python's Tkinter library to create the graphical user interface and PytubeFix to retrieve video information and downloadable streams. A progress bar is included to provide visual feedback during the download process. Exception handling is implemented to manage invalid URLs, unavailable streams, incorrect input, and download-related errors.

This project demonstrates practical implementation of Python GUI programming, external library integration, file handling, event-driven programming, user input validation, exception handling, and download progress tracking.


## KEY FEATURES

- **YouTube URL Input** – Allows users to enter a YouTube video URL.
- **Video Information** – Displays the video title, channel name, and duration.
- **Quality Selection** – Allows the user to select from available progressive MP4 video qualities.
- **Download Location** – Allows users to select the folder where the video should be saved.
- **Download Progress** – Displays the progress of the video download using a progress bar.
- **Error Handling** – Provides user-friendly messages for invalid URLs and download errors.
- **Clear Function** – Allows users to reset the application and enter another video.
- **Graphical User Interface** – Provides a simple and easy-to-use Tkinter interface.


## TECHNOLOGIES USED

- Python
- Tkinter
- PytubeFix
- OS Module
- File Dialog
- MessageBox


## PROJECT SCOPE

The project focuses on developing a user-friendly desktop utility for downloading permitted YouTube video content. It demonstrates how Python can integrate a graphical user interface with an external library to retrieve video information and manage downloadable streams.

The application is designed primarily for educational purposes and demonstrates important programming concepts such as GUI development, event handling, exception management, file storage, and external API/library integration.


## APPLICATION WORKFLOW

1. The user launches the YouTube Video Downloader application.
2. The user enters a valid YouTube video URL.
3. The application retrieves and displays the video title, channel, and duration.
4. Available progressive MP4 video qualities are displayed.
5. The user selects the required video quality.
6. The user selects a destination folder using the Browse option.
7. The user clicks the Download Video button.
8. The application downloads the selected video to the chosen location.
9. A progress bar displays the download status.
10. A confirmation message is displayed after successful completion.


## OUTPUT

The completed application provides a functional graphical interface for retrieving YouTube video information and downloading an available progressive MP4 stream.
### Main Output

<img width="1402" height="1122" alt="ChatGPT Image Aug 28, 2026, 08_34_15 PM" src="https://github.com/user-attachments/assets/dc71e929-1488-49b9-96d7-3e413c3e0767" />

The application displays:

- YouTube video title
- Channel name
- Video duration
- Available video qualities
- Selected save location
- Download progress percentage
- Download completion message

### SAMPLE OUTPUT

```text
------------------------------------------------------------
              YOUTUBE VIDEO DOWNLOADER
------------------------------------------------------------

YouTube URL:
https://www.youtube.com/...

Video Information

Title      : Sample Educational Video
Channel    : Sample Channel
Duration   : 12:45

Select Quality:
[720p - video/mp4]

Save Location:
C:\Users\User\Downloads

Download Progress:
████████████████████████████ 100%

Download Complete!
------------------------------------------------------------
