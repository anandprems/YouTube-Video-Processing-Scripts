# YouTube Video Processing Scripts - pytube library

**1. Download YouTube Video**
This Python script uses the pytube library to download a YouTube video in the highest resolution. Users are prompted to enter a YouTube video URL, and the script saves the video to a specified download path.

Usage:
1. Install pytube using pip install pytube.
2. Replace the link variable with the desired YouTube video URL.
3. Run the script to download the video.
Note: Ensure an active internet connection and provide the correct download path.

**2. Extract Audio from YouTube Video**
This script demonstrates how to extract audio from a YouTube video using pytube. It specifies a YouTube video URL, creates a YouTube object, filters for the highest quality audio stream, and then downloads the audio stream to a specified output path with a specified filename.

Usage:
1. Install pytube using pip install pytube.
2. Replace the video_url, output_path, and filename variables as needed.
3. Run the script to extract audio from the specified YouTube video.

**3. Download YouTube Playlist**
This Python script downloads all videos from a YouTube playlist using the pytube library. It iterates over the videos in the playlist, creates a YouTube object for each video, and downloads the highest resolution stream for each video to the specified output path.

Usage:
1. Install pytube using pip install pytube.
2. Replace the playlist_url and output_path variables with the desired YouTube playlist URL and download path.
3. Run the script to download all videos from the specified playlist.

**4. Extract Details from YouTube Video**
This script fetches details from a YouTube video such as title, duration, views, and publish date using the pytube library. Users need to provide a YouTube video URL, and the script prints the extracted information.

Usage:
1. Install pytube using pip install pytube.
2. Replace the video_url variable with the desired YouTube video URL.
3. Run the script to print details of the specified YouTube video.
