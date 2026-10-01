# Full-Stack Projects

Three small full-stack apps built with Node.js, Express and SQLite, with plain HTML, CSS and JavaScript frontends.

| Folder | Project | Highlights |
|---|---|---|
| `01-ecommerce-store` | Leafy, a houseplant shop | Product pages, cart, login, server-checked orders |
| `02-social-media-app` | Hum, a mini social network | Profiles, posts, comments, likes, follows |
| `04-video-conferencing` | Meetly, video meetings | WebRTC calls, screen share, files, whiteboard, E2E-encrypted chat |

## Run any project
    cd 01-ecommerce-store      # or 02-social-media-app, 04-video-conferencing
    npm install
    npm start                  # http://localhost:3000

Each app uses port 3000, so run one at a time or set `PORT` for `04-video-conferencing`.
Set a `JWT_SECRET` environment variable before deploying anything. Each project's README has details.
