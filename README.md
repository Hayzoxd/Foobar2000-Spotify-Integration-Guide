# Spotify Integration Guide for foobar2000

## Overview:
This guide will walk you through the process of integrating Spotify with foobar2000, allowing you to seamlessly listen to your favorite Spotify music within the foobar2000 music player.

## Instructions:

1. **Download and Install foobar2000**
   Visit the official foobar2000 website at [https://www.foobar2000.org/download](https://www.foobar2000.org/download) to download the latest version of foobar2000. After downloading, run the installation process.

2. **Install the Spotify Component**
   In foobar2000, navigate to "Preferences" and select "Components." Click on the "Install..." button, then choose the [foo_input_spotify-v006.zip](https://github.com/FauxFaux/foo_input_spotify/wiki) file. Once installed, restart foobar2000.

3. **Download and Run SpotifyToFoobarV2**
   Get the SpotifyToFoobarV2 application from [https://github.com/paulb39/SpotifyToFoobar](https://github.com/paulb39/SpotifyToFoobar) and run the executable file (SpotifyToFoobarV2\Debug\SpotifyToFoobar.exe). You'll be prompted to enter your playlist ID.

   - *Note: If your playlist URL is: https://open.spotify.com/playlist/5ywHRayFSikBVRSKDizdPD?si=TkH5LpJrREuenIarFYyIkw, use only the alphanumeric code after the last slash (5ywHRayFSikBVRSKDizdPD) as your playlist ID.*

4. **Integrate Spotify Playlist**
   Locate the generated file named SpotifyPlaylist.m3u (SpotifyToFoobarV2\Debug\SpotifyPlaylist.m3u) and simply drag it into the foobar2000 interface to integrate your Spotify playlist.
