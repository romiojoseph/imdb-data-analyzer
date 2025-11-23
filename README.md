# IMDb Data Analyzer

### Better view on desktop

When you visit this website, you'll see dummy data pre-loaded. To view the correct data, upload your own exported CSV file. I've tested this thoroughly. Still if you notice any inconsistencies, [please feel free to let me know](https://tally.so/r/3jorya). Also if you like, join [Movies & TV Shows](https://bsky.app/profile/did:plc:xglrcj6gmrpktysohindaqhj/feed/MoviesTVShows) Bluesky feed. I will create a standalone feed for public use at a later stage and share it here.

### To download your CSV

Sign in to IMDb, click your profile in the top right corner, and choose either “Your watchlist” or “Your ratings”. On the next page, click the export button. Your download link will be generated shortly and can be accessed at [https://www.imdb.com/exports/](https://www.imdb.com/exports/).

### Things to note

I excluded the TV Episode count from most charts, keeping it only in the Runtime and Daily Rating Activity charts, since it is not particularly significant for a general analytical overview. All other content types remain included. Sometimes the 10 point or even 5 point scale can be a bit confusing, so I use the following conversion system: **Boring (1-3), Average (4-6), Good (7-9), or Masterpiece (10)**.

### Transparency notice

This platform is designed to help you analyze your personal movie/show/content watching experience. All selected files are processed and analyzed locally on your device. I'm also creating a completly open source version of a movie library platform that you can use locally to manage your movies, TV series, and mini-series. If you want a repository access, [please send me a message](https://tally.so/r/3jorya).

### Version 2.0

This is the second version of the project. The earlier version was built with plain HTML, CSS, and JavaScript, but this one uses Next.js and includes two additional charts, a browsing page, and several logic fixes. It now supports both watchlist and ratings CSV exports. Previously, it only worked with watchlist CSV because I assumed most people relied on a single list and because IMDb's handling of these lists was fairly confusing at the time. You can now analyse both, as their table structures are largely similar. This will remain stable unless IMDb makes internal changes to its export format.

### Why created this project?

Most people do not bother tracking everything they watch, but I make it a habit and enjoy analytical data because it offers clear, evidence based insights. Over time, we naturally forget our favourite movies and shows, which makes keeping a record even more meaningful. I also noticed that some people track everything they watch, and many of them use Letterboxd. I wanted to support that as well, but their export provides very limited data.

### Credits

Javascript created with Google AI and Claude. Chart library by [Nivo](https://nivo.rocks/).


[Share on Bluesky](https://bsky.app/intent/compose?text=https://romiojoseph.github.io/imdb-data-analyzer/)
