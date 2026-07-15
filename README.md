# mimir-plugin-registry

Registry of source plugins available to Mimir. See `registry.json` for the machine-readable manifest each plugin entry is sourced from.

## Plugins

- [Media Player Now Playing](https://github.com/ryanlane/mimir-source-mediaplayer) — Displays the poster of the currently playing video from Plex, Jellyfin, or Emby. Fires real-time push events so it can act as a now-playing interrupt source on any scene.
- [Slow Movie Player](https://github.com/ryanlane/mimir-slow-movie) — Plays video files one frame at a time at ultra-slow speeds, inspired by the Very Slow Movie Player concept. Supports quiet hours, per-movie timing, and random playback.
- [Photo Frame](https://github.com/ryanlane/image-frame-channel-mimir) — Gallery-based photo slideshow with intelligent image management. Supports multiple galleries, smart crop modes, and custom ordering.
- [Movie Posters](https://github.com/ryanlane/mimir-source-movie-posters) — Displays random movie poster art from The Movie Database (TMDB). Supports genre sub-channels (Action, Horror, Sci-Fi…) and curated lists (Popular, Top Rated). Requires a free TMDB API key.
- [Comic Covers](https://github.com/ryanlane/mimir-source-comic-covers) — Displays random comic book and graphic novel covers from the Open Library archive. Supports subjects (graphic_novels, manga, etc.) and publisher facets (Marvel Comics, DC Comics, Image Comics) as sub-channels.
- [Weather Display](https://github.com/ryanlane/mimir-source-weather) — Renders live weather conditions and forecasts as full-resolution images using OpenWeatherMap. Each configured city is an independent sub-channel; supports landscape, portrait, and square display layouts with dark/light themes. Requires a free OWM API key.
- [Spotify Now Playing](https://github.com/ryanlane/spotify-status) — Displays the currently playing Spotify track with album art and metadata. Supports push updates for instant display refresh when tracks change.
- [Met Museum Art](https://github.com/ryanlane/mimir-source-metart) — Displays artworks from The Metropolitan Museum of Art's open collection. Browse by department, keyword search, or highlights gallery — no API key required. Supports multiple user-defined galleries as sub-channels.
- [Headlines](https://github.com/ryanlane/mimir-source-headlines) — Displays live news headlines from NewsAPI as full-resolution images. Each configured feed targets a category (Business, Tech, Sports…) or keyword search, rendered in a newspaper-style layout across landscape, portrait, and square displays. Supports dark, light, and high-contrast e-ink themes. Requires a free NewsAPI key.
- [Last.fm Now Playing](https://github.com/ryanlane/mimir-source-lastfm) — Displays your currently scrobbling track from Last.fm with album art. Works with Apple Music, Spotify, or any Last.fm-connected player. Requires a free Last.fm API key.
- [Generative Art](https://github.com/ryanlane/mimir-source-genart) — Gallery-grade algorithmic art rendered locally — no external APIs. Two print styles (Bauhaus × Wabi-Sabi giclée, 1960s constructivist risograph) across six composition algorithms, with static PNG for e-ink and seamless animated WebP loops for LCD/OLED displays.
