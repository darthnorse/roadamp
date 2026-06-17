# Roadamp Privacy Policy

**Last updated: June 2, 2026**

## Overview

Roadamp is a music player for Android Automotive that connects to your own personal media server. It supports Plex, Emby, and Jellyfin servers. The app is designed to respect your privacy and operates with minimal data access.

## Data Collection

Roadamp does **not** collect, store, or transmit any personal data to the developer or any third party.

## Data Stored on Your Device

The app stores the following data locally on your device:

- **Authentication credentials** — the access token used to authenticate with your media server, stored in encrypted storage. For Plex this is the Plex token obtained via plex.tv sign-in; for Emby and Jellyfin this is the access token returned by your server after sign-in.
- **Server connection details** — the address (URL) of your selected server and the active server type.
- **App preferences** — your display, library selection, and playback settings.

This data never leaves your device except to communicate directly with your own media server (and, for Plex, with Plex's authentication services at plex.tv).

## Network Communication

The app communicates only with:

- **plex.tv** — only when using Plex, for initial sign-in and server discovery.
- **Your media server** — the Plex, Emby, or Jellyfin server you configure, to sign in, browse your library, load artwork, and stream music.

When you sign in to an Emby or Jellyfin server, the username and password you enter are sent directly to the server address you provide in order to obtain an access token. They are not sent anywhere else.

No data is sent to the developer or any analytics, advertising, or tracking services.

## Third-Party Services

Roadamp does not integrate any third-party analytics, crash reporting, advertising, or tracking SDKs.

## Children's Privacy

Roadamp is not directed at children under 13 and does not knowingly collect information from children.

## Changes to This Policy

If this policy is updated, the revised version will be posted here with an updated date.

## Contact

If you have questions about this privacy policy, please open an issue at the project's repository.
