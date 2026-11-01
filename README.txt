GROTTO RADIO — FIRST WORKING BUILD

Files:
- index.html: standalone radio/player and catalogue
- assets/: six aligned transparent PNG layers from the supplied radio artwork

To preview:
Open index.html in a modern browser. Internet access is required for the Cloudinary audio files and Blogger artwork.

Included:
- 45 workbook entries with their embedded MP3, artwork and GremTV hyperlinks
- Europe/Dublin date unlocking
- future catalogue entries displayed in grayscale and disabled
- clean-only default
- explicit toggle with pause-and-confirm skip prompt when an explicit track is playing
- one shuffle entry per underlying song identity
- explicit-enabled 80/20 preference (explicit/clean) when both types exist
- four-song cooldown by underlying song identity
- previous, play, pause, next and repeat-current controls
- GremTV and Spotify badge links

Important implementation notes:
- This is a front-end Blogger-ready prototype, not secure media protection. MP3 URLs are present in page source, so a determined visitor can access a future track's URL before its date.
- The spreadsheet has 45 rows. The explicit flag is inferred from the track title/audio URL containing "explicit".
- Alternate versions grouped together in this build: More Than the Present, Snowflake Stack, I Like You More Than Bacon, Nuts to Resolutions, and Gremlin Take Down the Tree.
- One workbook row, "It's Alright", appears to point to the same Cloudinary MP3 as "Hosting (Holiday Spirit(tm))". Please verify that link before launch.
- The Gremlin Gambit Theme Songs artwork cell links to a GremTV page rather than an image. It currently displays a plain placeholder in the catalogue.
- The radio uses the six individual aligned artwork layers; the assembled branded image is retained separately as a reference and is not needed by the page.
