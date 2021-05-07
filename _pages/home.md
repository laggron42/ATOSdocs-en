---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.3
  overlay_image: /assets/images/homepage.png
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/install-red/"
excerpt: >
  A Discord bot for organizing your Challonge tournaments directly on Discord!
row1:
  - image_path: /assets/images/mm-free-feature.png
    alt: "organisation management"
    title: "Organisation and management"
    excerpt: "Powerful tools available for managing a whole tournament easily, tested with up to 128 players"
  - image_path: /assets/images/mm-responsive-feature.png
    alt: "discord integration"
    title: "Discord integration"
    excerpt: "No one needs to create a Challonge tournament, everything is linked between the bracket and your server!"
  - image_path: /assets/images/mm-customizable-feature.png
    alt: "automatisation"
    title: "Great automatisation"
    excerpt: "The bot automates almost everything for the organizers, the only thing left to do is to monitor!"

row2:
  - image_path: /assets/images/mm-free-feature.png
    alt: "Automatic channels"
    title: "Automatic channels"
    excerpt: >
      Private channels are created automatically for each match, bringing both players together who can discuss peacefully. <br/>
      They have tools available for their game, like displaying rules, stages, or even calling an organiser <br/><br/>
      The organisers, on the other hand, have an overview of all the channels and can easily intervene in a match without disturbing the rest!

row3:
  - image_path: /assets/images/mm-free-feature.png
    alt: "Integrated registrations and check-in"
    title: "Integrated registrations and check-in"
    excerpt: >
      The bot includes a registrations and check-in system. After an easy setup, members will just have to type `!in` to participate!<br/><br/>
      The available options adapt to small tournaments as well as major tournaments, built to work with large influxes of members quickly!

row4:
  - alt: "100% free"
    title: "100% free"
    excerpt: "You're free to invite the bot, and even install and host it, no command will be blocked, no message will insist over a Patreon!"

row5:
  - image_path: https://imgur.com/pY1WUFX.png
    alt: "powered by Red"
    title: "Powered by Red-DiscordBot"
    excerpt: >
      A.T.O.S. is an instance of Red-DiscordBot, a self-hosted open-source bot. <br/>
      The functions around tournaments are just a module, part of my collection of modules, <a
      href="https://github.com/retke/Laggrons-Dumb-Cogs">Laggron's Dumb Cogs</a>.
    url: "/what-is-red/"
    btn_label: "More info"
    btn_class: "btn--danger"

---

{% include feature_row id="row1" %}

{% include feature_row id="row2" type="left" %}

{% include feature_row id="row3" type="right" %}

{% include feature_row id="row4" type="center" %}

{% include feature_row id="row5" type="right" %}
