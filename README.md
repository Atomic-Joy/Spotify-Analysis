<div style="font-family: 'Times New Roman'; font-weight: bold; font-size: 30px;">Spotify-Analysis</div>
<div style="font-family: 'Times New Roman'; font-size: 18px;">
This project is a data analysis of a Spotify user's listening habits.

It uses the Spotify API to retrieve the user's top 50 tracks and top 10 artists over a "medium\_term" (last 6 months) and provides several analyses:

* ****Top Tracks and Artists:**** Lists the user's top 50 tracks.
* ****Popularity and Genres:**** Visualizes the popularity of top artists and the genre distribution among them.
* ****Album Trends:**** Provides a timeline of album release dates and a histogram of the total tracks per album for the user's top songs.
* ****Explicit Content:**** Analyzes the proportion of explicit tracks in the top songs (e.g., 46.0% were explicit in one run) and identifies which genres have the highest explicit content percentage.
</div>

Spotify API uses three main time ranges to query a user's top listening data:

| Parameter | Time Span Covered | Description / Use Case |
| :---: | :---: | :---: |
| `short_term` | Last 4 weeks (~1 month) | User's top tracks/artists from the past month. |
| `medium_term` | Last 6 months (~6 months) | User's top tracks/artists from the past half-year. |
| `long_term` | Several years (~years/all) | User's top tracks/artists over several years (Spotify account history). |
