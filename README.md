# Crawl Movie Database in Obsidian
This plugin is a simple plugin that allows you to crawl movie data from [omdb](https://www.omdbapi.com/) and Youtube trailers.
The newly added page is opened for you to add your notes or rating if required.

## Usage
1. You need to get an API key from [omdb](https://www.omdbapi.com/apikey.aspx) and set it in the plugin settings.
2. (optional) You need to get an API key from [Youtube](https://console.cloud.google.com/apis/credentials) and set it in the plugin settings. This is required to get the trailers. If you don't set it, you will not be able to get the trailers. If you can't get the API key from Youtube, you can visit [here](https://developers.google.com/youtube/v3/getting-started) to get more information.
3. Check the settings have the proper folders set up.
4. That's it! You can use the command palette to search for movies. You can also use the hotkey `Ctrl+Alt+M` or you can click the movie icon in the ribbon.


## Search Text Options
1. You can search by Title
2. Optionally, you can search by [IMDB title ID](https://developer.imdb.com/documentation/key-concepts#imdb-ids), eg. `tt13444014`
3. Optionally, in search by title, you can specify Year within parenthesis, eg. `Movie Name (2023)`

## Credits
Most of this work is borrowed from [onuraycicek/obsidian-movie](https://github.com/onuraycicek/obsidian-movie). This just builds upon this work.