# MediaAgent

MediaAgent is a personal, local media library organizer written in Python.

The application scans local drives for movie and TV show files, analyzes their technical metadata using FFprobe, identifies media using The Movie Database (TMDB), and prepares an organized media library.

## Features

* Scan local directories for video files
* Analyze video and audio streams using FFprobe
* Parse movie and TV show information from filenames
* Identify movies and TV shows using TMDB
* Detect seasons and episodes
* Retrieve metadata such as titles, release years and genres
* Prepare normalized filenames and folder structures
* Local-first processing

## Project status

The project is currently under development.

At this stage, the application only scans and analyzes media files. File renaming, moving and copying will be added after the identification process has been tested.

## Technology

* Python
* FFprobe / FFmpeg
* SQLite
* TMDB API

## Privacy

Media files are processed locally. The application does not upload media files to TMDB. Only metadata required to identify movies and TV shows is sent to the TMDB API.

This project is intended for personal use.
