+++
title = "Portfolio"
+++

*Deze pagina toont een aantal van mijn projecten waar ik trots op ben en graag laat zien. Voor meer van mijn
(voornamelijk onopvallende) projecten, bekijk mijn [GitHub-profiel](https://github.com/vijfhoek) of mijn
[zelf-gehoste Forgejo-instantie](https://git.sijman.nl/_).*

# Empede
[Empede](https://github.com/vijfhoek/empede) is een webclient voor MPD (Music Player Daemon). Het is
geschreven in Rust, HTML, CSS en JavaScript, waarbij actix-web wordt gebruikt voor de backend,
askama voor template rendering, en htmx als frontend-framework.

De client nadert de functionaliteit van andere populaire MPD-webclients, zoals phpMp.

![Screenshot](https://github.com/vijfhoek/empede/raw/main/screenshots/screenshot.webp)

# reegee-X
[reegee-X](https://github.com/vijfhoek/regexbot) ([@regexbot](https://t.me/regexbot)) is een
eenvoudige Telegram-bot waarmee gebruikers het Perl-achtige <code>s/a/b/</code>-patroon kunnen gebruiken om hun eigen (of andermans) fouten te corrigeren.

De bot is geschreven in Python, oorspronkelijk met behulp van de aiotg-bibliotheek, maar sindsdien herschreven naar
het veel betrouwbaardere Telethon door bijdragers (shoutout naar Lonami).

<img src="/images/regexbot.png" style="max-width: 500px">

# telematrix
[telematrix](https://github.com/vijfhoek/telematrix) was mijn oorspronkelijke poging in 2016 om een
brugbot te schrijven tussen Telegram en Matrix.

Hoewel telematrix niet veel meer was dan een prototype, trok het de aandacht omdat het de eerste
Telegram-Matrix brugbot was die *enigszins* bruikbaar was en vrij eenvoudig in te stellen --- tot het
punt dat het ooit werd getoond op het FOSDEM-podium door Matthew Hodgson, de technisch medeoprichter
van Matrix.