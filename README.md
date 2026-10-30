# Darza's Dominion translations

This repository holds the text of [Darza's Dominion](https://store.steampowered.com/app/1895130/Darzas_Dominion/) in English and in every language players are translating it into.

**To help, translate on the wiki at [darzawiki.com/translate](https://darzawiki.com/translate).** Sign in with Discord and pick your language. You can then suggest a translation for any message or vote for someone else's suggestion. Approved translations go into the game with its next update, and everyone who has one approved is listed in [CREDITS.md](CREDITS.md).

## What's in this repository

| File | What it is |
|---|---|
| `locales/darza.pot` | All of the game's text in English. It's generated from the game's code and replaced whenever the text changes, so please don't edit it. |
| `locales/<code>.po` | The translations, with one file for each language (for example `fr.po` or `pt_BR.po`). The wiki keeps these files up to date, and approved translations appear here within ten minutes. |
| `CREDITS.md` | The list of translators. The wiki keeps this file up to date. |

## Languages

| Code | Language |
|---|---|
| `de` | Deutsch (German) |
| `es` | Español (Spanish) |
| `fr` | Français (French) |
| `it` | Italiano (Italian) |
| `pl` | Polski (Polish) |
| `pt_BR` | Português brasileiro (Brazilian Portuguese) |
| `ru` | Русский (Russian) |
| `ja` | 日本語 (Japanese) |
| `ko` | 한국어 (Korean) |
| `zh_Hans` | 简体中文 (Simplified Chinese) |
| `zh_Hant` | 繁體中文 (Traditional Chinese) |

## Translating offline

These are standard gettext `.po` files, so you can open them in a translation program like [Poedit](https://poedit.net). Download your language's file from the wiki or from this repository, translate it, and open a pull request with your changes. Once it's merged, the wiki picks up your translations and checks them the same way it checks suggestions.

The same rules apply wherever you translate. The wiki's [translation guide](https://darzawiki.com/translate/guide) has the full list.

- Keep placeholders like `{count}` exactly as written. You can move them anywhere in the sentence, but don't remove any or add new ones. There's one exception: a plural form that only covers a single number can spell it out. German's form for 1 can say "ein Geschenk", for example.
- Keep color and icon tags like `<c#ffff77>` ... `<c/>` and `<e:silver>` exactly as written, and don't add new ones.
- Keep `@h`, `@p` and `@m` in enemy lines. The game fills these in.
- Translate every plural form your language has.

If a translation breaks one of the first three rules, the game shows that message in English instead.

## Seeing your work

As you type on the wiki, the editor shows how your translation will look in the game.

## License

The game and its English text are © Ripple Studio LLC. Translations are submitted under the wiki's [contributor terms](https://darzawiki.com/translate/terms), which allow Ripple Studio to use, change and publish them in Darza's Dominion. This repository is public so players can read, discuss and improve the translations. That doesn't give anyone permission to use them elsewhere. See [LICENSE.md](LICENSE.md) for details.
