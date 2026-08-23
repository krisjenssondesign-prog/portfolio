# krisjensson.com

The live site. Static — no build, no dependencies.

    index.html
    media/     video, posters, artwork
    fonts/     Inter only

This folder is generated. The source lives one level up in `site/`; run
`make-live.py` to rebuild, or `./publish.sh "what changed"` to rebuild,
commit and push in one go.

Inter is OFL. The working build uses Saans, which is trial-licensed and is
deliberately not in this repo.
