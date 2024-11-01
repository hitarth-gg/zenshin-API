# zenshin-API

The API response for an anime includes details of each episode, covering both main and special episodes available on AniDb. Each episode is mapped to its equivalent episode on Tvdb, along with IDs for various anime websites.
Data is typically updated every two days.

Currently 8200+ anime exist in the DB with 125426+ regular anime episodes in total.

### Example: Ao no hako / Blue Box
```
https://zenshin-supabase-api.onrender.com/mappings?mal_id=57181
https://zenshin-supabase-api.onrender.com/mappings?anilist_id=170942
https://zenshin-supabase-api.onrender.com/mappings?thetvdb_id=429934
https://zenshin-supabase-api.onrender.com/mappings?anidb_id=18278
```
**Response:**
```json
{
  "mainTitle": "Ao no Hako",
  "title": {
    "main": "Ao no Hako",
    "mainTitle": "Ao no Hako",
    "en": "Blue Box",
    "ja": "アオのハコ",
    "nl": "Blue Box",
    "es": "La caja azul",
    "cs": "Mládí na hřišti",
    "pl": "Niebieskie pudełko",
    "hr": "Plava kutija",
    "uk": "Блакитна скринька",
    "he": "האולם הכחול",
    "th": "กล่องรักวัยใส",
    "ar": "‎الصندوق الأزرق",
    "zh-Hans": "青春之箱",
    "ko": "푸른 상자"
  },
  "date": {
    "startDate": "2024-10-03",
    "endDate": null
  },
  "episodes": {
    "1": {
      "episode": "1",
      "anidbEid": "286674",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-10-03",
      "title": {
        "en": "Chinatsu Senpai"
      },
      "nameTvdb": "Chinatsu Senpai",
      "tvdbShowId": 429934,
      "tvdbId": 10152847,
      "seasonNumber": 1,
      "episodeNumber": 1,
      "absoluteEpisodeNumber": 1,
      "runtime": 24,
      "overview": "Despite a few heart-fluttering encounters, Taiki doubts his crush Chinatsu even knows his name. Later, shocking news forces him to make a bold move.",
      "image": "https://artworks.thetvdb.com/banners/v4/episode/10152847/screencap/66fa42e94a3bd.jpg",
      "airDate": "2024-09-27"
    },
    "2": {
      "episode": "2",
      "anidbEid": "286675",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-10-04",
      "title": {
        "en": "You Have to Go to Nationals"
      },
      "nameTvdb": "You Have to Go to Nationals",
      "tvdbShowId": 429934,
      "tvdbId": 10691954,
      "seasonNumber": 1,
      "episodeNumber": 2,
      "absoluteEpisodeNumber": 2,
      "runtime": 24,
      "overview": "Taiki's new housemate quickly makes herself at home. As they grow closer, his attempts to keep the situation a secret cause a misunderstanding.",
      "image": "https://artworks.thetvdb.com/banners/v4/episode/10691954/screencap/6704e1f39de6e.jpg",
      "airDate": "2024-10-04"
    },
    "3": {
      "episode": "3",
      "anidbEid": "286676",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-10-11",
      "title": {
        "en": "Chii"
      },
      "nameTvdb": "Chii",
      "tvdbShowId": 429934,
      "tvdbId": 10691955,
      "seasonNumber": 1,
      "episodeNumber": 3,
      "absoluteEpisodeNumber": 3,
      "runtime": 24,
      "overview": "Taiki overhears Haryu calling Chinatsu by a special nickname and gets flustered. Will it affect his upcoming match against the upperclassman?",
      "image": "https://artworks.thetvdb.com/banners/v4/episode/10691955/screencap/670d0e5b03e4e.jpg",
      "airDate": "2024-10-11"
    },
    "4": {
      "episode": "4",
      "anidbEid": "286677",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-10-18",
      "title": {
        "en": "If He Wins"
      },
      "nameTvdb": "If He Wins",
      "tvdbShowId": 429934,
      "tvdbId": 10691956,
      "seasonNumber": 1,
      "episodeNumber": 4,
      "absoluteEpisodeNumber": 4,
      "runtime": 24,
      "overview": "A gym uniform mix-up leads to a heart-pounding exchange. Later, Haryu raises the stakes for Taiki’s match, while Kyo makes a secret request to Chinatsu.",
      "image": "https://artworks.thetvdb.com/banners/v4/episode/10691956/screencap/67163583f0430.jpg",
      "airDate": "2024-10-18"
    },
    "5": {
      "episode": "5",
      "anidbEid": "287391",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-10-25",
      "title": {
        "en": "Aquarium"
      },
      "nameTvdb": "Aquarium",
      "tvdbShowId": 429934,
      "tvdbId": 10691957,
      "seasonNumber": 1,
      "episodeNumber": 5,
      "absoluteEpisodeNumber": 5,
      "runtime": 24,
      "overview": "With both players going neck and neck on the court, will Taiki win his match against Kishi — and will Chinatsu invite him to the aquarium?",
      "image": "https://artworks.thetvdb.com/banners/v4/episode/10691957/screencap/671f91a40d380.jpg",
      "airDate": "2024-10-25"
    },
    "6": {
      "episode": "6",
      "anidbEid": "287392",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-11-01",
      "title": {
        "en": "Wish Me Luck"
      },
      "nameTvdb": "Wish Me Luck",
      "tvdbShowId": 429934,
      "tvdbId": 10691958,
      "seasonNumber": 1,
      "episodeNumber": 6,
      "absoluteEpisodeNumber": 6,
      "runtime": 24,
      "overview": "On her way to return Chinatsu's mobile phone, Hina makes a shocking discovery. The gymnast faces mounting pressure while struggling with her new feelings.",
      "image": null,
      "airDate": "2024-11-01"
    },
    "7": {
      "episode": "7",
      "anidbEid": "287393",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-11-08",
      "title": {
        "en": "Episode 7"
      },
      "nameTvdb": null,
      "tvdbShowId": 429934,
      "tvdbId": 10691959,
      "seasonNumber": 1,
      "episodeNumber": 7,
      "absoluteEpisodeNumber": 7,
      "runtime": 24,
      "overview": null,
      "image": null,
      "airDate": "2024-11-15"
    },
    "8": {
      "episode": "8",
      "anidbEid": "287394",
      "type": "Regular Episode",
      "length": "25m",
      "airdate": "2024-11-15",
      "title": {
        "en": "Episode 8"
      },
      "nameTvdb": null,
      "tvdbShowId": 429934,
      "tvdbId": 10691960,
      "seasonNumber": 1,
      "episodeNumber": 8,
      "absoluteEpisodeNumber": 8,
      "runtime": 24,
      "overview": null,
      "image": null,
      "airDate": "2024-11-22"
    },
    "OP1": {
      "episode": "OP1",
      "anidbEid": "287113",
      "type": "Opening/Ending",
      "length": "2m",
      "airdate": "2024-10-03",
      "title": {
        "en": "Same Blue (1)"
      }
    }
  },
  "mappings": {
    "livechart_id": 11380,
    "thetvdb_id": 429934,
    "anime-planet_id": "blue-box",
    "imdb_id": "tt32639706",
    "anisearch_id": 18873,
    "themoviedb_id": 207347,
    "anidb_id": 18278,
    "kitsu_id": 48239,
    "mal_id": 57181,
    "type": "TV",
    "notify.moe_id": "zuBXTpDSR",
    "anilist_id": 170942
  }
}
```
