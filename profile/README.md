# Open Obsidian i18n

**Open Obsidian i18n (OO-i18n)** is a non-official, community-driven, and non-profit initiative dedicated to building sustainable internationalization (i18n) infrastructure for the Obsidian third-party ecosystem, including plugins, themes, and other configurable extensions.

Our mission:

> Make language no longer a barrier to using Obsidian and its ecosystem.

---

## What We Build

### i18n-plus — Framework and Obsidian Plugin

**i18n-plus** serves two roles:

#### As a Developer Framework

For third-party developers, i18n-plus provides a lightweight, embeddable i18n layer that enables:

- Complete decoupling of code/configuration and translation
- Minimal integration effort (small adapter + source dictionary)
- Releases independent of translation completion
- Community-driven, continuously evolving localization

Developers only need to provide the source dictionary; the rest can be handled by the community.

#### As an End-User Plugin

For users, i18n-plus offers:

- Visual identification of third-party plugins, themes, and other configurable extensions adapted to i18n-plus
- In-app bridging between extensions and dictionaries
- Dynamic loading and unloading of dictionaries without restart
- Built-in local dictionary editor for personalized translations
- Pre-designed interfaces for future cloud dictionary integration

i18n-plus has been validated in real-world usage with Blur Mode and Better Plugins Manager.

---

## Community Cloud Dictionary (In Progress)

We are building an open, reusable, and evolving community dictionary system to:

- Unify key terminology across the Obsidian ecosystem
- Allow translations to evolve independently from extension versions
- Support collaborative workflows (Crowdin + GitHub)
- Enable one-click dictionary updates inside i18n-plus

The technical interfaces are ready; the dictionary infrastructure is under active development.

---

## Why Open Obsidian i18n

Traditional i18n approaches face three major issues:

1. Translation blocks releases
2. Translations are subjective and hard to update
3. Poor iteration due to tight coupling with extension versions

i18n-plus solves these issues with dynamic dictionaries and community-driven translation, making localization faster, more flexible, and sustainable.

---

## Community Background

After the official Obsidian team declined to host an i18n plugin, the community self-organized and:

- Maintained an independent i18n ecosystem
- Localized hundreds of plugins and themes
- Built a community of nearly 1,000 members

Many potential users are stopped not by features but by language, which motivates our work.

---

## How to Get Involved

**Developers of Plugins, Themes, and Configurable Extensions**

- Integrate the i18n-plus adapter into your project
- Provide a source dictionary to the community repository

**Translators**

- Contribute via Crowdin (coming soon)
- Improve terminology consistency across extensions

**Users**

- Install i18n-plus
- Use and customize cloud/local dictionaries
- Report issues and suggestions on GitHub

---

## Links

- i18n-plus (Plugin & Framework): https://github.com/open-obsidian-i18n/i18n-plus
- Dictionaries (In Progress): https://github.com/open-obsidian-i18n/dictionaries
- Community Discussions: https://github.com/open-obsidian-i18n/community  
---

## License

This project is open under MIT + CC BY 4.0. You are free to reuse, fork, and reference this work.
