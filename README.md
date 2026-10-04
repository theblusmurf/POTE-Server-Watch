# POTE Server Watch

Android server-status notifier. [Download the latest APK](https://github.com/theblusmurf/POTE-Server-Watch/releases/latest). Android 8.0 or newer. No account or pairing key is required from version 1.3. Open the app and enable live alerts. Only possible server outages trigger alerts; recovery stays quiet. Updates download automatically and require Android installation approval.

## Public status feed

[Latest signed messages](https://ntfy.sh/pote-server-watch-theblusmurf/json?poll=1). Messages contain only reachability, UTC check times, generic outage notices and delivery identifiers. Anyone may read the feed. The APK verifies RSA/SHA-256 signatures using an embedded public verification key; only the PC retains the private signing key. The release asset public-feed.json describes the format. Subscribe through the POTE Server Watch APK to reject forged messages. Status is observed from one connection, not an independently confirmed global outage.

The monitoring PC and Codex must remain running. No game account details, character data, pairing secrets, signing secrets or raw logs are published. This repository distributes APKs and public metadata only.
