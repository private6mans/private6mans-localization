# Private6Mans Localization
Public translation files for the [Private 6 Mans](https://beta.private6mans.xyz/discord) discord bot.

## Community Contributions
 - English - [Coolcal](https://github.com/coolcalcacol) [Coolcal#8459]
 - Spanish - [Blacki](https://github.com/Blacker2911) [Blacki#6844]

## Contributing your translations
1. Fork this repository
2. Create a new file named as the two-letter country code you are translating for. (e.g. "en" for english, "de" for german) in the `/resources/translations` folder.
3. Translate each of the entries in `en.json` to your translation language. See [Basic Instructions](#basic-instructions) for more details on translation.
5. Submit a PR for review.

## Basic Instructions
* When translating messages please maintain basic formatting and leave variables for injection in place (`{{key}}`).
* Some special formatting such as `**BoldText**`, or `_ItalicText_` may exist in text and is markdown formatting for discord, please translate phrases inside the formatting as if they are independent of the rest of the message.
* Ensure that each line ends with a comma `,` outside of the closing quotes for the translated string.
* Ensure that no extra whitespace exists at the end of the line.

### Definitions
* Guild - This is a discord server, and can be translated as such.
* Room - This is a discord channel, also equivalent to a queue in most cases with respect to this bot.
* REST/WS - These are acronyms related to web developement, when fully capitalized they don't need to be translated.
  * REST = **RE**presational **S**tate **T**ransfer
  * WS = **W**eb **S**ocket(s)

## Need help?
### If you need help with translating, or have any questions feel free to reach out in our **[support discord](https://beta.private6mans.xyz/discord)**!
