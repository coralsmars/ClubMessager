# ClubMananger

[Telegram](https://telegram.org) is a messaging app with a focus on speed and security. It’s superfast, simple and free.

ClubsMananger is an UNOFFICIAL app that uses Telegram's API.

Google play store: https://play.google.com/store/apps/details?id=io.iclubs.chat&showAllReviews=true&umt=github

Update news: https://t.me/clubsmessagernews

Chat group (Chinese & English): Join our channel (https://t.me/clubmessager) and click "Chat"

## API, Protocol documentation

Telegram API manuals: https://core.telegram.org/api

MTproto protocol manuals: https://core.telegram.org/mtproto

## Compilation Guide

**Note**: In order to support [reproducible builds](https://core.telegram.org/reproducible-builds), this repo contains dummy release.keystore,  google-services.json and filled variables inside BuildVars.java. Before publishing your own APKs please make sure to replace all these files with your own.

You will require Android Studio 4.1.3, Android NDK rev. 20 and Android SDK 8.1

1. Download the ClubsMananger source code from https://github.com/coralsmars/ClubMessager ( git clone https://github.com/coralsmars/ClubMessager.git )
2. Copy your release.keystore into TMessagesProj/config
3. Fill out RELEASE_KEY_PASSWORD, RELEASE_KEY_ALIAS, RELEASE_STORE_PASSWORD in local.properties to access your  release.keystore
4. Open the project in the Studio (note that it should be opened, NOT imported).
5. If you're compiling DEBUG version, make sure your build variants is set to afatDebugMultidex.
6. You are ready to compile ClubMessager.

## Localization

ClubsMananger is forked from Telegram, thus most locales follows the translations of ClubsMananger for Android, checkout https://translations.telegram.org/en/android/.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
| :---: | :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

