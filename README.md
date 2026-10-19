# MoFlex Admin

Turn episodes and trailers on and off for the MoFlex site. It covers every show:
Tales Of The Legend and A Fix In Time.

Open the page, enter your GitHub username, the MoFlex repository name, and an access token, then select Connect.
Each show has its own switches. Nothing changes on the site until you select Publish changes.

How the release list is stored in `availability.json`:

- `episodes` and `trailers` at the top are for Tales Of The Legend (the original format).
- `shows` holds the other shows, for example `"a-fix-in-time": { "episodes": [], "trailers": [] }`.
