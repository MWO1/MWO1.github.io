# Hushwater website (https://hushwatergame.com)

Source lives in the private game repo (`site/`); it is published to the public repo `MWO1/MWO1.github.io`
with `bash tools/site/publish.sh`. Pages: home, privacy, terms, support (built from game/data/help.json by
`node tools/site/make_support.mjs`), `app-ads.txt` (AdMob), `config/remote.json` (remote config for the game;
`{}` = no changes; format in game/scripts/services/remote_config.gd).
