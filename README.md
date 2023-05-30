# Crawl Movie Data in Obsidian

This plugin is a simple plugin that allows you to crawl movie data from [omdb](https://www.omdbapi.com/) and Youtube trailers.

![Screencast-from-2023-05-30-16-36-23](https://github.com/onuraycicek/obsidian-movie/assets/87834696/c66504b0-e85a-48e6-a38a-b694dfa68962)

## Usage

1. You need to get an API key from [omdb](https://www.omdbapi.com/apikey.aspx) and set it in the plugin settings.
2. (optional) You need to get an API key from [Youtube](https://console.cloud.google.com/apis/credentials) and set it in the plugin settings. This is required to get the trailers. If you don't set it, you will not be able to get the trailers. If you can't get the API key from Youtube, you can visit [here](https://developers.google.com/youtube/v3/getting-started) to get more information.
3. You must have a folder named `movies` in your vault. You can change this folder name in the plugin settings (Main Path).
4. You must have a folder named `assets` in your vault. You can change this folder name in the plugin settings (Image Path).
5. That's it! You can use the command palette to search for movies. You can also use the hotkey `Ctrl+Alt+M` or you can click the movie icon in the ribbon.
