# Spotify Playlist Maker
## A small React project that searches spotify and allows playlist creation

# Getting Started
1. Download the project and use a terminal to navigate to the /spotifyPlaylistMaker folder
2. type `npm install`
3. Open the folder in your preferred editor and navigate to src/util/apiKey.js
4. And inside the variable at the top of the file `const clientID = ' '` and inside the empty string enter your spotify developer client ID
5. In your terminal type `npm start` within the project folder. This will start the react local server and open your browser to localhost:3000
6. Play around with it!

# Expected Program flow
- Using the search bar will prompt a spotify authentication window
- Once authenticated using the search bar will show results on the left of the window
- Clicking the `+` key will add the song to an empty playlist (alternatively clicking the `-` will remove it)
- At this point you can click 'Save Playlist' and it will save, or you can click the playlist name to rename your playlist
- Playlist will save to your personal spotify account with the tracks you selected and the name you chose to give the playlist

# Current issues
1. The web app cannot be hosted due to a refresh error I'm trying to solve.
2. When the 'search' button is used it will fail initially, re-entering the search and clicking again will make it function.
- SOLVED: Clicking the search button fires off the authentication to spotify's server and will redirect the user to the authenticted page (currently the only page)

# Planned Updates
1. Filter support for results
2. Album/Artist images with results
3. 'Total Playtime' information on created playlist