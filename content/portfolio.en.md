+++
title = "Portfolio"
+++

*This page shows off a couple of my projects I'm proud of and like to show off. For more of my
(mostly unremarkable) projects, see my [GitHub profile](https://github.com/vijfhoek) or my
[self-hosted Forgejo instance](https://git.sijman.nl/_).*

# Empede
[Empede](https://github.com/vijfhoek/empede) is a web client for MPD (Music Player Daemon). It was
written in Rust, HTML, CSS and JavaScript, using actix-web for the back-end, askama for template
rendering and the htmx front-end framework.

The client is approaching feature parity with other MPD web clients, such as phpMp.

![Screenshot](https://github.com/vijfhoek/empede/raw/main/screenshots/screenshot.webp)

# reegee-X
[reegee-X](https://github.com/vijfhoek/regexbot) ([@regexbot](https://t.me/regexbot)) is a
simple Telegram bot, allowing chatters to use the Perl-style <code>s/a/b/</code> pattern to correct
their own (or others') mistakes.

The bot was written using Python, originally using the aiotg library, but since then rewritten to
the much more reliable Telethon by contributors (shoutout to Lonami).

<img src="/images/regexbot.png" style="max-width: 500px">

# telematrix
[telematrix](https://github.com/vijfhoek/telematrix) was my original attempt in 2016 to write a
bridge bot between Telegram and Matrix.

While telematrix was not much more than a prototype, it gained attention for being the first
Telegram-Matrix bridge bot that was *somewhat* usable, and rather easy to set up --- to the
point of once being shown off on-stage by Matthew Hodgson, the technical co-founder of Matrix,
during FOSDEM.